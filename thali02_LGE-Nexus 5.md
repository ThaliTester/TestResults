#### Test 539786639813e59_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
I/GAv4    ( 3169): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3169):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3169):   adb logcat -s GAv4
W/GAv4    ( 3169): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3169): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3169): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 3169): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
D/ChimeraCfgMgr( 1625): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1625): Module APK com.google.android.play.games already loaded
D/Finsky  ( 2620): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
W/ResourcesManager( 3169): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3169): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/JNIHelp ( 3169): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/ActivityManager(  734): Killing 2592:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
W/System  ( 3169): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3169): Installed default security provider GmsCore_OpenSSL
W/libprocessgroup(  734): failed to open /acct/uid_10069/pid_2592/cgroup.procs: No such file or directory
V/GLSActivity( 1564): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 1625): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/Icing   ( 1625): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1625): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/Icing   ( 1625): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
,D/AndroidRuntime( 3233): 
D/AndroidRuntime( 3233): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3233): CheckJNI is OFF
D/AndroidRuntime( 3233): Calling main entry com.android.commands.am.Am
I/ActivityManager(  734): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  734): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3256 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3233): Shutting down VM
V/ActivityManager(  734): Display changed displayId=0
I/WebViewFactory( 3256): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3256): Time to load native libraries: 1 ms (timestamps 9156-9157)
I/LibraryLoader( 3256): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3256): Binding Chromium to main looper Looper (main, tid 1) {126fe7e1}
I/LibraryLoader( 3256): Expected native library version number "",actual native library version number ""
I/chromium( 3256): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3256): Initializing chromium process, singleProcess=true
W/art     ( 3256): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3256): ApplicationContext is null in ApplicationStatus
,W/chromium( 3256): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3256): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 3256): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3256): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  734): Message: 20
D/BluetoothManagerService(  734): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@30e39f15:true
,W/art     ( 3256): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3256): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3256): CordovaWebView is running on device made by: LGE
,W/art     ( 3256): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3256): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3256): Render dirty regions requested: true
,D/Atlas   ( 3256): Validating map...
,W/chromium( 3256): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3256): Initialized EGL, version 1.4
,I/ActivityManager(  734): Killing 2542:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,D/OpenGLRenderer( 3256): Enabling debug mode 0
,W/libprocessgroup(  734): failed to open /acct/uid_10045/pid_2542/cgroup.procs: No such file or directory
,I/ActivityManager(  734): Displayed com.test.thalitest/.MainActivity: +486ms (total +57s683ms)
,W/IInputConnectionWrapper( 3256): showStatusIcon on inactive InputConnection
,W/BindingManager( 3256): Cannot call determinedVisibility() - never saw a connection for the pid: 3256
,D/JsMessageQueue( 3256): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3256): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257342720
,D/JX-Cordova( 3256): jxcore cordova android initializing
,W/jxcore-log( 3256): Initializing JXcore engine
W/jxcore-log( 3256): JXcore engine is ready
,W/jxcore-log( 3256): Starting JXcore engine
,W/.test.thalitest( 3256): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[8047]" dev="sockfs" ino=8047 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3256): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 3256): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8504]" dev="sockfs" ino=8504 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3256): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[17254]" dev="sockfs" ino=17254 scontext=u:r:untrusted_app:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket
,W/jxcore-log( 3256): Platform android
W/jxcore-log( 3256): 
,W/jxcore-log( 3256): Process ARCH arm
W/jxcore-log( 3256): 
,I/jxcore-log( 3256): JXcore Cordova bridge is ready!
I/jxcore-log( 3256): 
W/jxcore-log( 3256): JXcore engine is started
,I/chromium( 3256): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3256): Toggling radios to true
I/jxcore-log( 3256): 
,D/BluetoothAdapter( 3256): enable(): BT is already enabled..!
,D/WifiService(  734): New client listening to asynchronous messages
,D/WifiService(  734): setWifiEnabled: true pid=3256, uid=10270
E/WifiService(  734): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3256): Radios toggled
I/jxcore-log( 3256): 
,I/wpa_supplicant(  993): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  734): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  734): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
E/native  (  734): do suspend true
D/CommandListener(  180): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1564): Read error: ssl=0xb4194e00: I/O error during system call, Connection timed out
,E/WifiConfigStore(  734): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  734): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  734): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,V/NativeCrypto( 1564): SSL shutdown failed: ssl=0xb4194e00: I/O error during system call, Broken pipe
,E/WifiStateMachine(  734): Start Disconnecting Watchdog 1
,I/wpa_supplicant(  993): wlan0: CTRL-EVENT-SCAN-STARTED 
,E/native  (  734): do suspend true
,D/ConnectivityService(  734): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): ValidatedState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): DefaultState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): Forcing reevaluation
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): Checking http://clients3.google.com/generate_204 on <unknown ssid>
,D/CommandListener(  180): Clearing all IP addresses on wlan0
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/ConnectivityService(  734): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/Nat464Xlat(  734): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  734): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityManager.CallbackHandler( 1625): CM callback handler got msg 524292
D/ConnectivityService(  734): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  734): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  734): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): Disconnected - quitting
D/ConnectivityManager.CallbackHandler(  916): CM callback handler got msg 524292
D/TelephonyNetworkFactory( 1268): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,W/ProcessCpuTracker(  734): Skipping unknown process pid 3337
,D/WifiNetworkAgent(  734): NetworkAgent: NetworkAgent channel lost
,W/NetworkUtils( 1410): OkHttp exception
W/EventLoggerService( 1410): Unable to send logs Error code: 262146
,I/wpa_supplicant(  993): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant(  993): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant(  993): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant(  993): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  734): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService(  734): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  734): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  734): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  180): Setting iface cfg
,E/WifiStateMachine(  734): Start Dhcp Watchdog 2
,E/native  (  734): do suspend false
,E/WifiStateMachine(  734): scanCount==0 - aborting
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 3256): Got Device Bluetooth address: 34:FC:EF:11:AE:67
I/jxcore-log( 3256): 
I/jxcore-log( 3256): my name is : LGE-Nexus 5_PT7166
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): attempting to connect to test coordinator
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): check test folder
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): found test : ./testFindPeers.js
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): found test : ./testReConnect.js
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): found test : ./testSendData.js
I/jxcore-log( 3256): 
,I/dhcpcd  ( 3361): version 5.5.6 starting
E/dhcpcd  ( 3361): get_duid: Read-only file system
,I/jxcore-log( 3256): Test app app.js loaded
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3256): 
,I/chromium( 3256): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/dhcpcd  ( 3361): wlan0: rebinding lease of 192.168.1.114
,I/jxcore-log( 3256): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3256): 
,I/dhcpcd  ( 3361): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3361): wlan0: leased 192.168.1.114 for 86400 seconds
,D/ConnectivityService(  734): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  734): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  734): MasterInitialState.processMessage what=3
D/Tethering(  734): MasterInitialState.processMessage what=3
,V/MusicLeanback( 2751): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,E/GpsLocationProvider(  734): No APN found to select.
,I/SystemUpdateService( 1625): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1625): onCreate
,D/SystemUpdateService( 1625): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
I/SystemUpdateService( 1625): active receiver: enabled
,I/iu.Environment( 1625): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
I/SystemUpdateService( 1625): showing system update notification
,I/iu.UploadsManager( 1625): num queued entries: 0
,I/iu.UploadsManager( 1625): num updated entries: 0
E/GpsLocationProvider(  734): No APN found to select.
I/iu.SyncManager( 1625): NEXT; no task
,I/Babel   ( 1883): connection state changed from CONNECTED to DISCONNECTED
,V/SystemUpdateService( 1625): retry (wakeup: false) in 3599980 ms
,I/ActivityManager(  734): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3403 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ValidateNoPeople(  734): skipping global notification
,D/SystemUpdateService( 1625): onDestroy
,I/GAv4    ( 3403): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3403):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3403):   adb logcat -s GAv4
,W/GAv4    ( 3403): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3403): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3403): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,E/native  (  734): do suspend true
,D/ConnectivityService(  734): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService(  734): Adding iface wlan0 to network 101
,E/WifiStateMachine(  734): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  734): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  734): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  734): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  734): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  734): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  734): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  734): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  734): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  734): rematching NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  734):    accepting network in place of null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/CSLegacyTypeTracker(  734): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  734): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  734): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::5255:27ff:fef0:fd0b/64,192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  734): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler(  916): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1625): CM callback handler got msg 524290
,I/WebViewFactory( 3403): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3403): Time to load native libraries: 3 ms (timestamps 5214-5217)
,I/LibraryLoader( 3403): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3403): Binding Chromium to main looper Looper (main, tid 1) {1bd2425}
,I/LibraryLoader( 3403): Expected native library version number "",actual native library version number ""
,I/chromium( 3403): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3403): Initializing chromium process, singleProcess=true
,W/art     ( 3403): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3403): ApplicationContext is null in ApplicationStatus
,W/chromium( 3403): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3403): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3403): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3403): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 17 Dec 2015 14:10:43 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450361443061], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450361443040]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): Validated
D/ConnectivityService(  734): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  734): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  734): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  734): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  916): CM callback handler got msg 524290
,D/TelephonyNetworkFactory( 1268): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  734): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1625): CM callback handler got msg 524290
,W/AudioManagerAndroid( 3403): Requires BLUETOOTH permission
,I/NSApplication( 3403): Starting up...
,I/ActivityManager(  734): Killing 2730:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/libprocessgroup(  734): failed to open /acct/uid_10003/pid_2730/cgroup.procs: No such file or directory
,V/MusicLeanback( 2751): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1625): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1625): onCreate
,D/SystemUpdateService( 1625): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1625): active receiver: enabled
,I/iu.Environment( 1625): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/SystemUpdateService( 1625): showing system update notification
,I/iu.UploadsManager( 1625): num queued entries: 0
,I/iu.UploadsManager( 1625): num updated entries: 0
I/iu.SyncManager( 1625): NEXT; no task
,I/ValidateNoPeople(  734): skipping global notification
,V/SystemUpdateService( 1625): retry (wakeup: false) in 3599968 ms
,D/SystemUpdateService( 1625): onDestroy
,I/Babel   ( 1883): connection state changed from DISCONNECTED to CONNECTED
,D/ConnectivityService(  734): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/jxcore-log( 3256): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3256): 
,D/ConnectivityService(  734): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  734): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2751): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2751): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1625): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1625): onCreate
,D/SystemUpdateService( 1625): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1625): active receiver: enabled
,I/SystemUpdateService( 1625): showing system update notification
,E/GpsLocationProvider(  734): No APN found to select.
,I/ValidateNoPeople(  734): skipping global notification
,V/SystemUpdateService( 1625): retry (wakeup: false) in 3599979 ms
,D/SystemUpdateService( 1625): onDestroy
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): setDiscoveryMode: Mode set to WIFI
,I/jxcore-log( 3256): BLE supported!!
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3256): 
,D/Finsky  ( 2620): [255] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2620): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/jxcore-log( 3256): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3256): 
,I/art     (  734): Explicit concurrent mark sweep GC freed 45377(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 27MB/41MB, paused 1.282ms total 97.235ms
,I/GoogleURLConnFactory( 1564): Using platform SSLCertificateSocketFactory
,V/GLSActivity( 1564): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1564): Vacuum at: now=1450361455422 tag=VacuumService
,W/PhenotypeConfigurator( 1564): Server returned 404
,I/PhenotypeConfigurator( 1564): Scheduling Phenotype for one-off execution 858 seconds from now (1450361456338)
,D/GetConfigurationSnapshotOperation( 1564): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1564): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1564): Using platform SSLCertificateSocketFactory
,V/GLSActivity( 1564): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1564): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 3256): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3256): 
,I/ClearcutLoggerApiImpl( 1564): disconnect managed GoogleApiClient
,I/jxcore-log( 3256): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): DBG, CoordinatorConnector connect called
I/jxcore-log( 3256): 
I/jxcore-log( 3256): Coordinator is now connected to the server!
I/jxcore-log( 3256): 
,I/chromium( 3256): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63)
,I/ActivityManager(  734): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=3614 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,I/GAv4    ( 3614): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3614):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3614):   adb logcat -s GAv4
,W/GAv4    ( 3614): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3614): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3614): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  734): Killing 2702:com.android.settings/1000 (adj 15): empty #17
,D/WifiService(  734): Client connection lost with reason: 4
,W/libprocessgroup(  734): failed to open /acct/uid_1000/pid_2702/cgroup.procs: No such file or directory
,I/jxcore-log( 3256): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): DBG, CoordinatorConnector command called
I/jxcore-log( 3256): 
I/jxcore-log( 3256): command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":20000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":14,"addressList":[{"address":"7C:F9:0E:37:96:AB","tryCount":0},{"address":"58:3F:54:73:64:C0","tryCount":0},{"address":"F8:95:C7:87:85:54","tryCount":0},{"address":"7C:F9:0E:34:8A:A0","tryCount":0},{"address":"F8:CF:C5:D9:E5:61","tryCount":0},{"address":"F8:95:C7:87:3C:51","tryCount":0},{"address":"08:EC:A9:50:75:41","tryCount":0},{"address":"90:E7:C4:F6:69:77","tryCount":0},{"address":"B0:C5:59:3F:75:69","tryCount":0},{"address":"7C:F9:0E:51:18:22","tryCount":0},{"address":"08:EC:A9:50:76:27","tryCount":0},{"address":"E0:DB:10:1F:C9:5E","tryCount":0},{"address":"44:80:EB:7B:5A:05","tryCount":0},{"address":"E0:DB:10:14:E2:C0","tryCount":0}]}
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): Start now : testSendData.js
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 14
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): check server
I/jxcore-log( 3256): 
I/jxcore-log( 3256): serverPort is 34306
I/jxcore-log( 3256): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): setDiscoveryMode: Mode set to WIFI
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): setDiscoveryMode: Failed to set discovery mode to BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): setDiscoveryMode: Mode set to WIFI
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): start: Peer ID: 34:FC:EF:11:AE:67, peer name: LGE-Nexus 5_PT7166
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3256): bind: Binding a new listener
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3256): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3256): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT7166","ra":"34:FC:EF:11:AE:67"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): setConnectionTimeout: 15000
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): start: OK
I/io.jxcore.node.ConnectionHelper( 3256): start: Using peer discovery mode: WIFI
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): start: Peer ID: 34:FC:EF:11:AE:67, peer name: LGE-Nexus 5_PT7166
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3256): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT7166","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3256): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT7166","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3256): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT7166","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3256): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3256): start: OK
I/jxcore-log( 3256): StartBroadcasting started ok
I/jxcore-log( 3256): 
I/jxcore-log( 3256): do fake peer & start
I/jxcore-log( 3256): 
I/jxcore-log( 3256): Connect to fake peer: E0:DB:10:14:E2:C0
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-17T14:16:43.888Z SendDataConnector.js: Start called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-17T14:16:43.889Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-17T14:16:43.889Z SendDataConnector.js: do connect now
I/jxcore-log( 3256): 
I/io.jxcore.node.ConnectionHelper( 3256): connect: Trying to connect to peer with ID E0:DB:10:14:E2:C0
D/io.jxcore.node.ConnectionHelper( 3256): hasConnection: No connection with peer with ID E0:DB:10:14:E2:C0
W/io.jxcore.node.ConnectionHelper( 3256): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): connect: [E0:DB:10:14:E2:C0 E0:DB:10:14:E2:C0]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): connect: Trying to start connecting to null in address E0:DB:10:14:E2:C0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): setInsecureRfcommSocketPort: Using port -1
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnecting: null E0:DB:10:14:E2:C0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): connect: Started connecting to null in address E0:DB:10:14:E2:C0
I/io.jxcore.node.ConnectionHelper( 3256): connect: Connection process successfully started (peer ID: E0:DB:10:14:E2:C0)
,I/jxcore-log( 3256): 2015-12-17T14:16:43.899Z SendDataTCPServer.js: TCP/IP server is bound to port: 34306
I/jxcore-log( 3256): 
I/chromium( 3256): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
I/io.jxcore.node.ConnectionHelper( 3256): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3256): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3256): onDiscoveryManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Trying to connect to peer with address E0:DB:10:14:E2:C0 (thread ID: 307)
W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2062): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2062): info:x10
,D/        ( 2062): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,E/BluetoothRemoteDevices( 2062): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2062): process_service_search_attr_rsp
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2062): info:x10
,D/        ( 2062): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,E/BluetoothRemoteDevices( 2062): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 1 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
,D/WifiP2pManager( 3256): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
,D/btif_config_util( 2062): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2062): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2062): aclStateChangeCallback: Device is NULL
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): Connection timeout
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnectionTimeout: [E0:DB:10:14:E2:C0 E0:DB:10:14:E2:C0]
,I/jxcore-log( 3256): 2015-12-17T14:16:58.918Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [E0:DB:10:14:E2:C0 E0:DB:10:14:E2:C0] timed out
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-17T14:16:58.918Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [E0:DB:10:14:E2:C0 E0:DB:10:14:E2:C0] timed out
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-17T14:16:58.920Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:17:03.922Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-17T14:17:03.923Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3256): 
,W/bt-btif ( 2062): info:x10
,D/        ( 2062): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,E/BluetoothRemoteDevices( 2062): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 2062): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/io.jxcore.node.ConnectionHelper( 3256): disconnectOutgoingConnection: Trying to close connection to peer with ID E0:DB:10:14:E2:C0
E/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID E0:DB:10:14:E2:C0
D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3256): disconnectOutgoingConnection: Failed to disconnect (peer ID: E0:DB:10:14:E2:C0), either no such connection or failed to close the connection
I/jxcore-log( 3256): 2015-12-17T14:17:08.930Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-17T14:17:08.931Z SendDataConnector.js: Connect (retry count 1) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-17T14:17:08.932Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-17T14:17:08.933Z SendDataConnector.js: do connect now
I/jxcore-log( 3256): 
I/io.jxcore.node.ConnectionHelper( 3256): connect: Trying to connect to peer with ID E0:DB:10:14:E2:C0
,D/io.jxcore.node.ConnectionHelper( 3256): hasConnection: No connection with peer with ID E0:DB:10:14:E2:C0
W/io.jxcore.node.ConnectionHelper( 3256): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): connect: [E0:DB:10:14:E2:C0 E0:DB:10:14:E2:C0]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): connect: Trying to start connecting to null in address E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnecting: null E0:DB:10:14:E2:C0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): connect: Started connecting to null in address E0:DB:10:14:E2:C0
I/io.jxcore.node.ConnectionHelper( 3256): connect: Connection process successfully started (peer ID: E0:DB:10:14:E2:C0)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Trying to connect to peer with address E0:DB:10:14:E2:C0 (thread ID: 309)
W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2062): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2062): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2062): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 2062): info:x10
,D/        ( 2062): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,E/BluetoothRemoteDevices( 2062): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 2062): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2062): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2062): aclStateChangeCallback: Device is NULL
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): setState: RESTARTING
,I/wpa_supplicant(  993): P2P-FIND-STOPPED 
,I/wpa_supplicant(  993): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): Start timer timeout, starting now...
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): Connection timeout
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnectionTimeout: [E0:DB:10:14:E2:C0 E0:DB:10:14:E2:C0]
,I/jxcore-log( 3256): 2015-12-17T14:17:23.971Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [E0:DB:10:14:E2:C0 E0:DB:10:14:E2:C0] timed out
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-17T14:17:23.972Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [E0:DB:10:14:E2:C0 E0:DB:10:14:E2:C0] timed out
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-17T14:17:23.973Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3256): 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2062): info:x10
,D/        ( 2062): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
E/BluetoothRemoteDevices( 2062): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2062): tBTM_SEC_DEV:0xa3e50ebc rs_disc_pending=0
,W/bt-btif ( 2062): bta_dm_check_av:0
,W/bt-btif ( 2062): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2062): invalid rfc slot id: 5
,E/bt-btm  ( 2062): invalid rfc slot id: 5
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 307)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Maximum number of allowed retries (0) reached, giving up... (thread ID: 307)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): shutdown (thread ID: 307)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Exiting thread (thread ID: 307)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [E0:DB:10:14:E2:C0 E0:DB:10:14:E2:C0]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): setInsecureRfcommSocketPort: Will use port 1 when trying to connect
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: Android_50a5 fa:cf:c5:d9:e5:62
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): restart: Restarting...
,D/WifiP2pManager( 3256): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  993): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: Android_50a5 fa:cf:c5:d9:e5:62
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: Android_50a5 fa:cf:c5:d9:e5:62
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
,E/bt-btm  ( 2062): tBTM_SEC_DEV:0xa3e50ebc rs_disc_pending=0
W/bt-btif ( 2062): bta_dm_check_av:0
,W/bt-btif ( 2062): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2062): process_service_search_attr_rsp
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BluetoothBondStateMachine( 2062): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
E/bt-btif ( 2062): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2062): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 2062): Entering PendingCommandState State
,I/ActivityManager(  734): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.BluetoothPairingRequest: pid=3653 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/BluetoothBondStateMachine( 2062): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,D/BluetoothAdapterProperties( 2062): Failed to remove device: F8:95:C7:87:3C:51
,I/BluetoothBondStateMachine( 2062): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2062): StableState(): Entering Off State
,D/BluetoothManagerService(  734): Message: 20
D/BluetoothManagerService(  734): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@25cd9852:true
,I/ActivityManager(  734): Killing 2563:com.google.android.gm/u0a70 (adj 15): empty #17
,W/libprocessgroup(  734): failed to open /acct/uid_10070/pid_2563/cgroup.procs: No such file or directory
,W/bt-btif ( 2062): new conn_srvc id:26, app_id:255
W/bt-btif ( 2062): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2062): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3256): Incoming connection accepted
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3256): Incoming connection initialized (thread ID: 311)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3256): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3256): Entering thread (ID: 311)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3256): onBytesRead: Read 77 bytes successfully (thread ID: 311)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3256): Got valid identity from [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3256): onBytesWritten: 77 bytes successfully written (thread ID: 311)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3256): removeThreadFromList: Removing thread with ID 311
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3256): Handshake thread disposed (thread ID: 311)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onIncomingConnectionConnected: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnected: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
I/io.jxcore.node.ConnectionHelper( 3256): onConnected: Incoming connection to peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
D/io.jxcore.node.ConnectionHelper( 3256): hasConnection: No connection with peer with ID F8:95:C7:87:3C:51
D/io.jxcore.node.ConnectionHelper( 3256): notifyPeerAvailability: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016] is available
I/io.jxcore.node.ConnectionHelper( 3256): onConnected: Incoming socket thread, for peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], created successfully
D/io.jxcore.node.ConnectionHelper( 3256): onConnected: The total number of connections is now 1
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3256): Exiting thread (ID: 311)
,D/io.jxcore.node.IncomingSocketThread( 3256): Entering thread (ID: 312)
,I/jxcore-log( 3256): 2015-12-17T14:17:28.542Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3256): 
,I/io.jxcore.node.IncomingSocketThread( 3256): Local host address: localhost/127.0.0.1, port: 34306
D/io.jxcore.node.IncomingSocketThread( 3256): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3256): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3256): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3256): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3256): Exiting thread (ID: 312)
,D/io.jxcore.node.StreamCopyingThread( 3256): Entering thread (ID: 314, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3256): Entering thread (ID: 313, name: Sender)
,I/BluetoothBondStateMachine( 2062): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 1
E/bt-btif ( 2062): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2062): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2062): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2062): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 0
,D/BluetoothAdapterProperties( 2062): Failed to remove device: E0:DB:10:14:E2:C0
,I/BluetoothBondStateMachine( 2062): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2062): StableState(): Entering Off State
,E/bt-btm  ( 2062): tBTM_SEC_DEV:0xa3e50ebc rs_disc_pending=1
W/bt-btif ( 2062): bta_dm_check_av:0
,W/bt-btif ( 2062): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3256): 2015-12-17T14:17:28.974Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:17:28.975Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3256): 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: Android_50a5 fa:cf:c5:d9:e5:62
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
,I/jxcore-log( 3256): 2015-12-17T14:17:29.323Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:17:29.377Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:17:29.419Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:17:29.442Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:17:29.453Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:17:29.466Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:17:29.500Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:17:29.524Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:17:29.550Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:17:29.568Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:17:29.594Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 3256): 
,E/bt-btm  ( 2062): tBTM_SEC_DEV:0xa3e50ebc rs_disc_pending=0
W/bt-btif ( 2062): bta_dm_check_av:0
,W/bt-btif ( 2062): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3256): 2015-12-17T14:17:29.627Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:17:29.639Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:17:29.693Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:17:29.727Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:17:29.754Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:17:29.791Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:17:29.799Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:17:29.846Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:17:29.899Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:17:29.921Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3256): 
,W/bt-btif ( 2062): new conn_srvc id:26, app_id:1
W/bt-btif ( 2062): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2062): bta_dm_pm_ssr:2, lat:1200
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): shutdown (thread ID: 309)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onSocketConnected: [E0:DB:10:14:E2:C0 E0:DB:10:14:E2:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 309)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Exiting thread (thread ID: 309)
,E/bt-btm  ( 2062): tBTM_SEC_DEV:0xa3e50ebc rs_disc_pending=1
W/bt-btif ( 2062): bta_dm_check_av:0
,W/bt-btif ( 2062): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2062): tBTM_SEC_DEV:0xa3e51084 rs_disc_pending=0
W/bt-btif ( 2062): bta_dm_check_av:0
,W/bt-btif ( 2062): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2062): invalid rfc slot id: 4
,W/io.jxcore.node.StreamCopyingThread( 3256): Either failed to read from the output stream or write to the input stream (thread ID: 314, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 3256): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3256): onDisconnected: Incoming connection, peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 312
D/io.jxcore.node.IncomingSocketThread( 3256): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3256): doStop: Thread ID: 314
D/io.jxcore.node.IncomingSocketThread( 3256): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3256): doStop: Thread ID: 313
D/io.jxcore.node.IncomingSocketThread( 3256): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 3256): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3256): Either failed to read from the output stream or write to the input stream (thread ID: 313, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3256): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3256): onDisconnected: Incoming connection, peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.IncomingSocketThread( 3256): closeLocalSocketAndStreams: Closing the local output stream...,
,D/io.jxcore.node.IncomingSocketThread( 3256): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3256): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3256): Exiting thread (ID: 313, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 3256): Exiting thread (ID: 314, name: Receiver)
,I/jxcore-log( 3256): 2015-12-17T14:17:30.657Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3256): 
,E/bt-btm  ( 2062): tBTM_SEC_DEV:0xa3e51084 rs_disc_pending=1
W/bt-btif ( 2062): bta_dm_check_av:0
,W/bt-btif ( 2062): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 2062): rfc_find_lcid_mcb LCID reused LCID:0x48 current:0x0
W/bt-rfcomm( 2062): RFCOMM_DisconnectInd LCID:0x48
,E/bt-btm  ( 2062): tBTM_SEC_DEV:0xa3e50ebc rs_disc_pending=0
W/bt-btif ( 2062): bta_dm_check_av:0
,W/bt-btif ( 2062): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2062): bta_jv_rfc_port_to_cb(port_handle:0x9):jv handle:0x0 not FOUND
,D/btif_config_util( 2062): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2062): tBTM_SEC_DEV:0xa3e51084 rs_disc_pending=0
W/bt-btif ( 2062): bta_dm_check_av:0
,W/bt-btif ( 2062): btif_dm_cback : unhandled event (14)
,D/io.jxcore.node.ConnectionHelper( 3256): disconnectOutgoingConnection: Trying to close connection to peer with ID E0:DB:10:14:E2:C0
E/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID E0:DB:10:14:E2:C0
D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3256): disconnectOutgoingConnection: Failed to disconnect (peer ID: E0:DB:10:14:E2:C0), either no such connection or failed to close the connection
,I/jxcore-log( 3256): 2015-12-17T14:17:33.991Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-17T14:17:33.992Z SendDataConnector.js: Connect (retry count 2) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-17T14:17:33.993Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-17T14:17:33.993Z SendDataConnector.js: do connect now
I/jxcore-log( 3256): 
,I/io.jxcore.node.ConnectionHelper( 3256): connect: Trying to connect to peer with ID E0:DB:10:14:E2:C0
D/io.jxcore.node.ConnectionHelper( 3256): hasConnection: No connection with peer with ID E0:DB:10:14:E2:C0
W/io.jxcore.node.ConnectionHelper( 3256): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): connect: [E0:DB:10:14:E2:C0 E0:DB:10:14:E2:C0]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): connect: Trying to start connecting to Note4-1 in address E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): setInsecureRfcommSocketPort: Using port 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnecting: Note4-1 E0:DB:10:14:E2:C0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): connect: Started connecting to Note4-1 in address E0:DB:10:14:E2:C0
I/io.jxcore.node.ConnectionHelper( 3256): connect: Connection process successfully started (peer ID: E0:DB:10:14:E2:C0)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Trying to connect to peer with address E0:DB:10:14:E2:C0 (thread ID: 315)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3256): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2062): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2062): process_service_search_attr_rsp
,E/bt-btm  ( 2062): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2062): onReceive
,D/BluetoothManagerService(  734): Message: 20
D/BluetoothManagerService(  734): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ab4e420:true
,I/BTConnectionReceiver( 1410): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1410): Bluetooth Device Name: G4-1
,W/bt-btif ( 2062): new conn_srvc id:26, app_id:1
W/bt-btif ( 2062): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2062): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onSocketConnected: [E0:DB:10:14:E2:C0 E0:DB:10:14:E2:C0]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Socket connection succeeded (using port 1), total number of attempts: 1 (thread ID: 315)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): onBytesWritten: 77 bytes successfully written (thread ID: 316)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Outgoing connection initialized (*handshake* thread ID: 316)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Exiting thread (thread ID: 315)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3256): Entering thread (ID: 316)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): onBytesRead: Read 82 bytes successfully (thread ID: 316)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Handshake succeeded with [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT9551]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onHandshakeSucceeded: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT9551]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3256): Exiting thread (ID: 316)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnected: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT9551]
I/io.jxcore.node.ConnectionHelper( 3256): onConnected: Outgoing connection to peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT9551]
,D/io.jxcore.node.ConnectionHelper( 3256): hasConnection: No connection with peer with ID E0:DB:10:14:E2:C0
D/io.jxcore.node.ConnectionHelper( 3256): notifyPeerAvailability: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT9551] is available
,I/io.jxcore.node.ConnectionHelper( 3256): onConnected: Outgoing socket thread, for peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT9551], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 3256): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 3256): Entering thread (ID: 317)
,D/io.jxcore.node.OutgoingSocketThread( 3256): Server socket local port: 44058
I/io.jxcore.node.OutgoingSocketThread( 3256): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3256): onListeningForIncomingConnections: Outgoing connection is using port 44058 (peer ID: E0:DB:10:14:E2:C0)
I/jxcore-log( 3256): 2015-12-17T14:17:35.489Z SendDataConnector.js: CLIENT connected to 44058, error: null
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-17T14:17:35.490Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3256): 
,I/io.jxcore.node.OutgoingSocketThread( 3256): Incoming data from address: /127.0.0.1, port: 44058
D/io.jxcore.node.OutgoingSocketThread( 3256): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3256): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3256): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.OutgoingSocketThread( 3256): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3256): Exiting thread (ID: 317)
,D/io.jxcore.node.StreamCopyingThread( 3256): Entering thread (ID: 319, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3256): Entering thread (ID: 318, name: Sender)
,I/jxcore-log( 3256): 2015-12-17T14:17:35.542Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:17:36.158Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:17:36.320Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:17:36.323Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:17:36.773Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:17:36.949Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:17:37.094Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:17:37.143Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:17:37.164Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:17:37.218Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-17T14:17:37.219Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:17:37.245Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-17T14:17:37.247Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3256): 
D/io.jxcore.node.ConnectionHelper( 3256): disconnectOutgoingConnection: Trying to close connection to peer with ID E0:DB:10:14:E2:C0
I/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: E0:DB:10:14:E2:C0
I/io.jxcore.node.OutgoingSocketThread( 3256): close
D/io.jxcore.node.OutgoingSocketThread( 3256): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3256): doStop: Thread ID: 319
D/io.jxcore.node.OutgoingSocketThread( 3256): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3256): doStop: Thread ID: 318
D/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3256): Either failed to read from the output stream or write to the input stream (thread ID: 318, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3256): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
,W/io.jxcore.node.ConnectionHelper( 3256): onDisconnected: Outgoing connection, peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT9551] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3256): closeBluetoothSocketAndStreams
W/io.jxcore.node.StreamCopyingThread( 3256): Either failed to read from the output stream or write to the input stream (thread ID: 319, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 3256): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3256): onDisconnected: Outgoing connection, peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT9551] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3256): disconnectOutgoingConnection: Successfully disconnected (peer ID: E0:DB:10:14:E2:C0
,E/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID E0:DB:10:14:E2:C0
D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3256): Exiting thread (ID: 318, name: Sender)
E/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID E0:DB:10:14:E2:C0
D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3256): Exiting thread (ID: 319, name: Receiver)
,I/jxcore-log( 3256): 2015-12-17T14:17:37.264Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): ---- round done--------
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): do fake peer & start
I/jxcore-log( 3256): 
I/jxcore-log( 3256): Connect to fake peer: 90:E7:C4:F6:69:77
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-17T14:17:37.266Z SendDataConnector.js: Start called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-17T14:17:37.266Z SendDataConnector.js: doConnect called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-17T14:17:37.266Z SendDataConnector.js: do connect now
I/jxcore-log( 3256): 
I/io.jxcore.node.ConnectionHelper( 3256): connect: Trying to connect to peer with ID 90:E7:C4:F6:69:77
D/io.jxcore.node.ConnectionHelper( 3256): hasConnection: No connection with peer with ID 90:E7:C4:F6:69:77
W/io.jxcore.node.ConnectionHelper( 3256): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): connect: [90:E7:C4:F6:69:77 90:E7:C4:F6:69:77]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): connect: Trying to start connecting to null in address 90:E7:C4:F6:69:77
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnecting: null 90:E7:C4:F6:69:77
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): connect: Started connecting to null in address 90:E7:C4:F6:69:77
I/io.jxcore.node.ConnectionHelper( 3256): connect: Connection process successfully started (peer ID: 90:E7:C4:F6:69:77)
,I/chromium( 3256): [INFO:CONSOLE(63)] "logCallback Round of send data to peer E0:DB:10:14:E2:C0 done with result: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Trying to connect to peer with address 90:E7:C4:F6:69:77 (thread ID: 320)
W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2062): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2062): tBTM_SEC_DEV:0xa3e50ebc rs_disc_pending=1
W/bt-btif ( 2062): bta_dm_check_av:0
,W/bt-btif ( 2062): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2062): bta_jv_rfc_port_to_cb(port_handle:0xb):jv handle:0x0 not FOUND
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 2062): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2062): onReceive
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BTConnectionReceiver( 1410): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1410): Bluetooth Device Name: Note4-1
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2062): SDP - Rcvd conn cnf with error: 0x4  CID 0x4b
E/bt-btif ( 2062): DISCOVERY_COMP_EVT slot id:9, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2062): invalid rfc slot id: 9
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 320)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Maximum number of allowed retries (0) reached, giving up... (thread ID: 320)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Exiting thread (thread ID: 320)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [90:E7:C4:F6:69:77 90:E7:C4:F6:69:77]
,I/jxcore-log( 3256): 2015-12-17T14:17:42.648Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [90:E7:C4:F6:69:77 90:E7:C4:F6:69:77] failed
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-17T14:17:42.649Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [90:E7:C4:F6:69:77 90:E7:C4:F6:69:77] failed
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-17T14:17:42.650Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3256): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): setInsecureRfcommSocketPort: Will use port 1 when trying to connect
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): shutdown (thread ID: 320)
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: Android_50a5 fa:cf:c5:d9:e5:62
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): restart: Restarting...
,D/WifiP2pManager( 3256): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: Android_50a5 fa:cf:c5:d9:e5:62
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
,I/jxcore-log( 3256): 2015-12-17T14:17:47.651Z SendDataConnector.js: re-try now : 90:E7:C4:F6:69:77
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-17T14:17:47.651Z SendDataConnector.js: ReStart called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3256): 
,D/io.jxcore.node.ConnectionHelper( 3256): disconnectOutgoingConnection: Trying to close connection to peer with ID 90:E7:C4:F6:69:77
E/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 90:E7:C4:F6:69:77
D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3256): disconnectOutgoingConnection: Failed to disconnect (peer ID: 90:E7:C4:F6:69:77), either no such connection or failed to close the connection
I/jxcore-log( 3256): 2015-12-17T14:17:52.660Z SendDataConnector.js: Mobile.Disconnect() callback with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-17T14:17:52.661Z SendDataConnector.js: Connect (retry count 1) to peer 90:E7:C4:F6:69:77 with availability status: true
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-17T14:17:52.662Z SendDataConnector.js: doConnect called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-17T14:17:52.662Z SendDataConnector.js: do connect now
I/jxcore-log( 3256): 
I/io.jxcore.node.ConnectionHelper( 3256): connect: Trying to connect to peer with ID 90:E7:C4:F6:69:77
D/io.jxcore.node.ConnectionHelper( 3256): hasConnection: No connection with peer with ID 90:E7:C4:F6:69:77
W/io.jxcore.node.ConnectionHelper( 3256): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): connect: [90:E7:C4:F6:69:77 90:E7:C4:F6:69:77]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): connect: Trying to start connecting to null in address 90:E7:C4:F6:69:77
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): setInsecureRfcommSocketPort: Using port 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnecting: null 90:E7:C4:F6:69:77
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): connect: Started connecting to null in address 90:E7:C4:F6:69:77
I/io.jxcore.node.ConnectionHelper( 3256): connect: Connection process successfully started (peer ID: 90:E7:C4:F6:69:77)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Trying to connect to peer with address 90:E7:C4:F6:69:77 (thread ID: 322)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3256): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2062): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2062): info:x10
,D/        ( 2062): remote version info [90:e7:c4:f6:69:77]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2062): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2062): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2062): bondStateChangeCallback: Status: 0 Address: 90:E7:C4:F6:69:77 newState: 1
E/bt-btif ( 2062): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2062): Bond State Change Intent:90:E7:C4:F6:69:77 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2062): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2062): bondStateChangeCallback: Status: 0 Address: 90:E7:C4:F6:69:77 newState: 0
,D/BluetoothAdapterProperties( 2062): Failed to remove device: 90:E7:C4:F6:69:77
,I/BluetoothBondStateMachine( 2062): Bond State Change Intent:90:E7:C4:F6:69:77 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2062): StableState(): Entering Off State
,W/bt-btif ( 2062): new conn_srvc id:26, app_id:1
W/bt-btif ( 2062): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2062): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onSocketConnected: [90:E7:C4:F6:69:77 90:E7:C4:F6:69:77]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Socket connection succeeded (using port 1), total number of attempts: 1 (thread ID: 322)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): onBytesWritten: 77 bytes successfully written (thread ID: 323)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Outgoing connection initialized (*handshake* thread ID: 323)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Exiting thread (thread ID: 322)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3256): Entering thread (ID: 323)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): onBytesRead: Read 81 bytes successfully (thread ID: 323)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Handshake succeeded with [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT7778]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onHandshakeSucceeded: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT7778]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3256): Exiting thread (ID: 323)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnected: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT7778]
I/io.jxcore.node.ConnectionHelper( 3256): onConnected: Outgoing connection to peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT7778]
D/io.jxcore.node.ConnectionHelper( 3256): hasConnection: No connection with peer with ID 90:E7:C4:F6:69:77
D/io.jxcore.node.ConnectionHelper( 3256): notifyPeerAvailability: Peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT7778] is available
I/io.jxcore.node.ConnectionHelper( 3256): onConnected: Outgoing socket thread, for peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT7778], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 3256): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 3256): Entering thread (ID: 324)
D/io.jxcore.node.OutgoingSocketThread( 3256): Server socket local port: 47489
I/io.jxcore.node.OutgoingSocketThread( 3256): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3256): onListeningForIncomingConnections: Outgoing connection is using port 47489 (peer ID: 90:E7:C4:F6:69:77)
I/jxcore-log( 3256): 2015-12-17T14:17:55.187Z SendDataConnector.js: CLIENT connected to 47489, error: null
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-17T14:17:55.188Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3256): 
,I/io.jxcore.node.OutgoingSocketThread( 3256): Incoming data from address: /127.0.0.1, port: 47489
D/io.jxcore.node.OutgoingSocketThread( 3256): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3256): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3256): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3256): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3256): Exiting thread (ID: 324)
,D/io.jxcore.node.StreamCopyingThread( 3256): Entering thread (ID: 326, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3256): Entering thread (ID: 325, name: Sender)
,I/jxcore-log( 3256): 2015-12-17T14:17:55.229Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3256): 
,D/        ( 2062): PORT_WriteDataCO: tx queue is full,tx.queue_size:10172,tx.queue.count:11,available:24706
,I/jxcore-log( 3256): 2015-12-17T14:17:56.294Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3256): 
,D/        ( 2062): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:19756
,I/jxcore-log( 3256): 2015-12-17T14:17:56.360Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:17:56.422Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3256): 
,D/        ( 2062): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:8866
,I/jxcore-log( 3256): 2015-12-17T14:17:56.483Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3256): 
,D/        ( 2062): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:1936
,I/jxcore-log( 3256): 2015-12-17T14:17:56.527Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:17:56.563Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:17:56.618Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:17:56.674Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:17:56.724Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:17:56.800Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-17T14:17:56.801Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:17:56.818Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-17T14:17:56.819Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3256): 
D/io.jxcore.node.ConnectionHelper( 3256): disconnectOutgoingConnection: Trying to close connection to peer with ID 90:E7:C4:F6:69:77
I/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 90:E7:C4:F6:69:77
I/io.jxcore.node.OutgoingSocketThread( 3256): close
D/io.jxcore.node.OutgoingSocketThread( 3256): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3256): doStop: Thread ID: 326
D/io.jxcore.node.OutgoingSocketThread( 3256): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3256): doStop: Thread ID: 325
D/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3256): Either failed to read from the output stream or write to the input stream (thread ID: 325, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3256): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3256): onDisconnected: Outgoing connection, peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT7778] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3256): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3256): Either failed to read from the output stream or write to the input stream (thread ID: 326, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.OutgoingSocketThread( 3256): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,W/io.jxcore.node.ConnectionHelper( 3256): onDisconnected: Outgoing connection, peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT7778] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3256): disconnectOutgoingConnection: Successfully disconnected (peer ID: 90:E7:C4:F6:69:77
,E/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 90:E7:C4:F6:69:77
,D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,E/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 90:E7:C4:F6:69:77
D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,W/bt-btif ( 2062): bta_jv_rfc_port_to_cb(port_handle:0xc):jv handle:0x0 not FOUND
,D/io.jxcore.node.StreamCopyingThread( 3256): Exiting thread (ID: 325, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 3256): Exiting thread (ID: 326, name: Receiver)
,I/jxcore-log( 3256): 2015-12-17T14:17:56.863Z SendDataConnector.js: Mobile.Disconnect() callback with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3256): 
I/jxcore-log( 3256): ---- round done--------
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): do fake peer & start
I/jxcore-log( 3256): 
I/jxcore-log( 3256): Connect to fake peer: 7C:F9:0E:34:8A:A0
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-17T14:17:56.864Z SendDataConnector.js: Start called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-17T14:17:56.864Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-17T14:17:56.864Z SendDataConnector.js: do connect now
I/jxcore-log( 3256): 
,I/io.jxcore.node.ConnectionHelper( 3256): connect: Trying to connect to peer with ID 7C:F9:0E:34:8A:A0
D/io.jxcore.node.ConnectionHelper( 3256): hasConnection: No connection with peer with ID 7C:F9:0E:34:8A:A0
W/io.jxcore.node.ConnectionHelper( 3256): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): connect: [7C:F9:0E:34:8A:A0 7C:F9:0E:34:8A:A0]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): connect: Trying to start connecting to null in address 7C:F9:0E:34:8A:A0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnecting: null 7C:F9:0E:34:8A:A0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): connect: Started connecting to null in address 7C:F9:0E:34:8A:A0
I/io.jxcore.node.ConnectionHelper( 3256): connect: Connection process successfully started (peer ID: 7C:F9:0E:34:8A:A0)
I/chromium( 3256): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 90:E7:C4:F6:69:77 done with result: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Trying to connect to peer with address 7C:F9:0E:34:8A:A0 (thread ID: 327)
W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2062): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2062): info:x10
,D/        ( 2062): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,E/BluetoothRemoteDevices( 2062): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2062): tBTM_SEC_DEV:0xa3e515dc rs_disc_pending=1
W/bt-btif ( 2062): bta_dm_check_av:0
,W/bt-btif ( 2062): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 2062): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2062): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 1
E/bt-btif ( 2062): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2062): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2062): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2062): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 0
,D/BluetoothAdapterProperties( 2062): Failed to remove device: 7C:F9:0E:34:8A:A0
,I/BluetoothBondStateMachine( 2062): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2062): StableState(): Entering Off State
,W/bt-btif ( 2062): new conn_srvc id:26, app_id:1
W/bt-btif ( 2062): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2062): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onSocketConnected: [7C:F9:0E:34:8A:A0 7C:F9:0E:34:8A:A0]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 327)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): onBytesWritten: 77 bytes successfully written (thread ID: 328)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Outgoing connection initialized (*handshake* thread ID: 328)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Exiting thread (thread ID: 327)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3256): Entering thread (ID: 328)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): onBytesRead: Read 81 bytes successfully (thread ID: 328)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Handshake succeeded with [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT793]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onHandshakeSucceeded: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT793]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3256): Exiting thread (ID: 328)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnected: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT793]
I/io.jxcore.node.ConnectionHelper( 3256): onConnected: Outgoing connection to peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT793]
D/io.jxcore.node.ConnectionHelper( 3256): hasConnection: No connection with peer with ID 7C:F9:0E:34:8A:A0
D/io.jxcore.node.ConnectionHelper( 3256): notifyPeerAvailability: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT793] is available
,I/io.jxcore.node.ConnectionHelper( 3256): onConnected: Outgoing socket thread, for peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT793], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 3256): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 3256): Entering thread (ID: 329)
D/io.jxcore.node.OutgoingSocketThread( 3256): Server socket local port: 32780
I/io.jxcore.node.OutgoingSocketThread( 3256): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3256): onListeningForIncomingConnections: Outgoing connection is using port 32780 (peer ID: 7C:F9:0E:34:8A:A0)
I/jxcore-log( 3256): 2015-12-17T14:17:58.763Z SendDataConnector.js: CLIENT connected to 32780, error: null
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-17T14:17:58.763Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3256): 
,I/io.jxcore.node.OutgoingSocketThread( 3256): Incoming data from address: /127.0.0.1, port: 32780
D/io.jxcore.node.OutgoingSocketThread( 3256): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3256): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3256): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3256): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3256): Exiting thread (ID: 329)
,I/jxcore-log( 3256): 2015-12-17T14:17:58.786Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3256): 
,D/io.jxcore.node.StreamCopyingThread( 3256): Entering thread (ID: 331, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3256): Entering thread (ID: 330, name: Sender)
,I/jxcore-log( 3256): 2015-12-17T14:17:59.308Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:17:59.339Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:17:59.355Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:17:59.414Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:17:59.459Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:17:59.474Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:17:59.700Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:17:59.784Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:17:59.841Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3256): 
,W/bt-btif ( 2062): info:x10
,D/        ( 2062): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 2062): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3256): 2015-12-17T14:17:59.969Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-17T14:17:59.970Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:17:59.987Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-17T14:17:59.987Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3256): 
D/io.jxcore.node.ConnectionHelper( 3256): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:34:8A:A0
I/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 7C:F9:0E:34:8A:A0
I/io.jxcore.node.OutgoingSocketThread( 3256): close
D/io.jxcore.node.OutgoingSocketThread( 3256): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3256): doStop: Thread ID: 331
D/io.jxcore.node.OutgoingSocketThread( 3256): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3256): doStop: Thread ID: 330
D/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3256): Either failed to read from the output stream or write to the input stream (thread ID: 330, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3256): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3256): onDisconnected: Outgoing connection, peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT793] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 3256): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3256): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3256): Either failed to read from the output stream or write to the input stream (thread ID: 331, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 3256): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3256): onDisconnected: Outgoing connection, peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT793] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3256): disconnectOutgoingConnection: Successfully disconnected (peer ID: 7C:F9:0E:34:8A:A0
,E/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:34:8A:A0
D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3256): Exiting thread (ID: 330, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:34:8A:A0
,D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3256): Exiting thread (ID: 331, name: Receiver)
,I/jxcore-log( 3256): 2015-12-17T14:18:00.030Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3256): 
I/jxcore-log( 3256): ---- round done--------
I/jxcore-log( 3256): 
I/jxcore-log( 3256): do fake peer & start
I/jxcore-log( 3256): 
I/jxcore-log( 3256): Connect to fake peer: E0:DB:10:1F:C9:5E
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-17T14:18:00.031Z SendDataConnector.js: Start called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-17T14:18:00.031Z SendDataConnector.js: doConnect called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-17T14:18:00.031Z SendDataConnector.js: do connect now
I/jxcore-log( 3256): 
I/io.jxcore.node.ConnectionHelper( 3256): connect: Trying to connect to peer with ID E0:DB:10:1F:C9:5E
D/io.jxcore.node.ConnectionHelper( 3256): hasConnection: No connection with peer with ID E0:DB:10:1F:C9:5E
W/io.jxcore.node.ConnectionHelper( 3256): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,W/bt-btif ( 2062): bta_jv_rfc_port_to_cb(port_handle:0xd):jv handle:0x0 not FOUND
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): connect: [E0:DB:10:1F:C9:5E E0:DB:10:1F:C9:5E]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): connect: Trying to start connecting to null in address E0:DB:10:1F:C9:5E
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnecting: null E0:DB:10:1F:C9:5E
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): connect: Started connecting to null in address E0:DB:10:1F:C9:5E
I/io.jxcore.node.ConnectionHelper( 3256): connect: Connection process successfully started (peer ID: E0:DB:10:1F:C9:5E)
,I/chromium( 3256): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 7C:F9:0E:34:8A:A0 done with result: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Trying to connect to peer with address E0:DB:10:1F:C9:5E (thread ID: 332)
W/BluetoothAdapter( 3256): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2062): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2062): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2062): onReceive
,I/BTConnectionReceiver( 1410): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=90:E7:C4:F6:69:77, alias=null, name=HTC One M8s, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1410): Bluetooth Device Name: HTC One M8s
,W/bt-btif ( 2062): info:x10
,D/        ( 2062): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
E/BluetoothRemoteDevices( 2062): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 2062): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 1
E/bt-btif ( 2062): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2062): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2062): Entering PendingCommandState State
,W/bt-sdp  ( 2062): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2062): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 0
,D/BluetoothAdapterProperties( 2062): Failed to remove device: 44:80:EB:7B:5A:05
,I/BluetoothBondStateMachine( 2062): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2062): StableState(): Entering Off State
,W/bt-btif ( 2062): info:x10
,D/        ( 2062): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
E/BluetoothRemoteDevices( 2062): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 2062): new conn_srvc id:26, app_id:255
W/bt-btif ( 2062): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2062): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3256): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3256): Incoming connection initialized (thread ID: 333)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3256): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3256): Entering thread (ID: 333)
,W/bt-btif ( 2062): invalid rfc slot id: 7
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3256): Disconnected: bt socket closed, read return: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3256): removeThreadFromList: Removing thread with ID 333
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3256): Handshake failed (thread ID: 333)
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3256): Exiting thread (ID: 333)
,W/bt-rfcomm( 2062): rfc_find_lcid_mcb LCID reused LCID:0x45 current:0x0
W/bt-rfcomm( 2062): RFCOMM_DisconnectInd LCID:0x45
,I/BluetoothBondStateMachine( 2062): bondStateChangeCallback: Status: 0 Address: E0:DB:10:1F:C9:5E newState: 1
E/bt-btif ( 2062): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2062): Bond State Change Intent:E0:DB:10:1F:C9:5E OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2062): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2062): bondStateChangeCallback: Status: 0 Address: E0:DB:10:1F:C9:5E newState: 0
,D/BluetoothAdapterProperties( 2062): Failed to remove device: E0:DB:10:1F:C9:5E
,I/BluetoothBondStateMachine( 2062): Bond State Change Intent:E0:DB:10:1F:C9:5E OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2062): StableState(): Entering Off State
,W/bt-btif ( 2062): new conn_srvc id:26, app_id:1
W/bt-btif ( 2062): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2062): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onSocketConnected: [E0:DB:10:1F:C9:5E E0:DB:10:1F:C9:5E]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 332)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): onBytesWritten: 77 bytes successfully written (thread ID: 334)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Outgoing connection initialized (*handshake* thread ID: 334)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): Exiting thread (thread ID: 332)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3256): Entering thread (ID: 334)
,E/bt-btm  ( 2062): tBTM_SEC_DEV:0xa3e5196c rs_disc_pending=0
W/bt-btif ( 2062): bta_dm_check_av:0
,W/bt-btif ( 2062): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2062): tBTM_SEC_DEV:0xa3e515dc rs_disc_pending=0
W/bt-btif ( 2062): bta_dm_check_av:0
,W/bt-btif ( 2062): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 2062): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 1
,E/bt-btif ( 2062): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2062): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2062): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2062): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 0
,D/BluetoothAdapterProperties( 2062): Failed to remove device: 7C:F9:0E:37:96:AB
,I/BluetoothBondStateMachine( 2062): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2062): StableState(): Entering Off State
,W/bt-btif ( 2062): new conn_srvc id:26, app_id:255
W/bt-btif ( 2062): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2062): bta_dm_pm_ssr:2, lat:1200,
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3256): Incoming connection accepted
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3256): Incoming connection initialized (thread ID: 335)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3256): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3256): Entering thread (ID: 335)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3256): onBytesRead: Read 83 bytes successfully (thread ID: 335)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3256): Got valid identity from [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3256): onBytesWritten: 77 bytes successfully written (thread ID: 335)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3256): removeThreadFromList: Removing thread with ID 335
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3256): Handshake thread disposed (thread ID: 335)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onIncomingConnectionConnected: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3256): Exiting thread (ID: 335)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnected: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
I/io.jxcore.node.ConnectionHelper( 3256): onConnected: Incoming connection to peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
D/io.jxcore.node.ConnectionHelper( 3256): hasConnection: No connection with peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 3256): notifyPeerAvailability: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654] is available
I/io.jxcore.node.ConnectionHelper( 3256): onConnected: Incoming socket thread, for peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], created successfully
D/io.jxcore.node.ConnectionHelper( 3256): onConnected: The total number of connections is now 1
,D/io.jxcore.node.IncomingSocketThread( 3256): Entering thread (ID: 336)
,I/jxcore-log( 3256): 2015-12-17T14:18:03.493Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3256): 
,I/io.jxcore.node.IncomingSocketThread( 3256): Local host address: localhost/127.0.0.1, port: 34306
D/io.jxcore.node.IncomingSocketThread( 3256): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3256): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3256): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3256): startStreamCopyingThreads: OK
,D/io.jxcore.node.IncomingSocketThread( 3256): Exiting thread (ID: 336)
,D/io.jxcore.node.StreamCopyingThread( 3256): Entering thread (ID: 338, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3256): Entering thread (ID: 337, name: Sender)
,W/bt-btm  ( 2062): btm_acl_role_changed -> Issuing delayed HCI_Disconnect!!!
E/bt-btm  ( 2062): tBTM_SEC_DEV:0xa3e515dc rs_disc_pending=2
W/bt-btif ( 2062): bta_dm_check_av:0
,W/bt-btif ( 2062): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2062): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2062): onReceive
,I/BTConnectionReceiver( 1410): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1410): Bluetooth Device Name: S5-1
,E/bt-btm  ( 2062): tBTM_SEC_DEV:0xa3e5196c rs_disc_pending=1
W/bt-btif ( 2062): bta_dm_check_av:0
,W/bt-btif ( 2062): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3256): 2015-12-17T14:18:04.237Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:04.243Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:04.250Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:04.280Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:04.285Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:04.292Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:04.298Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:04.382Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:04.393Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3256): 
,E/bt-btm  ( 2062): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2062): onReceive
,I/BTConnectionReceiver( 1410): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1410): Bluetooth Device Name: XT1072
,I/jxcore-log( 3256): 2015-12-17T14:18:04.474Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:04.493Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:04.495Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:04.535Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:04.540Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:04.547Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:04.557Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:04.623Z SendDataTCPServer.js: TCP/IP server has received 32768 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:04.629Z SendDataTCPServer.js: TCP/IP server has received 34748 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:04.635Z SendDataTCPServer.js: TCP/IP server has received 36728 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:04.674Z SendDataTCPServer.js: TCP/IP server has received 38708 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:04.681Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:04.687Z SendDataTCPServer.js: TCP/IP server has received 42668 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:04.726Z SendDataTCPServer.js: TCP/IP server has received 44648 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:04.762Z SendDataTCPServer.js: TCP/IP server has received 46628 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:04.771Z SendDataTCPServer.js: TCP/IP server has received 48608 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:04.781Z SendDataTCPServer.js: TCP/IP server has received 50588 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:04.827Z SendDataTCPServer.js: TCP/IP server has received 52568 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:04.859Z SendDataTCPServer.js: TCP/IP server has received 58508 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:04.868Z SendDataTCPServer.js: TCP/IP server has received 60488 bytes of data
I/jxcore-log( 3256): 
,E/bt-btm  ( 2062): tBTM_SEC_DEV:0xa3e517a4 rs_disc_pending=0
W/bt-btif ( 2062): bta_dm_check_av:0
,W/bt-btif ( 2062): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3256): 2015-12-17T14:18:04.957Z SendDataTCPServer.js: TCP/IP server has received 62468 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:04.998Z SendDataTCPServer.js: TCP/IP server has received 64448 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:05.007Z SendDataTCPServer.js: TCP/IP server has received 66428 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:05.014Z SendDataTCPServer.js: TCP/IP server has received 68408 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:05.021Z SendDataTCPServer.js: TCP/IP server has received 70388 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:05.092Z SendDataTCPServer.js: TCP/IP server has received 72368 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:05.129Z SendDataTCPServer.js: TCP/IP server has received 74348 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:05.136Z SendDataTCPServer.js: TCP/IP server has received 76328 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:05.143Z SendDataTCPServer.js: TCP/IP server has received 78308 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:05.230Z SendDataTCPServer.js: TCP/IP server has received 80288 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:05.260Z SendDataTCPServer.js: TCP/IP server has received 82268 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:05.296Z SendDataTCPServer.js: TCP/IP server has received 84248 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:05.379Z SendDataTCPServer.js: TCP/IP server has received 86228 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:05.386Z SendDataTCPServer.js: TCP/IP server has received 88208 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:05.431Z SendDataTCPServer.js: TCP/IP server has received 90188 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:05.465Z SendDataTCPServer.js: TCP/IP server has received 92168 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:05.548Z SendDataTCPServer.js: TCP/IP server has received 96128 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:05.588Z SendDataTCPServer.js: TCP/IP server has received 98108 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:05.695Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3256): 
,W/bt-btif ( 2062): dm_pm_timer expires
W/bt-btif ( 2062): dm_pm_timer expires 0
W/bt-btif ( 2062): proc dm_pm_timer expires
,D/btif_config_util( 2062): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 2062): invalid rfc slot id: 13
,W/io.jxcore.node.StreamCopyingThread( 3256): Either failed to read from the output stream or write to the input stream (thread ID: 338, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 3256): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3256): onDisconnected: Incoming connection, peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 336
D/io.jxcore.node.IncomingSocketThread( 3256): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3256): doStop: Thread ID: 338
,D/io.jxcore.node.IncomingSocketThread( 3256): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3256): doStop: Thread ID: 337
D/io.jxcore.node.IncomingSocketThread( 3256): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 3256): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3256): Either failed to read from the output stream or write to the input stream (thread ID: 337, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3256): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3256): onDisconnected: Incoming connection, peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.IncomingSocketThread( 3256): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 3256): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3256): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3256): Exiting thread (ID: 338, name: Receiver)
,D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.StreamCopyingThread( 3256): Exiting thread (ID: 337, name: Sender)
,I/jxcore-log( 3256): 2015-12-17T14:18:07.292Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3256): 
,E/bt-btm  ( 2062): tBTM_SEC_DEV:0xa3e517a4 rs_disc_pending=1
W/bt-btif ( 2062): bta_dm_check_av:0
,W/bt-btif ( 2062): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 2062): rfc_find_lcid_mcb LCID reused LCID:0x46 current:0x0
W/bt-rfcomm( 2062): RFCOMM_DisconnectInd LCID:0x46
,E/bt-btm  ( 2062): tBTM_SEC_DEV:0xa3e517a4 rs_disc_pending=0
W/bt-btif ( 2062): bta_dm_check_av:0
,W/bt-btif ( 2062): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2062): info:x10
,D/        ( 2062): remote version info [44:80:eb:7b:5a:05]: 7, f, 610c
,I/BTConnectionReceiver( 1410): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1410): Bluetooth Device Name: XT1072
,I/art     ( 1564): Explicit concurrent mark sweep GC freed 97450(5MB) AllocSpace objects, 32(535KB) LOS objects, 40% free, 23MB/38MB, paused 973us total 116.993ms
,E/bt-btm  ( 2062): tBTM_SEC_DEV:0xa3e517a4 rs_disc_pending=1
W/bt-btif ( 2062): bta_dm_check_av:0
W/bt-btif ( 2062): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2062): new conn_srvc id:26, app_id:255
W/bt-btif ( 2062): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2062): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3256): Incoming connection accepted
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3256): Incoming connection initialized (thread ID: 339)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3256): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3256): Entering thread (ID: 339)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3256): onBytesRead: Read 81 bytes successfully (thread ID: 339)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3256): Got valid identity from [44:80:EB:7B:5A:05 motorola-XT1072_PT4451]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3256): onBytesWritten: 77 bytes successfully written (thread ID: 339)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3256): removeThreadFromList: Removing thread with ID 339
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3256): Handshake thread disposed (thread ID: 339)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onIncomingConnectionConnected: [44:80:EB:7B:5A:05 motorola-XT1072_PT4451]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnected: [44:80:EB:7B:5A:05 motorola-XT1072_PT4451]
I/io.jxcore.node.ConnectionHelper( 3256): onConnected: Incoming connection to peer [44:80:EB:7B:5A:05 motorola-XT1072_PT4451]
D/io.jxcore.node.ConnectionHelper( 3256): hasConnection: No connection with peer with ID 44:80:EB:7B:5A:05
D/io.jxcore.node.ConnectionHelper( 3256): notifyPeerAvailability: Peer [44:80:EB:7B:5A:05 motorola-XT1072_PT4451] is available
I/io.jxcore.node.ConnectionHelper( 3256): onConnected: Incoming socket thread, for peer [44:80:EB:7B:5A:05 motorola-XT1072_PT4451], created successfully
D/io.jxcore.node.ConnectionHelper( 3256): onConnected: The total number of connections is now 1
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3256): Exiting thread (ID: 339)
,D/io.jxcore.node.IncomingSocketThread( 3256): Entering thread (ID: 340)
,I/io.jxcore.node.IncomingSocketThread( 3256): Local host address: localhost/127.0.0.1, port: 34306
D/io.jxcore.node.IncomingSocketThread( 3256): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3256): setBufferSize: Setting buffer size to 8192 bytes
,I/jxcore-log( 3256): 2015-12-17T14:18:11.642Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3256): 
,I/io.jxcore.node.StreamCopyingThread( 3256): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.IncomingSocketThread( 3256): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3256): Exiting thread (ID: 340)
,D/io.jxcore.node.StreamCopyingThread( 3256): Entering thread (ID: 342, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3256): Entering thread (ID: 341, name: Sender)
,I/jxcore-log( 3256): 2015-12-17T14:18:12.631Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:12.641Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:12.649Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:12.828Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:12.840Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:12.889Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3256): 
,W/bt-btif ( 2062): dm_pm_timer expires
W/bt-btif ( 2062): dm_pm_timer expires 0
,W/bt-btif ( 2062): proc dm_pm_timer expires
,I/jxcore-log( 3256): 2015-12-17T14:18:12.927Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:13.018Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:13.060Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:13.102Z SendDataTCPServer.js: TCP/IP server has received 36728 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:13.109Z SendDataTCPServer.js: TCP/IP server has received 38708 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:13.118Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:13.129Z SendDataTCPServer.js: TCP/IP server has received 42668 bytes of data
I/jxcore-log( 3256): 
,E/bt-btm  ( 2062): btm_sec_disconnected - Clearing Pending flag
,I/jxcore-log( 3256): 2015-12-17T14:18:13.161Z SendDataTCPServer.js: TCP/IP server has received 44648 bytes of data
I/jxcore-log( 3256): 
,D/BluetoothMapService( 2062): onReceive
,I/BTConnectionReceiver( 1410): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1410): Bluetooth Device Name: A5-1
,I/jxcore-log( 3256): 2015-12-17T14:18:13.243Z SendDataTCPServer.js: TCP/IP server has received 46628 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:13.249Z SendDataTCPServer.js: TCP/IP server has received 48608 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:13.256Z SendDataTCPServer.js: TCP/IP server has received 50588 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:13.261Z SendDataTCPServer.js: TCP/IP server has received 52568 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:13.295Z SendDataTCPServer.js: TCP/IP server has received 64448 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:13.298Z SendDataTCPServer.js: TCP/IP server has received 66428 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:13.347Z SendDataTCPServer.js: TCP/IP server has received 68408 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:13.350Z SendDataTCPServer.js: TCP/IP server has received 70388 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:13.358Z SendDataTCPServer.js: TCP/IP server has received 72368 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:13.395Z SendDataTCPServer.js: TCP/IP server has received 90188 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:13.398Z SendDataTCPServer.js: TCP/IP server has received 92168 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:13.401Z SendDataTCPServer.js: TCP/IP server has received 94148 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:13.436Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3256): 
,W/bt-btif ( 2062): invalid rfc slot id: 14
,W/io.jxcore.node.StreamCopyingThread( 3256): Either failed to read from the output stream or write to the input stream (thread ID: 342, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 3256): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3256): onDisconnected: Incoming connection, peer [44:80:EB:7B:5A:05 motorola-XT1072_PT4451] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 340
D/io.jxcore.node.IncomingSocketThread( 3256): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3256): doStop: Thread ID: 342
D/io.jxcore.node.IncomingSocketThread( 3256): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3256): doStop: Thread ID: 341
D/io.jxcore.node.IncomingSocketThread( 3256): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 3256): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3256): Either failed to read from the output stream or write to the input stream (thread ID: 341, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3256): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3256): onDisconnected: Incoming connection, peer [44:80:EB:7B:5A:05 motorola-XT1072_PT4451] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.IncomingSocketThread( 3256): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 3256): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3256): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3256): Exiting thread (ID: 341, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 3256): Exiting thread (ID: 342, name: Receiver)
,I/jxcore-log( 3256): 2015-12-17T14:18:13.526Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3256): 
,E/bt-btm  ( 2062): tBTM_SEC_DEV:0xa3e5124c rs_disc_pending=0
W/bt-btif ( 2062): bta_dm_check_av:0
,W/bt-btif ( 2062): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 2062): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3256): Disconnected: bt socket closed, read return: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): onDisconnected: [null null null] (thread ID: 334)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onConnectionFailed: Socket disconnected
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): shutdown (thread ID: 332)
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3256): Exiting thread (ID: 334)
,W/bt-btif ( 2062): invalid rfc slot id: 12
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnectionFailed: Socket disconnected [null null null]
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): setInsecureRfcommSocketPort: Will use port 1 when trying to connect
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3256): shutdown (thread ID: 332)
,W/bt-rfcomm( 2062): rfc_find_lcid_mcb LCID reused LCID:0x48 current:0x0
W/bt-rfcomm( 2062): RFCOMM_DisconnectInd LCID:0x48
,E/bt-btm  ( 2062): tBTM_SEC_DEV:0xa3e5124c rs_disc_pending=1
W/bt-btif ( 2062): bta_dm_check_av:0
,W/bt-btif ( 2062): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2062): tBTM_SEC_DEV:0xa3e517a4 rs_disc_pending=0
W/bt-btif ( 2062): bta_dm_check_av:0
,W/bt-btif ( 2062): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): setState: RESTARTING
,I/wpa_supplicant(  993): P2P-FIND-STOPPED 
,I/wpa_supplicant(  993): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant(  993): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant(  993): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant(  993): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant(  993): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 0 device(s) discovered
,E/bt-btm  ( 2062): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2062): onReceive
,E/bt-btm  ( 2062): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2062): onReceive
,I/BTConnectionReceiver( 1410): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1410): Bluetooth Device Name: XT1072
,I/BTConnectionReceiver( 1410): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1410): Bluetooth Device Name: Note3-1
,W/bt-btif ( 2062): info:x10
,D/        ( 2062): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
E/BluetoothRemoteDevices( 2062): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2062): tBTM_SEC_DEV:0xa3e51b34 rs_disc_pending=0
W/bt-btif ( 2062): bta_dm_check_av:0
,W/bt-btif ( 2062): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 2062): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 1
E/bt-btif ( 2062): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2062): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2062): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2062): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 0
,D/BluetoothAdapterProperties( 2062): Failed to remove device: 08:EC:A9:50:75:41
,I/BluetoothBondStateMachine( 2062): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2062): StableState(): Entering Off State
,W/bt-btif ( 2062): new conn_srvc id:26, app_id:255
W/bt-btif ( 2062): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2062): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3256): Incoming connection accepted
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3256): Incoming connection initialized (thread ID: 344)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3256): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3256): Entering thread (ID: 344)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3256): onBytesRead: Read 83 bytes successfully (thread ID: 344)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3256): Got valid identity from [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3256): onBytesWritten: 77 bytes successfully written (thread ID: 344)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3256): removeThreadFromList: Removing thread with ID 344
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3256): Handshake thread disposed (thread ID: 344)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onIncomingConnectionConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3256): Exiting thread (ID: 344)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
,I/io.jxcore.node.ConnectionHelper( 3256): onConnected: Incoming connection to peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/io.jxcore.node.ConnectionHelper( 3256): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
,D/io.jxcore.node.ConnectionHelper( 3256): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642] is available
,I/io.jxcore.node.ConnectionHelper( 3256): onConnected: Incoming socket thread, for peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], created successfully
D/io.jxcore.node.ConnectionHelper( 3256): onConnected: The total number of connections is now 1
,D/io.jxcore.node.IncomingSocketThread( 3256): Entering thread (ID: 345)
,I/jxcore-log( 3256): 2015-12-17T14:18:20.006Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3256): 
,I/io.jxcore.node.IncomingSocketThread( 3256): Local host address: localhost/127.0.0.1, port: 34306
,D/io.jxcore.node.IncomingSocketThread( 3256): Setting local streams and starting stream copying threads...
,I/io.jxcore.node.StreamCopyingThread( 3256): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3256): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.IncomingSocketThread( 3256): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3256): Exiting thread (ID: 345)
,D/io.jxcore.node.StreamCopyingThread( 3256): Entering thread (ID: 346, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 3256): Entering thread (ID: 347, name: Receiver)
,I/jxcore-log( 3256): 2015-12-17T14:18:20.765Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:20.772Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:20.780Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:20.794Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:20.799Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:20.853Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:20.865Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:20.897Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:20.941Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:20.979Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:20.993Z SendDataTCPServer.js: TCP/IP server has received 35640 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:21.027Z SendDataTCPServer.js: TCP/IP server has received 39600 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:21.034Z SendDataTCPServer.js: TCP/IP server has received 41580 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:21.043Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:21.096Z SendDataTCPServer.js: TCP/IP server has received 45540 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:21.109Z SendDataTCPServer.js: TCP/IP server has received 47520 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:21.123Z SendDataTCPServer.js: TCP/IP server has received 49500 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:21.144Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:21.164Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:21.198Z SendDataTCPServer.js: TCP/IP server has received 57420 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:21.233Z SendDataTCPServer.js: TCP/IP server has received 59400 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:21.245Z SendDataTCPServer.js: TCP/IP server has received 61380 bytes of data
I/jxcore-log( 3256): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): Start timer timeout, starting now...
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3256): 2015-12-17T14:18:21.282Z SendDataTCPServer.js: TCP/IP server has received 63360 bytes of data
I/jxcore-log( 3256): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/jxcore-log( 3256): 2015-12-17T14:18:21.295Z SendDataTCPServer.js: TCP/IP server has received 65340 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:21.384Z SendDataTCPServer.js: TCP/IP server has received 67320 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:21.415Z SendDataTCPServer.js: TCP/IP server has received 69300 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:21.432Z SendDataTCPServer.js: TCP/IP server has received 71280 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:21.441Z SendDataTCPServer.js: TCP/IP server has received 73260 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:21.476Z SendDataTCPServer.js: TCP/IP server has received 75240 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:21.502Z SendDataTCPServer.js: TCP/IP server has received 77220 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:21.600Z SendDataTCPServer.js: TCP/IP server has received 79200 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:21.711Z SendDataTCPServer.js: TCP/IP server has received 81180 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:21.721Z SendDataTCPServer.js: TCP/IP server has received 83160 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:21.850Z SendDataTCPServer.js: TCP/IP server has received 85140 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:21.943Z SendDataTCPServer.js: TCP/IP server has received 87120 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:21.977Z SendDataTCPServer.js: TCP/IP server has received 89100 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:22.047Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:22.097Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:22.209Z SendDataTCPServer.js: TCP/IP server has received 95040 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:22.249Z SendDataTCPServer.js: TCP/IP server has received 97020 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:22.354Z SendDataTCPServer.js: TCP/IP server has received 99000 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:18:22.362Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3256): 
,W/bt-btif ( 2062): invalid rfc slot id: 15
,W/io.jxcore.node.StreamCopyingThread( 3256): Either failed to read from the output stream or write to the input stream (thread ID: 347, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 3256): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3256): onDisconnected: Incoming connection, peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 345
D/io.jxcore.node.IncomingSocketThread( 3256): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3256): doStop: Thread ID: 347
D/io.jxcore.node.IncomingSocketThread( 3256): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3256): doStop: Thread ID: 346
D/io.jxcore.node.IncomingSocketThread( 3256): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 3256): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3256): Either failed to read from the output stream or write to the input stream (thread ID: 346, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3256): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3256): onDisconnected: Incoming connection, peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.IncomingSocketThread( 3256): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 3256): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3256): closeBluetoothSocketAndStreams
,D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3256): Exiting thread (ID: 347, name: Receiver)
,D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3256): Exiting thread (ID: 346, name: Sender)
,I/jxcore-log( 3256): 2015-12-17T14:18:22.754Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3256): 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): restart: Restarting...
,D/WifiP2pManager( 3256): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
,W/bt-rfcomm( 2062): rfc_find_lcid_mcb LCID reused LCID:0x49 current:0x0
W/bt-rfcomm( 2062): RFCOMM_DisconnectInd LCID:0x49
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
,D/btif_config_util( 2062): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2062): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2062): onReceive
,I/BTConnectionReceiver( 1410): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1410): Bluetooth Device Name: A3-1
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): restart: Restarting...
,D/WifiP2pManager( 3256): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): setState: RESTARTING
,I/wpa_supplicant(  993): P2P-FIND-STOPPED 
,I/wpa_supplicant(  993): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant(  993): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): setState: STARTED
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): restart: Restarting...
,D/WifiP2pManager( 3256): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: G4-1 a2:39:f7:6f:c9:5d
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1654","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654] already in the list, will not add again
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): restart: Restarting...
,D/WifiP2pManager( 3256): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1654","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
,I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654] already in the list, will not add again
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 3 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): restart: Restarting...
,D/WifiP2pManager( 3256): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
,I/ActivityManager(  734): Killing 1959:com.google.android.calendar/u0a31 (adj 15): empty #17
,W/libprocessgroup(  734): failed to open /acct/uid_10031/pid_1959/cgroup.procs: No such file or directory
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT8193","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], Bluetooth address: F8:95:C7:87:85:54, device name: , device address: a2:39:f7:70:12:80
D/io.jxcore.node.ConnectionHelper( 3256): notifyPeerAvailability: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193] is available
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT9642","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
,W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1016","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016] already in the list, will not add again
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  993): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
,D/WifiP2pManager( 3256): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1654","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654] already in the list, will not add again
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): restart: Restarting...
,D/WifiP2pManager( 3256): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT8193","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1654","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654] already in the list, will not add again
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): restart: Restarting...
,D/WifiP2pManager( 3256): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  993): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT8193","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1654","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654] already in the list, will not add again
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): restart: Restarting...
,D/WifiP2pManager( 3256): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT8193","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1654","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT9642","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1016","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016] already in the list, will not add again
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  993): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d,
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): restart: Restarting...
,D/WifiP2pManager( 3256): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT8193","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1654","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
,I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT9642","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1016","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016] already in the list, will not add again
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): restart: Restarting...
,D/WifiP2pManager( 3256): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler },
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT8193","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193] already in the list, will not add again
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): restart: Restarting...
,D/WifiP2pManager( 3256): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT8193","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
,I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT9642","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1016","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
,I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016] already in the list, will not add again
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): restart: Restarting...
,D/WifiP2pManager( 3256): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): setState: RESTARTING
,I/wpa_supplicant(  993): P2P-FIND-STOPPED 
,I/wpa_supplicant(  993): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant(  993): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant(  993): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant(  993): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): Start timer timeout, starting now...
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  993): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 2 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
,D/WifiP2pManager( 3256): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 3 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT9642","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642] already in the list, will not add again
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): restart: Restarting...
,D/WifiP2pManager( 3256): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
,W/bt-btif ( 2062): info:x10
,D/        ( 2062): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
E/BluetoothRemoteDevices( 2062): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 2062): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1
E/bt-btif ( 2062): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2062): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2062): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2062): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
,D/BluetoothAdapterProperties( 2062): Failed to remove device: F8:95:C7:87:85:54
,I/BluetoothBondStateMachine( 2062): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2062): StableState(): Entering Off State
,W/bt-btif ( 2062): new conn_srvc id:26, app_id:255
W/bt-btif ( 2062): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2062): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3256): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3256): Incoming connection initialized (thread ID: 348)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3256): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3256): Entering thread (ID: 348)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3256): onBytesRead: Read 77 bytes successfully (thread ID: 348)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3256): Got valid identity from [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3256): onBytesWritten: 77 bytes successfully written (thread ID: 348)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3256): removeThreadFromList: Removing thread with ID 348
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3256): Handshake thread disposed (thread ID: 348)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onIncomingConnectionConnected: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3256): Exiting thread (ID: 348)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): onConnected: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
I/io.jxcore.node.ConnectionHelper( 3256): onConnected: Incoming connection to peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
,D/io.jxcore.node.ConnectionHelper( 3256): hasConnection: No connection with peer with ID F8:95:C7:87:85:54
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 3256): onConnected: Incoming socket thread, for peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], created successfully
,D/io.jxcore.node.ConnectionHelper( 3256): onConnected: The total number of connections is now 1
,D/io.jxcore.node.IncomingSocketThread( 3256): Entering thread (ID: 349)
,I/jxcore-log( 3256): 2015-12-17T14:22:38.399Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3256): 
,I/io.jxcore.node.IncomingSocketThread( 3256): Local host address: localhost/127.0.0.1, port: 34306
D/io.jxcore.node.IncomingSocketThread( 3256): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3256): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3256): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3256): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3256): Exiting thread (ID: 349)
,D/io.jxcore.node.StreamCopyingThread( 3256): Entering thread (ID: 351, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3256): Entering thread (ID: 350, name: Sender)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT9642","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642] already in the list, will not add again
,I/jxcore-log( 3256): 2015-12-17T14:22:39.218Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:22:39.239Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:22:39.271Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:22:39.277Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:22:39.287Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:22:39.297Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:22:39.307Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:22:39.335Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:22:39.338Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3256): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1016","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016] already in the list, will not add again
,I/jxcore-log( 3256): 2015-12-17T14:22:39.383Z SendDataTCPServer.js: TCP/IP server has received 32768 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:22:39.416Z SendDataTCPServer.js: TCP/IP server has received 34748 bytes of data
I/jxcore-log( 3256): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1654","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654] already in the list, will not add again
,I/jxcore-log( 3256): 2015-12-17T14:22:39.424Z SendDataTCPServer.js: TCP/IP server has received 36728 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:22:39.432Z SendDataTCPServer.js: TCP/IP server has received 38708 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:22:39.460Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:22:39.471Z SendDataTCPServer.js: TCP/IP server has received 42668 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:22:39.520Z SendDataTCPServer.js: TCP/IP server has received 44648 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:22:39.562Z SendDataTCPServer.js: TCP/IP server has received 46628 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:22:39.602Z SendDataTCPServer.js: TCP/IP server has received 48608 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:22:39.655Z SendDataTCPServer.js: TCP/IP server has received 50588 bytes of data
I/jxcore-log( 3256): 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3256): 2015-12-17T14:22:39.766Z SendDataTCPServer.js: TCP/IP server has received 52568 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:22:39.789Z SendDataTCPServer.js: TCP/IP server has received 60488 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:22:39.800Z SendDataTCPServer.js: TCP/IP server has received 62468 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:22:39.821Z SendDataTCPServer.js: TCP/IP server has received 64448 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:22:39.861Z SendDataTCPServer.js: TCP/IP server has received 66428 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:22:39.869Z SendDataTCPServer.js: TCP/IP server has received 70388 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:22:39.900Z SendDataTCPServer.js: TCP/IP server has received 72368 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:22:39.937Z SendDataTCPServer.js: TCP/IP server has received 78308 bytes of data
I/jxcore-log( 3256): 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3256): 2015-12-17T14:22:39.998Z SendDataTCPServer.js: TCP/IP server has received 86228 bytes of data
I/jxcore-log( 3256): 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
I/jxcore-log( 3256): 2015-12-17T14:22:40.013Z SendDataTCPServer.js: TCP/IP server has received 88208 bytes of data
I/jxcore-log( 3256): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
,I/jxcore-log( 3256): 2015-12-17T14:22:40.042Z SendDataTCPServer.js: TCP/IP server has received 90188 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:22:40.075Z SendDataTCPServer.js: TCP/IP server has received 92168 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:22:40.086Z SendDataTCPServer.js: TCP/IP server has received 94148 bytes of data
I/jxcore-log( 3256): 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3256): 2015-12-17T14:22:40.124Z SendDataTCPServer.js: TCP/IP server has received 96128 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:22:40.128Z SendDataTCPServer.js: TCP/IP server has received 98108 bytes of data
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:22:40.165Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3256): 
,W/bt-btif ( 2062): invalid rfc slot id: 16
,W/io.jxcore.node.StreamCopyingThread( 3256): Either failed to read from the output stream or write to the input stream (thread ID: 351, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 3256): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3256): onDisconnected: Incoming connection, peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 349
D/io.jxcore.node.IncomingSocketThread( 3256): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3256): doStop: Thread ID: 351
,D/io.jxcore.node.IncomingSocketThread( 3256): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3256): doStop: Thread ID: 350
D/io.jxcore.node.IncomingSocketThread( 3256): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 3256): closeLocalSocketAndStreams: Closing the local input stream...
D/io.jxcore.node.IncomingSocketThread( 3256): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 3256): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3256): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3256): Exiting thread (ID: 351, name: Receiver)
,W/io.jxcore.node.StreamCopyingThread( 3256): Either failed to read from the output stream or write to the input stream (thread ID: 350, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3256): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3256): onDisconnected: Incoming connection, peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3256): Exiting thread (ID: 350, name: Sender)
,I/jxcore-log( 3256): 2015-12-17T14:22:40.299Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3256): 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,W/bt-rfcomm( 2062): rfc_find_lcid_mcb LCID reused LCID:0x4b current:0x0
W/bt-rfcomm( 2062): RFCOMM_DisconnectInd LCID:0x4b
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/btif_config_util( 2062): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 2062): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2062): onReceive
,I/BTConnectionReceiver( 1410): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1410): Bluetooth Device Name: G3s-1
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): setState: RESTARTING
,I/wpa_supplicant(  993): P2P-FIND-STOPPED 
,I/wpa_supplicant(  993): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant(  993): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant(  993): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant(  993): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 0 device(s) discovered
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  993): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 3 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
,D/WifiP2pManager( 3256): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT9642","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1016","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
,I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): Start timer timeout, starting now...
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT8193","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
,I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193] already in the list, will not add again
,I/wpa_supplicant(  993): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  993): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): setState: RESTARTING
,I/wpa_supplicant(  993): P2P-FIND-STOPPED 
,I/wpa_supplicant(  993): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant(  993): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant(  993): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant(  993): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 0 device(s) discovered
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  993): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  993): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
,D/WifiP2pManager( 3256): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT9642","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1654","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
,I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
,W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1016","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT8193","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
,I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
,W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193] already in the list, will not add again
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): Start timer timeout, starting now...
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): setState: RESTARTING
,I/wpa_supplicant(  993): P2P-FIND-STOPPED 
,I/wpa_supplicant(  993): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant(  993): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant(  993): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant(  993): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 0 device(s) discovered
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1,
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): restart: Restarting...
,D/WifiP2pManager( 3256): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  993): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): restart: Restarting...
,D/WifiP2pManager( 3256): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT9642","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1654","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
,I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT8193","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193] already in the list, will not add again
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1016","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016] already in the list, will not add again
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): setState: RESTARTING
,I/wpa_supplicant(  993): P2P-FIND-STOPPED 
,I/wpa_supplicant(  993): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant(  993): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant(  993): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant(  993): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 0 device(s) discovered
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  993): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
,D/WifiP2pManager( 3256): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  993): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d,
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
,D/WifiP2pManager( 3256): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1016","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
,W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT9642","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
,I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1654","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT8193","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193] already in the list, will not add again
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): restart: Restarting...
,D/WifiP2pManager( 3256): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1016","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT9642","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1654","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
,W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654] already in the list, will not add again
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  993): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
,D/WifiP2pManager( 3256): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1016","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1654","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT8193","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
,W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193] already in the list, will not add again
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  993): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): restart: Restarting...
,D/WifiP2pManager( 3256): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  993): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  993): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): setState: RESTARTING
,I/wpa_supplicant(  993): P2P-FIND-STOPPED 
,I/wpa_supplicant(  993): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant(  993): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant(  993): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant(  993): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 0 device(s) discovered
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  993): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
,D/WifiP2pManager( 3256): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1654","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): restart: Restarting...
,D/WifiP2pManager( 3256): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT9642","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
,I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642] already in the list, will not add again
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): restart: Restarting...
,D/WifiP2pManager( 3256): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  993): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT9642","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1016","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1654","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
,I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654] already in the list, will not add again
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): restart: Restarting...
,D/WifiP2pManager( 3256): Ignored { when=-4ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  993): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT9642","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1016","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1654","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT8193","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193] already in the list, will not add again
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0,
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): setState: RESTARTING
,I/wpa_supplicant(  993): P2P-FIND-STOPPED 
,I/wpa_supplicant(  993): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant(  993): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant(  993): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant(  993): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 0 device(s) discovered
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  993): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
,D/WifiP2pManager( 3256): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1016","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1654","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
,I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): Start timer timeout, starting now...
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT8193","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193] already in the list, will not add again
,I/wpa_supplicant(  993): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  993): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): setState: RESTARTING
,I/wpa_supplicant(  993): P2P-FIND-STOPPED 
,I/wpa_supplicant(  993): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant(  993): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant(  993): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant(  993): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
,D/WifiP2pManager( 3256): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 2 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 2 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1016","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT8193","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193] already in the list, will not add again
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT9642","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], Bluetooth address: 08:EC:A9:50:75:41, device name: , device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1654","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): Start timer timeout, starting now...
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016],
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): restart: Restarting...
,D/WifiP2pManager( 3256): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT9642","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1654","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654] already in the list, will not add again
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  993): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
,D/WifiP2pManager( 3256): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT9642","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1654","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
,I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1016","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
,I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT8193","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193] already in the list, will not add again
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): restart: Restarting...
,D/WifiP2pManager( 3256): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT9642","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1654","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
,W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654] already in the list, will not add again
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  993): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
,D/WifiP2pManager( 3256): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  993): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT9642","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1654","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654] already in the list, will not add again
,I/ActivityManager(  734): Start proc com.google.android.keep for service com.google.android.keep/.syncadapter.KeepSyncAdapterService: pid=3781 uid=10071 gids={50071, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GoogleURLConnFactory( 1625): Using platform SSLCertificateSocketFactory
,V/GLSActivity( 1564): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1564): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1564): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  734): Start proc com.google.android.calendar for service com.google.android.calendar/com.google.android.syncadapters.calendar.CalendarSyncAdapterService: pid=3814 uid=10031 gids={50031, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SQLiteLog( 3814): (283) recovered 17 frames from WAL file /data/data/com.google.android.calendar/databases/timelydata.db-wal
,W/AbstractGoogleClient( 3814): Application name is not set. Call Builder#setApplicationName.
,I/AnalyticsLogBase( 3814): PlayLogger.onLoggerConnected
,I/AnalyticsLogBase( 3814): PlayLogger.onLoggerConnected
,I/art     (  734): Explicit concurrent mark sweep GC freed 99160(4MB) AllocSpace objects, 19(304KB) LOS objects, 33% free, 29MB/43MB, paused 1.122ms total 77.403ms
,I/CalendarSyncAdapter( 3814): Found no pending settings
,I/ActivityManager(  734): Killing 3005:com.google.android.gms:car/u0a8 (adj 15): empty #17
,W/libprocessgroup(  734): failed to open /acct/uid_10008/pid_3005/cgroup.procs: No such file or directory
,I/ActivityManager(  734): Killing 2889:android.process.acore/u0a4 (adj 15): empty #17
,W/libprocessgroup(  734): failed to open /acct/uid_10004/pid_2889/cgroup.procs: No such file or directory
,I/ActivityManager(  734): Start proc com.google.android.gm for service com.google.android.gm/.provider.MailSyncAdapterService: pid=3875 uid=10070 gids={50070, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/BaseAppContext( 1564): Using Auth Proxy for data requests.
,E/BaseAppContext( 1564): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,D/ActivityThread( 3875): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,I/Gmail   ( 3875): getAccountsCursor
,V/GLSActivity( 1564): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  734): Start proc com.google.android.gm.exchange for service com.google.android.gm.exchange/com.android.exchange.service.EasService: pid=3905 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/GAV2    ( 3875): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/Gmail   ( 3875): Sync started for account: account:61035162
,I/Gmail   ( 3875): getAccountsCursor
,V/GLSActivity( 1564): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager(  734): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/Exchange( 3905): EasService.onCreate
,I/Gmail   ( 3875): Observing account changes for notifications
,I/Exchange( 3905): RestartPingTask
,E/SQLiteLog( 3875): (283) recovered 75 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,I/Exchange( 3905): RestartPingsTask did not start any pings.
I/Exchange( 3905): PSS stopIfIdle
I/Exchange( 3905): PSS has no active accounts; stopping service.
,I/Exchange( 3905): onDestroy
I/ActivityManager(  734): Killing 1482:com.google.android.partnersetup/u0a13 (adj 15): empty #17
,I/Gmail   ( 3875): notifyAccountChanged
,I/Gmail   ( 3875): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 3875): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 3875): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 3875): calculateUnknownSyncRationalesAndPurgeInBackground: running
,W/libprocessgroup(  734): failed to open /acct/uid_10013/pid_1482/cgroup.procs: No such file or directory
,I/Gmail   ( 3875): notifyAccountChanged
,V/GLSActivity( 1564): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 3875): getAccountsCursor
,V/GLSActivity( 1564): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1499): Explicit concurrent mark sweep GC freed 1574(55KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 15MB/21MB, paused 217us total 15.039ms
,I/Gmail   ( 3875): getAccountsCursor
,V/GLSActivity( 1564): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 3875): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 13009, normalSync: true
,W/ResourcesManager( 3875): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3875): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 3875): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/GCoreUlr( 1564): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_ACTIVE_STATE cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{source=sync_server_wins}]
,I/GCoreUlr( 1564): DispatchingService.onCreate()
,W/System  ( 3875): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[directory "."],nativeLibraryDirectories=[/vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 3875): Installed default security provider GmsCore_OpenSSL
,V/GLSActivity( 1564): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GCoreUlr( 1564): DispatchingService.updateActiveState+sync_server_wins: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/ActivityManager(  734): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=3972 uid=10004 gids={50004, 9997} abi=armeabi-v7a
,I/GCoreUlr( 1564): Unbound from all location providers
I/GCoreUlr( 1564): Place inference reporting - stopped
,I/GCoreUlr( 1564): DispatchingService.onDestroy()
I/GCoreUlr( 1564): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 1564): Unbound from all location providers
I/GCoreUlr( 1564): Place inference reporting - stopped
,I/ContactLocale( 3972): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,V/GLSActivity( 1564): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  734): Explicit concurrent mark sweep GC freed 45618(2MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 1.328ms total 91.686ms
,I/UsageStatsService(  734): User[0] Flushing usage stats to disk
,I/ValidateNoPeople(  734): mEvictionCount: 0
,E/SQLiteLog( 3972): (284) automatic index on sqlite_sq_A3828C90(STAT_DATA_ID)
,E/SQLiteLog( 3972): (284) automatic index on sqlite_sq_A3828100(STAT_DATA_ID)
,E/SQLiteLog( 3972): (284) automatic index on sqlite_sq_A3E18DD0(STAT_DATA_ID)
,E/SQLiteLog( 3972): (284) automatic index on sqlite_sq_A3E18330(STAT_DATA_ID)
,I/ActivityManager(  734): Killing 3139:com.android.musicfx/u0a15 (adj 15): empty #17
,W/libprocessgroup(  734): failed to open /acct/uid_10015/pid_3139/cgroup.procs: No such file or directory
,I/GHttpClientFactory( 2751): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 2751): Using platform SSLCertificateSocketFactory
,I/MusicLifecycle( 2751): Sync started
,V/GLSActivity( 1564): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1564): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/MusicSyncAdapter( 2751): Will attempt periodic sync for account: Account {name=thalitester@gmail.com, type=com.google}
,I/MusicSyncAdapter( 2751): Periodic update
,W/MusicApiClient( 2751): Activity events list is null or empty. Skip reporting.
,I/art     ( 3875): Explicit concurrent mark sweep GC freed 149414(5MB) AllocSpace objects, 15(263KB) LOS objects, 25% free, 18MB/25MB, paused 396us total 70.744ms
,I/MusicLifecycle( 2751): Sync ended
,I/Gmail   ( 3875): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 13084, normalSync: true
,I/Gmail   ( 3875): lowestBackward conversation id 0
,I/MusicLeanback( 2751): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 2751): Stop autocaching.
,I/SyncAdapterService( 3403): Ignoring sync request for non-current account
,D/WearableService( 1564): callingUid 10008, callindPid: 1564
,E/GmsUtils( 2751): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 2751): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/DelayedSyncController(  944): Delaying sync.
,W/BaseAppContext( 1625): Using Auth Proxy for data requests.
,W/BaseAppContext( 1625): Using Auth Proxy for data requests.
I/Gmail   ( 3875): notifyAccountChanged
I/Gmail   ( 3875): getAccountsCursor
,V/GLSActivity( 1564): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/BaseAppContext( 1625): Using Auth Proxy for data requests.
,I/Gmail   ( 3875): notifyAccountChanged
,W/Gmail   ( 3875): Sync complete for account: account:61035162
,I/Gmail   ( 3875): getAccountsCursor
,V/GLSActivity( 1564): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/BaseAppContext( 1625): Using Auth Proxy for data requests.
,I/art     ( 1499): Explicit concurrent mark sweep GC freed 13723(716KB) AllocSpace objects, 3(71KB) LOS objects, 24% free, 16MB/21MB, paused 398us total 22.948ms
,I/art     (  195): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 179us total 7.799ms
,I/art     (  195): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 171us total 7.524ms
,I/ActivityManager(  734): Start proc com.google.android.videos for service com.google.android.videos/.store.SyncService: pid=4053 uid=10077 gids={50077, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/art     (  195): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 170us total 7.536ms
W/BaseAppContext( 1625): Using Auth Proxy for data requests.
,W/BaseAppContext( 1625): Using Auth Proxy for data requests.
,W/BaseAppContext( 1625): Using Auth Proxy for data requests.
,W/ResourcesManager( 4053): Asset path '/system/framework/com.google.widevine.software.drm.jar' does not exist or contains no resources.
,I/ActivityManager(  734): Start proc com.google.android.apps.cloudprint:sync for service com.google.android.apps.cloudprint/.printdialog.services.CloudPrintSyncService: pid=4073 uid=10035 gids={50035, 9997, 3003, 1028} abi=armeabi-v7a
,I/ActivityManager(  734): Start proc com.google.android.apps.cloudprint for service com.google.android.apps.cloudprint/.printdialog.services.NotificationIntentService: pid=4101 uid=10035 gids={50035, 9997, 3003, 1028} abi=armeabi-v7a
,I/com.google.android.apps.cloudprint.printdialog.database.CloudPrintSyncAdapter( 4073): Sync request not initiated by GCP app. Dropping
,I/ActivityManager(  734): Killing 3169:com.google.android.apps.docs/u0a40 (adj 15): empty #17
,D/PlayMovies( 4053): PersistentCache.cleanup:103 Cache is below limit, no need to shrink: [size=0, limit=5242880]
,W/VideoCapabilities( 4053): Unrecognized profile 2130706433 for video/avc
,I/VideoCapabilities( 4053): Unsupported profile 4 for video/mp4v-es
,I/art     (  734): Explicit concurrent mark sweep GC freed 24055(978KB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 28MB/42MB, paused 816us total 52.867ms
,I/ActivityManager(  734): Killing 3091:com.android.defcontainer/u0a5 (adj 15): empty #17
,W/libprocessgroup(  734): failed to open /acct/uid_10040/pid_3169/cgroup.procs: No such file or directory
,W/libprocessgroup(  734): failed to open /acct/uid_10005/pid_3091/cgroup.procs: No such file or directory
,D/PlayMovies( 4053): TransferService.onCreate:52 creating transfer service
,W/ResourcesManager( 1625): Asset path '/system/framework/com.google.widevine.software.drm.jar' does not exist or contains no resources.
,E/Auth.Api.Credentials( 1625): [CredentialSyncAdapter] Unknown sync event.
,I/CalendarSyncAdapter( 3814): Found no pending settings
,I/Icing   ( 1625): Indexing 009F7E1EAB88E81C4EB4149FAD093AD3E8757DF2 from com.google.android.gm
,I/PlayMovies( 4053): SyncService.syncAllPurchasesAndWishlist:151 Starting sync for 515013DC511638B0584069811EF28701C0771BF5
,I/Gmail   ( 3875): Backfilling search sequence table
,I/Icing   ( 1625): Indexing done 009F7E1EAB88E81C4EB4149FAD093AD3E8757DF2
,W/ContextImpl( 3814): Implicit intents with startService are not safe: Intent { act=com.google.android.gms.analytics.service.START (has extras) } android.content.ContextWrapper.bindService:538 com.google.analytics.tracking.android.AnalyticsGmsCoreClient.connect:82 com.google.analytics.tracking.android.GAServiceProxy.connectToService:279 
,I/GAV2    ( 3814): Thread[GAThread,5,main]: No campaign data found.
,I/PlayMovies( 4053): SyncService.waitForCompletion:177 Sync completed for 515013DC511638B0584069811EF28701C0771BF5 purchases
,I/PlayMovies( 4053): SyncService.waitForCompletion:177 Sync completed for 515013DC511638B0584069811EF28701C0771BF5 wishlist
,I/ActivityManager(  734): Killing 3614:com.google.android.deskclock/u0a38 (adj 15): empty #17
,I/ActivityManager(  734): Killing 1883:com.google.android.talk/u0a54 (adj 15): empty #18
,W/libprocessgroup(  734): failed to open /acct/uid_10038/pid_3614/cgroup.procs: No such file or directory
,W/libprocessgroup(  734): failed to open /acct/uid_10054/pid_1883/cgroup.procs: No such file or directory
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): restart: Restarting...
,D/WifiP2pManager( 3256): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/GAV2    ( 3875): Thread[GAThread,5,main]: No campaign data found.
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1654","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1016","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT8193","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193] already in the list, will not add again
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  993): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/InputReader(  734): Reconfiguring input devices.  changes=0x00000010
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
,W/Launcher( 1311): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@2b527906 new=com.google.android.velvet.VelvetApplication@2b527906
,I/UpdateIcingCorporaServi( 1410): Updating corpora: APPS=com.google.android.videos, CONTACTS=MAYBE
,D/PackageBroadcastService( 1625): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.videos
,I/UpdateIcingCorporaServi( 1410): UpdateCorporaTask done [took 58 ms] updated apps [took 58 ms] 
,D/BackupManagerService(  734): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.videos flg=0x4000010 (has extras) }
,I/Launcher( 1311): Deferring update until onResume
,W/ResourcesManager( 1311): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 1311): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Launcher( 1311): Deferring update until onResume
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/Icing   ( 1625): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
,I/Icing   ( 1625): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): restart: Restarting...
,D/WifiP2pManager( 3256): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT8193","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193] already in the list, will not add again
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
,I/ActivityManager(  734): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=4194 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,I/GAv4    ( 4194): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4194):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4194):   adb logcat -s GAv4
,W/GAv4    ( 4194): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4194): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/GAv4    ( 4194): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  734): Killing 3653:com.android.settings/1000 (adj 15): empty #17
,W/libprocessgroup(  734): failed to open /acct/uid_1000/pid_3653/cgroup.procs: No such file or directory
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): restart: Restarting...
,D/WifiP2pManager( 3256): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  993): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT9642","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1654","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1016","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT8193","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193] already in the list, will not add again
,W/IcingInternalCorpora( 1625): getNumBytesRead when not calculated.
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/art     ( 1625): Explicit concurrent mark sweep GC freed 32445(2MB) AllocSpace objects, 27(455KB) LOS objects, 25% free, 22MB/30MB, paused 506us total 36.842ms
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): setState: RESTARTING
,I/wpa_supplicant(  993): P2P-FIND-STOPPED 
,I/wpa_supplicant(  993): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant(  993): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant(  993): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant(  993): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): Start timer timeout, starting now...
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): restart: Restarting...
,D/WifiP2pManager( 3256): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1654","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT9642","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], Bluetooth address: 08:EC:A9:50:75:41, device name: , device address: 0a:ec:a9:50:75:42
,W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1016","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT8193","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193] already in the list, will not add again
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/EventLogService( 1625): Aggregate from 1450360801146 (log), 1450360801146 (data)
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): setState: RESTARTING
,I/wpa_supplicant(  993): P2P-FIND-STOPPED 
,I/wpa_supplicant(  993): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant(  993): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant(  993): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,I/wpa_supplicant(  993): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): P2P device discovery started successfully
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  993): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  993): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d,
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
,D/WifiP2pManager( 3256): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1654","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1016","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT8193","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193] already in the list, will not add again
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  993): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): setState: RESTARTING
,I/wpa_supplicant(  993): P2P-FIND-STOPPED 
,I/wpa_supplicant(  993): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant(  993): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant(  993): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant(  993): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 0 device(s) discovered
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  993): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  993): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
,D/WifiP2pManager( 3256): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT9642","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): Start timer timeout, starting now...
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1654","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654] already in the list, will not add again
,I/wpa_supplicant(  993): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  993): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: true,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): restart: Restarting...
,D/WifiP2pManager( 3256): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT9642","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1654","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1016","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT8193","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193] already in the list, will not add again
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): setState: RESTARTING
,I/wpa_supplicant(  993): P2P-FIND-STOPPED 
,I/wpa_supplicant(  993): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant(  993): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant(  993): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant(  993): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): P2P device discovery started successfully
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): restart: Restarting...
,D/WifiP2pManager( 3256): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1016","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT9642","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
,I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT8193","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193] already in the list, will not add again
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  993): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3256): timeout now
I/jxcore-log( 3256): 
I/jxcore-log( 3256): dun
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): weAreDoneNow , resultArray.length: 3
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): done, now sending data to server
I/jxcore-log( 3256): 
I/jxcore-log( 3256): DBG, CoordinatorConnector sendData called
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): -- RESULT DATA {"name:":"LGE-Nexus 5_PT7166","time":1000089,"result":"TIMEOUT","sendList":[{"name":"E0:DB:10:14:E2:C0","time":53342,"result":"OK","connections":3,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"90:E7:C4:F6:69:77","time":19536,"result":"OK","connections":2,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:34:8A:A0","time":3106,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"connections":1,"name":"E0:DB:10:1F:C9:5E","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:75:41","time":0,"result":"Fail"},{"connections":0,"name":"B0:C5:59:3F:75:69","time":0,"result":"Fail"},{"connections":0,"name":"44:80:EB:7B:5A:05","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:3C:51","time":0,"result":"Fail"},{"connections":0,"name":"58:3F:54:73:64:C0","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:37:96:AB","time":0,"result":"Fail"},{"connections":0,
I/jxcore-log( 3256): sendList : 100% : 53342 ms, 99% : 53342 ms, 95 : 53342 ms, 90% : 53342 ms.
I/jxcore-log( 3256): 
I/jxcore-log( 3256): Result count 3, range 3106 ms to  53342 ms.
I/jxcore-log( 3256): 
I/jxcore-log( 3256): sendList failed peers count : 1 [25 %]
I/jxcore-log( 3256): 
I/jxcore-log( 3256): - Peer ID : E0:DB:10:1F:C9:5E, Tried : 1
I/jxcore-log( 3256): 
I/jxcore-log( 3256): sendList never tried peers count : 10 [71.42857142857143 %]
I/jxcore-log( 3256): 
I/jxcore-log( 3256): - Peer ID : 08:EC:A9:50:75:41
I/jxcore-log( 3256): 
I/jxcore-log( 3256): - Peer ID : B0:C5:59:3F:75:69
I/jxcore-log( 3256): 
I/jxcore-log( 3256): - Peer ID : 44:80:EB:7B:5A:05
I/jxcore-log( 3256): 
I/jxcore-log( 3256): - Peer ID : F8:95:C7:87:3C:51
I/jxcore-log( 3256): 
I/jxcore-log( 3256): - Peer ID : 58:3F:54:73:64:C0
I/jxcore-log( 3256): 
I/jxcore-log( 3256): - Peer ID : 7C:F9:0E:37:96:AB
I/jxcore-log( 3256): 
I/jxcore-log( 3256): - Peer ID : F8:95:C7:87:85:54
I/jxcore-log( 3256): 
I/jxcore-log( 3256): - Peer ID : 7C:F9:0E:51:18:22
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): - Peer ID : F8:CF:C5:D9:E5:61
I/jxcore-log( 3256): 
I/jxcore-log( 3256): - Peer ID : 08:EC:A9:50:76:27
I/jxcore-log( 3256): 
I/jxcore-log( 3256): 2015-12-17T14:33:23.966Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3256): 
D/io.jxcore.node.ConnectionHelper( 3256): disconnectOutgoingConnection: Trying to close connection to peer with ID E0:DB:10:1F:C9:5E
E/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID E0:DB:10:1F:C9:5E
D/io.jxcore.node.ConnectionHelper( 3256): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3256): disconnectOutgoingConnection: Failed to disconnect (peer ID: E0:DB:10:1F:C9:5E), either no such connection or failed to close the connection
,I/jxcore-log( 3256): 2015-12-17T14:33:23.968Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3256): 
,I/chromium( 3256): [INFO:CONSOLE(63)] "logCallback *** TIMEOUT ***", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3256): [INFO:CONSOLE(63)] "logCallback ---- finished : send-data -- ", source: file:///android_asset/www/js/thali_main.js (63)
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): setState: RESTARTING
,I/wpa_supplicant(  993): P2P-FIND-STOPPED 
,I/wpa_supplicant(  993): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant(  993): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant(  993): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant(  993): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  993): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3256): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT9642","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
,W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642] already in the list, will not add again,
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1016","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT8193","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193] already in the list, will not add again
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1654","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], Bluetooth address: 7C:F9:0E:37:96:AB, device name: , device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654] already in the list, will not add again
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): Start timer timeout, starting now...
,I/wpa_supplicant(  993): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  993): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): setState: RESTARTING
,I/wpa_supplicant(  993): P2P-FIND-STOPPED 
,I/wpa_supplicant(  993): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant(  993): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant(  993): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant(  993): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): Start timer timeout, starting now...
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): restart: Restarting...
,D/WifiP2pManager( 3256): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1654","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], Bluetooth address: 7C:F9:0E:37:96:AB, device name: , device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT9642","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642] already in the list, will not add again
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1016","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016] already in the list, will not add again
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): setState: RESTARTING
,I/wpa_supplicant(  993): P2P-FIND-STOPPED 
,I/wpa_supplicant(  993): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant(  993): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant(  993): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): Start timer timeout, starting now...
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): restart: Restarting...
,D/WifiP2pManager( 3256): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): setState: RESTARTING
,I/wpa_supplicant(  993): P2P-FIND-STOPPED 
,I/wpa_supplicant(  993): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant(  993): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant(  993): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): setState: STARTED
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): restart: Restarting...
,D/WifiP2pManager( 3256): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT9642","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
,W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1654","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1016","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
,I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT8193","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], Bluetooth address: F8:95:C7:87:85:54, device name: , device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193] already in the list, will not add again
,W/bt-smp  ( 2062): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2062): Plain text(LSB ~ MSB) = 0a 6f 4c 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2062): Encrypted text(LSB ~ MSB) = 41 bd e9 d1 62 7c eb cb 6a 90 7e 5f c2 15 e6 b7 
,W/bt-btm  ( 2062): Stopping oneshot timer
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80,
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  993): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): setState: RESTARTING
,I/wpa_supplicant(  993): P2P-FIND-STOPPED 
,I/wpa_supplicant(  993): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant(  993): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant(  993): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant(  993): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): P2P device discovery started successfully
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  993): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
,D/WifiP2pManager( 3256): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1016","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1654","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], Bluetooth address: 7C:F9:0E:37:96:AB, device name: , device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT9642","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT8193","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
,I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193] already in the list, will not add again
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  993): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): restart: Restarting...
,D/WifiP2pManager( 3256): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): restart: Restarting...
,D/WifiP2pManager( 3256): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): restart: Restarting...
,D/WifiP2pManager( 3256): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): restart: Restarting...
,D/WifiP2pManager( 3256): Ignored { when=-4ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1016","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1654","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT9642","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642] already in the list, will not add again
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): restart: Restarting...
,D/WifiP2pManager( 3256): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service request added successfully
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1016","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
,I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1654","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT9642","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT8193","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
,I/io.jxcore.node.ConnectionHelper( 3256): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 3256): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193] already in the list, will not add again
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1654]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1016]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  993): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8193], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8193]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT9642]
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3256): DBG, CoordinatorConnector command called
I/jxcore-log( 3256): 
I/jxcore-log( 3256): command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): stop tests now !
I/jxcore-log( 3256): 
I/jxcore-log( 3256): stop current!
I/jxcore-log( 3256): 
I/jxcore-log( 3256): testSendData stopped
I/jxcore-log( 3256): 
I/io.jxcore.node.ConnectionHelper( 3256): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3256): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3256): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3256): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3256): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3256): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3256): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): stop: Stopping P2P device discovery...
,I/wpa_supplicant(  993): P2P-FIND-STOPPED 
,I/wpa_supplicant(  993): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant(  993): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant(  993): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant(  993): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3256): release: No more listeners, de-initializing...
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3256): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3256): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3256): setState: NOT_STARTED
I/jxcore-log( 3256): StopBroadcasting went ok
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): 2015-12-17T14:37:43.653Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
I/jxcore-log( 3256): 
I/chromium( 3256): [INFO:CONSOLE(63)] "logCallback stop", source: file:///android_asset/www/js/thali_main.js (63)
,I/io.jxcore.node.ConnectionHelper( 3256): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3256): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3256): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3256): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 3256): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 3256): DBG, CoordinatorConnector command called
I/jxcore-log( 3256): 
I/jxcore-log( 3256): command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"7C:F9:0E:34:8A:A0\",\"time\":3106,\"result\":\"OK\",\"connections\":1,\"tryCount\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},{\"name\":\"90:E7:C4:F6:69:77\",\"time\":19536,\"result\":\"OK\",\"connections\":2,\"tryCount\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},{\"name\":\"E0:DB:10:14:E2:C0\",\"time\":53342,\"result\":\"OK\",\"connections\":3,\"tryCount\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000}],\"sendError\":{\"failedPeer\":[{\"connections\":1,\"name\":\"E0:DB:10:1F:C9:5E\",\"time\":0,\"result\":\"Fail\"}],\"notTriedList\":[{\"connections\":0,\"name\":\"08:EC:A9:50:75:41\",\"time\":0,\"result\":\"Fail\"},{\"connections\":0,\"name\":\"B0:C5:59:3F:75:69\",\"time\":0,\"result\":\"Fail\"},{\"connections\":0,\"name\":\"44:80:EB:7B:5A:05\",\"time\":0,\"result\":\"Fail\"},{\"connections\":0,\"name\":\"F8:95:C7:87:3C:51\",\"time\":0,\"
I/jxcore-log( 3256): ****TEST TOOK:  ms ****
I/jxcore-log( 3256): 
I/jxcore-log( 3256): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3256): 
I/jxcore-log( 3256): stop tests now !
I/jxcore-log( 3256): 
I/jxcore-log( 3256): end, event received
I/jxcore-log( 3256): 
I/jxcore-log( 3256): CoordinatorConnector close called
I/jxcore-log( 3256): 
,I/jxcore-log( 3256): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 3256): 
I/jxcore-log( 3256): The Coordinator has disconnected!
I/jxcore-log( 3256): 
I/jxcore-log( 3256): The Coordinator has closed!
I/jxcore-log( 3256): 
I/jxcore-log( 3256): stop tests now !
I/jxcore-log( 3256): 
I/jxcore-log( 3256): turning Radios off
I/jxcore-log( 3256): 
I/jxcore-log( 3256): Toggling radios to false
I/jxcore-log( 3256): 
D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  734): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@3e74cbc5 mBinding = false
I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  993): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  993): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  993): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/BluetoothManagerService(  734): Message: 2
,D/BluetoothManagerService(  734): Sending off request.
,D/BluetoothAdapterState( 2062): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 2062): Setting state to 13
I/BluetoothAdapterState( 2062): Bluetooth adapter state changed: 12-> 13
,D/BluetoothAdapterProperties( 2062): onBluetoothDisable()
I/BluetoothAdapterState( 2062): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,D/BluetoothAdapterProperties( 2062): Scan Mode:20
,D/BluetoothAdapterState( 2062): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,E/BtOppRfcommListener( 2062): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,V/BluetoothMapMasInstance( 2062): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 2062): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 2062): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
V/BluetoothMapMasInstance( 2062): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:489)
V/BluetoothMapMasInstance( 2062): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:399)
V/BluetoothMapMasInstance( 2062): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 2062): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 2062): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,D/btif_config_util( 2062): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 2062): bta_dm_disable BTA_DISABLE_DELAY set to 100 ms
W/bt-l2cap( 2062): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2062): L2CAP - PSM: 0x0017 not found for deregistration
,D/BluetoothManagerService(  734): Message: 60
,D/BluetoothManagerService(  734): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService(  734): Bluetooth State Change Intent: 12 -> 13
,D/BluetoothMapService( 2062): onReceive
D/BluetoothMapService( 2062): STATE_TURNING_OFF
V/BluetoothMapService( 2062): Handler(): got msg=4
D/BluetoothMapService( 2062): MAP Service closeService in
D/BluetoothMapMasInstance( 2062): MAP Service shutdown
V/BluetoothMapService( 2062): MAP Service closeService out
,I/BtOppRfcommListener( 2062): stopping Accept Thread
,I/BtOppRfcommListener( 2062): BluetoothSocket listen thread finished
,D/WifiService(  734): setWifiEnabled: false pid=3256, uid=10270
E/WifiService(  734): Invoking mWifiStateMachine.setWifiEnabled
,I/ActivityManager(  734): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=4286 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
I/jxcore-log( 3256): Radios toggled
I/jxcore-log( 3256): 
I/chromium( 3256): [INFO:CONSOLE(63)] "logCallback fully-closed", source: file:///android_asset/www/js/thali_main.js (63)
E/WifiStateMachine(  734): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  734): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
E/native  (  734): do suspend true
,D/CommandListener(  180): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1564): Read error: ssl=0xb4194e00: I/O error during system call, Connection timed out
V/NativeCrypto( 1564): SSL shutdown failed: ssl=0xb4194e00: I/O error during system call, Broken pipe
D/bt_userial( 2062): RX termination
W/bt_userial( 2062): select_read return size <=0:-1, exiting userial_read_thread
D/bt_userial( 2062): Leaving userial_read_thread()
W/bt-btif ( 2062): ag scb idx 1 not allocated
E/bt-btif ( 2062): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 2062): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2062): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2062): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2062): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2062): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2062): L2CAP - PSM: 0x0017 not found for deregistration
D/bt_userial( 2062): userial_close_reader Joined userial reader thread: 0
D/bt_hwcfg( 2062): hw_epilog_process
I/bt_userial_vendor( 2062): device fd = 53 close
,I/GKI_LINUX( 2062): gki_task task_id=0 [BTU] terminating
I/GKI_LINUX( 2062): GKI_exit_task 0 done
I/GKI_LINUX( 2062): GKI_shutdown(): task [BTU] terminated
D/BluetoothAdapterState( 2062): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/HeadsetService( 2062): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2062): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b527906
D/HeadsetStateMachine( 2062): Exit Disconnected: -1
D/A2dpService( 2062): Received stop request...Stopping profile...
D/A2dpStateMachine( 2062): Exit Disconnected: -1
D/BluetoothHeadset( 1237): Proxy object disconnected
D/BluetoothHeadset( 1268): Proxy object disconnected
D/BluetoothAdapterService( 2062): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b527906
D/HeadsetStateMachine( 2062): Unbinding service...
,D/BluetoothHeadset( 1237): Proxy object disconnected
W/BluetoothHeadsetServiceJni( 2062): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 2062): Cleaning up Bluetooth Handsfree callback object
,D/ConnectivityService(  734): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  734): NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
D/BluetoothHeadset(  734): Proxy object disconnected
D/BluetoothA2dp(  734): Proxy object disconnected
,D/HidService( 2062): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2062): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b527906
,D/ConnectivityService(  734): reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10008
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): ValidatedState{ when=-1ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): DefaultState{ when=-1ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): Checking http://clients3.google.com/generate_204 on <unknown ssid>
,I/GKI_LINUX( 2062): gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 2062): GKI_exit_task 2 done
I/GKI_LINUX( 2062): GKI_shutdown(): task [A2DP-MEDIA] terminated
D/HealthService( 2062): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2062): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b527906
D/PanService( 2062): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2062): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b527906
,D/BtGatt.DebugUtils( 2062): handleDebugAction() action=null
,D/BtGatt.GattService( 2062): Received stop request...Stopping profile...
D/BtGatt.GattService( 2062): stop()
D/BtGatt.AdvertiseManager( 2062): advertise clients cleared
D/BluetoothAdapterService( 2062): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b527906
,W/BluetoothHidServiceJni( 2062): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 2062): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 2062): Cleaning up Bluetooth GID callback object
W/BluetoothHealthServiceJni( 2062): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 2062): Cleaning up Bluetooth Health object
,W/BluetoothPanServiceJni( 2062): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 2062): Cleaning up Bluetooth PAN callback object
,D/BluetoothAdapterState( 2062): Stopping profile services that were post enabled
D/BluetoothMapService( 2062): Received stop request...Stopping profile...
D/BluetoothMapService( 2062): stop()
D/BluetoothMapEmailAppObserver( 2062): deinitObservers()
D/BluetoothMapEmailAppObserver( 2062): removeReceiver()
D/BluetoothAdapterService( 2062): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b527906
V/BluetoothMapService( 2062): Handler(): got msg=4
D/BluetoothMapService( 2062): MAP Service closeService in
V/BluetoothMapService( 2062): MAP Service closeService out
D/BluetoothAdapterState( 2062): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 2062): Setting state to 10
I/BluetoothAdapterState( 2062): Bluetooth adapter state changed: 13-> 10
D/BluetoothMapService( 2062): cleanup()
D/BluetoothMapService( 2062): MAP Service closeService in
V/BluetoothMapService( 2062): MAP Service closeService out
D/BluetoothManagerService(  734): Message: 60
D/BluetoothManagerService(  734): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService(  734): Broadcasting onBluetoothStateChange(false) to 5 receivers.
I/BluetoothAdapterState( 2062): Entering OffState
D/BluetoothHeadset( 1237): onBluetoothStateChange: up=false
,E/WifiConfigStore(  734): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiStateMachine(  734): scanCount==0 - aborting
,D/WifiScanningService(  734): SCAN_AVAILABLE : 1
D/RttService(  734): SCAN_AVAILABLE : 1
D/WifiScanningService(  734): StartedState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  734): DefaultState
D/AndroidRuntime( 4277): 
D/AndroidRuntime( 4277): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/RttService(  734): EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiNetworkAgent(  734): NetworkAgent: NetworkAgent channel lost
,D/AndroidRuntime( 4277): CheckJNI is OFF
,E/native  (  734): do suspend true
,D/BluetoothHeadset(  734): onBluetoothStateChange: up=false
D/BluetoothA2dp(  734): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1237): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1268): onBluetoothStateChange: up=false
,D/BluetoothManagerService(  734): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService(  734): Broadcasting onBluetoothServiceDown() to 9 receivers.
,D/BluetoothManagerService(  734): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@3e74cbc5 mBinding = false
,D/BluetoothManagerService(  734): Sending unbind request.
,D/BluetoothManagerService(  734): Bluetooth State Change Intent: 13 -> 10
,D/BluetoothAdapter(  916): 1050655995: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter(  916): 1050655995: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter(  916): 1050655995: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 1564): 627251146: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1564): 627251146: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 1564): 627251146: getState() :  mService = null. Returning STATE_OFF
,I/GKI_LINUX( 2062): gki_task task_id=1 [BTIF] terminating
,E/BluetoothDevice( 1564): BT not enabled. Cannot get Bluetooth Class
E/BluetoothDevice( 1564): BT not enabled. Cannot get Remote Device name
E/BluetoothDevice( 1564): BT not enabled. Cannot get Remote Device Alias
E/BluetoothDevice( 1564): BT not enabled. Cannot get Bluetooth Class
E/BluetoothDevice( 1564): BT not enabled. Cannot get Bluetooth Class
E/BluetoothDevice( 1564): BT not enabled. Cannot get Remote Device name
E/BluetoothDevice( 1564): BT not enabled. Cannot get Remote Device Alias
,I/GKI_LINUX( 2062): GKI_exit_task 1 done
I/GKI_LINUX( 2062): GKI_shutdown(): task [BTIF] terminated
I/BluetoothServiceJni( 2062): cleanupNative: return from cleanup
,D/CommandListener(  180): Clearing all IP addresses on wlan0
D/ConnectivityService(  734): notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,D/Nat464Xlat(  734): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/CSLegacyTypeTracker(  734): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,D/ConnectivityService(  734): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): Disconnected - quitting
D/ConnectivityService(  734): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  734): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler(  916): CM callback handler got msg 524292
,D/TelephonyNetworkFactory( 1268): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  734): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,D/ConnectivityManager.CallbackHandler( 1625): CM callback handler got msg 524292
,I/art     ( 2062): System.exit called, status: 0
I/AndroidRuntime( 2062): VM exiting with result code 0, cleanup skipped.
,D/AndroidRuntime( 4277): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  734): Process com.android.bluetooth (pid 2062) has died
W/ActivityManager(  734): Scheduling restart of crashed service com.android.bluetooth/.pbap.BluetoothPbapService in 1000ms
,I/wpa_supplicant(  993): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant(  993): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant(  993): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant(  993): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,I/wpa_supplicant(  993): p2p0: CTRL-EVENT-TERMINATING 
,I/wpa_supplicant(  993): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,W/PackageSettings(  734): Skipping PackageSetting{22861665 com.example.hello/10278} due to missing metadata
,I/ActivityManager(  734): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  734): Killing 3256:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
,W/ContextImpl( 4286): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/WifiService(  734): Client connection lost with reason: 4
I/WindowState(  734): WIN DEATH: Window{62b7785 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/Tethering(  734): InitialState.processMessage what=4
,I/wpa_supplicant(  993): wlan0: CTRL-EVENT-TERMINATING 
,I/ActivityManager(  734):   Force finishing activity ActivityRecord{1252e421 u0 com.test.thalitest/.MainActivity t214}
,W/ActivityManager(  734): Spurious death for ProcessRecord{2f454227 3256:com.test.thalitest/u0a270}, curProc for 3256: null
,D/Tethering(  734): sendTetherStateChangedBroadcast 0, 0, 0
,D/BluetoothManagerService(  734): Message: 20
D/BluetoothManagerService(  734): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@bbdae7d:true
,I/ActivityManager(  734): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=4347 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,I/ActivityManager(  734): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
,I/ActivityManager(  734):   Force finishing activity ActivityRecord{1252e421 u0 com.test.thalitest/.MainActivity t214 f}
W/ActivityManager(  734): Duplicate finish request for ActivityRecord{1252e421 u0 com.test.thalitest/.MainActivity t214 f}
,I/art     ( 1311): Explicit concurrent mark sweep GC freed 7167(467KB) AllocSpace objects, 2(207KB) LOS objects, 23% free, 26MB/34MB, paused 258us total 55.682ms
,D/BluetoothAdapter( 4286): 309323745: getState() :  mService = null. Returning STATE_OFF
I/InputReader(  734): Reconfiguring input devices.  changes=0x00000010
I/Keyboard.Facilitator( 1111): resetDictionaries() : en_US
W/GeofencerStateMachine( 1564): Ignoring removeGeofence because network location is disabled.
I/art     ( 1410): Explicit concurrent mark sweep GC freed 48078(2MB) AllocSpace objects, 9(144KB) LOS objects, 24% free, 19MB/25MB, paused 317us total 82.725ms
,I/art     ( 1625): Explicit concurrent mark sweep GC freed 1981(146KB) AllocSpace objects, 2(32KB) LOS objects, 24% free, 22MB/30MB, paused 1.514ms total 98.880ms
,D/BluetoothManagerService(  734): Message: 30
,D/BluetoothManagerService(  734): Message: 30
W/Settings( 1564): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/ResourcesManager( 4347): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,I/Keyboard.Facilitator.DecoderInitializer( 1111): run()
,I/Adreno-EGL(  944): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/OpenGLRenderer(  944): Initialized EGL, version 1.4
,D/LocalBluetoothProfileManager( 4286): Adding local MAP profile
D/BluetoothMap( 4286): Create BluetoothMap proxy object
D/BluetoothManagerService(  734): Message: 30
I/Decoder ( 1111): createOrResetDecoder
,I/art     (  734): Explicit concurrent mark sweep GC freed 84699(3MB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 29MB/43MB, paused 1.659ms total 105.489ms
D/OpenGLRenderer(  944): Enabling debug mode 0
,I/art     (  734): WaitForGcToComplete blocked for 25.863ms for cause Explicit
,D/BluetoothManagerService(  734): Message: 30
,D/LocalBluetoothProfileManager( 4286): LocalBluetoothProfileManager construction complete
,W/InputMethodManagerService(  734): Focus gain on non-focused client com.android.internal.view.IInputMethodClient$Stub$Proxy@2f72afc (uid=10034 pid=944)
,I/ConfigService( 1564): onCreate
,D/DockEventReceiver( 4286): finishStartingService: stopping service
,I/ActivityManager(  734): Killing 3781:com.google.android.keep/u0a71 (adj 15): empty #17
,D/BackupManagerService(  734): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService(  734): Receieved: android.intent.action.PACKAGE_REMOVED
,W/libprocessgroup(  734): failed to open /acct/uid_10071/pid_3781/cgroup.procs: No such file or directory
,D/AdapterServiceConfig( 4347): Adding HeadsetService
D/AdapterServiceConfig( 4347): Adding A2dpService
,D/AdapterServiceConfig( 4347): Adding HidService
D/AdapterServiceConfig( 4347): Adding HealthService
D/AdapterServiceConfig( 4347): Adding PanService
D/AdapterServiceConfig( 4347): Adding GattService
D/AdapterServiceConfig( 4347): Adding BluetoothMapService
,D/TaskPersister(  734): removeObsoleteFile: deleting file=214_task.xml
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1111): run()
,I/art     (  734): Explicit concurrent mark sweep GC freed 13640(651KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 29MB/43MB, paused 8.904ms total 166.575ms
,I/Launcher( 1311): Deferring update until onResume
,D/WifiService(  734): New client listening to asynchronous messages
,W/ResourcesManager( 1311): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  734): Message: 20
D/BluetoothManagerService(  734): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@34247f92:true
I/Keyboard.Facilitator.MainLanguageModelLoader( 1111): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
D/BluetoothAdapter( 4347): 843319909: getState() :  mService = null. Returning STATE_OFF
D/BluetoothPbap( 4286): Proxy object connected
,D/PbapServerProfile( 4286): Bluetooth service connected
D/BluetoothPbap( 4286): Proxy object disconnected
D/PbapServerProfile( 4286): Bluetooth service disconnected
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1111): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1111): run() : Loading LM = contacts
D/AuthorizationBluetoothService( 1564): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
I/ActivityManager(  734): Killing 3905:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1111): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1111): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1111): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1111): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1111): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1111): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1111): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1111): run()
I/StatsUtilsManager( 1111): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1111): shouldRecordStats() = Too Soon
,W/ResourcesManager( 1311): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Launcher( 1311): Deferring update until onResume
,W/libprocessgroup(  734): failed to open /acct/uid_10069/pid_3905/cgroup.procs: No such file or directory
,D/AndroidRuntime( 4277): Shutting down VM
,I/ActivityManager(  734): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=4388 uid=10054 gids={50054, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ResourcesManager( 4388): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 4388): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 4388): MmsConfig.loadMmsSettings
,I/Babel_SMS( 4388): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=Nexus5, mUaProfUrl=http://gsm.lge.com/html/gsm/Nexus5-M3.xml
I/Babel_SMS( 4388): MmsConfig.loadFromDatabase
,E/Babel_SMS( 4388): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 4388): MmsConfig.loadFromResources
,E/Babel_SMS( 4388): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 4388): MmsConfig.loadMmsSettings: mUserAgent=Nexus5, mUaProfUrl=http://gsm.lge.com/html/gsm/Nexus5-M3.xml
,I/Babel_SMS( 4388): ApnsOta: OTA version -1
,W/Settings( 4388): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 4388): startup - clean
,I/Babel   ( 4388): deleted: false for 0
,W/ContextImpl( 4286): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/DockEventReceiver( 4286): finishStartingService: stopping service
,D/BluetoothAdapter( 4286): 309323745: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 4286): 309323745: getState() :  mService = null. Returning STATE_OFF
,D/AuthorizationBluetoothService( 1564): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothAdapter( 4286): 309323745: getState() :  mService = null. Returning STATE_OFF
,W/VideoCapabilities( 4388): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  734): Start proc com.google.android.keep for broadcast com.google.android.keep/.notification.AlertReceiver: pid=4423 uid=10071 gids={50071, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/VideoCapabilities( 4388): Unsupported profile 4 for video/mp4v-es

```
