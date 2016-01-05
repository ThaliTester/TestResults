#### Test 550731521dbc378_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
D/ChimeraCfgMgr( 1635): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1635): Module APK com.google.android.play.games already loaded
,I/GAv4    ( 3193): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3193):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3193):   adb logcat -s GAv4
W/GAv4    ( 3193): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3193): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3193): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 3193): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
D/AndroidRuntime( 3237): 
D/AndroidRuntime( 3237): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3237): CheckJNI is OFF
D/Finsky  ( 2600): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
W/ResourcesManager( 3193): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3193): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  735): Killing 2559:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
V/JNIHelp ( 3193): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/AndroidRuntime( 3237): Calling main entry com.android.commands.am.Am
W/System  ( 3193): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3193): Installed default security provider GmsCore_OpenSSL
W/libprocessgroup(  735): failed to open /acct/uid_10069/pid_2559/cgroup.procs: No such file or directory
I/ActivityManager(  735): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  735): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3271 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3237): Shutting down VM
V/GLSActivity( 1566): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/ActivityManager(  735): Display changed displayId=0
I/WebViewFactory( 3271): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/Icing   ( 1635): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/LibraryLoader( 3271): Time to load native libraries: 2 ms (timestamps 7137-7139)
I/LibraryLoader( 3271): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3271): Binding Chromium to main looper Looper (main, tid 1) {a090a99}
I/LibraryLoader( 3271): Expected native library version number "",actual native library version number ""
I/chromium( 3271): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3271): Initializing chromium process, singleProcess=true
W/art     ( 3271): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3271): ApplicationContext is null in ApplicationStatus
I/Icing   ( 1635): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1635): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
W/chromium( 3271): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3271): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3271): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3271): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
I/Icing   ( 1635): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
D/BluetoothManagerService(  735): Message: 20
D/BluetoothManagerService(  735): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@67c2049:true
W/art     ( 3271): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 3271): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 3271): CordovaWebView is running on device made by: LGE
W/art     ( 3271): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3271): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 3271): Render dirty regions requested: true
D/Atlas   ( 3271): Validating map...
W/chromium( 3271): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/OpenGLRenderer( 3271): Initialized EGL, version 1.4
D/OpenGLRenderer( 3271): Enabling debug mode 0
W/IInputConnectionWrapper( 3271): showStatusIcon on inactive InputConnection
I/ActivityManager(  735): Displayed com.test.thalitest/.MainActivity: +486ms (total +56s374ms)
W/BindingManager( 3271): Cannot call determinedVisibility() - never saw a connection for the pid: 3271
D/JsMessageQueue( 3271): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 3271): JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1258381056
D/JX-Cordova( 3271): jxcore cordova android initializing
I/ActivityManager(  735): Killing 2508:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,W/libprocessgroup(  735): failed to open /acct/uid_10045/pid_2508/cgroup.procs: No such file or directory
,W/jxcore-log( 3271): Initializing JXcore engine
W/jxcore-log( 3271): JXcore engine is ready
,W/jxcore-log( 3271): Starting JXcore engine
,W/.test.thalitest( 3271): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[8326]" dev="sockfs" ino=8326 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/.test.thalitest( 3271): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 3271): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6644]" dev="sockfs" ino=6644 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3271): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[20117]" dev="sockfs" ino=20117 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3271): Platform android
W/jxcore-log( 3271): 
,W/jxcore-log( 3271): Process ARCH arm
W/jxcore-log( 3271): 
,I/jxcore-log( 3271): JXcore Cordova bridge is ready!
I/jxcore-log( 3271): 
,W/jxcore-log( 3271): JXcore engine is started
I/Choreographer( 3271): Skipped 114 frames!  The application may be doing too much work on its main thread.
I/chromium( 3271): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3271): Toggling radios to true
I/jxcore-log( 3271): 
,D/BluetoothAdapter( 3271): enable(): BT is already enabled..!
,D/WifiService(  735): New client listening to asynchronous messages
,D/WifiService(  735): setWifiEnabled: true pid=3271, uid=10270
E/WifiService(  735): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3271): Radios toggled
I/jxcore-log( 3271): 
,D/BluetoothManagerService(  735): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  735): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 3271): Received device characteristics:
I/jxcore-log( 3271): Bluetooth address: 34:FC:EF:11:AE:67
I/jxcore-log( 3271): Bluetooth name: Nexus 5
I/jxcore-log( 3271): Device name: LGE-Nexus 5
I/jxcore-log( 3271): 
,I/jxcore-log( 3271): Perf Test app loaded loaded
I/jxcore-log( 3271): 
,I/wpa_supplicant( 1025): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  735): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  735): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/native  (  735): do suspend true
,D/CommandListener(  181): Clearing all IP addresses on wlan0
I/jxcore-log( 3271): check test folder
I/jxcore-log( 3271): 
,I/jxcore-log( 3271): found test : ./testFindPeers.js
I/jxcore-log( 3271): 
,V/NativeCrypto( 1566): Read error: ssl=0xb3e47e00: I/O error during system call, Connection timed out
V/NativeCrypto( 1566): SSL shutdown failed: ssl=0xb3e47e00: I/O error during system call, Broken pipe
,E/WifiConfigStore(  735): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
I/jxcore-log( 3271): found test : ./testSendData.js
I/jxcore-log( 3271): 
D/ConnectivityService(  735): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  735): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,E/WifiStateMachine(  735): Start Disconnecting Watchdog 1
,I/wpa_supplicant( 1025): wlan0: CTRL-EVENT-SCAN-STARTED 
E/native  (  735): do suspend true
,D/ConnectivityService(  735): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): ValidatedState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): DefaultState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Checking http://clients3.google.com/generate_204 on <unknown ssid>
,D/CommandListener(  181): Clearing all IP addresses on wlan0
,D/ConnectivityService(  735): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/Nat464Xlat(  735): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  735): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Disconnected - quitting
D/ConnectivityService(  735): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  735): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1635): CM callback handler got msg 524292
D/ConnectivityManager.CallbackHandler(  896): CM callback handler got msg 524292
D/ConnectivityService(  735): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1250): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WifiNetworkAgent(  735): NetworkAgent: NetworkAgent channel lost
,I/Choreographer( 3271): Skipped 67 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3271): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,W/ProcessCpuTracker(  735): Skipping unknown process pid 3329
,W/ProcessCpuTracker(  735): Skipping unknown process pid 3332
W/ProcessCpuTracker(  735): Skipping unknown process pid 3333
,W/ProcessCpuTracker(  735): Skipping unknown process pid 3336
,V/GLSActivity( 1566): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1566): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/NetworkUtils( 1411): OkHttp exception
,W/EventLoggerService( 1411): Unable to send logs Error code: 262146
,I/wpa_supplicant( 1025): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant( 1025): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1025): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1025): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  735): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  735): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  735): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiConfigStore(  735): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/CommandListener(  181): Setting iface cfg
,E/WifiStateMachine(  735): Start Dhcp Watchdog 2
,E/native  (  735): do suspend false
,E/WifiStateMachine(  735): scanCount==0 - aborting
,I/dhcpcd  ( 3384): version 5.5.6 starting
,E/dhcpcd  ( 3384): get_duid: Read-only file system
,I/dhcpcd  ( 3384): wlan0: rebinding lease of 192.168.1.114
,I/dhcpcd  ( 3384): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3384): wlan0: leased 192.168.1.114 for 86400 seconds
,D/ConnectivityService(  735): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  735): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  735): MasterInitialState.processMessage what=3
D/Tethering(  735): MasterInitialState.processMessage what=3
,V/MusicLeanback( 2727): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1635): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1635): onCreate
,D/SystemUpdateService( 1635): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.Environment( 1635): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1635): num queued entries: 0
,I/ActivityManager(  735): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3424 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/GpsLocationProvider(  735): No APN found to select.
,I/SystemUpdateService( 1635): active receiver: enabled
,I/Babel   ( 1883): connection state changed from CONNECTED to DISCONNECTED
,I/iu.UploadsManager( 1635): num updated entries: 0
,I/iu.SyncManager( 1635): NEXT; no task
,I/SystemUpdateService( 1635): showing system update notification
,E/GpsLocationProvider(  735): No APN found to select.
,I/ValidateNoPeople(  735): skipping global notification
,V/SystemUpdateService( 1635): retry (wakeup: false) in 3599970 ms
,E/native  (  735): do suspend true
,D/SystemUpdateService( 1635): onDestroy
,D/ConnectivityService(  735): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  735): Adding iface wlan0 to network 101
,E/WifiStateMachine(  735): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  735): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  735): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  735): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/ConnectivityService(  735): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  735): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  735): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  735): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  735): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  735): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  735):    accepting network in place of null
,D/CSLegacyTypeTracker(  735): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  735): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  735): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::5255:27ff:fef0:fd0b/64,192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/ConnectivityService(  735): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  896): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1635): CM callback handler got msg 524290
,I/GAv4    ( 3424): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3424):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3424):   adb logcat -s GAv4
,W/GAv4    ( 3424): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3424): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3424): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 05 Jan 2016 10:18:34 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1451989114909], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1451989114894]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Validated
D/ConnectivityService(  735): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  735): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  735): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  735): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  735): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/TelephonyNetworkFactory( 1250): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler(  896): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1635): CM callback handler got msg 524290
,I/WebViewFactory( 3424): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3424): Time to load native libraries: 1 ms (timestamps 4211-4212)
I/LibraryLoader( 3424): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3424): Binding Chromium to main looper Looper (main, tid 1) {252e69a3}
,I/LibraryLoader( 3424): Expected native library version number "",actual native library version number ""
,I/chromium( 3424): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3424): Initializing chromium process, singleProcess=true
,W/art     ( 3424): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3424): ApplicationContext is null in ApplicationStatus
,W/chromium( 3424): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3424): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3424): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3424): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/AudioManagerAndroid( 3424): Requires BLUETOOTH permission
,I/NSApplication( 3424): Starting up...
,I/ActivityManager(  735): Killing 2699:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/libprocessgroup(  735): failed to open /acct/uid_10003/pid_2699/cgroup.procs: No such file or directory
,V/MusicLeanback( 2727): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1635): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1635): onCreate
,D/SystemUpdateService( 1635): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.Environment( 1635): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/SystemUpdateService( 1635): active receiver: enabled
,I/iu.UploadsManager( 1635): num queued entries: 0
I/iu.UploadsManager( 1635): num updated entries: 0
I/iu.SyncManager( 1635): NEXT; no task
,I/SystemUpdateService( 1635): showing system update notification
,I/ValidateNoPeople(  735): skipping global notification
,V/SystemUpdateService( 1635): retry (wakeup: false) in 3599964 ms
,D/SystemUpdateService( 1635): onDestroy
,I/Babel   ( 1883): connection state changed from DISCONNECTED to CONNECTED
,D/ConnectivityService(  735): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): setDiscoveryMode: Mode set to WIFI
,I/jxcore-log( 3271): BLE is supported
I/jxcore-log( 3271): 
,D/ConnectivityService(  735): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  735): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2727): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2727): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1635): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,I/art     (  735): Explicit concurrent mark sweep GC freed 43579(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 27MB/41MB, paused 941us total 58.929ms
,D/SystemUpdateService( 1635): onCreate
,D/SystemUpdateService( 1635): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1635): active receiver: enabled
,I/SystemUpdateService( 1635): showing system update notification
,I/ValidateNoPeople(  735): skipping global notification
,V/SystemUpdateService( 1635): retry (wakeup: false) in 3599985 ms
,D/SystemUpdateService( 1635): onDestroy
,E/GpsLocationProvider(  735): No APN found to select.
,D/Finsky  ( 2600): [255] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2600): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/GLSActivity( 1566): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1566): Vacuum at: now=1451989127880 tag=VacuumService
,I/PhenotypeConfigurator( 1566): Scheduling Phenotype for one-off execution 12299 seconds from now (1451989128117)
,D/GetConfigurationSnapshotOperation( 1566): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1566): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1566): Using platform SSLCertificateSocketFactory
,V/GLSActivity( 1566): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1566): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ClearcutLoggerApiImpl( 1566): disconnect managed GoogleApiClient
,I/jxcore-log( 3271): Connected to the server!
I/jxcore-log( 3271): 
,I/chromium( 3271): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3271): --- start :testFindPeers.js---
I/jxcore-log( 3271): 
,I/jxcore-log( 3271): testFindPeers created [object Object]
I/jxcore-log( 3271): 
I/jxcore-log( 3271): serverPort is 8876
I/jxcore-log( 3271): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): setDiscoveryMode: Mode set to WIFI
,D/BluetoothManagerService(  735): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3271): start: Peer ID: 34:FC:EF:11:AE:67, peer name: Nexus 5
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3271): bind: Binding a new listener
,D/BluetoothManagerService(  735): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3271): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  735): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3271): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"Nexus 5","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3271): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3271): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3271): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  735): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3271): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3271): setState: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3271): start: OK
I/io.jxcore.node.ConnectionHelper( 3271): start: Using peer discovery mode: WIFI
,D/BluetoothManagerService(  735): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): start: Peer ID: 34:FC:EF:11:AE:67, peer name: Nexus 5
,D/BluetoothManagerService(  735): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3271): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"Nexus 5","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3271): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3271): start: {"pi":"34:FC:EF:11:AE:67","pn":"Nexus 5","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3271): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"Nexus 5","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3271): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3271): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3271): start: OK
I/jxcore-log( 3271): StartBroadcasting started ok
I/jxcore-log( 3271): 
I/chromium( 3271): [INFO:CONSOLE(63)] "logCallback --- start :testFindPeers.js---", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3271): Waiting for incoming connections...
,I/io.jxcore.node.ConnectionHelper( 3271): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3271): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3271): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3271): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3271): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/io.jxcore.node.ConnectionHelper( 3271): onDiscoveryManagerStateChanged: RUNNING
,I/wpa_supplicant( 1025): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1025): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1025): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1025): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3271): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): onP2pDeviceListChanged: Peer 1: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3271): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3271): Service request added successfully
,I/wpa_supplicant( 1025): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1025): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1025): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3271): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3271): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
,I/wpa_supplicant( 1025): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1025): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1025): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3271): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3271): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3271): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3271): setState: RESTARTING
,I/wpa_supplicant( 1025): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1025): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 1025): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 1025): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3271): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3271): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3271): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3271): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3271): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3271): P2P device discovery started successfully
,I/wpa_supplicant( 1025): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3271): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3271): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1025): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1025): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3271): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3271): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3271): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 3271): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3271): Service request added successfully
,I/wpa_supplicant( 1025): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1025): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1025): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3271): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3271): Service discovery started successfully
,I/wpa_supplicant( 1025): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1025): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1025): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3271): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3271): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
,I/wpa_supplicant( 1025): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1025): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3271): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3271): restart: Restarting...
,D/WifiP2pManager( 3271): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3271): Service request added successfully
,I/wpa_supplicant( 1025): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1025): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1025): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3271): Service discovery started successfully
,I/wpa_supplicant( 1025): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1025): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1025): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1025): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3271): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3271): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3271): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 3271): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3271): Service request added successfully
,I/wpa_supplicant( 1025): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1025): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1025): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3271): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
,I/wpa_supplicant( 1025): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1025): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3271): Service discovery started successfully
,I/wpa_supplicant( 1025): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3271): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
,I/jxcore-log( 3271): timeout now
I/jxcore-log( 3271): 
,I/jxcore-log( 3271): weAreDoneNow
I/jxcore-log( 3271): 
I/jxcore-log( 3271): done, now sending data to server
I/jxcore-log( 3271): 
,I/jxcore-log( 3271): teardown
I/jxcore-log( 3271): 
,I/jxcore-log( 3271): testFindPeers stopped
I/jxcore-log( 3271): 
I/io.jxcore.node.ConnectionHelper( 3271): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3271): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3271): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3271): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3271): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3271): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3271): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3271): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3271): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3271): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3271): stop: Stopping P2P device discovery...
,I/wpa_supplicant( 1025): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1025): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 1025): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 1025): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 1025): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 1025): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 1025): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3271): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3271): release: No more listeners, de-initializing...
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3271): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3271): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): setState: NOT_STARTED
,I/jxcore-log( 3271): StopBroadcasting went ok
I/jxcore-log( 3271): 
,I/chromium( 3271): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
I/io.jxcore.node.ConnectionHelper( 3271): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3271): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3271): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3271): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 3271): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 3271): --- start :testSendData.js---
I/jxcore-log( 3271): 
,I/jxcore-log( 3271): testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":13}bt-address length : 0
I/jxcore-log( 3271): 
,I/jxcore-log( 3271): daya100000
I/jxcore-log( 3271): 
I/jxcore-log( 3271): check server
I/jxcore-log( 3271): 
,I/jxcore-log( 3271): serverPort is 36469
I/jxcore-log( 3271): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): setDiscoveryMode: Mode set to WIFI
,D/BluetoothManagerService(  735): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3271): start: Peer ID: 34:FC:EF:11:AE:67, peer name: Nexus 5
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3271): bind: Binding a new listener
D/BluetoothManagerService(  735): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3271): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  735): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3271): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"Nexus 5","ra":"34:FC:EF:11:AE:67"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3271): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3271): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3271): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  735): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3271): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3271): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3271): start: OK
I/io.jxcore.node.ConnectionHelper( 3271): start: Using peer discovery mode: WIFI
,D/BluetoothManagerService(  735): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): start: Peer ID: 34:FC:EF:11:AE:67, peer name: Nexus 5
,D/BluetoothManagerService(  735): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3271): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"Nexus 5","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3271): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3271): start: {"pi":"34:FC:EF:11:AE:67","pn":"Nexus 5","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3271): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"Nexus 5","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3271): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3271): start: Starting P2P device discovery...
,I/wpa_supplicant( 1025): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3271): start: OK
,I/jxcore-log( 3271): StartBroadcasting started ok
I/jxcore-log( 3271): 
,I/jxcore-log( 3271): null
I/jxcore-log( 3271): 
I/jxcore-log( 3271): 2016-01-05T10:26:46.156Z SendDataTCPServer.js: TCP/IP server is bound to port: 36469
I/jxcore-log( 3271): 
I/chromium( 3271): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
,I/io.jxcore.node.ConnectionHelper( 3271): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3271): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3271): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3271): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3271): setState: RESTARTING
,I/wpa_supplicant( 1025): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3271): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3271): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3271): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3271): onDiscoveryManagerStateChanged: RUNNING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3271): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3271): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3271): setState: RESTARTING
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3271): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3271): Start timer timeout, starting now...
,I/wpa_supplicant( 1025): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3271): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3271): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3271): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1025): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1025): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1025): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3271): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3271): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiP2pManager( 3271): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3271): Service request added successfully
,I/wpa_supplicant( 1025): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1025): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1025): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1025): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3271): Service discovery started successfully
,W/bt-btif ( 2046): info:x10
,D/        ( 2046): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,E/BluetoothRemoteDevices( 2046): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 1025): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3271): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3271): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3271): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3271): onServiceDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): onPeerDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): modifyListOfDiscoveredPeers: Adding new peer: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
,I/io.jxcore.node.ConnectionHelper( 3271): onPeerDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
D/io.jxcore.node.ConnectionHelper( 3271): notifyPeerAvailability: Peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)] is available
,I/jxcore-log( 3271): peerAvailabilityChanged [{"peerIdentifier":"B0:C5:59:3F:75:69","peerName":"Thali Test (Galaxy S5)","peerAvailable":true}]
I/jxcore-log( 3271): 
I/jxcore-log( 3271): Found peer : Thali Test (Galaxy S5), Available: true
I/jxcore-log( 3271): 
,I/jxcore-log( 3271): startWithNextDevice
I/jxcore-log( 3271): 
I/jxcore-log( 3271): device[1]: B0:C5:59:3F:75:69
I/jxcore-log( 3271): 
I/jxcore-log( 3271): 2016-01-05T10:26:55.250Z SendDataConnector.js: Start called with peer B0:C5:59:3F:75:69
I/jxcore-log( 3271): 
,I/jxcore-log( 3271): 2016-01-05T10:26:55.250Z SendDataConnector.js: doConnect called with peer B0:C5:59:3F:75:69
I/jxcore-log( 3271): 
I/jxcore-log( 3271): 2016-01-05T10:26:55.251Z SendDataConnector.js: do connect now
I/jxcore-log( 3271): 
,I/io.jxcore.node.ConnectionHelper( 3271): connect: Trying to connect to peer with ID B0:C5:59:3F:75:69
,D/io.jxcore.node.ConnectionHelper( 3271): hasConnection: No connection with peer with ID B0:C5:59:3F:75:69
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3271): connect: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3271): connect: Trying to start connecting to null in address B0:C5:59:3F:75:69
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3271): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3271): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3271): onConnecting: null B0:C5:59:3F:75:69
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3271): connect: Started connecting to null in address B0:C5:59:3F:75:69
I/io.jxcore.node.ConnectionHelper( 3271): connect: Connection process successfully started (peer ID: B0:C5:59:3F:75:69)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3271): Trying to connect to peer with address B0:C5:59:3F:75:69 (thread ID: 310)
W/BluetoothAdapter( 3271): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 2046): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2046): tBTM_SEC_DEV:0xa3d50ebc rs_disc_pending=1
W/bt-btif ( 2046): bta_dm_check_av:0
,W/bt-btif ( 2046): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 2046): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 1
E/bt-btif ( 2046): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2046): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2046): Entering PendingCommandState State
,W/BluetoothEventManager( 2659): CachedBluetoothDevice for device 7C:F9:0E:34:8A:A0 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2659): Got bonding state changed for 7C:F9:0E:34:8A:A0, but we have no record of that device.
,I/BluetoothBondStateMachine( 2046): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 0
,D/BluetoothAdapterProperties( 2046): Failed to remove device: 7C:F9:0E:34:8A:A0
,I/BluetoothBondStateMachine( 2046): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 11 NewState: 10
,W/BluetoothEventManager( 2659): CachedBluetoothDevice for device 7C:F9:0E:34:8A:A0 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2659): Got bonding state changed for 7C:F9:0E:34:8A:A0, but we have no record of that device.
,I/BluetoothBondStateMachine( 2046): StableState(): Entering Off State
,W/bt-btif ( 2046): new conn_srvc id:26, app_id:255
W/bt-btif ( 2046): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2046): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3271): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3271): Incoming connection initialized (thread ID: 311)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3271): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3271): Entering thread (ID: 311)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3271): onBytesRead: Read 63 bytes successfully (thread ID: 311)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3271): Got valid identity from [7C:F9:0E:34:8A:A0 S5-1]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3271): onBytesWritten: 66 bytes successfully written (thread ID: 311)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3271): removeThreadFromList: Removing thread with ID 311
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3271): Handshake thread disposed (thread ID: 311)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3271): onIncomingConnectionConnected: [7C:F9:0E:34:8A:A0 S5-1]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3271): onConnected: [7C:F9:0E:34:8A:A0 S5-1]
I/io.jxcore.node.ConnectionHelper( 3271): onConnected: Incoming connection to peer [7C:F9:0E:34:8A:A0 S5-1]
D/io.jxcore.node.ConnectionHelper( 3271): hasConnection: No connection with peer with ID 7C:F9:0E:34:8A:A0
D/io.jxcore.node.ConnectionHelper( 3271): notifyPeerAvailability: Peer [7C:F9:0E:34:8A:A0 S5-1] is available
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3271): Exiting thread (ID: 311)
,I/jxcore-log( 3271): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:34:8A:A0","peerName":"S5-1","peerAvailable":true}]
I/jxcore-log( 3271): 
I/jxcore-log( 3271): Found peer : S5-1, Available: true
I/jxcore-log( 3271): 
,I/io.jxcore.node.ConnectionHelper( 3271): onConnected: Incoming socket thread, for peer [7C:F9:0E:34:8A:A0 S5-1], created successfully
D/io.jxcore.node.ConnectionHelper( 3271): onConnected: The total number of connections is now 1
,D/io.jxcore.node.IncomingSocketThread( 3271): Entering thread (ID: 312)
,I/io.jxcore.node.IncomingSocketThread( 3271): Local host address: localhost/127.0.0.1, port: 36469
D/io.jxcore.node.IncomingSocketThread( 3271): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3271): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3271): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3271): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3271): Exiting thread (ID: 312)
,I/jxcore-log( 3271): 2016-01-05T10:26:57.072Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3271): 
,D/io.jxcore.node.StreamCopyingThread( 3271): Entering thread (ID: 314, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3271): Entering thread (ID: 313, name: Sender)
,W/bt-btif ( 2046): info:x10
,D/        ( 2046): remote version info [b0:c5:59:3f:75:69]: 7, f, 610c
E/BluetoothRemoteDevices( 2046): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2046): tBTM_SEC_DEV:0xa3d51084 rs_disc_pending=1
W/bt-btif ( 2046): bta_dm_check_av:0
,W/bt-btif ( 2046): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 2046): process_service_search_attr_rsp
,I/jxcore-log( 3271): 2016-01-05T10:26:58.149Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3271): 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3271): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3271): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3271): onServiceDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,I/io.jxcore.node.ConnectionHelper( 3271): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28,
,D/io.jxcore.node.ConnectionHelper( 3271): notifyPeerAvailability: Peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)] is available
,I/jxcore-log( 3271): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:76:27","peerName":"Thali Test (Galaxy A3)","peerAvailable":true}]
I/jxcore-log( 3271): 
I/jxcore-log( 3271): Found peer : Thali Test (Galaxy A3), Available: true
I/jxcore-log( 3271): 
I/jxcore-log( 3271): 2016-01-05T10:26:58.167Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3271): 
,I/jxcore-log( 3271): 2016-01-05T10:26:58.190Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3271): 
,I/jxcore-log( 3271): 2016-01-05T10:26:58.194Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3271): 
,I/jxcore-log( 3271): 2016-01-05T10:26:58.232Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3271): 
,I/jxcore-log( 3271): 2016-01-05T10:26:58.238Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3271): 
,I/jxcore-log( 3271): 2016-01-05T10:26:58.273Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3271): 
,I/jxcore-log( 3271): 2016-01-05T10:26:58.276Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3271): 
,I/jxcore-log( 3271): 2016-01-05T10:26:58.313Z SendDataTCPServer.js: TCP/IP server has received 38708 bytes of data
I/jxcore-log( 3271): 
,I/jxcore-log( 3271): 2016-01-05T10:26:58.315Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data
I/jxcore-log( 3271): 
,I/jxcore-log( 3271): 2016-01-05T10:26:58.317Z SendDataTCPServer.js: TCP/IP server has received 42668 bytes of data
I/jxcore-log( 3271): 
,I/jxcore-log( 3271): 2016-01-05T10:26:58.352Z SendDataTCPServer.js: TCP/IP server has received 48608 bytes of data
I/jxcore-log( 3271): 
,I/jxcore-log( 3271): 2016-01-05T10:26:58.361Z SendDataTCPServer.js: TCP/IP server has received 50588 bytes of data
I/jxcore-log( 3271): 
,I/jxcore-log( 3271): 2016-01-05T10:26:58.368Z SendDataTCPServer.js: TCP/IP server has received 52568 bytes of data
I/jxcore-log( 3271): 
,I/jxcore-log( 3271): 2016-01-05T10:26:58.403Z SendDataTCPServer.js: TCP/IP server has received 64448 bytes of data
I/jxcore-log( 3271): 
,I/wpa_supplicant( 1025): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3271): 2016-01-05T10:26:58.578Z SendDataTCPServer.js: TCP/IP server has received 66428 bytes of data
I/jxcore-log( 3271): 
,I/BluetoothBondStateMachine( 2046): bondStateChangeCallback: Status: 0 Address: B0:C5:59:3F:75:69 newState: 1
E/bt-btif ( 2046): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2046): Bond State Change Intent:B0:C5:59:3F:75:69 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2046): Entering PendingCommandState State
,I/jxcore-log( 3271): 2016-01-05T10:26:58.650Z SendDataTCPServer.js: TCP/IP server has received 80288 bytes of data
I/jxcore-log( 3271): 
,W/BluetoothEventManager( 2659): CachedBluetoothDevice for device B0:C5:59:3F:75:69 not found, calling readPairedDevices().
,I/jxcore-log( 3271): 2016-01-05T10:26:58.670Z SendDataTCPServer.js: TCP/IP server has received 82268 bytes of data
I/jxcore-log( 3271): 
,E/BluetoothEventManager( 2659): Got bonding state changed for B0:C5:59:3F:75:69, but we have no record of that device.
,I/jxcore-log( 3271): 2016-01-05T10:26:58.703Z SendDataTCPServer.js: TCP/IP server has received 88208 bytes of data
I/jxcore-log( 3271): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3271): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3271): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3271): onServiceDiscovered: [7C:F9:0E:37:96:AB A5-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB A5-1]
I/io.jxcore.node.ConnectionHelper( 3271): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1], Bluetooth address: 7C:F9:0E:37:96:AB, device name: , device address: 7e:f9:0e:37:96:ac
D/io.jxcore.node.ConnectionHelper( 3271): notifyPeerAvailability: Peer [7C:F9:0E:37:96:AB A5-1] is available
I/jxcore-log( 3271): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:37:96:AB","peerName":"A5-1","peerAvailable":true}]
I/jxcore-log( 3271): 
I/jxcore-log( 3271): Found peer : A5-1, Available: true
I/jxcore-log( 3271): 
,I/jxcore-log( 3271): 2016-01-05T10:26:58.765Z SendDataTCPServer.js: TCP/IP server has received 90188 bytes of data
I/jxcore-log( 3271): 
,I/jxcore-log( 3271): 2016-01-05T10:26:58.820Z SendDataTCPServer.js: TCP/IP server has received 92168 bytes of data
I/jxcore-log( 3271): 
,I/jxcore-log( 3271): 2016-01-05T10:26:58.852Z SendDataTCPServer.js: TCP/IP server has received 94148 bytes of data
I/jxcore-log( 3271): 
,I/jxcore-log( 3271): 2016-01-05T10:26:58.898Z SendDataTCPServer.js: TCP/IP server has received 96128 bytes of data
I/jxcore-log( 3271): 
,I/jxcore-log( 3271): 2016-01-05T10:26:58.906Z SendDataTCPServer.js: TCP/IP server has received 98108 bytes of data
I/jxcore-log( 3271): 
,I/jxcore-log( 3271): 2016-01-05T10:26:58.913Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3271): 
,W/bt-btif ( 2046): invalid rfc slot id: 5
,W/io.jxcore.node.StreamCopyingThread( 3271): Either failed to read from the output stream or write to the input stream (thread ID: 314, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 3271): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3271): onDisconnected: Incoming connection, peer [7C:F9:0E:34:8A:A0 S5-1] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3271): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 312
D/io.jxcore.node.IncomingSocketThread( 3271): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3271): doStop: Thread ID: 314
D/io.jxcore.node.IncomingSocketThread( 3271): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3271): doStop: Thread ID: 313
D/io.jxcore.node.IncomingSocketThread( 3271): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 3271): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3271): Either failed to read from the output stream or write to the input stream (thread ID: 313, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3271): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3271): onDisconnected: Incoming connection, peer [7C:F9:0E:34:8A:A0 S5-1] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.IncomingSocketThread( 3271): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 3271): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3271): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3271): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.ConnectionHelper( 3271): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.StreamCopyingThread( 3271): Exiting thread (ID: 313, name: Sender)
,I/wpa_supplicant( 1025): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BluetoothBondStateMachine( 2046): bondStateChangeCallback: Status: 0 Address: B0:C5:59:3F:75:69 newState: 0
,D/BluetoothAdapterProperties( 2046): Failed to remove device: B0:C5:59:3F:75:69
,D/io.jxcore.node.StreamCopyingThread( 3271): Exiting thread (ID: 314, name: Receiver)
,I/BluetoothBondStateMachine( 2046): Bond State Change Intent:B0:C5:59:3F:75:69 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2046): StableState(): Entering Off State
,W/BluetoothEventManager( 2659): CachedBluetoothDevice for device B0:C5:59:3F:75:69 not found, calling readPairedDevices().
,I/jxcore-log( 3271): 2016-01-05T10:26:59.095Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3271): 
,E/BluetoothEventManager( 2659): Got bonding state changed for B0:C5:59:3F:75:69, but we have no record of that device.
,I/wpa_supplicant( 1025): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 1025): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3271): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3271): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,E/bt-btm  ( 2046): tBTM_SEC_DEV:0xa3d50ebc rs_disc_pending=0
W/bt-btif ( 2046): bta_dm_check_av:0
,W/bt-btif ( 2046): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 2046): rfc_find_lcid_mcb LCID reused LCID:0x42 current:0x0
W/bt-rfcomm( 2046): RFCOMM_DisconnectInd LCID:0x42
,W/bt-btif ( 2046): new conn_srvc id:26, app_id:1
W/bt-btif ( 2046): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2046): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3271): onSocketConnected: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3271): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 310)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3271): onBytesWritten: 66 bytes successfully written (thread ID: 315)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3271): Outgoing connection initialized (*handshake* thread ID: 315)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3271): Exiting thread (thread ID: 310)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3271): Entering thread (ID: 315)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3271): onBytesRead: Read 81 bytes successfully (thread ID: 315)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3271): Handshake succeeded with [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3271): onHandshakeSucceeded: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3271): Exiting thread (ID: 315)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3271): onConnected: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
I/io.jxcore.node.ConnectionHelper( 3271): onConnected: Outgoing connection to peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/io.jxcore.node.ConnectionHelper( 3271): hasConnection: No connection with peer with ID B0:C5:59:3F:75:69
W/io.jxcore.node.ConnectionHelper( 3271): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 3271): onConnected: Outgoing socket thread, for peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], created successfully
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3271): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 3271): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 3271): Entering thread (ID: 316)
,D/io.jxcore.node.OutgoingSocketThread( 3271): Server socket local port: 36593
,I/io.jxcore.node.OutgoingSocketThread( 3271): Now accepting connections...
,E/bt-btm  ( 2046): tBTM_SEC_DEV:0xa3d50ebc rs_disc_pending=1
W/bt-btif ( 2046): bta_dm_check_av:0
,W/bt-btif ( 2046): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2046): new conn_srvc id:26, app_id:255
W/bt-btif ( 2046): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2046): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2046): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3271): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3271): Incoming connection initialized (thread ID: 317)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3271): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3271): Entering thread (ID: 317)
,I/io.jxcore.node.ConnectionHelper( 3271): onListeningForIncomingConnections: Outgoing connection is using port 36593 (peer ID: B0:C5:59:3F:75:69)
I/jxcore-log( 3271): 2016-01-05T10:27:00.869Z SendDataConnector.js: CLIENT connected to 36593, error: null
I/jxcore-log( 3271): 
I/jxcore-log( 3271): 2016-01-05T10:27:00.870Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3271): 
,I/io.jxcore.node.OutgoingSocketThread( 3271): Incoming data from address: /127.0.0.1, port: 36593
D/io.jxcore.node.OutgoingSocketThread( 3271): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3271): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3271): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3271): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3271): Exiting thread (ID: 316)
,D/io.jxcore.node.StreamCopyingThread( 3271): Entering thread (ID: 319, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3271): Entering thread (ID: 318, name: Sender)
,I/jxcore-log( 3271): 2016-01-05T10:27:00.916Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3271): 
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3271): onBytesRead: Read 81 bytes successfully (thread ID: 317)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3271): Got valid identity from [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3271): onBytesWritten: 66 bytes successfully written (thread ID: 317)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3271): removeThreadFromList: Removing thread with ID 317
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3271): Handshake thread disposed (thread ID: 317)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3271): onIncomingConnectionConnected: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3271): Exiting thread (ID: 317)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3271): onConnected: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
I/io.jxcore.node.ConnectionHelper( 3271): onConnected: Incoming connection to peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/io.jxcore.node.ConnectionHelper( 3271): hasConnection: We have an outgoing connection with peer with ID B0:C5:59:3F:75:69
W/io.jxcore.node.ConnectionHelper( 3271): onConnected: Already connected with peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], continuing anyway...
W/io.jxcore.node.ConnectionHelper( 3271): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 3271): onConnected: Incoming socket thread, for peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], created successfully
D/io.jxcore.node.ConnectionHelper( 3271): onConnected: The total number of connections is now 2
,D/io.jxcore.node.IncomingSocketThread( 3271): Entering thread (ID: 320)
,I/io.jxcore.node.IncomingSocketThread( 3271): Local host address: localhost/127.0.0.1, port: 36469
D/io.jxcore.node.IncomingSocketThread( 3271): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3271): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3271): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.IncomingSocketThread( 3271): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3271): Exiting thread (ID: 320)
I/jxcore-log( 3271): 2016-01-05T10:27:01.381Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3271): 
,D/io.jxcore.node.StreamCopyingThread( 3271): Entering thread (ID: 321, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 3271): Entering thread (ID: 322, name: Receiver)
,I/jxcore-log( 3271): 2016-01-05T10:27:01.864Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3271): 
,I/jxcore-log( 3271): 2016-01-05T10:27:01.871Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3271): 
,I/jxcore-log( 3271): 2016-01-05T10:27:01.897Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3271): 
,I/jxcore-log( 3271): 2016-01-05T10:27:01.903Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3271): 
,I/jxcore-log( 3271): 2016-01-05T10:27:01.910Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3271): 
,I/jxcore-log( 3271): 2016-01-05T10:27:01.916Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3271): 
,I/jxcore-log( 3271): 2016-01-05T10:27:01.931Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3271): 
,I/jxcore-log( 3271): 2016-01-05T10:27:01.964Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3271): 
,I/jxcore-log( 3271): 2016-01-05T10:27:02.071Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3271): 
I/jxcore-log( 3271): 2016-01-05T10:27:02.073Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3271): 
,I/jxcore-log( 3271): 2016-01-05T10:27:02.095Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3271): 
,I/jxcore-log( 3271): 2016-01-05T10:27:02.168Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3271): 
,I/jxcore-log( 3271): 2016-01-05T10:27:02.459Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3271): 
,I/jxcore-log( 3271): 2016-01-05T10:27:02.473Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3271): 
,I/jxcore-log( 3271): 2016-01-05T10:27:02.504Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3271): 
,I/jxcore-log( 3271): 2016-01-05T10:27:02.515Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3271): 
,I/jxcore-log( 3271): 2016-01-05T10:27:02.522Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3271): 
,I/jxcore-log( 3271): 2016-01-05T10:27:02.529Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3271): 
,I/jxcore-log( 3271): 2016-01-05T10:27:02.543Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3271): 
I/jxcore-log( 3271): 2016-01-05T10:27:02.546Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3271): 
,I/jxcore-log( 3271): 2016-01-05T10:27:02.581Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3271): 
,I/jxcore-log( 3271): 2016-01-05T10:27:02.589Z SendDataTCPServer.js: TCP/IP server has received 36728 bytes of data
I/jxcore-log( 3271): 
,I/jxcore-log( 3271): 2016-01-05T10:27:02.592Z SendDataTCPServer.js: TCP/IP server has received 38708 bytes of data
I/jxcore-log( 3271): 
,I/jxcore-log( 3271): 2016-01-05T10:27:02.595Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data
I/jxcore-log( 3271): 
,I/jxcore-log( 3271): 2016-01-05T10:27:02.603Z SendDataTCPServer.js: TCP/IP server has received 42668 bytes of data
I/jxcore-log( 3271): 
,I/jxcore-log( 3271): 2016-01-05T10:27:02.639Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3271): 
I/jxcore-log( 3271): 2016-01-05T10:27:02.639Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3271): 
I/jxcore-log( 3271): oneRoundDownNow
I/jxcore-log( 3271): 
I/jxcore-log( 3271): 2016-01-05T10:27:02.640Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3271): 
I/jxcore-log( 3271): 2016-01-05T10:27:02.640Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3271): 
D/io.jxcore.node.ConnectionHelper( 3271): disconnectOutgoingConnection: Trying to close connection to peer with ID B0:C5:59:3F:75:69
I/io.jxcore.node.ConnectionHelper( 3271): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: B0:C5:59:3F:75:69
I/io.jxcore.node.IncomingSocketThread( 3271): close
D/io.jxcore.node.IncomingSocketThread( 3271): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3271): doStop: Thread ID: 319
D/io.jxcore.node.IncomingSocketThread( 3271): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3271): doStop: Thread ID: 318
D/io.jxcore.node.IncomingSocketThread( 3271): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 3271): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3271): Either failed to read from the output stream or write to the input stream (thread ID: 318, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3271): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
,W/io.jxcore.node.ConnectionHelper( 3271): onDisconnected: Outgoing connection, peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.IncomingSocketThread( 3271): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 3271): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3271): closeBluetoothSocketAndStreams
W/io.jxcore.node.StreamCopyingThread( 3271): Either failed to read from the output stream or write to the input stream (thread ID: 319, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 3271): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3271): onDisconnected: Outgoing connection, peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3271): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3271): disconnectOutgoingConnection: Successfully disconnected (peer ID: B0:C5:59:3F:75:69
,E/io.jxcore.node.ConnectionHelper( 3271): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID B0:C5:59:3F:75:69
D/io.jxcore.node.ConnectionHelper( 3271): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3271): Exiting thread (ID: 318, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 3271): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID B0:C5:59:3F:75:69
D/io.jxcore.node.ConnectionHelper( 3271): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3271): Exiting thread (ID: 319, name: Receiver)
,I/jxcore-log( 3271): 2016-01-05T10:27:02.647Z SendDataConnector.js: Mobile.Disconnect() callback with peer B0:C5:59:3F:75:69
I/jxcore-log( 3271): 
I/jxcore-log( 3271): ---- round done--------
I/jxcore-log( 3271): 
I/jxcore-log( 3271): startWithNextDevice
I/jxcore-log( 3271): 
I/jxcore-log( 3271): device[2]: 7C:F9:0E:34:8A:A0
I/jxcore-log( 3271): 
I/jxcore-log( 3271): 2016-01-05T10:27:02.648Z SendDataConnector.js: Start called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3271): 
I/jxcore-log( 3271): 2016-01-05T10:27:02.648Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3271): 
I/jxcore-log( 3271): 2016-01-05T10:27:02.648Z SendDataConnector.js: do connect now
I/jxcore-log( 3271): 
I/io.jxcore.node.ConnectionHelper( 3271): connect: Trying to connect to peer with ID 7C:F9:0E:34:8A:A0
D/io.jxcore.node.ConnectionHelper( 3271): hasConnection: No connection with peer with ID 7C:F9:0E:34:8A:A0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3271): connect: [7C:F9:0E:34:8A:A0 S5-1]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3271): connect: Trying to start connecting to S5-1 in address 7C:F9:0E:34:8A:A0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3271): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3271): setMaxNumberOfRetries: 0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3271): onConnecting: S5-1 7C:F9:0E:34:8A:A0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3271): connect: Started connecting to S5-1 in address 7C:F9:0E:34:8A:A0
I/io.jxcore.node.ConnectionHelper( 3271): connect: Connection process successfully started (peer ID: 7C:F9:0E:34:8A:A0)
,I/jxcore-log( 3271): 2016-01-05T10:27:02.655Z SendDataTCPServer.js: TCP/IP server has received 54548 bytes of data
I/jxcore-log( 3271): 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3271): Trying to connect to peer with address 7C:F9:0E:34:8A:A0 (thread ID: 323)
W/BluetoothAdapter( 3271): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2046): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/jxcore-log( 3271): 2016-01-05T10:27:02.659Z SendDataTCPServer.js: TCP/IP server has received 56528 bytes of data
I/jxcore-log( 3271): 
,I/jxcore-log( 3271): 2016-01-05T10:27:02.692Z SendDataTCPServer.js: TCP/IP server has received 58508 bytes of data
I/jxcore-log( 3271): 
,W/bt-btif ( 2046): bta_jv_rfc_port_to_cb(port_handle:0xa):jv handle:0x0 not FOUND
,I/jxcore-log( 3271): 2016-01-05T10:27:02.698Z SendDataTCPServer.js: TCP/IP server has received 60488 bytes of data
I/jxcore-log( 3271): 
,I/jxcore-log( 3271): 2016-01-05T10:27:02.710Z SendDataTCPServer.js: TCP/IP server has received 62468 bytes of data
I/jxcore-log( 3271): 
,I/jxcore-log( 3271): 2016-01-05T10:27:02.742Z SendDataTCPServer.js: TCP/IP server has received 66428 bytes of data
I/jxcore-log( 3271): 
,I/jxcore-log( 3271): 2016-01-05T10:27:02.744Z SendDataTCPServer.js: TCP/IP server has received 68408 bytes of data
I/jxcore-log( 3271): 
,I/jxcore-log( 3271): 2016-01-05T10:27:02.747Z SendDataTCPServer.js: TCP/IP server has received 70388 bytes of data
I/jxcore-log( 3271): 
,I/jxcore-log( 3271): 2016-01-05T10:27:02.752Z SendDataTCPServer.js: TCP/IP server has received 72368 bytes of data
I/jxcore-log( 3271): 
,I/jxcore-log( 3271): 2016-01-05T10:27:02.783Z SendDataTCPServer.js: TCP/IP server has received 74348 bytes of data
I/jxcore-log( 3271): 
,I/jxcore-log( 3271): 2016-01-05T10:27:02.792Z SendDataTCPServer.js: TCP/IP server has received 76328 bytes of data
I/jxcore-log( 3271): 
,I/jxcore-log( 3271): 2016-01-05T10:27:02.795Z SendDataTCPServer.js: TCP/IP server has received 78308 bytes of data
I/jxcore-log( 3271): 
,I/jxcore-log( 3271): 2016-01-05T10:27:02.805Z SendDataTCPServer.js: TCP/IP server has received 80288 bytes of data
I/jxcore-log( 3271): 
,I/jxcore-log( 3271): 2016-01-05T10:27:02.834Z SendDataTCPServer.js: TCP/IP server has received 82268 bytes of data
I/jxcore-log( 3271): 
,I/jxcore-log( 3271): 2016-01-05T10:27:02.863Z SendDataTCPServer.js: TCP/IP server has received 88208 bytes of data
I/jxcore-log( 3271): 
,I/jxcore-log( 3271): 2016-01-05T10:27:02.871Z SendDataTCPServer.js: TCP/IP server has received 90188 bytes of data
I/jxcore-log( 3271): 
,I/jxcore-log( 3271): 2016-01-05T10:27:02.878Z SendDataTCPServer.js: TCP/IP server has received 92168 bytes of data
I/jxcore-log( 3271): 
,I/jxcore-log( 3271): 2016-01-05T10:27:02.883Z SendDataTCPServer.js: TCP/IP server has received 94148 bytes of data
I/jxcore-log( 3271): 
,I/jxcore-log( 3271): 2016-01-05T10:27:02.916Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3271): 
,W/bt-sdp  ( 2046): process_service_search_attr_rsp
,W/bt-btif ( 2046): invalid rfc slot id: 7
,W/io.jxcore.node.StreamCopyingThread( 3271): Either failed to read from the output stream or write to the input stream (thread ID: 322, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 3271): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3271): onDisconnected: Incoming connection, peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,I/io.jxcore.node.ConnectionHelper( 3271): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 320
D/io.jxcore.node.IncomingSocketThread( 3271): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3271): doStop: Thread ID: 322
D/io.jxcore.node.IncomingSocketThread( 3271): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3271): doStop: Thread ID: 321
D/io.jxcore.node.IncomingSocketThread( 3271): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 3271): closeLocalSocketAndStreams: Closing the local input stream...
,D/io.jxcore.node.IncomingSocketThread( 3271): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 3271): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3271): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3271): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3271): Exiting thread (ID: 322, name: Receiver)
,W/io.jxcore.node.StreamCopyingThread( 3271): Either failed to read from the output stream or write to the input stream (thread ID: 321, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3271): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3271): onDisconnected: Incoming connection, peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.ConnectionHelper( 3271): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3271): Exiting thread (ID: 321, name: Sender)
,I/jxcore-log( 3271): 2016-01-05T10:27:03.053Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3271): 
,W/bt-btif ( 2046): new conn_srvc id:26, app_id:1
W/bt-btif ( 2046): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 2046): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3271): onSocketConnected: [7C:F9:0E:34:8A:A0 S5-1]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3271): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 323)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3271): onBytesWritten: 66 bytes successfully written (thread ID: 324)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3271): Outgoing connection initialized (*handshake* thread ID: 324)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3271): Exiting thread (thread ID: 323)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3271): Entering thread (ID: 324)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3271): onBytesRead: Read 63 bytes successfully (thread ID: 324)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3271): Handshake succeeded with [7C:F9:0E:34:8A:A0 S5-1]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3271): onHandshakeSucceeded: [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3271): Exiting thread (ID: 324)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3271): onConnected: [7C:F9:0E:34:8A:A0 S5-1]
I/io.jxcore.node.ConnectionHelper( 3271): onConnected: Outgoing connection to peer [7C:F9:0E:34:8A:A0 S5-1]
D/io.jxcore.node.ConnectionHelper( 3271): hasConnection: No connection with peer with ID 7C:F9:0E:34:8A:A0
W/io.jxcore.node.ConnectionHelper( 3271): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 S5-1] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 3271): onConnected: Outgoing socket thread, for peer [7C:F9:0E:34:8A:A0 S5-1], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3271): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 3271): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 3271): Entering thread (ID: 325)
,D/io.jxcore.node.OutgoingSocketThread( 3271): Server socket local port: 45714
,I/io.jxcore.node.OutgoingSocketThread( 3271): Now accepting connections...
,D/btif_config_util( 2046): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/io.jxcore.node.ConnectionHelper( 3271): onListeningForIncomingConnections: Outgoing connection is using port 45714 (peer ID: 7C:F9:0E:34:8A:A0)
I/jxcore-log( 3271): 2016-01-05T10:27:04.124Z SendDataConnector.js: CLIENT connected to 45714, error: null
I/jxcore-log( 3271): 
I/jxcore-log( 3271): 2016-01-05T10:27:04.125Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3271): 
,I/io.jxcore.node.OutgoingSocketThread( 3271): Incoming data from address: /127.0.0.1, port: 45714
D/io.jxcore.node.OutgoingSocketThread( 3271): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3271): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3271): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3271): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3271): Exiting thread (ID: 325)
,I/jxcore-log( 3271): 2016-01-05T10:27:04.150Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3271): 
,D/io.jxcore.node.StreamCopyingThread( 3271): Entering thread (ID: 326, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 3271): Entering thread (ID: 327, name: Receiver)
,I/jxcore-log( 3271): 2016-01-05T10:27:05.229Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3271): 
,W/bt-btif ( 2046): info:x10
,D/        ( 2046): remote version info [7c:f9:0e:51:18:22]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2046): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3271): 2016-01-05T10:27:05.450Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3271): 
,I/jxcore-log( 3271): 2016-01-05T10:27:05.599Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3271): 
,E/bt-btm  ( 2046): tBTM_SEC_DEV:0xa3d5124c rs_disc_pending=0
W/bt-btif ( 2046): bta_dm_check_av:0
,W/bt-btif ( 2046): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3271): 2016-01-05T10:27:05.714Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3271): 
,I/jxcore-log( 3271): 2016-01-05T10:27:05.829Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3271): 
,I/jxcore-log( 3271): teardown
I/jxcore-log( 3271): 
,I/jxcore-log( 3271): testSendData stopped
I/jxcore-log( 3271): 
I/io.jxcore.node.ConnectionHelper( 3271): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3271): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3271): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3271): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3271): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3271): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3271): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3271): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3271): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3271): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3271): stop: Stopping P2P device discovery...
,I/wpa_supplicant( 1025): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1025): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 1025): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
I/wpa_supplicant( 1025): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 1025): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 1025): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3271): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): onIsWifiPeerDiscoveryStartedChanged: false
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3271): release: No more listeners, de-initializing...
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3271): release: The given listener does not exist in the list
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3271): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3271): setState: NOT_STARTED
D/io.jxcore.node.ConnectionHelper( 3271): closeAndRemoveAllOutgoingConnections: Peer: [7C:F9:0E:34:8A:A0 S5-1]
I/io.jxcore.node.OutgoingSocketThread( 3271): close
D/io.jxcore.node.OutgoingSocketThread( 3271): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3271): doStop: Thread ID: 327
D/io.jxcore.node.OutgoingSocketThread( 3271): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3271): doStop: Thread ID: 326
D/io.jxcore.node.OutgoingSocketThread( 3271): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 3271): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3271): Either failed to read from the output stream or write to the input stream (thread ID: 326, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3271): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3271): onDisconnected: Outgoing connection, peer [7C:F9:0E:34:8A:A0 S5-1] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.OutgoingSocketThread( 3271): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 3271): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3271): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3271): Either failed to read from the output stream or write to the input stream (thread ID: 327, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 3271): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3271): onDisconnected: Outgoing connection, peer [7C:F9:0E:34:8A:A0 S5-1] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,E/io.jxcore.node.ConnectionHelper( 3271): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:34:8A:A0
D/io.jxcore.node.ConnectionHelper( 3271): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3271): Exiting thread (ID: 326, name: Sender)
E/io.jxcore.node.ConnectionHelper( 3271): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:34:8A:A0
D/io.jxcore.node.ConnectionHelper( 3271): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3271): Exiting thread (ID: 327, name: Receiver)
,I/jxcore-log( 3271): StopBroadcasting went ok
I/jxcore-log( 3271): 
I/jxcore-log( 3271): 2016-01-05T10:27:06.402Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3271): 
,I/jxcore-log( 3271): 2016-01-05T10:27:06.403Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 3271): 
I/jxcore-log( 3271): 2016-01-05T10:27:06.403Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3271): 
D/io.jxcore.node.ConnectionHelper( 3271): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:34:8A:A0
,E/io.jxcore.node.ConnectionHelper( 3271): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:34:8A:A0
D/io.jxcore.node.ConnectionHelper( 3271): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3271): disconnectOutgoingConnection: Failed to disconnect (peer ID: 7C:F9:0E:34:8A:A0), either no such connection or failed to close the connection
I/jxcore-log( 3271): 2016-01-05T10:27:06.405Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3271): 
,I/jxcore-log( 3271): 2016-01-05T10:27:06.408Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
I/jxcore-log( 3271): 
I/chromium( 3271): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
I/io.jxcore.node.ConnectionHelper( 3271): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3271): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3271): P2P device discovery stopped successfully
I/io.jxcore.node.ConnectionHelper( 3271): onDiscoveryManagerStateChanged: NOT_STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3271): Service requests cleared successfully
,I/jxcore-log( 3271): ****TEST TOOK:  ms ****
I/jxcore-log( 3271): 
I/jxcore-log( 3271): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3271): 
,I/BluetoothBondStateMachine( 2046): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:51:18:22 newState: 1
E/bt-btif ( 2046): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2046): Bond State Change Intent:7C:F9:0E:51:18:22 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2046): Entering PendingCommandState State
,W/BluetoothEventManager( 2659): CachedBluetoothDevice for device 7C:F9:0E:51:18:22 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2659): Got bonding state changed for 7C:F9:0E:51:18:22, but we have no record of that device.
,E/bt-btm  ( 2046): tBTM_SEC_DEV:0xa3d50ebc rs_disc_pending=0
W/bt-btif ( 2046): bta_dm_check_av:0
W/bt-btif ( 2046): btif_dm_cback : unhandled event (14)
,D/AndroidRuntime( 3698): 
D/AndroidRuntime( 3698): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 3698): CheckJNI is OFF
,W/bt-btif ( 2046): bta_jv_rfc_port_to_cb(port_handle:0xc):jv handle:0x0 not FOUND
,D/AndroidRuntime( 3698): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  735): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
,I/ActivityManager(  735): Killing 3271:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
,I/WindowState(  735): WIN DEATH: Window{b10adb9 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  735): Client connection lost with reason: 4
,W/PackageSettings(  735): Skipping PackageSetting{2fd97d9d com.example.hello/10278} due to missing metadata
,I/ActivityManager(  735):   Force finishing activity ActivityRecord{437777f u0 com.test.thalitest/.MainActivity t214}
,I/ActivityManager(  735): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
,I/ActivityManager(  735):   Force finishing activity ActivityRecord{437777f u0 com.test.thalitest/.MainActivity t214 f}
W/ActivityManager(  735): Duplicate finish request for ActivityRecord{437777f u0 com.test.thalitest/.MainActivity t214 f}
,I/art     ( 1274): Explicit concurrent mark sweep GC freed 3945(293KB) AllocSpace objects, 1(126KB) LOS objects, 23% free, 25MB/33MB, paused 344us total 17.123ms
,I/art     ( 1411): Explicit concurrent mark sweep GC freed 9153(581KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 19MB/25MB, paused 298us total 44.686ms
,I/art     (  735): Explicit concurrent mark sweep GC freed 29501(1541KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 1.366ms total 63.241ms
,I/Keyboard.Facilitator( 1087): resetDictionaries() : en_US
,W/ActivityManager(  735): Spurious death for ProcessRecord{665bdda 3271:com.test.thalitest/u0a270}, curProc for 3271: null
,I/art     ( 1635): Explicit concurrent mark sweep GC freed 18859(1047KB) AllocSpace objects, 5(80KB) LOS objects, 24% free, 22MB/30MB, paused 2.102ms total 79.211ms
I/Keyboard.Facilitator.DecoderInitializer( 1087): run()
,I/InputReader(  735): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 1566): Ignoring removeGeofence because network location is disabled.
,I/Decoder ( 1087): createOrResetDecoder
,D/VoicemailCleanupService( 2867): Cleaning up data for package: com.test.thalitest
,I/ConfigService( 1566): onCreate
,I/UpdateIcingCorporaServi( 1411): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,W/Launcher( 1274): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@126a515e new=com.google.android.velvet.VelvetApplication@126a515e
,I/Adreno-EGL(  935): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
I/OpenGLRenderer(  935): Initialized EGL, version 1.4
,D/BackupManagerService(  735): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  735): Receieved: android.intent.action.PACKAGE_REMOVED
E/bt-btm  ( 2046): btm_sec_disconnected - Clearing Pending flag
,D/OpenGLRenderer(  935): Enabling debug mode 0
I/ActivityManager(  735): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3738 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,D/TaskPersister(  735): removeObsoleteFile: deleting file=214_task.xml
,D/BluetoothMapService( 2046): onReceive
,I/art     (  735): Explicit concurrent mark sweep GC freed 8031(447KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 1.615ms total 151.179ms
,W/InputMethodManagerService(  735): Focus gain on non-focused client com.android.internal.view.IInputMethodClient$Stub$Proxy@21f65cf2 (uid=10034 pid=935)
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1087): run()
,W/ContextImpl( 3738): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
,D/PackageBroadcastService( 1635): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1635): Clearing selected account for com.test.thalitest
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1087): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1087): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1087): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1087): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1087): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1087): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1087): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1087): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1087): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1087): run()
,I/Keyboard.Facilitator.RecurringTaskScheduler( 1087): run()
,I/StatsUtilsManager( 1087): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1087): shouldRecordStats() = Too Soon
D/ChimeraCfgMgr( 1635): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1635): Module APK com.google.android.play.games already loaded
,I/LocationSettingsChecker( 1635): Removing dialog suppression flag for package com.test.thalitest
,D/ChimeraCfgMgr( 1635): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1635): Module APK com.google.android.play.games already loaded
,I/ActivityManager(  735): Killing 2529:com.google.android.gm/u0a70 (adj 15): empty #17
,D/gH_CompatibleDatabase( 1635): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1635): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1635): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1635): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/AndroidRuntime( 3698): Shutting down VM
,D/gH_CompatibleDatabase( 1635): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1635): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1635): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/gH_CompatibleDatabase( 1635): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1635): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 1635): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,D/gH_CompatibleDatabase( 1635): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1635): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1635): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,E/NetworkScheduler.SchedulerReceiver( 1566): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1566): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,W/libprocessgroup(  735): failed to open /acct/uid_10070/pid_2529/cgroup.procs: No such file or directory
,I/Launcher( 1274): Deferring update until onResume
,W/ResourcesManager( 1274): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/BaseAppContext( 1635): Using Auth Proxy for data requests.
,W/ResourcesManager( 1274): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,E/bt-btm  ( 2046): tBTM_SEC_DEV:0xa3d50ebc rs_disc_pending=1
W/bt-btif ( 2046): bta_dm_check_av:0
,W/bt-btif ( 2046): btif_dm_cback : unhandled event (14)
,I/ActivityManager(  735): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3772 uid=10039 gids={50039, 9997} abi=armeabi-v7a
,I/Launcher( 1274): Deferring update until onResume
,W/BaseAppContext( 1635): Using Auth Proxy for data requests.
,I/GMPM-SVC( 1635): App measurement is starting up, version: 8489
,I/GMPM-SVC( 1635): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,I/UpdateIcingCorporaServi( 1411): UpdateCorporaTask done [took 353 ms] updated apps [took 353 ms] 
,I/Icing   ( 1635): doRemovePackageData com.test.thalitest
,I/ActivityManager(  735): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3796 uid=10007 gids={50007, 9997, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  735): Killing 1945:com.google.android.calendar/u0a31 (adj 15): empty #17
,W/libprocessgroup(  735): failed to open /acct/uid_10031/pid_1945/cgroup.procs: No such file or directory
,I/ActivityManager(  735): Killing 3018:com.google.android.gms:car/u0a8 (adj 15): empty #17
,W/libprocessgroup(  735): failed to open /acct/uid_10008/pid_3018/cgroup.procs: No such file or directory
,E/SQLiteLog( 1635): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
I/art     ( 1566): Explicit concurrent mark sweep GC freed 98828(5MB) AllocSpace objects, 28(471KB) LOS objects, 40% free, 23MB/39MB, paused 1.148ms total 87.970ms
,E/GMPM-SVC( 1635): Task exception on worker thread: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850): com.google.android.gms.measurement.internal.e.b(SourceFile:321)
,D/BluetoothManagerService(  735): Message: 20
D/BluetoothManagerService(  735): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1b21934d:true
,E/DataBuffer( 1566): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2693a831)
E/DataBuffer( 1566): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3103bb16)
E/DataBuffer( 1566): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@a9b8c97)
E/DataBuffer( 1566): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3cdb0e84)
,E/DataBuffer( 1566): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@25c9966d)
E/DataBuffer( 1566): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@7f872a2)
,I/BTConnectionReceiver( 1411): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,E/SharedPreferencesImpl( 1635): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
,D/ExternalStorage( 3796): After updating volumes, found 1 active roots
,I/BluetoothClassifier( 1411): Bluetooth Device Name: Thali Test (Galaxy S5)

```
