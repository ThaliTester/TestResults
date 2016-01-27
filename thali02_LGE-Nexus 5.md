#### Test 57348078846ce9d_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
D/Finsky  ( 2676): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
W/ResourcesManager( 3237): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3237): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  735): Killing 2631:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
,V/JNIHelp ( 3237): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/System  ( 3237): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3237): Installed default security provider GmsCore_OpenSSL
W/libprocessgroup(  735): failed to open /acct/uid_10069/pid_2631/cgroup.procs: No such file or directory
V/GLSActivity( 1640): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/AndroidRuntime( 3288): 
D/AndroidRuntime( 3288): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3288): CheckJNI is OFF
D/AndroidRuntime( 3288): Calling main entry com.android.commands.am.Am
I/ActivityManager(  735): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  735): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3305 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3288): Shutting down VM
V/ActivityManager(  735): Display changed displayId=0
I/Icing   ( 1684): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/Icing   ( 1684): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1684): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/WebViewFactory( 3305): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3305): Time to load native libraries: 1 ms (timestamps 7336-7337)
I/LibraryLoader( 3305): Expected native library version number "",actual native library version number ""
I/Icing   ( 1684): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
V/WebViewChromiumFactoryProvider( 3305): Binding Chromium to main looper Looper (main, tid 1) {d3b4c53}
I/LibraryLoader( 3305): Expected native library version number "",actual native library version number ""
I/chromium( 3305): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3305): Initializing chromium process, singleProcess=true
W/art     ( 3305): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3305): ApplicationContext is null in ApplicationStatus
W/chromium( 3305): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3305): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3305): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3305): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  735): Message: 20
D/BluetoothManagerService(  735): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@19be13d:true
W/art     ( 3305): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 3305): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 3305): CordovaWebView is running on device made by: LGE
W/art     ( 3305): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3305): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 3305): Render dirty regions requested: true
D/Atlas   ( 3305): Validating map...
W/chromium( 3305): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/OpenGLRenderer( 3305): Initialized EGL, version 1.4
D/OpenGLRenderer( 3305): Enabling debug mode 0
W/BindingManager( 3305): Cannot call determinedVisibility() - never saw a connection for the pid: 3305
W/IInputConnectionWrapper( 3305): showStatusIcon on inactive InputConnection
I/ActivityManager(  735): Displayed com.test.thalitest/.MainActivity: +461ms (total +56s733ms)
D/JsMessageQueue( 3305): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 3305): JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1258391296
I/chromium( 3305): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
I/ActivityManager(  735): Killing 2584:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
W/libprocessgroup(  735): failed to open /acct/uid_10045/pid_2584/cgroup.procs: No such file or directory
,W/jxcore-log( 3305): Initializing JXcore engine
W/jxcore-log( 3305): JXcore engine is ready
,W/Thread-317( 3361): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[8329]" dev="sockfs" ino=8329 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/Thread-317( 3361): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3097 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-317( 3361): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[10494]" dev="sockfs" ino=10494 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-317( 3361): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[21594]" dev="sockfs" ino=21594 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3305): Starting JXcore engine
,W/jxcore-log( 3305): Platform android
W/jxcore-log( 3305): 
W/jxcore-log( 3305): Process ARCH arm
W/jxcore-log( 3305): 
,I/jxcore-log( 3305): JXcore Cordova bridge is ready!
I/jxcore-log( 3305): 
,W/jxcore-log( 3305): JXcore engine is started
,I/jxcore-log( 3305): Toggling radios to true
I/jxcore-log( 3305): 
,D/BluetoothAdapter( 3305): enable(): BT is already enabled..!
,D/WifiService(  735): New client listening to asynchronous messages
,D/WifiService(  735): setWifiEnabled: true pid=3305, uid=10270
E/WifiService(  735): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3305): Radios toggled
I/jxcore-log( 3305): 
I/jxcore-log( 3305): My device name is: LGE-Nexus 5
I/jxcore-log( 3305): 
,I/wpa_supplicant( 1029): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  735): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  735): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
E/native  (  735): do suspend true
,D/CommandListener(  180): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1640): Read error: ssl=0xa4242e00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1640): SSL shutdown failed: ssl=0xa4242e00: I/O error during system call, Broken pipe
,D/ConnectivityService(  735): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): ValidatedState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): DefaultState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/ConnectivityService(  735): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  735): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,E/WifiConfigStore(  735): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiStateMachine(  735): Start Disconnecting Watchdog 1
,I/wpa_supplicant( 1029): wlan0: CTRL-EVENT-SCAN-STARTED 
,E/native  (  735): do suspend true
,D/CommandListener(  180): Clearing all IP addresses on wlan0
D/ConnectivityService(  735): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/Nat464Xlat(  735): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  735): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  735): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  735): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler(  901): CM callback handler got msg 524292
D/ConnectivityManager.CallbackHandler( 1684): CM callback handler got msg 524292
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/ConnectivityService(  735): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): EvaluatingState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): DefaultState{ when=-3ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Disconnected - quitting
,D/TelephonyNetworkFactory( 1252): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  735): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,D/WifiNetworkAgent(  735): NetworkAgent: NetworkAgent channel lost
,I/wpa_supplicant( 1029): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant( 1029): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1029): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1029): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  735): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  735): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  735): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiConfigStore(  735): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  180): Setting iface cfg
E/WifiStateMachine(  735): Start Dhcp Watchdog 2
,E/native  (  735): do suspend false
,E/WifiStateMachine(  735): scanCount==0 - aborting
,I/dhcpcd  ( 3402): version 5.5.6 starting
E/dhcpcd  ( 3402): get_duid: Read-only file system
,I/dhcpcd  ( 3402): wlan0: rebinding lease of 192.168.1.114
,I/dhcpcd  ( 3402): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,D/ConnectivityService(  735): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  735): MasterInitialState.processMessage what=3
,D/ConnectivityService(  735): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  735): MasterInitialState.processMessage what=3
,V/MusicLeanback( 2792): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,E/GpsLocationProvider(  735): No APN found to select.
,I/dhcpcd  ( 3402): wlan0: leased 192.168.1.114 for 86400 seconds
,I/SystemUpdateService( 1684): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1684): onCreate
,D/SystemUpdateService( 1684): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.Environment( 1684): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1684): num queued entries: 0
I/iu.UploadsManager( 1684): num updated entries: 0
I/iu.SyncManager( 1684): NEXT; no task
,I/SystemUpdateService( 1684): active receiver: enabled
,I/Babel   ( 1952): connection state changed from CONNECTED to DISCONNECTED
,I/SystemUpdateService( 1684): showing system update notification
,I/ActivityManager(  735): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3435 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/GpsLocationProvider(  735): No APN found to select.
,I/ValidateNoPeople(  735): skipping global notification
,V/SystemUpdateService( 1684): retry (wakeup: false) in 3599883 ms
,D/SystemUpdateService( 1684): onDestroy
,I/GAv4    ( 3435): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3435):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3435):   adb logcat -s GAv4
,W/GAv4    ( 3435): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3435): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3435): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,E/native  (  735): do suspend true
,D/ConnectivityService(  735): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService(  735): Adding iface wlan0 to network 101
E/WifiStateMachine(  735): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  735): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  735): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  735): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/ConnectivityService(  735): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  735): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  735): requiresClat: netType=1, connected=true, hasIPv4Address=true
,D/ConnectivityService(  735): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  735): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  735): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  735):    accepting network in place of null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/CSLegacyTypeTracker(  735): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,D/ConnectivityService(  735): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  735): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::5255:27ff:fef0:fd0b/64,192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  735): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  901): CM callback handler got msg 524290
D/ConnectivityManager.CallbackHandler( 1684): CM callback handler got msg 524290
,I/WebViewFactory( 3435): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3435): Time to load native libraries: 2 ms (timestamps 3501-3503)
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 27 Jan 2016 13:56:10 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1453902970979], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1453902970966]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Validated
I/LibraryLoader( 3435): Expected native library version number "",actual native library version number ""
D/ConnectivityService(  735): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  735): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  735): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  735): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  735): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler(  901): CM callback handler got msg 524290
D/TelephonyNetworkFactory( 1252): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1684): CM callback handler got msg 524290
,V/WebViewChromiumFactoryProvider( 3435): Binding Chromium to main looper Looper (main, tid 1) {38e56777}
,I/LibraryLoader( 3435): Expected native library version number "",actual native library version number ""
,I/chromium( 3435): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3435): Initializing chromium process, singleProcess=true
W/art     ( 3435): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3435): ApplicationContext is null in ApplicationStatus
,W/chromium( 3435): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3435): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3435): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3435): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/AudioManagerAndroid( 3435): Requires BLUETOOTH permission
,I/NSApplication( 3435): Starting up...
,I/ActivityManager(  735): Killing 2772:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/libprocessgroup(  735): failed to open /acct/uid_10003/pid_2772/cgroup.procs: No such file or directory
,V/MusicLeanback( 2792): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1684): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1684): onCreate
,D/SystemUpdateService( 1684): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.Environment( 1684): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/SystemUpdateService( 1684): active receiver: enabled
,I/iu.UploadsManager( 1684): num queued entries: 0
,I/iu.UploadsManager( 1684): num updated entries: 0
I/SystemUpdateService( 1684): showing system update notification
,I/iu.SyncManager( 1684): NEXT; no task
,I/ValidateNoPeople(  735): skipping global notification
,V/SystemUpdateService( 1684): retry (wakeup: false) in 3599945 ms
,D/SystemUpdateService( 1684): onDestroy
,I/Babel   ( 1952): connection state changed from DISCONNECTED to CONNECTED
,I/jxcore-log( 3305): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3305): 
,D/ConnectivityService(  735): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/jxcore-log( 3305): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 3305): 
,I/jxcore-log( 3305): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 3305): 
,I/jxcore-log( 3305): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 3305): 
,I/jxcore-log( 3305): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 3305): 
,I/jxcore-log( 3305): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 3305): 
,I/jxcore-log( 3305): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 3305): 
,I/jxcore-log( 3305): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3305): 
,D/ConnectivityService(  735): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  735): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2792): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2792): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,E/GpsLocationProvider(  735): No APN found to select.
,I/SystemUpdateService( 1684): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1684): onCreate
,D/SystemUpdateService( 1684): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1684): active receiver: enabled
,I/SystemUpdateService( 1684): showing system update notification
,I/ValidateNoPeople(  735): skipping global notification
,V/SystemUpdateService( 1684): retry (wakeup: false) in 3599979 ms
,D/SystemUpdateService( 1684): onDestroy
,I/jxcore-log( 3305): Test app app.js loaded
I/jxcore-log( 3305): 
,I/chromium( 3305): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3305): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 3305): BLE advertisement is supported
I/jxcore-log( 3305): 
,D/Finsky  ( 2676): [265] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2676): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/art     (  735): Explicit concurrent mark sweep GC freed 46367(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 27MB/41MB, paused 1.039ms total 57.071ms
,V/GLSActivity( 1640): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1640): Vacuum at: now=1453902984581 tag=VacuumService
,I/ClearcutLoggerApiImpl( 1640): disconnect managed GoogleApiClient
,I/jxcore-log( 3305): --= Surplus to requirements =--
I/jxcore-log( 3305): 
I/jxcore-log( 3305): ****TEST TOOK:  ms ****
I/jxcore-log( 3305): 
I/jxcore-log( 3305): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3305): 
,D/AndroidRuntime( 3601): 
D/AndroidRuntime( 3601): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 3601): CheckJNI is OFF
,D/AndroidRuntime( 3601): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  735): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  735): Killing 3305:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
,I/WindowState(  735): WIN DEATH: Window{28ac93ad u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  735): Client connection lost with reason: 4
,W/PackageSettings(  735): Skipping PackageSetting{30657b7 com.example.hello/10278} due to missing metadata
,I/ActivityManager(  735):   Force finishing activity ActivityRecord{192f1ce u0 com.test.thalitest/.MainActivity t216}
,I/ActivityManager(  735): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
,I/ActivityManager(  735):   Force finishing activity ActivityRecord{192f1ce u0 com.test.thalitest/.MainActivity t216 f}
W/ActivityManager(  735): Duplicate finish request for ActivityRecord{192f1ce u0 com.test.thalitest/.MainActivity t216 f}
,I/art     ( 1684): Explicit concurrent mark sweep GC freed 19088(1068KB) AllocSpace objects, 5(80KB) LOS objects, 24% free, 22MB/30MB, paused 462us total 32.585ms
,I/art     ( 1372): Explicit concurrent mark sweep GC freed 13433(950KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 19MB/25MB, paused 357us total 19.965ms
,I/art     ( 1295): Explicit concurrent mark sweep GC freed 3934(293KB) AllocSpace objects, 1(126KB) LOS objects, 23% free, 25MB/33MB, paused 226us total 19.940ms
,W/ActivityManager(  735): Spurious death for ProcessRecord{88e5087 3305:com.test.thalitest/u0a270}, curProc for 3305: null
,I/InputReader(  735): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1640): Ignoring removeGeofence because network location is disabled.
,I/Keyboard.Facilitator( 1102): resetDictionaries() : en_US
,D/NetworkChangeNotifierAutoDetect(  948): Network connectivity changed, type is: 2
,I/Keyboard.Facilitator.DecoderInitializer( 1102): run()
,I/Decoder ( 1102): createOrResetDecoder
,I/LibraryLoader( 1536): Loading chrome directly from within /data/app/com.android.chrome-1/base.apk
,D/VoicemailCleanupService( 2897): Cleaning up data for package: com.test.thalitest
,I/art     (  735): Explicit concurrent mark sweep GC freed 14211(927KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 4.962ms total 82.883ms
,I/art     (  735): WaitForGcToComplete blocked for 30.777ms for cause Explicit
,I/ConfigService( 1640): onCreate
,I/OpenGLRenderer(  948): Initialized EGL, version 1.4
,D/OpenGLRenderer(  948): Enabling debug mode 0
,W/Launcher( 1295): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@eb2f990 new=com.google.android.velvet.VelvetApplication@eb2f990
,I/UpdateIcingCorporaServi( 1372): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,W/art     (  948): Attempt to remove local handle scope entry from IRT, ignoring
,I/LibraryLoader( 1536): Time to load native libraries: 80 ms (timestamps 3750-3830)
I/LibraryLoader( 1536): Expected native library version number "44.0.2403.133",actual native library version number "44.0.2403.133"
I/ActivityManager(  735): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3643 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
I/chromium( 1536): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
W/art     ( 1536): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 1536): Attempt to remove local handle scope entry from IRT, ignoring
,D/BackupManagerService(  735): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  735): Receieved: android.intent.action.PACKAGE_REMOVED
,I/EventLogService( 1684): Aggregate from 1453901373080 (log), 1453901373080 (data)
,D/TaskPersister(  735): removeObsoleteFile: deleting file=216_task.xml
,W/InputMethodManagerService(  735): Focus gain on non-focused client com.android.internal.view.IInputMethodClient$Stub$Proxy@2ac5e7d1 (uid=10034 pid=948)
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1102): run()
,W/ContextImpl( 3643): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1102): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1102): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1102): run() : Loading LM = contacts
,I/art     (  735): Explicit concurrent mark sweep GC freed 5735(298KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 2.197ms total 178.355ms
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1102): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1102): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1102): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1102): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1102): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1102): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1102): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1102): run()
I/StatsUtilsManager( 1102): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1102): shouldRecordStats() = Too Soon
,D/PackageBroadcastService( 1684): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1684): Clearing selected account for com.test.thalitest
,I/ActivityManager(  735): Killing 2753:com.android.settings/1000 (adj 15): empty #17
,I/UpdateIcingCorporaServi( 1372): UpdateCorporaTask done [took 167 ms] updated apps [took 167 ms] 
,D/WifiService(  735): Client connection lost with reason: 4
,D/AndroidRuntime( 3601): Shutting down VM
,W/libprocessgroup(  735): failed to open /acct/uid_1000/pid_2753/cgroup.procs: No such file or directory
I/Launcher( 1295): Deferring update until onResume
,D/ChimeraCfgMgr( 1684): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1684): Module APK com.google.android.play.games already loaded
,I/LocationSettingsChecker( 1684): Removing dialog suppression flag for package com.test.thalitest
,D/ChimeraCfgMgr( 1684): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1684): Module APK com.google.android.play.games already loaded
,W/ResourcesManager( 1295): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,E/NetworkScheduler.SchedulerReceiver( 1640): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1640): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,D/gH_CompatibleDatabase( 1684): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,D/gH_CompatibleDatabase( 1684): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 1684): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1684): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,W/ResourcesManager( 1295): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/gH_CompatibleDatabase( 1684): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1684): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/gH_CompatibleDatabase( 1684): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,I/Launcher( 1295): Deferring update until onResume
,D/gH_CompatibleDatabase( 1684): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1684): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 1684): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,D/gH_CompatibleDatabase( 1684): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1684): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1684): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/ActivityManager(  735): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=3685 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,W/BaseAppContext( 1684): Using Auth Proxy for data requests.
,W/BaseAppContext( 1684): Using Auth Proxy for data requests.
,I/GMPM-SVC( 1684): App measurement is starting up, version: 8489
I/GMPM-SVC( 1684): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,I/Icing   ( 1684): doRemovePackageData com.test.thalitest
,I/GAv4    ( 3685): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3685):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3685):   adb logcat -s GAv4
,W/GAv4    ( 3685): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3685): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3685): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  735): Killing 2602:com.google.android.gm/u0a70 (adj 15): empty #17
,W/libprocessgroup(  735): failed to open /acct/uid_10070/pid_2602/cgroup.procs: No such file or directory
,I/ActivityManager(  735): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3716 uid=10039 gids={50039, 9997} abi=armeabi-v7a
,E/SQLiteDatabase( 3716): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 3716): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3716): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3716): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 3716): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 3716): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3716): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3716): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3716): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 3716): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 3716): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 3716): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/SQLiteDatabase( 3716): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 3716): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 3716): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 3716): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/SQLiteDatabase( 3716): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/SQLiteDatabase( 3716): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:367)
E/SQLiteDatabase( 3716): 	at android.content.ContentResolver.call(ContentResolver.java:1372)
E/SQLiteDatabase( 3716): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/SQLiteDatabase( 3716): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2579)
E/SQLiteDatabase( 3716): 	at android.app.ActivityThread.access$1700(ActivityThread.java:144)
E/SQLiteDatabase( 3716): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1355)
E/SQLiteDatabase( 3716): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 3716): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 3716): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/SQLiteDatabase( 3716): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 3716): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 3716): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/SQLiteDatabase( 3716): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
,D/AndroidRuntime( 3716): Shutting down VM
--------- beginning of crash
E/AndroidRuntime( 3716): FATAL EXCEPTION: main
E/AndroidRuntime( 3716): Process: com.android.documentsui, PID: 3716
E/AndroidRuntime( 3716): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 3716): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2586)
E/AndroidRuntime( 3716): 	at android.app.ActivityThread.access$1700(ActivityThread.java:144)
E/AndroidRuntime( 3716): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1355)
E/AndroidRuntime( 3716): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 3716): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 3716): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/AndroidRuntime( 3716): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 3716): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 3716): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/AndroidRuntime( 3716): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
E/AndroidRuntime( 3716): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 3716): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 3716): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 3716): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 3716): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 3716): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 3716): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 3716): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AndroidRuntime( 3716): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AndroidRuntime( 3716): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 3716): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/AndroidRuntime( 3716): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 3716): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 3716): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 3716): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/AndroidRuntime( 3716): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/AndroidRuntime( 3716): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:367)
E/AndroidRuntime( 3716): 	at android.content.ContentResolver.call(ContentResolver.java:1372)
E/AndroidRuntime( 3716): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/AndroidRuntime( 3716): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2579)
E/AndroidRuntime( 3716): 	... 9 more
,I/ActivityManager(  735): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3735 uid=10007 gids={50007, 9997, 1028, 1015, 1023} abi=armeabi-v7a
I/ActivityManager(  735): Killing 2013:com.google.android.calendar/u0a31 (adj 15): empty #17

```
