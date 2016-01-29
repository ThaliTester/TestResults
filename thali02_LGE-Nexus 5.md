#### Test 57659382b63fd0b_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
I/GAv4    ( 3228): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3228):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3228):   adb logcat -s GAv4
W/GAv4    ( 3228): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3228): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3228): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 3228): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
,D/Finsky  ( 2625): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
W/ResourcesManager( 3228): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3228): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  740): Killing 2062:com.google.android.deskclock/u0a38 (adj 15): empty #17
V/JNIHelp ( 3228): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/System  ( 3228): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3228): Installed default security provider GmsCore_OpenSSL
W/libprocessgroup(  740): failed to open /acct/uid_10038/pid_2062/cgroup.procs: No such file or directory
V/GLSActivity( 1566): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/AndroidRuntime( 3276): 
D/AndroidRuntime( 3276): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3276): CheckJNI is OFF
D/AndroidRuntime( 3276): Calling main entry com.android.commands.am.Am
I/ActivityManager(  740): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  740): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3303 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3276): Shutting down VM
V/ActivityManager(  740): Display changed displayId=0
I/Icing   ( 1607): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/Icing   ( 1607): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/WebViewFactory( 3303): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/Icing   ( 1607): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1607): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
I/LibraryLoader( 3303): Time to load native libraries: 4 ms (timestamps 2430-2434)
I/LibraryLoader( 3303): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3303): Binding Chromium to main looper Looper (main, tid 1) {2b30afd}
I/LibraryLoader( 3303): Expected native library version number "",actual native library version number ""
I/chromium( 3303): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3303): Initializing chromium process, singleProcess=true
W/art     ( 3303): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3303): ApplicationContext is null in ApplicationStatus
W/chromium( 3303): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3303): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3303): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3303): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
D/BluetoothManagerService(  740): Message: 20
D/BluetoothManagerService(  740): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@27226d21:true
W/art     ( 3303): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 3303): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 3303): CordovaWebView is running on device made by: LGE
W/art     ( 3303): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3303): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 3303): Render dirty regions requested: true
D/Atlas   ( 3303): Validating map...
W/chromium( 3303): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/OpenGLRenderer( 3303): Initialized EGL, version 1.4
D/OpenGLRenderer( 3303): Enabling debug mode 0
W/BindingManager( 3303): Cannot call determinedVisibility() - never saw a connection for the pid: 3303
W/IInputConnectionWrapper( 3303): showStatusIcon on inactive InputConnection
I/ActivityManager(  740): Displayed com.test.thalitest/.MainActivity: +434ms (total +52s243ms)
D/JsMessageQueue( 3303): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 3303): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257342720
I/chromium( 3303): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 3303): Initializing JXcore engine
W/jxcore-log( 3303): JXcore engine is ready
,W/Thread-307( 3366): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[6604]" dev="sockfs" ino=6604 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-307( 3366): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
,W/Thread-307( 3366): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6746]" dev="sockfs" ino=6746 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-307( 3366): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[19245]" dev="sockfs" ino=19245 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3303): Starting JXcore engine
,W/jxcore-log( 3303): Platform android
W/jxcore-log( 3303): 
W/jxcore-log( 3303): Process ARCH arm
W/jxcore-log( 3303): 
,I/jxcore-log( 3303): JXcore Cordova bridge is ready!
I/jxcore-log( 3303): 
,W/jxcore-log( 3303): JXcore engine is started
,I/ActivityManager(  740): Killing 2532:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,I/jxcore-log( 3303): Toggling radios to true
I/jxcore-log( 3303): 
D/BluetoothAdapter( 3303): enable(): BT is already enabled..!
,D/WifiService(  740): New client listening to asynchronous messages
,D/WifiService(  740): setWifiEnabled: true pid=3303, uid=10270
E/WifiService(  740): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3303): Radios toggled
I/jxcore-log( 3303): 
,I/jxcore-log( 3303): My device name is: LGE-Nexus 5
I/jxcore-log( 3303): 
,I/wpa_supplicant( 1031): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  740): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  740): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/native  (  740): do suspend true
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1566): Read error: ssl=0xb3c3ae00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1566): SSL shutdown failed: ssl=0xb3c3ae00: I/O error during system call, Broken pipe
,D/ConnectivityService(  740): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  740): ValidatedState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  740): DefaultState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  740): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  740): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  740): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  740): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,W/libprocessgroup(  740): failed to open /acct/uid_10045/pid_2532/cgroup.procs: No such file or directory
,D/ConnectivityService(  740): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  740): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
E/WifiConfigStore(  740): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiStateMachine(  740): Start Disconnecting Watchdog 1
,I/wpa_supplicant( 1031): wlan0: CTRL-EVENT-SCAN-STARTED 
,E/native  (  740): do suspend true
D/ConnectivityService(  740): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/Nat464Xlat(  740): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  740): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  740): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  740): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  740): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  740): Disconnected - quitting
D/ConnectivityService(  740): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler(  900): CM callback handler got msg 524292
D/ConnectivityService(  740): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/CommandListener(  179): Clearing all IP addresses on wlan0
D/TelephonyNetworkFactory( 1233): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 1607): CM callback handler got msg 524292
,D/WifiNetworkAgent(  740): NetworkAgent: NetworkAgent channel lost
,I/wpa_supplicant( 1031): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant( 1031): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1031): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1031): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  740): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  740): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  740): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  740): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  179): Setting iface cfg
,E/WifiStateMachine(  740): Start Dhcp Watchdog 2
,E/native  (  740): do suspend false
,E/WifiStateMachine(  740): scanCount==0 - aborting
,I/dhcpcd  ( 3387): version 5.5.6 starting
E/dhcpcd  ( 3387): get_duid: Read-only file system
,I/dhcpcd  ( 3387): wlan0: rebinding lease of 192.168.1.114
,I/dhcpcd  ( 3387): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3387): wlan0: leased 192.168.1.114 for 86400 seconds
,D/ConnectivityService(  740): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  740): MasterInitialState.processMessage what=3
,D/ConnectivityService(  740): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/MusicLeanback( 2749): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/Tethering(  740): MasterInitialState.processMessage what=3
,I/SystemUpdateService( 1607): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1607): onCreate
,D/SystemUpdateService( 1607): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1607): active receiver: enabled
,I/SystemUpdateService( 1607): showing system update notification
,E/GpsLocationProvider(  740): No APN found to select.
,E/GpsLocationProvider(  740): No APN found to select.
,I/iu.Environment( 1607): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1607): num queued entries: 0
I/iu.UploadsManager( 1607): num updated entries: 0
,I/iu.SyncManager( 1607): NEXT; no task
,I/Babel   ( 1890): connection state changed from CONNECTED to DISCONNECTED
,I/ValidateNoPeople(  740): skipping global notification
,V/SystemUpdateService( 1607): retry (wakeup: false) in 3599939 ms
,I/ActivityManager(  740): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3428 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/native  (  740): do suspend true
,D/SystemUpdateService( 1607): onDestroy
,D/ConnectivityService(  740): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  740): Adding iface wlan0 to network 101
,E/WifiStateMachine(  740): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  740): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  740): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  740): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  740): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  740): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  740): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  740): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  740): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  740): rematching NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  740):    accepting network in place of null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  740): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  740): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  740): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  740): Checking http://clients3.google.com/generate_204 on "NG7005g"
D/CSLegacyTypeTracker(  740): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  740): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  740): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::5255:27ff:fef0:fd0b/64,192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService(  740): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler(  900): CM callback handler got msg 524290
D/ConnectivityManager.CallbackHandler( 1607): CM callback handler got msg 524290
,I/GAv4    ( 3428): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3428):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3428):   adb logcat -s GAv4
,W/GAv4    ( 3428): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3428): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3428): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  740): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 29 Jan 2016 15:49:59 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454082599148], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454082599124]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  740): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  740): Validated
D/ConnectivityService(  740): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  740): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  740): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  740): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler(  900): CM callback handler got msg 524290
D/ConnectivityService(  740): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/TelephonyNetworkFactory( 1233): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 1607): CM callback handler got msg 524290
,I/WebViewFactory( 3428): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3428): Time to load native libraries: 2 ms (timestamps 7960-7962)
,I/LibraryLoader( 3428): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3428): Binding Chromium to main looper Looper (main, tid 1) {2dcb5667}
,I/LibraryLoader( 3428): Expected native library version number "",actual native library version number ""
,I/chromium( 3428): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3428): Initializing chromium process, singleProcess=true
W/art     ( 3428): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3428): ApplicationContext is null in ApplicationStatus
,W/chromium( 3428): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3428): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3428): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3428): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/AudioManagerAndroid( 3428): Requires BLUETOOTH permission
,I/NSApplication( 3428): Starting up...
,I/ActivityManager(  740): Killing 2722:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/libprocessgroup(  740): failed to open /acct/uid_10003/pid_2722/cgroup.procs: No such file or directory
,V/MusicLeanback( 2749): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1607): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1607): onCreate
,D/SystemUpdateService( 1607): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.Environment( 1607): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/SystemUpdateService( 1607): active receiver: enabled
,I/SystemUpdateService( 1607): showing system update notification
,I/iu.UploadsManager( 1607): num queued entries: 0
,I/iu.UploadsManager( 1607): num updated entries: 0
,I/iu.SyncManager( 1607): NEXT; no task
,I/ValidateNoPeople(  740): skipping global notification
,V/SystemUpdateService( 1607): retry (wakeup: false) in 3599956 ms
,D/SystemUpdateService( 1607): onDestroy
,I/Babel   ( 1890): connection state changed from DISCONNECTED to CONNECTED
,I/jxcore-log( 3303): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3303): 
,D/ConnectivityService(  740): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,V/GLSActivity( 1566): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1566): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 3303): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 3303): 
,I/jxcore-log( 3303): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 3303): 
,I/jxcore-log( 3303): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 3303): 
,I/jxcore-log( 3303): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 3303): 
,I/jxcore-log( 3303): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 3303): 
,I/jxcore-log( 3303): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 3303): 
,I/jxcore-log( 3303): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3303): 
,D/ConnectivityService(  740): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  740): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2749): type=WIFI subType= reason=null isConnected=true
,E/GpsLocationProvider(  740): No APN found to select.
,V/MusicLeanback( 2749): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1607): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1607): onCreate
,I/art     (  740): Explicit concurrent mark sweep GC freed 44135(2MB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 27MB/41MB, paused 958us total 63.987ms
,D/SystemUpdateService( 1607): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1607): active receiver: enabled
,I/SystemUpdateService( 1607): showing system update notification
,I/ValidateNoPeople(  740): skipping global notification
,V/SystemUpdateService( 1607): retry (wakeup: false) in 3599968 ms
,D/SystemUpdateService( 1607): onDestroy
,I/jxcore-log( 3303): Test app app.js loaded
I/jxcore-log( 3303): 
,I/chromium( 3303): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3303): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3303): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3303): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3303): 	Bluetooth MAC address: null, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3303): 	Discovery mode: BLE, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3303): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3303): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3303): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3303): 	Scan mode: 1
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3303): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2914b954 added. We now have 1 listener(s)
,I/jxcore-log( 3303): BLE advertisement is not supported: Bluetooth LE advertising is not supported,
I/jxcore-log( 3303): 
,D/Finsky  ( 2625): [255] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 2625): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/GLSActivity( 1566): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1566): Vacuum at: now=1454082617298 tag=VacuumService
,I/ClearcutLoggerApiImpl( 1566): disconnect managed GoogleApiClient
,I/jxcore-log( 3303): --= Surplus to requirements =--
I/jxcore-log( 3303): 
I/jxcore-log( 3303): ****TEST TOOK:  ms ****
I/jxcore-log( 3303): 
I/jxcore-log( 3303): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3303): 
,D/AndroidRuntime( 3597): 
D/AndroidRuntime( 3597): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 3597): CheckJNI is OFF
,D/AndroidRuntime( 3597): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  740): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  740): Killing 3303:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
,I/WindowState(  740): WIN DEATH: Window{22fe091 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  740): Client connection lost with reason: 4
,W/PackageSettings(  740): Skipping PackageSetting{1318bfc1 com.example.hello/10278} due to missing metadata
,I/ActivityManager(  740):   Force finishing activity ActivityRecord{5aa22 u0 com.test.thalitest/.MainActivity t216}
,W/ActivityManager(  740): Spurious death for ProcessRecord{935ddf2 3303:com.test.thalitest/u0a270}, curProc for 3303: null
,I/ActivityManager(  740): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
,I/art     ( 1254): Explicit concurrent mark sweep GC freed 3943(293KB) AllocSpace objects, 1(126KB) LOS objects, 38% free, 25MB/41MB, paused 651us total 23.476ms,
I/art     ( 1607): Explicit concurrent mark sweep GC freed 10956(528KB) AllocSpace objects, 1(16KB) LOS objects, 25% free, 22MB/30MB, paused 451us total 41.351ms
,I/Keyboard.Facilitator( 1086): resetDictionaries() : en_US
,I/InputReader(  740): Reconfiguring input devices.  changes=0x00000010
,I/art     ( 1422): Explicit concurrent mark sweep GC freed 13450(951KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 19MB/25MB, paused 351us total 20.560ms
,I/Keyboard.Facilitator.DecoderInitializer( 1086): run()
,W/GeofencerStateMachine( 1566): Ignoring removeGeofence because network location is disabled.
,I/Decoder ( 1086): createOrResetDecoder
,D/VoicemailCleanupService( 2859): Cleaning up data for package: com.test.thalitest
,I/art     (  740): Explicit concurrent mark sweep GC freed 17110(1037KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 27MB/41MB, paused 3.236ms total 60.888ms
,I/ConfigService( 1566): onCreate
I/UpdateIcingCorporaServi( 1422): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,W/Launcher( 1254): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@3042f3f2 new=com.google.android.velvet.VelvetApplication@3042f3f2
,I/Adreno-EGL(  949): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
I/OpenGLRenderer(  949): Initialized EGL, version 1.4
,I/ActivityManager(  740): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3637 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
D/OpenGLRenderer(  949): Enabling debug mode 0
,D/BackupManagerService(  740): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  740): Receieved: android.intent.action.PACKAGE_REMOVED
,W/InputMethodManagerService(  740): Focus gain on non-focused client com.android.internal.view.IInputMethodClient$Stub$Proxy@f221f80 (uid=10034 pid=949)
,I/art     (  740): Explicit concurrent mark sweep GC freed 5557(300KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 4.090ms total 121.755ms
,D/TaskPersister(  740): removeObsoleteFile: deleting file=216_task.xml
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1086): run()
,W/ContextImpl( 3637): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
,I/UpdateIcingCorporaServi( 1422): UpdateCorporaTask done [took 130 ms] updated apps [took 130 ms] 
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1086): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1086): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1086): run() : Loading LM = contacts
D/PackageBroadcastService( 1607): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1607): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 1607): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1607): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1607): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1607): Module APK com.google.android.play.games already loaded
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1086): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1086): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1086): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1086): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1086): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1086): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1086): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1086): run()
,I/StatsUtilsManager( 1086): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1086): shouldRecordStats() = Too Soon
,E/NetworkScheduler.SchedulerReceiver( 1566): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1566): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/LocationSettingsChecker( 1607): Removing dialog suppression flag for package com.test.thalitest
,D/gH_CompatibleDatabase( 1607): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1607): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 1607): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1607): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/gH_CompatibleDatabase( 1607): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1607): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/gH_CompatibleDatabase( 1607): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/gH_CompatibleDatabase( 1607): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1607): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 1607): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1607): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1607): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1607): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/ActivityManager(  740): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3670 uid=10039 gids={50039, 9997} abi=armeabi-v7a
,I/Launcher( 1254): Deferring update until onResume
,D/AndroidRuntime( 3597): Shutting down VM
,W/ResourcesManager( 1254): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 1254): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/BaseAppContext( 1607): Using Auth Proxy for data requests.
I/ActivityManager(  740): Killing 2695:com.android.settings/1000 (adj 15): empty #17
,D/WifiService(  740): Client connection lost with reason: 4
,I/Launcher( 1254): Deferring update until onResume
,W/libprocessgroup(  740): failed to open /acct/uid_1000/pid_2695/cgroup.procs: No such file or directory
,W/BaseAppContext( 1607): Using Auth Proxy for data requests.
,I/GMPM-SVC( 1607): App measurement is starting up, version: 8489
,I/GMPM-SVC( 1607): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,I/ActivityManager(  740): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3692 uid=10007 gids={50007, 9997, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  740): Killing 2562:com.google.android.gm/u0a70 (adj 15): empty #17
,W/libprocessgroup(  740): failed to open /acct/uid_10070/pid_2562/cgroup.procs: No such file or directory
,I/Icing   ( 1607): doRemovePackageData com.test.thalitest
,I/ActivityManager(  740): Killing 1989:com.google.android.calendar/u0a31 (adj 15): empty #17
,D/ExternalStorage( 3692): After updating volumes, found 1 active roots
,W/libprocessgroup(  740): failed to open /acct/uid_10031/pid_1989/cgroup.procs: No such file or directory
,W/ResourcesManager( 3228): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3228): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.

```
