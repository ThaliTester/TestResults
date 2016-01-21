#### Test 56449660311ec66_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
I/GAv4    ( 3139): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3139):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3139):   adb logcat -s GAv4
,W/GAv4    ( 3139): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3139): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3139): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 3139): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
E/SQLiteLog( 3139): (283) recovered 25 frames from WAL file /data/data/com.google.android.apps.docs/databases/DocList.db-wal
D/Finsky  ( 2591): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
W/ResourcesManager( 3139): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3139): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  762): Killing 2558:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
V/JNIHelp ( 3139): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/AndroidRuntime( 3188): 
D/AndroidRuntime( 3188): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3188): CheckJNI is OFF
W/System  ( 3139): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3139): Installed default security provider GmsCore_OpenSSL
W/libprocessgroup(  762): failed to open /acct/uid_10069/pid_2558/cgroup.procs: No such file or directory
V/GLSActivity( 1572): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/AndroidRuntime( 3188): Calling main entry com.android.commands.am.Am
I/ActivityManager(  762): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  762): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3213 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3188): Shutting down VM
V/ActivityManager(  762): Display changed displayId=0
I/Icing   ( 1602): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/WebViewFactory( 3213): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3213): Time to load native libraries: 4 ms (timestamps 7628-7632)
I/LibraryLoader( 3213): Expected native library version number "",actual native library version number ""
,I/Icing   ( 1602): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1602): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
V/WebViewChromiumFactoryProvider( 3213): Binding Chromium to main looper Looper (main, tid 1) {1cd80b08}
I/LibraryLoader( 3213): Expected native library version number "",actual native library version number ""
I/chromium( 3213): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3213): Initializing chromium process, singleProcess=true
W/art     ( 3213): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3213): ApplicationContext is null in ApplicationStatus
W/chromium( 3213): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3213): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3213): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3213): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
I/Icing   ( 1602): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
D/BluetoothManagerService(  762): Message: 20
D/BluetoothManagerService(  762): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@15fd1094:true
W/art     ( 3213): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 3213): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 3213): CordovaWebView is running on device made by: LGE
W/art     ( 3213): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3213): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 3213): Render dirty regions requested: true
D/Atlas   ( 3213): Validating map...
W/chromium( 3213): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/OpenGLRenderer( 3213): Initialized EGL, version 1.4
D/OpenGLRenderer( 3213): Enabling debug mode 0
I/ActivityManager(  762): Killing 2513:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
I/Keyboard.Facilitator( 1085): onFinishInput()
W/BindingManager( 3213): Cannot call determinedVisibility() - never saw a connection for the pid: 3213
W/IInputConnectionWrapper( 3213): showStatusIcon on inactive InputConnection
W/libprocessgroup(  762): failed to open /acct/uid_10045/pid_2513/cgroup.procs: No such file or directory
I/ActivityManager(  762): Displayed com.test.thalitest/.MainActivity: +441ms (total +54s820ms)
D/JsMessageQueue( 3213): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 3213): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257332480
I/chromium( 3213): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 3213): Initializing JXcore engine
W/jxcore-log( 3213): JXcore engine is ready
,W/Thread-306( 3274): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[9497]" dev="sockfs" ino=9497 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/Thread-306( 3274): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-306( 3274): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8484]" dev="sockfs" ino=8484 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/Thread-306( 3274): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[19204]" dev="sockfs" ino=19204 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3213): Starting JXcore engine
,W/jxcore-log( 3213): Platform android
W/jxcore-log( 3213): 
W/jxcore-log( 3213): Process ARCH arm
W/jxcore-log( 3213): 
,I/jxcore-log( 3213): JXcore Cordova bridge is ready!
I/jxcore-log( 3213): 
W/jxcore-log( 3213): JXcore engine is started
,I/jxcore-log( 3213): Toggling radios to true
I/jxcore-log( 3213): 
,D/BluetoothAdapter( 3213): enable(): BT is already enabled..!
,D/WifiService(  762): New client listening to asynchronous messages
,D/WifiService(  762): setWifiEnabled: true pid=3213, uid=10270
E/WifiService(  762): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3213): Radios toggled
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): My device name is: LGE-Nexus 5
I/jxcore-log( 3213): 
,I/wpa_supplicant( 1052): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  762): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  762): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/native  (  762): do suspend true
D/CommandListener(  179): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1572): Read error: ssl=0x9db4fe00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1572): SSL shutdown failed: ssl=0x9db4fe00: I/O error during system call, Broken pipe
,D/ConnectivityService(  762): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): ValidatedState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): DefaultState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): EvaluatingState{ when=-1ms what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,E/WifiConfigStore(  762): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  762): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  762): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,E/WifiStateMachine(  762): Start Disconnecting Watchdog 1
I/wpa_supplicant( 1052): wlan0: CTRL-EVENT-SCAN-STARTED 
E/native  (  762): do suspend true
,D/ConnectivityService(  762): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/Nat464Xlat(  762): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/CSLegacyTypeTracker(  762): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): Disconnected - quitting
D/ConnectivityManager.CallbackHandler(  902): CM callback handler got msg 524292
D/ConnectivityService(  762): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  762): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  762): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1602): CM callback handler got msg 524292
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,D/TelephonyNetworkFactory( 1200): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WifiNetworkAgent(  762): NetworkAgent: NetworkAgent channel lost
,I/wpa_supplicant( 1052): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant( 1052): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1052): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1052): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  762): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService(  762): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiConfigStore(  762): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
E/WifiConfigStore(  762): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  179): Setting iface cfg
E/WifiStateMachine(  762): Start Dhcp Watchdog 2
,E/native  (  762): do suspend false
,E/WifiStateMachine(  762): scanCount==0 - aborting
,I/dhcpcd  ( 3301): version 5.5.6 starting
,E/dhcpcd  ( 3301): get_duid: Read-only file system
,I/dhcpcd  ( 3301): wlan0: rebinding lease of 192.168.1.114
,I/dhcpcd  ( 3301): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3301): wlan0: leased 192.168.1.114 for 86400 seconds
,E/native  (  762): do suspend true
,E/WifiStateMachine(  762): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/ConnectivityService(  762): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  762): Adding iface wlan0 to network 101
,E/ConnectivityService(  762): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  762): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/ConnectivityService(  762): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/ConnectivityService(  762): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/ConnectivityService(  762): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  762): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  762): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  762): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  762): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  762):    accepting network in place of null
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/CSLegacyTypeTracker(  762): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  762): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  762): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  762): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  902): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1602): CM callback handler got msg 524290
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 21 Jan 2016 09:17:40 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1453367860301], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1453367860283]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): Validated
,D/ConnectivityService(  762): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  762): rematching NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  762): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  762): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler(  902): CM callback handler got msg 524290
D/ConnectivityService(  762): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/TelephonyNetworkFactory( 1200): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1602): CM callback handler got msg 524290
,D/Nat464Xlat(  762): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  762): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler(  902): CM callback handler got msg 524295
D/ConnectivityManager.CallbackHandler( 1602): CM callback handler got msg 524295
,D/ConnectivityService(  762): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  762): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  762): MasterInitialState.processMessage what=3
,D/Tethering(  762): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2707): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2707): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 2707): type=WIFI subType= reason=null isConnected=true
,I/SystemUpdateService( 1602): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1602): onCreate
,D/SystemUpdateService( 1602): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1602): active receiver: enabled
,E/GpsLocationProvider(  762): No APN found to select.
,I/SystemUpdateService( 1602): showing system update notification
,I/ActivityManager(  762): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3355 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/GpsLocationProvider(  762): No APN found to select.
,I/ValidateNoPeople(  762): skipping global notification
,V/SystemUpdateService( 1602): retry (wakeup: false) in 3599925 ms
D/SystemUpdateService( 1602): onDestroy
,I/GAv4    ( 3355): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3355):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3355):   adb logcat -s GAv4
,W/GAv4    ( 3355): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3355): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3355): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 3355): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3355): Time to load native libraries: 1 ms (timestamps 3755-3756)
,I/LibraryLoader( 3355): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3355): Binding Chromium to main looper Looper (main, tid 1) {27e4d1ba}
I/LibraryLoader( 3355): Expected native library version number "",actual native library version number ""
I/chromium( 3355): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3355): Initializing chromium process, singleProcess=true
,W/art     ( 3355): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3355): ApplicationContext is null in ApplicationStatus
,W/chromium( 3355): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3355): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3355): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3355): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/NSApplication( 3355): Starting up...
,W/AudioManagerAndroid( 3355): Requires BLUETOOTH permission
,V/MusicLeanback( 2707): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1602): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1602): onCreate
,D/SystemUpdateService( 1602): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1602): active receiver: enabled
,I/SystemUpdateService( 1602): showing system update notification
,I/ValidateNoPeople(  762): skipping global notification
V/SystemUpdateService( 1602): retry (wakeup: false) in 3599986 ms
,D/SystemUpdateService( 1602): onDestroy
,D/ConnectivityService(  762): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/ActivityManager(  762): Killing 2686:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,I/jxcore-log( 3213): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3213): 
,W/libprocessgroup(  762): failed to open /acct/uid_10003/pid_2686/cgroup.procs: No such file or directory
,I/jxcore-log( 3213): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 3213): 
,I/jxcore-log( 3213): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3213): 
,D/ConnectivityService(  762): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  762): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2707): type=WIFI subType= reason=null isConnected=true
,E/GpsLocationProvider(  762): No APN found to select.
,V/MusicLeanback( 2707): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1602): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1602): onCreate
,I/art     (  762): Explicit concurrent mark sweep GC freed 44988(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 27MB/41MB, paused 1.470ms total 79.180ms
D/SystemUpdateService( 1602): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1602): active receiver: enabled
,I/SystemUpdateService( 1602): showing system update notification
,I/ValidateNoPeople(  762): skipping global notification
,V/SystemUpdateService( 1602): retry (wakeup: false) in 3599969 ms
,D/SystemUpdateService( 1602): onDestroy
,I/jxcore-log( 3213): Test app app.js loaded
I/jxcore-log( 3213): 
,I/chromium( 3213): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3213): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 3213): BLE advertisement is supported
I/jxcore-log( 3213): 
,D/Finsky  ( 2591): [255] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2591): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/GLSActivity( 1572): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1572): Vacuum at: now=1453367876142 tag=VacuumService
,I/Keyboard.Facilitator.LanguageModelFlusher( 1085): run()
I/Keyboard.Facilitator( 1085): flushDynamicLanguageModels()
,I/ConfigService( 1572): onCreate
,I/ConfigService( 1572): onDestroy
,I/ClearcutLoggerApiImpl( 1572): disconnect managed GoogleApiClient
,I/ActivityManager(  762): Killing 2667:com.android.settings/1000 (adj 15): empty #17
,D/WifiService(  762): Client connection lost with reason: 4
,W/libprocessgroup(  762): failed to open /acct/uid_1000/pid_2667/cgroup.procs: No such file or directory
,I/ActivityManager(  762): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=3509 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,I/GAv4    ( 3509): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3509):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3509):   adb logcat -s GAv4
,W/GAv4    ( 3509): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3509): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3509): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  762): Killing 2532:com.google.android.gm/u0a70 (adj 15): empty #17
,W/libprocessgroup(  762): failed to open /acct/uid_10070/pid_2532/cgroup.procs: No such file or directory
,W/bt-smp  ( 2090): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2090): Plain text(LSB ~ MSB) = d8 f0 40 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2090): Encrypted text(LSB ~ MSB) = 47 d5 cd 1d 3d fa bc 75 37 76 ea ed 5c 72 fb ee 
,W/bt-btm  ( 2090): Stopping oneshot timer
,I/PhenotypeConfigurator( 1572): Scheduling Phenotype for one-off execution 643 seconds from now (1453368766856)
,D/GetConfigurationSnapshotOperation( 1572): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1572): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1572): Using platform SSLCertificateSocketFactory
,I/UsageStatsService(  762): User[0] Flushing usage stats to disk
,TIME-OUT KILL (timeout was 1200000ms)
```
