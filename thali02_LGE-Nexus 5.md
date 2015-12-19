#### Test 50650278161ce7f_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
D/ChimeraCfgMgr( 1668): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1668): Module APK com.google.android.play.games already loaded
I/GAv4    ( 3219): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3219):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3219):   adb logcat -s GAv4
W/GAv4    ( 3219): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3219): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3219): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 3219): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
,D/Finsky  ( 2642): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
W/ResourcesManager( 3219): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3219): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  758): Killing 2611:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
V/JNIHelp ( 3219): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/AndroidRuntime( 3276): 
D/AndroidRuntime( 3276): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
W/System  ( 3219): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3219): Installed default security provider GmsCore_OpenSSL
D/AndroidRuntime( 3276): CheckJNI is OFF
W/libprocessgroup(  758): failed to open /acct/uid_10069/pid_2611/cgroup.procs: No such file or directory
V/GLSActivity( 1627): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/AndroidRuntime( 3276): Calling main entry com.android.commands.am.Am
I/ActivityManager(  758): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  758): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3300 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3276): Shutting down VM
V/ActivityManager(  758): Display changed displayId=0
I/Icing   ( 1668): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/WebViewFactory( 3300): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/Icing   ( 1668): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/LibraryLoader( 3300): Time to load native libraries: 2 ms (timestamps 6412-6414)
I/LibraryLoader( 3300): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3300): Binding Chromium to main looper Looper (main, tid 1) {33874f1c}
I/LibraryLoader( 3300): Expected native library version number "",actual native library version number ""
I/chromium( 3300): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3300): Initializing chromium process, singleProcess=true
W/art     ( 3300): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3300): ApplicationContext is null in ApplicationStatus
W/chromium( 3300): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3300): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3300): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3300): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
I/Icing   ( 1668): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1668): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
D/BluetoothManagerService(  758): Message: 20
D/BluetoothManagerService(  758): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@321a8ce1:true
W/art     ( 3300): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 3300): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 3300): CordovaWebView is running on device made by: LGE
W/art     ( 3300): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3300): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 3300): Render dirty regions requested: true
D/Atlas   ( 3300): Validating map...
W/chromium( 3300): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/OpenGLRenderer( 3300): Initialized EGL, version 1.4
D/OpenGLRenderer( 3300): Enabling debug mode 0
W/BindingManager( 3300): Cannot call determinedVisibility() - never saw a connection for the pid: 3300
W/IInputConnectionWrapper( 3300): showStatusIcon on inactive InputConnection
I/ActivityManager(  758): Displayed com.test.thalitest/.MainActivity: +456ms (total +54s912ms)
D/JsMessageQueue( 3300): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 3300): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1356460288
D/JX-Cordova( 3300): jxcore cordova android initializing
I/ActivityManager(  758): Killing 2565:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
W/libprocessgroup(  758): failed to open /acct/uid_10045/pid_2565/cgroup.procs: No such file or directory
,W/jxcore-log( 3300): Initializing JXcore engine
W/jxcore-log( 3300): JXcore engine is ready
,W/jxcore-log( 3300): Starting JXcore engine
,W/.test.thalitest( 3300): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[6497]" dev="sockfs" ino=6497 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3300): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 3300): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[9456]" dev="sockfs" ino=9456 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3300): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[19632]" dev="sockfs" ino=19632 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3300): Platform android
W/jxcore-log( 3300): 
,W/jxcore-log( 3300): Process ARCH arm
W/jxcore-log( 3300): 
,I/jxcore-log( 3300): JXcore Cordova bridge is ready!
I/jxcore-log( 3300): 
W/jxcore-log( 3300): JXcore engine is started
I/chromium( 3300): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,V/GLSActivity( 1627): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1627): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 3300): Toggling radios to true
I/jxcore-log( 3300): 
,D/BluetoothAdapter( 3300): enable(): BT is already enabled..!
,D/WifiService(  758): New client listening to asynchronous messages
,D/WifiService(  758): setWifiEnabled: true pid=3300, uid=10270
E/WifiService(  758): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3300): Radios toggled
I/jxcore-log( 3300): 
,D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 3300): Got Device Bluetooth address: 34:FC:EF:11:AE:67
I/jxcore-log( 3300): 
I/jxcore-log( 3300): Perf Test app loaded loaded
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): check test folder
I/jxcore-log( 3300): 
I/wpa_supplicant( 1034): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  758): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  758): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/native  (  758): do suspend true
,I/jxcore-log( 3300): found test : ./testFindPeers.js
I/jxcore-log( 3300): 
,D/CommandListener(  180): Clearing all IP addresses on wlan0
,I/jxcore-log( 3300): found test : ./testSendData.js
I/jxcore-log( 3300): 
V/NativeCrypto( 1627): Read error: ssl=0xb3bf7e00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1627): SSL shutdown failed: ssl=0xb3bf7e00: I/O error during system call, Broken pipe
,E/WifiConfigStore(  758): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  758): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  758): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,E/WifiStateMachine(  758): Start Disconnecting Watchdog 1
,I/wpa_supplicant( 1034): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/ConnectivityService(  758): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): ValidatedState{ when=-1ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): DefaultState{ when=-1ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): Checking http://clients3.google.com/generate_204 on <unknown ssid>
,E/native  (  758): do suspend true
,D/CommandListener(  180): Clearing all IP addresses on wlan0
,D/ConnectivityService(  758): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/Nat464Xlat(  758): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/ConnectivityManager.CallbackHandler(  898): CM callback handler got msg 524292
,D/CSLegacyTypeTracker(  758): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,D/ConnectivityService(  758): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  758): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): EvaluatingState{ when=-3ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): DefaultState{ when=-3ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): Disconnected - quitting
,D/ConnectivityService(  758): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1188): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1668): CM callback handler got msg 524292
,D/WifiNetworkAgent(  758): NetworkAgent: NetworkAgent channel lost
,I/chromium( 3300): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/wpa_supplicant( 1034): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant( 1034): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1034): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1034): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  758): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  758): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  758): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiConfigStore(  758): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  180): Setting iface cfg
E/WifiStateMachine(  758): Start Dhcp Watchdog 2
,E/native  (  758): do suspend false
,E/WifiStateMachine(  758): scanCount==0 - aborting
,I/dhcpcd  ( 3429): version 5.5.6 starting
,E/dhcpcd  ( 3429): get_duid: Read-only file system
,I/dhcpcd  ( 3429): wlan0: rebinding lease of 192.168.1.114
,I/dhcpcd  ( 3429): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3429): wlan0: leased 192.168.1.114 for 86400 seconds
,D/ConnectivityService(  758): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  758): MasterInitialState.processMessage what=3
,D/ConnectivityService(  758): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE,
,D/Tethering(  758): MasterInitialState.processMessage what=3
,V/MusicLeanback( 2757): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1668): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1668): onCreate
,D/SystemUpdateService( 1668): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1668): active receiver: enabled
,E/GpsLocationProvider(  758): No APN found to select.
,I/iu.Environment( 1668): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/SystemUpdateService( 1668): showing system update notification
I/iu.UploadsManager( 1668): num queued entries: 0
I/iu.UploadsManager( 1668): num updated entries: 0
I/iu.SyncManager( 1668): NEXT; no task
,E/GpsLocationProvider(  758): No APN found to select.
,I/Babel   ( 1939): connection state changed from CONNECTED to DISCONNECTED
,I/ActivityManager(  758): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3471 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ValidateNoPeople(  758): skipping global notification
,V/SystemUpdateService( 1668): retry (wakeup: false) in 3599955 ms
,D/SystemUpdateService( 1668): onDestroy
,E/native  (  758): do suspend true
,D/ConnectivityService(  758): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  758): Adding iface wlan0 to network 101
,E/WifiStateMachine(  758): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  758): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  758): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  758): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/ConnectivityService(  758): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  758): Setting Dns servers for network 101 to [/192.168.1.1]
D/Nat464Xlat(  758): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  758): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  758): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  758): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  758):    accepting network in place of null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/CSLegacyTypeTracker(  758): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  758): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  758): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::5255:27ff:fef0:fd0b/64,192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  758): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler( 1668): CM callback handler got msg 524290
D/ConnectivityManager.CallbackHandler(  898): CM callback handler got msg 524290
,I/GAv4    ( 3471): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3471):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3471):   adb logcat -s GAv4
,W/GAv4    ( 3471): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3471): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3471): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Sat, 19 Dec 2015 01:31:04 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450488664419], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450488664402]}
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): Don't send network conditions - lacking user consent.
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): Validated
D/ConnectivityService(  758): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  758): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  758): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  758): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler(  898): CM callback handler got msg 524290
,D/ConnectivityService(  758): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/TelephonyNetworkFactory( 1188): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 1668): CM callback handler got msg 524290
,I/WebViewFactory( 3471): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3471): Time to load native libraries: 2 ms (timestamps 3494-3496)
,I/LibraryLoader( 3471): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3471): Binding Chromium to main looper Looper (main, tid 1) {a013eae}
,I/LibraryLoader( 3471): Expected native library version number "",actual native library version number ""
I/chromium( 3471): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3471): Initializing chromium process, singleProcess=true
,W/art     ( 3471): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3471): ApplicationContext is null in ApplicationStatus
,W/chromium( 3471): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3471): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3471): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3471): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/AudioManagerAndroid( 3471): Requires BLUETOOTH permission
,I/NSApplication( 3471): Starting up...
,I/ActivityManager(  758): Killing 2734:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/libprocessgroup(  758): failed to open /acct/uid_10003/pid_2734/cgroup.procs: No such file or directory
,V/MusicLeanback( 2757): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1668): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1668): onCreate
,D/SystemUpdateService( 1668): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1668): active receiver: enabled
,I/SystemUpdateService( 1668): showing system update notification
,I/iu.Environment( 1668): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1668): num queued entries: 0
,I/iu.UploadsManager( 1668): num updated entries: 0
,I/iu.SyncManager( 1668): NEXT; no task
,I/ValidateNoPeople(  758): skipping global notification
,V/SystemUpdateService( 1668): retry (wakeup: false) in 3599978 ms
,D/SystemUpdateService( 1668): onDestroy
,I/Babel   ( 1939): connection state changed from DISCONNECTED to CONNECTED
,D/ConnectivityService(  758): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): setDiscoveryMode: Mode set to WIFI
,I/jxcore-log( 3300): BLE supported!!
I/jxcore-log( 3300): 
,D/ConnectivityService(  758): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  758): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2757): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2757): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1668): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1668): onCreate
,D/SystemUpdateService( 1668): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1668): active receiver: enabled
,I/SystemUpdateService( 1668): showing system update notification
,I/ValidateNoPeople(  758): skipping global notification
,V/SystemUpdateService( 1668): retry (wakeup: false) in 3599959 ms
,I/art     (  758): Explicit concurrent mark sweep GC freed 42795(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 27MB/41MB, paused 4.058ms total 63.619ms
,D/SystemUpdateService( 1668): onDestroy
,E/GpsLocationProvider(  758): No APN found to select.
,D/Finsky  ( 2642): [260] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2642): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/GLSActivity( 1627): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1627): Vacuum at: now=1450488678567 tag=VacuumService
,I/PhenotypeConfigurator( 1627): Scheduling Phenotype for one-off execution 2089 seconds from now (1450488678809)
,D/GetConfigurationSnapshotOperation( 1627): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1627): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1627): Using platform SSLCertificateSocketFactory
,V/GLSActivity( 1627): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1627): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ClearcutLoggerApiImpl( 1627): disconnect managed GoogleApiClient
,I/jxcore-log( 3300): Connected to the server!
I/jxcore-log( 3300): 
,I/chromium( 3300): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3300): --- start :testSendData.js---
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): testSendData created {"name":"testSendData.js","serverTimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":14}bt-address length : 0
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): daya100000
I/jxcore-log( 3300): 
I/jxcore-log( 3300): check server
I/jxcore-log( 3300): 
I/jxcore-log( 3300): serverPort is 34900
I/jxcore-log( 3300): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): setDiscoveryMode: Mode set to WIFI
,D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): start: Peer ID: 34:FC:EF:11:AE:67, peer name: LGE-Nexus 5_PT2713
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3300): bind: Binding a new listener
,D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3300): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3300): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT2713","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3300): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): start: OK
I/io.jxcore.node.ConnectionHelper( 3300): start: Using peer discovery mode: WIFI
,D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): start: Peer ID: 34:FC:EF:11:AE:67, peer name: LGE-Nexus 5_PT2713
,D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3300): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT2713","ra":"34:FC:EF:11:AE:67"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3300): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT2713","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3300): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT2713","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3300): start: OK
I/jxcore-log( 3300): StartBroadcasting started ok
I/jxcore-log( 3300): 
I/jxcore-log( 3300): null
I/jxcore-log( 3300): 
I/jxcore-log( 3300): 2015-12-19T01:36:58.621Z SendDataTCPServer.js: TCP/IP server is bound to port: 34900
I/jxcore-log( 3300): 
I/chromium( 3300): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
I/io.jxcore.node.ConnectionHelper( 3300): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3300): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3300): onDiscoveryManagerStateChanged: RUNNING
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1034): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/WifiP2pManager( 3300): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1034): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): restart: Restarting...
,D/WifiP2pManager( 3300): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): restart: Restarting...
,D/WifiP2pManager( 3300): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): restart: Restarting...
,W/bt-btif ( 2107): info:x10
,D/        ( 2107): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
E/BluetoothRemoteDevices( 2107): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 2107): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 1
E/bt-btif ( 2107): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2107): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2107): Entering PendingCommandState State
,W/BluetoothEventManager( 2714): CachedBluetoothDevice for device 7C:F9:0E:37:96:AB not found, calling readPairedDevices().
,E/BluetoothEventManager( 2714): Got bonding state changed for 7C:F9:0E:37:96:AB, but we have no record of that device.
,I/BluetoothBondStateMachine( 2107): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 0
,D/BluetoothAdapterProperties( 2107): Failed to remove device: 7C:F9:0E:37:96:AB
,I/BluetoothBondStateMachine( 2107): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 11 NewState: 10
,W/BluetoothEventManager( 2714): CachedBluetoothDevice for device 7C:F9:0E:37:96:AB not found, calling readPairedDevices().
,E/BluetoothEventManager( 2714): Got bonding state changed for 7C:F9:0E:37:96:AB, but we have no record of that device.
,I/BluetoothBondStateMachine( 2107): StableState(): Entering Off State
,W/bt-btif ( 2107): new conn_srvc id:26, app_id:255
W/bt-btif ( 2107): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2107): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): Incoming connection accepted
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): Incoming connection initialized (thread ID: 314)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3300): Entering thread (ID: 314)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): onBytesRead: Read 83 bytes successfully (thread ID: 314)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): Got valid identity from [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): onBytesWritten: 77 bytes successfully written (thread ID: 314)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): removeThreadFromList: Removing thread with ID 314
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): Handshake thread disposed (thread ID: 314)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): onIncomingConnectionConnected: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): onConnected: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317]
I/io.jxcore.node.ConnectionHelper( 3300): onConnected: Incoming connection to peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317]
D/io.jxcore.node.ConnectionHelper( 3300): hasConnection: No connection with peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 3300): notifyPeerAvailability: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317] is available
,I/jxcore-log( 3300): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:37:96:AB","peerName":"samsung-SM-A500FU_PT4317","peerAvailable":true}]
I/jxcore-log( 3300): 
I/jxcore-log( 3300): Found peer : samsung-SM-A500FU_PT4317, Available: true
I/jxcore-log( 3300): 
I/jxcore-log( 3300): startWithNextDevice
I/jxcore-log( 3300): 
I/jxcore-log( 3300): device[1]: 7C:F9:0E:37:96:AB
I/jxcore-log( 3300): 
I/jxcore-log( 3300): 2015-12-19T01:37:42.532Z SendDataConnector.js: Start called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:37:42.540Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
,I/jxcore-log( 3300): 
I/jxcore-log( 3300): 2015-12-19T01:37:42.542Z SendDataConnector.js: do connect now
I/jxcore-log( 3300): 
,I/io.jxcore.node.ConnectionHelper( 3300): connect: Trying to connect to peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 3300): hasConnection: No connection with peer with ID 7C:F9:0E:37:96:AB
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): connect: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): connect: Trying to start connecting to A5-1 in address 7C:F9:0E:37:96:AB
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): onConnecting: A5-1 7C:F9:0E:37:96:AB
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): connect: Started connecting to A5-1 in address 7C:F9:0E:37:96:AB
I/io.jxcore.node.ConnectionHelper( 3300): connect: Connection process successfully started (peer ID: 7C:F9:0E:37:96:AB)
I/io.jxcore.node.ConnectionHelper( 3300): onConnected: Incoming socket thread, for peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317], created successfully
D/io.jxcore.node.ConnectionHelper( 3300): onConnected: The total number of connections is now 1
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3300): Exiting thread (ID: 314)
,D/io.jxcore.node.IncomingSocketThread( 3300): Entering thread (ID: 316)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): Trying to connect to peer with address 7C:F9:0E:37:96:AB (thread ID: 315)
W/BluetoothAdapter( 3300): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2107): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/jxcore-log( 3300): 2015-12-19T01:37:42.564Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3300): 
,I/io.jxcore.node.IncomingSocketThread( 3300): Local host address: localhost/127.0.0.1, port: 34900
D/io.jxcore.node.IncomingSocketThread( 3300): Setting local streams and starting stream copying threads...
,I/io.jxcore.node.StreamCopyingThread( 3300): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3300): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3300): startStreamCopyingThreads: OK
,D/io.jxcore.node.IncomingSocketThread( 3300): Exiting thread (ID: 316)
,D/io.jxcore.node.StreamCopyingThread( 3300): Entering thread (ID: 318, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3300): Entering thread (ID: 317, name: Sender)
,W/bt-sdp  ( 2107): process_service_search_attr_rsp
,W/bt-btif ( 2107): new conn_srvc id:26, app_id:1
W/bt-btif ( 2107): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2107): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2107): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): onSocketConnected: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 315)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): onBytesWritten: 77 bytes successfully written (thread ID: 319)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): Outgoing connection initialized (*handshake* thread ID: 319)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): Exiting thread (thread ID: 315)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3300): Entering thread (ID: 319)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): onBytesRead: Read 83 bytes successfully (thread ID: 319)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): Handshake succeeded with [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): onHandshakeSucceeded: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3300): Exiting thread (ID: 319)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): onConnected: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317]
,I/io.jxcore.node.ConnectionHelper( 3300): onConnected: Outgoing connection to peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317]
D/io.jxcore.node.ConnectionHelper( 3300): hasConnection: We have an incoming connection with peer with ID 7C:F9:0E:37:96:AB
,W/io.jxcore.node.ConnectionHelper( 3300): onConnected: Already connected with peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317], continuing anyway...
,W/io.jxcore.node.ConnectionHelper( 3300): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 3300): onConnected: Outgoing socket thread, for peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 3300): onConnected: The total number of connections is now 2
,D/io.jxcore.node.OutgoingSocketThread( 3300): Entering thread (ID: 320)
,D/io.jxcore.node.OutgoingSocketThread( 3300): Server socket local port: 49714
,I/io.jxcore.node.OutgoingSocketThread( 3300): Now accepting connections...
,D/WifiP2pManager( 3300): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,I/io.jxcore.node.ConnectionHelper( 3300): onListeningForIncomingConnections: Outgoing connection is using port 49714 (peer ID: 7C:F9:0E:37:96:AB)
,I/jxcore-log( 3300): 2015-12-19T01:37:43.284Z SendDataConnector.js: CLIENT connected to 49714, error: null
I/jxcore-log( 3300): 
I/jxcore-log( 3300): 2015-12-19T01:37:43.285Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3300): 
,I/io.jxcore.node.OutgoingSocketThread( 3300): Incoming data from address: /127.0.0.1, port: 49714
,D/io.jxcore.node.OutgoingSocketThread( 3300): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3300): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 3300): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.OutgoingSocketThread( 3300): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3300): Exiting thread (ID: 320)
,I/jxcore-log( 3300): 2015-12-19T01:37:43.307Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:37:43.307Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3300): 
,D/io.jxcore.node.StreamCopyingThread( 3300): Entering thread (ID: 322, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3300): Entering thread (ID: 321, name: Sender)
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3300): 2015-12-19T01:37:43.729Z SendDataTCPServer.js: TCP/IP server has received 37620 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:37:43.809Z SendDataTCPServer.js: TCP/IP server has received 39600 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:37:43.848Z SendDataTCPServer.js: TCP/IP server has received 41580 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:37:43.877Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:37:43.914Z SendDataTCPServer.js: TCP/IP server has received 45540 bytes of data
I/jxcore-log( 3300): 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3300): 2015-12-19T01:37:43.968Z SendDataTCPServer.js: TCP/IP server has received 47520 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:37:43.979Z SendDataTCPServer.js: TCP/IP server has received 49500 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:37:44.024Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:37:44.076Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 3300): 
,D/        ( 2107): PORT_WriteDataCO: tx queue is full,tx.queue_size:10172,tx.queue.count:11,available:24706
,I/jxcore-log( 3300): 2015-12-19T01:37:44.143Z SendDataTCPServer.js: TCP/IP server has received 55440 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:37:44.160Z SendDataTCPServer.js: TCP/IP server has received 57420 bytes of data,
I/jxcore-log( 3300): 
I/jxcore-log( 3300): 2015-12-19T01:37:44.165Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:37:44.215Z SendDataTCPServer.js: TCP/IP server has received 59400 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:37:44.249Z SendDataTCPServer.js: TCP/IP server has received 61380 bytes of data
I/jxcore-log( 3300): 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3300): 2015-12-19T01:37:44.299Z SendDataTCPServer.js: TCP/IP server has received 63360 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:37:44.379Z SendDataTCPServer.js: TCP/IP server has received 65340 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:37:44.454Z SendDataTCPServer.js: TCP/IP server has received 67320 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:37:44.470Z SendDataTCPServer.js: TCP/IP server has received 71280 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:37:44.480Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:37:44.487Z SendDataTCPServer.js: TCP/IP server has received 73260 bytes of data
I/jxcore-log( 3300): 
,D/        ( 2107): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:14806
,I/jxcore-log( 3300): 2015-12-19T01:37:44.526Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:37:44.533Z SendDataTCPServer.js: TCP/IP server has received 81180 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:37:44.542Z SendDataTCPServer.js: TCP/IP server has received 85140 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:37:44.623Z SendDataTCPServer.js: TCP/IP server has received 87120 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:37:44.645Z SendDataTCPServer.js: TCP/IP server has received 89100 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:37:44.655Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:37:44.683Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:37:44.689Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:37:44.721Z SendDataTCPServer.js: TCP/IP server has received 97020 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:37:44.757Z SendDataTCPServer.js: TCP/IP server has received 99000 bytes of data
I/jxcore-log( 3300): 
,D/        ( 2107): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:2926
,I/jxcore-log( 3300): 2015-12-19T01:37:44.771Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:37:44.788Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3300): 
,W/bt-btif ( 2107): invalid rfc slot id: 4
,W/io.jxcore.node.StreamCopyingThread( 3300): Either failed to read from the output stream or write to the input stream (thread ID: 318, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 3300): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3300): onDisconnected: Incoming connection, peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 316
D/io.jxcore.node.OutgoingSocketThread( 3300): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3300): doStop: Thread ID: 318
D/io.jxcore.node.OutgoingSocketThread( 3300): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3300): doStop: Thread ID: 317
D/io.jxcore.node.OutgoingSocketThread( 3300): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 3300): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3300): Either failed to read from the output stream or write to the input stream (thread ID: 317, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3300): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3300): onDisconnected: Incoming connection, peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 3300): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 3300): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3300): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.StreamCopyingThread( 3300): Exiting thread (ID: 317, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 3300): Exiting thread (ID: 318, name: Receiver)
,I/jxcore-log( 3300): 2015-12-19T01:37:44.873Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:37:44.875Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:37:45.005Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:37:45.134Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3300): 
I/jxcore-log( 3300): 2015-12-19T01:37:45.135Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): oneRoundDownNow
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:37:45.144Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3300): 
I/jxcore-log( 3300): 2015-12-19T01:37:45.145Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3300): 
,D/io.jxcore.node.ConnectionHelper( 3300): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:37:96:AB
I/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 7C:F9:0E:37:96:AB
I/io.jxcore.node.OutgoingSocketThread( 3300): close
D/io.jxcore.node.OutgoingSocketThread( 3300): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3300): doStop: Thread ID: 322
D/io.jxcore.node.OutgoingSocketThread( 3300): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3300): doStop: Thread ID: 321
D/io.jxcore.node.OutgoingSocketThread( 3300): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 3300): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3300): Either failed to read from the output stream or write to the input stream (thread ID: 321, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3300): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3300): onDisconnected: Outgoing connection, peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 3300): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 3300): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3300): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3300): Either failed to read from the output stream or write to the input stream (thread ID: 322, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 3300): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3300): onDisconnected: Outgoing connection, peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3300): disconnectOutgoingConnection: Successfully disconnected (peer ID: 7C:F9:0E:37:96:AB
,E/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:37:96:AB
,D/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3300): Exiting thread (ID: 321, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3300): Exiting thread (ID: 322, name: Receiver)
,I/jxcore-log( 3300): 2015-12-19T01:37:45.184Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3300): 
I/jxcore-log( 3300): ---- round done--------
I/jxcore-log( 3300): 
I/jxcore-log( 3300): startWithNextDevice
I/jxcore-log( 3300): 
,W/bt-btif ( 2107): bta_jv_rfc_port_to_cb(port_handle:0x9):jv handle:0x0 not FOUND
,D/btif_config_util( 2107): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2107): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2107): onReceive
,D/BluetoothManagerService(  758): Message: 20
D/BluetoothManagerService(  758): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f5a52e5:true
,I/BTConnectionReceiver( 1456): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1456): Bluetooth Device Name: A5-1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT317","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT317]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT317]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT317]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT317], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT317]
I/io.jxcore.node.ConnectionHelper( 3300): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT317], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
D/io.jxcore.node.ConnectionHelper( 3300): notifyPeerAvailability: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT317] is available
I/jxcore-log( 3300): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:85:54","peerName":"LGE-LG-D722_PT317","peerAvailable":true}]
I/jxcore-log( 3300): 
I/jxcore-log( 3300): Found peer : LGE-LG-D722_PT317, Available: true
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): startWithNextDevice
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): device[2]: F8:95:C7:87:85:54
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:37:50.869Z SendDataConnector.js: Start called with peer F8:95:C7:87:85:54
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:37:50.872Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3300): 
I/jxcore-log( 3300): 2015-12-19T01:37:50.873Z SendDataConnector.js: do connect now
I/jxcore-log( 3300): 
I/io.jxcore.node.ConnectionHelper( 3300): connect: Trying to connect to peer with ID F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 3300): hasConnection: No connection with peer with ID F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): connect: [F8:95:C7:87:85:54 LGE-LG-D722_PT317]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): connect: Trying to start connecting to null in address F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): onConnecting: null F8:95:C7:87:85:54
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): connect: Started connecting to null in address F8:95:C7:87:85:54
I/io.jxcore.node.ConnectionHelper( 3300): connect: Connection process successfully started (peer ID: F8:95:C7:87:85:54)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): Trying to connect to peer with address F8:95:C7:87:85:54 (thread ID: 323)
W/BluetoothAdapter( 3300): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2107): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2107): info:x10
,D/        ( 2107): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,E/BluetoothRemoteDevices( 2107): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2107): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2107): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1
E/bt-btif ( 2107): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2107): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2107): Entering PendingCommandState State
,W/BluetoothEventManager( 2714): CachedBluetoothDevice for device F8:95:C7:87:85:54 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2714): Got bonding state changed for F8:95:C7:87:85:54, but we have no record of that device.
,I/BluetoothBondStateMachine( 2107): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
,D/BluetoothAdapterProperties( 2107): Failed to remove device: F8:95:C7:87:85:54
,I/BluetoothBondStateMachine( 2107): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2107): StableState(): Entering Off State
,W/BluetoothEventManager( 2714): CachedBluetoothDevice for device F8:95:C7:87:85:54 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2714): Got bonding state changed for F8:95:C7:87:85:54, but we have no record of that device.
,W/bt-btif ( 2107): new conn_srvc id:26, app_id:1
W/bt-btif ( 2107): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2107): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): onSocketConnected: [F8:95:C7:87:85:54 LGE-LG-D722_PT317]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 323)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): onBytesWritten: 77 bytes successfully written (thread ID: 324)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): Outgoing connection initialized (*handshake* thread ID: 324)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): Exiting thread (thread ID: 323)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3300): Entering thread (ID: 324)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): onBytesRead: Read 76 bytes successfully (thread ID: 324)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): Handshake succeeded with [F8:95:C7:87:85:54 LGE-LG-D722_PT317]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): onHandshakeSucceeded: [F8:95:C7:87:85:54 LGE-LG-D722_PT317]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3300): Exiting thread (ID: 324)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): onConnected: [F8:95:C7:87:85:54 LGE-LG-D722_PT317]
I/io.jxcore.node.ConnectionHelper( 3300): onConnected: Outgoing connection to peer [F8:95:C7:87:85:54 LGE-LG-D722_PT317]
,D/io.jxcore.node.ConnectionHelper( 3300): hasConnection: No connection with peer with ID F8:95:C7:87:85:54
W/io.jxcore.node.ConnectionHelper( 3300): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT317] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 3300): onConnected: Outgoing socket thread, for peer [F8:95:C7:87:85:54 LGE-LG-D722_PT317], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 3300): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 3300): Entering thread (ID: 325)
,D/io.jxcore.node.OutgoingSocketThread( 3300): Server socket local port: 54956
I/io.jxcore.node.OutgoingSocketThread( 3300): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3300): onListeningForIncomingConnections: Outgoing connection is using port 54956 (peer ID: F8:95:C7:87:85:54)
,I/jxcore-log( 3300): 2015-12-19T01:37:53.357Z SendDataConnector.js: CLIENT connected to 54956, error: null
I/jxcore-log( 3300): 
I/jxcore-log( 3300): 2015-12-19T01:37:53.362Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3300): 
,W/bt-btif ( 2107): new conn_srvc id:26, app_id:255
W/bt-btif ( 2107): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2107): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2107): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): Incoming connection initialized (thread ID: 326)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): Waiting for incoming connections...
,I/io.jxcore.node.OutgoingSocketThread( 3300): Incoming data from address: /127.0.0.1, port: 54956
D/io.jxcore.node.OutgoingSocketThread( 3300): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3300): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3300): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3300): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3300): Exiting thread (ID: 325)
,I/jxcore-log( 3300): 2015-12-19T01:37:53.424Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3300): 
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3300): Entering thread (ID: 326)
,D/io.jxcore.node.StreamCopyingThread( 3300): Entering thread (ID: 328, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3300): Entering thread (ID: 327, name: Sender)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): onBytesRead: Read 76 bytes successfully (thread ID: 326)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): Got valid identity from [F8:95:C7:87:85:54 LGE-LG-D722_PT317]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): onBytesWritten: 77 bytes successfully written (thread ID: 326)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): removeThreadFromList: Removing thread with ID 326
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): Handshake thread disposed (thread ID: 326)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): onIncomingConnectionConnected: [F8:95:C7:87:85:54 LGE-LG-D722_PT317]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3300): Exiting thread (ID: 326)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): onConnected: [F8:95:C7:87:85:54 LGE-LG-D722_PT317]
I/io.jxcore.node.ConnectionHelper( 3300): onConnected: Incoming connection to peer [F8:95:C7:87:85:54 LGE-LG-D722_PT317]
,D/io.jxcore.node.ConnectionHelper( 3300): hasConnection: We have an outgoing connection with peer with ID F8:95:C7:87:85:54
W/io.jxcore.node.ConnectionHelper( 3300): onConnected: Already connected with peer [F8:95:C7:87:85:54 LGE-LG-D722_PT317], continuing anyway...
W/io.jxcore.node.ConnectionHelper( 3300): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT317] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 3300): onConnected: Incoming socket thread, for peer [F8:95:C7:87:85:54 LGE-LG-D722_PT317], created successfully
D/io.jxcore.node.ConnectionHelper( 3300): onConnected: The total number of connections is now 2
D/io.jxcore.node.IncomingSocketThread( 3300): Entering thread (ID: 329)
,I/io.jxcore.node.IncomingSocketThread( 3300): Local host address: localhost/127.0.0.1, port: 34900
,D/io.jxcore.node.IncomingSocketThread( 3300): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3300): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3300): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.IncomingSocketThread( 3300): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3300): Exiting thread (ID: 329)
,I/jxcore-log( 3300): 2015-12-19T01:37:53.908Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3300): 
,D/io.jxcore.node.StreamCopyingThread( 3300): Entering thread (ID: 330, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 3300): Entering thread (ID: 331, name: Receiver)
,I/jxcore-log( 3300): 2015-12-19T01:37:54.773Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:37:54.781Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:37:54.789Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:37:54.793Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:37:54.862Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:37:54.917Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:37:54.946Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:37:55.010Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:37:55.070Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:37:55.077Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:37:55.088Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3300): 
I/jxcore-log( 3300): 2015-12-19T01:37:55.089Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3300): 
I/jxcore-log( 3300): oneRoundDownNow
I/jxcore-log( 3300): 
I/jxcore-log( 3300): 2015-12-19T01:37:55.091Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3300): 
I/jxcore-log( 3300): 2015-12-19T01:37:55.091Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3300): 
D/io.jxcore.node.ConnectionHelper( 3300): disconnectOutgoingConnection: Trying to close connection to peer with ID F8:95:C7:87:85:54
I/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: F8:95:C7:87:85:54
I/io.jxcore.node.IncomingSocketThread( 3300): close
D/io.jxcore.node.IncomingSocketThread( 3300): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3300): doStop: Thread ID: 328
D/io.jxcore.node.IncomingSocketThread( 3300): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3300): doStop: Thread ID: 327
D/io.jxcore.node.IncomingSocketThread( 3300): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 3300): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3300): Either failed to read from the output stream or write to the input stream (thread ID: 327, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3300): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3300): onDisconnected: Outgoing connection, peer [F8:95:C7:87:85:54 LGE-LG-D722_PT317] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.IncomingSocketThread( 3300): closeLocalSocketAndStreams: Closing the local output stream...
,D/io.jxcore.node.IncomingSocketThread( 3300): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3300): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3300): Either failed to read from the output stream or write to the input stream (thread ID: 328, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 3300): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3300): onDisconnected: Outgoing connection, peer [F8:95:C7:87:85:54 LGE-LG-D722_PT317] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
D/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3300): disconnectOutgoingConnection: Successfully disconnected (peer ID: F8:95:C7:87:85:54
,E/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3300): Exiting thread (ID: 327, name: Sender)
E/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3300): Exiting thread (ID: 328, name: Receiver)
,I/jxcore-log( 3300): 2015-12-19T01:37:55.116Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): ---- round done--------
I/jxcore-log( 3300): 
I/jxcore-log( 3300): startWithNextDevice
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:37:55.120Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:37:55.148Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:37:55.176Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:37:55.241Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:37:55.741Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:37:55.780Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3300): 
,W/bt-btif ( 2107): bta_jv_rfc_port_to_cb(port_handle:0xa):jv handle:0x0 not FOUND
,I/jxcore-log( 3300): 2015-12-19T01:37:55.823Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:37:55.831Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:37:55.846Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:37:55.934Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:37:55.965Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:37:55.986Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:37:55.997Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:37:56.005Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:37:56.041Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:37:56.059Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:37:56.115Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:37:56.143Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:37:56.175Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:37:56.286Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:37:56.300Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:37:56.331Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:37:56.344Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3300): 
,E/bt-btm  ( 2107): tBTM_SEC_DEV:0xa3e51084 rs_disc_pending=0
,W/bt-btif ( 2107): bta_dm_check_av:0
,W/bt-btif ( 2107): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2107): invalid rfc slot id: 5
,W/io.jxcore.node.StreamCopyingThread( 3300): Either failed to read from the output stream or write to the input stream (thread ID: 331, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.IncomingSocketThread( 3300): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3300): onDisconnected: Incoming connection, peer [F8:95:C7:87:85:54 LGE-LG-D722_PT317] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 329
D/io.jxcore.node.IncomingSocketThread( 3300): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3300): doStop: Thread ID: 331
D/io.jxcore.node.IncomingSocketThread( 3300): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3300): doStop: Thread ID: 330
D/io.jxcore.node.IncomingSocketThread( 3300): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 3300): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3300): Either failed to read from the output stream or write to the input stream (thread ID: 330, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3300): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3300): onDisconnected: Incoming connection, peer [F8:95:C7:87:85:54 LGE-LG-D722_PT317] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.IncomingSocketThread( 3300): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 3300): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3300): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3300): Exiting thread (ID: 331, name: Receiver)
,D/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3300): Exiting thread (ID: 330, name: Sender)
,I/jxcore-log( 3300): 2015-12-19T01:37:57.148Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3300): 
,D/btif_config_util( 2107): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2107): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2107): onReceive
,I/BTConnectionReceiver( 1456): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1456): Bluetooth Device Name: G3s-1
,I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT317], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT317]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT317], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT317]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3300): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT9642","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642]
I/io.jxcore.node.ConnectionHelper( 3300): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: , device address: ee:1f:72:63:11:86
D/io.jxcore.node.ConnectionHelper( 3300): notifyPeerAvailability: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642] is available
I/jxcore-log( 3300): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:34:8A:A0","peerName":"samsung-SM-G900F_PT9642","peerAvailable":true}]
I/jxcore-log( 3300): 
I/jxcore-log( 3300): Found peer : samsung-SM-G900F_PT9642, Available: true
I/jxcore-log( 3300): 
I/jxcore-log( 3300): startWithNextDevice
I/jxcore-log( 3300): 
I/jxcore-log( 3300): device[3]: 7C:F9:0E:34:8A:A0
I/jxcore-log( 3300): 
I/jxcore-log( 3300): 2015-12-19T01:38:15.076Z SendDataConnector.js: Start called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3300): 
I/jxcore-log( 3300): 2015-12-19T01:38:15.077Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:38:15.085Z SendDataConnector.js: do connect now
I/jxcore-log( 3300): 
,I/io.jxcore.node.ConnectionHelper( 3300): connect: Trying to connect to peer with ID 7C:F9:0E:34:8A:A0
D/io.jxcore.node.ConnectionHelper( 3300): hasConnection: No connection with peer with ID 7C:F9:0E:34:8A:A0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): connect: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): connect: Trying to start connecting to null in address 7C:F9:0E:34:8A:A0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): setInsecureRfcommSocketPort: Using port -1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): setMaxNumberOfRetries: 0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): onConnecting: null 7C:F9:0E:34:8A:A0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): connect: Started connecting to null in address 7C:F9:0E:34:8A:A0
I/io.jxcore.node.ConnectionHelper( 3300): connect: Connection process successfully started (peer ID: 7C:F9:0E:34:8A:A0)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): Trying to connect to peer with address 7C:F9:0E:34:8A:A0 (thread ID: 332)
,W/BluetoothAdapter( 3300): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 2107): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9326","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
I/io.jxcore.node.ConnectionHelper( 3300): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
D/io.jxcore.node.ConnectionHelper( 3300): notifyPeerAvailability: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326] is available
,I/jxcore-log( 3300): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:3C:51","peerName":"LGE-LG-H815_PT9326","peerAvailable":true}]
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): Found peer : LGE-LG-H815_PT9326, Available: true
I/jxcore-log( 3300): 
,W/bt-btif ( 2107): info:x10
,D/        ( 2107): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,E/BluetoothRemoteDevices( 2107): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2107): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2107): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 1
E/bt-btif ( 2107): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2107): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2107): Entering PendingCommandState State
,W/BluetoothEventManager( 2714): CachedBluetoothDevice for device 7C:F9:0E:34:8A:A0 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2714): Got bonding state changed for 7C:F9:0E:34:8A:A0, but we have no record of that device.
,I/BluetoothBondStateMachine( 2107): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 0
,D/BluetoothAdapterProperties( 2107): Failed to remove device: 7C:F9:0E:34:8A:A0
,I/BluetoothBondStateMachine( 2107): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2107): StableState(): Entering Off State
,W/BluetoothEventManager( 2714): CachedBluetoothDevice for device 7C:F9:0E:34:8A:A0 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2714): Got bonding state changed for 7C:F9:0E:34:8A:A0, but we have no record of that device.
,W/bt-btif ( 2107): new conn_srvc id:26, app_id:1
W/bt-btif ( 2107): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2107): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): onSocketConnected: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 332)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): onBytesWritten: 77 bytes successfully written (thread ID: 333)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): Outgoing connection initialized (*handshake* thread ID: 333)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): Exiting thread (thread ID: 332)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3300): Entering thread (ID: 333)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): onBytesRead: Read 82 bytes successfully (thread ID: 333)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): Handshake succeeded with [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): onHandshakeSucceeded: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3300): Exiting thread (ID: 333)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): onConnected: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642]
I/io.jxcore.node.ConnectionHelper( 3300): onConnected: Outgoing connection to peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642]
,D/io.jxcore.node.ConnectionHelper( 3300): hasConnection: No connection with peer with ID 7C:F9:0E:34:8A:A0
W/io.jxcore.node.ConnectionHelper( 3300): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 3300): onConnected: Outgoing socket thread, for peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 3300): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 3300): Entering thread (ID: 334)
,D/io.jxcore.node.OutgoingSocketThread( 3300): Server socket local port: 41171
I/io.jxcore.node.OutgoingSocketThread( 3300): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3300): onListeningForIncomingConnections: Outgoing connection is using port 41171 (peer ID: 7C:F9:0E:34:8A:A0)
I/jxcore-log( 3300): 2015-12-19T01:38:19.846Z SendDataConnector.js: CLIENT connected to 41171, error: null
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:38:19.847Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3300): 
,I/io.jxcore.node.OutgoingSocketThread( 3300): Incoming data from address: /127.0.0.1, port: 41171
D/io.jxcore.node.OutgoingSocketThread( 3300): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3300): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3300): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3300): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3300): Exiting thread (ID: 334)
,I/jxcore-log( 3300): 2015-12-19T01:38:19.897Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3300): 
,D/io.jxcore.node.StreamCopyingThread( 3300): Entering thread (ID: 335, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 3300): Entering thread (ID: 336, name: Receiver)
,I/jxcore-log( 3300): 2015-12-19T01:38:20.498Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:38:20.577Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:38:20.597Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:38:21.182Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:38:21.796Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:38:22.326Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:38:22.670Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3300): 
,D/btif_config_util( 2107): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3300): 2015-12-19T01:38:23.669Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:38:24.237Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:38:24.517Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:38:24.520Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3300): 
I/jxcore-log( 3300): oneRoundDownNow
I/jxcore-log( 3300): 
I/jxcore-log( 3300): 2015-12-19T01:38:24.522Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3300): 
I/jxcore-log( 3300): 2015-12-19T01:38:24.523Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3300): 
D/io.jxcore.node.ConnectionHelper( 3300): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:34:8A:A0
I/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 7C:F9:0E:34:8A:A0
I/io.jxcore.node.OutgoingSocketThread( 3300): close
D/io.jxcore.node.OutgoingSocketThread( 3300): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3300): doStop: Thread ID: 336
,D/io.jxcore.node.OutgoingSocketThread( 3300): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3300): doStop: Thread ID: 335
D/io.jxcore.node.OutgoingSocketThread( 3300): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 3300): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3300): Either failed to read from the output stream or write to the input stream (thread ID: 335, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3300): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3300): onDisconnected: Outgoing connection, peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 3300): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 3300): closeLocalSocketAndStreams: Closing the localhost socket...
,I/io.jxcore.node.OutgoingSocketThread( 3300): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3300): Either failed to read from the output stream or write to the input stream (thread ID: 336, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.OutgoingSocketThread( 3300): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3300): onDisconnected: Outgoing connection, peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3300): disconnectOutgoingConnection: Successfully disconnected (peer ID: 7C:F9:0E:34:8A:A0
,E/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:34:8A:A0
D/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,E/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:34:8A:A0
D/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3300): Exiting thread (ID: 336, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3300): Exiting thread (ID: 335, name: Sender)
,I/jxcore-log( 3300): 2015-12-19T01:38:24.569Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): ---- round done--------
I/jxcore-log( 3300): 
I/jxcore-log( 3300): startWithNextDevice
I/jxcore-log( 3300): 
I/jxcore-log( 3300): device[4]: F8:95:C7:87:3C:51
I/jxcore-log( 3300): 
I/jxcore-log( 3300): 2015-12-19T01:38:24.572Z SendDataConnector.js: Start called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3300): 
I/jxcore-log( 3300): 2015-12-19T01:38:24.573Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3300): 
I/jxcore-log( 3300): 2015-12-19T01:38:24.573Z SendDataConnector.js: do connect now
I/jxcore-log( 3300): 
I/io.jxcore.node.ConnectionHelper( 3300): connect: Trying to connect to peer with ID F8:95:C7:87:3C:51
D/io.jxcore.node.ConnectionHelper( 3300): hasConnection: No connection with peer with ID F8:95:C7:87:3C:51
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): connect: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): connect: Trying to start connecting to null in address F8:95:C7:87:3C:51
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): setMaxNumberOfRetries: 0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): onConnecting: null F8:95:C7:87:3C:51
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): connect: Started connecting to null in address F8:95:C7:87:3C:51
I/io.jxcore.node.ConnectionHelper( 3300): connect: Connection process successfully started (peer ID: F8:95:C7:87:3C:51)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): Trying to connect to peer with address F8:95:C7:87:3C:51 (thread ID: 337)
W/BluetoothAdapter( 3300): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2107): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2107): bta_jv_rfc_port_to_cb(port_handle:0xc):jv handle:0x0 not FOUND
,E/bt-btm  ( 2107): tBTM_SEC_DEV:0xa3e5124c rs_disc_pending=1
W/bt-btif ( 2107): bta_dm_check_av:0
,W/bt-btif ( 2107): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2107): info:x10
,D/        ( 2107): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,E/BluetoothRemoteDevices( 2107): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2107): tBTM_SEC_DEV:0xa3e51414 rs_disc_pending=1
W/bt-btif ( 2107): bta_dm_check_av:0
,W/bt-btif ( 2107): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 2107): process_service_search_attr_rsp
,E/bt-btm  ( 2107): tBTM_SEC_DEV:0xa3e5124c rs_disc_pending=0
W/bt-btif ( 2107): bta_dm_check_av:0
,W/bt-btif ( 2107): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 2107): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
E/bt-btif ( 2107): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2107): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2107): Entering PendingCommandState State
,W/BluetoothEventManager( 2714): CachedBluetoothDevice for device F8:95:C7:87:3C:51 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2714): Got bonding state changed for F8:95:C7:87:3C:51, but we have no record of that device.
,I/BluetoothBondStateMachine( 2107): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,D/BluetoothAdapterProperties( 2107): Failed to remove device: F8:95:C7:87:3C:51
,I/BluetoothBondStateMachine( 2107): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2107): StableState(): Entering Off State
,W/BluetoothEventManager( 2714): CachedBluetoothDevice for device F8:95:C7:87:3C:51 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2714): Got bonding state changed for F8:95:C7:87:3C:51, but we have no record of that device.
,E/bt-btm  ( 2107): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2107): onReceive
,I/BTConnectionReceiver( 1456): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1456): Bluetooth Device Name: S5-1
,W/bt-btif ( 2107): new conn_srvc id:26, app_id:1
W/bt-btif ( 2107): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2107): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): onSocketConnected: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 337)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): onBytesWritten: 77 bytes successfully written (thread ID: 338)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): Outgoing connection initialized (*handshake* thread ID: 338)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): Exiting thread (thread ID: 337)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3300): Entering thread (ID: 338)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): onBytesRead: Read 77 bytes successfully (thread ID: 338)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): Handshake succeeded with [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): onHandshakeSucceeded: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3300): Exiting thread (ID: 338)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): onConnected: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
I/io.jxcore.node.ConnectionHelper( 3300): onConnected: Outgoing connection to peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
,D/io.jxcore.node.ConnectionHelper( 3300): hasConnection: No connection with peer with ID F8:95:C7:87:3C:51
W/io.jxcore.node.ConnectionHelper( 3300): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 3300): onConnected: Outgoing socket thread, for peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
,D/io.jxcore.node.ConnectionHelper( 3300): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 3300): Entering thread (ID: 339)
,D/io.jxcore.node.OutgoingSocketThread( 3300): Server socket local port: 48149
I/io.jxcore.node.OutgoingSocketThread( 3300): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3300): onListeningForIncomingConnections: Outgoing connection is using port 48149 (peer ID: F8:95:C7:87:3C:51)
I/jxcore-log( 3300): 2015-12-19T01:38:30.486Z SendDataConnector.js: CLIENT connected to 48149, error: null
I/jxcore-log( 3300): 
I/jxcore-log( 3300): 2015-12-19T01:38:30.487Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3300): 
,I/io.jxcore.node.OutgoingSocketThread( 3300): Incoming data from address: /127.0.0.1, port: 48149
D/io.jxcore.node.OutgoingSocketThread( 3300): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3300): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3300): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3300): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3300): Exiting thread (ID: 339)
,I/jxcore-log( 3300): 2015-12-19T01:38:30.510Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3300): 
,D/io.jxcore.node.StreamCopyingThread( 3300): Entering thread (ID: 340, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 3300): Entering thread (ID: 341, name: Receiver)
,I/jxcore-log( 3300): 2015-12-19T01:38:31.404Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:38:31.890Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:38:31.995Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:38:32.331Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:38:32.445Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:38:32.563Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3300): 
,D/btif_config_util( 2107): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3300): 2015-12-19T01:38:32.624Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:38:32.682Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:38:32.721Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:38:32.792Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3300): 
I/jxcore-log( 3300): 2015-12-19T01:38:32.793Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3300): 
I/jxcore-log( 3300): oneRoundDownNow
I/jxcore-log( 3300): 
I/jxcore-log( 3300): 2015-12-19T01:38:32.795Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3300): 
I/jxcore-log( 3300): 2015-12-19T01:38:32.795Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3300): 
,D/io.jxcore.node.ConnectionHelper( 3300): disconnectOutgoingConnection: Trying to close connection to peer with ID F8:95:C7:87:3C:51
I/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: F8:95:C7:87:3C:51
,I/io.jxcore.node.OutgoingSocketThread( 3300): close
D/io.jxcore.node.OutgoingSocketThread( 3300): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3300): doStop: Thread ID: 341
D/io.jxcore.node.OutgoingSocketThread( 3300): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3300): doStop: Thread ID: 340
D/io.jxcore.node.OutgoingSocketThread( 3300): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 3300): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3300): Either failed to read from the output stream or write to the input stream (thread ID: 340, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3300): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3300): onDisconnected: Outgoing connection, peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 3300): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 3300): closeLocalSocketAndStreams: Closing the localhost socket...
,I/io.jxcore.node.OutgoingSocketThread( 3300): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3300): Either failed to read from the output stream or write to the input stream (thread ID: 341, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.OutgoingSocketThread( 3300): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3300): onDisconnected: Outgoing connection, peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3300): disconnectOutgoingConnection: Successfully disconnected (peer ID: F8:95:C7:87:3C:51
,E/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:95:C7:87:3C:51
D/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,E/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:95:C7:87:3C:51
D/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3300): Exiting thread (ID: 341, name: Receiver)
,W/bt-btif ( 2107): bta_jv_rfc_port_to_cb(port_handle:0xd):jv handle:0x0 not FOUND
,D/io.jxcore.node.StreamCopyingThread( 3300): Exiting thread (ID: 340, name: Sender)
,I/jxcore-log( 3300): 2015-12-19T01:38:32.843Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 3300): 
I/jxcore-log( 3300): ---- round done--------
I/jxcore-log( 3300): 
I/jxcore-log( 3300): startWithNextDevice
I/jxcore-log( 3300): 
,I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): restart: Restarting...
,D/WifiP2pManager( 3300): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,E/bt-btm  ( 2107): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2107): onReceive
,I/BTConnectionReceiver( 1456): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1456): Bluetooth Device Name: G4-1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT5261","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5261]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onServiceDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5261]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5261]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5261], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5261]
I/io.jxcore.node.ConnectionHelper( 3300): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5261], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
D/io.jxcore.node.ConnectionHelper( 3300): notifyPeerAvailability: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5261] is available
I/jxcore-log( 3300): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:76:27","peerName":"samsung-SM-A300FU_PT5261","peerAvailable":true}]
I/jxcore-log( 3300): 
I/jxcore-log( 3300): Found peer : samsung-SM-A300FU_PT5261, Available: true
I/jxcore-log( 3300): 
I/jxcore-log( 3300): startWithNextDevice
I/jxcore-log( 3300): 
I/jxcore-log( 3300): device[5]: 08:EC:A9:50:76:27
I/jxcore-log( 3300): 
I/jxcore-log( 3300): 2015-12-19T01:38:40.096Z SendDataConnector.js: Start called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3300): 
I/jxcore-log( 3300): 2015-12-19T01:38:40.096Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3300): 
I/jxcore-log( 3300): 2015-12-19T01:38:40.097Z SendDataConnector.js: do connect now
I/jxcore-log( 3300): 
,I/io.jxcore.node.ConnectionHelper( 3300): connect: Trying to connect to peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 3300): hasConnection: No connection with peer with ID 08:EC:A9:50:76:27
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): connect: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5261]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): connect: Trying to start connecting to null in address 08:EC:A9:50:76:27
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): onConnecting: null 08:EC:A9:50:76:27
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): connect: Started connecting to null in address 08:EC:A9:50:76:27
I/io.jxcore.node.ConnectionHelper( 3300): connect: Connection process successfully started (peer ID: 08:EC:A9:50:76:27)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): Trying to connect to peer with address 08:EC:A9:50:76:27 (thread ID: 342)
W/BluetoothAdapter( 3300): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2107): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2107): SDP - Rcvd conn cnf with error: 0x4  CID 0x4a
E/bt-btif ( 2107): DISCOVERY_COMP_EVT slot id:11, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2107): invalid rfc slot id: 11
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 342)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): Maximum number of allowed retries (0) reached, giving up... (thread ID: 342)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): Exiting thread (thread ID: 342)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5261]
,I/jxcore-log( 3300): 2015-12-19T01:38:45.284Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5261] failed
I/jxcore-log( 3300): 
I/jxcore-log( 3300): 2015-12-19T01:38:45.285Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5261] failed
I/jxcore-log( 3300): 
I/jxcore-log( 3300): 2015-12-19T01:38:45.287Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3300): 
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): shutdown (thread ID: 342)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): setInsecureRfcommSocketPort: Will use port 1 when trying to connect
,I/jxcore-log( 3300): 2015-12-19T01:38:50.300Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 3300): 
I/jxcore-log( 3300): 2015-12-19T01:38:50.302Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3300): 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5261], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5261]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): restart: Restarting...
,D/WifiP2pManager( 3300): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5261], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5261]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
,D/io.jxcore.node.ConnectionHelper( 3300): disconnectOutgoingConnection: Trying to close connection to peer with ID 08:EC:A9:50:76:27
E/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3300): disconnectOutgoingConnection: Failed to disconnect (peer ID: 08:EC:A9:50:76:27), either no such connection or failed to close the connection
,I/jxcore-log( 3300): 2015-12-19T01:38:55.313Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:38:55.315Z SendDataConnector.js: Connect (retry count 1) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:38:55.318Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:38:55.319Z SendDataConnector.js: do connect now
I/jxcore-log( 3300): 
,I/io.jxcore.node.ConnectionHelper( 3300): connect: Trying to connect to peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 3300): hasConnection: No connection with peer with ID 08:EC:A9:50:76:27
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): connect: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5261]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): connect: Trying to start connecting to null in address 08:EC:A9:50:76:27
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): setInsecureRfcommSocketPort: Using port 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): onConnecting: null 08:EC:A9:50:76:27
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): connect: Started connecting to null in address 08:EC:A9:50:76:27
I/io.jxcore.node.ConnectionHelper( 3300): connect: Connection process successfully started (peer ID: 08:EC:A9:50:76:27)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): Trying to connect to peer with address 08:EC:A9:50:76:27 (thread ID: 344)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3300): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3300): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2107): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2107): SDP - Rcvd conn cnf with error: 0x4  CID 0x4b
E/bt-btif ( 2107): DISCOVERY_COMP_EVT slot id:12, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2107): invalid rfc slot id: 12
W/BluetoothAdapter( 3300): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2107): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2107): SDP - Rcvd conn cnf with error: 0x4  CID 0x4c
E/bt-btif ( 2107): DISCOVERY_COMP_EVT slot id:13, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2107): invalid rfc slot id: 13
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 344)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): Maximum number of allowed retries (0) reached, giving up... (thread ID: 344)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): Exiting thread (thread ID: 344)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5261]
I/jxcore-log( 3300): 2015-12-19T01:39:05.635Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5261] failed
I/jxcore-log( 3300): 
I/jxcore-log( 3300): 2015-12-19T01:39:05.636Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5261] failed
I/jxcore-log( 3300): 
I/jxcore-log( 3300): 2015-12-19T01:39:05.637Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3300): 
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): shutdown (thread ID: 344)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
,I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5261], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5261]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5261], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5261]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
,D/WifiP2pManager( 3300): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3300): 2015-12-19T01:39:10.648Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 3300): 
I/jxcore-log( 3300): 2015-12-19T01:39:10.649Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3300): 
,D/io.jxcore.node.ConnectionHelper( 3300): disconnectOutgoingConnection: Trying to close connection to peer with ID 08:EC:A9:50:76:27
,E/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3300): disconnectOutgoingConnection: Failed to disconnect (peer ID: 08:EC:A9:50:76:27), either no such connection or failed to close the connection
I/jxcore-log( 3300): 2015-12-19T01:39:15.653Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 3300): 
I/jxcore-log( 3300): 2015-12-19T01:39:15.654Z SendDataConnector.js: Connect (retry count 2) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 3300): 
I/jxcore-log( 3300): 2015-12-19T01:39:15.654Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3300): 
I/jxcore-log( 3300): 2015-12-19T01:39:15.655Z SendDataConnector.js: do connect now
I/jxcore-log( 3300): 
I/io.jxcore.node.ConnectionHelper( 3300): connect: Trying to connect to peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 3300): hasConnection: No connection with peer with ID 08:EC:A9:50:76:27
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): connect: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5261]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): connect: Trying to start connecting to null in address 08:EC:A9:50:76:27
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): onConnecting: null 08:EC:A9:50:76:27
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): connect: Started connecting to null in address 08:EC:A9:50:76:27
I/io.jxcore.node.ConnectionHelper( 3300): connect: Connection process successfully started (peer ID: 08:EC:A9:50:76:27)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): Trying to connect to peer with address 08:EC:A9:50:76:27 (thread ID: 346)
W/BluetoothAdapter( 3300): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2107): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2107): info:x10
,D/        ( 2107): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2107): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2107): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2107): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:76:27 newState: 1
E/bt-btif ( 2107): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2107): Bond State Change Intent:08:EC:A9:50:76:27 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2107): Entering PendingCommandState State
,W/BluetoothEventManager( 2714): CachedBluetoothDevice for device 08:EC:A9:50:76:27 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2714): Got bonding state changed for 08:EC:A9:50:76:27, but we have no record of that device.
,I/BluetoothBondStateMachine( 2107): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:76:27 newState: 0
,D/BluetoothAdapterProperties( 2107): Failed to remove device: 08:EC:A9:50:76:27
,I/BluetoothBondStateMachine( 2107): Bond State Change Intent:08:EC:A9:50:76:27 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2107): StableState(): Entering Off State
,W/BluetoothEventManager( 2714): CachedBluetoothDevice for device 08:EC:A9:50:76:27 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2714): Got bonding state changed for 08:EC:A9:50:76:27, but we have no record of that device.
,W/bt-btif ( 2107): new conn_srvc id:26, app_id:1
W/bt-btif ( 2107): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2107): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): onSocketConnected: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5261]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 346)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): onBytesWritten: 77 bytes successfully written (thread ID: 347)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): Outgoing connection initialized (*handshake* thread ID: 347)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): Exiting thread (thread ID: 346)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3300): Entering thread (ID: 347)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): onBytesRead: Read 83 bytes successfully (thread ID: 347)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): Handshake succeeded with [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5261]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): onHandshakeSucceeded: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5261]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): onConnected: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5261]
I/io.jxcore.node.ConnectionHelper( 3300): onConnected: Outgoing connection to peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5261]
D/io.jxcore.node.ConnectionHelper( 3300): hasConnection: No connection with peer with ID 08:EC:A9:50:76:27
W/io.jxcore.node.ConnectionHelper( 3300): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5261] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 3300): onConnected: Outgoing socket thread, for peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5261], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 3300): onConnected: The total number of connections is now 1
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3300): Exiting thread (ID: 347)
,D/io.jxcore.node.OutgoingSocketThread( 3300): Entering thread (ID: 348)
D/io.jxcore.node.OutgoingSocketThread( 3300): Server socket local port: 33429
I/io.jxcore.node.OutgoingSocketThread( 3300): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3300): onListeningForIncomingConnections: Outgoing connection is using port 33429 (peer ID: 08:EC:A9:50:76:27)
I/jxcore-log( 3300): 2015-12-19T01:39:17.690Z SendDataConnector.js: CLIENT connected to 33429, error: null
I/jxcore-log( 3300): 
I/jxcore-log( 3300): 2015-12-19T01:39:17.690Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:39:17.692Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3300): 
,I/io.jxcore.node.OutgoingSocketThread( 3300): Incoming data from address: /127.0.0.1, port: 33429
D/io.jxcore.node.OutgoingSocketThread( 3300): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3300): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3300): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3300): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3300): Exiting thread (ID: 348)
,D/io.jxcore.node.StreamCopyingThread( 3300): Entering thread (ID: 349, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 3300): Entering thread (ID: 350, name: Receiver)
,D/        ( 2107): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23716
,I/jxcore-log( 3300): 2015-12-19T01:39:18.225Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:39:18.284Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3300): 
,D/        ( 2107): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:12826
,I/jxcore-log( 3300): 2015-12-19T01:39:18.571Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:39:19.274Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3300): 
,D/        ( 2107): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:2926
,I/jxcore-log( 3300): 2015-12-19T01:39:19.309Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:39:19.348Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:39:19.403Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:39:19.410Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:39:19.461Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:39:19.504Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3300): 
I/jxcore-log( 3300): 2015-12-19T01:39:19.505Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3300): 
I/jxcore-log( 3300): oneRoundDownNow
I/jxcore-log( 3300): 
I/jxcore-log( 3300): 2015-12-19T01:39:19.506Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3300): 
I/jxcore-log( 3300): 2015-12-19T01:39:19.507Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3300): 
,D/io.jxcore.node.ConnectionHelper( 3300): disconnectOutgoingConnection: Trying to close connection to peer with ID 08:EC:A9:50:76:27
I/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 08:EC:A9:50:76:27
I/io.jxcore.node.OutgoingSocketThread( 3300): close
D/io.jxcore.node.OutgoingSocketThread( 3300): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3300): doStop: Thread ID: 350
D/io.jxcore.node.OutgoingSocketThread( 3300): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3300): doStop: Thread ID: 349
D/io.jxcore.node.OutgoingSocketThread( 3300): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 3300): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3300): Either failed to read from the output stream or write to the input stream (thread ID: 349, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3300): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3300): onDisconnected: Outgoing connection, peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5261] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 3300): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 3300): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3300): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3300): Either failed to read from the output stream or write to the input stream (thread ID: 350, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.OutgoingSocketThread( 3300): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3300): onDisconnected: Outgoing connection, peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5261] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3300): disconnectOutgoingConnection: Successfully disconnected (peer ID: 08:EC:A9:50:76:27
,E/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,E/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3300): Exiting thread (ID: 350, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3300): Exiting thread (ID: 349, name: Sender)
,W/bt-btif ( 2107): bta_jv_rfc_port_to_cb(port_handle:0xe):jv handle:0x0 not FOUND
,I/jxcore-log( 3300): 2015-12-19T01:39:19.557Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 3300): 
I/jxcore-log( 3300): ---- round done--------
I/jxcore-log( 3300): 
I/jxcore-log( 3300): startWithNextDevice
I/jxcore-log( 3300): 
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): checkListForExpiredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642] expired
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): checkListForExpiredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT317] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Removed [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT317], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Removed [F8:95:C7:87:85:54 LGE-LG-D722_PT317]
I/io.jxcore.node.ConnectionHelper( 3300): onPeerLost: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642]
D/io.jxcore.node.ConnectionHelper( 3300): hasConnection: No connection with peer with ID 7C:F9:0E:34:8A:A0
D/io.jxcore.node.ConnectionHelper( 3300): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642] removed
D/io.jxcore.node.ConnectionHelper( 3300): notifyPeerAvailability: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642] not available
I/jxcore-log( 3300): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:34:8A:A0","peerName":"samsung-SM-G900F_PT9642","peerAvailable":false}]
I/jxcore-log( 3300): 
I/jxcore-log( 3300): startWithNextDevice
I/jxcore-log( 3300): 
I/io.jxcore.node.ConnectionHelper( 3300): onPeerLost: [F8:95:C7:87:85:54 LGE-LG-D722_PT317]
D/io.jxcore.node.ConnectionHelper( 3300): hasConnection: No connection with peer with ID F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 3300): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT317] removed
D/io.jxcore.node.ConnectionHelper( 3300): notifyPeerAvailability: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT317] not available
I/jxcore-log( 3300): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:85:54","peerName":"LGE-LG-D722_PT317","peerAvailable":false}]
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): startWithNextDevice
I/jxcore-log( 3300): 
,D/btif_config_util( 2107): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2107): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2107): onReceive
,I/BTConnectionReceiver( 1456): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1456): Bluetooth Device Name: Thali Test (Galaxy A3)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: RESTARTING
,I/wpa_supplicant( 1034): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Start timer timeout, starting now...
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): restart: Restarting...
,D/WifiP2pManager( 3300): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT7958","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958]
I/io.jxcore.node.ConnectionHelper( 3300): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
,D/io.jxcore.node.ConnectionHelper( 3300): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958] is available
,I/jxcore-log( 3300): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:75:41","peerName":"samsung-SM-A300FU_PT7958","peerAvailable":true}]
I/jxcore-log( 3300): 
I/jxcore-log( 3300): Found peer : samsung-SM-A300FU_PT7958, Available: true
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): startWithNextDevice
I/jxcore-log( 3300): 
I/jxcore-log( 3300): device[6]: 08:EC:A9:50:75:41
I/jxcore-log( 3300): 
I/jxcore-log( 3300): 2015-12-19T01:39:45.832Z SendDataConnector.js: Start called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3300): 
I/jxcore-log( 3300): 2015-12-19T01:39:45.832Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3300): 
I/jxcore-log( 3300): 2015-12-19T01:39:45.833Z SendDataConnector.js: do connect now
I/jxcore-log( 3300): 
I/io.jxcore.node.ConnectionHelper( 3300): connect: Trying to connect to peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 3300): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): connect: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): connect: Trying to start connecting to null in address 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): onConnecting: null 08:EC:A9:50:75:41
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): connect: Started connecting to null in address 08:EC:A9:50:75:41
I/io.jxcore.node.ConnectionHelper( 3300): connect: Connection process successfully started (peer ID: 08:EC:A9:50:75:41)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): Trying to connect to peer with address 08:EC:A9:50:75:41 (thread ID: 351)
W/BluetoothAdapter( 3300): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2107): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2107): SDP - Rcvd conn cnf with error: 0x4  CID 0x4f
E/bt-btif ( 2107): DISCOVERY_COMP_EVT slot id:15, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2107): invalid rfc slot id: 15
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 351)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): Maximum number of allowed retries (0) reached, giving up... (thread ID: 351)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): Exiting thread (thread ID: 351)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958]
I/jxcore-log( 3300): 2015-12-19T01:39:50.996Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958] failed
I/jxcore-log( 3300): 
I/jxcore-log( 3300): 2015-12-19T01:39:50.996Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958] failed
I/jxcore-log( 3300): 
I/jxcore-log( 3300): 2015-12-19T01:39:50.996Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3300): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): setInsecureRfcommSocketPort: Will use port 1 when trying to connect
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): shutdown (thread ID: 351)
,W/bt-btif ( 2107): info:x10
,D/        ( 2107): remote version info [f8:95:c7:87:3c:51]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1456): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1456): Bluetooth Device Name: G4-1
,I/BluetoothBondStateMachine( 2107): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
E/bt-btif ( 2107): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2107): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2107): Entering PendingCommandState State
,W/BluetoothEventManager( 2714): CachedBluetoothDevice for device F8:95:C7:87:3C:51 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2714): Got bonding state changed for F8:95:C7:87:3C:51, but we have no record of that device.
,I/BluetoothBondStateMachine( 2107): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,D/BluetoothAdapterProperties( 2107): Failed to remove device: F8:95:C7:87:3C:51
,I/BluetoothBondStateMachine( 2107): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2107): StableState(): Entering Off State
,W/BluetoothEventManager( 2714): CachedBluetoothDevice for device F8:95:C7:87:3C:51 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2714): Got bonding state changed for F8:95:C7:87:3C:51, but we have no record of that device.
,W/bt-btif ( 2107): new conn_srvc id:26, app_id:255
W/bt-btif ( 2107): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2107): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): Incoming connection initialized (thread ID: 353)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3300): Entering thread (ID: 353)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): onBytesRead: Read 77 bytes successfully (thread ID: 353)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): Got valid identity from [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): onBytesWritten: 77 bytes successfully written (thread ID: 353)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): removeThreadFromList: Removing thread with ID 353
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): Handshake thread disposed (thread ID: 353)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): onIncomingConnectionConnected: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3300): Exiting thread (ID: 353)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): onConnected: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
I/io.jxcore.node.ConnectionHelper( 3300): onConnected: Incoming connection to peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
D/io.jxcore.node.ConnectionHelper( 3300): hasConnection: No connection with peer with ID F8:95:C7:87:3C:51
W/io.jxcore.node.ConnectionHelper( 3300): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 3300): onConnected: Incoming socket thread, for peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326], created successfully
D/io.jxcore.node.ConnectionHelper( 3300): onConnected: The total number of connections is now 1
,D/io.jxcore.node.IncomingSocketThread( 3300): Entering thread (ID: 354)
,I/io.jxcore.node.IncomingSocketThread( 3300): Local host address: localhost/127.0.0.1, port: 34900
D/io.jxcore.node.IncomingSocketThread( 3300): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3300): setBufferSize: Setting buffer size to 8192 bytes
,I/jxcore-log( 3300): 2015-12-19T01:39:51.946Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3300): 
,I/io.jxcore.node.StreamCopyingThread( 3300): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3300): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3300): Exiting thread (ID: 354)
,D/io.jxcore.node.StreamCopyingThread( 3300): Entering thread (ID: 356, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3300): Entering thread (ID: 355, name: Sender)
,I/jxcore-log( 3300): 2015-12-19T01:39:52.606Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:39:52.614Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:39:52.627Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:39:52.674Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:39:52.700Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:39:52.710Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:39:52.723Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:39:52.753Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:39:52.760Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:39:52.793Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:39:52.831Z SendDataTCPServer.js: TCP/IP server has received 35640 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:39:52.846Z SendDataTCPServer.js: TCP/IP server has received 37620 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:39:52.855Z SendDataTCPServer.js: TCP/IP server has received 39600 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:39:52.864Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:39:52.913Z SendDataTCPServer.js: TCP/IP server has received 49500 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:39:52.963Z SendDataTCPServer.js: TCP/IP server has received 57420 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:39:52.995Z SendDataTCPServer.js: TCP/IP server has received 59400 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:39:53.003Z SendDataTCPServer.js: TCP/IP server has received 61380 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:39:53.032Z SendDataTCPServer.js: TCP/IP server has received 65340 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:39:53.050Z SendDataTCPServer.js: TCP/IP server has received 67320 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:39:53.056Z SendDataTCPServer.js: TCP/IP server has received 69300 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:39:53.088Z SendDataTCPServer.js: TCP/IP server has received 71280 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:39:53.099Z SendDataTCPServer.js: TCP/IP server has received 75240 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:39:53.133Z SendDataTCPServer.js: TCP/IP server has received 79200 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:39:53.141Z SendDataTCPServer.js: TCP/IP server has received 81180 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:39:53.174Z SendDataTCPServer.js: TCP/IP server has received 83160 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:39:53.219Z SendDataTCPServer.js: TCP/IP server has received 89100 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:39:53.223Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:39:53.284Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:39:53.320Z SendDataTCPServer.js: TCP/IP server has received 99000 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:39:53.389Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3300): 
,W/bt-btif ( 2107): invalid rfc slot id: 8
,W/io.jxcore.node.StreamCopyingThread( 3300): Either failed to read from the output stream or write to the input stream (thread ID: 356, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 3300): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3300): onDisconnected: Incoming connection, peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,I/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 354
D/io.jxcore.node.IncomingSocketThread( 3300): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3300): doStop: Thread ID: 356
D/io.jxcore.node.IncomingSocketThread( 3300): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3300): doStop: Thread ID: 355
D/io.jxcore.node.IncomingSocketThread( 3300): closeLocalSocketAndStreams: Closing...
,D/io.jxcore.node.IncomingSocketThread( 3300): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3300): Either failed to read from the output stream or write to the input stream (thread ID: 355, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3300): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3300): onDisconnected: Incoming connection, peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.IncomingSocketThread( 3300): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 3300): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3300): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3300): Exiting thread (ID: 356, name: Receiver)
,D/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3300): Exiting thread (ID: 355, name: Sender)
,I/jxcore-log( 3300): 2015-12-19T01:39:53.539Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3300): 
,W/bt-rfcomm( 2107): rfc_find_lcid_mcb LCID reused LCID:0x42 current:0x0
W/bt-rfcomm( 2107): RFCOMM_DisconnectInd LCID:0x42
,I/jxcore-log( 3300): 2015-12-19T01:39:55.996Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41
I/jxcore-log( 3300): 
I/jxcore-log( 3300): 2015-12-19T01:39:55.997Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3300): 
,D/btif_config_util( 2107): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2107): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2107): onReceive
,I/BTConnectionReceiver( 1456): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1456): Bluetooth Device Name: G4-1
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/io.jxcore.node.ConnectionHelper( 3300): disconnectOutgoingConnection: Trying to close connection to peer with ID 08:EC:A9:50:75:41
E/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3300): disconnectOutgoingConnection: Failed to disconnect (peer ID: 08:EC:A9:50:75:41), either no such connection or failed to close the connection
I/jxcore-log( 3300): 2015-12-19T01:40:01.002Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3300): 
I/jxcore-log( 3300): 2015-12-19T01:40:01.003Z SendDataConnector.js: Connect (retry count 1) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 3300): 
I/jxcore-log( 3300): 2015-12-19T01:40:01.003Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3300): 
I/jxcore-log( 3300): 2015-12-19T01:40:01.004Z SendDataConnector.js: do connect now
I/jxcore-log( 3300): 
I/io.jxcore.node.ConnectionHelper( 3300): connect: Trying to connect to peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 3300): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): connect: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): connect: Trying to start connecting to null in address 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): setInsecureRfcommSocketPort: Using port 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): onConnecting: null 08:EC:A9:50:75:41
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): connect: Started connecting to null in address 08:EC:A9:50:75:41
I/io.jxcore.node.ConnectionHelper( 3300): connect: Connection process successfully started (peer ID: 08:EC:A9:50:75:41)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): Trying to connect to peer with address 08:EC:A9:50:75:41 (thread ID: 357)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3300): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3300): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2107): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2107): SDP - Rcvd conn cnf with error: 0x4  CID 0x41
E/bt-btif ( 2107): DISCOVERY_COMP_EVT slot id:17, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2107): invalid rfc slot id: 17
,W/BluetoothAdapter( 3300): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2107): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2107): SDP - Rcvd conn cnf with error: 0x4  CID 0x43
E/bt-btif ( 2107): DISCOVERY_COMP_EVT slot id:18, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2107): invalid rfc slot id: 18
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 357)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): Maximum number of allowed retries (0) reached, giving up... (thread ID: 357)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): Exiting thread (thread ID: 357)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958]
,I/jxcore-log( 3300): 2015-12-19T01:40:11.335Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958] failed
I/jxcore-log( 3300): 
I/jxcore-log( 3300): 2015-12-19T01:40:11.335Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958] failed
I/jxcore-log( 3300): 
I/jxcore-log( 3300): 2015-12-19T01:40:11.336Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3300): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): shutdown (thread ID: 357)
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): restart: Restarting...
,D/WifiP2pManager( 3300): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958]
,I/jxcore-log( 3300): 2015-12-19T01:40:16.338Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41
I/jxcore-log( 3300): 
I/jxcore-log( 3300): 2015-12-19T01:40:16.339Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3300): 
,I/ActivityManager(  758): Killing 2585:com.google.android.gm/u0a70 (adj 15): empty #17
,W/libprocessgroup(  758): failed to open /acct/uid_10070/pid_2585/cgroup.procs: No such file or directory
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): checkListForExpiredPeers: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5261] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5261], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Removed [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5261]
I/io.jxcore.node.ConnectionHelper( 3300): onPeerLost: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5261]
D/io.jxcore.node.ConnectionHelper( 3300): hasConnection: No connection with peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 3300): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5261] removed
,D/io.jxcore.node.ConnectionHelper( 3300): notifyPeerAvailability: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5261] not available
,I/jxcore-log( 3300): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:76:27","peerName":"samsung-SM-A300FU_PT5261","peerAvailable":false}]
I/jxcore-log( 3300): 
,D/io.jxcore.node.ConnectionHelper( 3300): disconnectOutgoingConnection: Trying to close connection to peer with ID 08:EC:A9:50:75:41
E/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3300): disconnectOutgoingConnection: Failed to disconnect (peer ID: 08:EC:A9:50:75:41), either no such connection or failed to close the connection
I/jxcore-log( 3300): 2015-12-19T01:40:21.344Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3300): 
I/jxcore-log( 3300): 2015-12-19T01:40:21.344Z SendDataConnector.js: Connect (retry count 2) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 3300): 
I/jxcore-log( 3300): 2015-12-19T01:40:21.345Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3300): 
I/jxcore-log( 3300): 2015-12-19T01:40:21.346Z SendDataConnector.js: do connect now
I/jxcore-log( 3300): 
I/io.jxcore.node.ConnectionHelper( 3300): connect: Trying to connect to peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 3300): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): connect: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): connect: Trying to start connecting to null in address 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): onConnecting: null 08:EC:A9:50:75:41
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): connect: Started connecting to null in address 08:EC:A9:50:75:41
I/io.jxcore.node.ConnectionHelper( 3300): connect: Connection process successfully started (peer ID: 08:EC:A9:50:75:41)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): Trying to connect to peer with address 08:EC:A9:50:75:41 (thread ID: 359)
W/BluetoothAdapter( 3300): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2107): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2107): SDP - Rcvd conn cnf with error: 0x4  CID 0x45
E/bt-btif ( 2107): DISCOVERY_COMP_EVT slot id:19, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2107): invalid rfc slot id: 19
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 359)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): Maximum number of allowed retries (0) reached, giving up... (thread ID: 359)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): Exiting thread (thread ID: 359)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958]
,I/jxcore-log( 3300): 2015-12-19T01:40:26.522Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958] failed
I/jxcore-log( 3300): 
I/jxcore-log( 3300): 2015-12-19T01:40:26.523Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958] failed
I/jxcore-log( 3300): 
I/jxcore-log( 3300): 2015-12-19T01:40:26.523Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3300): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): setInsecureRfcommSocketPort: Will use port 1 when trying to connect
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): shutdown (thread ID: 359)
,I/jxcore-log( 3300): 2015-12-19T01:40:31.523Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41
I/jxcore-log( 3300): 
I/jxcore-log( 3300): 2015-12-19T01:40:31.524Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3300): 
,D/io.jxcore.node.ConnectionHelper( 3300): disconnectOutgoingConnection: Trying to close connection to peer with ID 08:EC:A9:50:75:41
E/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3300): disconnectOutgoingConnection: Failed to disconnect (peer ID: 08:EC:A9:50:75:41), either no such connection or failed to close the connection
,I/jxcore-log( 3300): 2015-12-19T01:40:36.534Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3300): 
I/jxcore-log( 3300): 2015-12-19T01:40:36.535Z SendDataConnector.js: Connect (retry count 3) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 3300): 
I/jxcore-log( 3300): 2015-12-19T01:40:36.536Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3300): 
I/jxcore-log( 3300): 2015-12-19T01:40:36.537Z SendDataConnector.js: do connect now
I/jxcore-log( 3300): 
,I/io.jxcore.node.ConnectionHelper( 3300): connect: Trying to connect to peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 3300): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): connect: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): connect: Trying to start connecting to null in address 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): setInsecureRfcommSocketPort: Using port 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): onConnecting: null 08:EC:A9:50:75:41
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): connect: Started connecting to null in address 08:EC:A9:50:75:41
I/io.jxcore.node.ConnectionHelper( 3300): connect: Connection process successfully started (peer ID: 08:EC:A9:50:75:41)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): Trying to connect to peer with address 08:EC:A9:50:75:41 (thread ID: 361)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3300): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3300): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2107): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2107): SDP - Rcvd conn cnf with error: 0x4  CID 0x44
E/bt-btif ( 2107): DISCOVERY_COMP_EVT slot id:20, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2107): invalid rfc slot id: 20
,W/BluetoothAdapter( 3300): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2107): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: RESTARTING
,I/wpa_supplicant( 1034): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
,W/bt-sdp  ( 2107): SDP - Rcvd conn cnf with error: 0x4  CID 0x46
E/bt-btif ( 2107): DISCOVERY_COMP_EVT slot id:21, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2107): invalid rfc slot id: 21
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 361)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): Maximum number of allowed retries (0) reached, giving up... (thread ID: 361)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): Exiting thread (thread ID: 361)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958]
I/jxcore-log( 3300): 2015-12-19T01:40:46.874Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958] failed
I/jxcore-log( 3300): 
I/jxcore-log( 3300): 2015-12-19T01:40:46.875Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958] failed
I/jxcore-log( 3300): 
I/jxcore-log( 3300): 2015-12-19T01:40:46.876Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3300): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): shutdown (thread ID: 361)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Start timer timeout, starting now...
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/jxcore-log( 3300): 2015-12-19T01:40:51.877Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:40:51.882Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3300): 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1034): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
,D/WifiP2pManager( 3300): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
,W/bt-btif ( 2107): info:x10
,D/        ( 2107): remote version info [08:ec:a9:50:76:27]: 7, f, 6109
,I/BTConnectionReceiver( 1456): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1456): Bluetooth Device Name: Thali Test (Galaxy A3)
,W/bt-btif ( 2107): new conn_srvc id:26, app_id:255
W/bt-btif ( 2107): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2107): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): Incoming connection initialized (thread ID: 363)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3300): Entering thread (ID: 363)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): onBytesRead: Read 83 bytes successfully (thread ID: 363)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): Got valid identity from [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5261]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): onBytesWritten: 77 bytes successfully written (thread ID: 363)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): removeThreadFromList: Removing thread with ID 363
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): Handshake thread disposed (thread ID: 363)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): onIncomingConnectionConnected: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5261]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3300): Exiting thread (ID: 363)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): onConnected: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5261]
,I/io.jxcore.node.ConnectionHelper( 3300): onConnected: Incoming connection to peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5261]
D/io.jxcore.node.ConnectionHelper( 3300): hasConnection: No connection with peer with ID 08:EC:A9:50:76:27
,D/io.jxcore.node.ConnectionHelper( 3300): notifyPeerAvailability: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5261] is available
,I/jxcore-log( 3300): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:76:27","peerName":"samsung-SM-A300FU_PT5261","peerAvailable":true}]
I/jxcore-log( 3300): 
I/io.jxcore.node.ConnectionHelper( 3300): onConnected: Incoming socket thread, for peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5261], created successfully
D/io.jxcore.node.ConnectionHelper( 3300): onConnected: The total number of connections is now 1
,D/io.jxcore.node.IncomingSocketThread( 3300): Entering thread (ID: 364)
,I/jxcore-log( 3300): 2015-12-19T01:40:56.606Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3300): 
,I/io.jxcore.node.IncomingSocketThread( 3300): Local host address: localhost/127.0.0.1, port: 34900
D/io.jxcore.node.IncomingSocketThread( 3300): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3300): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3300): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3300): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3300): Exiting thread (ID: 364)
,D/io.jxcore.node.StreamCopyingThread( 3300): Entering thread (ID: 365, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 3300): Entering thread (ID: 366, name: Receiver)
,D/io.jxcore.node.ConnectionHelper( 3300): disconnectOutgoingConnection: Trying to close connection to peer with ID 08:EC:A9:50:75:41
E/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3300): disconnectOutgoingConnection: Failed to disconnect (peer ID: 08:EC:A9:50:75:41), either no such connection or failed to close the connection
I/jxcore-log( 3300): 2015-12-19T01:40:56.886Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:40:56.892Z SendDataConnector.js: Connect (retry count 4) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 3300): 
I/jxcore-log( 3300): 2015-12-19T01:40:56.893Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3300): 
I/jxcore-log( 3300): 2015-12-19T01:40:56.893Z SendDataConnector.js: do connect now
I/jxcore-log( 3300): 
I/io.jxcore.node.ConnectionHelper( 3300): connect: Trying to connect to peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 3300): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): connect: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): connect: Trying to start connecting to null in address 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): onConnecting: null 08:EC:A9:50:75:41
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): connect: Started connecting to null in address 08:EC:A9:50:75:41
I/io.jxcore.node.ConnectionHelper( 3300): connect: Connection process successfully started (peer ID: 08:EC:A9:50:75:41)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): Trying to connect to peer with address 08:EC:A9:50:75:41 (thread ID: 367)
W/BluetoothAdapter( 3300): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2107): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2107): tBTM_SEC_DEV:0xa3e515dc rs_disc_pending=1
W/bt-btif ( 2107): bta_dm_check_av:0
,W/bt-btif ( 2107): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3300): 2015-12-19T01:40:57.913Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:40:58.048Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:40:58.211Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:40:58.302Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:40:58.444Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:40:58.596Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:40:58.817Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:40:58.893Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:40:59.040Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3300): 
,D/btif_config_util( 2107): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3300): 2015-12-19T01:40:59.491Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:40:59.577Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:40:59.651Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:40:59.726Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:40:59.794Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:40:59.964Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:41:00.034Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:41:00.102Z SendDataTCPServer.js: TCP/IP server has received 32768 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:41:00.176Z SendDataTCPServer.js: TCP/IP server has received 34748 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:41:00.255Z SendDataTCPServer.js: TCP/IP server has received 36728 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:41:00.329Z SendDataTCPServer.js: TCP/IP server has received 38708 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:41:00.479Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:41:00.603Z SendDataTCPServer.js: TCP/IP server has received 42668 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:41:00.736Z SendDataTCPServer.js: TCP/IP server has received 44648 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:41:00.805Z SendDataTCPServer.js: TCP/IP server has received 46628 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:41:00.937Z SendDataTCPServer.js: TCP/IP server has received 48608 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:41:01.087Z SendDataTCPServer.js: TCP/IP server has received 50588 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:41:01.268Z SendDataTCPServer.js: TCP/IP server has received 52568 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:41:01.335Z SendDataTCPServer.js: TCP/IP server has received 54548 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:41:01.471Z SendDataTCPServer.js: TCP/IP server has received 56528 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:41:01.622Z SendDataTCPServer.js: TCP/IP server has received 58508 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:41:01.806Z SendDataTCPServer.js: TCP/IP server has received 60488 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:41:01.874Z SendDataTCPServer.js: TCP/IP server has received 62468 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:41:01.943Z SendDataTCPServer.js: TCP/IP server has received 64448 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:41:02.014Z SendDataTCPServer.js: TCP/IP server has received 66428 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:41:02.087Z SendDataTCPServer.js: TCP/IP server has received 68408 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:41:02.179Z SendDataTCPServer.js: TCP/IP server has received 70388 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:41:02.344Z SendDataTCPServer.js: TCP/IP server has received 72368 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:41:02.414Z SendDataTCPServer.js: TCP/IP server has received 74348 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:41:02.562Z SendDataTCPServer.js: TCP/IP server has received 76328 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:41:02.647Z SendDataTCPServer.js: TCP/IP server has received 78308 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:41:02.716Z SendDataTCPServer.js: TCP/IP server has received 80288 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:41:02.890Z SendDataTCPServer.js: TCP/IP server has received 82268 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:41:03.003Z SendDataTCPServer.js: TCP/IP server has received 84248 bytes of data
I/jxcore-log( 3300): 
,W/bt-sdp  ( 2107): SDP - Rcvd conn cnf with error: 0x4  CID 0x49
E/bt-btif ( 2107): DISCOVERY_COMP_EVT slot id:23, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2107): invalid rfc slot id: 23
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 367)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): Maximum number of allowed retries (0) reached, giving up... (thread ID: 367)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): Exiting thread (thread ID: 367)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958]
,I/jxcore-log( 3300): 2015-12-19T01:41:03.052Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958] failed
I/jxcore-log( 3300): 
I/jxcore-log( 3300): 2015-12-19T01:41:03.052Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958] failed
I/jxcore-log( 3300): 
I/jxcore-log( 3300): oneRoundDownNow
I/jxcore-log( 3300): 
I/jxcore-log( 3300): 2015-12-19T01:41:03.054Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3300): 
D/io.jxcore.node.ConnectionHelper( 3300): disconnectOutgoingConnection: Trying to close connection to peer with ID 08:EC:A9:50:75:41
E/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3300): disconnectOutgoingConnection: Failed to disconnect (peer ID: 08:EC:A9:50:75:41), either no such connection or failed to close the connection
I/jxcore-log( 3300): 2015-12-19T01:41:03.057Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3300): 
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): shutdown (thread ID: 367)
,I/jxcore-log( 3300): ---- round done--------
I/jxcore-log( 3300): 
I/jxcore-log( 3300): startWithNextDevice
I/jxcore-log( 3300): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): setInsecureRfcommSocketPort: Will use port 1 when trying to connect
,I/jxcore-log( 3300): 2015-12-19T01:41:03.093Z SendDataTCPServer.js: TCP/IP server has received 86228 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:41:03.129Z SendDataTCPServer.js: TCP/IP server has received 88208 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:41:03.136Z SendDataTCPServer.js: TCP/IP server has received 90188 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:41:03.143Z SendDataTCPServer.js: TCP/IP server has received 92168 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:41:03.178Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3300): 
,W/bt-btif ( 2107): invalid rfc slot id: 16
,W/io.jxcore.node.StreamCopyingThread( 3300): Either failed to read from the output stream or write to the input stream (thread ID: 366, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 3300): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3300): onDisconnected: Incoming connection, peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5261] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 364
D/io.jxcore.node.IncomingSocketThread( 3300): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3300): doStop: Thread ID: 366
D/io.jxcore.node.IncomingSocketThread( 3300): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3300): doStop: Thread ID: 365
D/io.jxcore.node.IncomingSocketThread( 3300): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 3300): closeLocalSocketAndStreams: Closing the local input stream...
D/io.jxcore.node.IncomingSocketThread( 3300): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 3300): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3300): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3300): Exiting thread (ID: 366, name: Receiver)
,W/io.jxcore.node.StreamCopyingThread( 3300): Either failed to read from the output stream or write to the input stream (thread ID: 365, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3300): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3300): onDisconnected: Incoming connection, peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5261] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3300): Exiting thread (ID: 365, name: Sender)
,I/jxcore-log( 3300): 2015-12-19T01:41:03.239Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3300): 
,W/bt-rfcomm( 2107): rfc_find_lcid_mcb LCID reused LCID:0x48 current:0x0
W/bt-rfcomm( 2107): RFCOMM_DisconnectInd LCID:0x48
,E/bt-btm  ( 2107): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2107): onReceive
,I/BTConnectionReceiver( 1456): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1456): Bluetooth Device Name: Thali Test (Galaxy A3)
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): checkListForExpiredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Removed [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958]
I/io.jxcore.node.ConnectionHelper( 3300): onPeerLost: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958]
D/io.jxcore.node.ConnectionHelper( 3300): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 3300): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958] removed
D/io.jxcore.node.ConnectionHelper( 3300): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958] not available
I/jxcore-log( 3300): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:75:41","peerName":"samsung-SM-A300FU_PT7958","peerAvailable":false}]
I/jxcore-log( 3300): 
I/jxcore-log( 3300): startWithNextDevice
I/jxcore-log( 3300): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: RESTARTING
,I/wpa_supplicant( 1034): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Start timer timeout, starting now...
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): restart: Restarting...
,D/WifiP2pManager( 3300): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: RESTARTING
,I/wpa_supplicant( 1034): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Start timer timeout, starting now...
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): restart: Restarting...
,D/WifiP2pManager( 3300): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
,W/bt-btif ( 2107): info:x10
,D/        ( 2107): remote version info [7c:f9:0e:34:8a:a0]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1456): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1456): Bluetooth Device Name: S5-1
,W/bt-btif ( 2107): new conn_srvc id:26, app_id:255
W/bt-btif ( 2107): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2107): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): Incoming connection accepted
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): Incoming connection initialized (thread ID: 369)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3300): Entering thread (ID: 369)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): onBytesRead: Read 82 bytes successfully (thread ID: 369)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): Got valid identity from [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): onBytesWritten: 77 bytes successfully written (thread ID: 369)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): removeThreadFromList: Removing thread with ID 369
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): Handshake thread disposed (thread ID: 369)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): onIncomingConnectionConnected: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3300): Exiting thread (ID: 369)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): onConnected: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642]
I/io.jxcore.node.ConnectionHelper( 3300): onConnected: Incoming connection to peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642]
D/io.jxcore.node.ConnectionHelper( 3300): hasConnection: No connection with peer with ID 7C:F9:0E:34:8A:A0
D/io.jxcore.node.ConnectionHelper( 3300): notifyPeerAvailability: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642] is available
,I/jxcore-log( 3300): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:34:8A:A0","peerName":"samsung-SM-G900F_PT9642","peerAvailable":true}]
I/jxcore-log( 3300): 
I/jxcore-log( 3300): startWithNextDevice
I/jxcore-log( 3300): 
,I/io.jxcore.node.ConnectionHelper( 3300): onConnected: Incoming socket thread, for peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642], created successfully
D/io.jxcore.node.ConnectionHelper( 3300): onConnected: The total number of connections is now 1
,D/io.jxcore.node.IncomingSocketThread( 3300): Entering thread (ID: 370)
,I/jxcore-log( 3300): 2015-12-19T01:42:21.241Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3300): 
,I/io.jxcore.node.IncomingSocketThread( 3300): Local host address: localhost/127.0.0.1, port: 34900
D/io.jxcore.node.IncomingSocketThread( 3300): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3300): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3300): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.IncomingSocketThread( 3300): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3300): Exiting thread (ID: 370)
,D/io.jxcore.node.StreamCopyingThread( 3300): Entering thread (ID: 371, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 3300): Entering thread (ID: 372, name: Receiver)
,I/jxcore-log( 3300): 2015-12-19T01:42:22.258Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:42:22.297Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:42:22.351Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3300): 
I/jxcore-log( 3300): 2015-12-19T01:42:22.353Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3300): 
,D/btif_config_util( 2107): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3300): 2015-12-19T01:42:22.402Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:42:22.443Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:42:22.493Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:42:22.529Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:42:22.535Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:42:22.602Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:42:22.705Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:42:22.715Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:42:22.750Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:42:22.806Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:42:22.812Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:42:22.870Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:42:22.879Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:42:22.959Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:42:23.000Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:42:23.006Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data,
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:42:23.062Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:42:23.071Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:42:23.104Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:42:23.194Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:42:23.282Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:42:23.311Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:42:23.320Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:42:23.356Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:42:23.395Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:42:23.401Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:42:23.443Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:42:23.455Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:42:23.593Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:42:23.641Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:42:23.690Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:42:23.774Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:42:23.830Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:42:23.836Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:42:23.904Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:42:23.963Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:42:24.095Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:42:24.146Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:42:24.154Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:42:24.193Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:42:24.319Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:42:24.362Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:42:24.403Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:42:24.407Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:42:24.440Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3300): 
,W/bt-btif ( 2107): invalid rfc slot id: 22
,W/io.jxcore.node.StreamCopyingThread( 3300): Either failed to read from the output stream or write to the input stream (thread ID: 372, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 3300): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3300): onDisconnected: Incoming connection, peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 370
D/io.jxcore.node.IncomingSocketThread( 3300): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3300): doStop: Thread ID: 372
D/io.jxcore.node.IncomingSocketThread( 3300): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3300): doStop: Thread ID: 371
D/io.jxcore.node.IncomingSocketThread( 3300): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 3300): closeLocalSocketAndStreams: Closing the local input stream...
D/io.jxcore.node.IncomingSocketThread( 3300): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 3300): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3300): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3300): Exiting thread (ID: 372, name: Receiver)
,W/io.jxcore.node.StreamCopyingThread( 3300): Either failed to read from the output stream or write to the input stream (thread ID: 371, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3300): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3300): onDisconnected: Incoming connection, peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3300): Exiting thread (ID: 371, name: Sender)
,I/jxcore-log( 3300): 2015-12-19T01:42:24.565Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3300): 
,W/bt-rfcomm( 2107): rfc_find_lcid_mcb LCID reused LCID:0x4b current:0x0
W/bt-rfcomm( 2107): RFCOMM_DisconnectInd LCID:0x4b
,W/bt-btif ( 2107): info:x10
,D/        ( 2107): remote version info [b0:c5:59:3f:75:69]: 7, f, 610c
,E/BluetoothRemoteDevices( 2107): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2107): tBTM_SEC_DEV:0xa3e5196c rs_disc_pending=0
W/bt-btif ( 2107): bta_dm_check_av:0
,W/bt-btif ( 2107): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 2107): bondStateChangeCallback: Status: 0 Address: B0:C5:59:3F:75:69 newState: 1
E/bt-btif ( 2107): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2107): Bond State Change Intent:B0:C5:59:3F:75:69 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2107): Entering PendingCommandState State
,W/BluetoothEventManager( 2714): CachedBluetoothDevice for device B0:C5:59:3F:75:69 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2714): Got bonding state changed for B0:C5:59:3F:75:69, but we have no record of that device.
,I/BluetoothBondStateMachine( 2107): bondStateChangeCallback: Status: 0 Address: B0:C5:59:3F:75:69 newState: 0
,D/BluetoothAdapterProperties( 2107): Failed to remove device: B0:C5:59:3F:75:69
,W/BluetoothEventManager( 2714): CachedBluetoothDevice for device B0:C5:59:3F:75:69 not found, calling readPairedDevices().
,I/BluetoothBondStateMachine( 2107): Bond State Change Intent:B0:C5:59:3F:75:69 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2107): StableState(): Entering Off State
,E/BluetoothEventManager( 2714): Got bonding state changed for B0:C5:59:3F:75:69, but we have no record of that device.
,W/bt-btif ( 2107): new conn_srvc id:26, app_id:255
W/bt-btif ( 2107): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2107): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): Incoming connection initialized (thread ID: 373)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3300): Entering thread (ID: 373)
,E/bt-btm  ( 2107): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2107): onReceive
,I/BTConnectionReceiver( 1456): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1456): Bluetooth Device Name: S5-1
,E/bt-btm  ( 2107): tBTM_SEC_DEV:0xa3e5196c rs_disc_pending=1
W/bt-btif ( 2107): bta_dm_check_av:0
,W/bt-btif ( 2107): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2107): tBTM_SEC_DEV:0xa3e5196c rs_disc_pending=0
W/bt-btif ( 2107): bta_dm_check_av:0
,W/bt-btif ( 2107): btif_dm_cback : unhandled event (14)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): onBytesRead: Read 82 bytes successfully (thread ID: 373)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): Got valid identity from [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9541]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): onBytesWritten: 77 bytes successfully written (thread ID: 373)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): removeThreadFromList: Removing thread with ID 373
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): Handshake thread disposed (thread ID: 373)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): onIncomingConnectionConnected: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9541]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3300): Exiting thread (ID: 373)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): onConnected: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9541]
,I/io.jxcore.node.ConnectionHelper( 3300): onConnected: Incoming connection to peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9541]
D/io.jxcore.node.ConnectionHelper( 3300): hasConnection: No connection with peer with ID B0:C5:59:3F:75:69
D/io.jxcore.node.ConnectionHelper( 3300): notifyPeerAvailability: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9541] is available
,I/jxcore-log( 3300): peerAvailabilityChanged [{"peerIdentifier":"B0:C5:59:3F:75:69","peerName":"samsung-SM-G900F_PT9541","peerAvailable":true}]
I/jxcore-log( 3300): 
I/jxcore-log( 3300): Found peer : samsung-SM-G900F_PT9541, Available: true
I/jxcore-log( 3300): 
I/jxcore-log( 3300): startWithNextDevice
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): device[7]: B0:C5:59:3F:75:69
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:42:29.171Z SendDataConnector.js: Start called with peer B0:C5:59:3F:75:69
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:42:29.174Z SendDataConnector.js: doConnect called with peer B0:C5:59:3F:75:69
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:42:29.177Z SendDataConnector.js: do connect now
I/jxcore-log( 3300): 
,I/io.jxcore.node.ConnectionHelper( 3300): connect: Trying to connect to peer with ID B0:C5:59:3F:75:69
D/io.jxcore.node.ConnectionHelper( 3300): hasConnection: No connection with peer with ID B0:C5:59:3F:75:69
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): connect: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9541]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): connect: Trying to start connecting to Thali Test (Galaxy S5) in address B0:C5:59:3F:75:69
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): setInsecureRfcommSocketPort: Using port 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): setMaxNumberOfRetries: 0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): onConnecting: Thali Test (Galaxy S5) B0:C5:59:3F:75:69
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): connect: Started connecting to Thali Test (Galaxy S5) in address B0:C5:59:3F:75:69
I/io.jxcore.node.ConnectionHelper( 3300): connect: Connection process successfully started (peer ID: B0:C5:59:3F:75:69)
I/io.jxcore.node.ConnectionHelper( 3300): onConnected: Incoming socket thread, for peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9541], created successfully
D/io.jxcore.node.ConnectionHelper( 3300): onConnected: The total number of connections is now 1
,D/io.jxcore.node.IncomingSocketThread( 3300): Entering thread (ID: 375)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): Trying to connect to peer with address B0:C5:59:3F:75:69 (thread ID: 374)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3300): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3300): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2107): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/jxcore-log( 3300): 2015-12-19T01:42:29.199Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3300): 
,I/io.jxcore.node.IncomingSocketThread( 3300): Local host address: localhost/127.0.0.1, port: 34900
D/io.jxcore.node.IncomingSocketThread( 3300): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3300): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3300): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3300): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3300): Exiting thread (ID: 375)
,D/io.jxcore.node.StreamCopyingThread( 3300): Entering thread (ID: 377, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3300): Entering thread (ID: 376, name: Sender)
,W/bt-sdp  ( 2107): process_service_search_attr_rsp
,W/bt-btif ( 2107): new conn_srvc id:26, app_id:1
W/bt-btif ( 2107): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2107): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2107): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): onSocketConnected: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9541]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): Socket connection succeeded (using port 1), total number of attempts: 1 (thread ID: 374)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): onBytesWritten: 77 bytes successfully written (thread ID: 378)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): Outgoing connection initialized (*handshake* thread ID: 378)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): Exiting thread (thread ID: 374)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3300): Entering thread (ID: 378)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): onBytesRead: Read 82 bytes successfully (thread ID: 378)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): Handshake succeeded with [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9541]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): onHandshakeSucceeded: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9541]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3300): Exiting thread (ID: 378)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): onConnected: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9541]
I/io.jxcore.node.ConnectionHelper( 3300): onConnected: Outgoing connection to peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9541]
,D/io.jxcore.node.ConnectionHelper( 3300): hasConnection: We have an incoming connection with peer with ID B0:C5:59:3F:75:69
W/io.jxcore.node.ConnectionHelper( 3300): onConnected: Already connected with peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9541], continuing anyway...
W/io.jxcore.node.ConnectionHelper( 3300): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9541] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 3300): onConnected: Outgoing socket thread, for peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9541], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 3300): onConnected: The total number of connections is now 2
,D/io.jxcore.node.OutgoingSocketThread( 3300): Entering thread (ID: 379)
,D/io.jxcore.node.OutgoingSocketThread( 3300): Server socket local port: 58658
I/io.jxcore.node.OutgoingSocketThread( 3300): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3300): onListeningForIncomingConnections: Outgoing connection is using port 58658 (peer ID: B0:C5:59:3F:75:69)
I/jxcore-log( 3300): 2015-12-19T01:42:30.351Z SendDataConnector.js: CLIENT connected to 58658, error: null
I/jxcore-log( 3300): 
I/jxcore-log( 3300): 2015-12-19T01:42:30.352Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3300): 
,I/io.jxcore.node.OutgoingSocketThread( 3300): Incoming data from address: /127.0.0.1, port: 58658
D/io.jxcore.node.OutgoingSocketThread( 3300): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3300): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3300): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3300): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3300): Exiting thread (ID: 379)
,I/jxcore-log( 3300): 2015-12-19T01:42:30.381Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3300): 
I/jxcore-log( 3300): 2015-12-19T01:42:30.382Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3300): 
,D/io.jxcore.node.StreamCopyingThread( 3300): Entering thread (ID: 380, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 3300): Entering thread (ID: 381, name: Receiver)
,I/jxcore-log( 3300): 2015-12-19T01:42:30.852Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:42:30.878Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:42:30.885Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:42:30.945Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:42:30.979Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:42:31.000Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 3300): 
,D/btif_config_util( 2107): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3300): 2015-12-19T01:42:31.062Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:42:31.190Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:42:31.244Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:42:31.311Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:42:31.882Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:42:32.732Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:42:32.858Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:42:32.977Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:42:32.986Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:42:33.036Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:42:33.176Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:42:33.310Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:42:33.324Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:42:33.334Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:42:33.717Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:42:33.723Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3300): 
I/jxcore-log( 3300): 2015-12-19T01:42:33.724Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3300): 
I/jxcore-log( 3300): oneRoundDownNow
I/jxcore-log( 3300): 
I/jxcore-log( 3300): 2015-12-19T01:42:33.725Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3300): 
I/jxcore-log( 3300): 2015-12-19T01:42:33.726Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3300): 
,D/io.jxcore.node.ConnectionHelper( 3300): disconnectOutgoingConnection: Trying to close connection to peer with ID B0:C5:59:3F:75:69
I/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: B0:C5:59:3F:75:69
I/io.jxcore.node.OutgoingSocketThread( 3300): close
D/io.jxcore.node.OutgoingSocketThread( 3300): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3300): doStop: Thread ID: 381
D/io.jxcore.node.OutgoingSocketThread( 3300): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3300): doStop: Thread ID: 380
D/io.jxcore.node.OutgoingSocketThread( 3300): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 3300): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3300): Either failed to read from the output stream or write to the input stream (thread ID: 380, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3300): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3300): onDisconnected: Outgoing connection, peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9541] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 3300): closeLocalSocketAndStreams: Closing the local output stream...
,D/io.jxcore.node.OutgoingSocketThread( 3300): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3300): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3300): Either failed to read from the output stream or write to the input stream (thread ID: 381, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.OutgoingSocketThread( 3300): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3300): onDisconnected: Outgoing connection, peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9541] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3300): disconnectOutgoingConnection: Successfully disconnected (peer ID: B0:C5:59:3F:75:69
,E/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID B0:C5:59:3F:75:69
,D/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3300): Exiting thread (ID: 380, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID B0:C5:59:3F:75:69
D/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3300): Exiting thread (ID: 381, name: Receiver)
,I/jxcore-log( 3300): 2015-12-19T01:42:33.783Z SendDataConnector.js: Mobile.Disconnect() callback with peer B0:C5:59:3F:75:69
I/jxcore-log( 3300): 
I/jxcore-log( 3300): ---- round done--------
I/jxcore-log( 3300): 
I/jxcore-log( 3300): startWithNextDevice
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:42:33.804Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:42:33.843Z SendDataTCPServer.js: TCP/IP server has received 35640 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:42:33.853Z SendDataTCPServer.js: TCP/IP server has received 37620 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:42:33.863Z SendDataTCPServer.js: TCP/IP server has received 39600 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:42:33.871Z SendDataTCPServer.js: TCP/IP server has received 41580 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:42:33.917Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:42:33.948Z SendDataTCPServer.js: TCP/IP server has received 47520 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:42:34.286Z SendDataTCPServer.js: TCP/IP server has received 49500 bytes of data
I/jxcore-log( 3300): 
,W/bt-btif ( 2107): bta_jv_rfc_port_to_cb(port_handle:0x13):jv handle:0x0 not FOUND
,I/jxcore-log( 3300): 2015-12-19T01:42:34.579Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:42:34.589Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:42:34.656Z SendDataTCPServer.js: TCP/IP server has received 55440 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:42:34.709Z SendDataTCPServer.js: TCP/IP server has received 57420 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:42:34.760Z SendDataTCPServer.js: TCP/IP server has received 59400 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:42:34.767Z SendDataTCPServer.js: TCP/IP server has received 61380 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:42:34.780Z SendDataTCPServer.js: TCP/IP server has received 65340 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:42:34.822Z SendDataTCPServer.js: TCP/IP server has received 67320 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:42:34.830Z SendDataTCPServer.js: TCP/IP server has received 69300 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:42:34.836Z SendDataTCPServer.js: TCP/IP server has received 71280 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:42:34.882Z SendDataTCPServer.js: TCP/IP server has received 73260 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:42:34.920Z SendDataTCPServer.js: TCP/IP server has received 79200 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:42:34.942Z SendDataTCPServer.js: TCP/IP server has received 81180 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:42:34.952Z SendDataTCPServer.js: TCP/IP server has received 83160 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:42:34.991Z SendDataTCPServer.js: TCP/IP server has received 85140 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:42:35.071Z SendDataTCPServer.js: TCP/IP server has received 87120 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:42:35.140Z SendDataTCPServer.js: TCP/IP server has received 89100 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:42:35.201Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:42:35.263Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:42:35.571Z SendDataTCPServer.js: TCP/IP server has received 95040 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:42:35.627Z SendDataTCPServer.js: TCP/IP server has received 97020 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:42:35.687Z SendDataTCPServer.js: TCP/IP server has received 99000 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:42:35.694Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3300): 
,W/bt-btif ( 2107): invalid rfc slot id: 24
,W/io.jxcore.node.StreamCopyingThread( 3300): Either failed to read from the output stream or write to the input stream (thread ID: 377, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.OutgoingSocketThread( 3300): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3300): onDisconnected: Incoming connection, peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9541] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,I/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 375
D/io.jxcore.node.OutgoingSocketThread( 3300): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3300): doStop: Thread ID: 377
D/io.jxcore.node.OutgoingSocketThread( 3300): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3300): doStop: Thread ID: 376
,D/io.jxcore.node.OutgoingSocketThread( 3300): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 3300): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3300): Either failed to read from the output stream or write to the input stream (thread ID: 376, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3300): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3300): onDisconnected: Incoming connection, peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9541] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 3300): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 3300): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3300): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3300): Exiting thread (ID: 376, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 3300): Exiting thread (ID: 377, name: Receiver)
,I/jxcore-log( 3300): 2015-12-19T01:42:35.910Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3300): 
,W/bt-rfcomm( 2107): rfc_find_lcid_mcb LCID reused LCID:0x4d current:0x0
W/bt-rfcomm( 2107): RFCOMM_DisconnectInd LCID:0x4d
,E/bt-btm  ( 2107): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2107): onReceive
,I/BTConnectionReceiver( 1456): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1456): Bluetooth Device Name: Thali Test (Galaxy S5)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: RESTARTING
,I/wpa_supplicant( 1034): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Start timer timeout, starting now...
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): restart: Restarting...
,D/WifiP2pManager( 3300): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Got discovery timeout, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: RESTARTING
,I/wpa_supplicant( 1034): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery started successfully
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): restart: Restarting...
,D/WifiP2pManager( 3300): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT9541","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9541]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onServiceDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9541]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9541]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9541], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Adding new peer: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9541]
I/io.jxcore.node.ConnectionHelper( 3300): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9541], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
W/io.jxcore.node.ConnectionHelper( 3300): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9541] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT5260","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260]
I/io.jxcore.node.ConnectionHelper( 3300): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260], Bluetooth address: 7C:F9:0E:51:18:22, device name: , device address: 7e:f9:0e:51:18:23
D/io.jxcore.node.ConnectionHelper( 3300): notifyPeerAvailability: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260] is available
I/jxcore-log( 3300): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:51:18:22","peerName":"samsung-SM-A500FU_PT5260","peerAvailable":true}]
I/jxcore-log( 3300): 
I/jxcore-log( 3300): Found peer : samsung-SM-A500FU_PT5260, Available: true
I/jxcore-log( 3300): 
I/jxcore-log( 3300): startWithNextDevice
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): device[8]: 7C:F9:0E:51:18:22
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:43:40.334Z SendDataConnector.js: Start called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:43:40.340Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3300): 
I/jxcore-log( 3300): 2015-12-19T01:43:40.354Z SendDataConnector.js: do connect now
I/jxcore-log( 3300): 
I/io.jxcore.node.ConnectionHelper( 3300): connect: Trying to connect to peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 3300): hasConnection: No connection with peer with ID 7C:F9:0E:51:18:22
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): connect: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): connect: Trying to start connecting to null in address 7C:F9:0E:51:18:22
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): onConnecting: null 7C:F9:0E:51:18:22
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): connect: Started connecting to null in address 7C:F9:0E:51:18:22
I/io.jxcore.node.ConnectionHelper( 3300): connect: Connection process successfully started (peer ID: 7C:F9:0E:51:18:22)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): Trying to connect to peer with address 7C:F9:0E:51:18:22 (thread ID: 382)
W/BluetoothAdapter( 3300): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2107): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2107): info:x10
,D/        ( 2107): remote version info [7c:f9:0e:51:18:22]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2107): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2107): process_service_search_attr_rsp
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BluetoothBondStateMachine( 2107): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:51:18:22 newState: 1
E/bt-btif ( 2107): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2107): Bond State Change Intent:7C:F9:0E:51:18:22 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2107): Entering PendingCommandState State
,W/BluetoothEventManager( 2714): CachedBluetoothDevice for device 7C:F9:0E:51:18:22 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2714): Got bonding state changed for 7C:F9:0E:51:18:22, but we have no record of that device.
,I/BluetoothBondStateMachine( 2107): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:51:18:22 newState: 0
,D/BluetoothAdapterProperties( 2107): Failed to remove device: 7C:F9:0E:51:18:22
,I/BluetoothBondStateMachine( 2107): Bond State Change Intent:7C:F9:0E:51:18:22 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2107): StableState(): Entering Off State
,W/BluetoothEventManager( 2714): CachedBluetoothDevice for device 7C:F9:0E:51:18:22 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2714): Got bonding state changed for 7C:F9:0E:51:18:22, but we have no record of that device.
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2107): new conn_srvc id:26, app_id:1
W/bt-btif ( 2107): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2107): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): onSocketConnected: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 382)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): onBytesWritten: 77 bytes successfully written (thread ID: 383)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): Outgoing connection initialized (*handshake* thread ID: 383)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): Exiting thread (thread ID: 382)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3300): Entering thread (ID: 383)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): onBytesRead: Read 83 bytes successfully (thread ID: 383)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): Handshake succeeded with [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): onHandshakeSucceeded: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): onConnected: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260]
I/io.jxcore.node.ConnectionHelper( 3300): onConnected: Outgoing connection to peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260]
D/io.jxcore.node.ConnectionHelper( 3300): hasConnection: No connection with peer with ID 7C:F9:0E:51:18:22
W/io.jxcore.node.ConnectionHelper( 3300): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 3300): onConnected: Outgoing socket thread, for peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 3300): onConnected: The total number of connections is now 1
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3300): Exiting thread (ID: 383)
,D/io.jxcore.node.OutgoingSocketThread( 3300): Entering thread (ID: 384)
D/io.jxcore.node.OutgoingSocketThread( 3300): Server socket local port: 51099
I/io.jxcore.node.OutgoingSocketThread( 3300): Now accepting connections...
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9541], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9541]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): restart: Restarting...
,D/WifiP2pManager( 3300): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/io.jxcore.node.ConnectionHelper( 3300): onListeningForIncomingConnections: Outgoing connection is using port 51099 (peer ID: 7C:F9:0E:51:18:22)
,I/jxcore-log( 3300): 2015-12-19T01:43:43.267Z SendDataConnector.js: CLIENT connected to 51099, error: null
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:43:43.270Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3300): 
,I/io.jxcore.node.OutgoingSocketThread( 3300): Incoming data from address: /127.0.0.1, port: 51099
D/io.jxcore.node.OutgoingSocketThread( 3300): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3300): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3300): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3300): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3300): Exiting thread (ID: 384)
,I/jxcore-log( 3300): 2015-12-19T01:43:43.295Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3300): 
,D/io.jxcore.node.StreamCopyingThread( 3300): Entering thread (ID: 385, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 3300): Entering thread (ID: 386, name: Receiver)
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9541], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9541]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
,D/        ( 2107): PORT_WriteDataCO: tx queue is full,tx.queue_size:10172,tx.queue.count:11,available:24706
,I/jxcore-log( 3300): 2015-12-19T01:43:43.857Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3300): 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3300): 2015-12-19T01:43:44.086Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3300): 
,I/wpa_supplicant( 1034): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,D/        ( 2107): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:14806
,I/jxcore-log( 3300): 2015-12-19T01:43:44.180Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3300): 
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1034): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9541], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9541]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9541], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9541]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
,I/jxcore-log( 3300): 2015-12-19T01:43:44.655Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3300): 
,D/        ( 2107): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:3916
,I/jxcore-log( 3300): 2015-12-19T01:43:44.735Z SendDataConnector.js: CLIENT is data received : 50000,
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:43:44.784Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:43:44.823Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:43:44.919Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:43:45.234Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:43:45.394Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3300): 
I/jxcore-log( 3300): 2015-12-19T01:43:45.395Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3300): 
I/jxcore-log( 3300): oneRoundDownNow
I/jxcore-log( 3300): 
I/jxcore-log( 3300): 2015-12-19T01:43:45.396Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3300): 
I/jxcore-log( 3300): 2015-12-19T01:43:45.396Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3300): 
,D/io.jxcore.node.ConnectionHelper( 3300): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:51:18:22
I/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 7C:F9:0E:51:18:22
I/io.jxcore.node.OutgoingSocketThread( 3300): close
D/io.jxcore.node.OutgoingSocketThread( 3300): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3300): doStop: Thread ID: 386
D/io.jxcore.node.OutgoingSocketThread( 3300): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3300): doStop: Thread ID: 385
D/io.jxcore.node.OutgoingSocketThread( 3300): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 3300): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3300): Either failed to read from the output stream or write to the input stream (thread ID: 385, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3300): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3300): onDisconnected: Outgoing connection, peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 3300): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 3300): closeLocalSocketAndStreams: Closing the localhost socket...
,I/io.jxcore.node.OutgoingSocketThread( 3300): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3300): Either failed to read from the output stream or write to the input stream (thread ID: 386, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.OutgoingSocketThread( 3300): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3300): onDisconnected: Outgoing connection, peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3300): disconnectOutgoingConnection: Successfully disconnected (peer ID: 7C:F9:0E:51:18:22
,W/bt-btif ( 2107): bta_jv_rfc_port_to_cb(port_handle:0x14):jv handle:0x0 not FOUND
,E/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3300): Exiting thread (ID: 385, name: Sender)
E/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3300): Exiting thread (ID: 386, name: Receiver)
,I/jxcore-log( 3300): 2015-12-19T01:43:45.436Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3300): 
I/jxcore-log( 3300): ---- round done--------
I/jxcore-log( 3300): 
I/jxcore-log( 3300): startWithNextDevice
I/jxcore-log( 3300): 
,D/btif_config_util( 2107): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2107): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2107): onReceive
,I/BTConnectionReceiver( 1456): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:51:18:22, alias=null, name=Thali Test (Galaxy A5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1456): Bluetooth Device Name: Thali Test (Galaxy A5)
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT4591","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT4591]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onServiceDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT4591]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT4591]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT4591], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Adding new peer: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT4591]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9541], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9541]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9541], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9541]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
I/io.jxcore.node.ConnectionHelper( 3300): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT4591], Bluetooth address: E0:DB:10:14:E2:C0, device name: Note4-1, device address: 92:b6:86:43:73:1c
D/io.jxcore.node.ConnectionHelper( 3300): notifyPeerAvailability: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT4591] is available
,I/jxcore-log( 3300): peerAvailabilityChanged [{"peerIdentifier":"E0:DB:10:14:E2:C0","peerName":"samsung-SM-N910C_PT4591","peerAvailable":true}]
I/jxcore-log( 3300): 
I/jxcore-log( 3300): Found peer : samsung-SM-N910C_PT4591, Available: true
I/jxcore-log( 3300): 
I/jxcore-log( 3300): startWithNextDevice
I/jxcore-log( 3300): 
I/jxcore-log( 3300): device[9]: E0:DB:10:14:E2:C0
I/jxcore-log( 3300): 
I/jxcore-log( 3300): 2015-12-19T01:43:55.220Z SendDataConnector.js: Start called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3300): 
I/jxcore-log( 3300): 2015-12-19T01:43:55.220Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3300): 
I/jxcore-log( 3300): 2015-12-19T01:43:55.220Z SendDataConnector.js: do connect now
I/jxcore-log( 3300): 
,I/io.jxcore.node.ConnectionHelper( 3300): connect: Trying to connect to peer with ID E0:DB:10:14:E2:C0
D/io.jxcore.node.ConnectionHelper( 3300): hasConnection: No connection with peer with ID E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): connect: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT4591]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): connect: Trying to start connecting to null in address E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): onConnecting: null E0:DB:10:14:E2:C0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): connect: Started connecting to null in address E0:DB:10:14:E2:C0
I/io.jxcore.node.ConnectionHelper( 3300): connect: Connection process successfully started (peer ID: E0:DB:10:14:E2:C0)
,D/WifiP2pManager( 3300): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): Trying to connect to peer with address E0:DB:10:14:E2:C0 (thread ID: 387)
W/BluetoothAdapter( 3300): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2107): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9541], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9541]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
,W/bt-btif ( 2107): info:x10
,D/        ( 2107): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,E/BluetoothRemoteDevices( 2107): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2107): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2107): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 1
E/bt-btif ( 2107): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2107): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 2107): Entering PendingCommandState State
,W/BluetoothEventManager( 2714): CachedBluetoothDevice for device E0:DB:10:14:E2:C0 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2714): Got bonding state changed for E0:DB:10:14:E2:C0, but we have no record of that device.
,I/BluetoothBondStateMachine( 2107): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 0
,D/BluetoothAdapterProperties( 2107): Failed to remove device: E0:DB:10:14:E2:C0
,I/BluetoothBondStateMachine( 2107): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2107): StableState(): Entering Off State
,W/BluetoothEventManager( 2714): CachedBluetoothDevice for device E0:DB:10:14:E2:C0 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2714): Got bonding state changed for E0:DB:10:14:E2:C0, but we have no record of that device.
,W/bt-btif ( 2107): new conn_srvc id:26, app_id:1
W/bt-btif ( 2107): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 2107): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): onSocketConnected: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT4591]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 387)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): onBytesWritten: 77 bytes successfully written (thread ID: 388)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): Outgoing connection initialized (*handshake* thread ID: 388)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): Exiting thread (thread ID: 387)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3300): Entering thread (ID: 388)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): onBytesRead: Read 82 bytes successfully (thread ID: 388)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): Handshake succeeded with [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT4591]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): onHandshakeSucceeded: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT4591]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): onConnected: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT4591]
I/io.jxcore.node.ConnectionHelper( 3300): onConnected: Outgoing connection to peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT4591]
,D/io.jxcore.node.ConnectionHelper( 3300): hasConnection: No connection with peer with ID E0:DB:10:14:E2:C0
,W/io.jxcore.node.ConnectionHelper( 3300): modifyListOfDiscoveredPeers: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT4591] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 3300): onConnected: Outgoing socket thread, for peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT4591], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 3300): onConnected: The total number of connections is now 1
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3300): Exiting thread (ID: 388)
,D/io.jxcore.node.OutgoingSocketThread( 3300): Entering thread (ID: 389)
,D/io.jxcore.node.OutgoingSocketThread( 3300): Server socket local port: 42684
I/io.jxcore.node.OutgoingSocketThread( 3300): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3300): onListeningForIncomingConnections: Outgoing connection is using port 42684 (peer ID: E0:DB:10:14:E2:C0)
I/jxcore-log( 3300): 2015-12-19T01:43:58.206Z SendDataConnector.js: CLIENT connected to 42684, error: null
I/jxcore-log( 3300): 
I/jxcore-log( 3300): 2015-12-19T01:43:58.207Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3300): 
,I/io.jxcore.node.OutgoingSocketThread( 3300): Incoming data from address: /127.0.0.1, port: 42684
D/io.jxcore.node.OutgoingSocketThread( 3300): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3300): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3300): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3300): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3300): Exiting thread (ID: 389)
,I/jxcore-log( 3300): 2015-12-19T01:43:58.237Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3300): 
,D/io.jxcore.node.StreamCopyingThread( 3300): Entering thread (ID: 391, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3300): Entering thread (ID: 390, name: Sender)
,I/jxcore-log( 3300): 2015-12-19T01:43:58.920Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:43:59.441Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:43:59.715Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:44:00.314Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:44:00.848Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:44:01.161Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:44:01.662Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:44:01.702Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:44:01.754Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:44:01.759Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3300): 
I/jxcore-log( 3300): oneRoundDownNow
I/jxcore-log( 3300): 
I/jxcore-log( 3300): 2015-12-19T01:44:01.761Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3300): 
I/jxcore-log( 3300): 2015-12-19T01:44:01.762Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3300): 
D/io.jxcore.node.ConnectionHelper( 3300): disconnectOutgoingConnection: Trying to close connection to peer with ID E0:DB:10:14:E2:C0
I/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: E0:DB:10:14:E2:C0
I/io.jxcore.node.OutgoingSocketThread( 3300): close
D/io.jxcore.node.OutgoingSocketThread( 3300): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3300): doStop: Thread ID: 391
D/io.jxcore.node.OutgoingSocketThread( 3300): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3300): doStop: Thread ID: 390
D/io.jxcore.node.OutgoingSocketThread( 3300): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 3300): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3300): Either failed to read from the output stream or write to the input stream (thread ID: 390, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3300): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3300): onDisconnected: Outgoing connection, peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT4591] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 3300): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 3300): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3300): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3300): Either failed to read from the output stream or write to the input stream (thread ID: 391, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 3300): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3300): onDisconnected: Outgoing connection, peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT4591] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3300): disconnectOutgoingConnection: Successfully disconnected (peer ID: E0:DB:10:14:E2:C0
,E/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID E0:DB:10:14:E2:C0
D/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3300): Exiting thread (ID: 390, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID E0:DB:10:14:E2:C0
,D/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,D/io.jxcore.node.StreamCopyingThread( 3300): Exiting thread (ID: 391, name: Receiver)
,I/jxcore-log( 3300): 2015-12-19T01:44:01.807Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): ---- round done--------
I/jxcore-log( 3300): 
I/jxcore-log( 3300): startWithNextDevice
I/jxcore-log( 3300): 
,W/bt-btif ( 2107): bta_jv_rfc_port_to_cb(port_handle:0x15):jv handle:0x0 not FOUND
,D/btif_config_util( 2107): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2107): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2107): onReceive
,I/BTConnectionReceiver( 1456): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1456): Bluetooth Device Name: Note4-1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: RESTARTING
,I/wpa_supplicant( 1034): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Start timer timeout, starting now...
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): restart: Restarting...
,D/WifiP2pManager( 3300): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9326","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
I/io.jxcore.node.ConnectionHelper( 3300): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: a2:39:f7:6f:c9:5d
,W/io.jxcore.node.ConnectionHelper( 3300): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT317","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT317]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT317]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT317]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT317], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT317]
I/io.jxcore.node.ConnectionHelper( 3300): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT317], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
D/io.jxcore.node.ConnectionHelper( 3300): notifyPeerAvailability: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT317] is available
I/jxcore-log( 3300): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:85:54","peerName":"LGE-LG-D722_PT317","peerAvailable":true}]
I/jxcore-log( 3300): 
I/jxcore-log( 3300): startWithNextDevice
I/jxcore-log( 3300): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT9642","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642]
I/io.jxcore.node.ConnectionHelper( 3300): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
W/io.jxcore.node.ConnectionHelper( 3300): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642] already in the list, will not add again
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1034): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1034): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT317], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT317]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT317], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT317]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT317], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT317]
,D/WifiP2pManager( 3300): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1034): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT317], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT317]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT317], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT317]
,I/ActivityManager(  758): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=3839 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,I/GAv4    ( 3839): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3839):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3839):   adb logcat -s GAv4
,W/GAv4    ( 3839): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3839): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3839): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  758): Killing 2002:com.google.android.calendar/u0a31 (adj 15): empty #17
,W/libprocessgroup(  758): failed to open /acct/uid_10031/pid_2002/cgroup.procs: No such file or directory
,W/bt-btif ( 2107): info:x10
,D/        ( 2107): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,I/BTConnectionReceiver( 1456): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1456): Bluetooth Device Name: Note4-1
,W/bt-btif ( 2107): new conn_srvc id:26, app_id:255
W/bt-btif ( 2107): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2107): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): Incoming connection initialized (thread ID: 392)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3300): Entering thread (ID: 392)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): onBytesRead: Read 82 bytes successfully (thread ID: 392)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): Got valid identity from [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT4591]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): onBytesWritten: 77 bytes successfully written (thread ID: 392)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): removeThreadFromList: Removing thread with ID 392
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): Handshake thread disposed (thread ID: 392)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): onIncomingConnectionConnected: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT4591]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3300): Exiting thread (ID: 392)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): onConnected: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT4591]
,I/io.jxcore.node.ConnectionHelper( 3300): onConnected: Incoming connection to peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT4591]
D/io.jxcore.node.ConnectionHelper( 3300): hasConnection: No connection with peer with ID E0:DB:10:14:E2:C0
W/io.jxcore.node.ConnectionHelper( 3300): modifyListOfDiscoveredPeers: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT4591] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 3300): onConnected: Incoming socket thread, for peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT4591], created successfully
,D/io.jxcore.node.ConnectionHelper( 3300): onConnected: The total number of connections is now 1
,D/io.jxcore.node.IncomingSocketThread( 3300): Entering thread (ID: 393)
,I/jxcore-log( 3300): 2015-12-19T01:45:07.715Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3300): 
,I/io.jxcore.node.IncomingSocketThread( 3300): Local host address: localhost/127.0.0.1, port: 34900
D/io.jxcore.node.IncomingSocketThread( 3300): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3300): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 3300): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.IncomingSocketThread( 3300): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3300): Exiting thread (ID: 393)
,D/io.jxcore.node.StreamCopyingThread( 3300): Entering thread (ID: 395, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3300): Entering thread (ID: 394, name: Sender)
,I/jxcore-log( 3300): 2015-12-19T01:45:08.436Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:45:08.448Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:45:08.501Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:45:08.507Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:45:08.561Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:45:08.568Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:45:08.580Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:45:08.617Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:45:08.683Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:45:08.687Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:45:08.736Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:45:08.802Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:45:08.839Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:45:08.846Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:45:08.905Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:45:08.924Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:45:08.935Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:45:08.971Z SendDataTCPServer.js: TCP/IP server has received 35640 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:45:08.984Z SendDataTCPServer.js: TCP/IP server has received 41580 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:45:08.996Z SendDataTCPServer.js: TCP/IP server has received 47520 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:45:09.032Z SendDataTCPServer.js: TCP/IP server has received 61380 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:45:09.047Z SendDataTCPServer.js: TCP/IP server has received 69300 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:45:09.110Z SendDataTCPServer.js: TCP/IP server has received 89100 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:45:09.117Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:45:09.120Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:45:09.158Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3300): 
,W/bt-btif ( 2107): invalid rfc slot id: 25
,W/io.jxcore.node.StreamCopyingThread( 3300): Either failed to read from the output stream or write to the input stream (thread ID: 395, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 3300): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3300): onDisconnected: Incoming connection, peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT4591] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 393
D/io.jxcore.node.IncomingSocketThread( 3300): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3300): doStop: Thread ID: 395
D/io.jxcore.node.IncomingSocketThread( 3300): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3300): doStop: Thread ID: 394
D/io.jxcore.node.IncomingSocketThread( 3300): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 3300): closeLocalSocketAndStreams: Closing the local input stream...
D/io.jxcore.node.IncomingSocketThread( 3300): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 3300): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3300): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3300): Exiting thread (ID: 395, name: Receiver)
,W/io.jxcore.node.StreamCopyingThread( 3300): Either failed to read from the output stream or write to the input stream (thread ID: 394, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3300): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3300): onDisconnected: Incoming connection, peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT4591] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3300): Exiting thread (ID: 394, name: Sender)
,I/jxcore-log( 3300): 2015-12-19T01:45:09.198Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3300): 
,W/bt-rfcomm( 2107): rfc_find_lcid_mcb LCID reused LCID:0x45 current:0x0
W/bt-rfcomm( 2107): RFCOMM_DisconnectInd LCID:0x45
,D/btif_config_util( 2107): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): checkListForExpiredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9541] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9541], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Removed [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9541]
I/io.jxcore.node.ConnectionHelper( 3300): onPeerLost: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9541]
D/io.jxcore.node.ConnectionHelper( 3300): hasConnection: No connection with peer with ID B0:C5:59:3F:75:69
D/io.jxcore.node.ConnectionHelper( 3300): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9541] removed
D/io.jxcore.node.ConnectionHelper( 3300): notifyPeerAvailability: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9541] not available
I/jxcore-log( 3300): peerAvailabilityChanged [{"peerIdentifier":"B0:C5:59:3F:75:69","peerName":"samsung-SM-G900F_PT9541","peerAvailable":false}]
I/jxcore-log( 3300): 
I/jxcore-log( 3300): startWithNextDevice
I/jxcore-log( 3300): 
,E/bt-btm  ( 2107): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2107): onReceive
,I/BTConnectionReceiver( 1456): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1456): Bluetooth Device Name: Note4-1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: RESTARTING
,I/wpa_supplicant( 1034): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Start timer timeout, starting now...
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT317], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT317]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
,D/WifiP2pManager( 3300): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): restart: Restarting...
,D/WifiP2pManager( 3300): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT5260","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260]
I/io.jxcore.node.ConnectionHelper( 3300): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
W/io.jxcore.node.ConnectionHelper( 3300): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT5943","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT5943]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5943]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5943]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5943], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT5943]
I/io.jxcore.node.ConnectionHelper( 3300): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5943], Bluetooth address: 58:3F:54:73:64:C0, device name: , device address: 02:9a:02:7b:60:ac
D/io.jxcore.node.ConnectionHelper( 3300): notifyPeerAvailability: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5943] is available
,I/jxcore-log( 3300): peerAvailabilityChanged [{"peerIdentifier":"58:3F:54:73:64:C0","peerName":"LGE-LG-D855_PT5943","peerAvailable":true}]
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): Found peer : LGE-LG-D855_PT5943, Available: true
I/jxcore-log( 3300): 
I/jxcore-log( 3300): startWithNextDevice
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): device[10]: 58:3F:54:73:64:C0
I/jxcore-log( 3300): 
I/jxcore-log( 3300): 2015-12-19T01:45:44.823Z SendDataConnector.js: Start called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3300): 
I/jxcore-log( 3300): 2015-12-19T01:45:44.824Z SendDataConnector.js: doConnect called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3300): 
I/jxcore-log( 3300): 2015-12-19T01:45:44.824Z SendDataConnector.js: do connect now
I/jxcore-log( 3300): 
I/io.jxcore.node.ConnectionHelper( 3300): connect: Trying to connect to peer with ID 58:3F:54:73:64:C0
D/io.jxcore.node.ConnectionHelper( 3300): hasConnection: No connection with peer with ID 58:3F:54:73:64:C0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): connect: [58:3F:54:73:64:C0 LGE-LG-D855_PT5943]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): connect: Trying to start connecting to null in address 58:3F:54:73:64:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): setMaxNumberOfRetries: 0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): onConnecting: null 58:3F:54:73:64:C0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): connect: Started connecting to null in address 58:3F:54:73:64:C0
I/io.jxcore.node.ConnectionHelper( 3300): connect: Connection process successfully started (peer ID: 58:3F:54:73:64:C0)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): Trying to connect to peer with address 58:3F:54:73:64:C0 (thread ID: 396)
W/BluetoothAdapter( 3300): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2107): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2107): info:x10
,D/        ( 2107): remote version info [58:3f:54:73:64:c0]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 2107): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2107): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2107): bondStateChangeCallback: Status: 0 Address: 58:3F:54:73:64:C0 newState: 1
E/bt-btif ( 2107): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2107): Bond State Change Intent:58:3F:54:73:64:C0 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2107): Entering PendingCommandState State
,W/BluetoothEventManager( 2714): CachedBluetoothDevice for device 58:3F:54:73:64:C0 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2714): Got bonding state changed for 58:3F:54:73:64:C0, but we have no record of that device.
,I/BluetoothBondStateMachine( 2107): bondStateChangeCallback: Status: 0 Address: 58:3F:54:73:64:C0 newState: 0
,D/BluetoothAdapterProperties( 2107): Failed to remove device: 58:3F:54:73:64:C0
,I/BluetoothBondStateMachine( 2107): Bond State Change Intent:58:3F:54:73:64:C0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2107): StableState(): Entering Off State
,W/BluetoothEventManager( 2714): CachedBluetoothDevice for device 58:3F:54:73:64:C0 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2714): Got bonding state changed for 58:3F:54:73:64:C0, but we have no record of that device.
,W/bt-btif ( 2107): new conn_srvc id:26, app_id:1
W/bt-btif ( 2107): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2107): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): onSocketConnected: [58:3F:54:73:64:C0 LGE-LG-D855_PT5943]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 396)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): onBytesWritten: 77 bytes successfully written (thread ID: 397)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): Outgoing connection initialized (*handshake* thread ID: 397)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): Exiting thread (thread ID: 396)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3300): Entering thread (ID: 397)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): onBytesRead: Read 77 bytes successfully (thread ID: 397)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): Handshake succeeded with [58:3F:54:73:64:C0 LGE-LG-D855_PT5943]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): onHandshakeSucceeded: [58:3F:54:73:64:C0 LGE-LG-D855_PT5943]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): onConnected: [58:3F:54:73:64:C0 LGE-LG-D855_PT5943]
I/io.jxcore.node.ConnectionHelper( 3300): onConnected: Outgoing connection to peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5943]
,D/io.jxcore.node.ConnectionHelper( 3300): hasConnection: No connection with peer with ID 58:3F:54:73:64:C0
W/io.jxcore.node.ConnectionHelper( 3300): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5943] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 3300): onConnected: Outgoing socket thread, for peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5943], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 3300): onConnected: The total number of connections is now 1
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3300): Exiting thread (ID: 397)
,D/io.jxcore.node.OutgoingSocketThread( 3300): Entering thread (ID: 398)
,D/io.jxcore.node.OutgoingSocketThread( 3300): Server socket local port: 59155
I/io.jxcore.node.OutgoingSocketThread( 3300): Now accepting connections...
,W/bt-btif ( 2107): new conn_srvc id:26, app_id:255
W/bt-btif ( 2107): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2107): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2107): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): Incoming connection initialized (thread ID: 399)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3300): Entering thread (ID: 399)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): onBytesRead: Read 77 bytes successfully (thread ID: 399)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): Got valid identity from [58:3F:54:73:64:C0 LGE-LG-D855_PT5943]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): onBytesWritten: 77 bytes successfully written (thread ID: 399)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): removeThreadFromList: Removing thread with ID 399
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): Handshake thread disposed (thread ID: 399)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): onIncomingConnectionConnected: [58:3F:54:73:64:C0 LGE-LG-D855_PT5943]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): onConnected: [58:3F:54:73:64:C0 LGE-LG-D855_PT5943]
I/io.jxcore.node.ConnectionHelper( 3300): onConnected: Incoming connection to peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5943]
D/io.jxcore.node.ConnectionHelper( 3300): hasConnection: We have an outgoing connection with peer with ID 58:3F:54:73:64:C0
W/io.jxcore.node.ConnectionHelper( 3300): onConnected: Already connected with peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5943], continuing anyway...
W/io.jxcore.node.ConnectionHelper( 3300): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5943] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 3300): onConnected: Incoming socket thread, for peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5943], created successfully
D/io.jxcore.node.ConnectionHelper( 3300): onConnected: The total number of connections is now 2
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3300): Exiting thread (ID: 399)
,D/io.jxcore.node.IncomingSocketThread( 3300): Entering thread (ID: 400)
,I/io.jxcore.node.IncomingSocketThread( 3300): Local host address: localhost/127.0.0.1, port: 34900
D/io.jxcore.node.IncomingSocketThread( 3300): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3300): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 3300): setBufferSize: Setting buffer size to 8192 bytes
,I/jxcore-log( 3300): 2015-12-19T01:45:47.092Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3300): 
,I/io.jxcore.node.IncomingSocketThread( 3300): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3300): Exiting thread (ID: 400)
,D/io.jxcore.node.StreamCopyingThread( 3300): Entering thread (ID: 402, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3300): Entering thread (ID: 401, name: Sender)
,I/io.jxcore.node.ConnectionHelper( 3300): onListeningForIncomingConnections: Outgoing connection is using port 59155 (peer ID: 58:3F:54:73:64:C0)
I/jxcore-log( 3300): 2015-12-19T01:45:47.311Z SendDataConnector.js: CLIENT connected to 59155, error: null
I/jxcore-log( 3300): 
I/jxcore-log( 3300): 2015-12-19T01:45:47.311Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3300): 
,I/io.jxcore.node.IncomingSocketThread( 3300): Incoming data from address: /127.0.0.1, port: 59155
D/io.jxcore.node.IncomingSocketThread( 3300): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3300): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3300): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3300): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3300): Exiting thread (ID: 398)
,I/jxcore-log( 3300): 2015-12-19T01:45:47.334Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3300): 
,D/io.jxcore.node.StreamCopyingThread( 3300): Entering thread (ID: 404, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3300): Entering thread (ID: 403, name: Sender)
,D/        ( 2107): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23716
,I/jxcore-log( 3300): 2015-12-19T01:45:48.034Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:45:48.044Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:45:48.048Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:45:48.057Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:45:48.097Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3300): 
,D/        ( 2107): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:13816
,I/jxcore-log( 3300): 2015-12-19T01:45:48.133Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:45:48.140Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:45:48.157Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:45:48.189Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:45:48.256Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:45:48.328Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:45:48.462Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:45:48.499Z SendDataTCPServer.js: TCP/IP server has received 34748 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:45:48.618Z SendDataTCPServer.js: TCP/IP server has received 36728 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:45:48.638Z SendDataTCPServer.js: TCP/IP server has received 38708 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:45:48.645Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:45:48.656Z SendDataTCPServer.js: TCP/IP server has received 44648 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:45:48.691Z SendDataTCPServer.js: TCP/IP server has received 48608 bytes of data
I/jxcore-log( 3300): 
,D/        ( 2107): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:3916
,I/jxcore-log( 3300): 2015-12-19T01:45:48.704Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:45:48.711Z SendDataTCPServer.js: TCP/IP server has received 54548 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:45:48.722Z SendDataTCPServer.js: TCP/IP server has received 58508 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:45:48.770Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3300): 
I/jxcore-log( 3300): 2015-12-19T01:45:48.772Z SendDataTCPServer.js: TCP/IP server has received 72368 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:45:48.881Z SendDataTCPServer.js: TCP/IP server has received 74348 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:45:48.899Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:45:48.918Z SendDataTCPServer.js: TCP/IP server has received 78308 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:45:48.930Z SendDataTCPServer.js: TCP/IP server has received 80288 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:45:49.031Z SendDataTCPServer.js: TCP/IP server has received 82268 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:45:49.072Z SendDataTCPServer.js: TCP/IP server has received 86228 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:45:49.163Z SendDataTCPServer.js: TCP/IP server has received 88208 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:45:49.237Z SendDataTCPServer.js: TCP/IP server has received 90188 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:45:49.250Z SendDataTCPServer.js: TCP/IP server has received 98108 bytes of data
I/jxcore-log( 3300): 
I/jxcore-log( 3300): 2015-12-19T01:45:49.253Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:45:49.263Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:45:49.323Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3300): 
I/jxcore-log( 3300): 2015-12-19T01:45:49.323Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3300): 
I/jxcore-log( 3300): oneRoundDownNow
I/jxcore-log( 3300): 
I/jxcore-log( 3300): 2015-12-19T01:45:49.323Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3300): 
I/jxcore-log( 3300): 2015-12-19T01:45:49.323Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3300): 
D/io.jxcore.node.ConnectionHelper( 3300): disconnectOutgoingConnection: Trying to close connection to peer with ID 58:3F:54:73:64:C0
I/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 58:3F:54:73:64:C0
I/io.jxcore.node.IncomingSocketThread( 3300): close
D/io.jxcore.node.IncomingSocketThread( 3300): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3300): doStop: Thread ID: 404
D/io.jxcore.node.IncomingSocketThread( 3300): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3300): doStop: Thread ID: 403
D/io.jxcore.node.IncomingSocketThread( 3300): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 3300): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3300): Either failed to read from the output stream or write to the input stream (thread ID: 403, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3300): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3300): onDisconnected: Outgoing connection, peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5943] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.IncomingSocketThread( 3300): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 3300): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3300): closeBluetoothSocketAndStreams
W/io.jxcore.node.StreamCopyingThread( 3300): Either failed to read from the output stream or write to the input stream (thread ID: 404, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 3300): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3300): onDisconnected: Outgoing connection, peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5943] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3300): disconnectOutgoingConnection: Successfully disconnected (peer ID: 58:3F:54:73:64:C0
,E/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 58:3F:54:73:64:C0
D/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,E/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 58:3F:54:73:64:C0
D/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3300): Exiting thread (ID: 404, name: Receiver)
D/io.jxcore.node.StreamCopyingThread( 3300): Exiting thread (ID: 403, name: Sender)
,I/jxcore-log( 3300): 2015-12-19T01:45:49.330Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:3F:54:73:64:C0
I/jxcore-log( 3300): 
I/jxcore-log( 3300): ---- round done--------
I/jxcore-log( 3300): 
I/jxcore-log( 3300): startWithNextDevice
I/jxcore-log( 3300): 
,W/bt-btif ( 2107): invalid rfc slot id: 29
,W/io.jxcore.node.StreamCopyingThread( 3300): Either failed to read from the output stream or write to the input stream (thread ID: 402, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 3300): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3300): onDisconnected: Incoming connection, peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5943] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 400
D/io.jxcore.node.IncomingSocketThread( 3300): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3300): doStop: Thread ID: 402
D/io.jxcore.node.IncomingSocketThread( 3300): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3300): doStop: Thread ID: 401
D/io.jxcore.node.IncomingSocketThread( 3300): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 3300): closeLocalSocketAndStreams: Closing the local input stream...
D/io.jxcore.node.IncomingSocketThread( 3300): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 3300): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3300): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3300): Exiting thread (ID: 402, name: Receiver)
,W/io.jxcore.node.StreamCopyingThread( 3300): Either failed to read from the output stream or write to the input stream (thread ID: 401, thread name: Sender): Socket closed
,E/io.jxcore.node.IncomingSocketThread( 3300): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3300): onDisconnected: Incoming connection, peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5943] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3300): Exiting thread (ID: 401, name: Sender)
,I/jxcore-log( 3300): 2015-12-19T01:45:49.353Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3300): 
,W/bt-btif ( 2107): bta_jv_rfc_port_to_cb(port_handle:0x17):jv handle:0x0 not FOUND
,D/btif_config_util( 2107): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2107): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2107): onReceive
,I/BTConnectionReceiver( 1456): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1456): Bluetooth Device Name: G3-1
,I/GoogleURLConnFactory( 1627): Using platform SSLCertificateSocketFactory
,I/PhenotypeConfigurator( 1627): Scheduling Phenotype every 14400 seconds, with flex of 1800 seconds
,W/PhenotypeConfigurator( 1627): Server returned 404
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): checkListForExpiredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Removed [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642]
I/io.jxcore.node.ConnectionHelper( 3300): onPeerLost: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642]
D/io.jxcore.node.ConnectionHelper( 3300): hasConnection: No connection with peer with ID 7C:F9:0E:34:8A:A0
D/io.jxcore.node.ConnectionHelper( 3300): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642] removed
D/io.jxcore.node.ConnectionHelper( 3300): notifyPeerAvailability: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642] not available
I/jxcore-log( 3300): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:34:8A:A0","peerName":"samsung-SM-G900F_PT9642","peerAvailable":false}]
I/jxcore-log( 3300): 
I/jxcore-log( 3300): startWithNextDevice
I/jxcore-log( 3300): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: RESTARTING
,I/wpa_supplicant( 1034): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Start timer timeout, starting now...
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1034): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5943], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5943]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5943], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5943]
,D/WifiP2pManager( 3300): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5943], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5943]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1034): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT5260","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260]
I/io.jxcore.node.ConnectionHelper( 3300): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
W/io.jxcore.node.ConnectionHelper( 3300): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: RESTARTING
,I/wpa_supplicant( 1034): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery started successfully
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): restart: Restarting...
,D/WifiP2pManager( 3300): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
,W/bt-btif ( 2107): info:x10
,D/        ( 2107): remote version info [90:e7:c4:f6:69:77]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2107): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BluetoothBondStateMachine( 2107): bondStateChangeCallback: Status: 0 Address: 90:E7:C4:F6:69:77 newState: 1
E/bt-btif ( 2107): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2107): Bond State Change Intent:90:E7:C4:F6:69:77 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2107): Entering PendingCommandState State
,W/BluetoothEventManager( 2714): CachedBluetoothDevice for device 90:E7:C4:F6:69:77 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2714): Got bonding state changed for 90:E7:C4:F6:69:77, but we have no record of that device.
,I/BluetoothBondStateMachine( 2107): bondStateChangeCallback: Status: 0 Address: 90:E7:C4:F6:69:77 newState: 0
,D/BluetoothAdapterProperties( 2107): Failed to remove device: 90:E7:C4:F6:69:77
,I/BluetoothBondStateMachine( 2107): Bond State Change Intent:90:E7:C4:F6:69:77 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2107): StableState(): Entering Off State
,W/BluetoothEventManager( 2714): CachedBluetoothDevice for device 90:E7:C4:F6:69:77 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2714): Got bonding state changed for 90:E7:C4:F6:69:77, but we have no record of that device.
,W/bt-btif ( 2107): new conn_srvc id:26, app_id:255
W/bt-btif ( 2107): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2107): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): Incoming connection initialized (thread ID: 405)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3300): Entering thread (ID: 405)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): onBytesRead: Read 81 bytes successfully (thread ID: 405)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): Got valid identity from [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514]
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): onBytesWritten: 77 bytes successfully written (thread ID: 405)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): removeThreadFromList: Removing thread with ID 405
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): Handshake thread disposed (thread ID: 405)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): onIncomingConnectionConnected: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3300): Exiting thread (ID: 405)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): onConnected: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514]
I/io.jxcore.node.ConnectionHelper( 3300): onConnected: Incoming connection to peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514]
,D/io.jxcore.node.ConnectionHelper( 3300): hasConnection: No connection with peer with ID 90:E7:C4:F6:69:77
D/io.jxcore.node.ConnectionHelper( 3300): notifyPeerAvailability: Peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514] is available
,I/jxcore-log( 3300): peerAvailabilityChanged [{"peerIdentifier":"90:E7:C4:F6:69:77","peerName":"HTC-HTC One M8s_PT8514","peerAvailable":true}]
I/jxcore-log( 3300): 
I/jxcore-log( 3300): Found peer : HTC-HTC One M8s_PT8514, Available: true
I/jxcore-log( 3300): 
I/jxcore-log( 3300): startWithNextDevice
I/jxcore-log( 3300): 
I/jxcore-log( 3300): device[11]: 90:E7:C4:F6:69:77
I/jxcore-log( 3300): 
I/jxcore-log( 3300): 2015-12-19T01:47:12.163Z SendDataConnector.js: Start called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3300): 
I/jxcore-log( 3300): 2015-12-19T01:47:12.164Z SendDataConnector.js: doConnect called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3300): 
I/jxcore-log( 3300): 2015-12-19T01:47:12.164Z SendDataConnector.js: do connect now
I/jxcore-log( 3300): 
I/io.jxcore.node.ConnectionHelper( 3300): connect: Trying to connect to peer with ID 90:E7:C4:F6:69:77
D/io.jxcore.node.ConnectionHelper( 3300): hasConnection: No connection with peer with ID 90:E7:C4:F6:69:77
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): connect: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): connect: Trying to start connecting to HTC One M8s in address 90:E7:C4:F6:69:77
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): setMaxNumberOfRetries: 0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): onConnecting: HTC One M8s 90:E7:C4:F6:69:77
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): connect: Started connecting to HTC One M8s in address 90:E7:C4:F6:69:77
I/io.jxcore.node.ConnectionHelper( 3300): connect: Connection process successfully started (peer ID: 90:E7:C4:F6:69:77)
I/io.jxcore.node.ConnectionHelper( 3300): onConnected: Incoming socket thread, for peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514], created successfully
D/io.jxcore.node.ConnectionHelper( 3300): onConnected: The total number of connections is now 1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): Trying to connect to peer with address 90:E7:C4:F6:69:77 (thread ID: 406)
W/BluetoothAdapter( 3300): getBluetoothService() called with no BluetoothManagerCallback
,D/io.jxcore.node.IncomingSocketThread( 3300): Entering thread (ID: 407)
,D/BTIF_SOCK( 2107): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/jxcore-log( 3300): 2015-12-19T01:47:12.197Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3300): 
,I/io.jxcore.node.IncomingSocketThread( 3300): Local host address: localhost/127.0.0.1, port: 34900
D/io.jxcore.node.IncomingSocketThread( 3300): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3300): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3300): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3300): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3300): Exiting thread (ID: 407)
,D/io.jxcore.node.StreamCopyingThread( 3300): Entering thread (ID: 409, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3300): Entering thread (ID: 408, name: Sender)
,W/bt-sdp  ( 2107): process_service_search_attr_rsp
,W/bt-btif ( 2107): new conn_srvc id:26, app_id:1
W/bt-btif ( 2107): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2107): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2107): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): onSocketConnected: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 406)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): onBytesWritten: 77 bytes successfully written (thread ID: 410)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): Outgoing connection initialized (*handshake* thread ID: 410)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): Exiting thread (thread ID: 406)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3300): Entering thread (ID: 410)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): onBytesRead: Read 81 bytes successfully (thread ID: 410)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3300): Handshake succeeded with [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): onHandshakeSucceeded: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3300): Exiting thread (ID: 410)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): onConnected: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514]
I/io.jxcore.node.ConnectionHelper( 3300): onConnected: Outgoing connection to peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514]
D/io.jxcore.node.ConnectionHelper( 3300): hasConnection: We have an incoming connection with peer with ID 90:E7:C4:F6:69:77
W/io.jxcore.node.ConnectionHelper( 3300): onConnected: Already connected with peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514], continuing anyway...
W/io.jxcore.node.ConnectionHelper( 3300): modifyListOfDiscoveredPeers: Peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 3300): onConnected: Outgoing socket thread, for peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 3300): onConnected: The total number of connections is now 2
,D/io.jxcore.node.OutgoingSocketThread( 3300): Entering thread (ID: 411)
D/io.jxcore.node.OutgoingSocketThread( 3300): Server socket local port: 48923
I/io.jxcore.node.OutgoingSocketThread( 3300): Now accepting connections...
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): restart: Restarting...
,D/WifiP2pManager( 3300): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/io.jxcore.node.ConnectionHelper( 3300): onListeningForIncomingConnections: Outgoing connection is using port 48923 (peer ID: 90:E7:C4:F6:69:77)
I/jxcore-log( 3300): 2015-12-19T01:47:12.654Z SendDataConnector.js: CLIENT connected to 48923, error: null
I/jxcore-log( 3300): 
I/jxcore-log( 3300): 2015-12-19T01:47:12.655Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3300): 
,I/io.jxcore.node.OutgoingSocketThread( 3300): Incoming data from address: /127.0.0.1, port: 48923
D/io.jxcore.node.OutgoingSocketThread( 3300): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3300): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3300): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3300): startStreamCopyingThreads: OK
,D/io.jxcore.node.OutgoingSocketThread( 3300): Exiting thread (ID: 411)
,D/io.jxcore.node.StreamCopyingThread( 3300): Entering thread (ID: 413, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3300): Entering thread (ID: 412, name: Sender)
,I/jxcore-log( 3300): 2015-12-19T01:47:12.701Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3300): 
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3300): 2015-12-19T01:47:13.111Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3300): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3300): 2015-12-19T01:47:13.160Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:47:13.215Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:47:13.226Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:47:13.243Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:47:13.278Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:47:13.313Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 3300): 
,D/        ( 2107): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23716
,I/jxcore-log( 3300): 2015-12-19T01:47:13.321Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:47:13.335Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:47:13.344Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3300): 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3300): 2015-12-19T01:47:13.443Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:47:13.486Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:47:13.517Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:47:13.526Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:47:13.584Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3300): 
,D/        ( 2107): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:15796
,I/jxcore-log( 3300): 2015-12-19T01:47:13.674Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:47:13.773Z SendDataTCPServer.js: TCP/IP server has received 35640 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:47:13.856Z SendDataTCPServer.js: TCP/IP server has received 37620 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:47:13.868Z SendDataTCPServer.js: TCP/IP server has received 39600 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:47:13.944Z SendDataTCPServer.js: TCP/IP server has received 41580 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:47:13.964Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data
I/jxcore-log( 3300): 
I/jxcore-log( 3300): 2015-12-19T01:47:13.967Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:47:13.999Z SendDataTCPServer.js: TCP/IP server has received 45540 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:47:14.044Z SendDataTCPServer.js: TCP/IP server has received 47520 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:47:14.060Z SendDataTCPServer.js: TCP/IP server has received 49500 bytes of data
I/jxcore-log( 3300): 
,D/        ( 2107): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:7876
,I/jxcore-log( 3300): 2015-12-19T01:47:14.075Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:47:14.082Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:47:14.122Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:47:14.138Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:47:14.169Z SendDataTCPServer.js: TCP/IP server has received 55440 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:47:14.210Z SendDataTCPServer.js: TCP/IP server has received 57420 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:47:14.224Z SendDataTCPServer.js: TCP/IP server has received 59400 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:47:14.236Z SendDataTCPServer.js: TCP/IP server has received 61380 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:47:14.246Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:47:14.252Z SendDataTCPServer.js: TCP/IP server has received 63360 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:47:14.305Z SendDataTCPServer.js: TCP/IP server has received 65340 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:47:14.320Z SendDataTCPServer.js: TCP/IP server has received 67320 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:47:14.332Z SendDataTCPServer.js: TCP/IP server has received 69300 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:47:14.388Z SendDataTCPServer.js: TCP/IP server has received 71280 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:47:14.408Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:47:14.478Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:47:14.494Z SendDataTCPServer.js: TCP/IP server has received 73260 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:47:14.529Z SendDataTCPServer.js: TCP/IP server has received 75240 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:47:14.582Z SendDataTCPServer.js: TCP/IP server has received 77220 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:47:14.593Z SendDataTCPServer.js: TCP/IP server has received 79200 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:47:14.604Z SendDataTCPServer.js: TCP/IP server has received 81180 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:47:14.667Z SendDataTCPServer.js: TCP/IP server has received 83160 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:47:14.705Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:47:14.712Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:47:14.749Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3300): 
I/jxcore-log( 3300): 2015-12-19T01:47:14.750Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): oneRoundDownNow
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:47:14.765Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3300): 
I/jxcore-log( 3300): 2015-12-19T01:47:14.765Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3300): 
,D/io.jxcore.node.ConnectionHelper( 3300): disconnectOutgoingConnection: Trying to close connection to peer with ID 90:E7:C4:F6:69:77
I/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 90:E7:C4:F6:69:77
,I/io.jxcore.node.OutgoingSocketThread( 3300): close
D/io.jxcore.node.OutgoingSocketThread( 3300): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3300): doStop: Thread ID: 413
,D/io.jxcore.node.OutgoingSocketThread( 3300): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3300): doStop: Thread ID: 412
D/io.jxcore.node.OutgoingSocketThread( 3300): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 3300): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3300): Either failed to read from the output stream or write to the input stream (thread ID: 412, thread name: Sender): Socket closed,
E/io.jxcore.node.OutgoingSocketThread( 3300): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3300): onDisconnected: Outgoing connection, peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 3300): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 3300): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3300): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3300): Either failed to read from the output stream or write to the input stream (thread ID: 413, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 3300): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3300): onDisconnected: Outgoing connection, peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3300): disconnectOutgoingConnection: Successfully disconnected (peer ID: 90:E7:C4:F6:69:77
,E/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 90:E7:C4:F6:69:77
D/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3300): Exiting thread (ID: 412, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 90:E7:C4:F6:69:77
D/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3300): Exiting thread (ID: 413, name: Receiver)
,I/jxcore-log( 3300): 2015-12-19T01:47:14.797Z SendDataConnector.js: Mobile.Disconnect() callback with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): ---- round done--------
I/jxcore-log( 3300): 
I/jxcore-log( 3300): startWithNextDevice
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:47:14.800Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3300): 
,W/bt-btif ( 2107): bta_jv_rfc_port_to_cb(port_handle:0x1a):jv handle:0x0 not FOUND
,W/bt-btif ( 2107): invalid rfc slot id: 31
,W/io.jxcore.node.StreamCopyingThread( 3300): Either failed to read from the output stream or write to the input stream (thread ID: 409, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 3300): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3300): onDisconnected: Incoming connection, peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 407
D/io.jxcore.node.OutgoingSocketThread( 3300): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3300): doStop: Thread ID: 409
D/io.jxcore.node.OutgoingSocketThread( 3300): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3300): doStop: Thread ID: 408
D/io.jxcore.node.OutgoingSocketThread( 3300): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 3300): closeLocalSocketAndStreams: Closing the local input stream...
D/io.jxcore.node.OutgoingSocketThread( 3300): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 3300): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3300): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3300): Exiting thread (ID: 409, name: Receiver)
,W/io.jxcore.node.StreamCopyingThread( 3300): Either failed to read from the output stream or write to the input stream (thread ID: 408, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3300): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3300): onDisconnected: Incoming connection, peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.ConnectionHelper( 3300): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3300): Exiting thread (ID: 408, name: Sender)
,I/jxcore-log( 3300): 2015-12-19T01:47:14.856Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3300): 
,W/bt-rfcomm( 2107): rfc_find_lcid_mcb LCID reused LCID:0x48 current:0x0
W/bt-rfcomm( 2107): RFCOMM_DisconnectInd LCID:0x48
,D/btif_config_util( 2107): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2107): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2107): onReceive
,I/BTConnectionReceiver( 1456): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=90:E7:C4:F6:69:77, alias=null, name=HTC One M8s, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1456): Bluetooth Device Name: HTC One M8s
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): checkListForExpiredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Removed [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260]
I/io.jxcore.node.ConnectionHelper( 3300): onPeerLost: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260]
D/io.jxcore.node.ConnectionHelper( 3300): hasConnection: No connection with peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 3300): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260] removed
D/io.jxcore.node.ConnectionHelper( 3300): notifyPeerAvailability: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260] not available
I/jxcore-log( 3300): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:51:18:22","peerName":"samsung-SM-A500FU_PT5260","peerAvailable":false}]
I/jxcore-log( 3300): 
I/jxcore-log( 3300): startWithNextDevice
I/jxcore-log( 3300): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: RESTARTING
,I/wpa_supplicant( 1034): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: STARTED
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): restart: Restarting...
,D/WifiP2pManager( 3300): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1034): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 4 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1034): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT5943","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT5943]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5943]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5943]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5943], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT5943]
I/io.jxcore.node.ConnectionHelper( 3300): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5943], Bluetooth address: 58:3F:54:73:64:C0, device name: , device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper( 3300): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5943] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: RESTARTING
,I/wpa_supplicant( 1034): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery started successfully
I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1034): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
,D/WifiP2pManager( 3300): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT9642","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642]
I/io.jxcore.node.ConnectionHelper( 3300): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: , device address: ee:1f:72:63:11:86
D/io.jxcore.node.ConnectionHelper( 3300): notifyPeerAvailability: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642] is available
I/jxcore-log( 3300): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:34:8A:A0","peerName":"samsung-SM-G900F_PT9642","peerAvailable":true}]
I/jxcore-log( 3300): 
I/jxcore-log( 3300): startWithNextDevice
I/jxcore-log( 3300): 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1034): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1034): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
,D/WifiP2pManager( 3300): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): checkListForExpiredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Removed [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
I/io.jxcore.node.ConnectionHelper( 3300): onPeerLost: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
D/io.jxcore.node.ConnectionHelper( 3300): hasConnection: No connection with peer with ID F8:95:C7:87:3C:51
D/io.jxcore.node.ConnectionHelper( 3300): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326] removed
D/io.jxcore.node.ConnectionHelper( 3300): notifyPeerAvailability: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326] not available
I/jxcore-log( 3300): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:3C:51","peerName":"LGE-LG-H815_PT9326","peerAvailable":false}]
I/jxcore-log( 3300): 
I/jxcore-log( 3300): startWithNextDevice
I/jxcore-log( 3300): 
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): restart: Restarting...
,D/WifiP2pManager( 3300): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): restart: Restarting...
,D/WifiP2pManager( 3300): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT5260","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260]
I/io.jxcore.node.ConnectionHelper( 3300): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260], Bluetooth address: 7C:F9:0E:51:18:22, device name: , device address: 7e:f9:0e:51:18:23
D/io.jxcore.node.ConnectionHelper( 3300): notifyPeerAvailability: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260] is available
,I/jxcore-log( 3300): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:51:18:22","peerName":"samsung-SM-A500FU_PT5260","peerAvailable":true}]
I/jxcore-log( 3300): 
I/jxcore-log( 3300): startWithNextDevice
I/jxcore-log( 3300): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT7958","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958]
,I/io.jxcore.node.ConnectionHelper( 3300): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
D/io.jxcore.node.ConnectionHelper( 3300): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958] is available
I/jxcore-log( 3300): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:75:41","peerName":"samsung-SM-A300FU_PT7958","peerAvailable":true}]
I/jxcore-log( 3300): 
I/jxcore-log( 3300): startWithNextDevice
I/jxcore-log( 3300): 
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): checkListForExpiredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5943] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5943], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Removed [58:3F:54:73:64:C0 LGE-LG-D855_PT5943]
I/io.jxcore.node.ConnectionHelper( 3300): onPeerLost: [58:3F:54:73:64:C0 LGE-LG-D855_PT5943]
D/io.jxcore.node.ConnectionHelper( 3300): hasConnection: No connection with peer with ID 58:3F:54:73:64:C0
D/io.jxcore.node.ConnectionHelper( 3300): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5943] removed
D/io.jxcore.node.ConnectionHelper( 3300): notifyPeerAvailability: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5943] not available
I/jxcore-log( 3300): peerAvailabilityChanged [{"peerIdentifier":"58:3F:54:73:64:C0","peerName":"LGE-LG-D855_PT5943","peerAvailable":false}]
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): startWithNextDevice
I/jxcore-log( 3300): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: RESTARTING
,I/wpa_supplicant( 1034): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): checkListForExpiredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Removed [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642]
I/io.jxcore.node.ConnectionHelper( 3300): onPeerLost: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642]
D/io.jxcore.node.ConnectionHelper( 3300): hasConnection: No connection with peer with ID 7C:F9:0E:34:8A:A0
D/io.jxcore.node.ConnectionHelper( 3300): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642] removed
D/io.jxcore.node.ConnectionHelper( 3300): notifyPeerAvailability: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642] not available
,I/jxcore-log( 3300): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:34:8A:A0","peerName":"samsung-SM-G900F_PT9642","peerAvailable":false}]
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): startWithNextDevice
I/jxcore-log( 3300): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Start timer timeout, starting now...
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): restart: Restarting...
,D/WifiP2pManager( 3300): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1034): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9326","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
I/io.jxcore.node.ConnectionHelper( 3300): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
D/io.jxcore.node.ConnectionHelper( 3300): notifyPeerAvailability: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326] is available
I/jxcore-log( 3300): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:3C:51","peerName":"LGE-LG-H815_PT9326","peerAvailable":true}]
I/jxcore-log( 3300): 
I/jxcore-log( 3300): startWithNextDevice
I/jxcore-log( 3300): 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT4317","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317]
I/io.jxcore.node.ConnectionHelper( 3300): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317], Bluetooth address: 7C:F9:0E:37:96:AB, device name: , device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 3300): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317] already in the list, will not add again
,I/UsageStatsService(  758): User[0] Flushing usage stats to disk
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): checkListForExpiredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958] expired
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): checkListForExpiredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Removed [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Removed [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260]
I/io.jxcore.node.ConnectionHelper( 3300): onPeerLost: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958]
D/io.jxcore.node.ConnectionHelper( 3300): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
,D/io.jxcore.node.ConnectionHelper( 3300): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958] removed
D/io.jxcore.node.ConnectionHelper( 3300): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958] not available
,I/jxcore-log( 3300): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:75:41","peerName":"samsung-SM-A300FU_PT7958","peerAvailable":false}]
I/jxcore-log( 3300): 
I/jxcore-log( 3300): startWithNextDevice
I/jxcore-log( 3300): 
I/io.jxcore.node.ConnectionHelper( 3300): onPeerLost: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260]
D/io.jxcore.node.ConnectionHelper( 3300): hasConnection: No connection with peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 3300): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260] removed
D/io.jxcore.node.ConnectionHelper( 3300): notifyPeerAvailability: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260] not available
I/jxcore-log( 3300): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:51:18:22","peerName":"samsung-SM-A500FU_PT5260","peerAvailable":false}]
I/jxcore-log( 3300): 
I/jxcore-log( 3300): startWithNextDevice
I/jxcore-log( 3300): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: RESTARTING
,I/wpa_supplicant( 1034): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Start timer timeout, starting now...
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): restart: Restarting...
,D/WifiP2pManager( 3300): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: RESTARTING
,I/wpa_supplicant( 1034): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery started successfully
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): restart: Restarting...
,D/WifiP2pManager( 3300): Ignored { when=-3ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): checkListForExpiredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Removed [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317]
I/io.jxcore.node.ConnectionHelper( 3300): onPeerLost: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317]
D/io.jxcore.node.ConnectionHelper( 3300): hasConnection: No connection with peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 3300): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317] removed
D/io.jxcore.node.ConnectionHelper( 3300): notifyPeerAvailability: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317] not available
I/jxcore-log( 3300): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:37:96:AB","peerName":"samsung-SM-A500FU_PT4317","peerAvailable":false}]
I/jxcore-log( 3300): 
I/jxcore-log( 3300): startWithNextDevice
I/jxcore-log( 3300): 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): restart: Restarting...
,D/WifiP2pManager( 3300): Ignored { when=-8ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT7958","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958]
I/io.jxcore.node.ConnectionHelper( 3300): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958], Bluetooth address: 08:EC:A9:50:75:41, device name: , device address: 0a:ec:a9:50:75:42
D/io.jxcore.node.ConnectionHelper( 3300): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958] is available
I/jxcore-log( 3300): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:75:41","peerName":"samsung-SM-A300FU_PT7958","peerAvailable":true}]
I/jxcore-log( 3300): 
I/jxcore-log( 3300): startWithNextDevice
I/jxcore-log( 3300): 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): restart: Restarting...
,D/WifiP2pManager( 3300): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1034): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326],
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT4317","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317]
I/io.jxcore.node.ConnectionHelper( 3300): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
D/io.jxcore.node.ConnectionHelper( 3300): notifyPeerAvailability: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317] is available
I/jxcore-log( 3300): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:37:96:AB","peerName":"samsung-SM-A500FU_PT4317","peerAvailable":true}]
I/jxcore-log( 3300): 
I/jxcore-log( 3300): startWithNextDevice
I/jxcore-log( 3300): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT317","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT317]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT317]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT317]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT317], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT317]
I/io.jxcore.node.ConnectionHelper( 3300): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT317], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 3300): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT317] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT7958","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958]
I/io.jxcore.node.ConnectionHelper( 3300): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper( 3300): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9326","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
,I/io.jxcore.node.ConnectionHelper( 3300): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3300): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326] already in the list, will not add again
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1034): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT317], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT317]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT317], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT317]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
,D/WifiP2pManager( 3300): Ignored { when=-8ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1034): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1034): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): restart: Restarting...
,D/WifiP2pManager( 3300): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT8514","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Resolved peer properties: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onServiceDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Adding new peer: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514]
I/io.jxcore.node.ConnectionHelper( 3300): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514], Bluetooth address: 90:E7:C4:F6:69:77, device name: Android_608e, device address: 92:e7:c4:e6:4c:f8
W/io.jxcore.node.ConnectionHelper( 3300): modifyListOfDiscoveredPeers: Peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT9642","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642]
I/io.jxcore.node.ConnectionHelper( 3300): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
D/io.jxcore.node.ConnectionHelper( 3300): notifyPeerAvailability: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642] is available
I/jxcore-log( 3300): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:34:8A:A0","peerName":"samsung-SM-G900F_PT9642","peerAvailable":true}]
I/jxcore-log( 3300): 
I/jxcore-log( 3300): startWithNextDevice
I/jxcore-log( 3300): 
,I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 4: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 4: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 4: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514]
,D/WifiP2pManager( 3300): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514]
,D/WifiP2pManager( 3300): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514]
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT5260","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260]
I/io.jxcore.node.ConnectionHelper( 3300): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260], Bluetooth address: 7C:F9:0E:51:18:22, device name: , device address: 7e:f9:0e:51:18:23
D/io.jxcore.node.ConnectionHelper( 3300): notifyPeerAvailability: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260] is available
I/jxcore-log( 3300): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:51:18:22","peerName":"samsung-SM-A500FU_PT5260","peerAvailable":true}]
I/jxcore-log( 3300): 
I/jxcore-log( 3300): startWithNextDevice
I/jxcore-log( 3300): 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT4317","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317]
,I/io.jxcore.node.ConnectionHelper( 3300): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 3300): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317] already in the list, will not add again
D/WifiP2pManager( 3300): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 4: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514]
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
,I/jxcore-log( 3300): timeout now
I/jxcore-log( 3300): 
I/jxcore-log( 3300): weAreDoneNow, resultArray.length: 11
I/jxcore-log( 3300): 
I/jxcore-log( 3300): sendReportNow
I/jxcore-log( 3300): 
I/jxcore-log( 3300): done, now sending data to server
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:53:38.668Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3300): 
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): checkListForExpiredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326] expired
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Removed [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
I/io.jxcore.node.ConnectionHelper( 3300): onPeerLost: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
D/io.jxcore.node.ConnectionHelper( 3300): hasConnection: No connection with peer with ID F8:95:C7:87:3C:51
D/io.jxcore.node.ConnectionHelper( 3300): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326] removed
D/io.jxcore.node.ConnectionHelper( 3300): notifyPeerAvailability: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326] not available
I/jxcore-log( 3300): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:3C:51","peerName":"LGE-LG-H815_PT9326","peerAvailable":false}]
I/jxcore-log( 3300): 
I/jxcore-log( 3300): startWithNextDevice
I/jxcore-log( 3300): 
,I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): restart: Restarting...
,D/WifiP2pManager( 3300): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1034): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT7958","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958]
I/io.jxcore.node.ConnectionHelper( 3300): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper( 3300): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958] already in the list, will not add again
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): checkListForExpiredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Removed [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642]
I/io.jxcore.node.ConnectionHelper( 3300): onPeerLost: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642]
D/io.jxcore.node.ConnectionHelper( 3300): hasConnection: No connection with peer with ID 7C:F9:0E:34:8A:A0
D/io.jxcore.node.ConnectionHelper( 3300): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642] removed
D/io.jxcore.node.ConnectionHelper( 3300): notifyPeerAvailability: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642] not available
I/jxcore-log( 3300): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:34:8A:A0","peerName":"samsung-SM-G900F_PT9642","peerAvailable":false}]
I/jxcore-log( 3300): 
I/jxcore-log( 3300): startWithNextDevice
I/jxcore-log( 3300): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: RESTARTING
,I/wpa_supplicant( 1034): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: STARTED
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): restart: Restarting...
,D/WifiP2pManager( 3300): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1034): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1034): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT317","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT317]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT317]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT317]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT317], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT317]
I/io.jxcore.node.ConnectionHelper( 3300): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT317], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 3300): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT317] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9326","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
I/io.jxcore.node.ConnectionHelper( 3300): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
,D/io.jxcore.node.ConnectionHelper( 3300): notifyPeerAvailability: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326] is available
,I/jxcore-log( 3300): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:3C:51","peerName":"LGE-LG-H815_PT9326","peerAvailable":true}]
I/jxcore-log( 3300): 
I/jxcore-log( 3300): startWithNextDevice
I/jxcore-log( 3300): 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1034): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1034): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT9541","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9541]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onServiceDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9541]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9541]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9541], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Adding new peer: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9541]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT317], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT317]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
,I/io.jxcore.node.ConnectionHelper( 3300): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9541], Bluetooth address: B0:C5:59:3F:75:69, device name: , device address: ee:1f:72:18:8b:78
D/io.jxcore.node.ConnectionHelper( 3300): notifyPeerAvailability: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9541] is available
I/jxcore-log( 3300): peerAvailabilityChanged [{"peerIdentifier":"B0:C5:59:3F:75:69","peerName":"samsung-SM-G900F_PT9541","peerAvailable":true}]
I/jxcore-log( 3300): 
I/jxcore-log( 3300): startWithNextDevice
I/jxcore-log( 3300): 
,D/WifiP2pManager( 3300): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 5 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT5260","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260]
I/io.jxcore.node.ConnectionHelper( 3300): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260], Bluetooth address: 7C:F9:0E:51:18:22, device name: , device address: 7e:f9:0e:51:18:23
W/io.jxcore.node.ConnectionHelper( 3300): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260] already in the list, will not add again
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): checkListForExpiredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958] expired
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): checkListForExpiredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Removed [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Removed [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317]
I/io.jxcore.node.ConnectionHelper( 3300): onPeerLost: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958]
D/io.jxcore.node.ConnectionHelper( 3300): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 3300): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958] removed
D/io.jxcore.node.ConnectionHelper( 3300): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958] not available
I/jxcore-log( 3300): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:75:41","peerName":"samsung-SM-A300FU_PT7958","peerAvailable":false}]
I/jxcore-log( 3300): 
I/jxcore-log( 3300): startWithNextDevice
I/jxcore-log( 3300): 
I/io.jxcore.node.ConnectionHelper( 3300): onPeerLost: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317]
,D/io.jxcore.node.ConnectionHelper( 3300): hasConnection: No connection with peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 3300): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317] removed
D/io.jxcore.node.ConnectionHelper( 3300): notifyPeerAvailability: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317] not available
,I/jxcore-log( 3300): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:37:96:AB","peerName":"samsung-SM-A500FU_PT4317","peerAvailable":false}]
I/jxcore-log( 3300): 
I/jxcore-log( 3300): startWithNextDevice
I/jxcore-log( 3300): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: RESTARTING
,I/wpa_supplicant( 1034): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery started successfully
I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): restart: Restarting...
,D/WifiP2pManager( 3300): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1034): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1034): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: RESTARTING
,I/wpa_supplicant( 1034): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Start timer timeout, starting now...
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1034): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1034): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d,
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
,D/WifiP2pManager( 3300): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): restart: Restarting...
,D/WifiP2pManager( 3300): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): checkListForExpiredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Removed [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260]
I/io.jxcore.node.ConnectionHelper( 3300): onPeerLost: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260]
D/io.jxcore.node.ConnectionHelper( 3300): hasConnection: No connection with peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 3300): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260] removed
D/io.jxcore.node.ConnectionHelper( 3300): notifyPeerAvailability: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260] not available
,I/jxcore-log( 3300): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:51:18:22","peerName":"samsung-SM-A500FU_PT5260","peerAvailable":false}]
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): startWithNextDevice
I/jxcore-log( 3300): 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT7958","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958]
I/io.jxcore.node.ConnectionHelper( 3300): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958], Bluetooth address: 08:EC:A9:50:75:41, device name: , device address: 0a:ec:a9:50:75:42
D/io.jxcore.node.ConnectionHelper( 3300): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958] is available
,I/jxcore-log( 3300): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:75:41","peerName":"samsung-SM-A300FU_PT7958","peerAvailable":true}]
I/jxcore-log( 3300): 
I/jxcore-log( 3300): startWithNextDevice
I/jxcore-log( 3300): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT9541","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9541]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onServiceDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9541]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9541]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9541], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Adding new peer: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9541]
I/io.jxcore.node.ConnectionHelper( 3300): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9541], Bluetooth address: B0:C5:59:3F:75:69, device name: , device address: ee:1f:72:18:8b:78
W/io.jxcore.node.ConnectionHelper( 3300): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9541] already in the list, will not add again
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1034): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9541], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9541]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9541], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9541]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
,D/WifiP2pManager( 3300): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
,I/jxcore-log( 3300): teardown
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): testSendData stopped
I/jxcore-log( 3300): 
I/io.jxcore.node.ConnectionHelper( 3300): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3300): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): stop: Stopping P2P device discovery...
,I/wpa_supplicant( 1034): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3300): release: No more listeners, de-initializing...
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3300): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3300): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): setState: NOT_STARTED
I/jxcore-log( 3300): StopBroadcasting went ok
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): 2015-12-19T01:56:58.605Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
I/jxcore-log( 3300): 
I/chromium( 3300): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/io.jxcore.node.ConnectionHelper( 3300): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3300): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 3300): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 3300): --- start :testFindPeers.js---
I/jxcore-log( 3300): 
,I/jxcore-log( 3300): testFindPeers created [object Object]
I/jxcore-log( 3300): 
I/jxcore-log( 3300): serverPort is 8876
I/jxcore-log( 3300): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): setDiscoveryMode: Mode set to WIFI
,D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): start: Peer ID: 34:FC:EF:11:AE:67, peer name: LGE-Nexus 5_PT2713
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3300): bind: Binding a new listener
D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3300): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3300): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT2713","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3300): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 3300): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3300): start: OK
I/io.jxcore.node.ConnectionHelper( 3300): start: Using peer discovery mode: WIFI
,D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): start: Peer ID: 34:FC:EF:11:AE:67, peer name: LGE-Nexus 5_PT2713
,D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3300): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT2713","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3300): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT2713","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3300): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT2713","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3300): start: OK
I/jxcore-log( 3300): StartBroadcasting started ok
I/jxcore-log( 3300): 
I/chromium( 3300): [INFO:CONSOLE(63)] "logCallback --- start :testFindPeers.js---", source: file:///android_asset/www/js/thali_main.js (63)
,I/io.jxcore.node.ConnectionHelper( 3300): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3300): Local service added successfully
I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: RESTARTING
,I/wpa_supplicant( 1034): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3300): onDiscoveryManagerStateChanged: RUNNING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: RESTARTING
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3300): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Start timer timeout, starting now...
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1034): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 2 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/WifiP2pManager( 3300): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1034): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT7958","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958]
I/io.jxcore.node.ConnectionHelper( 3300): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper( 3300): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT4317","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317]
I/io.jxcore.node.ConnectionHelper( 3300): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317], Bluetooth address: 7C:F9:0E:37:96:AB, device name: , device address: 7e:f9:0e:37:96:ac
,D/io.jxcore.node.ConnectionHelper( 3300): notifyPeerAvailability: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317] is available
,I/jxcore-log( 3300): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:37:96:AB","peerName":"samsung-SM-A500FU_PT4317","peerAvailable":true}]
I/jxcore-log( 3300): 
I/jxcore-log( 3300): Found peer : 7C:F9:0E:37:96:AB, peerAvailable: true
I/jxcore-log( 3300): 
I/jxcore-log( 3300): weAreDoneNow
I/jxcore-log( 3300): 
I/jxcore-log( 3300): done, now sending data to server
I/jxcore-log( 3300): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT5260","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260]
,I/io.jxcore.node.ConnectionHelper( 3300): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260], Bluetooth address: 7C:F9:0E:51:18:22, device name: , device address: 7e:f9:0e:51:18:23
D/io.jxcore.node.ConnectionHelper( 3300): notifyPeerAvailability: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260] is available
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT8514","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Resolved peer properties: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onServiceDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Adding new peer: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514]
I/io.jxcore.node.ConnectionHelper( 3300): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514], Bluetooth address: 90:E7:C4:F6:69:77, device name: Android_608e, device address: 92:e7:c4:e6:4c:f8
W/io.jxcore.node.ConnectionHelper( 3300): modifyListOfDiscoveredPeers: Peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT5943","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT5943]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5943]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5943]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5943], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT5943]
I/io.jxcore.node.ConnectionHelper( 3300): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5943], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
D/io.jxcore.node.ConnectionHelper( 3300): notifyPeerAvailability: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5943] is available
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5943], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5943]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958]
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5943], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5943]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): restart: Restarting...
,D/WifiP2pManager( 3300): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5943], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5943]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958]
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5943], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5943]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1034): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 6 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5943], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5943]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5943], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5943]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT9642","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642]
I/io.jxcore.node.ConnectionHelper( 3300): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
D/io.jxcore.node.ConnectionHelper( 3300): notifyPeerAvailability: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642] is available
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9326","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
I/io.jxcore.node.ConnectionHelper( 3300): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3300): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326] already in the list, will not add again
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5943], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5943]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): restart: Restarting...
,D/WifiP2pManager( 3300): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958]
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: RESTARTING
,I/wpa_supplicant( 1034): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Start timer timeout, starting now...
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): restart: Restarting...
,D/WifiP2pManager( 3300): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT8514","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Resolved peer properties: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onServiceDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Adding new peer: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514]
I/io.jxcore.node.ConnectionHelper( 3300): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514], Bluetooth address: 90:E7:C4:F6:69:77, device name: Android_608e, device address: 92:e7:c4:e6:4c:f8
W/io.jxcore.node.ConnectionHelper( 3300): modifyListOfDiscoveredPeers: Peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514] already in the list, will not add again
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT9642","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642]
,I/io.jxcore.node.ConnectionHelper( 3300): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: , device address: ee:1f:72:63:11:86
W/io.jxcore.node.ConnectionHelper( 3300): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642] already in the list, will not add again
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT5943","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT5943]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5943]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5943]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5943], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT5943]
I/io.jxcore.node.ConnectionHelper( 3300): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5943], Bluetooth address: 58:3F:54:73:64:C0, device name: , device address: 02:9a:02:7b:60:ac
,W/io.jxcore.node.ConnectionHelper( 3300): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5943] already in the list, will not add again
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514]
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5943], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5943]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 4: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514]
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5943], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5943]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9326","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
I/io.jxcore.node.ConnectionHelper( 3300): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3300): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326] already in the list, will not add again
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT4591","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT4591]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onServiceDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT4591]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT4591]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT4591], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Adding new peer: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT4591]
I/io.jxcore.node.ConnectionHelper( 3300): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT4591], Bluetooth address: E0:DB:10:14:E2:C0, device name: Note4-1, device address: 92:b6:86:43:73:1c
W/io.jxcore.node.ConnectionHelper( 3300): modifyListOfDiscoveredPeers: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT4591] already in the list, will not add again
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT4591], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT4591]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): restart: Restarting...
,D/WifiP2pManager( 3300): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT4317","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317]
I/io.jxcore.node.ConnectionHelper( 3300): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317], Bluetooth address: 7C:F9:0E:37:96:AB, device name: , device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 3300): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317] already in the list, will not add again
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): checkListForExpiredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Removed [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260]
I/io.jxcore.node.ConnectionHelper( 3300): onPeerLost: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260]
D/io.jxcore.node.ConnectionHelper( 3300): hasConnection: No connection with peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 3300): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260] removed
D/io.jxcore.node.ConnectionHelper( 3300): notifyPeerAvailability: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260] not available
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: RESTARTING
,I/wpa_supplicant( 1034): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Start timer timeout, starting now...
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): restart: Restarting...
,D/WifiP2pManager( 3300): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT9642","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642]
I/io.jxcore.node.ConnectionHelper( 3300): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
W/io.jxcore.node.ConnectionHelper( 3300): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT5260","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260]
I/io.jxcore.node.ConnectionHelper( 3300): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260], Bluetooth address: 7C:F9:0E:51:18:22, device name: , device address: 7e:f9:0e:51:18:23
D/io.jxcore.node.ConnectionHelper( 3300): notifyPeerAvailability: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260] is available
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT8514","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Resolved peer properties: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onServiceDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514]
I/io.jxcore.node.ConnectionHelper( 3300): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514], Bluetooth address: 90:E7:C4:F6:69:77, device name: Android_608e, device address: 92:e7:c4:e6:4c:f8
W/io.jxcore.node.ConnectionHelper( 3300): modifyListOfDiscoveredPeers: Peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514] already in the list, will not add again
,W/bt-smp  ( 2107): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2107): Plain text(LSB ~ MSB) = 49 a9 4e 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2107): Encrypted text(LSB ~ MSB) = 87 83 5c cb ee 91 6a aa 92 84 61 76 36 63 ff 51 
,W/bt-btm  ( 2107): Stopping oneshot timer
,D/WifiP2pManager( 3300): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1034): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1034): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac,
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): checkListForExpiredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326] expired
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): checkListForExpiredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Removed [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Removed [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958]
I/io.jxcore.node.ConnectionHelper( 3300): onPeerLost: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
D/io.jxcore.node.ConnectionHelper( 3300): hasConnection: No connection with peer with ID F8:95:C7:87:3C:51
D/io.jxcore.node.ConnectionHelper( 3300): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326] removed
D/io.jxcore.node.ConnectionHelper( 3300): notifyPeerAvailability: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326] not available
I/io.jxcore.node.ConnectionHelper( 3300): onPeerLost: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958]
D/io.jxcore.node.ConnectionHelper( 3300): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 3300): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958] removed
D/io.jxcore.node.ConnectionHelper( 3300): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958] not available
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: RESTARTING
,I/wpa_supplicant( 1034): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86,
I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Start timer timeout, starting now...
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): restart: Restarting...
,D/WifiP2pManager( 3300): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/ProcessStatsService(  758): Prepared write state in 45ms
,I/ProcessStatsService(  758): Prepared write state in 4ms
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
,I/ProcessStatsService(  758): Pruning old procstats: /data/system/procstats/state-2015-12-18-12-51-38.bin
,I/art     (  758): Explicit concurrent mark sweep GC freed 96115(4MB) AllocSpace objects, 8(181KB) LOS objects, 33% free, 28MB/43MB, paused 919us total 73.058ms
,I/EventLogService( 1668): Aggregate from 1450487973696 (log), 1450487973696 (data)
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT7958","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958]
I/io.jxcore.node.ConnectionHelper( 3300): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
D/io.jxcore.node.ConnectionHelper( 3300): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958] is available
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: RESTARTING
,I/wpa_supplicant( 1034): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 1034): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): P2P device discovery started successfully
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3300): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): checkListForExpiredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Removed [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317]
I/io.jxcore.node.ConnectionHelper( 3300): onPeerLost: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317]
D/io.jxcore.node.ConnectionHelper( 3300): hasConnection: No connection with peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 3300): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317] removed
D/io.jxcore.node.ConnectionHelper( 3300): notifyPeerAvailability: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317] not available
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
,D/WifiP2pManager( 3300): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1034): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 3 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT5943","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT5943]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5943]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5943]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5943], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT5943]
I/io.jxcore.node.ConnectionHelper( 3300): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT5943], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper( 3300): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5943] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9326","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
I/io.jxcore.node.ConnectionHelper( 3300): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: a2:39:f7:6f:c9:5d
D/io.jxcore.node.ConnectionHelper( 3300): notifyPeerAvailability: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326] is available
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT8514","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Resolved peer properties: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onServiceDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Adding new peer: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514]
I/io.jxcore.node.ConnectionHelper( 3300): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514], Bluetooth address: 90:E7:C4:F6:69:77, device name: Android_608e, device address: 92:e7:c4:e6:4c:f8
,W/io.jxcore.node.ConnectionHelper( 3300): modifyListOfDiscoveredPeers: Peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT4317","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317]
,I/io.jxcore.node.ConnectionHelper( 3300): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
D/io.jxcore.node.ConnectionHelper( 3300): notifyPeerAvailability: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317] is available
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT5943], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT5943]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): restart: Restarting...
,D/WifiP2pManager( 3300): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service request added successfully
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 4: Android_608e 92:e7:c4:e6:4c:f8
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514]
,I/wpa_supplicant( 1034): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1034): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): Service discovery started successfully
,I/wpa_supplicant( 1034): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1034): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1034): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT317","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT317]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT317]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT317]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT317], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT317]
I/io.jxcore.node.ConnectionHelper( 3300): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT317], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 3300): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT317] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT9541","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3300): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9541]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3300): onServiceDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9541]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9541]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9541], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Adding new peer: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9541]
I/io.jxcore.node.ConnectionHelper( 3300): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9541], Bluetooth address: B0:C5:59:3F:75:69, device name: , device address: ee:1f:72:18:8b:78
,W/io.jxcore.node.ConnectionHelper( 3300): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT9541] already in the list, will not add again
,I/ActivityManager(  758): Killing 3058:com.android.defcontainer/u0a5 (adj 13): empty for 1801s
,I/ActivityManager(  758): Killing 3219:com.google.android.apps.docs/u0a40 (adj 13): empty for 1803s
,I/ActivityManager(  758): Killing 3181:com.android.musicfx/u0a15 (adj 13): empty for 1803s
,I/ActivityManager(  758): Killing 1532:com.google.android.partnersetup/u0a13 (adj 13): empty for 1803s
,I/ActivityManager(  758): Killing 2905:android.process.acore/u0a4 (adj 15): empty for 1803s
,I/ActivityManager(  758): Killing 3077:com.google.android.gms:car/u0a8 (adj 15): empty for 1810s
,I/ActivityManager(  758): Killing 2820:com.android.providers.calendar/u0a2 (adj 15): empty for 1811s
,W/libprocessgroup(  758): failed to open /acct/uid_10040/pid_3219/cgroup.procs: No such file or directory
,W/libprocessgroup(  758): failed to open /acct/uid_10008/pid_3077/cgroup.procs: No such file or directory
,W/libprocessgroup(  758): failed to open /acct/uid_10002/pid_2820/cgroup.procs: No such file or directory
,W/libprocessgroup(  758): failed to open /acct/uid_10005/pid_3058/cgroup.procs: No such file or directory
,W/libprocessgroup(  758): failed to open /acct/uid_10015/pid_3181/cgroup.procs: No such file or directory
,W/libprocessgroup(  758): failed to open /acct/uid_10013/pid_1532/cgroup.procs: No such file or directory
,W/libprocessgroup(  758): failed to open /acct/uid_10004/pid_2905/cgroup.procs: No such file or directory
,V/GLSActivity( 1627): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1627): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): checkListForExpiredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3300): modifyListOfDiscoveredPeers: Removed [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958]
I/io.jxcore.node.ConnectionHelper( 3300): onPeerLost: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958]
D/io.jxcore.node.ConnectionHelper( 3300): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 3300): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958] removed
D/io.jxcore.node.ConnectionHelper( 3300): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958] not available
,TIME-OUT KILL (timeout was 1800000ms)
```
