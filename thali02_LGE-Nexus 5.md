#### Test 549702617d40def_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
D/Finsky  ( 2700): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
W/ResourcesManager( 3227): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3227): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  756): Killing 2122:com.google.android.deskclock/u0a38 (adj 15): empty #17
V/JNIHelp ( 3227): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/System  ( 3227): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3227): Installed default security provider GmsCore_OpenSSL
W/libprocessgroup(  756): failed to open /acct/uid_10038/pid_2122/cgroup.procs: No such file or directory
V/GLSActivity( 1573): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 1661): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/Icing   ( 1661): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1661): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/Icing   ( 1661): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
,I/ActivityManager(  756): Killing 2601:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
D/AndroidRuntime( 3282): 
D/AndroidRuntime( 3282): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3282): CheckJNI is OFF
W/libprocessgroup(  756): failed to open /acct/uid_10045/pid_2601/cgroup.procs: No such file or directory
D/AndroidRuntime( 3282): Calling main entry com.android.commands.am.Am
I/ActivityManager(  756): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  756): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3316 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3282): Shutting down VM
V/ActivityManager(  756): Display changed displayId=0
I/WebViewFactory( 3316): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3316): Time to load native libraries: 1 ms (timestamps 8548-8549)
I/LibraryLoader( 3316): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3316): Binding Chromium to main looper Looper (main, tid 1) {3f30f90f}
,I/LibraryLoader( 3316): Expected native library version number "",actual native library version number ""
,I/chromium( 3316): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3316): Initializing chromium process, singleProcess=true
,W/art     ( 3316): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3316): ApplicationContext is null in ApplicationStatus
,W/chromium( 3316): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3316): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3316): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3316): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  756): Message: 20
D/BluetoothManagerService(  756): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a431d62:true
,W/art     ( 3316): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3316): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3316): CordovaWebView is running on device made by: LGE
,W/art     ( 3316): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3316): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3316): Render dirty regions requested: true
,D/Atlas   ( 3316): Validating map...
,W/chromium( 3316): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3316): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3316): Enabling debug mode 0
,W/IInputConnectionWrapper( 3316): showStatusIcon on inactive InputConnection
,I/ActivityManager(  756): Displayed com.test.thalitest/.MainActivity: +491ms (total +55s955ms)
,W/BindingManager( 3316): Cannot call determinedVisibility() - never saw a connection for the pid: 3316
,D/JsMessageQueue( 3316): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3316): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257342720
,D/JX-Cordova( 3316): jxcore cordova android initializing
,W/jxcore-log( 3316): Initializing JXcore engine
W/jxcore-log( 3316): JXcore engine is ready
,W/jxcore-log( 3316): Starting JXcore engine
,W/.test.thalitest( 3316): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[9418]" dev="sockfs" ino=9418 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3316): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 3316): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6544]" dev="sockfs" ino=6544 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3316): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[17962]" dev="sockfs" ino=17962 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3316): Platform android
W/jxcore-log( 3316): 
W/jxcore-log( 3316): Process ARCH arm
W/jxcore-log( 3316): 
,I/jxcore-log( 3316): JXcore Cordova bridge is ready!
I/jxcore-log( 3316): 
,W/jxcore-log( 3316): JXcore engine is started
I/Choreographer( 3316): Skipped 108 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3316): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3316): Toggling radios to true
I/jxcore-log( 3316): 
,D/BluetoothAdapter( 3316): enable(): BT is already enabled..!
,D/WifiService(  756): New client listening to asynchronous messages
D/WifiService(  756): setWifiEnabled: true pid=3316, uid=10270
E/WifiService(  756): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3316): Radios toggled
I/jxcore-log( 3316): 
,I/wpa_supplicant(  989): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  756): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  756): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/native  (  756): do suspend true
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,E/WifiConfigStore(  756): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  756): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  756): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,V/NativeCrypto( 1573): Read error: ssl=0xafe63e00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1573): SSL shutdown failed: ssl=0xafe63e00: I/O error during system call, Broken pipe
,D/ConnectivityService(  756): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): ValidatedState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): DefaultState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): Checking http://clients3.google.com/generate_204 on <unknown ssid>
,E/WifiStateMachine(  756): Start Disconnecting Watchdog 1
,E/native  (  756): do suspend true
,I/wpa_supplicant(  989): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/CommandListener(  179): Clearing all IP addresses on wlan0
D/ConnectivityService(  756): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/Nat464Xlat(  756): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  756): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  756): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  756): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  756): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler(  902): CM callback handler got msg 524292
D/TelephonyNetworkFactory( 1217): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): EvaluatingState{ when=-3ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): DefaultState{ when=-3ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): Disconnected - quitting
,D/ConnectivityManager.CallbackHandler( 1661): CM callback handler got msg 524292
,D/WifiNetworkAgent(  756): NetworkAgent: NetworkAgent channel lost
,I/wpa_supplicant(  989): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant(  989): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant(  989): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant(  989): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  756): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  756): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  756): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiConfigStore(  756): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/CommandListener(  179): Setting iface cfg
E/WifiStateMachine(  756): Start Dhcp Watchdog 2
,E/native  (  756): do suspend false
,E/WifiStateMachine(  756): scanCount==0 - aborting
,I/dhcpcd  ( 3397): version 5.5.6 starting
E/dhcpcd  ( 3397): get_duid: Read-only file system
,I/dhcpcd  ( 3397): wlan0: rebinding lease of 192.168.1.114
,W/NetworkUtils( 1380): OkHttp exception
W/EventLoggerService( 1380): Unable to send logs Error code: 262146
,I/dhcpcd  ( 3397): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3397): wlan0: leased 192.168.1.114 for 86400 seconds
,D/ConnectivityService(  756): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  756): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  756): MasterInitialState.processMessage what=3
,D/Tethering(  756): MasterInitialState.processMessage what=3
,V/MusicLeanback( 2820): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,E/GpsLocationProvider(  756): No APN found to select.
,I/SystemUpdateService( 1661): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1661): onCreate
,D/SystemUpdateService( 1661): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.Environment( 1661): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1661): num queued entries: 0
I/iu.UploadsManager( 1661): num updated entries: 0
I/iu.SyncManager( 1661): NEXT; no task
,I/SystemUpdateService( 1661): active receiver: enabled
,I/SystemUpdateService( 1661): showing system update notification
E/GpsLocationProvider(  756): No APN found to select.
,I/Babel   ( 1964): connection state changed from CONNECTED to DISCONNECTED
,I/ActivityManager(  756): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3434 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ValidateNoPeople(  756): skipping global notification
,V/SystemUpdateService( 1661): retry (wakeup: false) in 3599915 ms
,E/native  (  756): do suspend true
,D/SystemUpdateService( 1661): onDestroy
,D/ConnectivityService(  756): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  756): Adding iface wlan0 to network 101
E/WifiStateMachine(  756): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  756): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  756): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/ConnectivityService(  756): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/ConnectivityService(  756): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/ConnectivityService(  756): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  756): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  756): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  756): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  756): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  756):    accepting network in place of null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/CSLegacyTypeTracker(  756): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  756): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  756): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  756): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler(  902): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1661): CM callback handler got msg 524290
,I/GAv4    ( 3434): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3434):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3434):   adb logcat -s GAv4
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 05 Jan 2016 01:20:39 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1451956839260], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1451956839238]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  756): Validated
,D/ConnectivityService(  756): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  756): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  756): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  756): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler(  902): CM callback handler got msg 524290
,D/ConnectivityService(  756): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1661): CM callback handler got msg 524290
D/TelephonyNetworkFactory( 1217): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,W/GAv4    ( 3434): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3434): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3434): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/Nat464Xlat(  756): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  756): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  902): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 1661): CM callback handler got msg 524295
,I/WebViewFactory( 3434): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3434): Time to load native libraries: 1 ms (timestamps 4565-4566)
,I/LibraryLoader( 3434): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3434): Binding Chromium to main looper Looper (main, tid 1) {2fecafa9}
,I/LibraryLoader( 3434): Expected native library version number "",actual native library version number ""
I/chromium( 3434): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3434): Initializing chromium process, singleProcess=true
W/art     ( 3434): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3434): ApplicationContext is null in ApplicationStatus
,W/chromium( 3434): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3434): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 3434): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3434): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/AudioManagerAndroid( 3434): Requires BLUETOOTH permission
,I/NSApplication( 3434): Starting up...
,I/ActivityManager(  756): Killing 2794:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/libprocessgroup(  756): failed to open /acct/uid_10003/pid_2794/cgroup.procs: No such file or directory
,V/MusicLeanback( 2820): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1661): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1661): onCreate
,D/SystemUpdateService( 1661): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1661): active receiver: enabled
,I/SystemUpdateService( 1661): showing system update notification
,I/iu.Environment( 1661): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1661): num queued entries: 0
I/iu.UploadsManager( 1661): num updated entries: 0
I/iu.SyncManager( 1661): NEXT; no task
,I/ValidateNoPeople(  756): skipping global notification
,V/SystemUpdateService( 1661): retry (wakeup: false) in 3599970 ms
,D/SystemUpdateService( 1661): onDestroy
,I/Babel   ( 1964): connection state changed from DISCONNECTED to CONNECTED
,D/ConnectivityService(  756): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/jxcore-log( 3316): Test app app.js loaded
I/jxcore-log( 3316): 
,I/Choreographer( 3316): Skipped 372 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3316): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/ConnectivityService(  756): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  756): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2820): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2820): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1661): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1661): onCreate
,D/SystemUpdateService( 1661): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1661): active receiver: enabled
,I/SystemUpdateService( 1661): showing system update notification
I/ValidateNoPeople(  756): skipping global notification
,V/SystemUpdateService( 1661): retry (wakeup: false) in 3599984 ms
,I/art     (  756): Explicit concurrent mark sweep GC freed 42475(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 27MB/41MB, paused 1.048ms total 68.574ms
,E/GpsLocationProvider(  756): No APN found to select.
,D/SystemUpdateService( 1661): onDestroy
,E/ActivityThread( 1661): Failed to find provider info for com.android.contacts.metadata
,D/SyncManager(  756): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 65213, reason: UserStart, SyncResult: databaseError: true stats []
D/SyncManager(  756): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 119587, reason: UserStart
,D/Finsky  ( 2700): [265] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2700): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/GLSActivity( 1573): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1573): Vacuum at: now=1451956854251 tag=VacuumService
,I/PhenotypeConfigurator( 1573): Scheduling Phenotype for one-off execution 13821 seconds from now (1451956854556)
,D/GetConfigurationSnapshotOperation( 1573): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1573): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1573): Using platform SSLCertificateSocketFactory
,I/ClearcutLoggerApiImpl( 1573): disconnect managed GoogleApiClient
,I/ActivityManager(  756): Killing 2766:com.android.settings/1000 (adj 15): empty #17
,D/WifiService(  756): Client connection lost with reason: 4
,W/libprocessgroup(  756): failed to open /acct/uid_1000/pid_2766/cgroup.procs: No such file or directory
,I/ActivityManager(  756): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=3595 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,I/GAv4    ( 3595): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3595):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3595):   adb logcat -s GAv4
,W/GAv4    ( 3595): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3595): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3595): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  756): Killing 2635:com.google.android.gm/u0a70 (adj 15): empty #17
,W/libprocessgroup(  756): failed to open /acct/uid_10070/pid_2635/cgroup.procs: No such file or directory
,W/bt-smp  ( 2149): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2149): Plain text(LSB ~ MSB) = 2e d9 5d 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2149): Encrypted text(LSB ~ MSB) = 99 63 b1 73 f3 d3 df 9b 24 6e 68 45 bd 19 62 d4 
,W/bt-btm  ( 2149): Stopping oneshot timer
,I/EventLogService( 1661): Aggregate from 1451955901792 (log), 1451955901792 (data)
,I/UsageStatsService(  756): User[0] Flushing usage stats to disk
,I/ProcessStatsService(  756): Prepared write state in 10ms
,I/ProcessStatsService(  756): Prepared write state in 2ms
I/ProcessStatsService(  756): Prepared write state in 2ms
,W/bt-smp  ( 2149): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2149): Plain text(LSB ~ MSB) = b0 4e 50 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2149): Encrypted text(LSB ~ MSB) = 60 2f 9c b2 40 57 28 04 65 c7 41 c6 42 b5 e9 e2 
W/bt-btm  ( 2149): Stopping oneshot timer
,I/ProcessStatsService(  756): Pruning old procstats: /data/system/procstats/state-2016-01-04-02-30-26.bin
,I/ActivityManager(  756): Killing 3197:com.android.musicfx/u0a15 (adj 13): empty for 1809s
,I/ActivityManager(  756): Killing 2296:com.google.android.partnersetup/u0a13 (adj 13): empty for 1809s
,I/ActivityManager(  756): Killing 2942:android.process.acore/u0a4 (adj 13): empty for 1809s
,I/ActivityManager(  756): Killing 3112:com.google.android.gms:car/u0a8 (adj 13): empty for 1815s
,I/ActivityManager(  756): Killing 2080:com.android.providers.calendar/u0a2 (adj 15): empty for 1815s
,I/ActivityManager(  756): Killing 2060:com.google.android.calendar/u0a31 (adj 15): empty for 1845s
,W/libprocessgroup(  756): failed to open /acct/uid_10015/pid_3197/cgroup.procs: No such file or directory
,W/libprocessgroup(  756): failed to open /acct/uid_10004/pid_2942/cgroup.procs: No such file or directory
,W/libprocessgroup(  756): failed to open /acct/uid_10008/pid_3112/cgroup.procs: No such file or directory
,W/libprocessgroup(  756): failed to open /acct/uid_10002/pid_2080/cgroup.procs: No such file or directory
,W/libprocessgroup(  756): failed to open /acct/uid_10031/pid_2060/cgroup.procs: No such file or directory
,W/libprocessgroup(  756): failed to open /acct/uid_10013/pid_2296/cgroup.procs: No such file or directory
,V/GLSActivity( 1573): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1573): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1573): Explicit concurrent mark sweep GC freed 91873(5MB) AllocSpace objects, 27(455KB) LOS objects, 39% free, 23MB/38MB, paused 1.023ms total 54.217ms
,I/ActivityManager(  756): Killing 3227:com.google.android.apps.docs/u0a40 (adj 15): empty for 1809s
,W/libprocessgroup(  756): failed to open /acct/uid_10040/pid_3227/cgroup.procs: No such file or directory
,TIME-OUT KILL (timeout was 1800000ms)
```
