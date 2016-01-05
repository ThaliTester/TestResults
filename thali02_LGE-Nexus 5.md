#### Test 549702610263d9b_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
D/ChimeraCfgMgr( 1633): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1633): Module APK com.google.android.play.games already loaded
I/GAv4    ( 3190): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3190):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3190):   adb logcat -s GAv4
W/GAv4    ( 3190): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3190): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3190): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 3190): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
D/Finsky  ( 2587): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
W/ResourcesManager( 3190): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3190): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/JNIHelp ( 3190): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/ActivityManager(  732): Killing 2553:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
W/System  ( 3190): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3190): Installed default security provider GmsCore_OpenSSL
W/libprocessgroup(  732): failed to open /acct/uid_10069/pid_2553/cgroup.procs: No such file or directory
V/GLSActivity( 1563): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 1633): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/Icing   ( 1633): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1633): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/Icing   ( 1633): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
,D/AndroidRuntime( 3244): 
D/AndroidRuntime( 3244): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3244): CheckJNI is OFF
D/AndroidRuntime( 3244): Calling main entry com.android.commands.am.Am
I/ActivityManager(  732): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  732): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3268 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3244): Shutting down VM
V/ActivityManager(  732): Display changed displayId=0
I/ActivityManager(  732): Killing 2507:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
I/WebViewFactory( 3268): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
W/libprocessgroup(  732): failed to open /acct/uid_10045/pid_2507/cgroup.procs: No such file or directory
I/LibraryLoader( 3268): Time to load native libraries: 2 ms (timestamps 8807-8809)
I/LibraryLoader( 3268): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3268): Binding Chromium to main looper Looper (main, tid 1) {244f2efd}
,I/LibraryLoader( 3268): Expected native library version number "",actual native library version number ""
,I/chromium( 3268): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3268): Initializing chromium process, singleProcess=true
W/art     ( 3268): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3268): ApplicationContext is null in ApplicationStatus
,W/chromium( 3268): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3268): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3268): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3268): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  732): Message: 20
,D/BluetoothManagerService(  732): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@32052f7a:true
,W/art     ( 3268): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3268): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3268): CordovaWebView is running on device made by: LGE
,W/art     ( 3268): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3268): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3268): Render dirty regions requested: true
,D/Atlas   ( 3268): Validating map...
,W/chromium( 3268): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3268): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3268): Enabling debug mode 0
,W/BindingManager( 3268): Cannot call determinedVisibility() - never saw a connection for the pid: 3268
,W/IInputConnectionWrapper( 3268): showStatusIcon on inactive InputConnection
,I/ActivityManager(  732): Displayed com.test.thalitest/.MainActivity: +540ms (total +57s669ms)
,D/JsMessageQueue( 3268): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3268): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257343360
,D/JX-Cordova( 3268): jxcore cordova android initializing
,W/jxcore-log( 3268): Initializing JXcore engine
,W/jxcore-log( 3268): JXcore engine is ready
,W/jxcore-log( 3268): Starting JXcore engine
,W/.test.thalitest( 3268): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[8117]" dev="sockfs" ino=8117 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3268): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 3268): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[9503]" dev="sockfs" ino=9503 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3268): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[20672]" dev="sockfs" ino=20672 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3268): Platform android
W/jxcore-log( 3268): 
W/jxcore-log( 3268): Process ARCH arm
W/jxcore-log( 3268): 
,I/jxcore-log( 3268): JXcore Cordova bridge is ready!
I/jxcore-log( 3268): 
W/jxcore-log( 3268): JXcore engine is started
I/Choreographer( 3268): Skipped 116 frames!  The application may be doing too much work on its main thread.
I/chromium( 3268): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3268): Toggling radios to true
I/jxcore-log( 3268): 
,D/BluetoothAdapter( 3268): enable(): BT is already enabled..!
,D/WifiService(  732): New client listening to asynchronous messages
,D/WifiService(  732): setWifiEnabled: true pid=3268, uid=10270
E/WifiService(  732): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3268): Radios toggled
I/jxcore-log( 3268): 
,I/wpa_supplicant(  985): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  732): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  732): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/native  (  732): do suspend true
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1563): Read error: ssl=0xb404ae00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1563): SSL shutdown failed: ssl=0xb404ae00: I/O error during system call, Broken pipe
,D/ConnectivityService(  732): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  732): ValidatedState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  732): DefaultState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  732): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  732): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  732): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  732): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/ConnectivityService(  732): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  732): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
E/WifiConfigStore(  732): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
E/WifiStateMachine(  732): Start Disconnecting Watchdog 1
,I/wpa_supplicant(  985): wlan0: CTRL-EVENT-SCAN-STARTED 
,E/native  (  732): do suspend true
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,D/ConnectivityService(  732): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler(  896): CM callback handler got msg 524292
,D/ConnectivityManager.CallbackHandler( 1633): CM callback handler got msg 524292
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  732): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  732): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  732): Disconnected - quitting
,D/Nat464Xlat(  732): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  732): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  732): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/WifiNetworkAgent(  732): NetworkAgent: NetworkAgent channel lost
,D/ConnectivityService(  732): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  732): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1240): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/ConnectivityService(  732): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,V/GLSActivity( 1563): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1563): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/NetworkUtils( 1365): OkHttp exception
W/EventLoggerService( 1365): Unable to send logs Error code: 262146
,I/wpa_supplicant(  985): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant(  985): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant(  985): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant(  985): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  732): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  732): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  732): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  732): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  179): Setting iface cfg
,E/WifiStateMachine(  732): Start Dhcp Watchdog 2
,E/native  (  732): do suspend false
,E/WifiStateMachine(  732): scanCount==0 - aborting
,I/dhcpcd  ( 3358): version 5.5.6 starting
,E/dhcpcd  ( 3358): get_duid: Read-only file system
,I/dhcpcd  ( 3358): wlan0: rebinding lease of 192.168.1.114
,D/ConnectivityService(  732): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  732): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  732): MasterInitialState.processMessage what=3
,D/Tethering(  732): MasterInitialState.processMessage what=3
,V/MusicLeanback( 2706): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1633): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1633): onCreate
,D/SystemUpdateService( 1633): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.Environment( 1633): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1633): num queued entries: 0
I/iu.UploadsManager( 1633): num updated entries: 0
I/iu.SyncManager( 1633): NEXT; no task
,I/ActivityManager(  732): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3366 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Babel   ( 1882): connection state changed from CONNECTED to DISCONNECTED
,I/SystemUpdateService( 1633): active receiver: enabled
,I/SystemUpdateService( 1633): showing system update notification
,E/GpsLocationProvider(  732): No APN found to select.
,E/GpsLocationProvider(  732): No APN found to select.
,I/ValidateNoPeople(  732): skipping global notification
,V/SystemUpdateService( 1633): retry (wakeup: false) in 3599981 ms
,D/SystemUpdateService( 1633): onDestroy
,I/GAv4    ( 3366): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3366):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3366):   adb logcat -s GAv4
,W/GAv4    ( 3366): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3366): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3366): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 3366): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3366): Time to load native libraries: 1 ms (timestamps 5085-5086)
,I/LibraryLoader( 3366): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3366): Binding Chromium to main looper Looper (main, tid 1) {1831ad81}
,I/LibraryLoader( 3366): Expected native library version number "",actual native library version number ""
I/chromium( 3366): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3366): Initializing chromium process, singleProcess=true
W/art     ( 3366): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3366): ApplicationContext is null in ApplicationStatus
,W/chromium( 3366): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3366): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3366): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3366): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/AudioManagerAndroid( 3366): Requires BLUETOOTH permission
,I/NSApplication( 3366): Starting up...
,I/ActivityManager(  732): Killing 2686:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/libprocessgroup(  732): failed to open /acct/uid_10003/pid_2686/cgroup.procs: No such file or directory
,V/MusicLeanback( 2706): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1633): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
D/SystemUpdateService( 1633): onCreate
D/SystemUpdateService( 1633): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1633): active receiver: enabled
,I/SystemUpdateService( 1633): showing system update notification
,I/ValidateNoPeople(  732): skipping global notification
,V/SystemUpdateService( 1633): retry (wakeup: false) in 3599980 ms
,D/SystemUpdateService( 1633): onDestroy
,I/dhcpcd  ( 3358): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3358): wlan0: leased 192.168.1.114 for 86400 seconds
,E/native  (  732): do suspend true
,D/ConnectivityService(  732): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  732): Adding iface wlan0 to network 101
,E/WifiStateMachine(  732): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  732): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  732): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  732): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  732): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  732): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  732): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  732): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  732): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  732): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  732):    accepting network in place of null
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  732): DefaultState{ when=-2ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  732): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  732): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  732): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/CSLegacyTypeTracker(  732): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  732): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  732): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::5255:27ff:fef0:fd0b/64,192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService(  732): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1633): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler(  896): CM callback handler got msg 524290
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  732): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 05 Jan 2016 17:32:33 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452015153356], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452015153344]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  732): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  732): Validated
D/ConnectivityService(  732): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  732): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  732): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  732): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  732): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/TelephonyNetworkFactory( 1240): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler(  896): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1633): CM callback handler got msg 524290
,I/jxcore-log( 3268): Test app app.js loaded
I/jxcore-log( 3268): 
,I/chromium( 3268): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/ConnectivityService(  732): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,D/ConnectivityService(  732): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  732): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2706): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2706): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1633): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1633): onCreate
D/SystemUpdateService( 1633): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
I/iu.Environment( 1633): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1633): num queued entries: 0
I/iu.UploadsManager( 1633): num updated entries: 0
I/iu.SyncManager( 1633): NEXT; no task
,I/SystemUpdateService( 1633): active receiver: enabled
,I/SystemUpdateService( 1633): showing system update notification
,I/ValidateNoPeople(  732): skipping global notification
,V/SystemUpdateService( 1633): retry (wakeup: false) in 3599973 ms
,I/art     (  732): Explicit concurrent mark sweep GC freed 43887(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 27MB/41MB, paused 954us total 71.783ms
,D/SystemUpdateService( 1633): onDestroy
D/ConnectivityService(  732): reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10008
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  732): ValidatedState{ when=-1ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  732): DefaultState{ when=-1ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  732): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  732): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  732): Checking http://clients3.google.com/generate_204 on "NG7005g"
,I/Babel   ( 1882): connection state changed from DISCONNECTED to CONNECTED
,E/GpsLocationProvider(  732): No APN found to select.
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  732): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 05 Jan 2016 17:32:36 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452015156444], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452015156426]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  732): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  732): Validated
D/ConnectivityService(  732): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  732): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  732): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  732): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  896): CM callback handler got msg 524290
D/ConnectivityManager.CallbackHandler( 1633): CM callback handler got msg 524290
,D/Finsky  ( 2587): [260] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2587): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/GLSActivity( 1563): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1563): Vacuum at: now=1452015163837 tag=VacuumService
,I/ClearcutLoggerApiImpl( 1563): disconnect managed GoogleApiClient
,I/jxcore-log( 3268): TAP version 13
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): # setup
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): # multiplex can send data
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): # teardown
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): ok 1 String should be length:200
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): # setup
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): # basic
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): # teardown
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): ok 2 sane
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): # setup
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): # another
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): # teardown
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): ok 3 sane
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): # setup
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): # successfully create a new pkcs12 file and return hash value
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): # teardown
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): ok 4 should be equal
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): ok 5 null
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): ok 6 (unnamed assert)
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): ok 7 should be equal
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): ok 8 should not throw
I/jxcore-log( 3268): 
I/jxcore-log( 3268): # setup
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): # successfully read a previous pkcs12 file and return hash value
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): # teardown
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): ok 9 (unnamed assert)
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): ok 10 (unnamed assert)
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): ok 11 should not throw
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): ok 12 should be equal
I/jxcore-log( 3268): 
I/jxcore-log( 3268): ok 13 should be equal
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): # setup
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): # failed to extract public key because of corrupt pkcs12 file
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): # teardown
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): ok 14 should be equal
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): # setup
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): # failed to get mobile documents path
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): # teardown
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): ok 15 should be equal
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): # setup
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): # #init should register the peerAvailabilityChanged event
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): # teardown
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): ok 16 should be equal
I/jxcore-log( 3268): 
I/jxcore-log( 3268): ok 17 should be equal
I/jxcore-log( 3268): 
I/jxcore-log( 3268): ok 18 should be equal
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): # setup
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): # #init should register the networkChanged event
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): # teardown
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): ok 19 should be equal
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): # setup
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): # #startBroadcasting should throw on null device name
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): # teardown
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): ok 20 should throw
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): # setup
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): # #startBroadcasting should throw on empty string device name
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): # teardown
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): ok 21 should throw
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): # setup
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): # #startBroadcasting should throw on non-number port
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): # teardown
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): ok 22 should throw
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): # setup
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): # #startBroadcasting should throw on NaN port
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): # teardown
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): ok 23 should throw
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): # setup
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): # #startBroadcasting should throw on negative port
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): # teardown
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): ok 24 should throw
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): # setup
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): # #startBroadcasting should throw on too large port
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): # teardown
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): ok 25 should throw
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): # setup
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): # #startBroadcasting should call Mobile("StartBroadcasting") without an error
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): # teardown
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): ok 26 should be equal
I/jxcore-log( 3268): 
I/jxcore-log( 3268): ok 27 should be equal
I/jxcore-log( 3268): 
I/jxcore-log( 3268): ok 28 should be equal
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): # setup
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): # #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): # teardown
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): ok 29 should be equal
I/jxcore-log( 3268): 
I/jxcore-log( 3268): ok 30 should be equal
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): ok 31 should be equal
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): # setup
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): # #stopBroadcasting should call Mobile("StopBroadcasting") without an error
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): # teardown
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): ok 32 should be equal
I/jxcore-log( 3268): 
I/jxcore-log( 3268): ok 33 should be equal
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): # setup
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): # #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): # teardown
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): ok 34 should be equal
I/jxcore-log( 3268): 
I/jxcore-log( 3268): ok 35 should be equal
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): # setup
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): # #connect should call Mobile("Connect") with a port and without an error
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): # teardown
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): ok 36 should be equal
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): ok 37 should be equal
I/jxcore-log( 3268): 
I/jxcore-log( 3268): ok 38 should be equal
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): # setup
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): # #connect should call Mobile("Connect") and handle an error
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): # teardown
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): ok 39 should be equal
I/jxcore-log( 3268): 
I/jxcore-log( 3268): ok 40 should be equal
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): # setup
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): # should call Mobile("Disconnect") without an error
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): # teardown
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): ok 41 should be equal
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): ok 42 should be equal
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): # setup
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): # should call Mobile("Disconnect") and handle an error
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): # teardown
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): ok 43 should be equal
I/jxcore-log( 3268): 
I/jxcore-log( 3268): ok 44 should be equal
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): # setup
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): # ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
I/jxcore-log( 3268): 
,I/jxcore-log( 3268): # teardown
I/jxcore-log( 3268): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): setDiscoveryMode: Mode set to WIFI
,D/BluetoothManagerService(  732): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3268): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452015606651.3268
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3268): bind: Binding a new listener
,D/BluetoothManagerService(  732): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3268): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  732): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3268): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1452015606651.3268","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3268): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3268): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3268): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  732): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3268): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3268): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3268): start: OK
I/io.jxcore.node.ConnectionHelper( 3268): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  732): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452015606651.3268
,D/BluetoothManagerService(  732): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3268): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1452015606651.3268","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3268): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3268): start: {"pi":"34:FC:EF:11:AE:67","pn":"1452015606651.3268","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3268): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1452015606651.3268","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3268): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3268): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3268): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3268): start: OK
I/jxcore-log( 3268): ok 45 Should be able to call startBroadcasting without error
I/jxcore-log( 3268): 
I/io.jxcore.node.ConnectionHelper( 3268): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3268): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3268): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3268): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3268): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3268): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3268): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3268): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3268): setState: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3268): stop: Stopping services
,I/wpa_supplicant(  985): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3268): stop: Stopping P2P device discovery...
,I/wpa_supplicant(  985): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3268): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3268): release: No more listeners, de-initializing...
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3268): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3268): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): setState: NOT_STARTED
,I/jxcore-log( 3268): ok 46 Should be able to call stopBroadcasting without error
I/jxcore-log( 3268): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): setDiscoveryMode: Mode set to WIFI
,D/BluetoothManagerService(  732): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3268): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452015606808.3268
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3268): bind: Binding a new listener
,D/BluetoothManagerService(  732): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3268): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  732): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3268): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1452015606808.3268","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3268): setConnectionTimeout: 15000
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3268): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3268): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  732): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 3268): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3268): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3268): start: OK
I/io.jxcore.node.ConnectionHelper( 3268): start: Using peer discovery mode: WIFI
,D/BluetoothManagerService(  732): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452015606808.3268
,D/BluetoothManagerService(  732): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3268): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1452015606808.3268","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3268): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3268): start: {"pi":"34:FC:EF:11:AE:67","pn":"1452015606808.3268","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3268): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1452015606808.3268","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3268): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3268): start: Starting P2P device discovery...
,I/wpa_supplicant(  985): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3268): start: OK
I/jxcore-log( 3268): ok 47 Should be able to call startBroadcasting without error
I/jxcore-log( 3268): 
I/io.jxcore.node.ConnectionHelper( 3268): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3268): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3268): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3268): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3268): shutdown
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3268): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3268): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3268): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3268): stop: Stopping P2P device discovery...
,I/wpa_supplicant(  985): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3268): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3268): release: No more listeners, de-initializing...
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3268): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3268): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): setState: NOT_STARTED
,I/jxcore-log( 3268): ok 48 Should be able to call stopBroadcasting without error
I/jxcore-log( 3268): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): setDiscoveryMode: Mode set to WIFI
,D/BluetoothManagerService(  732): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3268): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452015606836.3268
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3268): bind: Binding a new listener
,D/BluetoothManagerService(  732): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3268): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  732): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3268): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1452015606836.3268","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3268): setConnectionTimeout: 15000
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3268): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3268): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  732): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3268): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3268): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3268): start: OK
I/io.jxcore.node.ConnectionHelper( 3268): start: Using peer discovery mode: WIFI
,D/BluetoothManagerService(  732): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452015606836.3268
,D/BluetoothManagerService(  732): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3268): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1452015606836.3268","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3268): bind: Binding a new listener
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3268): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3268): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3268): start: {"pi":"34:FC:EF:11:AE:67","pn":"1452015606836.3268","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3268): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1452015606836.3268","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3268): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3268): start: Starting P2P device discovery...
,I/wpa_supplicant(  985): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3268): start: OK
I/jxcore-log( 3268): ok 49 Should be able to call startBroadcasting without error
I/jxcore-log( 3268): 
I/io.jxcore.node.ConnectionHelper( 3268): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3268): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3268): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3268): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3268): shutdown
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3268): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3268): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3268): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3268): stop: Stopping P2P device discovery...
,I/wpa_supplicant(  985): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3268): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3268): release: No more listeners, de-initializing...
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3268): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3268): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): setState: NOT_STARTED
,I/jxcore-log( 3268): ok 50 Should be able to call stopBroadcasting without error
I/jxcore-log( 3268): 
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3268): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3268): onServerStopped
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): setDiscoveryMode: Mode set to WIFI
,D/BluetoothManagerService(  732): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3268): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452015606866.3268
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3268): bind: Binding a new listener
,D/BluetoothManagerService(  732): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3268): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  732): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3268): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1452015606866.3268","ra":"34:FC:EF:11:AE:67"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3268): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3268): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3268): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  732): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3268): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3268): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3268): start: OK
I/io.jxcore.node.ConnectionHelper( 3268): start: Using peer discovery mode: WIFI
,D/BluetoothManagerService(  732): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452015606866.3268
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3268): Waiting for incoming connections...
,D/BluetoothManagerService(  732): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3268): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1452015606866.3268","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3268): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3268): start: {"pi":"34:FC:EF:11:AE:67","pn":"1452015606866.3268","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3268): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1452015606866.3268","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3268): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3268): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3268): start: OK
I/wpa_supplicant(  985): p2p0: P2P: Reject scan trigger since one is already pending
I/jxcore-log( 3268): ok 51 Should be able to call startBroadcasting without error
I/jxcore-log( 3268): 
I/io.jxcore.node.ConnectionHelper( 3268): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3268): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3268): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3268): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3268): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3268): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3268): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3268): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3268): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3268): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3268): stop: Stopping P2P device discovery...
,I/wpa_supplicant(  985): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3268): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3268): release: No more listeners, de-initializing...
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3268): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3268): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): setState: NOT_STARTED
I/jxcore-log( 3268): ok 52 Should be able to call stopBroadcasting without error
I/jxcore-log( 3268): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): setDiscoveryMode: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService(  732): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3268): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452015606899.3268
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3268): bind: Binding a new listener
D/BluetoothManagerService(  732): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3268): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  732): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3268): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1452015606899.3268","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3268): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3268): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3268): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  732): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 3268): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3268): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3268): start: OK
I/io.jxcore.node.ConnectionHelper( 3268): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  732): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3268): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452015606899.3268
D/BluetoothManagerService(  732): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3268): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1452015606899.3268","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3268): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3268): start: {"pi":"34:FC:EF:11:AE:67","pn":"1452015606899.3268","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3268): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1452015606899.3268","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3268): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3268): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3268): start: OK
I/jxcore-log( 3268): ok 53 Should be able to call startBroadcasting without error
I/jxcore-log( 3268): 
I/io.jxcore.node.ConnectionHelper( 3268): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3268): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3268): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3268): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3268): shutdown
I/wpa_supplicant(  985): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3268): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3268): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3268): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3268): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3268): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3268): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3268): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3268): release: No more listeners, de-initializing...
,I/wpa_supplicant(  985): P2P-FIND-STOPPED 
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3268): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3268): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): setState: NOT_STARTED
I/jxcore-log( 3268): ok 54 Should be able to call stopBroadcasting without error
I/jxcore-log( 3268): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): setDiscoveryMode: Failed to set discovery mode to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService(  732): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3268): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452015606919.3268
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3268): bind: Binding a new listener
D/BluetoothManagerService(  732): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3268): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  732): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3268): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1452015606919.3268","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3268): setConnectionTimeout: 15000
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3268): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3268): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  732): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3268): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3268): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3268): start: OK
I/io.jxcore.node.ConnectionHelper( 3268): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  732): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3268): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452015606919.3268
,D/BluetoothManagerService(  732): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3268): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1452015606919.3268","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3268): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3268): start: {"pi":"34:FC:EF:11:AE:67","pn":"1452015606919.3268","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3268): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1452015606919.3268","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3268): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3268): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3268): start: OK
I/wpa_supplicant(  985): p2p0: P2P: Reject scan trigger since one is already pending
I/jxcore-log( 3268): ok 55 Should be able to call startBroadcasting without error
I/jxcore-log( 3268): 
I/io.jxcore.node.ConnectionHelper( 3268): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3268): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3268): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3268): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3268): shutdown
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3268): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3268): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3268): onServerStopped
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3268): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3268): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3268): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3268): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3268): release: No more listeners, de-initializing...
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3268): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3268): release: No more listeners, de-initializing...
I/wpa_supplicant(  985): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): setState: NOT_STARTED
I/jxcore-log( 3268): ok 56 Should be able to call stopBroadcasting without error
I/jxcore-log( 3268): 
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService(  732): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3268): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452015606940.3268
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3268): bind: Binding a new listener
D/BluetoothManagerService(  732): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3268): initialize: My bluetooth address is 34:FC:EF:11:AE:67
D/BluetoothManagerService(  732): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3268): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1452015606940.3268","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3268): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3268): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3268): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  732): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 3268): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3268): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3268): start: OK
I/io.jxcore.node.ConnectionHelper( 3268): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  732): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3268): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452015606940.3268
D/BluetoothManagerService(  732): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3268): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1452015606940.3268","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3268): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3268): start: {"pi":"34:FC:EF:11:AE:67","pn":"1452015606940.3268","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3268): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1452015606940.3268","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3268): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3268): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3268): start: OK
I/wpa_supplicant(  985): p2p0: P2P: Reject scan trigger since one is already pending
I/jxcore-log( 3268): ok 57 Should be able to call startBroadcasting without error
I/jxcore-log( 3268): 
I/io.jxcore.node.ConnectionHelper( 3268): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3268): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3268): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3268): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3268): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3268): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3268): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3268): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3268): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3268): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3268): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3268): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3268): release: No more listeners, de-initializing...
I/wpa_supplicant(  985): P2P-FIND-STOPPED 
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3268): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3268): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): setState: NOT_STARTED
I/jxcore-log( 3268): ok 58 Should be able to call stopBroadcasting without error
I/jxcore-log( 3268): 
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService(  732): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3268): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452015606959.3268
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3268): bind: Binding a new listener
D/BluetoothManagerService(  732): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3268): initialize: My bluetooth address is 34:FC:EF:11:AE:67
D/BluetoothManagerService(  732): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3268): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1452015606959.3268","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3268): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3268): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3268): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  732): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 3268): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3268): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3268): start: OK
I/io.jxcore.node.ConnectionHelper( 3268): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  732): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452015606959.3268
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3268): Waiting for incoming connections...
D/BluetoothManagerService(  732): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3268): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1452015606959.3268","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3268): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3268): start: {"pi":"34:FC:EF:11:AE:67","pn":"1452015606959.3268","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3268): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1452015606959.3268","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3268): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3268): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3268): start: OK
I/wpa_supplicant(  985): p2p0: P2P: Reject scan trigger since one is already pending
I/jxcore-log( 3268): ok 59 Should be able to call startBroadcasting without error
I/jxcore-log( 3268): 
I/io.jxcore.node.ConnectionHelper( 3268): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3268): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3268): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3268): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3268): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3268): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3268): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3268): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3268): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3268): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3268): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3268): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3268): release: No more listeners, de-initializing...
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3268): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3268): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): setState: NOT_STARTED
I/wpa_supplicant(  985): P2P-FIND-STOPPED 
I/jxcore-log( 3268): ok 60 Should be able to call stopBroadcasting without error
I/jxcore-log( 3268): 
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService(  732): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3268): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452015606985.3268
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3268): bind: Binding a new listener
D/BluetoothManagerService(  732): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3268): initialize: My bluetooth address is 34:FC:EF:11:AE:67
D/BluetoothManagerService(  732): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3268): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1452015606985.3268","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3268): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3268): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3268): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  732): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 3268): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3268): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3268): start: OK
I/io.jxcore.node.ConnectionHelper( 3268): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  732): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452015606985.3268
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3268): Waiting for incoming connections...
D/BluetoothManagerService(  732): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3268): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1452015606985.3268","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3268): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3268): start: {"pi":"34:FC:EF:11:AE:67","pn":"1452015606985.3268","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3268): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1452015606985.3268","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3268): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3268): start: Starting P2P device discovery...
I/wpa_supplicant(  985): p2p0: P2P: Reject scan trigger since one is already pending
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3268): start: OK
I/jxcore-log( 3268): ok 61 Should be able to call startBroadcasting without error
I/jxcore-log( 3268): 
I/io.jxcore.node.ConnectionHelper( 3268): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3268): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3268): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3268): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3268): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3268): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3268): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3268): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3268): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3268): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3268): stop: Stopping P2P device discovery...
I/wpa_supplicant(  985): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3268): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3268): release: No more listeners, de-initializing...
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3268): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3268): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): setState: NOT_STARTED
I/jxcore-log( 3268): ok 62 Should be able to call stopBroadcasting without error
I/jxcore-log( 3268): 
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService(  732): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3268): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452015607004.3268
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3268): bind: Binding a new listener
D/BluetoothManagerService(  732): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3268): initialize: My bluetooth address is 34:FC:EF:11:AE:67
D/BluetoothManagerService(  732): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3268): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1452015607004.3268","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3268): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3268): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3268): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  732): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 3268): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3268): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3268): start: OK
I/io.jxcore.node.ConnectionHelper( 3268): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  732): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3268): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452015607004.3268
D/BluetoothManagerService(  732): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3268): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1452015607004.3268","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3268): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3268): start: {"pi":"34:FC:EF:11:AE:67","pn":"1452015607004.3268","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3268): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1452015607004.3268","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3268): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3268): start: Starting P2P device discovery...
I/wpa_supplicant(  985): p2p0: P2P: Reject scan trigger since one is already pending
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3268): start: OK
I/jxcore-log( 3268): ok 63 Should be able to call startBroadcasting without error
I/jxcore-log( 3268): 
I/io.jxcore.node.ConnectionHelper( 3268): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3268): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3268): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3268): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3268): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3268): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3268): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3268): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3268): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3268): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3268): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3268): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3268): release: No more listeners, de-initializing...
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3268): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3268): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3268): setState: NOT_STARTED
I/jxcore-log( 3268): ok 64 Should be able to call stopBroadcasting without error
I/jxcore-log( 3268): 
I/jxcore-log( 3268): # setup
I/jxcore-log( 3268): 
I/io.jxcore.node.ConnectionHelper( 3268): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3268): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3268): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3268): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 3268): onDiscoveryManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 3268): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3268): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3268): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3268): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 3268): onDiscoveryManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3268): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3268): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3268): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3268): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 3268): onDiscoveryManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 3268): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3268): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3268): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3268): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 3268): onDiscoveryManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3268): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3268): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3268): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3268): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 3268): onDiscoveryManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 3268): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3268): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3268): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3268): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 3268): onDiscoveryManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3268): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3268): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 3268): onDiscoveryManagerStateChanged: RUNNING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3268): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3268): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 3268): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3268): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3268): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3268): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 3268): onDiscoveryManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3268): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 3268): onDiscoveryManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3268): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3268): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3268): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 3268): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3268): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3268): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3268): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 3268): onDiscoveryManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3268): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3268): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 3268): onDiscoveryManagerStateChanged: RUNNING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3268): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3268): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 3268): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3268): Local services cleared successfully
I/io.jxcore.node.ConnectionHelper( 3268): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3268): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3268): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 3268): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3268): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 3268): onDiscoveryManagerStateChanged: RUNNING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3268): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3268): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 3268): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3268): Local services cleared successfully
I/io.jxcore.node.ConnectionHelper( 3268): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3268): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3268): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 3268): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3268): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 3268): onDiscoveryManagerStateChanged: RUNNING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3268): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3268): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 3268): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3268): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3268): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3268): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3268): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 3268): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3268): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3268): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3268): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 3268): onDiscoveryManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 3268): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3268): Local services cleared successfully
I/io.jxcore.node.ConnectionHelper( 3268): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3268): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3268): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 3268): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3268): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3268): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3268): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 3268): onDiscoveryManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 3268): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3268): Local services cleared successfully
I/io.jxcore.node.ConnectionHelper( 3268): onDiscoveryManagerStateChanged: NOT_STARTED
I/wpa_supplicant(  985): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3268): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3268): Service requests cleared successfully
,I/ActivityManager(  732): Killing 2655:com.android.settings/1000 (adj 15): empty #17
,D/WifiService(  732): Client connection lost with reason: 4
,W/libprocessgroup(  732): failed to open /acct/uid_1000/pid_2655/cgroup.procs: No such file or directory
,I/ActivityManager(  732): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=3635 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,W/bt-smp  ( 2047): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2047): Plain text(LSB ~ MSB) = 9c 35 64 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2047): Encrypted text(LSB ~ MSB) = d2 a6 b5 be 24 7f 8b ec db 48 eb 51 2f 8b d3 de 
W/bt-btm  ( 2047): Stopping oneshot timer
,I/EventLogService( 1633): Aggregate from 1452013901777 (log), 1452013901777 (data)
,I/GAv4    ( 3635): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3635):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3635):   adb logcat -s GAv4
,W/GAv4    ( 3635): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3635): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3635): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  732): Killing 2527:com.google.android.gm/u0a70 (adj 15): empty #17
,W/libprocessgroup(  732): failed to open /acct/uid_10070/pid_2527/cgroup.procs: No such file or directory
,I/GoogleURLConnFactory( 1563): Using platform SSLCertificateSocketFactory
,I/PhenotypeConfigurator( 1563): Scheduling Phenotype every 14400 seconds, with flex of 1800 seconds
,I/PhenotypeConfigurator( 1563): Scheduling Phenotype for one-off execution 12889 seconds from now (1452016059702)
,D/GetConfigurationSnapshotOperation( 1563): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1563): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1563): Using platform SSLCertificateSocketFactory
,W/PhenotypeConfigurator( 1563): Server returned 404
,I/UsageStatsService(  732): User[0] Flushing usage stats to disk
,I/ProcessStatsService(  732): Prepared write state in 53ms
,I/ProcessStatsService(  732): Prepared write state in 5ms
,W/bt-smp  ( 2047): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2047): Plain text(LSB ~ MSB) = 74 98 7a 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2047): Encrypted text(LSB ~ MSB) = 67 29 d3 67 fd f7 26 3a 28 4c b0 9f b3 b7 63 5d 
W/bt-btm  ( 2047): Stopping oneshot timer
,I/ProcessStatsService(  732): Pruning old procstats: /data/system/procstats/state-2016-01-04-23-34-40.bin
,TIME-OUT KILL (timeout was 1800000ms)
```
