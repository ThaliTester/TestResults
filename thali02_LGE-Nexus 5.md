#### Test 543122982543be8_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
I/GAv4    ( 3156): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3156):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3156):   adb logcat -s GAv4
W/GAv4    ( 3156): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3156): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3156): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 3156): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
D/Finsky  ( 2607): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
W/ResourcesManager( 3156): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3156): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  761): Killing 2578:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
V/JNIHelp ( 3156): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/libprocessgroup(  761): failed to open /acct/uid_10069/pid_2578/cgroup.procs: No such file or directory
W/System  ( 3156): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3156): Installed default security provider GmsCore_OpenSSL
V/GLSActivity( 1573): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 1594): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/Icing   ( 1594): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1594): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/Icing   ( 1594): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
,D/AndroidRuntime( 3209): 
D/AndroidRuntime( 3209): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3209): CheckJNI is OFF
D/AndroidRuntime( 3209): Calling main entry com.android.commands.am.Am
I/ActivityManager(  761): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  761): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3223 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3209): Shutting down VM
V/ActivityManager(  761): Display changed displayId=0
I/WebViewFactory( 3223): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3223): Time to load native libraries: 2 ms (timestamps 7778-7780)
I/LibraryLoader( 3223): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3223): Binding Chromium to main looper Looper (main, tid 1) {12755cf9}
I/LibraryLoader( 3223): Expected native library version number "",actual native library version number ""
I/chromium( 3223): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3223): Initializing chromium process, singleProcess=true
W/art     ( 3223): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3223): ApplicationContext is null in ApplicationStatus
W/chromium( 3223): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3223): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3223): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3223): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  761): Message: 20
D/BluetoothManagerService(  761): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@170fb5a6:true
,W/art     ( 3223): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3223): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3223): CordovaWebView is running on device made by: LGE
,W/art     ( 3223): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3223): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3223): Render dirty regions requested: true
,D/Atlas   ( 3223): Validating map...
,W/chromium( 3223): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/ActivityManager(  761): Killing 2527:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10045/pid_2527/cgroup.procs: No such file or directory
,I/OpenGLRenderer( 3223): Initialized EGL, version 1.4
D/OpenGLRenderer( 3223): Enabling debug mode 0
,I/Keyboard.Facilitator( 1096): onFinishInput()
,W/IInputConnectionWrapper( 3223): showStatusIcon on inactive InputConnection
,I/ActivityManager(  761): Displayed com.test.thalitest/.MainActivity: +420ms (total +56s166ms)
,W/BindingManager( 3223): Cannot call determinedVisibility() - never saw a connection for the pid: 3223
,D/JsMessageQueue( 3223): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3223): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257332480
D/JX-Cordova( 3223): jxcore cordova android initializing
,W/jxcore-log( 3223): Initializing JXcore engine
W/jxcore-log( 3223): JXcore engine is ready
W/jxcore-log( 3223): Starting JXcore engine
,W/.test.thalitest( 3223): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[6639]" dev="sockfs" ino=6639 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3223): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 3223): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6708]" dev="sockfs" ino=6708 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3223): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[19721]" dev="sockfs" ino=19721 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3223): Platform android
W/jxcore-log( 3223): 
W/jxcore-log( 3223): Process ARCH arm
W/jxcore-log( 3223): 
,I/jxcore-log( 3223): JXcore Cordova bridge is ready!
I/jxcore-log( 3223): 
,W/jxcore-log( 3223): JXcore engine is started
,I/Choreographer( 3223): Skipped 110 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3223): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/ActivityManager(  761): Killing 2712:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10003/pid_2712/cgroup.procs: No such file or directory
,I/jxcore-log( 3223): Toggling radios to true
I/jxcore-log( 3223): 
,D/BluetoothAdapter( 3223): enable(): BT is already enabled..!
,D/WifiService(  761): New client listening to asynchronous messages
,D/WifiService(  761): setWifiEnabled: true pid=3223, uid=10270
E/WifiService(  761): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3223): Radios toggled
I/jxcore-log( 3223): 
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 3223): Got Device Bluetooth address: 34:FC:EF:11:AE:67
I/jxcore-log( 3223): 
I/jxcore-log( 3223): Perf Test app loaded loaded
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): check test folder
I/jxcore-log( 3223): 
I/jxcore-log( 3223): found test : ./testFindPeers.js
I/jxcore-log( 3223): 
I/wpa_supplicant(  981): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  761): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  761): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/native  (  761): do suspend true
,I/jxcore-log( 3223): found test : ./testSendData.js
I/jxcore-log( 3223): 
D/CommandListener(  179): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1573): Read error: ssl=0xb3c42e00: I/O error during system call, Connection timed out
,I/jxcore-log( 3223): found test : ./testSendData2.js
I/jxcore-log( 3223): 
,V/NativeCrypto( 1573): SSL shutdown failed: ssl=0xb3c42e00: I/O error during system call, Broken pipe
,D/ConnectivityService(  761): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  761): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,E/WifiConfigStore(  761): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiStateMachine(  761): Start Disconnecting Watchdog 1
,D/ConnectivityService(  761): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
,I/wpa_supplicant(  981): wlan0: CTRL-EVENT-SCAN-STARTED 
,E/native  (  761): do suspend true
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): ValidatedState{ when=-10ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): DefaultState{ when=-11ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Checking http://clients3.google.com/generate_204 on <unknown ssid>
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,D/ConnectivityService(  761): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler(  899): CM callback handler got msg 524292
,D/Nat464Xlat(  761): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  761): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1594): CM callback handler got msg 524292
D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): EvaluatingState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Disconnected - quitting
D/ConnectivityService(  761): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory( 1244): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WifiNetworkAgent(  761): NetworkAgent: NetworkAgent channel lost
,I/chromium( 3223): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,V/GLSActivity( 1573): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1573): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/NetworkUtils( 1375): OkHttp exception
W/EventLoggerService( 1375): Unable to send logs Error code: 262146
,I/wpa_supplicant(  981): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant(  981): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant(  981): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant(  981): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  761): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  761): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  761): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  761): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  179): Setting iface cfg
,E/WifiStateMachine(  761): Start Dhcp Watchdog 2
,E/native  (  761): do suspend false
,E/WifiStateMachine(  761): scanCount==0 - aborting
,I/dhcpcd  ( 3322): version 5.5.6 starting
,E/dhcpcd  ( 3322): get_duid: Read-only file system
,I/dhcpcd  ( 3322): wlan0: rebinding lease of 192.168.1.114
,D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  761): MasterInitialState.processMessage what=3
,D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  761): MasterInitialState.processMessage what=3
,V/MusicLeanback( 2736): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1594): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1594): onCreate
,D/SystemUpdateService( 1594): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.Environment( 1594): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1594): num queued entries: 0
I/iu.UploadsManager( 1594): num updated entries: 0
I/SystemUpdateService( 1594): active receiver: enabled
I/SystemUpdateService( 1594): showing system update notification
,I/iu.SyncManager( 1594): NEXT; no task
,I/Babel   ( 1895): connection state changed from CONNECTED to DISCONNECTED
,I/ActivityManager(  761): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3352 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/GpsLocationProvider(  761): No APN found to select.
,E/GpsLocationProvider(  761): No APN found to select.
,I/ValidateNoPeople(  761): skipping global notification
,V/SystemUpdateService( 1594): retry (wakeup: false) in 3599945 ms
,D/SystemUpdateService( 1594): onDestroy
,I/dhcpcd  ( 3322): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3322): wlan0: leased 192.168.1.114 for 86400 seconds
,I/GAv4    ( 3352): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3352):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3352):   adb logcat -s GAv4
,W/GAv4    ( 3352): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3352): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3352): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 3352): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3352): Time to load native libraries: 1 ms (timestamps 4804-4805)
I/LibraryLoader( 3352): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3352): Binding Chromium to main looper Looper (main, tid 1) {8064fbd}
,I/LibraryLoader( 3352): Expected native library version number "",actual native library version number ""
,I/chromium( 3352): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3352): Initializing chromium process, singleProcess=true
,W/art     ( 3352): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3352): ApplicationContext is null in ApplicationStatus
,W/chromium( 3352): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3352): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3352): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3352): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,E/native  (  761): do suspend true
,D/ConnectivityService(  761): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,E/WifiStateMachine(  761): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/ConnectivityService(  761): Adding iface wlan0 to network 101
,E/ConnectivityService(  761): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  761): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  761): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  761): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  761): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  761): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  761): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  761): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  761): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  761):    accepting network in place of null
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/CSLegacyTypeTracker(  761): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  761): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::5255:27ff:fef0:fd0b/64,192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  761): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler(  899): CM callback handler got msg 524290
D/ConnectivityManager.CallbackHandler( 1594): CM callback handler got msg 524290
,W/AudioManagerAndroid( 3352): Requires BLUETOOTH permission
,I/NSApplication( 3352): Starting up...
,I/ActivityManager(  761): Killing 2693:com.android.settings/1000 (adj 15): empty #17
,D/WifiService(  761): Client connection lost with reason: 4
,W/libprocessgroup(  761): failed to open /acct/uid_1000/pid_2693/cgroup.procs: No such file or directory
,V/MusicLeanback( 2736): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1594): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1594): onCreate
,D/SystemUpdateService( 1594): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1594): active receiver: enabled
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 22 Dec 2015 00:50:33 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450745433952], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450745433935]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Validated
,D/ConnectivityService(  761): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  761): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  761): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  761): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler(  899): CM callback handler got msg 524290
D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1594): CM callback handler got msg 524290
,D/TelephonyNetworkFactory( 1244): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/iu.Environment( 1594): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1594): num queued entries: 0
I/SystemUpdateService( 1594): showing system update notification
I/iu.UploadsManager( 1594): num updated entries: 0
,I/iu.SyncManager( 1594): NEXT; no task
,I/ValidateNoPeople(  761): skipping global notification
,V/SystemUpdateService( 1594): retry (wakeup: false) in 3599971 ms
,D/SystemUpdateService( 1594): onDestroy
,I/Babel   ( 1895): connection state changed from DISCONNECTED to CONNECTED
,I/art     (  761): Explicit concurrent mark sweep GC freed 40812(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 27MB/41MB, paused 1.033ms total 61.285ms
,D/ConnectivityService(  761): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): setDiscoveryMode: Mode set to WIFI
,I/jxcore-log( 3223): BLE supported!!
I/jxcore-log( 3223): 
,D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  761): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2736): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2736): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1594): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1594): onCreate
,D/SystemUpdateService( 1594): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1594): active receiver: enabled
,I/SystemUpdateService( 1594): showing system update notification
,I/ValidateNoPeople(  761): skipping global notification
,V/SystemUpdateService( 1594): retry (wakeup: false) in 3599984 ms
,D/SystemUpdateService( 1594): onDestroy
,E/GpsLocationProvider(  761): No APN found to select.
,D/Finsky  ( 2607): [255] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2607): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/GLSActivity( 1573): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1573): Vacuum at: now=1450745446030 tag=VacuumService
,I/PhenotypeConfigurator( 1573): Scheduling Phenotype for one-off execution 12175 seconds from now (1450745446298)
,D/GetConfigurationSnapshotOperation( 1573): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1573): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1573): Using platform SSLCertificateSocketFactory
,V/GLSActivity( 1573): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1573): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Keyboard.Facilitator.LanguageModelFlusher( 1096): run()
I/Keyboard.Facilitator( 1096): flushDynamicLanguageModels()
,I/ConfigService( 1573): onCreate
,I/ConfigService( 1573): onDestroy
,I/ClearcutLoggerApiImpl( 1573): disconnect managed GoogleApiClient
,I/jxcore-log( 3223): Connected to the server!
I/jxcore-log( 3223): 
,I/chromium( 3223): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3223): --- start :testFindPeers.js---
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): testFindPeers created [object Object]
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): serverPort is 8876
I/jxcore-log( 3223): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): setDiscoveryMode: Mode set to WIFI
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3223): start: Peer ID: 34:FC:EF:11:AE:67, peer name: LGE-Nexus 5_PT1510
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3223): bind: Binding a new listener
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3223): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3223): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT1510","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3223): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3223): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3223): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3223): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3223): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3223): start: OK
I/io.jxcore.node.ConnectionHelper( 3223): start: Using peer discovery mode: WIFI
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): start: Peer ID: 34:FC:EF:11:AE:67, peer name: LGE-Nexus 5_PT1510
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3223): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT1510","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3223): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3223): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT1510","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3223): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT1510","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3223): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3223): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3223): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3223): start: OK
I/jxcore-log( 3223): StartBroadcasting started ok
I/jxcore-log( 3223): 
I/chromium( 3223): [INFO:CONSOLE(63)] "logCallback --- start :testFindPeers.js---", source: file:///android_asset/www/js/thali_main.js (63)
,I/io.jxcore.node.ConnectionHelper( 3223): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3223): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3223): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3223): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3223): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3223): onDiscoveryManagerStateChanged: RUNNING
,I/wpa_supplicant(  981): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  981): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  981): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3223): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
,D/WifiP2pManager( 3223): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3223): Service request added successfully
,I/wpa_supplicant(  981): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  981): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  981): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  981): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  981): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  981): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3223): onP2pDeviceListChanged: 5 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3223): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3223): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3223): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3223): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
,I/wpa_supplicant(  981): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  981): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3223): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): onP2pDeviceListChanged: Peer 6: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3223): Service discovery started successfully
,I/wpa_supplicant(  981): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3223): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3223): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3223): setState: RESTARTING
,I/wpa_supplicant(  981): P2P-FIND-STOPPED 
,I/wpa_supplicant(  981): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant(  981): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant(  981): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant(  981): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant(  981): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant(  981): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant(  981): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3223): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3223): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3223): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3223): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3223): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3223): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3223): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3223): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3223): Start timer timeout, starting now...
,I/wpa_supplicant(  981): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3223): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3223): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3223): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  981): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  981): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  981): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3223): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3223): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3223): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 3223): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3223): Service request added successfully
,I/wpa_supplicant(  981): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  981): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  981): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3223): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3223): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
,I/wpa_supplicant(  981): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  981): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3223): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3223): Service discovery started successfully
,I/wpa_supplicant(  981): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3223): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3223): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3223): setState: RESTARTING
,I/wpa_supplicant(  981): P2P-FIND-STOPPED 
,I/wpa_supplicant(  981): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
I/wpa_supplicant(  981): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant(  981): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant(  981): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant(  981): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3223): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3223): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3223): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3223): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3223): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3223): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3223): Start timer timeout, starting now...
,I/wpa_supplicant(  981): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3223): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3223): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3223): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  981): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3223): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3223): restart: Restarting...
,D/WifiP2pManager( 3223): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3223): Service request added successfully
,I/wpa_supplicant(  981): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  981): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  981): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  981): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3223): Service discovery started successfully
,I/wpa_supplicant(  981): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3223): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3223): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT3064","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3223): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT3064]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3223): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT3064]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT3064]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT3064], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT3064]
I/io.jxcore.node.ConnectionHelper( 3223): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT3064], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
D/io.jxcore.node.ConnectionHelper( 3223): notifyPeerAvailability: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT3064] is available
,I/jxcore-log( 3223): peerAvailabilityChanged [{"peerIdentifier":"58:3F:54:73:64:C0","peerName":"LGE-LG-D855_PT3064","peerAvailable":true}]
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): Found peer : 58:3F:54:73:64:C0, peerAvailable: true
I/jxcore-log( 3223): 
I/jxcore-log( 3223): weAreDoneNow
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): done, now sending data to server
I/jxcore-log( 3223): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3223): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT2086","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3223): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2086]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3223): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2086]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2086]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2086], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2086]
I/io.jxcore.node.ConnectionHelper( 3223): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2086], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
D/io.jxcore.node.ConnectionHelper( 3223): notifyPeerAvailability: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2086] is available
,I/wpa_supplicant(  981): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  981): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3223): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2086], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2086]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT3064], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT3064]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3223): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3223): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3223): setState: RESTARTING
,I/wpa_supplicant(  981): P2P-FIND-STOPPED 
,I/wpa_supplicant(  981): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant(  981): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant(  981): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3223): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3223): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3223): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3223): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3223): Start timer timeout, starting now...
,I/wpa_supplicant(  981): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3223): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3223): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3223): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/jxcore-log( 3223): teardown
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): testFindPeers stopped
I/jxcore-log( 3223): 
,I/io.jxcore.node.ConnectionHelper( 3223): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3223): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3223): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3223): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3223): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3223): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3223): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3223): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3223): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3223): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3223): stop: Stopping P2P device discovery...
,I/wpa_supplicant(  981): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3223): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3223): release: No more listeners, de-initializing...
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3223): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3223): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): setState: NOT_STARTED
,I/jxcore-log( 3223): StopBroadcasting went ok
I/jxcore-log( 3223): 
,I/chromium( 3223): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
I/io.jxcore.node.ConnectionHelper( 3223): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3223): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3223): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3223): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 3223): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 3223): --- start :testSendData.js---
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":14}bt-address length : 0
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): daya100000
I/jxcore-log( 3223): 
I/jxcore-log( 3223): check server
I/jxcore-log( 3223): 
I/jxcore-log( 3223): serverPort is 47561
I/jxcore-log( 3223): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): setDiscoveryMode: Mode set to WIFI
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3223): start: Peer ID: 34:FC:EF:11:AE:67, peer name: LGE-Nexus 5_PT1510
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3223): bind: Binding a new listener
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3223): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3223): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT1510","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3223): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3223): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3223): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3223): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3223): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3223): start: OK
I/io.jxcore.node.ConnectionHelper( 3223): start: Using peer discovery mode: WIFI
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): start: Peer ID: 34:FC:EF:11:AE:67, peer name: LGE-Nexus 5_PT1510
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3223): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT1510","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3223): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3223): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT1510","ra":"34:FC:EF:11:AE:67"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3223): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT1510","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3223): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3223): start: Starting P2P device discovery...
,I/wpa_supplicant(  981): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): startWifiPeerDiscovery: Wi-Fi Direct OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3223): start: OK
I/jxcore-log( 3223): StartBroadcasting started ok
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): null
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T00:58:45.364Z SendDataTCPServer.js: TCP/IP server is bound to port: 47561
I/jxcore-log( 3223): 
I/chromium( 3223): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
,I/io.jxcore.node.ConnectionHelper( 3223): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3223): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3223): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3223): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3223): setState: RESTARTING
,I/wpa_supplicant(  981): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3223): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3223): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3223): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3223): onDiscoveryManagerStateChanged: RUNNING
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3223): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3223): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3223): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3223): setState: RESTARTING
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3223): Waiting for incoming connections...
,I/wpa_supplicant(  981): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  981): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3223): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3223): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
,D/WifiP2pManager( 3223): Ignored { when=-5ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3223): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3223): Service discovery started successfully
,I/wpa_supplicant(  981): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3223): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3223): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3223): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3223): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  981): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  981): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3223): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3223): restart: Restarting...
,D/WifiP2pManager( 3223): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3223): Service request added successfully
,I/wpa_supplicant(  981): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  981): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3223): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
,I/wpa_supplicant(  981): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  981): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3223): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3223): Service discovery started successfully
,I/wpa_supplicant(  981): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2075): info:x10
,D/        ( 2075): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
E/BluetoothRemoteDevices( 2075): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 2075): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1
E/bt-btif ( 2075): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2075): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2075): Entering PendingCommandState State
,I/ActivityManager(  761): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.BluetoothPairingRequest: pid=3570 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/BluetoothBondStateMachine( 2075): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
,D/BluetoothAdapterProperties( 2075): Failed to remove device: F8:95:C7:87:85:54
,I/BluetoothBondStateMachine( 2075): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
,D/BluetoothManagerService(  761): Message: 20
D/BluetoothManagerService(  761): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2acf48fe:true
,I/ActivityManager(  761): Killing 2552:com.google.android.gm/u0a70 (adj 15): empty #17
,W/bt-btif ( 2075): new conn_srvc id:26, app_id:255
W/bt-btif ( 2075): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 2075): bta_dm_pm_ssr:2, lat:1200
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3223): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3223): Incoming connection initialized (thread ID: 309)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3223): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3223): Entering thread (ID: 309)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3223): onBytesRead: Read 77 bytes successfully (thread ID: 309)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3223): Got valid identity from [F8:95:C7:87:85:54 LGE-LG-D722_PT1947]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3223): onBytesWritten: 77 bytes successfully written (thread ID: 309)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3223): removeThreadFromList: Removing thread with ID 309
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3223): Handshake thread disposed (thread ID: 309)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3223): onIncomingConnectionConnected: [F8:95:C7:87:85:54 LGE-LG-D722_PT1947]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3223): onConnected: [F8:95:C7:87:85:54 LGE-LG-D722_PT1947]
I/io.jxcore.node.ConnectionHelper( 3223): onConnected: Incoming connection to peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1947]
D/io.jxcore.node.ConnectionHelper( 3223): hasConnection: No connection with peer with ID F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 3223): notifyPeerAvailability: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1947] is available
I/jxcore-log( 3223): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:85:54","peerName":"LGE-LG-D722_PT1947","peerAvailable":true}]
I/jxcore-log( 3223): 
I/jxcore-log( 3223): Found peer : LGE-LG-D722_PT1947, Available: true
I/jxcore-log( 3223): 
I/jxcore-log( 3223): startWithNextDevice
I/jxcore-log( 3223): 
I/jxcore-log( 3223): device[1]: F8:95:C7:87:85:54
I/jxcore-log( 3223): 
I/jxcore-log( 3223): 2015-12-22T00:58:59.819Z SendDataConnector.js: Start called with peer F8:95:C7:87:85:54
I/jxcore-log( 3223): 
I/jxcore-log( 3223): 2015-12-22T00:58:59.820Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3223): 
I/jxcore-log( 3223): 2015-12-22T00:58:59.820Z SendDataConnector.js: do connect now
I/jxcore-log( 3223): 
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3223): Exiting thread (ID: 309)
I/io.jxcore.node.ConnectionHelper( 3223): connect: Trying to connect to peer with ID F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 3223): hasConnection: No connection with peer with ID F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3223): connect: [F8:95:C7:87:85:54 LGE-LG-D722_PT1947]
,W/libprocessgroup(  761): failed to open /acct/uid_10070/pid_2552/cgroup.procs: No such file or directory
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3223): connect: Trying to start connecting to G3s-1 in address F8:95:C7:87:85:54
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3223): setInsecureRfcommSocketPort: Using port -1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3223): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3223): onConnecting: G3s-1 F8:95:C7:87:85:54
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3223): connect: Started connecting to G3s-1 in address F8:95:C7:87:85:54
I/io.jxcore.node.ConnectionHelper( 3223): connect: Connection process successfully started (peer ID: F8:95:C7:87:85:54)
,I/io.jxcore.node.ConnectionHelper( 3223): onConnected: Incoming socket thread, for peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1947], created successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3223): Trying to connect to peer with address F8:95:C7:87:85:54 (thread ID: 310)
D/io.jxcore.node.ConnectionHelper( 3223): onConnected: The total number of connections is now 1
,W/BluetoothAdapter( 3223): getBluetoothService() called with no BluetoothManagerCallback
,D/io.jxcore.node.IncomingSocketThread( 3223): Entering thread (ID: 311)
,D/BTIF_SOCK( 2075): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/BluetoothBondStateMachine( 2075): StableState(): Entering Off State
,I/jxcore-log( 3223): 2015-12-22T00:58:59.842Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3223): 
,I/io.jxcore.node.IncomingSocketThread( 3223): Local host address: localhost/127.0.0.1, port: 47561
D/io.jxcore.node.IncomingSocketThread( 3223): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3223): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3223): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3223): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3223): Exiting thread (ID: 311)
D/io.jxcore.node.StreamCopyingThread( 3223): Entering thread (ID: 313, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3223): Entering thread (ID: 312, name: Sender)
,W/bt-sdp  ( 2075): process_service_search_attr_rsp
,W/bt-btif ( 2075): new conn_srvc id:26, app_id:1
,W/bt-btif ( 2075): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 2075): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2075): bta_dm_pm_ssr:2, lat:1200
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3223): onSocketConnected: [F8:95:C7:87:85:54 LGE-LG-D722_PT1947]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3223): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 310)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3223): onBytesWritten: 77 bytes successfully written (thread ID: 314)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3223): Outgoing connection initialized (*handshake* thread ID: 314)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3223): Exiting thread (thread ID: 310)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3223): Entering thread (ID: 314)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3223): onBytesRead: Read 77 bytes successfully (thread ID: 314)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3223): Handshake succeeded with [F8:95:C7:87:85:54 LGE-LG-D722_PT1947]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3223): onHandshakeSucceeded: [F8:95:C7:87:85:54 LGE-LG-D722_PT1947]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3223): Exiting thread (ID: 314)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3223): onConnected: [F8:95:C7:87:85:54 LGE-LG-D722_PT1947]
I/io.jxcore.node.ConnectionHelper( 3223): onConnected: Outgoing connection to peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1947]
D/io.jxcore.node.ConnectionHelper( 3223): hasConnection: We have an incoming connection with peer with ID F8:95:C7:87:85:54
W/io.jxcore.node.ConnectionHelper( 3223): onConnected: Already connected with peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1947], continuing anyway...
W/io.jxcore.node.ConnectionHelper( 3223): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1947] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 3223): onConnected: Outgoing socket thread, for peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1947], created successfully
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3223): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 3223): onConnected: The total number of connections is now 2
D/io.jxcore.node.OutgoingSocketThread( 3223): Entering thread (ID: 315)
,D/io.jxcore.node.OutgoingSocketThread( 3223): Server socket local port: 56932
I/io.jxcore.node.OutgoingSocketThread( 3223): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3223): onListeningForIncomingConnections: Outgoing connection is using port 56932 (peer ID: F8:95:C7:87:85:54)
,I/jxcore-log( 3223): 2015-12-22T00:59:00.254Z SendDataConnector.js: CLIENT connected to 56932, error: null
I/jxcore-log( 3223): 
I/jxcore-log( 3223): 2015-12-22T00:59:00.254Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T00:59:00.258Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3223): 
,I/io.jxcore.node.OutgoingSocketThread( 3223): Incoming data from address: /127.0.0.1, port: 56932
,D/io.jxcore.node.OutgoingSocketThread( 3223): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3223): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 3223): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.OutgoingSocketThread( 3223): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3223): Exiting thread (ID: 315)
D/io.jxcore.node.StreamCopyingThread( 3223): Entering thread (ID: 316, name: Sender)
D/io.jxcore.node.StreamCopyingThread( 3223): Entering thread (ID: 317, name: Receiver)
,I/jxcore-log( 3223): 2015-12-22T00:59:00.666Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T00:59:00.686Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T00:59:00.699Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T00:59:00.706Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T00:59:00.723Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T00:59:00.729Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T00:59:00.761Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T00:59:00.819Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T00:59:00.823Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T00:59:00.836Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T00:59:00.839Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T00:59:00.879Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T00:59:00.883Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T00:59:00.915Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T00:59:01.068Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T00:59:01.113Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T00:59:01.128Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T00:59:01.148Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T00:59:01.155Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T00:59:01.165Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T00:59:01.167Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3223): 
I/jxcore-log( 3223): 2015-12-22T00:59:01.167Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T00:59:01.180Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T00:59:01.211Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T00:59:01.214Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3223): 
I/jxcore-log( 3223): 2015-12-22T00:59:01.215Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3223): 
I/jxcore-log( 3223): 2015-12-22T00:59:01.215Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3223): 
I/jxcore-log( 3223): oneRoundDownNow
I/jxcore-log( 3223): 
I/jxcore-log( 3223): 2015-12-22T00:59:01.215Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3223): 
I/jxcore-log( 3223): 2015-12-22T00:59:01.215Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3223): 
D/io.jxcore.node.ConnectionHelper( 3223): disconnectOutgoingConnection: Trying to close connection to peer with ID F8:95:C7:87:85:54
I/io.jxcore.node.ConnectionHelper( 3223): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: F8:95:C7:87:85:54
I/io.jxcore.node.OutgoingSocketThread( 3223): close
D/io.jxcore.node.OutgoingSocketThread( 3223): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3223): doStop: Thread ID: 317
D/io.jxcore.node.OutgoingSocketThread( 3223): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3223): doStop: Thread ID: 316
,D/io.jxcore.node.OutgoingSocketThread( 3223): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 3223): closeLocalSocketAndStreams: Closing the local input stream...
W/io.jxcore.node.StreamCopyingThread( 3223): Either failed to read from the output stream or write to the input stream (thread ID: 316, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3223): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3223): onDisconnected: Outgoing connection, peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1947] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 3223): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 3223): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3223): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3223): Either failed to read from the output stream or write to the input stream (thread ID: 317, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 3223): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3223): onDisconnected: Outgoing connection, peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1947] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3223): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3223): disconnectOutgoingConnection: Successfully disconnected (peer ID: F8:95:C7:87:85:54
,E/io.jxcore.node.ConnectionHelper( 3223): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 3223): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3223): Exiting thread (ID: 316, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 3223): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 3223): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3223): Exiting thread (ID: 317, name: Receiver)
,I/jxcore-log( 3223): 2015-12-22T00:59:01.224Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3223): 
I/jxcore-log( 3223): ---- round done--------
I/jxcore-log( 3223): 
I/jxcore-log( 3223): startWithNextDevice
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T00:59:01.231Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T00:59:01.251Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T00:59:01.495Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3223): 
,W/bt-btif ( 2075): bta_jv_rfc_port_to_cb(port_handle:0xa):jv handle:0x0 not FOUND
,I/jxcore-log( 3223): 2015-12-22T00:59:01.524Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T00:59:01.546Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T00:59:01.584Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T00:59:01.600Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3223): 
,W/bt-btif ( 2075): invalid rfc slot id: 5
,W/io.jxcore.node.StreamCopyingThread( 3223): Either failed to read from the output stream or write to the input stream (thread ID: 313, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 3223): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3223): onDisconnected: Incoming connection, peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1947] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3223): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 311
D/io.jxcore.node.OutgoingSocketThread( 3223): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3223): doStop: Thread ID: 313
D/io.jxcore.node.OutgoingSocketThread( 3223): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3223): doStop: Thread ID: 312
D/io.jxcore.node.OutgoingSocketThread( 3223): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 3223): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3223): Either failed to read from the output stream or write to the input stream (thread ID: 312, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3223): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3223): onDisconnected: Incoming connection, peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1947] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 3223): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 3223): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3223): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3223): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.ConnectionHelper( 3223): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3223): Exiting thread (ID: 312, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 3223): Exiting thread (ID: 313, name: Receiver)
,I/jxcore-log( 3223): 2015-12-22T00:59:01.696Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3223): 
,W/bt-rfcomm( 2075): rfc_find_lcid_mcb LCID reused LCID:0x41 current:0x0
W/bt-rfcomm( 2075): RFCOMM_DisconnectInd LCID:0x41
,D/btif_config_util( 2075): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2075): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2075): onReceive
,D/BluetoothManagerService(  761): Message: 20
D/BluetoothManagerService(  761): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@185d2ac:true
,I/BTConnectionReceiver( 1375): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1375): Bluetooth Device Name: G3s-1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3223): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3223): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3223): setState: RESTARTING
,I/wpa_supplicant(  981): P2P-FIND-STOPPED 
,I/wpa_supplicant(  981): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant(  981): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant(  981): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant(  981): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3223): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3223): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3223): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3223): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3223): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3223): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3223): P2P device discovery started successfully
,I/wpa_supplicant(  981): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3223): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3223): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  981): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  981): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  981): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3223): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3223): restart: Restarting...
,D/WifiP2pManager( 3223): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3223): Service request added successfully
,I/wpa_supplicant(  981): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  981): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  981): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3223): Service discovery started successfully
,I/wpa_supplicant(  981): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3223): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
,W/bt-btif ( 2075): info:x10
,D/        ( 2075): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,E/BluetoothRemoteDevices( 2075): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 2075): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
E/bt-btif ( 2075): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2075): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2075): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2075): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,D/BluetoothAdapterProperties( 2075): Failed to remove device: F8:95:C7:87:3C:51
,I/BluetoothBondStateMachine( 2075): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2075): StableState(): Entering Off State
,W/bt-btif ( 2075): new conn_srvc id:26, app_id:255
W/bt-btif ( 2075): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2075): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3223): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3223): Incoming connection initialized (thread ID: 318)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3223): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3223): Entering thread (ID: 318)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3223): onBytesRead: Read 77 bytes successfully (thread ID: 318)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3223): Got valid identity from [F8:95:C7:87:3C:51 LGE-LG-H815_PT8123]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3223): onBytesWritten: 77 bytes successfully written (thread ID: 318)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3223): removeThreadFromList: Removing thread with ID 318
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3223): Handshake thread disposed (thread ID: 318)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3223): onIncomingConnectionConnected: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8123]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3223): Exiting thread (ID: 318)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3223): onConnected: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8123]
I/io.jxcore.node.ConnectionHelper( 3223): onConnected: Incoming connection to peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT8123]
D/io.jxcore.node.ConnectionHelper( 3223): hasConnection: No connection with peer with ID F8:95:C7:87:3C:51
D/io.jxcore.node.ConnectionHelper( 3223): notifyPeerAvailability: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT8123] is available
I/jxcore-log( 3223): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:3C:51","peerName":"LGE-LG-H815_PT8123","peerAvailable":true}]
I/jxcore-log( 3223): 
I/jxcore-log( 3223): Found peer : LGE-LG-H815_PT8123, Available: true
I/jxcore-log( 3223): 
I/jxcore-log( 3223): startWithNextDevice
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): device[2]: F8:95:C7:87:3C:51
I/jxcore-log( 3223): 
I/jxcore-log( 3223): 2015-12-22T00:59:51.727Z SendDataConnector.js: Start called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3223): 
I/jxcore-log( 3223): 2015-12-22T00:59:51.727Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3223): 
I/jxcore-log( 3223): 2015-12-22T00:59:51.727Z SendDataConnector.js: do connect now
I/jxcore-log( 3223): 
,I/io.jxcore.node.ConnectionHelper( 3223): connect: Trying to connect to peer with ID F8:95:C7:87:3C:51
D/io.jxcore.node.ConnectionHelper( 3223): hasConnection: No connection with peer with ID F8:95:C7:87:3C:51
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3223): connect: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8123]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3223): connect: Trying to start connecting to G4-1 in address F8:95:C7:87:3C:51
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3223): setInsecureRfcommSocketPort: Using port -1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3223): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3223): onConnecting: G4-1 F8:95:C7:87:3C:51
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3223): connect: Started connecting to G4-1 in address F8:95:C7:87:3C:51
I/io.jxcore.node.ConnectionHelper( 3223): connect: Connection process successfully started (peer ID: F8:95:C7:87:3C:51)
I/io.jxcore.node.ConnectionHelper( 3223): onConnected: Incoming socket thread, for peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT8123], created successfully
D/io.jxcore.node.ConnectionHelper( 3223): onConnected: The total number of connections is now 1
,D/io.jxcore.node.IncomingSocketThread( 3223): Entering thread (ID: 320)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3223): Trying to connect to peer with address F8:95:C7:87:3C:51 (thread ID: 319)
W/BluetoothAdapter( 3223): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2075): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/io.jxcore.node.IncomingSocketThread( 3223): Local host address: localhost/127.0.0.1, port: 47561
D/io.jxcore.node.IncomingSocketThread( 3223): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3223): setBufferSize: Setting buffer size to 8192 bytes
,I/jxcore-log( 3223): 2015-12-22T00:59:51.737Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3223): 
,I/io.jxcore.node.StreamCopyingThread( 3223): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3223): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3223): Exiting thread (ID: 320)
,D/io.jxcore.node.StreamCopyingThread( 3223): Entering thread (ID: 322, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3223): Entering thread (ID: 321, name: Sender)
,W/bt-sdp  ( 2075): process_service_search_attr_rsp
,W/bt-btif ( 2075): new conn_srvc id:26, app_id:1
W/bt-btif ( 2075): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2075): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2075): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3223): onSocketConnected: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8123]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3223): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 319)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3223): onBytesWritten: 77 bytes successfully written (thread ID: 323)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3223): Outgoing connection initialized (*handshake* thread ID: 323)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3223): Exiting thread (thread ID: 319)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3223): Entering thread (ID: 323)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3223): onBytesRead: Read 77 bytes successfully (thread ID: 323)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3223): Handshake succeeded with [F8:95:C7:87:3C:51 LGE-LG-H815_PT8123]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3223): onHandshakeSucceeded: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8123]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3223): Exiting thread (ID: 323)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3223): onConnected: [F8:95:C7:87:3C:51 LGE-LG-H815_PT8123]
I/io.jxcore.node.ConnectionHelper( 3223): onConnected: Outgoing connection to peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT8123]
D/io.jxcore.node.ConnectionHelper( 3223): hasConnection: We have an incoming connection with peer with ID F8:95:C7:87:3C:51
W/io.jxcore.node.ConnectionHelper( 3223): onConnected: Already connected with peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT8123], continuing anyway...
W/io.jxcore.node.ConnectionHelper( 3223): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT8123] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 3223): onConnected: Outgoing socket thread, for peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT8123], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3223): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 3223): onConnected: The total number of connections is now 2
,D/io.jxcore.node.OutgoingSocketThread( 3223): Entering thread (ID: 324)
,D/io.jxcore.node.OutgoingSocketThread( 3223): Server socket local port: 55901
I/io.jxcore.node.OutgoingSocketThread( 3223): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3223): onListeningForIncomingConnections: Outgoing connection is using port 55901 (peer ID: F8:95:C7:87:3C:51)
I/jxcore-log( 3223): 2015-12-22T00:59:52.108Z SendDataConnector.js: CLIENT connected to 55901, error: null
I/jxcore-log( 3223): 
I/jxcore-log( 3223): 2015-12-22T00:59:52.108Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T00:59:52.119Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3223): 
,I/io.jxcore.node.OutgoingSocketThread( 3223): Incoming data from address: /127.0.0.1, port: 55901
D/io.jxcore.node.OutgoingSocketThread( 3223): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3223): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3223): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3223): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3223): Exiting thread (ID: 324)
,D/io.jxcore.node.StreamCopyingThread( 3223): Entering thread (ID: 325, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 3223): Entering thread (ID: 326, name: Receiver)
,I/jxcore-log( 3223): 2015-12-22T00:59:52.561Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T00:59:52.569Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T00:59:52.601Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T00:59:52.605Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T00:59:52.635Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T00:59:52.637Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T00:59:52.678Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T00:59:52.682Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T00:59:52.733Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T00:59:52.752Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T00:59:52.795Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T00:59:52.826Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T00:59:52.829Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T00:59:52.831Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T00:59:52.841Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3223): 
,W/bt-btif ( 2075): invalid rfc slot id: 6
,W/io.jxcore.node.StreamCopyingThread( 3223): Either failed to read from the output stream or write to the input stream (thread ID: 322, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 3223): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3223): onDisconnected: Incoming connection, peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT8123] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3223): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 320
D/io.jxcore.node.OutgoingSocketThread( 3223): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3223): doStop: Thread ID: 322
D/io.jxcore.node.OutgoingSocketThread( 3223): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3223): doStop: Thread ID: 321
D/io.jxcore.node.OutgoingSocketThread( 3223): closeLocalSocketAndStreams: Closing...
,D/io.jxcore.node.OutgoingSocketThread( 3223): closeLocalSocketAndStreams: Closing the local input stream...
D/io.jxcore.node.OutgoingSocketThread( 3223): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 3223): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3223): closeBluetoothSocketAndStreams
W/io.jxcore.node.StreamCopyingThread( 3223): Either failed to read from the output stream or write to the input stream (thread ID: 321, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3223): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3223): onDisconnected: Incoming connection, peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT8123] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.ConnectionHelper( 3223): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3223): Exiting thread (ID: 322, name: Receiver)
,D/io.jxcore.node.ConnectionHelper( 3223): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3223): Exiting thread (ID: 321, name: Sender)
I/jxcore-log( 3223): 2015-12-22T00:59:52.860Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T00:59:53.245Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3223): 
I/jxcore-log( 3223): 2015-12-22T00:59:53.246Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3223): 
I/jxcore-log( 3223): oneRoundDownNow
I/jxcore-log( 3223): 
I/jxcore-log( 3223): 2015-12-22T00:59:53.248Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3223): 
I/jxcore-log( 3223): 2015-12-22T00:59:53.248Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3223): 
,D/io.jxcore.node.ConnectionHelper( 3223): disconnectOutgoingConnection: Trying to close connection to peer with ID F8:95:C7:87:3C:51
I/io.jxcore.node.ConnectionHelper( 3223): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: F8:95:C7:87:3C:51
I/io.jxcore.node.OutgoingSocketThread( 3223): close
D/io.jxcore.node.OutgoingSocketThread( 3223): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3223): doStop: Thread ID: 326
D/io.jxcore.node.OutgoingSocketThread( 3223): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3223): doStop: Thread ID: 325
D/io.jxcore.node.OutgoingSocketThread( 3223): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 3223): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3223): Either failed to read from the output stream or write to the input stream (thread ID: 325, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3223): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3223): onDisconnected: Outgoing connection, peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT8123] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 3223): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 3223): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3223): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3223): Either failed to read from the output stream or write to the input stream (thread ID: 326, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 3223): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3223): onDisconnected: Outgoing connection, peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT8123] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3223): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3223): disconnectOutgoingConnection: Successfully disconnected (peer ID: F8:95:C7:87:3C:51
,E/io.jxcore.node.ConnectionHelper( 3223): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:95:C7:87:3C:51
,D/io.jxcore.node.ConnectionHelper( 3223): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,E/io.jxcore.node.ConnectionHelper( 3223): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:95:C7:87:3C:51
D/io.jxcore.node.ConnectionHelper( 3223): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3223): Exiting thread (ID: 326, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3223): Exiting thread (ID: 325, name: Sender)
,I/jxcore-log( 3223): 2015-12-22T00:59:53.286Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 3223): 
I/jxcore-log( 3223): ---- round done--------
I/jxcore-log( 3223): 
I/jxcore-log( 3223): startWithNextDevice
I/jxcore-log( 3223): 
,W/bt-btif ( 2075): bta_jv_rfc_port_to_cb(port_handle:0xc):jv handle:0x0 not FOUND
,D/btif_config_util( 2075): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2075): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2075): onReceive
,I/BTConnectionReceiver( 1375): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1375): Bluetooth Device Name: G4-1
,W/bt-btif ( 2075): info:x10
,D/        ( 2075): remote version info [58:3f:54:73:64:c0]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 2075): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 2075): bondStateChangeCallback: Status: 0 Address: 58:3F:54:73:64:C0 newState: 1
E/bt-btif ( 2075): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2075): Bond State Change Intent:58:3F:54:73:64:C0 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2075): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2075): bondStateChangeCallback: Status: 0 Address: 58:3F:54:73:64:C0 newState: 0
,D/BluetoothAdapterProperties( 2075): Failed to remove device: 58:3F:54:73:64:C0
,I/BluetoothBondStateMachine( 2075): Bond State Change Intent:58:3F:54:73:64:C0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2075): StableState(): Entering Off State
,W/bt-btif ( 2075): new conn_srvc id:26, app_id:255
W/bt-btif ( 2075): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2075): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3223): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3223): Incoming connection initialized (thread ID: 327)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3223): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3223): Entering thread (ID: 327)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3223): onBytesRead: Read 77 bytes successfully (thread ID: 327)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3223): Got valid identity from [58:3F:54:73:64:C0 LGE-LG-D855_PT3064]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3223): onBytesWritten: 77 bytes successfully written (thread ID: 327)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3223): removeThreadFromList: Removing thread with ID 327
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3223): Handshake thread disposed (thread ID: 327)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3223): onIncomingConnectionConnected: [58:3F:54:73:64:C0 LGE-LG-D855_PT3064]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3223): onConnected: [58:3F:54:73:64:C0 LGE-LG-D855_PT3064]
I/io.jxcore.node.ConnectionHelper( 3223): onConnected: Incoming connection to peer [58:3F:54:73:64:C0 LGE-LG-D855_PT3064]
D/io.jxcore.node.ConnectionHelper( 3223): hasConnection: No connection with peer with ID 58:3F:54:73:64:C0
W/io.jxcore.node.ConnectionHelper( 3223): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT3064] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 3223): onConnected: Incoming socket thread, for peer [58:3F:54:73:64:C0 LGE-LG-D855_PT3064], created successfully
D/io.jxcore.node.ConnectionHelper( 3223): onConnected: The total number of connections is now 1
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3223): Exiting thread (ID: 327)
,D/io.jxcore.node.IncomingSocketThread( 3223): Entering thread (ID: 328)
,I/io.jxcore.node.IncomingSocketThread( 3223): Local host address: localhost/127.0.0.1, port: 47561
D/io.jxcore.node.IncomingSocketThread( 3223): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3223): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3223): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3223): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3223): Exiting thread (ID: 328)
,I/jxcore-log( 3223): 2015-12-22T01:00:05.657Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3223): 
,D/io.jxcore.node.StreamCopyingThread( 3223): Entering thread (ID: 330, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3223): Entering thread (ID: 329, name: Sender)
,I/jxcore-log( 3223): 2015-12-22T01:00:06.660Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T01:00:06.671Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T01:00:06.677Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T01:00:06.688Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T01:00:06.723Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T01:00:06.996Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T01:00:07.035Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T01:00:07.050Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T01:00:07.084Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T01:00:07.123Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T01:00:07.136Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T01:00:07.164Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T01:00:07.179Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T01:00:07.212Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T01:00:07.239Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T01:00:07.273Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T01:00:07.283Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T01:00:07.312Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3223): 
,W/bt-btif ( 2075): invalid rfc slot id: 8
,W/io.jxcore.node.StreamCopyingThread( 3223): Either failed to read from the output stream or write to the input stream (thread ID: 330, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.IncomingSocketThread( 3223): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3223): onDisconnected: Incoming connection, peer [58:3F:54:73:64:C0 LGE-LG-D855_PT3064] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3223): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 328
D/io.jxcore.node.IncomingSocketThread( 3223): close: Stopping receiving thread...
,I/io.jxcore.node.StreamCopyingThread( 3223): doStop: Thread ID: 330
D/io.jxcore.node.IncomingSocketThread( 3223): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3223): doStop: Thread ID: 329
D/io.jxcore.node.IncomingSocketThread( 3223): closeLocalSocketAndStreams: Closing...
,D/io.jxcore.node.IncomingSocketThread( 3223): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3223): Either failed to read from the output stream or write to the input stream (thread ID: 329, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3223): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3223): onDisconnected: Incoming connection, peer [58:3F:54:73:64:C0 LGE-LG-D855_PT3064] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.IncomingSocketThread( 3223): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 3223): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3223): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3223): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.ConnectionHelper( 3223): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3223): Exiting thread (ID: 329, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 3223): Exiting thread (ID: 330, name: Receiver)
,W/bt-rfcomm( 2075): rfc_find_lcid_mcb LCID reused LCID:0x47 current:0x0
,W/bt-rfcomm( 2075): RFCOMM_DisconnectInd LCID:0x47
,I/jxcore-log( 3223): 2015-12-22T01:00:07.431Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3223): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3223): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3223): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3223): setState: RESTARTING
,I/wpa_supplicant(  981): P2P-FIND-STOPPED 
,I/wpa_supplicant(  981): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant(  981): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3223): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3223): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3223): onP2pDeviceListChanged: 0 device(s) discovered
,D/btif_config_util( 2075): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2075): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2075): onReceive
,I/BTConnectionReceiver( 1375): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1375): Bluetooth Device Name: G3-1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3223): Start timer timeout, starting now...
,I/wpa_supplicant(  981): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3223): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3223): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3223): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  981): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  981): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3223): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3223): restart: Restarting...
,D/WifiP2pManager( 3223): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3223): Service request added successfully
,I/wpa_supplicant(  981): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  981): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3223): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
,I/wpa_supplicant(  981): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  981): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3223): Service discovery started successfully
,W/bt-btif ( 2075): info:x10
,D/        ( 2075): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 2075): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 2075): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 1
E/bt-btif ( 2075): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2075): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2075): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2075): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 0
,D/BluetoothAdapterProperties( 2075): Failed to remove device: 44:80:EB:7B:5A:05
,I/BluetoothBondStateMachine( 2075): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2075): StableState(): Entering Off State
,W/bt-btif ( 2075): new conn_srvc id:26, app_id:255
W/bt-btif ( 2075): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2075): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3223): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3223): Incoming connection initialized (thread ID: 331)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3223): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3223): Entering thread (ID: 331)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3223): onBytesRead: Read 81 bytes successfully (thread ID: 331)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3223): Got valid identity from [44:80:EB:7B:5A:05 motorola-XT1072_PT3784]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3223): onBytesWritten: 77 bytes successfully written (thread ID: 331)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3223): removeThreadFromList: Removing thread with ID 331
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3223): Handshake thread disposed (thread ID: 331)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3223): onIncomingConnectionConnected: [44:80:EB:7B:5A:05 motorola-XT1072_PT3784]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3223): Exiting thread (ID: 331)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3223): onConnected: [44:80:EB:7B:5A:05 motorola-XT1072_PT3784]
I/io.jxcore.node.ConnectionHelper( 3223): onConnected: Incoming connection to peer [44:80:EB:7B:5A:05 motorola-XT1072_PT3784]
D/io.jxcore.node.ConnectionHelper( 3223): hasConnection: No connection with peer with ID 44:80:EB:7B:5A:05
D/io.jxcore.node.ConnectionHelper( 3223): notifyPeerAvailability: Peer [44:80:EB:7B:5A:05 motorola-XT1072_PT3784] is available
I/jxcore-log( 3223): peerAvailabilityChanged [{"peerIdentifier":"44:80:EB:7B:5A:05","peerName":"motorola-XT1072_PT3784","peerAvailable":true}]
I/jxcore-log( 3223): 
I/jxcore-log( 3223): Found peer : motorola-XT1072_PT3784, Available: true
I/jxcore-log( 3223): 
I/jxcore-log( 3223): startWithNextDevice
I/jxcore-log( 3223): 
I/jxcore-log( 3223): device[3]: 44:80:EB:7B:5A:05
I/jxcore-log( 3223): 
I/jxcore-log( 3223): 2015-12-22T01:00:19.473Z SendDataConnector.js: Start called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3223): 
I/jxcore-log( 3223): 2015-12-22T01:00:19.473Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3223): 
I/jxcore-log( 3223): 2015-12-22T01:00:19.474Z SendDataConnector.js: do connect now
I/jxcore-log( 3223): 
I/io.jxcore.node.ConnectionHelper( 3223): connect: Trying to connect to peer with ID 44:80:EB:7B:5A:05
D/io.jxcore.node.ConnectionHelper( 3223): hasConnection: No connection with peer with ID 44:80:EB:7B:5A:05
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3223): connect: [44:80:EB:7B:5A:05 motorola-XT1072_PT3784]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3223): connect: Trying to start connecting to XT1072 in address 44:80:EB:7B:5A:05
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3223): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3223): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3223): onConnecting: XT1072 44:80:EB:7B:5A:05
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3223): connect: Started connecting to XT1072 in address 44:80:EB:7B:5A:05
I/io.jxcore.node.ConnectionHelper( 3223): connect: Connection process successfully started (peer ID: 44:80:EB:7B:5A:05)
I/io.jxcore.node.ConnectionHelper( 3223): onConnected: Incoming socket thread, for peer [44:80:EB:7B:5A:05 motorola-XT1072_PT3784], created successfully
D/io.jxcore.node.ConnectionHelper( 3223): onConnected: The total number of connections is now 1
,D/io.jxcore.node.IncomingSocketThread( 3223): Entering thread (ID: 333)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3223): Trying to connect to peer with address 44:80:EB:7B:5A:05 (thread ID: 332)
W/BluetoothAdapter( 3223): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2075): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/jxcore-log( 3223): 2015-12-22T01:00:19.482Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3223): 
,I/io.jxcore.node.IncomingSocketThread( 3223): Local host address: localhost/127.0.0.1, port: 47561
D/io.jxcore.node.IncomingSocketThread( 3223): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3223): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 3223): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3223): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3223): Exiting thread (ID: 333)
,D/io.jxcore.node.StreamCopyingThread( 3223): Entering thread (ID: 335, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3223): Entering thread (ID: 334, name: Sender)
,W/bt-sdp  ( 2075): process_service_search_attr_rsp
,W/bt-btif ( 2075): new conn_srvc id:26, app_id:1
W/bt-btif ( 2075): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2075): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2075): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3223): onSocketConnected: [44:80:EB:7B:5A:05 motorola-XT1072_PT3784]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3223): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 332)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3223): onBytesWritten: 77 bytes successfully written (thread ID: 336)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3223): Outgoing connection initialized (*handshake* thread ID: 336)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3223): Exiting thread (thread ID: 332)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3223): Entering thread (ID: 336)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3223): onBytesRead: Read 81 bytes successfully (thread ID: 336)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3223): Handshake succeeded with [44:80:EB:7B:5A:05 motorola-XT1072_PT3784]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3223): onHandshakeSucceeded: [44:80:EB:7B:5A:05 motorola-XT1072_PT3784]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3223): Exiting thread (ID: 336)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3223): onConnected: [44:80:EB:7B:5A:05 motorola-XT1072_PT3784]
I/io.jxcore.node.ConnectionHelper( 3223): onConnected: Outgoing connection to peer [44:80:EB:7B:5A:05 motorola-XT1072_PT3784]
D/io.jxcore.node.ConnectionHelper( 3223): hasConnection: We have an incoming connection with peer with ID 44:80:EB:7B:5A:05
W/io.jxcore.node.ConnectionHelper( 3223): onConnected: Already connected with peer [44:80:EB:7B:5A:05 motorola-XT1072_PT3784], continuing anyway...
W/io.jxcore.node.ConnectionHelper( 3223): modifyListOfDiscoveredPeers: Peer [44:80:EB:7B:5A:05 motorola-XT1072_PT3784] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 3223): onConnected: Outgoing socket thread, for peer [44:80:EB:7B:5A:05 motorola-XT1072_PT3784], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3223): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 3223): onConnected: The total number of connections is now 2
,D/io.jxcore.node.OutgoingSocketThread( 3223): Entering thread (ID: 337)
D/io.jxcore.node.OutgoingSocketThread( 3223): Server socket local port: 46199
I/io.jxcore.node.OutgoingSocketThread( 3223): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3223): onListeningForIncomingConnections: Outgoing connection is using port 46199 (peer ID: 44:80:EB:7B:5A:05)
I/jxcore-log( 3223): 2015-12-22T01:00:19.826Z SendDataConnector.js: CLIENT connected to 46199, error: null
I/jxcore-log( 3223): 
I/jxcore-log( 3223): 2015-12-22T01:00:19.826Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T01:00:19.828Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3223): 
,I/io.jxcore.node.OutgoingSocketThread( 3223): Incoming data from address: /127.0.0.1, port: 46199
D/io.jxcore.node.OutgoingSocketThread( 3223): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3223): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3223): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3223): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3223): Exiting thread (ID: 337)
,D/io.jxcore.node.StreamCopyingThread( 3223): Entering thread (ID: 339, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3223): Entering thread (ID: 338, name: Sender)
,I/jxcore-log( 3223): 2015-12-22T01:00:20.369Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T01:00:20.379Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T01:00:20.388Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T01:00:20.394Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T01:00:20.398Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T01:00:20.402Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T01:00:20.406Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3223): 
,D/        ( 2075): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23716
,I/jxcore-log( 3223): 2015-12-22T01:00:20.418Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T01:00:20.442Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T01:00:20.447Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T01:00:20.451Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T01:00:20.454Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T01:00:20.481Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T01:00:20.504Z SendDataTCPServer.js: TCP/IP server has received 32768 bytes of data
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T01:00:20.509Z SendDataTCPServer.js: TCP/IP server has received 34748 bytes of data
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T01:00:20.515Z SendDataTCPServer.js: TCP/IP server has received 36728 bytes of data
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T01:00:20.522Z SendDataTCPServer.js: TCP/IP server has received 38708 bytes of data
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T01:00:20.540Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T01:00:20.559Z SendDataTCPServer.js: TCP/IP server has received 44648 bytes of data
I/jxcore-log( 3223): 
,D/        ( 2075): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:13816
,I/jxcore-log( 3223): 2015-12-22T01:00:20.574Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T01:00:20.594Z SendDataTCPServer.js: TCP/IP server has received 52568 bytes of data
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T01:00:20.606Z SendDataTCPServer.js: TCP/IP server has received 54548 bytes of data
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T01:00:20.615Z SendDataTCPServer.js: TCP/IP server has received 56528 bytes of data
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T01:00:20.626Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T01:00:20.644Z SendDataTCPServer.js: TCP/IP server has received 62468 bytes of data
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T01:00:20.673Z SendDataTCPServer.js: TCP/IP server has received 64448 bytes of data
I/jxcore-log( 3223): 
,D/        ( 2075): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:3916
,I/jxcore-log( 3223): 2015-12-22T01:00:20.709Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T01:00:20.717Z SendDataTCPServer.js: TCP/IP server has received 80288 bytes of data
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T01:00:20.757Z SendDataTCPServer.js: TCP/IP server has received 90188 bytes of data
I/jxcore-log( 3223): 
I/jxcore-log( 3223): 2015-12-22T01:00:20.758Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T01:00:20.760Z SendDataTCPServer.js: TCP/IP server has received 94148 bytes of data
I/jxcore-log( 3223): 
I/jxcore-log( 3223): 2015-12-22T01:00:20.760Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T01:00:20.781Z SendDataTCPServer.js: TCP/IP server has received 96128 bytes of data
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T01:00:20.820Z SendDataTCPServer.js: TCP/IP server has received 98108 bytes of data
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T01:00:20.824Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T01:00:20.827Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T01:00:20.867Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3223): 
,W/io.jxcore.node.StreamCopyingThread( 3223): Either failed to read from the output stream or write to the input stream (thread ID: 335, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 3223): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3223): onDisconnected: Incoming connection, peer [44:80:EB:7B:5A:05 motorola-XT1072_PT3784] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3223): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 333
D/io.jxcore.node.OutgoingSocketThread( 3223): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3223): doStop: Thread ID: 335
D/io.jxcore.node.OutgoingSocketThread( 3223): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3223): doStop: Thread ID: 334
D/io.jxcore.node.OutgoingSocketThread( 3223): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 3223): closeLocalSocketAndStreams: Closing the local input stream...
D/io.jxcore.node.OutgoingSocketThread( 3223): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 3223): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3223): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3223): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3223): Exiting thread (ID: 335, name: Receiver)
,W/io.jxcore.node.StreamCopyingThread( 3223): Either failed to read from the output stream or write to the input stream (thread ID: 334, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3223): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3223): onDisconnected: Incoming connection, peer [44:80:EB:7B:5A:05 motorola-XT1072_PT3784] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.ConnectionHelper( 3223): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3223): Exiting thread (ID: 334, name: Sender)
W/bt-btif ( 2075): invalid rfc slot id: 10
I/jxcore-log( 3223): 2015-12-22T01:00:20.894Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3223): 
I/wpa_supplicant(  981): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3223): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
I/jxcore-log( 3223): 2015-12-22T01:00:20.906Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3223): 
I/jxcore-log( 3223): 2015-12-22T01:00:20.907Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3223): 
I/jxcore-log( 3223): oneRoundDownNow
I/jxcore-log( 3223): 
I/jxcore-log( 3223): 2015-12-22T01:00:20.908Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3223): 
I/jxcore-log( 3223): 2015-12-22T01:00:20.908Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3223): 
D/io.jxcore.node.ConnectionHelper( 3223): disconnectOutgoingConnection: Trying to close connection to peer with ID 44:80:EB:7B:5A:05
I/io.jxcore.node.ConnectionHelper( 3223): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 44:80:EB:7B:5A:05
I/io.jxcore.node.OutgoingSocketThread( 3223): close
D/io.jxcore.node.OutgoingSocketThread( 3223): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3223): doStop: Thread ID: 339
D/io.jxcore.node.OutgoingSocketThread( 3223): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3223): doStop: Thread ID: 338
D/io.jxcore.node.OutgoingSocketThread( 3223): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 3223): closeLocalSocketAndStreams: Closing the local input stream...
W/io.jxcore.node.StreamCopyingThread( 3223): Either failed to read from the output stream or write to the input stream (thread ID: 338, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3223): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3223): onDisconnected: Outgoing connection, peer [44:80:EB:7B:5A:05 motorola-XT1072_PT3784] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.OutgoingSocketThread( 3223): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 3223): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3223): closeBluetoothSocketAndStreams
W/io.jxcore.node.StreamCopyingThread( 3223): Either failed to read from the output stream or write to the input stream (thread ID: 339, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 3223): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3223): onDisconnected: Outgoing connection, peer [44:80:EB:7B:5A:05 motorola-XT1072_PT3784] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
D/io.jxcore.node.ConnectionHelper( 3223): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3223): disconnectOutgoingConnection: Successfully disconnected (peer ID: 44:80:EB:7B:5A:05
E/io.jxcore.node.ConnectionHelper( 3223): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 44:80:EB:7B:5A:05
D/io.jxcore.node.ConnectionHelper( 3223): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3223): Exiting thread (ID: 338, name: Sender)
E/io.jxcore.node.ConnectionHelper( 3223): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 44:80:EB:7B:5A:05
D/io.jxcore.node.ConnectionHelper( 3223): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3223): Exiting thread (ID: 339, name: Receiver)
I/jxcore-log( 3223): 2015-12-22T01:00:20.915Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3223): 
I/jxcore-log( 3223): ---- round done--------
I/jxcore-log( 3223): 
I/jxcore-log( 3223): startWithNextDevice
I/jxcore-log( 3223): 
,W/bt-btif ( 2075): bta_jv_rfc_port_to_cb(port_handle:0xf):jv handle:0x0 not FOUND
,D/btif_config_util( 2075): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2075): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2075): onReceive
,I/BTConnectionReceiver( 1375): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1375): Bluetooth Device Name: XT1072
,W/bt-btif ( 2075): info:x10
D/        ( 2075): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
E/BluetoothRemoteDevices( 2075): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3223): timeout now
I/jxcore-log( 3223): 
I/jxcore-log( 3223): weAreDoneNow, resultArray.length: 3
I/jxcore-log( 3223): 
I/jxcore-log( 3223): sendReportNow
I/jxcore-log( 3223): 
I/jxcore-log( 3223): done, now sending data to server
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T01:00:25.382Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3223): 
,E/bt-btm  ( 2075): tBTM_SEC_DEV:0xa40515dc rs_disc_pending=0
W/bt-btif ( 2075): bta_dm_check_av:0
W/bt-btif ( 2075): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 2075): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 1
E/bt-btif ( 2075): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2075): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2075): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2075): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 0
D/BluetoothAdapterProperties( 2075): Failed to remove device: E0:DB:10:14:E2:C0
,I/BluetoothBondStateMachine( 2075): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2075): StableState(): Entering Off State
,W/bt-btif ( 2075): new conn_srvc id:26, app_id:255
W/bt-btif ( 2075): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2075): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3223): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3223): Incoming connection initialized (thread ID: 340)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3223): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3223): Entering thread (ID: 340)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3223): onBytesRead: Read 82 bytes successfully (thread ID: 340)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3223): Got valid identity from [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1903]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3223): onBytesWritten: 77 bytes successfully written (thread ID: 340)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3223): removeThreadFromList: Removing thread with ID 340
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3223): Handshake thread disposed (thread ID: 340)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3223): onIncomingConnectionConnected: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1903]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3223): Exiting thread (ID: 340)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3223): onConnected: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1903]
I/io.jxcore.node.ConnectionHelper( 3223): onConnected: Incoming connection to peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1903]
D/io.jxcore.node.ConnectionHelper( 3223): hasConnection: No connection with peer with ID E0:DB:10:14:E2:C0
D/io.jxcore.node.ConnectionHelper( 3223): notifyPeerAvailability: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1903] is available
,I/jxcore-log( 3223): peerAvailabilityChanged [{"peerIdentifier":"E0:DB:10:14:E2:C0","peerName":"samsung-SM-N910C_PT1903","peerAvailable":true}]
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): Found peer : samsung-SM-N910C_PT1903, Available: true
I/jxcore-log( 3223): 
I/jxcore-log( 3223): startWithNextDevice
I/jxcore-log( 3223): 
I/io.jxcore.node.ConnectionHelper( 3223): onConnected: Incoming socket thread, for peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1903], created successfully
D/io.jxcore.node.ConnectionHelper( 3223): onConnected: The total number of connections is now 1
,D/io.jxcore.node.IncomingSocketThread( 3223): Entering thread (ID: 341)
,I/io.jxcore.node.IncomingSocketThread( 3223): Local host address: localhost/127.0.0.1, port: 47561
D/io.jxcore.node.IncomingSocketThread( 3223): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3223): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3223): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3223): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3223): Exiting thread (ID: 341)
,I/jxcore-log( 3223): 2015-12-22T01:00:25.944Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3223): 
,D/io.jxcore.node.StreamCopyingThread( 3223): Entering thread (ID: 342, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 3223): Entering thread (ID: 343, name: Receiver)
,I/jxcore-log( 3223): 2015-12-22T01:00:26.650Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T01:00:26.656Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T01:00:26.677Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T01:00:26.684Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T01:00:26.707Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T01:00:26.716Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T01:00:26.741Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T01:00:26.773Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T01:00:26.797Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T01:00:26.814Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T01:00:26.827Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T01:00:26.862Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T01:00:26.880Z SendDataTCPServer.js: TCP/IP server has received 47520 bytes of data
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T01:00:26.914Z SendDataTCPServer.js: TCP/IP server has received 69300 bytes of data
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T01:00:26.954Z SendDataTCPServer.js: TCP/IP server has received 79200 bytes of data
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T01:00:26.974Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T01:00:26.995Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T01:00:26.999Z SendDataTCPServer.js: TCP/IP server has received 95040 bytes of data
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T01:00:27.032Z SendDataTCPServer.js: TCP/IP server has received 97020 bytes of data
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T01:00:27.056Z SendDataTCPServer.js: TCP/IP server has received 99000 bytes of data
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T01:00:27.074Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3223): 
,W/bt-btif ( 2075): invalid rfc slot id: 11
,W/io.jxcore.node.StreamCopyingThread( 3223): Either failed to read from the output stream or write to the input stream (thread ID: 343, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 3223): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3223): onDisconnected: Incoming connection, peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1903] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3223): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 341
D/io.jxcore.node.IncomingSocketThread( 3223): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3223): doStop: Thread ID: 343
D/io.jxcore.node.IncomingSocketThread( 3223): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3223): doStop: Thread ID: 342
D/io.jxcore.node.IncomingSocketThread( 3223): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 3223): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3223): Either failed to read from the output stream or write to the input stream (thread ID: 342, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3223): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3223): onDisconnected: Incoming connection, peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1903] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.IncomingSocketThread( 3223): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 3223): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3223): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3223): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3223): Exiting thread (ID: 343, name: Receiver)
,D/io.jxcore.node.ConnectionHelper( 3223): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.StreamCopyingThread( 3223): Exiting thread (ID: 342, name: Sender)
,I/jxcore-log( 3223): 2015-12-22T01:00:27.174Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3223): 
,W/bt-rfcomm( 2075): rfc_find_lcid_mcb LCID reused LCID:0x4c current:0x0
W/bt-rfcomm( 2075): RFCOMM_DisconnectInd LCID:0x4c
,E/bt-btm  ( 2075): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2075): onReceive
,I/BTConnectionReceiver( 1375): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1375): Bluetooth Device Name: Note4-1
,D/btif_config_util( 2075): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3223): teardown
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): testSendData stopped
I/jxcore-log( 3223): 
I/io.jxcore.node.ConnectionHelper( 3223): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3223): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3223): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3223): stopListeningForIncomingConnections: Stopping...
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3223): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3223): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3223): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3223): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3223): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3223): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3223): stop: Stopping P2P device discovery...
,I/wpa_supplicant(  981): P2P-FIND-STOPPED 
,I/wpa_supplicant(  981): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant(  981): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3223): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3223): release: No more listeners, de-initializing...
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3223): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3223): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3223): setState: NOT_STARTED
,I/jxcore-log( 3223): StopBroadcasting went ok
I/jxcore-log( 3223): 
,I/jxcore-log( 3223): 2015-12-22T01:00:46.148Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
I/jxcore-log( 3223): 
I/chromium( 3223): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
I/io.jxcore.node.ConnectionHelper( 3223): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3223): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3223): P2P device discovery stopped successfully
I/io.jxcore.node.ConnectionHelper( 3223): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3223): Service requests cleared successfully
,I/jxcore-log( 3223): ****TEST TOOK:  ms ****
I/jxcore-log( 3223): 
I/jxcore-log( 3223): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3223): 
,D/AndroidRuntime( 3680): 
D/AndroidRuntime( 3680): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 3680): CheckJNI is OFF
,D/AndroidRuntime( 3680): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  761): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
,I/ActivityManager(  761): Killing 3223:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
,W/PackageSettings(  761): Skipping PackageSetting{1a3169fd com.example.hello/10278} due to missing metadata
,I/WindowState(  761): WIN DEATH: Window{2386d456 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  761): Client connection lost with reason: 4
,I/ActivityManager(  761):   Force finishing activity ActivityRecord{7c5f882 u0 com.test.thalitest/.MainActivity t214}
,W/ActivityManager(  761): Spurious death for ProcessRecord{9334b75 3223:com.test.thalitest/u0a270}, curProc for 3223: null
,I/ActivityManager(  761): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
,I/art     ( 1269): Explicit concurrent mark sweep GC freed 4016(297KB) AllocSpace objects, 1(126KB) LOS objects, 38% free, 25MB/41MB, paused 626us total 47.089ms
,W/GeofencerStateMachine( 1573): Ignoring removeGeofence because network location is disabled.
,I/InputReader(  761): Reconfiguring input devices.  changes=0x00000010
,I/Keyboard.Facilitator( 1096): resetDictionaries() : en_US
,I/Keyboard.Facilitator.DecoderInitializer( 1096): run()
I/Decoder ( 1096): createOrResetDecoder
,I/art     ( 1375): Explicit concurrent mark sweep GC freed 28991(1407KB) AllocSpace objects, 5(80KB) LOS objects, 25% free, 18MB/25MB, paused 321us total 96.642ms
I/art     ( 1594): Explicit concurrent mark sweep GC freed 11065(532KB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 22MB/30MB, paused 586us total 98.834ms
,D/VoicemailCleanupService( 2879): Cleaning up data for package: com.test.thalitest
,I/UpdateIcingCorporaServi( 1375): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/art     (  761): Explicit concurrent mark sweep GC freed 41188(2MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 1.785ms total 83.833ms
,I/art     (  761): WaitForGcToComplete blocked for 38.852ms for cause Explicit
,W/Launcher( 1269): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@3fe2a43e new=com.google.android.velvet.VelvetApplication@3fe2a43e
,I/Adreno-EGL(  950): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/OpenGLRenderer(  950): Initialized EGL, version 1.4
,D/OpenGLRenderer(  950): Enabling debug mode 0
,I/ActivityManager(  761): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3722 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/ConfigService( 1573): onCreate
,D/BackupManagerService(  761): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  761): Receieved: android.intent.action.PACKAGE_REMOVED
,D/TaskPersister(  761): removeObsoleteFile: deleting file=214_task.xml
,W/InputMethodManagerService(  761): Focus gain on non-focused client com.android.internal.view.IInputMethodClient$Stub$Proxy@19dbbdca (uid=10034 pid=950)
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1096): run()
,W/ContextImpl( 3722): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
,D/PackageBroadcastService( 1594): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1594): Clearing selected account for com.test.thalitest
,I/UpdateIcingCorporaServi( 1375): UpdateCorporaTask done [took 151 ms] updated apps [took 151 ms] 
D/ChimeraCfgMgr( 1594): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1594): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1594): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1594): Module APK com.google.android.play.games already loaded
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1096): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/LocationSettingsChecker( 1594): Removing dialog suppression flag for package com.test.thalitest
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1096): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1096): run() : Loading LM = contacts
,E/NetworkScheduler.SchedulerReceiver( 1573): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1573): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1096): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1096): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1096): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1096): run() : Loading LM = user
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1096): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1096): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1096): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1096): run()
I/StatsUtilsManager( 1096): startPeriodStatsRecorder() : Success
,I/PeriodicStatsRecorder( 1096): shouldRecordStats() = Too Soon
I/art     (  761): Explicit concurrent mark sweep GC freed 8824(456KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 1.727ms total 174.545ms
,W/InputMethodManagerService(  761): Got RemoteException sending setActive(false) notification to pid 3223 uid 10270
,I/Keyboard.Facilitator( 1096): onFinishInput()
,I/Launcher( 1269): Deferring update until onResume
,W/ResourcesManager( 1269): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/gH_CompatibleDatabase( 1594): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1594): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1594): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1594): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/gH_CompatibleDatabase( 1594): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1594): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1594): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,W/ResourcesManager( 1269): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/gH_CompatibleDatabase( 1594): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1594): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 1594): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,D/gH_CompatibleDatabase( 1594): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
,D/gH_CompatibleDatabase( 1594): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1594): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/ActivityManager(  761): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3755 uid=10039 gids={50039, 9997} abi=armeabi-v7a
,I/Launcher( 1269): Deferring update until onResume
,D/AndroidRuntime( 3680): Shutting down VM
,I/GMPM-SVC( 1594): App measurement is starting up, version: 8489
I/GMPM-SVC( 1594): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,W/BaseAppContext( 1594): Using Auth Proxy for data requests.
,W/BaseAppContext( 1594): Using Auth Proxy for data requests.
,I/Icing   ( 1594): doRemovePackageData com.test.thalitest
,I/ActivityManager(  761): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3779 uid=10007 gids={50007, 9997, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  761): Killing 1990:com.google.android.calendar/u0a31 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10031/pid_1990/cgroup.procs: No such file or directory
,I/ActivityManager(  761): Killing 3003:com.google.android.gms:car/u0a8 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10008/pid_3003/cgroup.procs: No such file or directory
,D/ExternalStorage( 3779): After updating volumes, found 1 active roots
,W/ResourcesManager( 3156): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3156): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.

```
