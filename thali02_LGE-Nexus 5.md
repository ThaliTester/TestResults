#### Test 549702613245198_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
I/GAv4    ( 3156): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3156):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3156):   adb logcat -s GAv4
W/GAv4    ( 3156): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3156): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3156): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 3156): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
D/Finsky  ( 2587): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
W/ResourcesManager( 3156): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3156): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  765): Killing 2556:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
V/JNIHelp ( 3156): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/System  ( 3156): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3156): Installed default security provider GmsCore_OpenSSL
W/libprocessgroup(  765): failed to open /acct/uid_10069/pid_2556/cgroup.procs: No such file or directory
V/GLSActivity( 1579): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 1605): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/Icing   ( 1605): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/Icing   ( 1605): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1605): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
,D/AndroidRuntime( 3218): 
D/AndroidRuntime( 3218): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3218): CheckJNI is OFF
D/AndroidRuntime( 3218): Calling main entry com.android.commands.am.Am
I/ActivityManager(  765): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  765): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3241 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3218): Shutting down VM
V/ActivityManager(  765): Display changed displayId=0
I/WebViewFactory( 3241): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/ActivityManager(  765): Killing 2512:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
I/LibraryLoader( 3241): Time to load native libraries: 1 ms (timestamps 6746-6747)
I/LibraryLoader( 3241): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3241): Binding Chromium to main looper Looper (main, tid 1) {946bcff}
I/LibraryLoader( 3241): Expected native library version number "",actual native library version number ""
I/chromium( 3241): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3241): Initializing chromium process, singleProcess=true
W/art     ( 3241): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3241): ApplicationContext is null in ApplicationStatus
W/libprocessgroup(  765): failed to open /acct/uid_10045/pid_2512/cgroup.procs: No such file or directory
W/chromium( 3241): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3241): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3241): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3241): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  765): Message: 20
D/BluetoothManagerService(  765): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2c55c380:true
,W/art     ( 3241): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3241): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3241): CordovaWebView is running on device made by: LGE
,W/art     ( 3241): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3241): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3241): Render dirty regions requested: true
,D/Atlas   ( 3241): Validating map...
,W/chromium( 3241): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3241): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3241): Enabling debug mode 0
,I/Keyboard.Facilitator( 1100): onFinishInput()
,W/BindingManager( 3241): Cannot call determinedVisibility() - never saw a connection for the pid: 3241
,W/IInputConnectionWrapper( 3241): showStatusIcon on inactive InputConnection
,I/ActivityManager(  765): Displayed com.test.thalitest/.MainActivity: +428ms (total +55s421ms)
,D/JsMessageQueue( 3241): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3241): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257342720
D/JX-Cordova( 3241): jxcore cordova android initializing
,W/jxcore-log( 3241): Initializing JXcore engine
W/jxcore-log( 3241): JXcore engine is ready
,W/jxcore-log( 3241): Starting JXcore engine
,W/.test.thalitest( 3241): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[9410]" dev="sockfs" ino=9410 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3241): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 3241): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[10305]" dev="sockfs" ino=10305 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3241): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[20721]" dev="sockfs" ino=20721 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3241): Platform android
W/jxcore-log( 3241): 
W/jxcore-log( 3241): Process ARCH arm
W/jxcore-log( 3241): 
,I/jxcore-log( 3241): JXcore Cordova bridge is ready!
I/jxcore-log( 3241): 
W/jxcore-log( 3241): JXcore engine is started
I/chromium( 3241): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3241): Toggling radios to true
I/jxcore-log( 3241): 
,D/BluetoothAdapter( 3241): enable(): BT is already enabled..!
,D/WifiService(  765): setWifiEnabled: true pid=3241, uid=10270
E/WifiService(  765): Invoking mWifiStateMachine.setWifiEnabled
,D/WifiService(  765): New client listening to asynchronous messages
,I/jxcore-log( 3241): Radios toggled
I/jxcore-log( 3241): 
,I/wpa_supplicant( 1043): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  765): WifiStateMachine: Leaving Connected state
,E/WifiConfigStore(  765): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/native  (  765): do suspend true
,D/CommandListener(  180): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1579): Read error: ssl=0xb3f2ae00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1579): SSL shutdown failed: ssl=0xb3f2ae00: I/O error during system call, Broken pipe
,D/ConnectivityService(  765): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  765): ValidatedState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  765): DefaultState{ when=-1ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  765): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  765): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  765): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  765): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,E/WifiConfigStore(  765): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  765): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  765): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
E/WifiStateMachine(  765): Start Disconnecting Watchdog 1
,I/wpa_supplicant( 1043): wlan0: CTRL-EVENT-SCAN-STARTED 
E/native  (  765): do suspend true
,D/CommandListener(  180): Clearing all IP addresses on wlan0
D/ConnectivityService(  765): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler(  902): CM callback handler got msg 524292
,D/Nat464Xlat(  765): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/ConnectivityManager.CallbackHandler( 1605): CM callback handler got msg 524292
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  765): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  765): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  765): Disconnected - quitting
,D/CSLegacyTypeTracker(  765): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,D/ConnectivityService(  765): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  765): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  765): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1234): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WifiNetworkAgent(  765): NetworkAgent: NetworkAgent channel lost
,I/wpa_supplicant( 1043): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant( 1043): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1043): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1043): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  765): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  765): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  765): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiConfigStore(  765): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  180): Setting iface cfg
E/WifiStateMachine(  765): Start Dhcp Watchdog 2
,E/native  (  765): do suspend false
,E/WifiStateMachine(  765): scanCount==0 - aborting
,I/dhcpcd  ( 3329): version 5.5.6 starting
E/dhcpcd  ( 3329): get_duid: Read-only file system
,I/dhcpcd  ( 3329): wlan0: rebinding lease of 192.168.1.114
,V/GLSActivity( 1579): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1579): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/NetworkUtils( 1372): OkHttp exception
W/EventLoggerService( 1372): Unable to send logs Error code: 262146
,D/ConnectivityService(  765): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  765): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  765): MasterInitialState.processMessage what=3
,D/Tethering(  765): MasterInitialState.processMessage what=3
,V/MusicLeanback( 2698): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1605): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1605): onCreate
,D/SystemUpdateService( 1605): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.Environment( 1605): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1605): num queued entries: 0
,I/iu.UploadsManager( 1605): num updated entries: 0
I/iu.SyncManager( 1605): NEXT; no task
,I/Babel   ( 1905): connection state changed from CONNECTED to DISCONNECTED
I/SystemUpdateService( 1605): active receiver: enabled
,I/SystemUpdateService( 1605): showing system update notification
,I/ActivityManager(  765): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3348 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/GpsLocationProvider(  765): No APN found to select.
,I/dhcpcd  ( 3329): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,E/GpsLocationProvider(  765): No APN found to select.
,I/ValidateNoPeople(  765): skipping global notification
,V/SystemUpdateService( 1605): retry (wakeup: false) in 3599929 ms
,D/SystemUpdateService( 1605): onDestroy
,I/dhcpcd  ( 3329): wlan0: leased 192.168.1.114 for 86400 seconds
,I/GAv4    ( 3348): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3348):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3348):   adb logcat -s GAv4
,W/GAv4    ( 3348): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3348): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3348): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,E/native  (  765): do suspend true
,E/WifiStateMachine(  765): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/ConnectivityService(  765): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  765): Adding iface wlan0 to network 101
,E/ConnectivityService(  765): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  765): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/ConnectivityService(  765): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  765): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  765): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  765): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  765): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  765): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  765): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  765):    accepting network in place of null
,D/CSLegacyTypeTracker(  765): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  765): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  765): Connected
D/ConnectivityService(  765): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  765): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  765): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/ConnectivityService(  765): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::5255:27ff:fef0:fd0b/64,192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  765): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  902): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1605): CM callback handler got msg 524290
,I/WebViewFactory( 3348): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3348): Time to load native libraries: 1 ms (timestamps 2735-2736)
I/LibraryLoader( 3348): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3348): Binding Chromium to main looper Looper (main, tid 1) {375eb163}
I/LibraryLoader( 3348): Expected native library version number "",actual native library version number ""
I/chromium( 3348): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  765): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 08 Jan 2016 20:07:49 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452283669341], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452283669324]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  765): Don't send network conditions - lacking user consent.
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  765): Validated
,D/ConnectivityService(  765): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  765): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  765): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  765): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
I/BrowserStartupController( 3348): Initializing chromium process, singleProcess=true
W/art     ( 3348): Attempt to remove local handle scope entry from IRT, ignoring
D/ConnectivityManager.CallbackHandler(  902): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1605): CM callback handler got msg 524290
D/ConnectivityService(  765): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/TelephonyNetworkFactory( 1234): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/SysUtils( 3348): ApplicationContext is null in ApplicationStatus
,W/chromium( 3348): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3348): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3348): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3348): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/AudioManagerAndroid( 3348): Requires BLUETOOTH permission
,I/NSApplication( 3348): Starting up...
,I/ActivityManager(  765): Killing 2674:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/libprocessgroup(  765): failed to open /acct/uid_10003/pid_2674/cgroup.procs: No such file or directory
,V/MusicLeanback( 2698): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1605): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1605): onCreate
,D/SystemUpdateService( 1605): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.Environment( 1605): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1605): num queued entries: 0
I/iu.UploadsManager( 1605): num updated entries: 0
I/iu.SyncManager( 1605): NEXT; no task
,I/SystemUpdateService( 1605): active receiver: enabled
,I/SystemUpdateService( 1605): showing system update notification
,I/ValidateNoPeople(  765): skipping global notification
,V/SystemUpdateService( 1605): retry (wakeup: false) in 3599966 ms
D/SystemUpdateService( 1605): onDestroy
,I/Babel   ( 1905): connection state changed from DISCONNECTED to CONNECTED
,D/ConnectivityService(  765): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/jxcore-log( 3241): Test app app.js loaded
I/jxcore-log( 3241): 
,I/chromium( 3241): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/ConnectivityService(  765): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  765): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2698): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2698): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1605): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,I/art     (  765): Explicit concurrent mark sweep GC freed 45510(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 27MB/41MB, paused 1.279ms total 57.824ms
,D/SystemUpdateService( 1605): onCreate
,D/SystemUpdateService( 1605): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1605): active receiver: enabled
,E/GpsLocationProvider(  765): No APN found to select.
,I/SystemUpdateService( 1605): showing system update notification
,I/ValidateNoPeople(  765): skipping global notification
,V/SystemUpdateService( 1605): retry (wakeup: false) in 3599976 ms
,D/SystemUpdateService( 1605): onDestroy
,D/Finsky  ( 2587): [255] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2587): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/GLSActivity( 1579): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1579): Vacuum at: now=1452283683300 tag=VacuumService
,D/HeadsetStateMachine( 2087): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 2087): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
D/HeadsetStateMachine( 2087): Disconnected process message: 11, size: 0
,I/Keyboard.Facilitator.LanguageModelFlusher( 1100): run()
I/Keyboard.Facilitator( 1100): flushDynamicLanguageModels()
,I/ConfigService( 1579): onCreate
,I/ConfigService( 1579): onDestroy
,I/ClearcutLoggerApiImpl( 1579): disconnect managed GoogleApiClient
,I/jxcore-log( 3241): --= Surplus to requirements =--
I/jxcore-log( 3241): 
I/jxcore-log( 3241): ****TEST TOOK:  ms ****
I/jxcore-log( 3241): 
I/jxcore-log( 3241): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3241): 
,D/AndroidRuntime( 3519): 
D/AndroidRuntime( 3519): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 3519): CheckJNI is OFF
,D/AndroidRuntime( 3519): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  765): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  765): Killing 3241:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
,I/WindowState(  765): WIN DEATH: Window{a210cb0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  765): Client connection lost with reason: 4
,W/PackageSettings(  765): Skipping PackageSetting{19c995a3 com.example.hello/10278} due to missing metadata
,I/ActivityManager(  765):   Force finishing activity ActivityRecord{120d577c u0 com.test.thalitest/.MainActivity t214}
,W/ActivityManager(  765): Spurious death for ProcessRecord{123d0c1b 3241:com.test.thalitest/u0a270}, curProc for 3241: null
I/ActivityManager(  765): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
,I/ActivityManager(  765):   Force finishing activity ActivityRecord{120d577c u0 com.test.thalitest/.MainActivity t214 f}
W/ActivityManager(  765): Duplicate finish request for ActivityRecord{120d577c u0 com.test.thalitest/.MainActivity t214 f}
,I/InputReader(  765): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1579): Ignoring removeGeofence because network location is disabled.
,I/art     ( 1260): Explicit concurrent mark sweep GC freed 3990(296KB) AllocSpace objects, 1(126KB) LOS objects, 38% free, 25MB/41MB, paused 771us total 35.891ms
,I/Keyboard.Facilitator( 1100): resetDictionaries() : en_US
,I/Keyboard.Facilitator.DecoderInitializer( 1100): run()
,I/Adreno-EGL(  948): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
I/OpenGLRenderer(  948): Initialized EGL, version 1.4
,D/OpenGLRenderer(  948): Enabling debug mode 0
,I/art     ( 1372): Explicit concurrent mark sweep GC freed 7607(525KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 19MB/25MB, paused 319us total 95.163ms
,D/VoicemailCleanupService( 2826): Cleaning up data for package: com.test.thalitest
,I/Decoder ( 1100): createOrResetDecoder
,I/art     (  765): Explicit concurrent mark sweep GC freed 18572(1114KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 1.314ms total 126.355ms
I/art     (  765): WaitForGcToComplete blocked for 125.745ms for cause Explicit
,W/Launcher( 1260): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@2cee5acc new=com.google.android.velvet.VelvetApplication@2cee5acc
,I/UpdateIcingCorporaServi( 1372): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/art     ( 1605): Explicit concurrent mark sweep GC freed 10967(527KB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 22MB/30MB, paused 10.854ms total 148.595ms
,I/ActivityManager(  765): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3559 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/ConfigService( 1579): onCreate
,W/InputMethodManagerService(  765): Got RemoteException sending setActive(false) notification to pid 3241 uid 10270
,I/Keyboard.Facilitator( 1100): onFinishInput()
,D/BackupManagerService(  765): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  765): Receieved: android.intent.action.PACKAGE_REMOVED
,D/TaskPersister(  765): removeObsoleteFile: deleting file=214_task.xml
,W/ContextImpl( 3559): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1100): run()
,D/PackageBroadcastService( 1605): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1605): Clearing selected account for com.test.thalitest
I/art     (  765): Explicit concurrent mark sweep GC freed 5598(300KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 2.254ms total 136.077ms
,D/ChimeraCfgMgr( 1605): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1605): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1605): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1605): Module APK com.google.android.play.games already loaded
,I/LocationSettingsChecker( 1605): Removing dialog suppression flag for package com.test.thalitest
,I/UpdateIcingCorporaServi( 1372): UpdateCorporaTask done [took 144 ms] updated apps [took 143 ms] 
,I/Keyboard.Facilitator( 1100): onFinishInput()
,W/IInputConnectionWrapper( 1260): showStatusIcon on inactive InputConnection
I/Keyboard.Facilitator.MainLanguageModelLoader( 1100): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1100): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1100): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1100): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1100): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1100): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1100): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1100): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1100): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1100): run()
E/NetworkScheduler.SchedulerReceiver( 1579): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1579): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/Keyboard.Facilitator.RecurringTaskScheduler( 1100): run()
I/StatsUtilsManager( 1100): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1100): shouldRecordStats() = Too Soon
D/gH_CompatibleDatabase( 1605): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1605): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1605): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1605): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/gH_CompatibleDatabase( 1605): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1605): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1605): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 1605): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1605): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1605): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1605): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1605): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1605): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/Launcher( 1260): Deferring update until onResume
,I/GMPM-SVC( 1605): App measurement is starting up, version: 8489
I/GMPM-SVC( 1605): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
W/BaseAppContext( 1605): Using Auth Proxy for data requests.
,W/ResourcesManager( 1260): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/AndroidRuntime( 3519): Shutting down VM
,I/ActivityManager(  765): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3594 uid=10039 gids={50039, 9997} abi=armeabi-v7a
,W/ResourcesManager( 1260): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Launcher( 1260): Deferring update until onResume
,W/BaseAppContext( 1605): Using Auth Proxy for data requests.
,I/ActivityManager(  765): Killing 2656:com.android.settings/1000 (adj 15): empty #17
,D/WifiService(  765): Client connection lost with reason: 4
,W/libprocessgroup(  765): failed to open /acct/uid_1000/pid_2656/cgroup.procs: No such file or directory
,I/Icing   ( 1605): doRemovePackageData com.test.thalitest
,E/SQLiteLog( 1605): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/GMPM-SVC( 1605): Task exception on worker thread: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850): com.google.android.gms.measurement.internal.e.b(SourceFile:321)
,E/SharedPreferencesImpl( 1605): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
,E/SQLiteDatabase( 3594): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 3594): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3594): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3594): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 3594): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 3594): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3594): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3594): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3594): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 3594): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 3594): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 3594): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/SQLiteDatabase( 3594): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 3594): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 3594): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 3594): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/SQLiteDatabase( 3594): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/SQLiteDatabase( 3594): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:367)
E/SQLiteDatabase( 3594): 	at android.content.ContentResolver.call(ContentResolver.java:1372)
E/SQLiteDatabase( 3594): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/SQLiteDatabase( 3594): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2579)
E/SQLiteDatabase( 3594): 	at android.app.ActivityThread.access$1700(ActivityThread.java:144)
E/SQLiteDatabase( 3594): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1355)
E/SQLiteDatabase( 3594): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 3594): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 3594): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/SQLiteDatabase( 3594): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 3594): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 3594): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/SQLiteDatabase( 3594): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
D/AndroidRuntime( 3594): Shutting down VM
,--------- beginning of crash
,E/AndroidRuntime( 3594): FATAL EXCEPTION: main
E/AndroidRuntime( 3594): Process: com.android.documentsui, PID: 3594
E/AndroidRuntime( 3594): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 3594): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2586)
E/AndroidRuntime( 3594): 	at android.app.ActivityThread.access$1700(ActivityThread.java:144)
E/AndroidRuntime( 3594): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1355)
E/AndroidRuntime( 3594): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 3594): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 3594): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/AndroidRuntime( 3594): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 3594): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 3594): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/AndroidRuntime( 3594): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
E/AndroidRuntime( 3594): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 3594): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 3594): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 3594): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 3594): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 3594): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 3594): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 3594): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AndroidRuntime( 3594): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AndroidRuntime( 3594): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 3594): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/AndroidRuntime( 3594): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 3594): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 3594): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 3594): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/AndroidRuntime( 3594): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/AndroidRuntime( 3594): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:367)
E/AndroidRuntime( 3594): 	at android.content.ContentResolver.call(ContentResolver.java:1372)
E/AndroidRuntime( 3594): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/AndroidRuntime( 3594): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2579)
E/AndroidRuntime( 3594): 	... 9 more
I/ActivityManager(  765): Killing 2530:com.google.android.gm/u0a70 (adj 15): empty #17

```
