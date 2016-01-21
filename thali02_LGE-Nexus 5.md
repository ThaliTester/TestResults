#### Test 568182548138a64_thali02_LGE-Nexus 5 Logs


```
--------- beginning of system
W/ResourcesManager( 3204): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3204): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
--------- beginning of main
D/Finsky  ( 2632): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
I/ActivityManager(  761): Killing 2600:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
V/JNIHelp ( 3204): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/System  ( 3204): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3204): Installed default security provider GmsCore_OpenSSL
W/libprocessgroup(  761): failed to open /acct/uid_10069/pid_2600/cgroup.procs: No such file or directory
V/GLSActivity( 1568): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 1594): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/Icing   ( 1594): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1594): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/Icing   ( 1594): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
I/ActivityManager(  761): Killing 2531:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
W/libprocessgroup(  761): failed to open /acct/uid_10045/pid_2531/cgroup.procs: No such file or directory
,D/AndroidRuntime( 3258): 
D/AndroidRuntime( 3258): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3258): CheckJNI is OFF
D/AndroidRuntime( 3258): Calling main entry com.android.commands.am.Am
I/ActivityManager(  761): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  761): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3282 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3258): Shutting down VM
V/ActivityManager(  761): Display changed displayId=0
I/WebViewFactory( 3282): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3282): Time to load native libraries: 10 ms (timestamps 8930-8940)
I/LibraryLoader( 3282): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3282): Binding Chromium to main looper Looper (main, tid 1) {b5eb143}
I/LibraryLoader( 3282): Expected native library version number "",actual native library version number ""
I/chromium( 3282): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3282): Initializing chromium process, singleProcess=true
W/art     ( 3282): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3282): ApplicationContext is null in ApplicationStatus
,W/chromium( 3282): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3282): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3282): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3282): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  761): Message: 20
D/BluetoothManagerService(  761): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@28b49e7a:true
,W/art     ( 3282): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3282): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3282): CordovaWebView is running on device made by: LGE
,W/art     ( 3282): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3282): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3282): Render dirty regions requested: true
,D/Atlas   ( 3282): Validating map...
,W/chromium( 3282): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3282): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3282): Enabling debug mode 0
,I/Keyboard.Facilitator( 1066): onFinishInput()
,W/BindingManager( 3282): Cannot call determinedVisibility() - never saw a connection for the pid: 3282
,W/IInputConnectionWrapper( 3282): showStatusIcon on inactive InputConnection
,I/ActivityManager(  761): Displayed com.test.thalitest/.MainActivity: +432ms (total +56s495ms)
,D/JsMessageQueue( 3282): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3282): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257342720
,I/chromium( 3282): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 3282): Initializing JXcore engine
W/jxcore-log( 3282): JXcore engine is ready
,W/Thread-306( 3339): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[7982]" dev="sockfs" ino=7982 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-306( 3339): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-306( 3339): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[9444]" dev="sockfs" ino=9444 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-306( 3339): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[18273]" dev="sockfs" ino=18273 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3282): Starting JXcore engine
,W/jxcore-log( 3282): Platform android
W/jxcore-log( 3282): 
W/jxcore-log( 3282): Process ARCH arm
W/jxcore-log( 3282): 
,I/jxcore-log( 3282): JXcore Cordova bridge is ready!
I/jxcore-log( 3282): 
,W/jxcore-log( 3282): JXcore engine is started
,I/jxcore-log( 3282): Toggling radios to true
I/jxcore-log( 3282): 
,D/BluetoothAdapter( 3282): enable(): BT is already enabled..!
,D/WifiService(  761): New client listening to asynchronous messages
,D/WifiService(  761): setWifiEnabled: true pid=3282, uid=10270
E/WifiService(  761): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3282): Radios toggled
I/jxcore-log( 3282): 
I/jxcore-log( 3282): My device name is: LGE-Nexus 5
I/jxcore-log( 3282): 
I/wpa_supplicant( 1078): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
E/WifiStateMachine(  761): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  761): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
E/native  (  761): do suspend true
D/CommandListener(  179): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1568): Read error: ssl=0x9b621c00: I/O error during system call, Connection timed out
E/WifiConfigStore(  761): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  761): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  761): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
V/NativeCrypto( 1568): SSL shutdown failed: ssl=0x9b621c00: I/O error during system call, Broken pipe
E/WifiStateMachine(  761): Start Disconnecting Watchdog 1
,D/ConnectivityService(  761): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): ValidatedState{ when=-1ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): DefaultState{ when=-1ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Checking http://clients3.google.com/generate_204 on <unknown ssid>
I/wpa_supplicant( 1078): wlan0: CTRL-EVENT-SCAN-STARTED 
,E/native  (  761): do suspend true
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,D/ConnectivityService(  761): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/ConnectivityManager.CallbackHandler(  900): CM callback handler got msg 524292
D/ConnectivityManager.CallbackHandler( 1594): CM callback handler got msg 524292
,D/Nat464Xlat(  761): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  761): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): EvaluatingState{ when=-4ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): DefaultState{ when=-4ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Disconnected - quitting
,D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  761): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1194): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WifiNetworkAgent(  761): NetworkAgent: NetworkAgent channel lost
,I/wpa_supplicant( 1078): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant( 1078): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1078): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1078): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  761): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  761): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
E/WifiConfigStore(  761): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  179): Setting iface cfg
,E/WifiStateMachine(  761): Start Dhcp Watchdog 2
,D/ConnectivityService(  761): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,V/GLSActivity( 1568): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1568): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/NetworkUtils( 1363): OkHttp exception
W/EventLoggerService( 1363): Unable to send logs Error code: 262146
,E/native  (  761): do suspend false
,E/WifiStateMachine(  761): scanCount==0 - aborting
,I/dhcpcd  ( 3374): version 5.5.6 starting
,E/dhcpcd  ( 3374): get_duid: Read-only file system
,I/dhcpcd  ( 3374): wlan0: rebinding lease of 192.168.1.114
,I/dhcpcd  ( 3374): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3374): wlan0: leased 192.168.1.114 for 86400 seconds
,D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  761): MasterInitialState.processMessage what=3
,D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  761): MasterInitialState.processMessage what=3
,V/MusicLeanback( 2748): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1594): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1594): onCreate
,D/SystemUpdateService( 1594): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.Environment( 1594): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1594): num queued entries: 0
I/iu.UploadsManager( 1594): num updated entries: 0
,I/iu.SyncManager( 1594): NEXT; no task
,I/SystemUpdateService( 1594): active receiver: enabled
,I/SystemUpdateService( 1594): showing system update notification
,E/GpsLocationProvider(  761): No APN found to select.
,I/Babel   ( 1902): connection state changed from CONNECTED to DISCONNECTED
,V/SystemUpdateService( 1594): retry (wakeup: false) in 3599972 ms
,I/ActivityManager(  761): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3417 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ValidateNoPeople(  761): skipping global notification
,E/native  (  761): do suspend true
,D/SystemUpdateService( 1594): onDestroy
,D/ConnectivityService(  761): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,E/WifiStateMachine(  761): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/ConnectivityService(  761): Adding iface wlan0 to network 101
,E/GpsLocationProvider(  761): No APN found to select.
,E/ConnectivityService(  761): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  761): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  761): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  761): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/ConnectivityService(  761): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  761): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  761): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  761): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  761): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  761):    accepting network in place of null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/CSLegacyTypeTracker(  761): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  761): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  761): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler(  900): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1594): CM callback handler got msg 524290
,I/GAv4    ( 3417): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3417):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3417):   adb logcat -s GAv4
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 21 Jan 2016 22:39:40 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1453415980264], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1453415980241]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Validated
,D/ConnectivityService(  761): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  761): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  761): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  761): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  900): CM callback handler got msg 524290
,D/TelephonyNetworkFactory( 1194): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 1594): CM callback handler got msg 524290
,W/GAv4    ( 3417): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3417): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3417): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/Nat464Xlat(  761): requiresClat: netType=1, connected=true, hasIPv4Address=true
,D/ConnectivityService(  761): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler(  900): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 1594): CM callback handler got msg 524295
,I/WebViewFactory( 3417): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3417): Time to load native libraries: 2 ms (timestamps 5113-5115)
I/LibraryLoader( 3417): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3417): Binding Chromium to main looper Looper (main, tid 1) {26844bbd}
,I/LibraryLoader( 3417): Expected native library version number "",actual native library version number ""
,I/chromium( 3417): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3417): Initializing chromium process, singleProcess=true
,W/art     ( 3417): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3417): ApplicationContext is null in ApplicationStatus
,I/jxcore-log( 3282): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3282): 
,W/chromium( 3417): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3417): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3417): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3417): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/AudioManagerAndroid( 3417): Requires BLUETOOTH permission
,I/NSApplication( 3417): Starting up...
,I/ActivityManager(  761): Killing 2724:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10003/pid_2724/cgroup.procs: No such file or directory
,V/MusicLeanback( 2748): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1594): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1594): onCreate
,D/SystemUpdateService( 1594): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1594): active receiver: enabled
,I/iu.Environment( 1594): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/iu.UploadsManager( 1594): num queued entries: 0
I/iu.UploadsManager( 1594): num updated entries: 0
I/iu.SyncManager( 1594): NEXT; no task
,I/SystemUpdateService( 1594): showing system update notification
,I/ValidateNoPeople(  761): skipping global notification
,V/SystemUpdateService( 1594): retry (wakeup: false) in 3599960 ms
,D/SystemUpdateService( 1594): onDestroy
,I/Babel   ( 1902): connection state changed from DISCONNECTED to CONNECTED
,I/jxcore-log( 3282): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 3282): 
,I/jxcore-log( 3282): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 3282): 
,D/ConnectivityService(  761): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/jxcore-log( 3282): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 3282): 
,I/jxcore-log( 3282): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 3282): 
,I/jxcore-log( 3282): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 3282): 
,I/jxcore-log( 3282): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3282): 
,I/jxcore-log( 3282): Test app app.js loaded
I/jxcore-log( 3282): 
,I/chromium( 3282): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3282): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 3282): BLE advertisement is supported
I/jxcore-log( 3282): 
,D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  761): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2748): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2748): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1594): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1594): onCreate
,D/SystemUpdateService( 1594): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1594): active receiver: enabled
I/SystemUpdateService( 1594): showing system update notification
,I/ValidateNoPeople(  761): skipping global notification
,V/SystemUpdateService( 1594): retry (wakeup: false) in 3599987 ms
,I/art     (  761): Explicit concurrent mark sweep GC freed 45007(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 27MB/41MB, paused 853us total 73.177ms
,E/GpsLocationProvider(  761): No APN found to select.
D/SystemUpdateService( 1594): onDestroy
,D/Finsky  ( 2632): [255] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2632): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/GLSActivity( 1568): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1568): Vacuum at: now=1453415994995 tag=VacuumService
,I/PhenotypeConfigurator( 1568): Scheduling Phenotype for one-off execution 5708 seconds from now (1453415995364)
,D/GetConfigurationSnapshotOperation( 1568): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1568): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1568): Using platform SSLCertificateSocketFactory
,I/Keyboard.Facilitator.LanguageModelFlusher( 1066): run()
I/Keyboard.Facilitator( 1066): flushDynamicLanguageModels()
,I/ConfigService( 1568): onCreate
,I/ConfigService( 1568): onDestroy
,I/ClearcutLoggerApiImpl( 1568): disconnect managed GoogleApiClient
,I/jxcore-log( 3282): --= Surplus to requirements =--
I/jxcore-log( 3282): 
I/jxcore-log( 3282): ****TEST TOOK:  ms ****
I/jxcore-log( 3282): 
I/jxcore-log( 3282): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3282): 
,D/AndroidRuntime( 3596): 
D/AndroidRuntime( 3596): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 3596): CheckJNI is OFF
,D/AndroidRuntime( 3596): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  761): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  761): Killing 3282:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
,I/WindowState(  761): WIN DEATH: Window{8b19a2a u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  761): Client connection lost with reason: 4
,W/PackageSettings(  761): Skipping PackageSetting{16bb4da7 com.example.hello/10278} due to missing metadata
,I/ActivityManager(  761):   Force finishing activity ActivityRecord{1f612d96 u0 com.test.thalitest/.MainActivity t216}
,W/ActivityManager(  761): Spurious death for ProcessRecord{17efddb5 3282:com.test.thalitest/u0a270}, curProc for 3282: null
I/ActivityManager(  761): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
I/ActivityManager(  761):   Force finishing activity ActivityRecord{1f612d96 u0 com.test.thalitest/.MainActivity t216 f}
W/ActivityManager(  761): Duplicate finish request for ActivityRecord{1f612d96 u0 com.test.thalitest/.MainActivity t216 f}
,I/art     ( 1594): Explicit concurrent mark sweep GC freed 11361(545KB) AllocSpace objects, 1(16KB) LOS objects, 25% free, 22MB/30MB, paused 441us total 29.858ms
,I/art     ( 1363): Explicit concurrent mark sweep GC freed 7804(535KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 19MB/25MB, paused 321us total 36.466ms
,I/art     ( 1250): Explicit concurrent mark sweep GC freed 3969(294KB) AllocSpace objects, 1(126KB) LOS objects, 23% free, 25MB/33MB, paused 223us total 26.399ms
,I/InputReader(  761): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 1568): Ignoring removeGeofence because network location is disabled.
I/Keyboard.Facilitator( 1066): resetDictionaries() : en_US
,I/Keyboard.Facilitator.DecoderInitializer( 1066): run()
I/Decoder ( 1066): createOrResetDecoder
,I/art     (  761): Explicit concurrent mark sweep GC freed 21035(1187KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 1.102ms total 74.286ms
,I/art     (  761): WaitForGcToComplete blocked for 45.096ms for cause Explicit
,D/VoicemailCleanupService( 2886): Cleaning up data for package: com.test.thalitest
,I/Adreno-EGL(  938): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/OpenGLRenderer(  938): Initialized EGL, version 1.4
,I/ConfigService( 1568): onCreate
,I/UpdateIcingCorporaServi( 1363): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,W/Launcher( 1250): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@e2613c0 new=com.google.android.velvet.VelvetApplication@e2613c0
D/OpenGLRenderer(  938): Enabling debug mode 0
,I/ActivityManager(  761): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3639 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,D/BackupManagerService(  761): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  761): Receieved: android.intent.action.PACKAGE_REMOVED
,D/TaskPersister(  761): removeObsoleteFile: deleting file=216_task.xml
,W/InputMethodManagerService(  761): Focus gain on non-focused client com.android.internal.view.IInputMethodClient$Stub$Proxy@41cc30a (uid=10034 pid=938)
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1066): run()
,I/art     (  761): Explicit concurrent mark sweep GC freed 5921(325KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 1.416ms total 150.261ms
,W/ContextImpl( 3639): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
,I/UpdateIcingCorporaServi( 1363): UpdateCorporaTask done [took 125 ms] updated apps [took 125 ms] 
,D/PackageBroadcastService( 1594): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1594): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1594): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1594): Module APK com.google.android.play.games already loaded
,I/ActivityManager(  761): Killing 2706:com.android.settings/1000 (adj 15): empty #17
,W/InputMethodManagerService(  761): Got RemoteException sending setActive(false) notification to pid 3282 uid 10270
I/Keyboard.Facilitator( 1066): onFinishInput()
,D/WifiService(  761): Client connection lost with reason: 4
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1066): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1066): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1066): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1066): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1066): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1066): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1066): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1066): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1066): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1066): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1066): run()
I/StatsUtilsManager( 1066): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1066): shouldRecordStats() = Too Soon
,W/libprocessgroup(  761): failed to open /acct/uid_1000/pid_2706/cgroup.procs: No such file or directory
,D/ChimeraCfgMgr( 1594): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1594): Module APK com.google.android.play.games already loaded
,I/Launcher( 1250): Deferring update until onResume
,I/LocationSettingsChecker( 1594): Removing dialog suppression flag for package com.test.thalitest
,D/AndroidRuntime( 3596): Shutting down VM
,E/NetworkScheduler.SchedulerReceiver( 1568): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1568): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,W/ResourcesManager( 1250): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 1250): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/gH_CompatibleDatabase( 1594): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1594): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1594): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1594): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/gH_CompatibleDatabase( 1594): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1594): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/gH_CompatibleDatabase( 1594): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
I/Launcher( 1250): Deferring update until onResume
,D/gH_CompatibleDatabase( 1594): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1594): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 1594): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1594): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1594): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1594): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/ActivityManager(  761): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3671 uid=10039 gids={50039, 9997} abi=armeabi-v7a
,I/GMPM-SVC( 1594): App measurement is starting up, version: 8489
,I/GMPM-SVC( 1594): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
W/BaseAppContext( 1594): Using Auth Proxy for data requests.
,W/BaseAppContext( 1594): Using Auth Proxy for data requests.
,I/Icing   ( 1594): doRemovePackageData com.test.thalitest
,I/ActivityManager(  761): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3698 uid=10007 gids={50007, 9997, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  761): Killing 2560:com.google.android.gm/u0a70 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10070/pid_2560/cgroup.procs: No such file or directory
,I/ActivityManager(  761): Killing 1986:com.google.android.calendar/u0a31 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10031/pid_1986/cgroup.procs: No such file or directory
,D/ExternalStorage( 3698): After updating volumes, found 1 active roots
,W/ResourcesManager( 3204): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3204): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.

```
