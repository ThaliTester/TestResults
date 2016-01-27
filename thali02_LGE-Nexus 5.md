#### Test 564496604206eac_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
D/Finsky  ( 2580): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
W/ResourcesManager( 3147): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3147): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  761): Killing 2550:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
V/JNIHelp ( 3147): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/System  ( 3147): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3147): Installed default security provider GmsCore_OpenSSL
W/libprocessgroup(  761): failed to open /acct/uid_10069/pid_2550/cgroup.procs: No such file or directory
V/GLSActivity( 1563): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 1612): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/Icing   ( 1612): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1612): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/Icing   ( 1612): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
,I/ActivityManager(  761): Killing 2505:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
W/libprocessgroup(  761): failed to open /acct/uid_10045/pid_2505/cgroup.procs: No such file or directory
D/AndroidRuntime( 3206): 
D/AndroidRuntime( 3206): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3206): CheckJNI is OFF
D/AndroidRuntime( 3206): Calling main entry com.android.commands.am.Am
I/ActivityManager(  761): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  761): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3227 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3206): Shutting down VM
V/ActivityManager(  761): Display changed displayId=0
I/WebViewFactory( 3227): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3227): Time to load native libraries: 2 ms (timestamps 8650-8652)
I/LibraryLoader( 3227): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3227): Binding Chromium to main looper Looper (main, tid 1) {58f0ff0}
I/LibraryLoader( 3227): Expected native library version number "",actual native library version number ""
I/chromium( 3227): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3227): Initializing chromium process, singleProcess=true
W/art     ( 3227): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3227): ApplicationContext is null in ApplicationStatus
,W/chromium( 3227): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3227): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3227): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3227): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  761): Message: 20
,D/BluetoothManagerService(  761): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3e84edd2:true
,W/art     ( 3227): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3227): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3227): CordovaWebView is running on device made by: LGE
,W/art     ( 3227): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3227): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3227): Render dirty regions requested: true
,D/Atlas   ( 3227): Validating map...
,W/chromium( 3227): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3227): Initialized EGL, version 1.4
D/OpenGLRenderer( 3227): Enabling debug mode 0
,W/IInputConnectionWrapper( 3227): showStatusIcon on inactive InputConnection
,I/ActivityManager(  761): Displayed com.test.thalitest/.MainActivity: +412ms (total +57s469ms)
,W/BindingManager( 3227): Cannot call determinedVisibility() - never saw a connection for the pid: 3227
,D/JsMessageQueue( 3227): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3227): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257332480
,I/chromium( 3227): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 3227): Initializing JXcore engine
W/jxcore-log( 3227): JXcore engine is ready
,W/Thread-306( 3275): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[6499]" dev="sockfs" ino=6499 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/Thread-306( 3275): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-306( 3275): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8461]" dev="sockfs" ino=8461 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-306( 3275): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[19936]" dev="sockfs" ino=19936 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3227): Starting JXcore engine
,W/jxcore-log( 3227): Platform android
W/jxcore-log( 3227): 
W/jxcore-log( 3227): Process ARCH arm
W/jxcore-log( 3227): 
,I/jxcore-log( 3227): JXcore Cordova bridge is ready!
I/jxcore-log( 3227): 
,W/jxcore-log( 3227): JXcore engine is started
,I/jxcore-log( 3227): Toggling radios to true
I/jxcore-log( 3227): 
,D/BluetoothAdapter( 3227): enable(): BT is already enabled..!
,D/WifiService(  761): New client listening to asynchronous messages
D/WifiService(  761): setWifiEnabled: true pid=3227, uid=10270
E/WifiService(  761): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3227): Radios toggled
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): My device name is: LGE-Nexus 5
I/jxcore-log( 3227): 
,I/wpa_supplicant(  992): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  761): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  761): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/native  (  761): do suspend true
,D/CommandListener(  180): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1563): Read error: ssl=0xb3e30000: I/O error during system call, Connection timed out
,V/NativeCrypto( 1563): SSL shutdown failed: ssl=0xb3e30000: I/O error during system call, Broken pipe
,D/ConnectivityService(  761): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  761): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,E/WifiConfigStore(  761): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiStateMachine(  761): Start Disconnecting Watchdog 1
I/wpa_supplicant(  992): wlan0: CTRL-EVENT-SCAN-STARTED 
D/ConnectivityService(  761): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): ValidatedState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): DefaultState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Checking http://clients3.google.com/generate_204 on <unknown ssid>
,E/native  (  761): do suspend true
,D/CommandListener(  180): Clearing all IP addresses on wlan0
D/ConnectivityService(  761): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/ConnectivityManager.CallbackHandler(  899): CM callback handler got msg 524292
D/Nat464Xlat(  761): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  761): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Disconnected - quitting
D/ConnectivityManager.CallbackHandler( 1612): CM callback handler got msg 524292
,D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  761): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1267): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WifiNetworkAgent(  761): NetworkAgent: NetworkAgent channel lost
,W/NetworkUtils( 1413): OkHttp exception
W/EventLoggerService( 1413): Unable to send logs Error code: 262146
,V/GLSActivity( 1563): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1563): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/wpa_supplicant(  992): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant(  992): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant(  992): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant(  992): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  761): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  761): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  761): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  761): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  180): Setting iface cfg
E/WifiStateMachine(  761): Start Dhcp Watchdog 2
,E/native  (  761): do suspend false
,E/WifiStateMachine(  761): scanCount==0 - aborting
,I/dhcpcd  ( 3309): version 5.5.6 starting
E/dhcpcd  ( 3309): get_duid: Read-only file system
,I/dhcpcd  ( 3309): wlan0: rebinding lease of 192.168.1.114
,I/dhcpcd  ( 3309): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3309): wlan0: leased 192.168.1.114 for 86400 seconds
,D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  761): MasterInitialState.processMessage what=3
,D/Tethering(  761): MasterInitialState.processMessage what=3
,V/MusicLeanback( 2714): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1612): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1612): onCreate
,D/SystemUpdateService( 1612): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
I/iu.Environment( 1612): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/SystemUpdateService( 1612): active receiver: enabled
,I/ActivityManager(  761): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3335 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/iu.UploadsManager( 1612): num queued entries: 0
I/iu.UploadsManager( 1612): num updated entries: 0
I/iu.SyncManager( 1612): NEXT; no task
,I/SystemUpdateService( 1612): showing system update notification
I/Babel   ( 1882): connection state changed from CONNECTED to DISCONNECTED
,I/ValidateNoPeople(  761): skipping global notification
,E/GpsLocationProvider(  761): No APN found to select.
,V/SystemUpdateService( 1612): retry (wakeup: false) in 3599919 ms
,E/GpsLocationProvider(  761): No APN found to select.
,D/SystemUpdateService( 1612): onDestroy
,E/native  (  761): do suspend true
,D/ConnectivityService(  761): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  761): Adding iface wlan0 to network 101
,E/WifiStateMachine(  761): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  761): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  761): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  761): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  761): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  761): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  761): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  761): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  761): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  761): rematching NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Connected
D/ConnectivityService(  761):    accepting network in place of null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Checking http://clients3.google.com/generate_204 on "NG7005g"
D/CSLegacyTypeTracker(  761): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  761): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::5255:27ff:fef0:fd0b/64,192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  761): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1612): CM callback handler got msg 524290
D/ConnectivityManager.CallbackHandler(  899): CM callback handler got msg 524290
,I/GAv4    ( 3335): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3335):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3335):   adb logcat -s GAv4
,W/GAv4    ( 3335): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3335): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.,
,W/GAv4    ( 3335): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 27 Jan 2016 09:05:01 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1453885501867], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1453885501850]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Validated
D/ConnectivityService(  761): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  761): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  761): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  761): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  899): CM callback handler got msg 524290
D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 1612): CM callback handler got msg 524290
D/TelephonyNetworkFactory( 1267): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/WebViewFactory( 3335): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3335): Time to load native libraries: 1 ms (timestamps 4628-4629)
,I/LibraryLoader( 3335): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3335): Binding Chromium to main looper Looper (main, tid 1) {34b7ea62}
,I/LibraryLoader( 3335): Expected native library version number "",actual native library version number ""
,I/chromium( 3335): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3335): Initializing chromium process, singleProcess=true
W/art     ( 3335): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3335): ApplicationContext is null in ApplicationStatus
,W/chromium( 3335): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3335): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3335): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3335): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/AudioManagerAndroid( 3335): Requires BLUETOOTH permission
,I/NSApplication( 3335): Starting up...
,I/ActivityManager(  761): Killing 2684:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10003/pid_2684/cgroup.procs: No such file or directory
,V/MusicLeanback( 2714): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1612): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1612): onCreate
,D/SystemUpdateService( 1612): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1612): active receiver: enabled
,I/SystemUpdateService( 1612): showing system update notification
,I/iu.Environment( 1612): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1612): num queued entries: 0
I/iu.UploadsManager( 1612): num updated entries: 0
I/iu.SyncManager( 1612): NEXT; no task
,I/ValidateNoPeople(  761): skipping global notification
,V/SystemUpdateService( 1612): retry (wakeup: false) in 3599955 ms
,D/SystemUpdateService( 1612): onDestroy
,I/Babel   ( 1882): connection state changed from DISCONNECTED to CONNECTED
,I/jxcore-log( 3227): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3227): 
,D/ConnectivityService(  761): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/jxcore-log( 3227): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 3227): 
I/jxcore-log( 3227): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3227): 
,D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  761): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2714): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2714): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/SystemUpdateService( 1612): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
D/SystemUpdateService( 1612): onCreate
D/SystemUpdateService( 1612): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1612): active receiver: enabled
,I/SystemUpdateService( 1612): showing system update notification
,I/ValidateNoPeople(  761): skipping global notification
V/SystemUpdateService( 1612): retry (wakeup: false) in 3599953 ms
,D/SystemUpdateService( 1612): onDestroy
,I/art     (  761): Explicit concurrent mark sweep GC freed 43206(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 27MB/41MB, paused 8.739ms total 72.771ms
,E/GpsLocationProvider(  761): No APN found to select.
,I/jxcore-log( 3227): Test app app.js loaded
I/jxcore-log( 3227): 
,I/chromium( 3227): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): setDiscoveryMode: Mode set to BLE
I/jxcore-log( 3227): BLE advertisement is supported
I/jxcore-log( 3227): 
,D/Finsky  ( 2580): [255] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2580): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/GLSActivity( 1563): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1563): Vacuum at: now=1453885515591 tag=VacuumService
,I/PhenotypeConfigurator( 1563): Scheduling Phenotype for one-off execution 12377 seconds from now (1453885516101)
,D/GetConfigurationSnapshotOperation( 1563): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1563): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1563): Using platform SSLCertificateSocketFactory
,I/ClearcutLoggerApiImpl( 1563): disconnect managed GoogleApiClient
,I/jxcore-log( 3227): --= Surplus to requirements =--
I/jxcore-log( 3227): 
I/jxcore-log( 3227): ****TEST TOOK:  ms ****
I/jxcore-log( 3227): 
I/jxcore-log( 3227): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3227): 
,D/AndroidRuntime( 3534): 
D/AndroidRuntime( 3534): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 3534): CheckJNI is OFF
,D/AndroidRuntime( 3534): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  761): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  761): Killing 3227:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
,I/WindowState(  761): WIN DEATH: Window{36c06f82 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  761): Client connection lost with reason: 4
,W/PackageSettings(  761): Skipping PackageSetting{38cabb84 com.example.hello/10278} due to missing metadata
,I/ActivityManager(  761):   Force finishing activity ActivityRecord{31a7b46e u0 com.test.thalitest/.MainActivity t216}
,W/ActivityManager(  761): Spurious death for ProcessRecord{2fb34e16 3227:com.test.thalitest/u0a270}, curProc for 3227: null
,I/ActivityManager(  761): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
I/ActivityManager(  761):   Force finishing activity ActivityRecord{31a7b46e u0 com.test.thalitest/.MainActivity t216 f}
W/ActivityManager(  761): Duplicate finish request for ActivityRecord{31a7b46e u0 com.test.thalitest/.MainActivity t216 f}
,I/Adreno-EGL(  946): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
I/OpenGLRenderer(  946): Initialized EGL, version 1.4
,D/OpenGLRenderer(  946): Enabling debug mode 0
,I/art     ( 1413): Explicit concurrent mark sweep GC freed 9110(579KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 19MB/25MB, paused 321us total 53.192ms
,I/art     ( 1321): Explicit concurrent mark sweep GC freed 3932(293KB) AllocSpace objects, 1(126KB) LOS objects, 23% free, 25MB/33MB, paused 234us total 24.016ms
,I/art     ( 1612): Explicit concurrent mark sweep GC freed 10965(527KB) AllocSpace objects, 1(16KB) LOS objects, 25% free, 22MB/30MB, paused 519us total 84.974ms
,W/InputMethodManagerService(  761): Got RemoteException sending setActive(false) notification to pid 3227 uid 10270
,I/Keyboard.Facilitator( 1104): onFinishInput()
,I/Keyboard.Facilitator( 1104): resetDictionaries() : en_US
,I/InputReader(  761): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 1563): Ignoring removeGeofence because network location is disabled.
I/Keyboard.Facilitator.DecoderInitializer( 1104): run()
,I/Decoder ( 1104): createOrResetDecoder
,D/VoicemailCleanupService( 2824): Cleaning up data for package: com.test.thalitest
,I/ConfigService( 1563): onCreate
,I/UpdateIcingCorporaServi( 1413): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/art     (  761): Explicit concurrent mark sweep GC freed 22134(1229KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 8.619ms total 97.459ms
,I/art     (  761): WaitForGcToComplete blocked for 50.441ms for cause Explicit
,W/Launcher( 1321): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@38651969 new=com.google.android.velvet.VelvetApplication@38651969
,I/ActivityManager(  761): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3588 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1104): run()
,I/UpdateIcingCorporaServi( 1413): UpdateCorporaTask done [took 111 ms] updated apps [took 111 ms] 
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1104): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1104): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1104): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1104): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1104): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1104): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1104): run() : Loading LM = user
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1104): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1104): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1104): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1104): run()
I/StatsUtilsManager( 1104): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1104): shouldRecordStats() = Too Soon
D/BackupManagerService(  761): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  761): Receieved: android.intent.action.PACKAGE_REMOVED
,W/ContextImpl( 3588): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
,D/PackageBroadcastService( 1612): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/AccountUtils( 1612): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 1612): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1612): Module APK com.google.android.play.games already loaded
D/TaskPersister(  761): removeObsoleteFile: deleting file=216_task.xml
,D/ChimeraCfgMgr( 1612): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1612): Module APK com.google.android.play.games already loaded
,I/art     (  761): Explicit concurrent mark sweep GC freed 5764(313KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 2.338ms total 122.994ms
,E/NetworkScheduler.SchedulerReceiver( 1563): Invalid parameter app,
E/NetworkScheduler.SchedulerReceiver( 1563): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/LocationSettingsChecker( 1612): Removing dialog suppression flag for package com.test.thalitest
,D/gH_CompatibleDatabase( 1612): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,D/gH_CompatibleDatabase( 1612): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1612): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1612): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/gH_CompatibleDatabase( 1612): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1612): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1612): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/gH_CompatibleDatabase( 1612): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1612): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 1612): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1612): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
,D/gH_CompatibleDatabase( 1612): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1612): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/ActivityManager(  761): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3618 uid=10039 gids={50039, 9997} abi=armeabi-v7a
,I/Launcher( 1321): Deferring update until onResume
,W/BaseAppContext( 1612): Using Auth Proxy for data requests.
,W/ResourcesManager( 1321): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/BaseAppContext( 1612): Using Auth Proxy for data requests.
,I/ActivityManager(  761): Killing 2653:com.android.settings/1000 (adj 15): empty #17
,D/WifiService(  761): Client connection lost with reason: 4
,W/ResourcesManager( 1321): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/AndroidRuntime( 3534): Shutting down VM
,I/Launcher( 1321): Deferring update until onResume
,W/libprocessgroup(  761): failed to open /acct/uid_1000/pid_2653/cgroup.procs: No such file or directory
,I/GMPM-SVC( 1612): App measurement is starting up, version: 8489
I/GMPM-SVC( 1612): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,I/Icing   ( 1612): doRemovePackageData com.test.thalitest
,I/ActivityManager(  761): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3661 uid=10007 gids={50007, 9997, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  761): Killing 2524:com.google.android.gm/u0a70 (adj 15): empty #17
,I/ActivityManager(  761): Killing 1987:com.google.android.calendar/u0a31 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10070/pid_2524/cgroup.procs: No such file or directory
,W/libprocessgroup(  761): failed to open /acct/uid_10031/pid_1987/cgroup.procs: No such file or directory
,E/SQLiteLog( 1612): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/GMPM-SVC( 1612): Task exception on worker thread: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850): com.google.android.gms.measurement.internal.e.b(SourceFile:321)
,D/ExternalStorage( 3661): After updating volumes, found 1 active roots
,E/SharedPreferencesImpl( 1612): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak

```
