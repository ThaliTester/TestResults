#### Test 55613145e2b298d_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
D/ChimeraCfgMgr( 1641): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1641): Module APK com.google.android.play.games already loaded
I/GAv4    ( 3382): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3382):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3382):   adb logcat -s GAv4
W/GAv4    ( 3382): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3382): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3382): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 3382): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
D/Finsky  ( 2629): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
I/ActivityManager(  760): Killing 2869:com.google.android.apps.magazines/u0a61 (adj 15): empty #17
W/ResourcesManager( 3382): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3382): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/libprocessgroup(  760): failed to open /acct/uid_10061/pid_2869/cgroup.procs: No such file or directory
V/JNIHelp ( 3382): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/System  ( 3382): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3382): Installed default security provider GmsCore_OpenSSL
V/GLSActivity( 1572): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 1641): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/Icing   ( 1641): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1641): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/Icing   ( 1641): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
,D/AndroidRuntime( 3431): 
D/AndroidRuntime( 3431): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3431): CheckJNI is OFF
D/AndroidRuntime( 3431): Calling main entry com.android.commands.am.Am
I/ActivityManager(  760): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  760): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3445 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3431): Shutting down VM
I/ActivityManager(  760): Killing 3002:com.google.android.apps.cloudprint/u0a35 (adj 15): empty #17
W/libprocessgroup(  760): failed to open /acct/uid_10035/pid_3002/cgroup.procs: No such file or directory
V/ActivityManager(  760): Display changed displayId=0
,I/WebViewFactory( 3445): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3445): Time to load native libraries: 2 ms (timestamps 236-238)
,I/LibraryLoader( 3445): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3445): Binding Chromium to main looper Looper (main, tid 1) {dba4b4d}
I/LibraryLoader( 3445): Expected native library version number "",actual native library version number ""
I/chromium( 3445): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3445): Initializing chromium process, singleProcess=true
W/art     ( 3445): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3445): ApplicationContext is null in ApplicationStatus
,W/chromium( 3445): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3445): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3445): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3445): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  760): Message: 20
D/BluetoothManagerService(  760): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b3fea39:true
,W/art     ( 3445): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3445): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3445): CordovaWebView is running on device made by: LGE
,W/art     ( 3445): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3445): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3445): Render dirty regions requested: true
,D/Atlas   ( 3445): Validating map...
,W/chromium( 3445): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3445): Initialized EGL, version 1.4
D/OpenGLRenderer( 3445): Enabling debug mode 0
,W/IInputConnectionWrapper( 3445): showStatusIcon on inactive InputConnection
,W/BindingManager( 3445): Cannot call determinedVisibility() - never saw a connection for the pid: 3445
,I/ActivityManager(  760): Displayed com.test.thalitest/.MainActivity: +466ms (total +57s533ms)
,D/JsMessageQueue( 3445): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3445): JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1405523712
,D/JX-Cordova( 3445): jxcore cordova android initializing
,W/jxcore-log( 3445): Initializing JXcore engine
W/jxcore-log( 3445): JXcore engine is ready
W/jxcore-log( 3445): Starting JXcore engine
,W/.test.thalitest( 3445): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[8739]" dev="sockfs" ino=8739 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3445): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 3445): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6675]" dev="sockfs" ino=6675 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3445): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[21797]" dev="sockfs" ino=21797 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3445): Platform android
W/jxcore-log( 3445): 
,W/jxcore-log( 3445): Process ARCH arm
W/jxcore-log( 3445): 
,I/jxcore-log( 3445): JXcore Cordova bridge is ready!
I/jxcore-log( 3445): 
,W/jxcore-log( 3445): JXcore engine is started
I/Choreographer( 3445): Skipped 112 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3445): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,V/GLSActivity( 1572): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1572): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 3445): Toggling radios to true
I/jxcore-log( 3445): 
,D/BluetoothAdapter( 3445): enable(): BT is already enabled..!
,D/WifiService(  760): New client listening to asynchronous messages
D/WifiService(  760): setWifiEnabled: true pid=3445, uid=10270
E/WifiService(  760): Invoking mWifiStateMachine.setWifiEnabled
,I/wpa_supplicant( 1023): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,I/jxcore-log( 3445): Radios toggled
I/jxcore-log( 3445): 
E/WifiStateMachine(  760): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  760): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
E/native  (  760): do suspend true
D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 3445): Received device characteristics:
I/jxcore-log( 3445): Bluetooth address: 34:FC:EF:11:AE:67
I/jxcore-log( 3445): Bluetooth name: Nexus 5
I/jxcore-log( 3445): Device name: LGE-Nexus 5
I/jxcore-log( 3445): 
I/jxcore-log( 3445): Perf Test app loaded loaded
I/jxcore-log( 3445): 
I/Choreographer( 3445): Skipped 71 frames!  The application may be doing too much work on its main thread.
D/CommandListener(  179): Clearing all IP addresses on wlan0
V/NativeCrypto( 1572): Read error: ssl=0xb3b42e00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1572): SSL shutdown failed: ssl=0xb3b42e00: I/O error during system call, Broken pipe
,I/jxcore-log( 3445): check test folder
I/jxcore-log( 3445): 
,D/ConnectivityService(  760): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): ValidatedState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): DefaultState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Checking http://clients3.google.com/generate_204 on "NG7005g"
I/jxcore-log( 3445): found test : ./testFindPeers.js
I/jxcore-log( 3445): 
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,I/jxcore-log( 3445): found test : ./testSendData.js
I/jxcore-log( 3445): 
,W/EventLoggerService( 1391): Unable to send logs Read error: ssl=0x9fd7de00: I/O error during system call, Connection timed out
,E/WifiConfigStore(  760): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  760): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  760): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,E/WifiStateMachine(  760): Start Disconnecting Watchdog 1
,I/wpa_supplicant( 1023): wlan0: CTRL-EVENT-SCAN-STARTED 
E/native  (  760): do suspend true
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,D/ConnectivityService(  760): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/Nat464Xlat(  760): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  760): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Disconnected - quitting
D/ConnectivityService(  760): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler(  899): CM callback handler got msg 524292
,D/TelephonyNetworkFactory( 1272): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 1641): CM callback handler got msg 524292
,D/WifiNetworkAgent(  760): NetworkAgent: NetworkAgent channel lost
,I/chromium( 3445): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/wpa_supplicant( 1023): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant( 1023): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1023): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1023): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  760): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  760): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  760): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  760): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  179): Setting iface cfg
,E/WifiStateMachine(  760): Start Dhcp Watchdog 2
,E/native  (  760): do suspend false
,E/WifiStateMachine(  760): scanCount==0 - aborting
,I/dhcpcd  ( 3536): version 5.5.6 starting
,E/dhcpcd  ( 3536): get_duid: Read-only file system
,I/dhcpcd  ( 3536): wlan0: rebinding lease of 192.168.1.114
,I/dhcpcd  ( 3536): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3536): wlan0: leased 192.168.1.114 for 86400 seconds
,E/native  (  760): do suspend true
,D/ConnectivityService(  760): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  760): Adding iface wlan0 to network 101
,E/WifiStateMachine(  760): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  760): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  760): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  760): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  760): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  760): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  760): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  760): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  760): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  760): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  760):    accepting network in place of null
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Connected
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/CSLegacyTypeTracker(  760): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  760): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  760): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler(  899): CM callback handler got msg 524290
D/ConnectivityManager.CallbackHandler( 1641): CM callback handler got msg 524290
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 11 Jan 2016 14:39:58 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452523198830], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452523198810]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Validated
,D/ConnectivityService(  760): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  760): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  760): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  760): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  899): CM callback handler got msg 524290
D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/TelephonyNetworkFactory( 1272): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1641): CM callback handler got msg 524290
,D/Nat464Xlat(  760): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  760): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  899): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 1641): CM callback handler got msg 524295
,D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  760): MasterInitialState.processMessage what=3
,D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  760): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2747): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2747): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 2747): type=WIFI subType= reason=null isConnected=true
,I/SystemUpdateService( 1641): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1641): onCreate
,D/SystemUpdateService( 1641): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,E/GpsLocationProvider(  760): No APN found to select.
,E/GpsLocationProvider(  760): No APN found to select.
,I/SystemUpdateService( 1641): active receiver: enabled
,I/SystemUpdateService( 1641): showing system update notification
,I/ValidateNoPeople(  760): skipping global notification
,V/SystemUpdateService( 1641): retry (wakeup: false) in 3599983 ms
,I/ActivityManager(  760): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3609 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/SystemUpdateService( 1641): onDestroy
,D/ConnectivityService(  760): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/GAv4    ( 3609): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3609):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3609):   adb logcat -s GAv4
,W/GAv4    ( 3609): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3609): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3609): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 3609): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3609): Time to load native libraries: 1 ms (timestamps 7365-7366)
,I/LibraryLoader( 3609): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3609): Binding Chromium to main looper Looper (main, tid 1) {3d3fba37}
,I/LibraryLoader( 3609): Expected native library version number "",actual native library version number ""
I/chromium( 3609): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3609): Initializing chromium process, singleProcess=true
,W/art     ( 3609): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3609): ApplicationContext is null in ApplicationStatus
,W/chromium( 3609): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3609): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3609): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3609): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/NSApplication( 3609): Starting up...
,W/AudioManagerAndroid( 3609): Requires BLUETOOTH permission
,I/ActivityManager(  760): Killing 2962:com.google.android.apps.cloudprint:sync/u0a35 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10035/pid_2962/cgroup.procs: No such file or directory
,V/MusicLeanback( 2747): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1641): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1641): onCreate
,D/SystemUpdateService( 1641): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1641): active receiver: enabled
,I/SystemUpdateService( 1641): showing system update notification
,I/ValidateNoPeople(  760): skipping global notification
,V/SystemUpdateService( 1641): retry (wakeup: false) in 3599954 ms
,I/art     (  760): Explicit concurrent mark sweep GC freed 41803(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 28MB/42MB, paused 3.489ms total 63.749ms
,D/SystemUpdateService( 1641): onDestroy
,W/ProcessCpuTracker(  760): Skipping unknown process pid 3588
,W/ProcessCpuTracker(  760): Skipping unknown process pid 3591
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): setDiscoveryMode: Mode set to WIFI
,I/jxcore-log( 3445): BLE is supported
I/jxcore-log( 3445): 
,D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  760): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2747): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2747): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1641): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1641): onCreate
,D/SystemUpdateService( 1641): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1641): active receiver: enabled
,I/SystemUpdateService( 1641): showing system update notification
,I/ValidateNoPeople(  760): skipping global notification
,E/GpsLocationProvider(  760): No APN found to select.
,V/SystemUpdateService( 1641): retry (wakeup: false) in 3599984 ms
,D/SystemUpdateService( 1641): onDestroy
,D/Finsky  ( 2629): [255] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2629): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/GLSActivity( 1572): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1572): Vacuum at: now=1452523212675 tag=VacuumService
,I/ClearcutLoggerApiImpl( 1572): disconnect managed GoogleApiClient
,I/jxcore-log( 3445): Connected to the server!
I/jxcore-log( 3445): 
,I/chromium( 3445): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3445): --- start :testFindPeers.js---
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): testFindPeers created [object Object]
I/jxcore-log( 3445): 
I/jxcore-log( 3445): serverPort is 8876
I/jxcore-log( 3445): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): setDiscoveryMode: Mode set to WIFI
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3445): start: Peer ID: 34:FC:EF:11:AE:67, peer name: Nexus 5
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3445): bind: Binding a new listener
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3445): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3445): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"Nexus 5","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3445): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3445): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3445): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3445): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3445): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3445): start: OK
I/io.jxcore.node.ConnectionHelper( 3445): start: Using peer discovery mode: WIFI
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): start: Peer ID: 34:FC:EF:11:AE:67, peer name: Nexus 5
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3445): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"Nexus 5","ra":"34:FC:EF:11:AE:67"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3445): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3445): start: {"pi":"34:FC:EF:11:AE:67","pn":"Nexus 5","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3445): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"Nexus 5","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3445): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3445): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3445): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3445): start: OK
I/jxcore-log( 3445): StartBroadcasting started ok
I/jxcore-log( 3445): 
,I/chromium( 3445): [INFO:CONSOLE(63)] "logCallback --- start :testFindPeers.js---", source: file:///android_asset/www/js/thali_main.js (63)
I/io.jxcore.node.ConnectionHelper( 3445): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3445): Local service added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3445): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3445): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3445): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3445): onDiscoveryManagerStateChanged: RUNNING
,I/wpa_supplicant( 1023): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1023): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1023): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1023): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3445): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3445): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/WifiP2pManager( 3445): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3445): Service request added successfully
,I/wpa_supplicant( 1023): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1023): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3445): onP2pDeviceListChanged: 3 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
,I/wpa_supplicant( 1023): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3445): Service discovery started successfully
,I/wpa_supplicant( 1023): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1023): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3445): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3445): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3445): setState: RESTARTING
,I/wpa_supplicant( 1023): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1023): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant( 1023): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 1023): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3445): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3445): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3445): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3445): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3445): Start timer timeout, starting now...
,I/wpa_supplicant( 1023): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3445): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3445): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3445): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1023): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1023): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1023): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3445): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3445): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3445): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3445): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
,D/WifiP2pManager( 3445): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3445): Service request added successfully
,I/wpa_supplicant( 1023): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1023): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1023): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1023): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3445): Service discovery started successfully
,I/wpa_supplicant( 1023): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1023): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3445): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): onP2pDeviceListChanged: Peer 4: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3445): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): onP2pDeviceListChanged: Peer 4: G3-1 02:9a:02:7b:60:ac
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3445): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"Note4-1","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local.",
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3445): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 Note4-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3445): onServiceDiscovered: [E0:DB:10:14:E2:C0 Note4-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): onPeerDiscovered: [E0:DB:10:14:E2:C0 Note4-1]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 Note4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): modifyListOfDiscoveredPeers: Adding new peer: [E0:DB:10:14:E2:C0 Note4-1]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3445): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3445): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3445): onServiceDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/io.jxcore.node.ConnectionHelper( 3445): onPeerDiscovered: [E0:DB:10:14:E2:C0 Note4-1], Bluetooth address: E0:DB:10:14:E2:C0, device name: Note4-1, device address: 92:b6:86:43:73:1c
,D/io.jxcore.node.ConnectionHelper( 3445): notifyPeerAvailability: Peer [E0:DB:10:14:E2:C0 Note4-1] is available
,I/jxcore-log( 3445): peerAvailabilityChanged [{"peerIdentifier":"E0:DB:10:14:E2:C0","peerName":"Note4-1","peerAvailable":true}]
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): Found peer : E0:DB:10:14:E2:C0, peerAvailable: true
I/jxcore-log( 3445): 
I/io.jxcore.node.ConnectionHelper( 3445): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
,D/io.jxcore.node.ConnectionHelper( 3445): notifyPeerAvailability: Peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)] is available
I/jxcore-log( 3445): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:51:18:22","peerName":"Thali Test (Galaxy A5)","peerAvailable":true}]
I/jxcore-log( 3445): 
I/jxcore-log( 3445): Found peer : 7C:F9:0E:51:18:22, peerAvailable: true
I/jxcore-log( 3445): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3445): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3445): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3445): onServiceDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): onPeerDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): modifyListOfDiscoveredPeers: Adding new peer: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
I/io.jxcore.node.ConnectionHelper( 3445): onPeerDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
D/io.jxcore.node.ConnectionHelper( 3445): notifyPeerAvailability: Peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)] is available
I/jxcore-log( 3445): peerAvailabilityChanged [{"peerIdentifier":"B0:C5:59:3F:75:69","peerName":"Thali Test (Galaxy S5)","peerAvailable":true}]
I/jxcore-log( 3445): 
I/jxcore-log( 3445): Found peer : B0:C5:59:3F:75:69, peerAvailable: true
I/jxcore-log( 3445): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3445): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3445): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3445): onServiceDiscovered: [58:3F:54:73:64:C0 G3-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): onPeerDiscovered: [58:3F:54:73:64:C0 G3-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 G3-1]
I/io.jxcore.node.ConnectionHelper( 3445): onPeerDiscovered: [58:3F:54:73:64:C0 G3-1], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
D/io.jxcore.node.ConnectionHelper( 3445): notifyPeerAvailability: Peer [58:3F:54:73:64:C0 G3-1] is available
I/jxcore-log( 3445): peerAvailabilityChanged [{"peerIdentifier":"58:3F:54:73:64:C0","peerName":"G3-1","peerAvailable":true}]
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): Found peer : 58:3F:54:73:64:C0, peerAvailable: true
I/jxcore-log( 3445): 
,I/wpa_supplicant( 1023): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1023): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1023): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1023): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3445): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 Note4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 Note4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3445): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3445): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 Note4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 Note4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
,D/WifiP2pManager( 3445): Ignored { when=-3ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3445): Service request added successfully
,I/wpa_supplicant( 1023): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1023): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1023): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3445): Service discovery started successfully
,I/wpa_supplicant( 1023): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1023): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3445): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 Note4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 Note4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3445): onP2pDeviceListChanged: 7 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac,
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 Note4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 Note4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3445): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3445): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3445): setState: RESTARTING
,I/wpa_supplicant( 1023): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1023): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 1023): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant( 1023): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 1023): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 1023): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant( 1023): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 1023): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3445): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3445): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3445): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3445): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3445): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3445): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3445): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3445): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3445): Start timer timeout, starting now...
,I/wpa_supplicant( 1023): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3445): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3445): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3445): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1023): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3445): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3445): restart: Restarting...
,D/WifiP2pManager( 3445): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3445): Service request added successfully
,I/wpa_supplicant( 1023): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1023): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1023): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3445): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
,I/wpa_supplicant( 1023): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1023): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3445): Service discovery started successfully
,I/wpa_supplicant( 1023): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3445): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
,I/jxcore-log( 3445): timeout now
I/jxcore-log( 3445): 
I/jxcore-log( 3445): weAreDoneNow
I/jxcore-log( 3445): 
I/jxcore-log( 3445): done, now sending data to server
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): teardown
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): testFindPeers stopped
I/jxcore-log( 3445): 
I/io.jxcore.node.ConnectionHelper( 3445): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3445): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3445): Shutting down...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3445): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3445): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3445): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3445): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3445): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3445): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3445): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3445): stop: Stopping P2P device discovery...
,I/wpa_supplicant( 1023): P2P-FIND-STOPPED 
I/wpa_supplicant( 1023): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant( 1023): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3445): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3445): release: No more listeners, de-initializing...
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3445): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3445): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): setState: NOT_STARTED
,I/jxcore-log( 3445): StopBroadcasting went ok
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): --- start :testSendData.js---
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":14}bt-address length : 13
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): daya100000
I/jxcore-log( 3445): 
I/jxcore-log( 3445): check server
I/jxcore-log( 3445): 
I/jxcore-log( 3445): serverPort is 36482
I/jxcore-log( 3445): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): setDiscoveryMode: Mode set to WIFI
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3445): start: Peer ID: 34:FC:EF:11:AE:67, peer name: Nexus 5
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3445): bind: Binding a new listener
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3445): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3445): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"Nexus 5","ra":"34:FC:EF:11:AE:67"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3445): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3445): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3445): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3445): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3445): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3445): start: OK
I/io.jxcore.node.ConnectionHelper( 3445): start: Using peer discovery mode: WIFI
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): start: Peer ID: 34:FC:EF:11:AE:67, peer name: Nexus 5
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3445): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"Nexus 5","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3445): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3445): start: {"pi":"34:FC:EF:11:AE:67","pn":"Nexus 5","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3445): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"Nexus 5","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3445): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3445): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3445): start: OK
I/jxcore-log( 3445): StartBroadcasting started ok
I/jxcore-log( 3445): 
,I/wpa_supplicant( 1023): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3445): Waiting for incoming connections...
,I/jxcore-log( 3445): [ { address: 'E0:DB:10:14:E2:C0', tryCount: 0 },
I/jxcore-log( 3445):   { address: 'F8:95:C7:87:3C:51', tryCount: 0 },
I/jxcore-log( 3445):   { address: '7C:F9:0E:51:18:22', tryCount: 0 },
I/jxcore-log( 3445):   { address: 'B0:C5:59:3F:75:69', tryCount: 0 },
I/jxcore-log( 3445):   { address: '7C:F9:0E:37:96:AB', tryCount: 0 },
I/jxcore-log( 3445):   { address: '90:E7:C4:F6:69:77', tryCount: 0 },
I/jxcore-log( 3445):   { address: 'F8:95:C7:87:85:54', tryCount: 0 },
I/jxcore-log( 3445):   { address: '7C:F9:0E:34:8A:A0', tryCount: 0 },
I/jxcore-log( 3445):   { address: '58:3F:54:73:64:C0', tryCount: 0 },
I/jxcore-log( 3445):   { address: '08:EC:A9:50:76:27', tryCount: 0 },
I/jxcore-log( 3445):   { address: '44:80:EB:7B:5A:05', tryCount: 0 },
I/jxcore-log( 3445):   { address: 'F4:F1:E1:5C:3B:E2', tryCount: 0 },
I/jxcore-log( 3445):   { address: '08:EC:A9:50:75:41', tryCount: 0 } ]
I/jxcore-log( 3445): 
I/jxcore-log( 3445): startWithNextDevice
I/jxcore-log( 3445): 
I/jxcore-log( 3445): do fake peer & start
I/jxcore-log( 3445): 
I/jxcore-log( 3445): Connect to fake peer: E0:DB:10:14:E2:C0
I/jxcore-log( 3445): 
I/jxcore-log( 3445): 2016-01-11T14:47:38.818Z SendDataConnector.js: Start called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3445): 
I/jxcore-log( 3445): 2016-01-11T14:47:38.819Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3445): 
I/jxcore-log( 3445): 2016-01-11T14:47:38.819Z SendDataConnector.js: do connect now
I/jxcore-log( 3445): 
I/io.jxcore.node.ConnectionHelper( 3445): connect: Trying to connect to peer with ID E0:DB:10:14:E2:C0
D/io.jxcore.node.ConnectionHelper( 3445): hasConnection: No connection with peer with ID E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3445): connect: [E0:DB:10:14:E2:C0 Note4-1]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3445): connect: Trying to start connecting to null in address E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3445): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3445): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3445): onConnecting: null E0:DB:10:14:E2:C0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3445): connect: Started connecting to null in address E0:DB:10:14:E2:C0
I/io.jxcore.node.ConnectionHelper( 3445): connect: Connection process successfully started (peer ID: E0:DB:10:14:E2:C0)
I/jxcore-log( 3445): 2016-01-11T14:47:38.823Z SendDataTCPServer.js: TCP/IP server is bound to port: 36482
I/jxcore-log( 3445): 
I/chromium( 3445): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
I/io.jxcore.node.ConnectionHelper( 3445): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3445): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3445): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3445): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 3445): onDiscoveryManagerStateChanged: NOT_STARTED
I/chromium( 3445): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
I/io.jxcore.node.ConnectionHelper( 3445): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3445): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3445): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3445): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3445): setState: RESTARTING
,I/wpa_supplicant( 1023): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3445): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3445): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3445): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3445): onDiscoveryManagerStateChanged: RUNNING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3445): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3445): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3445): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3445): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3445): Trying to connect to peer with address E0:DB:10:14:E2:C0 (thread ID: 329)
W/BluetoothAdapter( 3445): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 2063): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2063): info:x10
,D/        ( 2063): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,E/BluetoothRemoteDevices( 2063): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2063): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2063): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 1
E/bt-btif ( 2063): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2063): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2063): Entering PendingCommandState State
,I/ActivityManager(  760): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.BluetoothPairingRequest: pid=3774 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,D/BluetoothManagerService(  760): Message: 20
D/BluetoothManagerService(  760): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@17d25214:true
,I/ActivityManager(  760): Killing 2559:com.google.android.gm/u0a70 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10070/pid_2559/cgroup.procs: No such file or directory
,I/BluetoothBondStateMachine( 2063): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 0
,D/BluetoothAdapterProperties( 2063): Failed to remove device: E0:DB:10:14:E2:C0
,I/BluetoothBondStateMachine( 2063): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2063): StableState(): Entering Off State
,W/bt-btif ( 2063): new conn_srvc id:26, app_id:1
W/bt-btif ( 2063): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2063): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3445): onSocketConnected: [E0:DB:10:14:E2:C0 Note4-1]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3445): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 329)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3445): onBytesWritten: 66 bytes successfully written (thread ID: 330)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3445): Outgoing connection initialized (*handshake* thread ID: 330)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3445): Exiting thread (thread ID: 329)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3445): Entering thread (ID: 330)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3445): onBytesRead: Read 66 bytes successfully (thread ID: 330)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3445): Handshake succeeded with [E0:DB:10:14:E2:C0 Note4-1]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3445): onHandshakeSucceeded: [E0:DB:10:14:E2:C0 Note4-1]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3445): onConnected: [E0:DB:10:14:E2:C0 Note4-1]
I/io.jxcore.node.ConnectionHelper( 3445): onConnected: Outgoing connection to peer [E0:DB:10:14:E2:C0 Note4-1]
,D/io.jxcore.node.ConnectionHelper( 3445): hasConnection: No connection with peer with ID E0:DB:10:14:E2:C0
W/io.jxcore.node.ConnectionHelper( 3445): modifyListOfDiscoveredPeers: Peer [E0:DB:10:14:E2:C0 Note4-1] already in the list, will not add again
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3445): Exiting thread (ID: 330)
,I/io.jxcore.node.ConnectionHelper( 3445): onConnected: Outgoing socket thread, for peer [E0:DB:10:14:E2:C0 Note4-1], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3445): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 3445): onConnected: The total number of connections is now 1
D/io.jxcore.node.OutgoingSocketThread( 3445): Entering thread (ID: 331)
D/io.jxcore.node.OutgoingSocketThread( 3445): Server socket local port: 54819
I/io.jxcore.node.OutgoingSocketThread( 3445): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3445): onListeningForIncomingConnections: Outgoing connection is using port 54819 (peer ID: E0:DB:10:14:E2:C0)
I/jxcore-log( 3445): 2016-01-11T14:47:40.782Z SendDataConnector.js: CLIENT connected to 54819, error: null
I/jxcore-log( 3445): 
I/jxcore-log( 3445): 2016-01-11T14:47:40.782Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:47:40.786Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3445): 
,I/io.jxcore.node.OutgoingSocketThread( 3445): Incoming data from address: /127.0.0.1, port: 54819
D/io.jxcore.node.OutgoingSocketThread( 3445): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3445): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3445): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3445): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3445): Exiting thread (ID: 331)
,D/io.jxcore.node.StreamCopyingThread( 3445): Entering thread (ID: 332, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 3445): Entering thread (ID: 333, name: Receiver)
,D/        ( 2063): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:40230
,I/jxcore-log( 3445): 2016-01-11T14:47:41.892Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:47:41.968Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3445): 
,D/        ( 2063): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:1620
,I/jxcore-log( 3445): 2016-01-11T14:47:42.702Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:47:42.717Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:47:42.841Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:47:42.952Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3445): 
I/jxcore-log( 3445): 2016-01-11T14:47:42.953Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3445): 
I/jxcore-log( 3445): oneRoundDownNow
I/jxcore-log( 3445): 
I/jxcore-log( 3445): 2016-01-11T14:47:42.957Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:47:42.958Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3445): 
,D/io.jxcore.node.ConnectionHelper( 3445): disconnectOutgoingConnection: Trying to close connection to peer with ID E0:DB:10:14:E2:C0
I/io.jxcore.node.ConnectionHelper( 3445): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: E0:DB:10:14:E2:C0
I/io.jxcore.node.OutgoingSocketThread( 3445): close
D/io.jxcore.node.OutgoingSocketThread( 3445): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3445): doStop: Thread ID: 333
D/io.jxcore.node.OutgoingSocketThread( 3445): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3445): doStop: Thread ID: 332
D/io.jxcore.node.OutgoingSocketThread( 3445): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 3445): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3445): Either failed to read from the output stream or write to the input stream (thread ID: 332, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3445): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3445): onDisconnected: Outgoing connection, peer [E0:DB:10:14:E2:C0 Note4-1] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 3445): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 3445): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3445): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3445): Either failed to read from the output stream or write to the input stream (thread ID: 333, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 3445): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3445): onDisconnected: Outgoing connection, peer [E0:DB:10:14:E2:C0 Note4-1] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3445): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3445): disconnectOutgoingConnection: Successfully disconnected (peer ID: E0:DB:10:14:E2:C0
,E/io.jxcore.node.ConnectionHelper( 3445): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID E0:DB:10:14:E2:C0
D/io.jxcore.node.ConnectionHelper( 3445): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,E/io.jxcore.node.ConnectionHelper( 3445): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID E0:DB:10:14:E2:C0
,D/io.jxcore.node.ConnectionHelper( 3445): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3445): Exiting thread (ID: 333, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3445): Exiting thread (ID: 332, name: Sender)
,I/jxcore-log( 3445): 2016-01-11T14:47:43.007Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3445): 
I/jxcore-log( 3445): ---- round done--------
I/jxcore-log( 3445): 
I/jxcore-log( 3445): startWithNextDevice
I/jxcore-log( 3445): 
I/jxcore-log( 3445): do fake peer & start
I/jxcore-log( 3445): 
I/jxcore-log( 3445): Connect to fake peer: F8:95:C7:87:3C:51
I/jxcore-log( 3445): 
I/jxcore-log( 3445): 2016-01-11T14:47:43.008Z SendDataConnector.js: Start called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3445): 
I/jxcore-log( 3445): 2016-01-11T14:47:43.008Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3445): 
I/jxcore-log( 3445): 2016-01-11T14:47:43.008Z SendDataConnector.js: do connect now
I/jxcore-log( 3445): 
I/io.jxcore.node.ConnectionHelper( 3445): connect: Trying to connect to peer with ID F8:95:C7:87:3C:51
D/io.jxcore.node.ConnectionHelper( 3445): hasConnection: No connection with peer with ID F8:95:C7:87:3C:51
W/io.jxcore.node.ConnectionHelper( 3445): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3445): connect: [F8:95:C7:87:3C:51 F8:95:C7:87:3C:51]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3445): connect: Trying to start connecting to null in address F8:95:C7:87:3C:51
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3445): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3445): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3445): onConnecting: null F8:95:C7:87:3C:51
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3445): connect: Started connecting to null in address F8:95:C7:87:3C:51
I/io.jxcore.node.ConnectionHelper( 3445): connect: Connection process successfully started (peer ID: F8:95:C7:87:3C:51)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3445): Trying to connect to peer with address F8:95:C7:87:3C:51 (thread ID: 334)
W/BluetoothAdapter( 3445): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2063): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2063): tBTM_SEC_DEV:0xa3d50ebc rs_disc_pending=1
,W/bt-btif ( 2063): bta_dm_check_av:0
,W/bt-btif ( 2063): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2063): bta_jv_rfc_port_to_cb(port_handle:0x9):jv handle:0x0 not FOUND
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3445): Start timer timeout, starting now...
,I/wpa_supplicant( 1023): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3445): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3445): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3445): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,E/bt-btm  ( 2063): tBTM_SEC_DEV:0xa3d50ebc rs_disc_pending=0
W/bt-btif ( 2063): bta_dm_check_av:0
,W/bt-btif ( 2063): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2063): info:x10
,D/        ( 2063): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,E/BluetoothRemoteDevices( 2063): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2063): tBTM_SEC_DEV:0xa3d50ebc rs_disc_pending=1
W/bt-btif ( 2063): bta_dm_check_av:0
,W/bt-btif ( 2063): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 2063): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2063): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
E/bt-btif ( 2063): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2063): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2063): Entering PendingCommandState State
,I/wpa_supplicant( 1023): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BluetoothBondStateMachine( 2063): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,D/BluetoothAdapterProperties( 2063): Failed to remove device: F8:95:C7:87:3C:51
,I/BluetoothBondStateMachine( 2063): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2063): StableState(): Entering Off State
,W/bt-btif ( 2063): new conn_srvc id:26, app_id:1
W/bt-btif ( 2063): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2063): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3445): onSocketConnected: [F8:95:C7:87:3C:51 F8:95:C7:87:3C:51]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3445): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 334)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3445): onBytesWritten: 66 bytes successfully written (thread ID: 335)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3445): Outgoing connection initialized (*handshake* thread ID: 335)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3445): Exiting thread (thread ID: 334)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3445): Entering thread (ID: 335)
,I/wpa_supplicant( 1023): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 2063): tBTM_SEC_DEV:0xa3d50ebc rs_disc_pending=0
W/bt-btif ( 2063): bta_dm_check_av:0
,W/bt-btif ( 2063): btif_dm_cback : unhandled event (14)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3445): onBytesRead: Read 63 bytes successfully (thread ID: 335)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3445): Handshake succeeded with [F8:95:C7:87:3C:51 G4-1]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3445): onHandshakeSucceeded: [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3445): Exiting thread (ID: 335)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3445): onConnected: [F8:95:C7:87:3C:51 G4-1]
I/io.jxcore.node.ConnectionHelper( 3445): onConnected: Outgoing connection to peer [F8:95:C7:87:3C:51 G4-1]
D/io.jxcore.node.ConnectionHelper( 3445): hasConnection: No connection with peer with ID F8:95:C7:87:3C:51
D/io.jxcore.node.ConnectionHelper( 3445): notifyPeerAvailability: Peer [F8:95:C7:87:3C:51 G4-1] is available
I/io.jxcore.node.ConnectionHelper( 3445): onConnected: Outgoing socket thread, for peer [F8:95:C7:87:3C:51 G4-1], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3445): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 3445): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 3445): Entering thread (ID: 336)
,D/io.jxcore.node.OutgoingSocketThread( 3445): Server socket local port: 55075
I/io.jxcore.node.OutgoingSocketThread( 3445): Now accepting connections...
,I/wpa_supplicant( 1023): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3445): onP2pDeviceListChanged: 1 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,D/WifiP2pManager( 3445): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3445): Service request added successfully
,I/io.jxcore.node.ConnectionHelper( 3445): onListeningForIncomingConnections: Outgoing connection is using port 55075 (peer ID: F8:95:C7:87:3C:51)
I/jxcore-log( 3445): 2016-01-11T14:47:46.679Z SendDataConnector.js: CLIENT connected to 55075, error: null
I/jxcore-log( 3445): 
I/jxcore-log( 3445): 2016-01-11T14:47:46.679Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3445): 
,I/io.jxcore.node.OutgoingSocketThread( 3445): Incoming data from address: /127.0.0.1, port: 55075
D/io.jxcore.node.OutgoingSocketThread( 3445): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3445): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3445): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3445): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3445): Exiting thread (ID: 336)
,I/jxcore-log( 3445): 2016-01-11T14:47:46.683Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3445): 
,D/io.jxcore.node.StreamCopyingThread( 3445): Entering thread (ID: 338, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3445): Entering thread (ID: 337, name: Sender)
,I/wpa_supplicant( 1023): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1023): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3445): Service discovery started successfully
,I/wpa_supplicant( 1023): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/        ( 2063): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:41220
,I/jxcore-log( 3445): 2016-01-11T14:47:48.014Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3445): 
,D/        ( 2063): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:29340
,I/jxcore-log( 3445): 2016-01-11T14:47:48.163Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:47:48.287Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3445): 
,D/        ( 2063): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:7560
,I/jxcore-log( 3445): 2016-01-11T14:47:48.389Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3445): 
,E/bt-btm  ( 2063): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2063): onReceive
,D/BluetoothManagerService(  760): Message: 20
D/BluetoothManagerService(  760): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3727c8b2:true
,I/BTConnectionReceiver( 1391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1391): Bluetooth Device Name: Note4-1
,I/jxcore-log( 3445): 2016-01-11T14:47:48.546Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:47:48.612Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:47:48.646Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:47:48.699Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:47:48.801Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:47:48.837Z SendDataConnector.js: CLIENT is data received : 100000,
I/jxcore-log( 3445): 
I/jxcore-log( 3445): 2016-01-11T14:47:48.837Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): oneRoundDownNow
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:47:48.850Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3445): 
I/jxcore-log( 3445): 2016-01-11T14:47:48.850Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3445): 
D/io.jxcore.node.ConnectionHelper( 3445): disconnectOutgoingConnection: Trying to close connection to peer with ID F8:95:C7:87:3C:51
I/io.jxcore.node.ConnectionHelper( 3445): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: F8:95:C7:87:3C:51
I/io.jxcore.node.OutgoingSocketThread( 3445): close
D/io.jxcore.node.OutgoingSocketThread( 3445): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3445): doStop: Thread ID: 338
D/io.jxcore.node.OutgoingSocketThread( 3445): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3445): doStop: Thread ID: 337
D/io.jxcore.node.OutgoingSocketThread( 3445): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 3445): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3445): Either failed to read from the output stream or write to the input stream (thread ID: 337, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3445): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3445): onDisconnected: Outgoing connection, peer [F8:95:C7:87:3C:51 G4-1] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 3445): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 3445): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3445): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3445): Either failed to read from the output stream or write to the input stream (thread ID: 338, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 3445): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3445): onDisconnected: Outgoing connection, peer [F8:95:C7:87:3C:51 G4-1] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3445): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3445): disconnectOutgoingConnection: Successfully disconnected (peer ID: F8:95:C7:87:3C:51
,E/io.jxcore.node.ConnectionHelper( 3445): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:95:C7:87:3C:51
D/io.jxcore.node.ConnectionHelper( 3445): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3445): Exiting thread (ID: 337, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 3445): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:95:C7:87:3C:51
D/io.jxcore.node.ConnectionHelper( 3445): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3445): Exiting thread (ID: 338, name: Receiver)
,I/jxcore-log( 3445): 2016-01-11T14:47:48.891Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): ---- round done--------
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): startWithNextDevice
I/jxcore-log( 3445): 
I/jxcore-log( 3445): do fake peer & start
I/jxcore-log( 3445): 
I/jxcore-log( 3445): Connect to fake peer: 7C:F9:0E:51:18:22
I/jxcore-log( 3445): 
I/jxcore-log( 3445): 2016-01-11T14:47:48.894Z SendDataConnector.js: Start called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:47:48.895Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3445): 
I/jxcore-log( 3445): 2016-01-11T14:47:48.895Z SendDataConnector.js: do connect now
I/jxcore-log( 3445): 
,I/io.jxcore.node.ConnectionHelper( 3445): connect: Trying to connect to peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 3445): hasConnection: No connection with peer with ID 7C:F9:0E:51:18:22
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3445): connect: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3445): connect: Trying to start connecting to null in address 7C:F9:0E:51:18:22
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3445): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3445): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3445): onConnecting: null 7C:F9:0E:51:18:22
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3445): connect: Started connecting to null in address 7C:F9:0E:51:18:22
I/io.jxcore.node.ConnectionHelper( 3445): connect: Connection process successfully started (peer ID: 7C:F9:0E:51:18:22)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3445): Trying to connect to peer with address 7C:F9:0E:51:18:22 (thread ID: 339)
W/BluetoothAdapter( 3445): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2063): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2063): bta_jv_rfc_port_to_cb(port_handle:0xa):jv handle:0x0 not FOUND
,I/wpa_supplicant( 1023): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1,
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3445): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
,D/btif_config_util( 2063): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2063): tBTM_SEC_DEV:0xa3d51084 rs_disc_pending=0
W/bt-btif ( 2063): bta_dm_check_av:0
,W/bt-btif ( 2063): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2063): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2063): onReceive
,I/BTConnectionReceiver( 1391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1391): Bluetooth Device Name: G4-1
,I/wpa_supplicant( 1023): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3445): Connection timeout
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3445): onConnectionTimeout: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/jxcore-log( 3445): 2016-01-11T14:48:03.907Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)] timed out
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:03.910Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)] timed out
I/jxcore-log( 3445): 
I/jxcore-log( 3445): 2016-01-11T14:48:03.912Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3445): 
,W/bt-btif ( 2063): info:x10
,D/        ( 2063): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2063): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 2063): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 1
E/bt-btif ( 2063): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2063): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2063): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2063): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 0
D/BluetoothAdapterProperties( 2063): Failed to remove device: 08:EC:A9:50:75:41
,I/BluetoothBondStateMachine( 2063): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2063): StableState(): Entering Off State
,W/bt-btif ( 2063): new conn_srvc id:26, app_id:255
W/bt-btif ( 2063): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2063): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3445): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3445): Incoming connection initialized (thread ID: 341)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3445): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3445): Entering thread (ID: 341)
,E/bt-btm  ( 2063): tBTM_SEC_DEV:0xa3d51414 rs_disc_pending=0
W/bt-btif ( 2063): bta_dm_check_av:0
,W/bt-btif ( 2063): btif_dm_cback : unhandled event (14)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3445): onBytesRead: Read 63 bytes successfully (thread ID: 341)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3445): Got valid identity from [08:EC:A9:50:75:41 A3-1]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3445): onBytesWritten: 66 bytes successfully written (thread ID: 341)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3445): removeThreadFromList: Removing thread with ID 341
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3445): Handshake thread disposed (thread ID: 341)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3445): onIncomingConnectionConnected: [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3445): Exiting thread (ID: 341)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3445): onConnected: [08:EC:A9:50:75:41 A3-1]
I/io.jxcore.node.ConnectionHelper( 3445): onConnected: Incoming connection to peer [08:EC:A9:50:75:41 A3-1]
D/io.jxcore.node.ConnectionHelper( 3445): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 3445): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 A3-1] is available
I/io.jxcore.node.ConnectionHelper( 3445): onConnected: Incoming socket thread, for peer [08:EC:A9:50:75:41 A3-1], created successfully
D/io.jxcore.node.ConnectionHelper( 3445): onConnected: The total number of connections is now 1
,D/io.jxcore.node.IncomingSocketThread( 3445): Entering thread (ID: 342)
,I/jxcore-log( 3445): 2016-01-11T14:48:08.624Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3445): 
,I/io.jxcore.node.IncomingSocketThread( 3445): Local host address: localhost/127.0.0.1, port: 36482
D/io.jxcore.node.IncomingSocketThread( 3445): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3445): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3445): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3445): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3445): Exiting thread (ID: 342)
,D/io.jxcore.node.StreamCopyingThread( 3445): Entering thread (ID: 344, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3445): Entering thread (ID: 343, name: Sender)
,I/jxcore-log( 3445): 2016-01-11T14:48:08.914Z SendDataConnector.js: re-try now : 7C:F9:0E:51:18:22
I/jxcore-log( 3445): 
I/jxcore-log( 3445): 2016-01-11T14:48:08.915Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:09.762Z SendDataTCPServer.js: TCP/IP server has received 990 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:09.824Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:09.836Z SendDataTCPServer.js: TCP/IP server has received 2970 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:09.842Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:09.874Z SendDataTCPServer.js: TCP/IP server has received 4950 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:09.901Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:09.910Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:09.937Z SendDataTCPServer.js: TCP/IP server has received 8910 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:09.945Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:09.987Z SendDataTCPServer.js: TCP/IP server has received 10890 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:10.014Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:10.051Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:10.075Z SendDataTCPServer.js: TCP/IP server has received 16830 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:10.087Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:10.095Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:10.132Z SendDataTCPServer.js: TCP/IP server has received 20790 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:10.142Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:10.187Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3445): 
I/jxcore-log( 3445): 2016-01-11T14:48:10.190Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:10.221Z SendDataTCPServer.js: TCP/IP server has received 26730 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:10.227Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:10.237Z SendDataTCPServer.js: TCP/IP server has received 28710 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:10.308Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:10.315Z SendDataTCPServer.js: TCP/IP server has received 30690 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:10.324Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:10.361Z SendDataTCPServer.js: TCP/IP server has received 34650 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:10.390Z SendDataTCPServer.js: TCP/IP server has received 35640 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:10.397Z SendDataTCPServer.js: TCP/IP server has received 37620 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:10.437Z SendDataTCPServer.js: TCP/IP server has received 38610 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:10.460Z SendDataTCPServer.js: TCP/IP server has received 39600 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:10.467Z SendDataTCPServer.js: TCP/IP server has received 40590 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:10.479Z SendDataTCPServer.js: TCP/IP server has received 41580 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:10.497Z SendDataTCPServer.js: TCP/IP server has received 42570 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:10.531Z SendDataTCPServer.js: TCP/IP server has received 44550 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:10.550Z SendDataTCPServer.js: TCP/IP server has received 45540 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:10.592Z SendDataTCPServer.js: TCP/IP server has received 46530 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:10.601Z SendDataTCPServer.js: TCP/IP server has received 47520 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:10.622Z SendDataTCPServer.js: TCP/IP server has received 48510 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:10.628Z SendDataTCPServer.js: TCP/IP server has received 49500 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:10.640Z SendDataTCPServer.js: TCP/IP server has received 50490 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:10.663Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:10.701Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:10.708Z SendDataTCPServer.js: TCP/IP server has received 54450 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:10.744Z SendDataTCPServer.js: TCP/IP server has received 55440 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:10.758Z SendDataTCPServer.js: TCP/IP server has received 56430 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:10.790Z SendDataTCPServer.js: TCP/IP server has received 57420 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:10.795Z SendDataTCPServer.js: TCP/IP server has received 58410 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:10.822Z SendDataTCPServer.js: TCP/IP server has received 59400 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:10.828Z SendDataTCPServer.js: TCP/IP server has received 60390 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:10.838Z SendDataTCPServer.js: TCP/IP server has received 61380 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:10.913Z SendDataTCPServer.js: TCP/IP server has received 62370 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:10.922Z SendDataTCPServer.js: TCP/IP server has received 63360 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:10.953Z SendDataTCPServer.js: TCP/IP server has received 65340 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:10.993Z SendDataTCPServer.js: TCP/IP server has received 67320 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:11.000Z SendDataTCPServer.js: TCP/IP server has received 68310 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:11.007Z SendDataTCPServer.js: TCP/IP server has received 69300 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:11.053Z SendDataTCPServer.js: TCP/IP server has received 70290 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:11.065Z SendDataTCPServer.js: TCP/IP server has received 71280 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:11.106Z SendDataTCPServer.js: TCP/IP server has received 72270 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:11.112Z SendDataTCPServer.js: TCP/IP server has received 73260 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:11.119Z SendDataTCPServer.js: TCP/IP server has received 74250 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:11.210Z SendDataTCPServer.js: TCP/IP server has received 75240 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:11.223Z SendDataTCPServer.js: TCP/IP server has received 76230 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:11.263Z SendDataTCPServer.js: TCP/IP server has received 77220 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:11.269Z SendDataTCPServer.js: TCP/IP server has received 78210 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:11.303Z SendDataTCPServer.js: TCP/IP server has received 79200 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:11.312Z SendDataTCPServer.js: TCP/IP server has received 80190 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:11.350Z SendDataTCPServer.js: TCP/IP server has received 81180 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:11.392Z SendDataTCPServer.js: TCP/IP server has received 84150 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:11.415Z SendDataTCPServer.js: TCP/IP server has received 85140 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:11.424Z SendDataTCPServer.js: TCP/IP server has received 86130 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:11.432Z SendDataTCPServer.js: TCP/IP server has received 87120 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:11.457Z SendDataTCPServer.js: TCP/IP server has received 88110 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:11.463Z SendDataTCPServer.js: TCP/IP server has received 89100 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:11.503Z SendDataTCPServer.js: TCP/IP server has received 90090 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:11.535Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:11.570Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:11.579Z SendDataTCPServer.js: TCP/IP server has received 94050 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:11.594Z SendDataTCPServer.js: TCP/IP server has received 96030 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:11.601Z SendDataTCPServer.js: TCP/IP server has received 97020 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:11.666Z SendDataTCPServer.js: TCP/IP server has received 98010 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:11.672Z SendDataTCPServer.js: TCP/IP server has received 99000 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:11.696Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3445): 
,W/bt-btif ( 2063): invalid rfc slot id: 5
,W/io.jxcore.node.StreamCopyingThread( 3445): Either failed to read from the output stream or write to the input stream (thread ID: 344, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 3445): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3445): onDisconnected: Incoming connection, peer [08:EC:A9:50:75:41 A3-1] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3445): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 342
D/io.jxcore.node.IncomingSocketThread( 3445): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3445): doStop: Thread ID: 344
D/io.jxcore.node.IncomingSocketThread( 3445): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3445): doStop: Thread ID: 343
D/io.jxcore.node.IncomingSocketThread( 3445): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 3445): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3445): Either failed to read from the output stream or write to the input stream (thread ID: 343, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3445): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3445): onDisconnected: Incoming connection, peer [08:EC:A9:50:75:41 A3-1] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.IncomingSocketThread( 3445): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 3445): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3445): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3445): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.ConnectionHelper( 3445): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3445): Exiting thread (ID: 343, name: Sender)
D/io.jxcore.node.StreamCopyingThread( 3445): Exiting thread (ID: 344, name: Receiver)
I/jxcore-log( 3445): 2016-01-11T14:48:11.871Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3445): 
,W/bt-rfcomm( 2063): rfc_find_lcid_mcb LCID reused LCID:0x46 current:0x0
W/bt-rfcomm( 2063): RFCOMM_DisconnectInd LCID:0x46
,D/btif_config_util( 2063): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/io.jxcore.node.ConnectionHelper( 3445): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:51:18:22
E/io.jxcore.node.ConnectionHelper( 3445): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 3445): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3445): disconnectOutgoingConnection: Failed to disconnect (peer ID: 7C:F9:0E:51:18:22), either no such connection or failed to close the connection
I/jxcore-log( 3445): 2016-01-11T14:48:13.921Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3445): 
I/jxcore-log( 3445): 2016-01-11T14:48:13.922Z SendDataConnector.js: Connect (retry count 1) to peer 7C:F9:0E:51:18:22 with availability status: true
I/jxcore-log( 3445): 
I/jxcore-log( 3445): 2016-01-11T14:48:13.923Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3445): 
I/jxcore-log( 3445): 2016-01-11T14:48:13.923Z SendDataConnector.js: do connect now
I/jxcore-log( 3445): 
I/io.jxcore.node.ConnectionHelper( 3445): connect: Trying to connect to peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 3445): hasConnection: No connection with peer with ID 7C:F9:0E:51:18:22
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3445): connect: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3445): connect: Trying to start connecting to null in address 7C:F9:0E:51:18:22
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3445): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3445): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3445): onConnecting: null 7C:F9:0E:51:18:22
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3445): connect: Started connecting to null in address 7C:F9:0E:51:18:22
I/io.jxcore.node.ConnectionHelper( 3445): connect: Connection process successfully started (peer ID: 7C:F9:0E:51:18:22)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3445): Trying to connect to peer with address 7C:F9:0E:51:18:22 (thread ID: 345)
W/BluetoothAdapter( 3445): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2063): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2063): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2063): onReceive
,I/BTConnectionReceiver( 1391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1391): Bluetooth Device Name: A3-1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3445): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3445): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3445): setState: RESTARTING
,I/wpa_supplicant( 1023): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1023): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 1023): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3445): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3445): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3445): onP2pDeviceListChanged: 0 device(s) discovered
,W/bt-sdp  ( 2063): SDP - Rcvd conn cnf with error: 0x22  CID 0x44
E/bt-btif ( 2063): DISCOVERY_COMP_EVT slot id:8, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2063): invalid rfc slot id: 8
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3445): shutdown (thread ID: 339)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3445): Exiting thread (thread ID: 339)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3445): Start timer timeout, starting now...
,I/wpa_supplicant( 1023): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3445): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3445): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3445): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1023): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1023): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1023): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2063): info:x10
,D/        ( 2063): remote version info [7c:f9:0e:51:18:22]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2063): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 1023): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2063): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2063): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:51:18:22 newState: 1
E/bt-btif ( 2063): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2063): Bond State Change Intent:7C:F9:0E:51:18:22 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2063): Entering PendingCommandState State
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3445): Connection timeout
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3445): onConnectionTimeout: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/jxcore-log( 3445): 2016-01-11T14:48:28.943Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)] timed out
I/jxcore-log( 3445): 
I/jxcore-log( 3445): 2016-01-11T14:48:28.944Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)] timed out
I/jxcore-log( 3445): 
I/jxcore-log( 3445): 2016-01-11T14:48:28.945Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3445): 
,I/BluetoothBondStateMachine( 2063): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:51:18:22 newState: 0
,D/BluetoothAdapterProperties( 2063): Failed to remove device: 7C:F9:0E:51:18:22
,I/BluetoothBondStateMachine( 2063): Bond State Change Intent:7C:F9:0E:51:18:22 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2063): StableState(): Entering Off State
,I/wpa_supplicant( 1023): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2063): new conn_srvc id:26, app_id:1
W/bt-btif ( 2063): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2063): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3445): onSocketConnected: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3445): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 345)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3445): shutdown (thread ID: 345)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3445): onBytesWritten: 66 bytes successfully written (thread ID: 347)
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3445): Unexpected error: Attempt to invoke virtual method 'long org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread.getId()' on a null object reference
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3445): java.lang.NullPointerException: Attempt to invoke virtual method 'long org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread.getId()' on a null object reference
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3445): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:186)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3445): onConnectionFailed: Unexpected error: Attempt to invoke virtual method 'long org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread.getId()' on a null object reference
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3445): Exiting thread (thread ID: 345)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3445): onConnectionFailed: Unexpected error: Attempt to invoke virtual method 'long org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread.getId()' on a null object reference [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3445): setInsecureRfcommSocketPort: Will use port 1 when trying to connect
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3445): Entering thread (ID: 347)
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3445): Exiting thread (ID: 347)
,W/bt-btif ( 2063): bta_jv_rfc_port_to_cb(port_handle:0xc):jv handle:0x0 not FOUND
,I/wpa_supplicant( 1023): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1023): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1023): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1023): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1023): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1023): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1023): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3445): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3445): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3445): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3445): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3445): Service request added successfully
,I/wpa_supplicant( 1023): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 2063): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2063): onReceive
,I/BTConnectionReceiver( 1391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:51:18:22, alias=null, name=Thali Test (Galaxy A5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1391): Bluetooth Device Name: Thali Test (Galaxy A5)
,I/wpa_supplicant( 1023): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3445): Service discovery started successfully
,I/wpa_supplicant( 1023): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3445): 2016-01-11T14:48:33.947Z SendDataConnector.js: re-try now : 7C:F9:0E:51:18:22
I/jxcore-log( 3445): 
I/jxcore-log( 3445): 2016-01-11T14:48:33.948Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3445): 
,D/btif_config_util( 2063): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/io.jxcore.node.ConnectionHelper( 3445): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:51:18:22
E/io.jxcore.node.ConnectionHelper( 3445): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 3445): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3445): disconnectOutgoingConnection: Failed to disconnect (peer ID: 7C:F9:0E:51:18:22), either no such connection or failed to close the connection
I/jxcore-log( 3445): 2016-01-11T14:48:38.952Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3445): 
I/jxcore-log( 3445): 2016-01-11T14:48:38.952Z SendDataConnector.js: Connect (retry count 2) to peer 7C:F9:0E:51:18:22 with availability status: true
I/jxcore-log( 3445): 
I/jxcore-log( 3445): 2016-01-11T14:48:38.953Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3445): 
I/jxcore-log( 3445): 2016-01-11T14:48:38.953Z SendDataConnector.js: do connect now
I/jxcore-log( 3445): 
I/io.jxcore.node.ConnectionHelper( 3445): connect: Trying to connect to peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 3445): hasConnection: No connection with peer with ID 7C:F9:0E:51:18:22
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3445): connect: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3445): connect: Trying to start connecting to Thali Test (Galaxy A5) in address 7C:F9:0E:51:18:22
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3445): setInsecureRfcommSocketPort: Using port 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3445): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3445): onConnecting: Thali Test (Galaxy A5) 7C:F9:0E:51:18:22
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3445): connect: Started connecting to Thali Test (Galaxy A5) in address 7C:F9:0E:51:18:22
I/io.jxcore.node.ConnectionHelper( 3445): connect: Connection process successfully started (peer ID: 7C:F9:0E:51:18:22)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3445): Trying to connect to peer with address 7C:F9:0E:51:18:22 (thread ID: 348)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3445): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3445): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2063): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2063): SDP - Rcvd conn cnf with error: 0x4  CID 0x49
E/bt-btif ( 2063): DISCOVERY_COMP_EVT slot id:11, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2063): invalid rfc slot id: 11
W/BluetoothAdapter( 3445): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 2063): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2063): info:x10
,D/        ( 2063): remote version info [b0:c5:59:3f:75:69]: 7, f, 610c
,E/BluetoothRemoteDevices( 2063): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2063): tBTM_SEC_DEV:0xa3d515dc rs_disc_pending=0
W/bt-btif ( 2063): bta_dm_check_av:0
,W/bt-btif ( 2063): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 2063): bondStateChangeCallback: Status: 0 Address: B0:C5:59:3F:75:69 newState: 1
E/bt-btif ( 2063): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2063): Bond State Change Intent:B0:C5:59:3F:75:69 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2063): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2063): bondStateChangeCallback: Status: 0 Address: B0:C5:59:3F:75:69 newState: 0
,D/BluetoothAdapterProperties( 2063): Failed to remove device: B0:C5:59:3F:75:69
,I/BluetoothBondStateMachine( 2063): Bond State Change Intent:B0:C5:59:3F:75:69 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2063): StableState(): Entering Off State
,W/bt-btif ( 2063): new conn_srvc id:26, app_id:255
W/bt-btif ( 2063): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2063): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3445): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3445): Incoming connection initialized (thread ID: 349)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3445): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3445): Entering thread (ID: 349)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3445): onBytesRead: Read 81 bytes successfully (thread ID: 349)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3445): Got valid identity from [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3445): onBytesWritten: 66 bytes successfully written (thread ID: 349)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3445): removeThreadFromList: Removing thread with ID 349
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3445): Handshake thread disposed (thread ID: 349)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3445): onIncomingConnectionConnected: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3445): Exiting thread (ID: 349)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3445): onConnected: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
,I/io.jxcore.node.ConnectionHelper( 3445): onConnected: Incoming connection to peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
,D/io.jxcore.node.ConnectionHelper( 3445): hasConnection: No connection with peer with ID B0:C5:59:3F:75:69
W/io.jxcore.node.ConnectionHelper( 3445): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)] already in the list, will not add again,
,I/io.jxcore.node.ConnectionHelper( 3445): onConnected: Incoming socket thread, for peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], created successfully
,D/io.jxcore.node.ConnectionHelper( 3445): onConnected: The total number of connections is now 1
,D/io.jxcore.node.IncomingSocketThread( 3445): Entering thread (ID: 350)
,I/jxcore-log( 3445): 2016-01-11T14:48:51.856Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3445): 
,I/io.jxcore.node.IncomingSocketThread( 3445): Local host address: localhost/127.0.0.1, port: 36482
D/io.jxcore.node.IncomingSocketThread( 3445): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3445): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 3445): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.IncomingSocketThread( 3445): startStreamCopyingThreads: OK
,D/io.jxcore.node.IncomingSocketThread( 3445): Exiting thread (ID: 350)
,D/io.jxcore.node.StreamCopyingThread( 3445): Entering thread (ID: 352, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3445): Entering thread (ID: 351, name: Sender)
,I/jxcore-log( 3445): 2016-01-11T14:48:53.147Z SendDataTCPServer.js: TCP/IP server has received 990 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:53.173Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:53.183Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:53.192Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:53.220Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:53.261Z SendDataTCPServer.js: TCP/IP server has received 9182 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:53.273Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:53.284Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:53.320Z SendDataTCPServer.js: TCP/IP server has received 13142 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:53.351Z SendDataTCPServer.js: TCP/IP server has received 17374 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:53.362Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:53.371Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:53.382Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:53.422Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:53.429Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:53.452Z SendDataTCPServer.js: TCP/IP server has received 29254 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:53.460Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:53.470Z SendDataTCPServer.js: TCP/IP server has received 31234 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:53.503Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:53.507Z SendDataTCPServer.js: TCP/IP server has received 35194 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:53.519Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:53.535Z SendDataTCPServer.js: TCP/IP server has received 37174 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:53.544Z SendDataTCPServer.js: TCP/IP server has received 39154 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:53.551Z SendDataTCPServer.js: TCP/IP server has received 41134 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:53.584Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:53.621Z SendDataTCPServer.js: TCP/IP server has received 45094 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:53.644Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:53.685Z SendDataTCPServer.js: TCP/IP server has received 47074 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:53.696Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:53.723Z SendDataTCPServer.js: TCP/IP server has received 49054 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:53.732Z SendDataTCPServer.js: TCP/IP server has received 51034 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:53.766Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:53.799Z SendDataTCPServer.js: TCP/IP server has received 53014 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:53.808Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:53.823Z SendDataTCPServer.js: TCP/IP server has received 56974 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:53.853Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:53.865Z SendDataTCPServer.js: TCP/IP server has received 58954 bytes of data
I/jxcore-log( 3445): 
I/jxcore-log( 3445): 2016-01-11T14:48:53.867Z SendDataTCPServer.js: TCP/IP server has received 60934 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:53.876Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:53.911Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:53.924Z SendDataTCPServer.js: TCP/IP server has received 66874 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:53.961Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:53.967Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3445): 
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3445): Connection timeout
,I/jxcore-log( 3445): 2016-01-11T14:48:53.975Z SendDataTCPServer.js: TCP/IP server has received 70834 bytes of data
I/jxcore-log( 3445): 
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3445): onConnectionTimeout: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/jxcore-log( 3445): 2016-01-11T14:48:53.983Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)] timed out
I/jxcore-log( 3445): 
I/jxcore-log( 3445): 2016-01-11T14:48:53.983Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)] timed out
I/jxcore-log( 3445): 
I/jxcore-log( 3445): 2016-01-11T14:48:53.984Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:54.001Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:54.028Z SendDataTCPServer.js: TCP/IP server has received 76774 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:54.046Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:54.049Z SendDataTCPServer.js: TCP/IP server has received 78754 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:54.053Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:54.057Z SendDataTCPServer.js: TCP/IP server has received 80734 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:54.087Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:54.118Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:54.124Z SendDataTCPServer.js: TCP/IP server has received 84694 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:54.128Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:54.159Z SendDataTCPServer.js: TCP/IP server has received 86674 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:54.199Z SendDataTCPServer.js: TCP/IP server has received 88654 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:54.240Z SendDataTCPServer.js: TCP/IP server has received 92614 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:54.245Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:54.279Z SendDataTCPServer.js: TCP/IP server has received 94594 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:54.322Z SendDataTCPServer.js: TCP/IP server has received 98554 bytes of data
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:48:54.360Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3445): 
,W/bt-btif ( 2063): invalid rfc slot id: 9
,W/io.jxcore.node.StreamCopyingThread( 3445): Either failed to read from the output stream or write to the input stream (thread ID: 352, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 3445): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3445): onDisconnected: Incoming connection, peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3445): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 350
D/io.jxcore.node.IncomingSocketThread( 3445): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3445): doStop: Thread ID: 352
D/io.jxcore.node.IncomingSocketThread( 3445): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3445): doStop: Thread ID: 351
D/io.jxcore.node.IncomingSocketThread( 3445): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 3445): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3445): Either failed to read from the output stream or write to the input stream (thread ID: 351, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3445): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3445): onDisconnected: Incoming connection, peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.IncomingSocketThread( 3445): closeLocalSocketAndStreams: Closing the local output stream...
,D/io.jxcore.node.IncomingSocketThread( 3445): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3445): closeBluetoothSocketAndStreams
,D/io.jxcore.node.ConnectionHelper( 3445): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.ConnectionHelper( 3445): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.StreamCopyingThread( 3445): Exiting thread (ID: 351, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 3445): Exiting thread (ID: 352, name: Receiver)
,I/jxcore-log( 3445): 2016-01-11T14:48:54.475Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3445): 
,W/bt-rfcomm( 2063): rfc_find_lcid_mcb LCID reused LCID:0x4c current:0x0
W/bt-rfcomm( 2063): RFCOMM_DisconnectInd LCID:0x4c
,D/btif_config_util( 2063): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2063): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2063): onReceive
,I/BTConnectionReceiver( 1391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1391): Bluetooth Device Name: Thali Test (Galaxy S5)
,I/jxcore-log( 3445): 2016-01-11T14:48:58.985Z SendDataConnector.js: re-try now : 7C:F9:0E:51:18:22
I/jxcore-log( 3445): 
I/jxcore-log( 3445): 2016-01-11T14:48:58.986Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3445): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3445): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3445): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3445): setState: RESTARTING
,I/wpa_supplicant( 1023): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1023): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 1023): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3445): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3445): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3445): onP2pDeviceListChanged: 0 device(s) discovered
,D/io.jxcore.node.ConnectionHelper( 3445): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:51:18:22
E/io.jxcore.node.ConnectionHelper( 3445): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 3445): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3445): disconnectOutgoingConnection: Failed to disconnect (peer ID: 7C:F9:0E:51:18:22), either no such connection or failed to close the connection
I/jxcore-log( 3445): 2016-01-11T14:49:03.991Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3445): 
I/jxcore-log( 3445): 2016-01-11T14:49:03.991Z SendDataConnector.js: Connect (retry count 3) to peer 7C:F9:0E:51:18:22 with availability status: true
I/jxcore-log( 3445): 
I/jxcore-log( 3445): 2016-01-11T14:49:03.992Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3445): 
I/jxcore-log( 3445): 2016-01-11T14:49:03.992Z SendDataConnector.js: do connect now
I/jxcore-log( 3445): 
I/io.jxcore.node.ConnectionHelper( 3445): connect: Trying to connect to peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 3445): hasConnection: No connection with peer with ID 7C:F9:0E:51:18:22
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3445): connect: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3445): connect: Trying to start connecting to Thali Test (Galaxy A5) in address 7C:F9:0E:51:18:22
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3445): setInsecureRfcommSocketPort: Using port 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3445): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3445): onConnecting: Thali Test (Galaxy A5) 7C:F9:0E:51:18:22
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3445): connect: Started connecting to Thali Test (Galaxy A5) in address 7C:F9:0E:51:18:22
I/io.jxcore.node.ConnectionHelper( 3445): connect: Connection process successfully started (peer ID: 7C:F9:0E:51:18:22)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3445): Trying to connect to peer with address 7C:F9:0E:51:18:22 (thread ID: 354)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3445): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3445): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2063): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2063): SDP - Rcvd conn cnf with error: 0x8  CID 0x4a
E/bt-btif ( 2063): DISCOVERY_COMP_EVT slot id:12, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2063): invalid rfc slot id: 12
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3445): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 348)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3445): Maximum number of allowed retries (0) reached, giving up... (thread ID: 348)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3445): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3445): Exiting thread (thread ID: 348)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3445): shutdown (thread ID: 348)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3445): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/jxcore-log( 3445): 2016-01-11T14:49:06.047Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)] failed
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:49:06.054Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)] failed
I/jxcore-log( 3445): 
I/jxcore-log( 3445): 2016-01-11T14:49:06.055Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3445): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3445): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3445): Start timer timeout, starting now...
,I/wpa_supplicant( 1023): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3445): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3445): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3445): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1023): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1023): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1023): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1023): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1023): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3445): 2016-01-11T14:49:11.057Z SendDataConnector.js: re-try now : 7C:F9:0E:51:18:22
I/jxcore-log( 3445): 
I/jxcore-log( 3445): 2016-01-11T14:49:11.058Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3445): 
,W/bt-sdp  ( 2063): SDP - Rcvd conn cnf with error: 0x4  CID 0x4d
E/bt-btif ( 2063): DISCOVERY_COMP_EVT slot id:14, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2063): invalid rfc slot id: 14
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3445): shutdown (thread ID: 354)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3445): Exiting thread (thread ID: 354)
,I/wpa_supplicant( 1023): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1023): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3445): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3445): restart: Restarting...
,D/WifiP2pManager( 3445): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3445): Service request added successfully
,I/wpa_supplicant( 1023): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1023): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3445): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
,I/wpa_supplicant( 1023): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1023): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3445): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3445): Service discovery started successfully
,I/wpa_supplicant( 1023): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/ActivityManager(  760): Killing 1955:com.google.android.calendar/u0a31 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10031/pid_1955/cgroup.procs: No such file or directory
,I/wpa_supplicant( 1023): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3445): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3445): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3445): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3445): onServiceDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): onPeerDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): modifyListOfDiscoveredPeers: Adding new peer: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
,I/io.jxcore.node.ConnectionHelper( 3445): onPeerDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
W/io.jxcore.node.ConnectionHelper( 3445): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)] already in the list, will not add again
,D/io.jxcore.node.ConnectionHelper( 3445): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:51:18:22
E/io.jxcore.node.ConnectionHelper( 3445): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 3445): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3445): disconnectOutgoingConnection: Failed to disconnect (peer ID: 7C:F9:0E:51:18:22), either no such connection or failed to close the connection
I/jxcore-log( 3445): 2016-01-11T14:49:16.082Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3445): 
I/jxcore-log( 3445): 2016-01-11T14:49:16.083Z SendDataConnector.js: Connect (retry count 4) to peer 7C:F9:0E:51:18:22 with availability status: true
I/jxcore-log( 3445): 
I/jxcore-log( 3445): 2016-01-11T14:49:16.083Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3445): 
I/jxcore-log( 3445): 2016-01-11T14:49:16.084Z SendDataConnector.js: do connect now
I/jxcore-log( 3445): 
I/io.jxcore.node.ConnectionHelper( 3445): connect: Trying to connect to peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 3445): hasConnection: No connection with peer with ID 7C:F9:0E:51:18:22
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3445): connect: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3445): connect: Trying to start connecting to Thali Test (Galaxy A5) in address 7C:F9:0E:51:18:22
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3445): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3445): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3445): onConnecting: Thali Test (Galaxy A5) 7C:F9:0E:51:18:22
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3445): connect: Started connecting to Thali Test (Galaxy A5) in address 7C:F9:0E:51:18:22
I/io.jxcore.node.ConnectionHelper( 3445): connect: Connection process successfully started (peer ID: 7C:F9:0E:51:18:22)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3445): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3445): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3445): onServiceDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/io.jxcore.node.ConnectionHelper( 3445): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], Bluetooth address: 7C:F9:0E:51:18:22, device name: , device address: 7e:f9:0e:51:18:23
W/io.jxcore.node.ConnectionHelper( 3445): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3445): Trying to connect to peer with address 7C:F9:0E:51:18:22 (thread ID: 356)
W/BluetoothAdapter( 3445): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2063): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2063): info:x10
,D/        ( 2063): remote version info [7c:f9:0e:51:18:22]: 7, f, 610c
,W/bt-sdp  ( 2063): process_service_search_attr_rsp
,I/BTConnectionReceiver( 1391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:51:18:22, alias=null, name=Thali Test (Galaxy A5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1391): Bluetooth Device Name: Thali Test (Galaxy A5)
,W/bt-btif ( 2063): new conn_srvc id:26, app_id:1
W/bt-btif ( 2063): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2063): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3445): onSocketConnected: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3445): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 356)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3445): onBytesWritten: 66 bytes successfully written (thread ID: 357)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3445): Outgoing connection initialized (*handshake* thread ID: 357)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3445): Exiting thread (thread ID: 356)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3445): Entering thread (ID: 357)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3445): onBytesRead: Read 81 bytes successfully (thread ID: 357)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3445): Handshake succeeded with [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3445): onHandshakeSucceeded: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3445): onConnected: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/io.jxcore.node.ConnectionHelper( 3445): onConnected: Outgoing connection to peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/io.jxcore.node.ConnectionHelper( 3445): hasConnection: No connection with peer with ID 7C:F9:0E:51:18:22
W/io.jxcore.node.ConnectionHelper( 3445): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 3445): onConnected: Outgoing socket thread, for peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3445): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 3445): onConnected: The total number of connections is now 1
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3445): Exiting thread (ID: 357)
,D/io.jxcore.node.OutgoingSocketThread( 3445): Entering thread (ID: 358)
D/io.jxcore.node.OutgoingSocketThread( 3445): Server socket local port: 49722
I/io.jxcore.node.OutgoingSocketThread( 3445): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3445): onListeningForIncomingConnections: Outgoing connection is using port 49722 (peer ID: 7C:F9:0E:51:18:22)
I/jxcore-log( 3445): 2016-01-11T14:49:18.152Z SendDataConnector.js: CLIENT connected to 49722, error: null
I/jxcore-log( 3445): 
I/jxcore-log( 3445): 2016-01-11T14:49:18.153Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3445): 
,I/io.jxcore.node.OutgoingSocketThread( 3445): Incoming data from address: /127.0.0.1, port: 49722
D/io.jxcore.node.OutgoingSocketThread( 3445): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3445): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3445): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3445): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3445): Exiting thread (ID: 358)
,I/jxcore-log( 3445): 2016-01-11T14:49:18.177Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3445): 
,D/io.jxcore.node.StreamCopyingThread( 3445): Entering thread (ID: 359, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 3445): Entering thread (ID: 360, name: Receiver)
,I/jxcore-log( 3445): timeout now
I/jxcore-log( 3445): 
I/jxcore-log( 3445): weAreDoneNow, resultArray.length: 2
I/jxcore-log( 3445): 
I/jxcore-log( 3445): sendReportNow
I/jxcore-log( 3445): 
I/jxcore-log( 3445): done, now sending data to server
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:49:19.054Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3445): 
I/jxcore-log( 3445): 2016-01-11T14:49:19.054Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 3445): 
I/jxcore-log( 3445): 2016-01-11T14:49:19.054Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3445): 
D/io.jxcore.node.ConnectionHelper( 3445): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:51:18:22
I/io.jxcore.node.ConnectionHelper( 3445): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 7C:F9:0E:51:18:22
I/io.jxcore.node.OutgoingSocketThread( 3445): close
D/io.jxcore.node.OutgoingSocketThread( 3445): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3445): doStop: Thread ID: 360
D/io.jxcore.node.OutgoingSocketThread( 3445): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3445): doStop: Thread ID: 359
D/io.jxcore.node.OutgoingSocketThread( 3445): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 3445): closeLocalSocketAndStreams: Closing the local input stream...
D/io.jxcore.node.OutgoingSocketThread( 3445): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 3445): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3445): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3445): Either failed to read from the output stream or write to the input stream (thread ID: 360, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 3445): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3445): onDisconnected: Outgoing connection, peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.StreamCopyingThread( 3445): Either failed to read from the output stream or write to the input stream (thread ID: 359, thread name: Sender): Broken pipe
E/io.jxcore.node.OutgoingSocketThread( 3445): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Broken pipe
W/io.jxcore.node.ConnectionHelper( 3445): onDisconnected: Outgoing connection, peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)] disconnected: Either failed to read from the output stream or write to the input stream: Broken pipe
,D/io.jxcore.node.ConnectionHelper( 3445): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3445): disconnectOutgoingConnection: Successfully disconnected (peer ID: 7C:F9:0E:51:18:22
,E/io.jxcore.node.ConnectionHelper( 3445): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 3445): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3445): Exiting thread (ID: 360, name: Receiver)
E/io.jxcore.node.ConnectionHelper( 3445): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 3445): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3445): Exiting thread (ID: 359, name: Sender)
,I/jxcore-log( 3445): 2016-01-11T14:49:19.061Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3445): 
,D/        ( 2063): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:72020
,E/bt-btif ( 2063): unknown send() error, sent:-1, p_buf->len:3,  errno:32
,W/bt-btif ( 2063): bta_jv_rfc_port_to_cb(port_handle:0xe):jv handle:0x0 not FOUND
,W/bt-btif ( 2063): bta_jv_rfc_port_to_cb(port_handle:0xe):jv handle:0x0 not FOUND
,D/btif_config_util( 2063): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2063): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2063): onReceive
,I/BTConnectionReceiver( 1391): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:51:18:22, alias=null, name=Thali Test (Galaxy A5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1391): Bluetooth Device Name: Thali Test (Galaxy A5)
,I/jxcore-log( 3445): teardown
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): testSendData stopped
I/jxcore-log( 3445): 
,I/io.jxcore.node.ConnectionHelper( 3445): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3445): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3445): Shutting down...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3445): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3445): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3445): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3445): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3445): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3445): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3445): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3445): stop: Stopping P2P device discovery...
,I/wpa_supplicant( 1023): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1023): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 1023): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant( 1023): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 1023): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3445): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3445): release: No more listeners, de-initializing...
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3445): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3445): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3445): setState: NOT_STARTED
I/jxcore-log( 3445): StopBroadcasting went ok
I/jxcore-log( 3445): 
,I/jxcore-log( 3445): 2016-01-11T14:49:38.591Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
I/jxcore-log( 3445): 
,I/chromium( 3445): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
I/io.jxcore.node.ConnectionHelper( 3445): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3445): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3445): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3445): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 3445): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 3445): ****TEST TOOK:  ms ****
I/jxcore-log( 3445): 
I/jxcore-log( 3445): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3445): 
,D/AndroidRuntime( 3869): 
D/AndroidRuntime( 3869): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 3869): CheckJNI is OFF
,D/AndroidRuntime( 3869): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  760): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  760): Killing 3445:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
,W/PackageSettings(  760): Skipping PackageSetting{18569b11 com.example.hello/10278} due to missing metadata
,I/WindowState(  760): WIN DEATH: Window{3e12d3a9 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  760): Client connection lost with reason: 4
,I/ActivityManager(  760):   Force finishing activity ActivityRecord{f61dc85 u0 com.test.thalitest/.MainActivity t214}
,W/ActivityManager(  760): Spurious death for ProcessRecord{6c2e003 3445:com.test.thalitest/u0a270}, curProc for 3445: null
,I/ActivityManager(  760): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
,I/ActivityManager(  760):   Force finishing activity ActivityRecord{f61dc85 u0 com.test.thalitest/.MainActivity t214 f}
W/ActivityManager(  760): Duplicate finish request for ActivityRecord{f61dc85 u0 com.test.thalitest/.MainActivity t214 f}
,W/GeofencerStateMachine( 1572): Ignoring removeGeofence because network location is disabled.
,I/art     ( 1309): Explicit concurrent mark sweep GC freed 7205(542KB) AllocSpace objects, 2(253KB) LOS objects, 38% free, 25MB/41MB, paused 240us total 24.632ms
,I/Keyboard.Facilitator( 1114): resetDictionaries() : en_US
,I/InputReader(  760): Reconfiguring input devices.  changes=0x00000010
,I/Adreno-EGL(  946): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/OpenGLRenderer(  946): Initialized EGL, version 1.4
,D/VoicemailCleanupService( 1418): Cleaning up data for package: com.test.thalitest
,I/Keyboard.Facilitator.DecoderInitializer( 1114): run()
,D/OpenGLRenderer(  946): Enabling debug mode 0
,I/Decoder ( 1114): createOrResetDecoder
,W/InputMethodManagerService(  760): Focus gain on non-focused client com.android.internal.view.IInputMethodClient$Stub$Proxy@37933557 (uid=10034 pid=946)
,I/art     ( 1391): Explicit concurrent mark sweep GC freed 36555(1946KB) AllocSpace objects, 6(119KB) LOS objects, 24% free, 19MB/25MB, paused 345us total 120.157ms
,I/art     ( 1641): Explicit concurrent mark sweep GC freed 11921(569KB) AllocSpace objects, 1(16KB) LOS objects, 25% free, 22MB/30MB, paused 485us total 114.035ms
,I/ConfigService( 1572): onCreate
,I/UpdateIcingCorporaServi( 1391): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,W/Launcher( 1309): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@25d1b602 new=com.google.android.velvet.VelvetApplication@25d1b602
,I/art     (  760): Explicit concurrent mark sweep GC freed 37494(1949KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 28MB/42MB, paused 2.158ms total 149.210ms
,I/art     (  760): WaitForGcToComplete blocked for 75.813ms for cause Explicit
,I/ActivityManager(  760): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3910 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/art     ( 1572): Explicit concurrent mark sweep GC freed 50627(2MB) AllocSpace objects, 5(80KB) LOS objects, 39% free, 21MB/36MB, paused 928us total 41.634ms
,D/BackupManagerService(  760): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  760): Receieved: android.intent.action.PACKAGE_REMOVED
,D/TaskPersister(  760): removeObsoleteFile: deleting file=214_task.xml
,W/ContextImpl( 3910): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1114): run()
,D/PackageBroadcastService( 1641): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1641): Clearing selected account for com.test.thalitest
,I/LocationSettingsChecker( 1641): Removing dialog suppression flag for package com.test.thalitest
,D/ChimeraCfgMgr( 1641): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1641): Module APK com.google.android.play.games already loaded
,I/Launcher( 1309): Deferring update until onResume
,I/art     (  760): Explicit concurrent mark sweep GC freed 8485(438KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 28MB/42MB, paused 3.017ms total 138.644ms
,E/NetworkScheduler.SchedulerReceiver( 1572): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1572): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,W/ResourcesManager( 1309): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/ChimeraCfgMgr( 1641): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1641): Module APK com.google.android.play.games already loaded
,W/ResourcesManager( 1309): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/Keyboard.Facilitator.MainLanguageModelLoader( 1114): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1114): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1114): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1114): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1114): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1114): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1114): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1114): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1114): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1114): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1114): run()
D/gH_CompatibleDatabase( 1641): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
I/StatsUtilsManager( 1114): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1114): shouldRecordStats() = Too Soon
D/gH_CompatibleDatabase( 1641): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1641): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1641): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,I/Launcher( 1309): Deferring update until onResume
,D/gH_CompatibleDatabase( 1641): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1641): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/gH_CompatibleDatabase( 1641): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,I/UpdateIcingCorporaServi( 1391): UpdateCorporaTask done [took 234 ms] updated apps [took 234 ms] 
,D/gH_CompatibleDatabase( 1641): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1641): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 1641): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1641): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1641): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1641): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/ActivityManager(  760): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3947 uid=10039 gids={50039, 9997} abi=armeabi-v7a
,D/AndroidRuntime( 3869): Shutting down VM
,I/GMPM-SVC( 1641): App measurement is starting up, version: 8489
I/GMPM-SVC( 1641): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,W/BaseAppContext( 1641): Using Auth Proxy for data requests.
,W/BaseAppContext( 1641): Using Auth Proxy for data requests.
,I/Icing   ( 1641): doRemovePackageData com.test.thalitest
,I/ActivityManager(  760): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3970 uid=10007 gids={50007, 9997, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  760): Killing 2918:com.google.android.videos/u0a77 (adj 15): empty #17
,I/art     (  194): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 205us total 7.884ms
,I/art     (  194): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 169us total 7.438ms
,I/art     (  194): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 169us total 7.434ms
,W/libprocessgroup(  760): failed to open /acct/uid_10077/pid_2918/cgroup.procs: No such file or directory
,I/ActivityManager(  760): Killing 3218:com.google.android.gms:car/u0a8 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10008/pid_3218/cgroup.procs: No such file or directory
,D/ExternalStorage( 3970): After updating volumes, found 1 active roots
,W/ResourcesManager( 3382): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 3382): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/Documents( 3947): Update found 7 roots in 311ms
,D/Documents( 3947): Update found 7 roots in 223ms

```
