#### Test 50650278d6c551a_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
D/ChimeraCfgMgr( 1619): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1619): Module APK com.google.android.play.games already loaded
,I/GAv4    ( 3124): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3124):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3124):   adb logcat -s GAv4
W/GAv4    ( 3124): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3124): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3124): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 3124): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
D/Finsky  ( 2587): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
W/ResourcesManager( 3124): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3124): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  735): Killing 2552:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
V/JNIHelp ( 3124): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/AndroidRuntime( 3173): 
D/AndroidRuntime( 3173): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3173): CheckJNI is OFF
W/System  ( 3124): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3124): Installed default security provider GmsCore_OpenSSL
W/libprocessgroup(  735): failed to open /acct/uid_10069/pid_2552/cgroup.procs: No such file or directory
V/GLSActivity( 1569): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/AndroidRuntime( 3173): Calling main entry com.android.commands.am.Am
I/ActivityManager(  735): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  735): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3199 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3173): Shutting down VM
V/ActivityManager(  735): Display changed displayId=0
I/Icing   ( 1619): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/WebViewFactory( 3199): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/Icing   ( 1619): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1619): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
,I/LibraryLoader( 3199): Time to load native libraries: 1 ms (timestamps 7030-7031)
I/LibraryLoader( 3199): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3199): Binding Chromium to main looper Looper (main, tid 1) {166a6095}
,I/LibraryLoader( 3199): Expected native library version number "",actual native library version number ""
I/chromium( 3199): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3199): Initializing chromium process, singleProcess=true
W/art     ( 3199): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3199): ApplicationContext is null in ApplicationStatus
,W/chromium( 3199): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,I/Icing   ( 1619): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
,E/libEGL  ( 3199): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3199): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3199): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  735): Message: 20
D/BluetoothManagerService(  735): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@254573cf:true
,W/art     ( 3199): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3199): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3199): CordovaWebView is running on device made by: LGE
,W/art     ( 3199): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 3199): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3199): Render dirty regions requested: true
,D/Atlas   ( 3199): Validating map...
,W/chromium( 3199): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3199): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3199): Enabling debug mode 0
,W/IInputConnectionWrapper( 3199): showStatusIcon on inactive InputConnection
I/ActivityManager(  735): Displayed com.test.thalitest/.MainActivity: +483ms (total +55s258ms)
W/BindingManager( 3199): Cannot call determinedVisibility() - never saw a connection for the pid: 3199
D/JsMessageQueue( 3199): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 3199): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257342720
D/JX-Cordova( 3199): jxcore cordova android initializing
I/ActivityManager(  735): Killing 2507:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
W/libprocessgroup(  735): failed to open /acct/uid_10045/pid_2507/cgroup.procs: No such file or directory
,W/jxcore-log( 3199): Initializing JXcore engine
W/jxcore-log( 3199): JXcore engine is ready
,W/jxcore-log( 3199): Starting JXcore engine
,W/.test.thalitest( 3199): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[6633]" dev="sockfs" ino=6633 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/.test.thalitest( 3199): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 3199): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[9482]" dev="sockfs" ino=9482 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3199): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[19022]" dev="sockfs" ino=19022 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3199): Platform android
W/jxcore-log( 3199): 
,W/jxcore-log( 3199): Process ARCH arm
W/jxcore-log( 3199): 
,I/jxcore-log( 3199): JXcore Cordova bridge is ready!
I/jxcore-log( 3199): 
W/jxcore-log( 3199): JXcore engine is started
I/Choreographer( 3199): Skipped 114 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3199): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3199): Toggling radios to true
I/jxcore-log( 3199): 
,D/BluetoothAdapter( 3199): enable(): BT is already enabled..!
,D/WifiService(  735): New client listening to asynchronous messages
,D/WifiService(  735): setWifiEnabled: true pid=3199, uid=10270
E/WifiService(  735): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3199): Radios toggled
I/jxcore-log( 3199): 
,D/BluetoothManagerService(  735): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 3199): Got Device Bluetooth address: 34:FC:EF:11:AE:67
I/jxcore-log( 3199): 
,I/jxcore-log( 3199): Perf Test app loaded loaded
I/jxcore-log( 3199): 
I/Choreographer( 3199): Skipped 56 frames!  The application may be doing too much work on its main thread.
I/jxcore-log( 3199): check test folder
I/jxcore-log( 3199): 
I/jxcore-log( 3199): found test : ./testFindPeers.js
I/jxcore-log( 3199): 
I/wpa_supplicant( 1036): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  735): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  735): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
E/native  (  735): do suspend true
,I/jxcore-log( 3199): found test : ./testSendData.js
I/jxcore-log( 3199): 
D/CommandListener(  181): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1569): Read error: ssl=0xaf380e00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1569): SSL shutdown failed: ssl=0xaf380e00: I/O error during system call, Broken pipe
D/ConnectivityService(  735): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): ValidatedState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): DefaultState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Checking http://clients3.google.com/generate_204 on "NG7005g"
,E/WifiConfigStore(  735): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
E/WifiStateMachine(  735): Start Disconnecting Watchdog 1
D/ConnectivityService(  735): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  735): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
I/wpa_supplicant( 1036): wlan0: CTRL-EVENT-SCAN-STARTED 
E/native  (  735): do suspend true
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/CommandListener(  181): Clearing all IP addresses on wlan0
,D/ConnectivityService(  735): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler(  903): CM callback handler got msg 524292
D/Nat464Xlat(  735): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  735): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  735): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Disconnected - quitting
D/ConnectivityManager.CallbackHandler( 1619): CM callback handler got msg 524292
,D/ConnectivityService(  735): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  735): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory( 1255): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/chromium( 3199): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/WifiNetworkAgent(  735): NetworkAgent: NetworkAgent channel lost
,W/ProcessCpuTracker(  735): Skipping unknown process pid 3261
,W/ProcessCpuTracker(  735): Skipping unknown process pid 3264
,W/ProcessCpuTracker(  735): Skipping unknown process pid 3265
W/ProcessCpuTracker(  735): Skipping unknown process pid 3268
,I/wpa_supplicant( 1036): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant( 1036): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1036): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1036): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  735): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  735): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  735): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  181): Setting iface cfg
,E/WifiStateMachine(  735): Start Dhcp Watchdog 2
,D/ConnectivityService(  735): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/native  (  735): do suspend false
,E/WifiStateMachine(  735): scanCount==0 - aborting
,I/dhcpcd  ( 3308): version 5.5.6 starting
,E/dhcpcd  ( 3308): get_duid: Read-only file system
,I/dhcpcd  ( 3308): wlan0: rebinding lease of 192.168.1.114
,I/dhcpcd  ( 3308): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3308): wlan0: leased 192.168.1.114 for 86400 seconds
,V/GLSActivity( 1569): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1569): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/NetworkUtils( 1371): OkHttp exception
,W/EventLoggerService( 1371): Unable to send logs Error code: 262146
,E/native  (  735): do suspend true
,D/ConnectivityService(  735): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  735): Adding iface wlan0 to network 101
,E/WifiStateMachine(  735): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  735): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  735): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  735): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  735): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  735): Setting Dns servers for network 101 to [/192.168.1.1]
D/Nat464Xlat(  735): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  735): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  735): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  735): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  735):    accepting network in place of null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/CSLegacyTypeTracker(  735): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  735): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  735): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  735): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  903): CM callback handler got msg 524290
D/ConnectivityManager.CallbackHandler( 1619): CM callback handler got msg 524290
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 10 Dec 2015 13:39:47 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1449754787730], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1449754787711]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Validated
,D/ConnectivityService(  735): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  735): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  735): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  735): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  903): CM callback handler got msg 524290
D/ConnectivityService(  735): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/TelephonyNetworkFactory( 1255): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 1619): CM callback handler got msg 524290
,D/Nat464Xlat(  735): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  735): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  903): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 1619): CM callback handler got msg 524295
,D/ConnectivityService(  735): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  735): MasterInitialState.processMessage what=3
,D/ConnectivityService(  735): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  735): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2700): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2700): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 2700): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  735): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3368 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/GpsLocationProvider(  735): No APN found to select.
,E/GpsLocationProvider(  735): No APN found to select.
,D/ConnectivityService(  735): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/GAv4    ( 3368): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3368):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3368):   adb logcat -s GAv4
,W/GAv4    ( 3368): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3368): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3368): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 3368): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3368): Time to load native libraries: 2 ms (timestamps 4036-4038)
,I/LibraryLoader( 3368): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3368): Binding Chromium to main looper Looper (main, tid 1) {2889f43f}
,I/LibraryLoader( 3368): Expected native library version number "",actual native library version number ""
I/chromium( 3368): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3368): Initializing chromium process, singleProcess=true
,W/art     ( 3368): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3368): ApplicationContext is null in ApplicationStatus
,W/chromium( 3368): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3368): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3368): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3368): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/AudioManagerAndroid( 3368): Requires BLUETOOTH permission
,I/NSApplication( 3368): Starting up...
,I/ActivityManager(  735): Killing 2677:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/libprocessgroup(  735): failed to open /acct/uid_10003/pid_2677/cgroup.procs: No such file or directory
,V/MusicLeanback( 2700): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/jxcore-log( 3199): BLE advertisement not supported: MultipleAdvertisement not supported
I/jxcore-log( 3199): 
,D/ConnectivityService(  735): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  735): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2700): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2700): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,E/GpsLocationProvider(  735): No APN found to select.
,D/Finsky  ( 2587): [255] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2587): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/art     (  735): Explicit concurrent mark sweep GC freed 45137(2MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 27MB/41MB, paused 1.213ms total 105.396ms
,V/GLSActivity( 1569): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1569): Vacuum at: now=1449754803260 tag=VacuumService
,D/HeadsetStateMachine( 2057): Disconnected process message: 10, size: 0
,I/ClearcutLoggerApiImpl( 1569): disconnect managed GoogleApiClient

```
