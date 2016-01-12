#### Test 55742142a5c2fdb_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
D/ChimeraCfgMgr( 1617): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1617): Module APK com.google.android.play.games already loaded
I/GAv4    ( 3141): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3141):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3141):   adb logcat -s GAv4
W/GAv4    ( 3141): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3141): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3141): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 3141): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
D/Finsky  ( 2638): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
W/ResourcesManager( 3141): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3141): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  735): Killing 2550:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
V/JNIHelp ( 3141): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/System  ( 3141): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3141): Installed default security provider GmsCore_OpenSSL
W/libprocessgroup(  735): failed to open /acct/uid_10045/pid_2550/cgroup.procs: No such file or directory
V/GLSActivity( 1569): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 1617): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/Icing   ( 1617): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1617): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/Icing   ( 1617): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
,D/AndroidRuntime( 3206): 
D/AndroidRuntime( 3206): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3206): CheckJNI is OFF
I/ActivityManager(  735): Killing 2719:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
D/AndroidRuntime( 3206): Calling main entry com.android.commands.am.Am
W/libprocessgroup(  735): failed to open /acct/uid_10003/pid_2719/cgroup.procs: No such file or directory
I/ActivityManager(  735): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  735): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3227 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3206): Shutting down VM
V/ActivityManager(  735): Display changed displayId=0
I/WebViewFactory( 3227): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3227): Time to load native libraries: 2 ms (timestamps 9080-9082)
I/LibraryLoader( 3227): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3227): Binding Chromium to main looper Looper (main, tid 1) {1fa8a2d4}
I/LibraryLoader( 3227): Expected native library version number "",actual native library version number ""
I/chromium( 3227): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3227): Initializing chromium process, singleProcess=true
W/art     ( 3227): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3227): ApplicationContext is null in ApplicationStatus
,W/chromium( 3227): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3227): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3227): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3227): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  735): Message: 20
D/BluetoothManagerService(  735): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1853baaa:true
,W/art     ( 3227): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3227): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3227): CordovaWebView is running on device made by: LGE
,W/art     ( 3227): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3227): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3227): Render dirty regions requested: true
,D/Atlas   ( 3227): Validating map...
,W/chromium( 3227): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3227): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3227): Enabling debug mode 0
,W/BindingManager( 3227): Cannot call determinedVisibility() - never saw a connection for the pid: 3227
,I/ActivityManager(  735): Displayed com.test.thalitest/.MainActivity: +444ms (total +57s418ms)
,W/IInputConnectionWrapper( 3227): showStatusIcon on inactive InputConnection
,D/JsMessageQueue( 3227): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3227): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257342720
D/JX-Cordova( 3227): jxcore cordova android initializing
,W/jxcore-log( 3227): Initializing JXcore engine
W/jxcore-log( 3227): JXcore engine is ready
,W/jxcore-log( 3227): Starting JXcore engine
,W/.test.thalitest( 3227): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[8090]" dev="sockfs" ino=8090 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3227): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 3227): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6615]" dev="sockfs" ino=6615 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3227): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[19096]" dev="sockfs" ino=19096 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3227): Platform android
W/jxcore-log( 3227): 
,W/jxcore-log( 3227): Process ARCH arm
W/jxcore-log( 3227): 
,I/jxcore-log( 3227): JXcore Cordova bridge is ready!
I/jxcore-log( 3227): 
W/jxcore-log( 3227): JXcore engine is started
,I/Choreographer( 3227): Skipped 112 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3227): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,V/GLSActivity( 1569): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1569): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 3227): Toggling radios to true
I/jxcore-log( 3227): 
,D/BluetoothAdapter( 3227): enable(): BT is already enabled..!
,D/WifiService(  735): setWifiEnabled: true pid=3227, uid=10270
E/WifiService(  735): Invoking mWifiStateMachine.setWifiEnabled
,D/WifiService(  735): New client listening to asynchronous messages
,I/jxcore-log( 3227): Radios toggled
I/jxcore-log( 3227): 
,D/BluetoothManagerService(  735): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/wpa_supplicant(  986): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
D/BluetoothManagerService(  735): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 3227): Received device characteristics:
I/jxcore-log( 3227): Bluetooth address: 34:FC:EF:11:AE:67
I/jxcore-log( 3227): Bluetooth name: Nexus 5
I/jxcore-log( 3227): Device name: LGE-Nexus 5
I/jxcore-log( 3227): 
,E/WifiStateMachine(  735): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  735): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/native  (  735): do suspend true
I/jxcore-log( 3227): Perf Test app loaded loaded
I/jxcore-log( 3227): 
,I/chromium( 3227): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/CommandListener(  181): Clearing all IP addresses on wlan0
,I/jxcore-log( 3227): check test folder
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): found test : ./testFindPeers.js
I/jxcore-log( 3227): 
,V/NativeCrypto( 1569): Read error: ssl=0x9d4f7e00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1569): SSL shutdown failed: ssl=0x9d4f7e00: I/O error during system call, Broken pipe
I/jxcore-log( 3227): found test : ./testSendData.js
I/jxcore-log( 3227): 
,D/ConnectivityService(  735): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): ValidatedState{ when=-1ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): DefaultState{ when=-1ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,E/WifiConfigStore(  735): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  735): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  735): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,W/NetworkUtils( 1388): OkHttp exception
W/NetworkUtils( 1388): java.net.ConnectException: failed to connect to www.google.com/216.58.209.36 (port 443) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
W/NetworkUtils( 1388): 	at libcore.io.IoBridge.connect(IoBridge.java:124)
W/NetworkUtils( 1388): 	at java.net.PlainSocketImpl.connect(PlainSocketImpl.java:183)
W/NetworkUtils( 1388): 	at java.net.PlainSocketImpl.connect(PlainSocketImpl.java:456)
W/NetworkUtils( 1388): 	at java.net.Socket.connect(Socket.java:882)
W/NetworkUtils( 1388): 	at kbm.a(PG:257)
W/NetworkUtils( 1388): 	at kac.a(PG:101)
W/NetworkUtils( 1388): 	at kcc.byl(PG:206)
W/NetworkUtils( 1388): 	at kcj.jJ(PG:351)
W/NetworkUtils( 1388): 	at kcj.connect(PG:90)
W/NetworkUtils( 1388): 	at kcm.connect(PG:161)
W/NetworkUtils( 1388): 	at bzk.connect(PG:63)
W/NetworkUtils( 1388): 	at dmc.d(PG:38)
W/NetworkUtils( 1388): 	at gmc.a(PG:91)
W/NetworkUtils( 1388): 	at gmc.am(PG:68)
W/NetworkUtils( 1388): 	at com.google.android.voicesearch.logger.EventLoggerService.h(PG:379)
W/NetworkUtils( 1388): 	at com.google.android.voicesearch.logger.EventLoggerService.onHandleIntent(PG:182)
W/NetworkUtils( 1388): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/NetworkUtils( 1388): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkUtils( 1388): 	at android.os.Looper.loop(Looper.java:135)
W/NetworkUtils( 1388): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/NetworkUtils( 1388): Caused by: android.system.ErrnoException: connect failed: ENETUNREACH (Network is unreachable)
W/NetworkUtils( 1388): 	at libcore.io.Posix.connect(Native Method)
W/NetworkUtils( 1388): 	at libcore.io.BlockGuardOs.connect(BlockGuardOs.java:111)
W/NetworkUtils( 1388): 	at libcore.io.IoBridge.connectErrno(IoBridge.java:154)
W/NetworkUtils( 1388): 	at libcore.io.IoBridge.connect(IoBridge.java:122)
W/NetworkUtils( 1388): 	... 19 more
W/EventLoggerService( 1388): Unable to send logs Error code: 262146
,E/WifiStateMachine(  735): Start Disconnecting Watchdog 1
,E/native  (  735): do suspend true
,I/wpa_supplicant(  986): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/CommandListener(  181): Clearing all IP addresses on wlan0
D/ConnectivityService(  735): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/Nat464Xlat(  735): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  735): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  735): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  735): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Disconnected - quitting
D/ConnectivityManager.CallbackHandler(  899): CM callback handler got msg 524292
,D/ConnectivityManager.CallbackHandler( 1617): CM callback handler got msg 524292
,D/ConnectivityService(  735): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1221): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WifiNetworkAgent(  735): NetworkAgent: NetworkAgent channel lost
,I/wpa_supplicant(  986): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant(  986): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant(  986): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant(  986): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  735): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  735): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  735): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiConfigStore(  735): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  181): Setting iface cfg
,E/WifiStateMachine(  735): Start Dhcp Watchdog 2
,E/native  (  735): do suspend false
,E/WifiStateMachine(  735): scanCount==0 - aborting
,I/dhcpcd  ( 3316): version 5.5.6 starting
,E/dhcpcd  ( 3316): get_duid: Read-only file system
,I/dhcpcd  ( 3316): wlan0: rebinding lease of 192.168.1.114
,I/dhcpcd  ( 3316): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3316): wlan0: leased 192.168.1.114 for 86400 seconds
,E/native  (  735): do suspend true
,D/ConnectivityService(  735): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  735): Adding iface wlan0 to network 101
,E/WifiStateMachine(  735): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  735): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  735): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  735): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  735): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  735): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  735): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  735): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  735): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/ConnectivityService(  735): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  735):    accepting network in place of null
,D/CSLegacyTypeTracker(  735): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  735): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  735): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  735): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler(  899): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1617): CM callback handler got msg 524290
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 12 Jan 2016 12:15:46 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452600946337], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452600946317]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Validated
,D/ConnectivityService(  735): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  735): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  735): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  735): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  899): CM callback handler got msg 524290
D/ConnectivityService(  735): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1617): CM callback handler got msg 524290
D/TelephonyNetworkFactory( 1221): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/Nat464Xlat(  735): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  735): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  899): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 1617): CM callback handler got msg 524295
,D/ConnectivityService(  735): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  735): MasterInitialState.processMessage what=3
,D/ConnectivityService(  735): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  735): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2744): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2744): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 2744): type=WIFI subType= reason=null isConnected=true
,I/SystemUpdateService( 1617): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1617): onCreate
,D/SystemUpdateService( 1617): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/ActivityManager(  735): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3385 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SystemUpdateService( 1617): active receiver: enabled
,I/SystemUpdateService( 1617): showing system update notification
,I/ValidateNoPeople(  735): skipping global notification
,V/SystemUpdateService( 1617): retry (wakeup: false) in 3599928 ms
,D/SystemUpdateService( 1617): onDestroy
,E/GpsLocationProvider(  735): No APN found to select.
,E/GpsLocationProvider(  735): No APN found to select.
,E/ActivityThread( 1617): Failed to find provider info for com.android.contacts.metadata
,D/SyncManager(  735): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 64626, reason: UserStart, SyncResult: databaseError: true stats []
,D/SyncManager(  735): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 148944, reason: UserStart
,D/ConnectivityService(  735): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/GAv4    ( 3385): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3385):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3385):   adb logcat -s GAv4
,W/GAv4    ( 3385): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3385): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3385): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 3385): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3385): Time to load native libraries: 1 ms (timestamps 6228-6229)
I/LibraryLoader( 3385): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3385): Binding Chromium to main looper Looper (main, tid 1) {9bf05a6}
,I/LibraryLoader( 3385): Expected native library version number "",actual native library version number ""
,I/chromium( 3385): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3385): Initializing chromium process, singleProcess=true
W/art     ( 3385): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3385): ApplicationContext is null in ApplicationStatus
,W/chromium( 3385): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3385): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3385): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3385): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/AudioManagerAndroid( 3385): Requires BLUETOOTH permission
,I/NSApplication( 3385): Starting up...
,I/ActivityManager(  735): Killing 2694:com.android.settings/1000 (adj 15): empty #17
,D/WifiService(  735): Client connection lost with reason: 4
,W/libprocessgroup(  735): failed to open /acct/uid_1000/pid_2694/cgroup.procs: No such file or directory
,V/MusicLeanback( 2744): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1617): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
D/SystemUpdateService( 1617): onCreate
,D/SystemUpdateService( 1617): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1617): active receiver: enabled
,I/SystemUpdateService( 1617): showing system update notification
,I/ValidateNoPeople(  735): skipping global notification
,V/SystemUpdateService( 1617): retry (wakeup: false) in 3599954 ms
,I/art     (  735): Explicit concurrent mark sweep GC freed 47042(2MB) AllocSpace objects, 8(128KB) LOS objects, 33% free, 27MB/41MB, paused 1.577ms total 64.394ms
,D/SystemUpdateService( 1617): onDestroy
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): setDiscoveryMode: Mode set to WIFI
,I/jxcore-log( 3227): BLE is supported
I/jxcore-log( 3227): 
,D/ConnectivityService(  735): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  735): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2744): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2744): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1617): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1617): onCreate
,D/SystemUpdateService( 1617): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1617): active receiver: enabled
,I/SystemUpdateService( 1617): showing system update notification
,E/GpsLocationProvider(  735): No APN found to select.
,I/ValidateNoPeople(  735): skipping global notification
,V/SystemUpdateService( 1617): retry (wakeup: false) in 3599980 ms
,D/SystemUpdateService( 1617): onDestroy
,D/Finsky  ( 2638): [260] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2638): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/GLSActivity( 1569): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1569): Vacuum at: now=1452600960169 tag=VacuumService
,I/PhenotypeConfigurator( 1569): Scheduling Phenotype for one-off execution 4836 seconds from now (1452600960583)
,D/GetConfigurationSnapshotOperation( 1569): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1569): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1569): Using platform SSLCertificateSocketFactory
,V/GLSActivity( 1569): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1569): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ClearcutLoggerApiImpl( 1569): disconnect managed GoogleApiClient
,I/jxcore-log( 3227): Connected to the server!
I/jxcore-log( 3227): 
,I/chromium( 3227): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3227): --- start :testFindPeers.js---
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): testFindPeers created [object Object]
I/jxcore-log( 3227): 
I/jxcore-log( 3227): serverPort is 8876
I/jxcore-log( 3227): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): setDiscoveryMode: Mode set to WIFI
,D/BluetoothManagerService(  735): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3227): start: Peer ID: 34:FC:EF:11:AE:67, peer name: Nexus 5
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3227): bind: Binding a new listener
,D/BluetoothManagerService(  735): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3227): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  735): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3227): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"Nexus 5","ra":"34:FC:EF:11:AE:67"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3227): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3227): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3227): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  735): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3227): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3227): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3227): start: OK
I/io.jxcore.node.ConnectionHelper( 3227): start: Using peer discovery mode: WIFI
,D/BluetoothManagerService(  735): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): start: Peer ID: 34:FC:EF:11:AE:67, peer name: Nexus 5
,D/BluetoothManagerService(  735): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3227): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"Nexus 5","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3227): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3227): start: {"pi":"34:FC:EF:11:AE:67","pn":"Nexus 5","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3227): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"Nexus 5","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3227): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3227): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3227): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3227): start: OK
I/jxcore-log( 3227): StartBroadcasting started ok
I/jxcore-log( 3227): 
I/chromium( 3227): [INFO:CONSOLE(63)] "logCallback --- start :testFindPeers.js---", source: file:///android_asset/www/js/thali_main.js (63)
I/io.jxcore.node.ConnectionHelper( 3227): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3227): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3227): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3227): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3227): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3227): onDiscoveryManagerStateChanged: RUNNING
,I/wpa_supplicant(  986): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  986): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  986): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  986): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3227): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3227): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/WifiP2pManager( 3227): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3227): Service request added successfully
,I/wpa_supplicant(  986): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  986): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3227): Service discovery started successfully
,I/wpa_supplicant(  986): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  986): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant(  986): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  986): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  986): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  986): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3227): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3227): onP2pDeviceListChanged: 4 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3227): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"G4-1","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3227): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3227): onServiceDiscovered: [F8:95:C7:87:3C:51 G4-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onPeerDiscovered: [F8:95:C7:87:3C:51 G4-1]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 G4-1]
,I/io.jxcore.node.ConnectionHelper( 3227): onPeerDiscovered: [F8:95:C7:87:3C:51 G4-1], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
D/io.jxcore.node.ConnectionHelper( 3227): notifyPeerAvailability: Peer [F8:95:C7:87:3C:51 G4-1] is available
,I/jxcore-log( 3227): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:3C:51","peerName":"G4-1","peerAvailable":true}]
I/jxcore-log( 3227): 
I/jxcore-log( 3227): Found peer : F8:95:C7:87:3C:51, peerAvailable: true
I/jxcore-log( 3227): 
,I/wpa_supplicant(  986): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  986): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3227): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3227): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"S5-1","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3227): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3227): onServiceDiscovered: [7C:F9:0E:34:8A:A0 S5-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onPeerDiscovered: [7C:F9:0E:34:8A:A0 S5-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 S5-1]
,I/io.jxcore.node.ConnectionHelper( 3227): onPeerDiscovered: [7C:F9:0E:34:8A:A0 S5-1], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
,D/io.jxcore.node.ConnectionHelper( 3227): notifyPeerAvailability: Peer [7C:F9:0E:34:8A:A0 S5-1] is available
,I/jxcore-log( 3227): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:34:8A:A0","peerName":"S5-1","peerAvailable":true}]
I/jxcore-log( 3227): 
I/jxcore-log( 3227): Found peer : 7C:F9:0E:34:8A:A0, peerAvailable: true
I/jxcore-log( 3227): 
,I/wpa_supplicant(  986): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  986): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  986): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3227): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
,I/wpa_supplicant(  986): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  986): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3227): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
,I/wpa_supplicant(  986): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  986): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3227): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3227): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3227): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3227): onServiceDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onPeerDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): modifyListOfDiscoveredPeers: Adding new peer: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
I/io.jxcore.node.ConnectionHelper( 3227): onPeerDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
D/io.jxcore.node.ConnectionHelper( 3227): notifyPeerAvailability: Peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)] is available
I/jxcore-log( 3227): peerAvailabilityChanged [{"peerIdentifier":"B0:C5:59:3F:75:69","peerName":"Thali Test (Galaxy S5)","peerAvailable":true}]
I/jxcore-log( 3227): 
I/jxcore-log( 3227): Found peer : B0:C5:59:3F:75:69, peerAvailable: true
I/jxcore-log( 3227): 
,I/wpa_supplicant(  986): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  986): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  986): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  986): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  986): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  986): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  986): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  986): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  986): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  986): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  986): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  986): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  986): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  986): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  986): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  986): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  986): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  986): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  986): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  986): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  986): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  986): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  986): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  986): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3227): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3227): restart: Restarting...
,D/WifiP2pManager( 3227): Ignored { when=-4ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3227): Service request added successfully
,I/wpa_supplicant(  986): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  986): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  986): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  986): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3227): Service discovery started successfully
,I/wpa_supplicant(  986): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  986): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3227): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3227): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3227): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3227): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3227): onServiceDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onPeerDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
I/io.jxcore.node.ConnectionHelper( 3227): onPeerDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
W/io.jxcore.node.ConnectionHelper( 3227): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3227): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"S5-1","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3227): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3227): onServiceDiscovered: [7C:F9:0E:34:8A:A0 S5-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onPeerDiscovered: [7C:F9:0E:34:8A:A0 S5-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 S5-1]
I/io.jxcore.node.ConnectionHelper( 3227): onPeerDiscovered: [7C:F9:0E:34:8A:A0 S5-1], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
W/io.jxcore.node.ConnectionHelper( 3227): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 S5-1] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3227): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"G4-1","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3227): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3227): onServiceDiscovered: [F8:95:C7:87:3C:51 G4-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onPeerDiscovered: [F8:95:C7:87:3C:51 G4-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
I/io.jxcore.node.ConnectionHelper( 3227): onPeerDiscovered: [F8:95:C7:87:3C:51 G4-1], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3227): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 G4-1] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3227): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3227): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3227): onServiceDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/io.jxcore.node.ConnectionHelper( 3227): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
D/io.jxcore.node.ConnectionHelper( 3227): notifyPeerAvailability: Peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)] is available
,I/jxcore-log( 3227): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:76:27","peerName":"Thali Test (Galaxy A3)","peerAvailable":true}]
I/jxcore-log( 3227): 
I/jxcore-log( 3227): Found peer : 08:EC:A9:50:76:27, peerAvailable: true
I/jxcore-log( 3227): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3227): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3227): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3227): onServiceDiscovered: [7C:F9:0E:37:96:AB A5-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB A5-1]
I/io.jxcore.node.ConnectionHelper( 3227): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
D/io.jxcore.node.ConnectionHelper( 3227): notifyPeerAvailability: Peer [7C:F9:0E:37:96:AB A5-1] is available
I/jxcore-log( 3227): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:37:96:AB","peerName":"A5-1","peerAvailable":true}]
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): Found peer : 7C:F9:0E:37:96:AB, peerAvailable: true
I/jxcore-log( 3227): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3227): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3227): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3227): setState: RESTARTING
,I/wpa_supplicant(  986): P2P-FIND-STOPPED 
,I/wpa_supplicant(  986): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant(  986): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant(  986): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant(  986): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant(  986): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant(  986): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant(  986): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3227): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3227): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3227): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3227): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3227): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3227): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3227): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3227): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3227): Start timer timeout, starting now...
,I/wpa_supplicant(  986): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3227): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3227): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3227): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  986): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3227): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3227): restart: Restarting...
,D/WifiP2pManager( 3227): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3227): Service request added successfully
,I/wpa_supplicant(  986): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  986): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  986): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3227): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3227): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
,I/wpa_supplicant(  986): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3227): Service discovery started successfully
,I/wpa_supplicant(  986): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  986): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3227): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3227): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3227): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3227): setState: RESTARTING
,I/wpa_supplicant(  986): P2P-FIND-STOPPED 
,I/wpa_supplicant(  986): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant(  986): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant(  986): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3227): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3227): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3227): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3227): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): checkListForExpiredPeers: Peer [7C:F9:0E:34:8A:A0 S5-1] expired
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): checkListForExpiredPeers: Peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)] expired
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): checkListForExpiredPeers: Peer [7C:F9:0E:37:96:AB A5-1] expired
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): checkListForExpiredPeers: Peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: false
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): modifyListOfDiscoveredPeers: Removed [7C:F9:0E:34:8A:A0 S5-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): modifyListOfDiscoveredPeers: Removed [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): modifyListOfDiscoveredPeers: Removed [7C:F9:0E:37:96:AB A5-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): modifyListOfDiscoveredPeers: Removed [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/io.jxcore.node.ConnectionHelper( 3227): onPeerLost: [7C:F9:0E:34:8A:A0 S5-1]
,D/io.jxcore.node.ConnectionHelper( 3227): hasConnection: No connection with peer with ID 7C:F9:0E:34:8A:A0
,D/io.jxcore.node.ConnectionHelper( 3227): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 S5-1] removed
,D/io.jxcore.node.ConnectionHelper( 3227): notifyPeerAvailability: Peer [7C:F9:0E:34:8A:A0 S5-1] not available
,I/jxcore-log( 3227): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:34:8A:A0","peerName":"S5-1","peerAvailable":false}]
I/jxcore-log( 3227): 
I/io.jxcore.node.ConnectionHelper( 3227): onPeerLost: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/io.jxcore.node.ConnectionHelper( 3227): hasConnection: No connection with peer with ID B0:C5:59:3F:75:69
D/io.jxcore.node.ConnectionHelper( 3227): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)] removed
D/io.jxcore.node.ConnectionHelper( 3227): notifyPeerAvailability: Peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)] not available
I/jxcore-log( 3227): peerAvailabilityChanged [{"peerIdentifier":"B0:C5:59:3F:75:69","peerName":"Thali Test (Galaxy S5)","peerAvailable":false}]
I/jxcore-log( 3227): 
I/io.jxcore.node.ConnectionHelper( 3227): onPeerLost: [7C:F9:0E:37:96:AB A5-1]
D/io.jxcore.node.ConnectionHelper( 3227): hasConnection: No connection with peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 3227): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB A5-1] removed
D/io.jxcore.node.ConnectionHelper( 3227): notifyPeerAvailability: Peer [7C:F9:0E:37:96:AB A5-1] not available
I/jxcore-log( 3227): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:37:96:AB","peerName":"A5-1","peerAvailable":false}]
I/jxcore-log( 3227): 
I/io.jxcore.node.ConnectionHelper( 3227): onPeerLost: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/io.jxcore.node.ConnectionHelper( 3227): hasConnection: No connection with peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 3227): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)] removed
D/io.jxcore.node.ConnectionHelper( 3227): notifyPeerAvailability: Peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)] not available
I/jxcore-log( 3227): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:76:27","peerName":"Thali Test (Galaxy A3)","peerAvailable":false}]
I/jxcore-log( 3227): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3227): Start timer timeout, starting now...
,I/wpa_supplicant(  986): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3227): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3227): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3227): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/jxcore-log( 3227): timeout now
I/jxcore-log( 3227): 
I/jxcore-log( 3227): weAreDoneNow
I/jxcore-log( 3227): 
I/jxcore-log( 3227): done, now sending data to server
I/jxcore-log( 3227): 
,I/wpa_supplicant(  986): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3227): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3227): restart: Restarting...
,D/WifiP2pManager( 3227): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3227): Service request added successfully
,I/wpa_supplicant(  986): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  986): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  986): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3227): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3227): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
,I/wpa_supplicant(  986): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  986): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3227): Service discovery started successfully
,I/jxcore-log( 3227): teardown
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): testFindPeers stopped
I/jxcore-log( 3227): 
I/io.jxcore.node.ConnectionHelper( 3227): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3227): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3227): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3227): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3227): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3227): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3227): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3227): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3227): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3227): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3227): stop: Stopping P2P device discovery...
,I/wpa_supplicant(  986): P2P-FIND-STOPPED 
,I/wpa_supplicant(  986): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant(  986): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant(  986): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3227): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3227): release: No more listeners, de-initializing...
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3227): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3227): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): setState: NOT_STARTED
,I/jxcore-log( 3227): StopBroadcasting went ok
I/jxcore-log( 3227): 
I/jxcore-log( 3227): --- start :testSendData.js---
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":13}bt-address length : 12
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): daya100000
I/jxcore-log( 3227): 
I/jxcore-log( 3227): check server
I/jxcore-log( 3227): 
I/jxcore-log( 3227): serverPort is 44236
I/jxcore-log( 3227): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): setDiscoveryMode: Mode set to WIFI
,D/BluetoothManagerService(  735): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3227): start: Peer ID: 34:FC:EF:11:AE:67, peer name: Nexus 5
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3227): bind: Binding a new listener
D/BluetoothManagerService(  735): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3227): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  735): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3227): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"Nexus 5","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3227): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3227): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3227): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  735): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3227): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3227): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3227): start: OK
I/io.jxcore.node.ConnectionHelper( 3227): start: Using peer discovery mode: WIFI
,D/BluetoothManagerService(  735): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): start: Peer ID: 34:FC:EF:11:AE:67, peer name: Nexus 5
,D/BluetoothManagerService(  735): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3227): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"Nexus 5","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3227): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3227): start: {"pi":"34:FC:EF:11:AE:67","pn":"Nexus 5","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3227): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"Nexus 5","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3227): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3227): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3227): start: OK
I/jxcore-log( 3227): StartBroadcasting started ok
I/jxcore-log( 3227): 
,I/wpa_supplicant(  986): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3227): Waiting for incoming connections...
,I/jxcore-log( 3227): [ { address: 'F8:95:C7:87:85:54', tryCount: 0 },
I/jxcore-log( 3227):   { address: '00:F4:6F:30:E0:6C', tryCount: 0 },
I/jxcore-log( 3227):   { address: '58:3F:54:73:64:C0', tryCount: 0 },
I/jxcore-log( 3227):   { address: '7C:F9:0E:34:8A:A0', tryCount: 0 },
I/jxcore-log( 3227):   { address: '7C:F9:0E:37:96:AB', tryCount: 0 },
I/jxcore-log( 3227):   { address: '08:EC:A9:50:76:27', tryCount: 0 },
I/jxcore-log( 3227):   { address: '7C:F9:0E:51:18:22', tryCount: 0 },
I/jxcore-log( 3227):   { address: '08:EC:A9:50:75:41', tryCount: 0 },
I/jxcore-log( 3227):   { address: 'B0:C5:59:3F:75:69', tryCount: 0 },
I/jxcore-log( 3227):   { address: 'E0:DB:10:14:E2:C0', tryCount: 0 },
I/jxcore-log( 3227):   { address: 'F8:95:C7:87:3C:51', tryCount: 0 },
I/jxcore-log( 3227):   { address: '44:80:EB:7B:5A:05', tryCount: 0 } ]
I/jxcore-log( 3227): 
I/jxcore-log( 3227): startWithNextDevice
I/jxcore-log( 3227): 
I/jxcore-log( 3227): do fake peer & start
I/jxcore-log( 3227): 
I/jxcore-log( 3227): Connect to fake peer: F8:95:C7:87:85:54
I/jxcore-log( 3227): 
I/jxcore-log( 3227): 2016-01-12T12:23:27.666Z SendDataConnector.js: Start called with peer F8:95:C7:87:85:54
I/jxcore-log( 3227): 
I/jxcore-log( 3227): 2016-01-12T12:23:27.667Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3227): 
I/jxcore-log( 3227): 2016-01-12T12:23:27.667Z SendDataConnector.js: do connect now
I/jxcore-log( 3227): 
I/io.jxcore.node.ConnectionHelper( 3227): connect: Trying to connect to peer with ID F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 3227): hasConnection: No connection with peer with ID F8:95:C7:87:85:54
W/io.jxcore.node.ConnectionHelper( 3227): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3227): connect: [F8:95:C7:87:85:54 F8:95:C7:87:85:54]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3227): connect: Trying to start connecting to null in address F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3227): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3227): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3227): onConnecting: null F8:95:C7:87:85:54
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3227): connect: Started connecting to null in address F8:95:C7:87:85:54
I/io.jxcore.node.ConnectionHelper( 3227): connect: Connection process successfully started (peer ID: F8:95:C7:87:85:54)
I/jxcore-log( 3227): 2016-01-12T12:23:27.671Z SendDataTCPServer.js: TCP/IP server is bound to port: 44236
I/jxcore-log( 3227): 
I/chromium( 3227): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/io.jxcore.node.ConnectionHelper( 3227): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3227): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3227): P2P device discovery stopped successfully
I/io.jxcore.node.ConnectionHelper( 3227): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3227): Service requests cleared successfully
,I/chromium( 3227): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
I/io.jxcore.node.ConnectionHelper( 3227): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3227): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3227): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3227): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3227): setState: RESTARTING
,I/wpa_supplicant(  986): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3227): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3227): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3227): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3227): onDiscoveryManagerStateChanged: RUNNING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3227): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3227): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3227): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3227): setState: RESTARTING
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3227): Trying to connect to peer with address F8:95:C7:87:85:54 (thread ID: 309)
W/BluetoothAdapter( 3227): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2080): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2080): info:x10
,D/        ( 2080): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,E/BluetoothRemoteDevices( 2080): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2080): process_service_search_attr_rsp
,W/bt-btif ( 2080): info:x10
,D/        ( 2080): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
E/BluetoothRemoteDevices( 2080): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 2080): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1
,E/bt-btif ( 2080): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2080): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2080): Entering PendingCommandState State
,I/ActivityManager(  735): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.BluetoothPairingRequest: pid=3588 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,D/BluetoothManagerService(  735): Message: 20
D/BluetoothManagerService(  735): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@25d3afef:true
,I/ActivityManager(  735): Killing 2569:com.google.android.gm/u0a70 (adj 15): empty #17
,W/libprocessgroup(  735): failed to open /acct/uid_10070/pid_2569/cgroup.procs: No such file or directory
,I/BluetoothBondStateMachine( 2080): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
,D/BluetoothAdapterProperties( 2080): Failed to remove device: F8:95:C7:87:85:54
,I/BluetoothBondStateMachine( 2080): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2080): StableState(): Entering Off State
,I/wpa_supplicant(  986): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3227): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 1: A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 3227): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3227): Service request added successfully
,W/bt-btif ( 2080): new conn_srvc id:26, app_id:1
W/bt-btif ( 2080): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2080): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3227): onSocketConnected: [F8:95:C7:87:85:54 F8:95:C7:87:85:54]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3227): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 309)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3227): onBytesWritten: 66 bytes successfully written (thread ID: 310)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3227): Outgoing connection initialized (*handshake* thread ID: 310)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3227): Exiting thread (thread ID: 309)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3227): Entering thread (ID: 310)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3227): onBytesRead: Read 64 bytes successfully (thread ID: 310)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3227): Handshake succeeded with [F8:95:C7:87:85:54 G3s-1]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3227): onHandshakeSucceeded: [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3227): Exiting thread (ID: 310)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3227): onConnected: [F8:95:C7:87:85:54 G3s-1]
,I/io.jxcore.node.ConnectionHelper( 3227): onConnected: Outgoing connection to peer [F8:95:C7:87:85:54 G3s-1]
D/io.jxcore.node.ConnectionHelper( 3227): hasConnection: No connection with peer with ID F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 3227): notifyPeerAvailability: Peer [F8:95:C7:87:85:54 G3s-1] is available
I/io.jxcore.node.ConnectionHelper( 3227): onConnected: Outgoing socket thread, for peer [F8:95:C7:87:85:54 G3s-1], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3227): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
,D/io.jxcore.node.ConnectionHelper( 3227): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 3227): Entering thread (ID: 311)
D/io.jxcore.node.OutgoingSocketThread( 3227): Server socket local port: 39895
I/io.jxcore.node.OutgoingSocketThread( 3227): Now accepting connections...
,E/bt-btm  ( 2080): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2080): aclStateChangeCallback: Device is NULL
,I/io.jxcore.node.ConnectionHelper( 3227): onListeningForIncomingConnections: Outgoing connection is using port 39895 (peer ID: F8:95:C7:87:85:54)
,I/jxcore-log( 3227): 2016-01-12T12:23:30.409Z SendDataConnector.js: CLIENT connected to 39895, error: null
I/jxcore-log( 3227): 
I/jxcore-log( 3227): 2016-01-12T12:23:30.412Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3227): 
,I/io.jxcore.node.OutgoingSocketThread( 3227): Incoming data from address: /127.0.0.1, port: 39895
D/io.jxcore.node.OutgoingSocketThread( 3227): Setting local streams and starting stream copying threads...
,E/bt-btm  ( 2080): tBTM_SEC_DEV:0xa41d8ebc rs_disc_pending=0
,W/bt-btif ( 2080): bta_dm_check_av:0
,W/bt-btif ( 2080): btif_dm_cback : unhandled event (14)
,I/io.jxcore.node.StreamCopyingThread( 3227): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3227): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.OutgoingSocketThread( 3227): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3227): Exiting thread (ID: 311)
,I/jxcore-log( 3227): 2016-01-12T12:23:30.469Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3227): 
,D/io.jxcore.node.StreamCopyingThread( 3227): Entering thread (ID: 313, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3227): Entering thread (ID: 312, name: Sender)
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3227): Service discovery started successfully
,I/wpa_supplicant(  986): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3227): 2016-01-12T12:23:31.973Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3227): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3227): Start timer timeout, starting now...
,D/        ( 2080): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:30058
,I/wpa_supplicant(  986): p2p0: P2P: Reject scan trigger since one is already pending
,I/jxcore-log( 3227): 2016-01-12T12:23:32.714Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3227): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3227): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3227): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3227): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/jxcore-log( 3227): 2016-01-12T12:23:32.915Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3227): 
,D/        ( 2080): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:9268
,I/jxcore-log( 3227): 2016-01-12T12:23:33.014Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:33.086Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:33.161Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:33.248Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:33.292Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:33.358Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3227): 
,I/wpa_supplicant(  986): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3227): 2016-01-12T12:23:33.589Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3227): 
I/jxcore-log( 3227): 2016-01-12T12:23:33.591Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3227): 
I/jxcore-log( 3227): oneRoundDownNow
I/jxcore-log( 3227): 
I/jxcore-log( 3227): 2016-01-12T12:23:33.595Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3227): 
I/jxcore-log( 3227): 2016-01-12T12:23:33.595Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3227): 
,D/io.jxcore.node.ConnectionHelper( 3227): disconnectOutgoingConnection: Trying to close connection to peer with ID F8:95:C7:87:85:54
I/io.jxcore.node.ConnectionHelper( 3227): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: F8:95:C7:87:85:54
I/io.jxcore.node.OutgoingSocketThread( 3227): close
D/io.jxcore.node.OutgoingSocketThread( 3227): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3227): doStop: Thread ID: 313
D/io.jxcore.node.OutgoingSocketThread( 3227): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3227): doStop: Thread ID: 312
D/io.jxcore.node.OutgoingSocketThread( 3227): closeLocalSocketAndStreams: Closing...
,D/io.jxcore.node.OutgoingSocketThread( 3227): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3227): Either failed to read from the output stream or write to the input stream (thread ID: 312, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3227): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3227): onDisconnected: Outgoing connection, peer [F8:95:C7:87:85:54 G3s-1] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 3227): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 3227): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3227): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3227): Either failed to read from the output stream or write to the input stream (thread ID: 313, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 3227): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3227): onDisconnected: Outgoing connection, peer [F8:95:C7:87:85:54 G3s-1] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3227): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3227): disconnectOutgoingConnection: Successfully disconnected (peer ID: F8:95:C7:87:85:54
,E/io.jxcore.node.ConnectionHelper( 3227): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 3227): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3227): Exiting thread (ID: 312, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 3227): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:95:C7:87:85:54
,W/bt-btif ( 2080): bta_jv_rfc_port_to_cb(port_handle:0x9):jv handle:0x0 not FOUND
,D/io.jxcore.node.ConnectionHelper( 3227): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3227): Exiting thread (ID: 313, name: Receiver)
,I/jxcore-log( 3227): 2016-01-12T12:23:33.657Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3227): 
I/jxcore-log( 3227): ---- round done--------
I/jxcore-log( 3227): 
I/jxcore-log( 3227): startWithNextDevice
I/jxcore-log( 3227): 
I/jxcore-log( 3227): do fake peer & start
I/jxcore-log( 3227): 
I/jxcore-log( 3227): Connect to fake peer: 00:F4:6F:30:E0:6C
I/jxcore-log( 3227): 
I/jxcore-log( 3227): 2016-01-12T12:23:33.658Z SendDataConnector.js: Start called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3227): 
I/jxcore-log( 3227): 2016-01-12T12:23:33.658Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3227): 
I/jxcore-log( 3227): 2016-01-12T12:23:33.658Z SendDataConnector.js: do connect now
I/jxcore-log( 3227): 
I/io.jxcore.node.ConnectionHelper( 3227): connect: Trying to connect to peer with ID 00:F4:6F:30:E0:6C
D/io.jxcore.node.ConnectionHelper( 3227): hasConnection: No connection with peer with ID 00:F4:6F:30:E0:6C
W/io.jxcore.node.ConnectionHelper( 3227): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3227): connect: [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3227): connect: Trying to start connecting to null in address 00:F4:6F:30:E0:6C
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3227): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3227): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3227): onConnecting: null 00:F4:6F:30:E0:6C
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3227): connect: Started connecting to null in address 00:F4:6F:30:E0:6C
I/io.jxcore.node.ConnectionHelper( 3227): connect: Connection process successfully started (peer ID: 00:F4:6F:30:E0:6C)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3227): Trying to connect to peer with address 00:F4:6F:30:E0:6C (thread ID: 314)
W/BluetoothAdapter( 3227): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2080): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2080): tBTM_SEC_DEV:0xa41d8ebc rs_disc_pending=1
W/bt-btif ( 2080): bta_dm_check_av:0
,W/bt-btif ( 2080): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant(  986): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/btif_config_util( 2080): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant(  986): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2080): info:x10
,D/        ( 2080): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,E/BluetoothRemoteDevices( 2080): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2080): process_service_search_attr_rsp
,E/bt-btif ( 2080): DISCOVERY_COMP_EVT slot id:7, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2080): invalid rfc slot id: 7
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3227): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 314)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3227): Maximum number of allowed retries (0) reached, giving up... (thread ID: 314)
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3227): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
,I/wpa_supplicant(  986): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3227): Exiting thread (thread ID: 314)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3227): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C]
I/jxcore-log( 3227): 2016-01-12T12:23:35.143Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C] failed
I/jxcore-log( 3227): 
I/jxcore-log( 3227): 2016-01-12T12:23:35.144Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C] failed
I/jxcore-log( 3227): 
I/jxcore-log( 3227): 2016-01-12T12:23:35.146Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3227): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3227): setInsecureRfcommSocketPort: Will use port 1 when trying to connect
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3227): shutdown (thread ID: 314)
,I/wpa_supplicant(  986): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3227): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 1: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
,I/wpa_supplicant(  986): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  986): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3227): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
,I/wpa_supplicant(  986): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 2080): tBTM_SEC_DEV:0xa41d8ebc rs_disc_pending=0
W/bt-btif ( 2080): bta_dm_check_av:0
,W/bt-btif ( 2080): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant(  986): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3227): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
,E/bt-btm  ( 2080): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2080): onReceive
,D/BluetoothManagerService(  735): Message: 20
D/BluetoothManagerService(  735): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@22c30585:true
,I/BTConnectionReceiver( 1388): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1388): Bluetooth Device Name: G3s-1
,I/wpa_supplicant(  986): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  986): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3227): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
,I/wpa_supplicant(  986): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/btif_config_util( 2080): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant(  986): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3227): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
,I/wpa_supplicant(  986): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 2080): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2080): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant(  986): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  986): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  986): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2080): info:x10
,D/        ( 2080): remote version info [58:3f:54:73:64:c0]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 2080): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant(  986): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3227): 2016-01-12T12:23:40.148Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:40.153Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3227): 
,I/BluetoothBondStateMachine( 2080): bondStateChangeCallback: Status: 0 Address: 58:3F:54:73:64:C0 newState: 1
E/bt-btif ( 2080): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2080): Bond State Change Intent:58:3F:54:73:64:C0 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2080): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2080): bondStateChangeCallback: Status: 0 Address: 58:3F:54:73:64:C0 newState: 0
,D/BluetoothAdapterProperties( 2080): Failed to remove device: 58:3F:54:73:64:C0
,I/BluetoothBondStateMachine( 2080): Bond State Change Intent:58:3F:54:73:64:C0 OldState: 11 NewState: 10
,I/wpa_supplicant(  986): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BluetoothBondStateMachine( 2080): StableState(): Entering Off State
,W/bt-btif ( 2080): new conn_srvc id:26, app_id:255
W/bt-btif ( 2080): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2080): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3227): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3227): Incoming connection initialized (thread ID: 316)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3227): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3227): Entering thread (ID: 316)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3227): onBytesRead: Read 63 bytes successfully (thread ID: 316)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3227): Got valid identity from [58:3F:54:73:64:C0 G3-1]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3227): onBytesWritten: 66 bytes successfully written (thread ID: 316)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3227): removeThreadFromList: Removing thread with ID 316
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3227): Handshake thread disposed (thread ID: 316)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3227): onIncomingConnectionConnected: [58:3F:54:73:64:C0 G3-1]
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3227): Exiting thread (ID: 316)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3227): onConnected: [58:3F:54:73:64:C0 G3-1]
,I/io.jxcore.node.ConnectionHelper( 3227): onConnected: Incoming connection to peer [58:3F:54:73:64:C0 G3-1]
D/io.jxcore.node.ConnectionHelper( 3227): hasConnection: No connection with peer with ID 58:3F:54:73:64:C0
D/io.jxcore.node.ConnectionHelper( 3227): notifyPeerAvailability: Peer [58:3F:54:73:64:C0 G3-1] is available
I/io.jxcore.node.ConnectionHelper( 3227): onConnected: Incoming socket thread, for peer [58:3F:54:73:64:C0 G3-1], created successfully
D/io.jxcore.node.ConnectionHelper( 3227): onConnected: The total number of connections is now 1
,D/io.jxcore.node.IncomingSocketThread( 3227): Entering thread (ID: 317)
,I/io.jxcore.node.IncomingSocketThread( 3227): Local host address: localhost/127.0.0.1, port: 44236
D/io.jxcore.node.IncomingSocketThread( 3227): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3227): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3227): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3227): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3227): Exiting thread (ID: 317)
,I/jxcore-log( 3227): 2016-01-12T12:23:40.566Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3227): 
,D/io.jxcore.node.StreamCopyingThread( 3227): Entering thread (ID: 319, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3227): Entering thread (ID: 318, name: Sender)
,I/wpa_supplicant(  986): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3227): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3227): restart: Restarting...
,D/WifiP2pManager( 3227): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3227): Service request added successfully
,I/wpa_supplicant(  986): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  986): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2080): info:x10
,D/        ( 2080): remote version info [08:ec:a9:50:76:27]: 6, f, 410d
,E/BluetoothRemoteDevices( 2080): aclStateChangeCallback: Device is NULL
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3227): Service discovery started successfully
,I/wpa_supplicant(  986): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 2080): tBTM_SEC_DEV:0xa41d9414 rs_disc_pending=1
W/bt-btif ( 2080): bta_dm_check_av:0
,W/bt-btif ( 2080): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3227): 2016-01-12T12:23:42.523Z SendDataTCPServer.js: TCP/IP server has received 990 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:42.533Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:42.537Z SendDataTCPServer.js: TCP/IP server has received 4950 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:42.558Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:42.572Z SendDataTCPServer.js: TCP/IP server has received 6930 bytes of data
I/jxcore-log( 3227): 
,I/BluetoothBondStateMachine( 2080): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:76:27 newState: 1
E/bt-btif ( 2080): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2080): Bond State Change Intent:08:EC:A9:50:76:27 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2080): Entering PendingCommandState State
,I/jxcore-log( 3227): 2016-01-12T12:23:42.609Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:42.623Z SendDataTCPServer.js: TCP/IP server has received 9182 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:42.629Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:42.632Z SendDataTCPServer.js: TCP/IP server has received 11162 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:42.670Z SendDataTCPServer.js: TCP/IP server has received 15122 bytes of data
I/jxcore-log( 3227): 
,I/BluetoothBondStateMachine( 2080): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:76:27 newState: 0
,D/BluetoothAdapterProperties( 2080): Failed to remove device: 08:EC:A9:50:76:27
,I/BluetoothBondStateMachine( 2080): Bond State Change Intent:08:EC:A9:50:76:27 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2080): StableState(): Entering Off State
,I/jxcore-log( 3227): 2016-01-12T12:23:42.727Z SendDataTCPServer.js: TCP/IP server has received 16112 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:42.766Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:42.822Z SendDataTCPServer.js: TCP/IP server has received 17374 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:42.827Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:42.831Z SendDataTCPServer.js: TCP/IP server has received 19354 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:42.853Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:42.859Z SendDataTCPServer.js: TCP/IP server has received 21334 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:42.893Z SendDataTCPServer.js: TCP/IP server has received 23314 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:42.944Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:42.952Z SendDataTCPServer.js: TCP/IP server has received 25294 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:42.962Z SendDataTCPServer.js: TCP/IP server has received 27274 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:42.971Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:43.013Z SendDataTCPServer.js: TCP/IP server has received 29254 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:43.085Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:43.096Z SendDataTCPServer.js: TCP/IP server has received 31234 bytes of data
I/jxcore-log( 3227): 
,W/bt-btif ( 2080): new conn_srvc id:26, app_id:255
W/bt-btif ( 2080): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2080): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3227): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3227): Incoming connection initialized (thread ID: 320)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3227): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3227): Entering thread (ID: 320)
,I/jxcore-log( 3227): 2016-01-12T12:23:43.132Z SendDataTCPServer.js: TCP/IP server has received 33214 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:43.156Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:43.165Z SendDataTCPServer.js: TCP/IP server has received 35194 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:43.176Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:43.218Z SendDataTCPServer.js: TCP/IP server has received 37174 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:43.248Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:43.254Z SendDataTCPServer.js: TCP/IP server has received 39154 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:43.260Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:43.279Z SendDataTCPServer.js: TCP/IP server has received 41134 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:43.311Z SendDataTCPServer.js: TCP/IP server has received 43114 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:43.435Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:43.447Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:43.455Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:43.461Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3227): 
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3227): onBytesRead: Read 81 bytes successfully (thread ID: 320)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3227): Got valid identity from [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3227): onBytesWritten: 66 bytes successfully written (thread ID: 320)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3227): removeThreadFromList: Removing thread with ID 320
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3227): Handshake thread disposed (thread ID: 320)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3227): onIncomingConnectionConnected: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3227): Exiting thread (ID: 320)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3227): onConnected: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/io.jxcore.node.ConnectionHelper( 3227): onConnected: Incoming connection to peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/io.jxcore.node.ConnectionHelper( 3227): hasConnection: No connection with peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 3227): notifyPeerAvailability: Peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)] is available
,I/io.jxcore.node.ConnectionHelper( 3227): onConnected: Incoming socket thread, for peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], created successfully
D/io.jxcore.node.ConnectionHelper( 3227): onConnected: The total number of connections is now 2
,D/io.jxcore.node.IncomingSocketThread( 3227): Entering thread (ID: 321)
,I/io.jxcore.node.IncomingSocketThread( 3227): Local host address: localhost/127.0.0.1, port: 44236
D/io.jxcore.node.IncomingSocketThread( 3227): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3227): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3227): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3227): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3227): Exiting thread (ID: 321)
,I/jxcore-log( 3227): 2016-01-12T12:23:43.499Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3227): 
,D/io.jxcore.node.StreamCopyingThread( 3227): Entering thread (ID: 322, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 3227): Entering thread (ID: 323, name: Receiver)
,I/jxcore-log( 3227): 2016-01-12T12:23:43.522Z SendDataTCPServer.js: TCP/IP server has received 51034 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:43.561Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:43.563Z SendDataTCPServer.js: TCP/IP server has received 54994 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:43.575Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:43.578Z SendDataTCPServer.js: TCP/IP server has received 56974 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:43.582Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:43.732Z SendDataTCPServer.js: TCP/IP server has received 58954 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:43.736Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:43.746Z SendDataTCPServer.js: TCP/IP server has received 60934 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:43.751Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:43.793Z SendDataTCPServer.js: TCP/IP server has received 64894 bytes of data
I/jxcore-log( 3227): 
,E/bt-btm  ( 2080): tBTM_SEC_DEV:0xa41d9084 rs_disc_pending=0
W/bt-btif ( 2080): bta_dm_check_av:0
,W/bt-btif ( 2080): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3227): 2016-01-12T12:23:43.876Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:43.885Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:44.063Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:44.129Z SendDataTCPServer.js: TCP/IP server has received 70834 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:44.141Z SendDataTCPServer.js: TCP/IP server has received 72814 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:44.175Z SendDataTCPServer.js: TCP/IP server has received 74794 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:44.324Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:44.660Z SendDataTCPServer.js: TCP/IP server has received 76774 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:44.696Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:44.727Z SendDataTCPServer.js: TCP/IP server has received 6930 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:44.732Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:44.739Z SendDataTCPServer.js: TCP/IP server has received 78754 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:44.838Z SendDataTCPServer.js: TCP/IP server has received 8910 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:44.845Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:44.860Z SendDataTCPServer.js: TCP/IP server has received 10890 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:44.941Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:44.966Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:45.123Z SendDataTCPServer.js: TCP/IP server has received 12870 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:45.134Z SendDataTCPServer.js: TCP/IP server has received 80734 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:45.144Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:45.151Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3227): 
,D/io.jxcore.node.ConnectionHelper( 3227): disconnectOutgoingConnection: Trying to close connection to peer with ID 00:F4:6F:30:E0:6C
,E/io.jxcore.node.ConnectionHelper( 3227): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:F4:6F:30:E0:6C
D/io.jxcore.node.ConnectionHelper( 3227): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3227): disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:F4:6F:30:E0:6C), either no such connection or failed to close the connection
I/jxcore-log( 3227): 2016-01-12T12:23:45.163Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3227): 
I/jxcore-log( 3227): 2016-01-12T12:23:45.164Z SendDataConnector.js: Connect (retry count 1) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3227): 
I/jxcore-log( 3227): 2016-01-12T12:23:45.164Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3227): 
I/jxcore-log( 3227): 2016-01-12T12:23:45.165Z SendDataConnector.js: do connect now
I/jxcore-log( 3227): 
I/io.jxcore.node.ConnectionHelper( 3227): connect: Trying to connect to peer with ID 00:F4:6F:30:E0:6C
D/io.jxcore.node.ConnectionHelper( 3227): hasConnection: No connection with peer with ID 00:F4:6F:30:E0:6C
W/io.jxcore.node.ConnectionHelper( 3227): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3227): connect: [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3227): connect: Trying to start connecting to null in address 00:F4:6F:30:E0:6C
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3227): setInsecureRfcommSocketPort: Using port 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3227): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3227): onConnecting: null 00:F4:6F:30:E0:6C
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3227): connect: Started connecting to null in address 00:F4:6F:30:E0:6C
I/io.jxcore.node.ConnectionHelper( 3227): connect: Connection process successfully started (peer ID: 00:F4:6F:30:E0:6C)
I/jxcore-log( 3227): 2016-01-12T12:23:45.176Z SendDataTCPServer.js: TCP/IP server has received 14850 bytes of data
I/jxcore-log( 3227): 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3227): Trying to connect to peer with address 00:F4:6F:30:E0:6C (thread ID: 324)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3227): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3227): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2080): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/jxcore-log( 3227): 2016-01-12T12:23:45.187Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:45.192Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:45.207Z SendDataTCPServer.js: TCP/IP server has received 82714 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:45.213Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:45.220Z SendDataTCPServer.js: TCP/IP server has received 84694 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:45.226Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:45.260Z SendDataTCPServer.js: TCP/IP server has received 86674 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:45.357Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:45.364Z SendDataTCPServer.js: TCP/IP server has received 88654 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:45.369Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:45.399Z SendDataTCPServer.js: TCP/IP server has received 90634 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:45.410Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 3227): 
,E/bt-btm  ( 2080): tBTM_SEC_DEV:0xa41d9084 rs_disc_pending=1
W/bt-btif ( 2080): bta_dm_check_av:0
,W/bt-btif ( 2080): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3227): 2016-01-12T12:23:45.438Z SendDataTCPServer.js: TCP/IP server has received 17374 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:45.452Z SendDataTCPServer.js: TCP/IP server has received 92614 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:45.461Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:45.467Z SendDataTCPServer.js: TCP/IP server has received 19354 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:45.473Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:45.484Z SendDataTCPServer.js: TCP/IP server has received 21334 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:45.526Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:45.554Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3227): 
,D/btif_config_util( 2080): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3227): 2016-01-12T12:23:47.556Z SendDataTCPServer.js: TCP/IP server has received 23314 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:48.101Z SendDataTCPServer.js: TCP/IP server has received 94594 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:48.122Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:48.131Z SendDataTCPServer.js: TCP/IP server has received 25294 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:48.139Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:48.153Z SendDataTCPServer.js: TCP/IP server has received 96574 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:48.159Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:48.204Z SendDataTCPServer.js: TCP/IP server has received 98554 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:48.211Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:48.216Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3227): 
,E/bt-btm  ( 2080): tBTM_SEC_DEV:0xa41d9414 rs_disc_pending=0
W/bt-btif ( 2080): bta_dm_check_av:0
,W/bt-btif ( 2080): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2080): invalid rfc slot id: 5
,W/io.jxcore.node.StreamCopyingThread( 3227): Either failed to read from the output stream or write to the input stream (thread ID: 319, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 3227): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3227): onDisconnected: Incoming connection, peer [58:3F:54:73:64:C0 G3-1] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3227): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 317
D/io.jxcore.node.IncomingSocketThread( 3227): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3227): doStop: Thread ID: 319
D/io.jxcore.node.IncomingSocketThread( 3227): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3227): doStop: Thread ID: 318
D/io.jxcore.node.IncomingSocketThread( 3227): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 3227): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3227): Either failed to read from the output stream or write to the input stream (thread ID: 318, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3227): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
,W/io.jxcore.node.ConnectionHelper( 3227): onDisconnected: Incoming connection, peer [58:3F:54:73:64:C0 G3-1] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.IncomingSocketThread( 3227): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 3227): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3227): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3227): closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,D/io.jxcore.node.ConnectionHelper( 3227): closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,D/io.jxcore.node.StreamCopyingThread( 3227): Exiting thread (ID: 318, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 3227): Exiting thread (ID: 319, name: Receiver)
,I/jxcore-log( 3227): 2016-01-12T12:23:48.801Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3227): 
,E/bt-btm  ( 2080): tBTM_SEC_DEV:0xa41d9414 rs_disc_pending=1
W/bt-btif ( 2080): bta_dm_check_av:0
,W/bt-btif ( 2080): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 2080): rfc_find_lcid_mcb LCID reused LCID:0x45 current:0x0
W/bt-rfcomm( 2080): RFCOMM_DisconnectInd LCID:0x45
,W/bt-btif ( 2080): info:x10
,D/        ( 2080): remote version info [00:f4:6f:30:e0:6c]: 0, 0, 0
,E/BluetoothRemoteDevices( 2080): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3227): 2016-01-12T12:23:50.475Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:50.484Z SendDataTCPServer.js: TCP/IP server has received 27274 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:50.489Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3227): 
,W/bt-btif ( 2080): info:x10
,D/        ( 2080): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 2080): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3227): 2016-01-12T12:23:50.703Z SendDataTCPServer.js: TCP/IP server has received 29254 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:50.713Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:50.726Z SendDataTCPServer.js: TCP/IP server has received 31234 bytes of data
I/jxcore-log( 3227): 
,W/bt-sdp  ( 2080): process_service_search_attr_rsp
,E/bt-btif ( 2080): DISCOVERY_COMP_EVT slot id:10, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2080): invalid rfc slot id: 10
,W/BluetoothAdapter( 3227): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2080): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/jxcore-log( 3227): 2016-01-12T12:23:50.756Z SendDataTCPServer.js: TCP/IP server has received 33214 bytes of data
I/jxcore-log( 3227): 
,E/bt-btm  ( 2080): tBTM_SEC_DEV:0xa41d9414 rs_disc_pending=0
W/bt-btif ( 2080): bta_dm_check_av:0
,W/bt-btif ( 2080): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 2080): process_service_search_attr_rsp
,I/jxcore-log( 3227): 2016-01-12T12:23:50.972Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:50.978Z SendDataTCPServer.js: TCP/IP server has received 35194 bytes of data
I/jxcore-log( 3227): 
,E/bt-btif ( 2080): DISCOVERY_COMP_EVT slot id:11, failed to find channle,                                       status:1, scn:0
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3227): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 324)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3227): Maximum number of allowed retries (0) reached, giving up... (thread ID: 324)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3227): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3227): Exiting thread (thread ID: 324)
,W/bt-btif ( 2080): invalid rfc slot id: 11
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3227): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C]
I/jxcore-log( 3227): 2016-01-12T12:23:51.012Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C] failed
I/jxcore-log( 3227): 
I/jxcore-log( 3227): 2016-01-12T12:23:51.013Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C] failed
I/jxcore-log( 3227): 
I/jxcore-log( 3227): 2016-01-12T12:23:51.014Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3227): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3227): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3227): shutdown (thread ID: 324)
,I/jxcore-log( 3227): 2016-01-12T12:23:51.056Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:51.163Z SendDataTCPServer.js: TCP/IP server has received 37174 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:51.169Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:51.176Z SendDataTCPServer.js: TCP/IP server has received 39154 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:51.182Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:51.445Z SendDataTCPServer.js: TCP/IP server has received 41134 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:51.482Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:51.498Z SendDataTCPServer.js: TCP/IP server has received 45094 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:51.512Z SendDataTCPServer.js: TCP/IP server has received 47074 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:51.617Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:51.624Z SendDataTCPServer.js: TCP/IP server has received 49054 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:51.631Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:51.649Z SendDataTCPServer.js: TCP/IP server has received 51034 bytes of data
I/jxcore-log( 3227): 
,E/bt-btm  ( 2080): tBTM_SEC_DEV:0xa41d9414 rs_disc_pending=1
W/bt-btif ( 2080): bta_dm_check_av:0
,W/bt-btif ( 2080): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3227): 2016-01-12T12:23:51.754Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:51.764Z SendDataTCPServer.js: TCP/IP server has received 53014 bytes of data
I/jxcore-log( 3227): 
,I/BluetoothBondStateMachine( 2080): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 1
E/bt-btif ( 2080): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2080): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2080): Entering PendingCommandState State
,I/jxcore-log( 3227): 2016-01-12T12:23:51.810Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:51.837Z SendDataTCPServer.js: TCP/IP server has received 56974 bytes of data
I/jxcore-log( 3227): 
,I/BluetoothBondStateMachine( 2080): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 0
,D/BluetoothAdapterProperties( 2080): Failed to remove device: 44:80:EB:7B:5A:05
,I/BluetoothBondStateMachine( 2080): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2080): StableState(): Entering Off State
,I/jxcore-log( 3227): 2016-01-12T12:23:51.992Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:51.998Z SendDataTCPServer.js: TCP/IP server has received 58954 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:52.004Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3227): 
,W/bt-btif ( 2080): new conn_srvc id:26, app_id:255
W/bt-btif ( 2080): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2080): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3227): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3227): Incoming connection initialized (thread ID: 326)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3227): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3227): Entering thread (ID: 326)
,I/jxcore-log( 3227): 2016-01-12T12:23:52.249Z SendDataTCPServer.js: TCP/IP server has received 60934 bytes of data
I/jxcore-log( 3227): 
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3227): onBytesRead: Read 65 bytes successfully (thread ID: 326)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3227): Got valid identity from [44:80:EB:7B:5A:05 XT1072]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3227): onBytesWritten: 66 bytes successfully written (thread ID: 326)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3227): removeThreadFromList: Removing thread with ID 326
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3227): Handshake thread disposed (thread ID: 326)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3227): onIncomingConnectionConnected: [44:80:EB:7B:5A:05 XT1072]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3227): Exiting thread (ID: 326)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3227): onConnected: [44:80:EB:7B:5A:05 XT1072]
I/io.jxcore.node.ConnectionHelper( 3227): onConnected: Incoming connection to peer [44:80:EB:7B:5A:05 XT1072]
,D/io.jxcore.node.ConnectionHelper( 3227): hasConnection: No connection with peer with ID 44:80:EB:7B:5A:05
D/io.jxcore.node.ConnectionHelper( 3227): notifyPeerAvailability: Peer [44:80:EB:7B:5A:05 XT1072] is available
,I/io.jxcore.node.ConnectionHelper( 3227): onConnected: Incoming socket thread, for peer [44:80:EB:7B:5A:05 XT1072], created successfully
D/io.jxcore.node.ConnectionHelper( 3227): onConnected: The total number of connections is now 2
,I/jxcore-log( 3227): 2016-01-12T12:23:52.360Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3227): 
,D/io.jxcore.node.IncomingSocketThread( 3227): Entering thread (ID: 327)
,I/jxcore-log( 3227): 2016-01-12T12:23:52.385Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3227): 
,I/io.jxcore.node.IncomingSocketThread( 3227): Local host address: localhost/127.0.0.1, port: 44236
D/io.jxcore.node.IncomingSocketThread( 3227): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3227): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3227): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3227): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3227): Exiting thread (ID: 327)
,D/io.jxcore.node.StreamCopyingThread( 3227): Entering thread (ID: 329, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3227): Entering thread (ID: 328, name: Sender)
,I/jxcore-log( 3227): 2016-01-12T12:23:52.391Z SendDataTCPServer.js: TCP/IP server has received 62914 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:52.424Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:52.434Z SendDataTCPServer.js: TCP/IP server has received 64894 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:52.440Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:52.451Z SendDataTCPServer.js: TCP/IP server has received 66874 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:52.519Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:52.524Z SendDataTCPServer.js: TCP/IP server has received 68854 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:52.532Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:52.539Z SendDataTCPServer.js: TCP/IP server has received 70834 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:52.594Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:52.632Z SendDataTCPServer.js: TCP/IP server has received 72814 bytes of data
I/jxcore-log( 3227): 
,E/bt-btm  ( 2080): tBTM_SEC_DEV:0xa41d95dc rs_disc_pending=0
W/bt-btif ( 2080): bta_dm_check_av:0
,W/bt-btif ( 2080): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3227): 2016-01-12T12:23:52.694Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:52.701Z SendDataTCPServer.js: TCP/IP server has received 74794 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:52.712Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:52.796Z SendDataTCPServer.js: TCP/IP server has received 76774 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:52.879Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:52.887Z SendDataTCPServer.js: TCP/IP server has received 78754 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:52.959Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:52.966Z SendDataTCPServer.js: TCP/IP server has received 80734 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:52.975Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:53.024Z SendDataTCPServer.js: TCP/IP server has received 82714 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:53.043Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3227): 
,E/bt-btm  ( 2080): tBTM_SEC_DEV:0xa41d9414 rs_disc_pending=0
W/bt-btif ( 2080): bta_dm_check_av:0
,W/bt-btif ( 2080): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3227): 2016-01-12T12:23:53.192Z SendDataTCPServer.js: TCP/IP server has received 84694 bytes of data
I/jxcore-log( 3227): 
,E/bt-btm  ( 2080): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2080): onReceive
,I/BTConnectionReceiver( 1388): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1388): Bluetooth Device Name: G3-1
,I/jxcore-log( 3227): 2016-01-12T12:23:53.532Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 3227): 
,E/bt-btm  ( 2080): tBTM_SEC_DEV:0xa41d95dc rs_disc_pending=1
W/bt-btif ( 2080): bta_dm_check_av:0
,W/bt-btif ( 2080): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3227): 2016-01-12T12:23:53.643Z SendDataTCPServer.js: TCP/IP server has received 86674 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:53.652Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:53.712Z SendDataTCPServer.js: TCP/IP server has received 88654 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:53.743Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:53.794Z SendDataTCPServer.js: TCP/IP server has received 90634 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:53.813Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:53.872Z SendDataTCPServer.js: TCP/IP server has received 990 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:53.894Z SendDataTCPServer.js: TCP/IP server has received 92614 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:53.904Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:53.983Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:53.990Z SendDataTCPServer.js: TCP/IP server has received 2970 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:54.045Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:54.077Z SendDataTCPServer.js: TCP/IP server has received 94594 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:54.086Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 3227): 
,E/bt-btm  ( 2080): tBTM_SEC_DEV:0xa41d924c rs_disc_pending=0
W/bt-btif ( 2080): bta_dm_check_av:0
,W/bt-btif ( 2080): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3227): 2016-01-12T12:23:54.144Z SendDataTCPServer.js: TCP/IP server has received 96574 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:54.152Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:54.252Z SendDataTCPServer.js: TCP/IP server has received 4950 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:54.259Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:54.320Z SendDataTCPServer.js: TCP/IP server has received 6930 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:54.330Z SendDataTCPServer.js: TCP/IP server has received 98554 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:54.338Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:54.343Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3227): 
,E/bt-btm  ( 2080): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2080): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3227): 2016-01-12T12:23:54.440Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:54.447Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:54.453Z SendDataTCPServer.js: TCP/IP server has received 9182 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:54.632Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:54.643Z SendDataTCPServer.js: TCP/IP server has received 11162 bytes of data
I/jxcore-log( 3227): 
,E/bt-btm  ( 2080): tBTM_SEC_DEV:0xa41d9084 rs_disc_pending=0
W/bt-btif ( 2080): bta_dm_check_av:0
,W/bt-btif ( 2080): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3227): 2016-01-12T12:23:54.830Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:54.903Z SendDataTCPServer.js: TCP/IP server has received 13142 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:54.936Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:54.944Z SendDataTCPServer.js: TCP/IP server has received 15122 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:55.025Z SendDataTCPServer.js: TCP/IP server has received 16112 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:55.065Z SendDataTCPServer.js: TCP/IP server has received 17102 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:55.074Z SendDataTCPServer.js: TCP/IP server has received 18092 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:55.144Z SendDataTCPServer.js: TCP/IP server has received 19082 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:55.178Z SendDataTCPServer.js: TCP/IP server has received 20072 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:55.335Z SendDataTCPServer.js: TCP/IP server has received 21062 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:55.373Z SendDataTCPServer.js: TCP/IP server has received 22052 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:55.378Z SendDataTCPServer.js: TCP/IP server has received 23042 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:55.453Z SendDataTCPServer.js: TCP/IP server has received 24032 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:55.462Z SendDataTCPServer.js: TCP/IP server has received 25022 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:55.469Z SendDataTCPServer.js: TCP/IP server has received 26012 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:55.634Z SendDataTCPServer.js: TCP/IP server has received 27002 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:55.665Z SendDataTCPServer.js: TCP/IP server has received 27992 bytes of data
I/jxcore-log( 3227): 
,W/bt-btif ( 2080): invalid rfc slot id: 8
,W/io.jxcore.node.StreamCopyingThread( 3227): Either failed to read from the output stream or write to the input stream (thread ID: 323, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 3227): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3227): onDisconnected: Incoming connection, peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3227): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 321
D/io.jxcore.node.IncomingSocketThread( 3227): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3227): doStop: Thread ID: 323
D/io.jxcore.node.IncomingSocketThread( 3227): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3227): doStop: Thread ID: 322
D/io.jxcore.node.IncomingSocketThread( 3227): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 3227): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3227): Either failed to read from the output stream or write to the input stream (thread ID: 322, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3227): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3227): onDisconnected: Incoming connection, peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.IncomingSocketThread( 3227): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 3227): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3227): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3227): closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3227): Exiting thread (ID: 323, name: Receiver)
,D/io.jxcore.node.ConnectionHelper( 3227): closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,D/io.jxcore.node.StreamCopyingThread( 3227): Exiting thread (ID: 322, name: Sender)
,I/jxcore-log( 3227): 2016-01-12T12:23:55.754Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3227): ,
I/jxcore-log( 3227): 2016-01-12T12:23:55.757Z SendDataTCPServer.js: TCP/IP server has received 29972 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:55.774Z SendDataTCPServer.js: TCP/IP server has received 30962 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:55.813Z SendDataTCPServer.js: TCP/IP server has received 31952 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:55.856Z SendDataTCPServer.js: TCP/IP server has received 32942 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:55.895Z SendDataTCPServer.js: TCP/IP server has received 33932 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:55.964Z SendDataTCPServer.js: TCP/IP server has received 34922 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:55.970Z SendDataTCPServer.js: TCP/IP server has received 35912 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:56.015Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3227): 
I/jxcore-log( 3227): 2016-01-12T12:23:56.015Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:56.075Z SendDataTCPServer.js: TCP/IP server has received 36902 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:56.189Z SendDataTCPServer.js: TCP/IP server has received 37892 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:56.254Z SendDataTCPServer.js: TCP/IP server has received 38882 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:56.261Z SendDataTCPServer.js: TCP/IP server has received 39872 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:56.349Z SendDataTCPServer.js: TCP/IP server has received 40862 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:56.363Z SendDataTCPServer.js: TCP/IP server has received 41852 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:56.391Z SendDataTCPServer.js: TCP/IP server has received 42842 bytes of data
I/jxcore-log( 3227): 
,D/btif_config_util( 2080): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3227): 2016-01-12T12:23:56.562Z SendDataTCPServer.js: TCP/IP server has received 43832 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:56.568Z SendDataTCPServer.js: TCP/IP server has received 44822 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:56.574Z SendDataTCPServer.js: TCP/IP server has received 45812 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:56.665Z SendDataTCPServer.js: TCP/IP server has received 46802 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:56.699Z SendDataTCPServer.js: TCP/IP server has received 47792 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:56.706Z SendDataTCPServer.js: TCP/IP server has received 48782 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:56.743Z SendDataTCPServer.js: TCP/IP server has received 49772 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:56.838Z SendDataTCPServer.js: TCP/IP server has received 50762 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:56.872Z SendDataTCPServer.js: TCP/IP server has received 51752 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:56.915Z SendDataTCPServer.js: TCP/IP server has received 52742 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:56.983Z SendDataTCPServer.js: TCP/IP server has received 53732 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:56.989Z SendDataTCPServer.js: TCP/IP server has received 54722 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:56.998Z SendDataTCPServer.js: TCP/IP server has received 55712 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:57.046Z SendDataTCPServer.js: TCP/IP server has received 56702 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:57.053Z SendDataTCPServer.js: TCP/IP server has received 57692 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:57.103Z SendDataTCPServer.js: TCP/IP server has received 58682 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:57.109Z SendDataTCPServer.js: TCP/IP server has received 59672 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:57.123Z SendDataTCPServer.js: TCP/IP server has received 60662 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:57.152Z SendDataTCPServer.js: TCP/IP server has received 61652 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:57.264Z SendDataTCPServer.js: TCP/IP server has received 62642 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:57.273Z SendDataTCPServer.js: TCP/IP server has received 63632 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:57.278Z SendDataTCPServer.js: TCP/IP server has received 64622 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:57.334Z SendDataTCPServer.js: TCP/IP server has received 65612 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:57.420Z SendDataTCPServer.js: TCP/IP server has received 66602 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:57.427Z SendDataTCPServer.js: TCP/IP server has received 67592 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:57.435Z SendDataTCPServer.js: TCP/IP server has received 68582 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:57.486Z SendDataTCPServer.js: TCP/IP server has received 69572 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:57.547Z SendDataTCPServer.js: TCP/IP server has received 70562 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:57.589Z SendDataTCPServer.js: TCP/IP server has received 71552 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:57.635Z SendDataTCPServer.js: TCP/IP server has received 72542 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:57.645Z SendDataTCPServer.js: TCP/IP server has received 73532 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:57.724Z SendDataTCPServer.js: TCP/IP server has received 74522 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:57.732Z SendDataTCPServer.js: TCP/IP server has received 75512 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:57.742Z SendDataTCPServer.js: TCP/IP server has received 76502 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:57.763Z SendDataTCPServer.js: TCP/IP server has received 77492 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:57.769Z SendDataTCPServer.js: TCP/IP server has received 78482 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:57.798Z SendDataTCPServer.js: TCP/IP server has received 79472 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:57.805Z SendDataTCPServer.js: TCP/IP server has received 80462 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:57.820Z SendDataTCPServer.js: TCP/IP server has received 81452 bytes of data
I/jxcore-log( 3227): 
,E/bt-btm  ( 2080): tBTM_SEC_DEV:0xa41d9084 rs_disc_pending=1
W/bt-btif ( 2080): bta_dm_check_av:0
,W/bt-btif ( 2080): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3227): 2016-01-12T12:23:57.873Z SendDataTCPServer.js: TCP/IP server has received 82442 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:57.879Z SendDataTCPServer.js: TCP/IP server has received 83432 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:57.886Z SendDataTCPServer.js: TCP/IP server has received 84422 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:57.918Z SendDataTCPServer.js: TCP/IP server has received 85412 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:57.926Z SendDataTCPServer.js: TCP/IP server has received 86402 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:57.931Z SendDataTCPServer.js: TCP/IP server has received 87392 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:58.022Z SendDataTCPServer.js: TCP/IP server has received 88382 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:58.028Z SendDataTCPServer.js: TCP/IP server has received 89372 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:58.063Z SendDataTCPServer.js: TCP/IP server has received 90362 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:58.074Z SendDataTCPServer.js: TCP/IP server has received 91352 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:58.103Z SendDataTCPServer.js: TCP/IP server has received 92342 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:58.109Z SendDataTCPServer.js: TCP/IP server has received 93332 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:58.165Z SendDataTCPServer.js: TCP/IP server has received 94322 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:58.174Z SendDataTCPServer.js: TCP/IP server has received 95312 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:58.212Z SendDataTCPServer.js: TCP/IP server has received 96302 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:58.225Z SendDataTCPServer.js: TCP/IP server has received 97292 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:58.231Z SendDataTCPServer.js: TCP/IP server has received 98282 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:58.262Z SendDataTCPServer.js: TCP/IP server has received 99272 bytes of data
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:23:58.307Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3227): 
,W/bt-btif ( 2080): invalid rfc slot id: 9
,W/io.jxcore.node.StreamCopyingThread( 3227): Either failed to read from the output stream or write to the input stream (thread ID: 329, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 3227): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3227): onDisconnected: Incoming connection, peer [44:80:EB:7B:5A:05 XT1072] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3227): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 327
D/io.jxcore.node.IncomingSocketThread( 3227): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3227): doStop: Thread ID: 329
D/io.jxcore.node.IncomingSocketThread( 3227): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3227): doStop: Thread ID: 328
D/io.jxcore.node.IncomingSocketThread( 3227): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 3227): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3227): Either failed to read from the output stream or write to the input stream (thread ID: 328, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3227): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3227): onDisconnected: Incoming connection, peer [44:80:EB:7B:5A:05 XT1072] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,W/bt-rfcomm( 2080): rfc_find_lcid_mcb LCID reused LCID:0x4b current:0x0
W/bt-rfcomm( 2080): RFCOMM_DisconnectInd LCID:0x4b
,D/io.jxcore.node.IncomingSocketThread( 3227): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 3227): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3227): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3227): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.ConnectionHelper( 3227): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3227): Exiting thread (ID: 328, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 3227): Exiting thread (ID: 329, name: Receiver)
,I/jxcore-log( 3227): 2016-01-12T12:23:58.434Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3227): 
,E/bt-btm  ( 2080): tBTM_SEC_DEV:0xa41d95dc rs_disc_pending=0
W/bt-btif ( 2080): bta_dm_check_av:0
,W/bt-btif ( 2080): btif_dm_cback : unhandled event (14)
,D/io.jxcore.node.ConnectionHelper( 3227): disconnectOutgoingConnection: Trying to close connection to peer with ID 00:F4:6F:30:E0:6C
E/io.jxcore.node.ConnectionHelper( 3227): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:F4:6F:30:E0:6C
D/io.jxcore.node.ConnectionHelper( 3227): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3227): disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:F4:6F:30:E0:6C), either no such connection or failed to close the connection
,I/jxcore-log( 3227): 2016-01-12T12:24:01.025Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3227): 
I/jxcore-log( 3227): 2016-01-12T12:24:01.026Z SendDataConnector.js: Connect (retry count 2) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:24:01.044Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3227): 
I/jxcore-log( 3227): 2016-01-12T12:24:01.045Z SendDataConnector.js: do connect now
I/jxcore-log( 3227): 
I/io.jxcore.node.ConnectionHelper( 3227): connect: Trying to connect to peer with ID 00:F4:6F:30:E0:6C
D/io.jxcore.node.ConnectionHelper( 3227): hasConnection: No connection with peer with ID 00:F4:6F:30:E0:6C
W/io.jxcore.node.ConnectionHelper( 3227): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3227): connect: [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3227): connect: Trying to start connecting to null in address 00:F4:6F:30:E0:6C
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3227): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3227): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3227): onConnecting: null 00:F4:6F:30:E0:6C
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3227): connect: Started connecting to null in address 00:F4:6F:30:E0:6C
I/io.jxcore.node.ConnectionHelper( 3227): connect: Connection process successfully started (peer ID: 00:F4:6F:30:E0:6C)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3227): Trying to connect to peer with address 00:F4:6F:30:E0:6C (thread ID: 330)
W/BluetoothAdapter( 3227): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2080): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2080): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2080): onReceive
,I/BTConnectionReceiver( 1388): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1388): Bluetooth Device Name: Thali Test (Galaxy A3)
,W/bt-btm  ( 2080): btm_acl_role_changed -> Issuing delayed HCI_Disconnect!!!
E/bt-btm  ( 2080): tBTM_SEC_DEV:0xa41d95dc rs_disc_pending=2
W/bt-btif ( 2080): bta_dm_check_av:0
,W/bt-btif ( 2080): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2080): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2080): onReceive
,I/BTConnectionReceiver( 1388): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1388): Bluetooth Device Name: XT1072
,W/bt-btif ( 2080): info:x10
,D/        ( 2080): remote version info [00:f4:6f:30:e0:6c]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 2080): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2080): process_service_search_attr_rsp
,E/bt-btif ( 2080): DISCOVERY_COMP_EVT slot id:13, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2080): invalid rfc slot id: 13
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3227): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 330)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3227): Maximum number of allowed retries (0) reached, giving up... (thread ID: 330)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3227): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3227): Exiting thread (thread ID: 330)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3227): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C]
I/jxcore-log( 3227): 2016-01-12T12:24:03.124Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C] failed
I/jxcore-log( 3227): 
I/jxcore-log( 3227): 2016-01-12T12:24:03.125Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C] failed
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:24:03.125Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3227): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3227): setInsecureRfcommSocketPort: Will use port 1 when trying to connect
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3227): shutdown (thread ID: 330)
,D/btif_config_util( 2080): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2080): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2080): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3227): 2016-01-12T12:24:08.126Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3227): 
I/jxcore-log( 3227): 2016-01-12T12:24:08.127Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3227): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3227): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3227): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3227): setState: RESTARTING
,I/wpa_supplicant(  986): P2P-FIND-STOPPED 
,I/wpa_supplicant(  986): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant(  986): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant(  986): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant(  986): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
I/wpa_supplicant(  986): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant(  986): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3227): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3227): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3227): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3227): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3227): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3227): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3227): onP2pDeviceListChanged: 0 device(s) discovered
,D/io.jxcore.node.ConnectionHelper( 3227): disconnectOutgoingConnection: Trying to close connection to peer with ID 00:F4:6F:30:E0:6C
E/io.jxcore.node.ConnectionHelper( 3227): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:F4:6F:30:E0:6C
D/io.jxcore.node.ConnectionHelper( 3227): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3227): disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:F4:6F:30:E0:6C), either no such connection or failed to close the connection
I/jxcore-log( 3227): 2016-01-12T12:24:13.129Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:24:13.129Z SendDataConnector.js: Connect (retry count 3) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3227): 
I/jxcore-log( 3227): 2016-01-12T12:24:13.129Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3227): 
I/jxcore-log( 3227): 2016-01-12T12:24:13.129Z SendDataConnector.js: do connect now
I/jxcore-log( 3227): 
I/io.jxcore.node.ConnectionHelper( 3227): connect: Trying to connect to peer with ID 00:F4:6F:30:E0:6C
D/io.jxcore.node.ConnectionHelper( 3227): hasConnection: No connection with peer with ID 00:F4:6F:30:E0:6C
W/io.jxcore.node.ConnectionHelper( 3227): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3227): connect: [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3227): connect: Trying to start connecting to null in address 00:F4:6F:30:E0:6C
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3227): setInsecureRfcommSocketPort: Using port 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3227): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3227): onConnecting: null 00:F4:6F:30:E0:6C
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3227): connect: Started connecting to null in address 00:F4:6F:30:E0:6C
I/io.jxcore.node.ConnectionHelper( 3227): connect: Connection process successfully started (peer ID: 00:F4:6F:30:E0:6C)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3227): Trying to connect to peer with address 00:F4:6F:30:E0:6C (thread ID: 332)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3227): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
,W/BluetoothAdapter( 3227): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2080): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2080): info:x10
,D/        ( 2080): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,E/BluetoothRemoteDevices( 2080): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2080): process_service_search_attr_rsp
,E/bt-btif ( 2080): DISCOVERY_COMP_EVT slot id:14, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2080): invalid rfc slot id: 14
,W/BluetoothAdapter( 3227): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2080): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2080): process_service_search_attr_rsp
,E/bt-btif ( 2080): DISCOVERY_COMP_EVT slot id:15, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2080): invalid rfc slot id: 15
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3227): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 332)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3227): Maximum number of allowed retries (0) reached, giving up... (thread ID: 332)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3227): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3227): Exiting thread (thread ID: 332)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3227): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C]
,I/jxcore-log( 3227): 2016-01-12T12:24:14.731Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C] failed
I/jxcore-log( 3227): 
I/jxcore-log( 3227): 2016-01-12T12:24:14.732Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C] failed
I/jxcore-log( 3227): 
I/jxcore-log( 3227): 2016-01-12T12:24:14.732Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3227): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3227): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3227): shutdown (thread ID: 332)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3227): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3227): P2P device discovery started successfully
,I/wpa_supplicant(  986): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3227): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3227): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,D/btif_config_util( 2080): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant(  986): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 2080): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2080): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant(  986): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  986): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  986): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3227): 2016-01-12T12:24:19.734Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3227): 
I/jxcore-log( 3227): 2016-01-12T12:24:19.735Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3227): 
,I/wpa_supplicant(  986): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  986): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  986): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  986): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  986): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  986): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3227): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3227): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3227): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
,D/WifiP2pManager( 3227): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3227): Service request added successfully
,I/wpa_supplicant(  986): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  986): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3227): Service discovery started successfully
,I/wpa_supplicant(  986): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  986): p2p0: P2P: Reject scan trigger since one is already pending
,D/io.jxcore.node.ConnectionHelper( 3227): disconnectOutgoingConnection: Trying to close connection to peer with ID 00:F4:6F:30:E0:6C
E/io.jxcore.node.ConnectionHelper( 3227): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:F4:6F:30:E0:6C
D/io.jxcore.node.ConnectionHelper( 3227): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3227): disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:F4:6F:30:E0:6C), either no such connection or failed to close the connection
,I/jxcore-log( 3227): 2016-01-12T12:24:24.739Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:24:24.745Z SendDataConnector.js: Connect (retry count 4) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3227): 
I/jxcore-log( 3227): 2016-01-12T12:24:24.748Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:24:24.751Z SendDataConnector.js: do connect now
I/jxcore-log( 3227): 
,I/io.jxcore.node.ConnectionHelper( 3227): connect: Trying to connect to peer with ID 00:F4:6F:30:E0:6C
D/io.jxcore.node.ConnectionHelper( 3227): hasConnection: No connection with peer with ID 00:F4:6F:30:E0:6C
W/io.jxcore.node.ConnectionHelper( 3227): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3227): connect: [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3227): connect: Trying to start connecting to null in address 00:F4:6F:30:E0:6C
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3227): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3227): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3227): onConnecting: null 00:F4:6F:30:E0:6C
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3227): connect: Started connecting to null in address 00:F4:6F:30:E0:6C
I/io.jxcore.node.ConnectionHelper( 3227): connect: Connection process successfully started (peer ID: 00:F4:6F:30:E0:6C)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3227): Trying to connect to peer with address 00:F4:6F:30:E0:6C (thread ID: 334)
W/BluetoothAdapter( 3227): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2080): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2080): info:x10
,D/        ( 2080): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,E/BluetoothRemoteDevices( 2080): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2080): process_service_search_attr_rsp
,E/bt-btif ( 2080): DISCOVERY_COMP_EVT slot id:16, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2080): invalid rfc slot id: 16
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3227): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 334)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3227): Maximum number of allowed retries (0) reached, giving up... (thread ID: 334)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3227): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3227): Exiting thread (thread ID: 334)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3227): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C]
I/jxcore-log( 3227): 2016-01-12T12:24:25.938Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C] failed
I/jxcore-log( 3227): 
I/jxcore-log( 3227): 2016-01-12T12:24:25.939Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C] failed
I/jxcore-log( 3227): 
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3227): shutdown (thread ID: 334)
,I/jxcore-log( 3227): oneRoundDownNow
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:24:25.954Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3227): 
D/io.jxcore.node.ConnectionHelper( 3227): disconnectOutgoingConnection: Trying to close connection to peer with ID 00:F4:6F:30:E0:6C
E/io.jxcore.node.ConnectionHelper( 3227): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:F4:6F:30:E0:6C
D/io.jxcore.node.ConnectionHelper( 3227): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3227): disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:F4:6F:30:E0:6C), either no such connection or failed to close the connection
I/jxcore-log( 3227): 2016-01-12T12:24:25.957Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3227): 
I/jxcore-log( 3227): ---- round done--------
I/jxcore-log( 3227): 
I/jxcore-log( 3227): ---- gotta redo : 00:F4:6F:30:E0:6C, try count now: 1
I/jxcore-log( 3227): 
I/jxcore-log( 3227): startWithNextDevice
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): do fake peer & start
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): Connect to fake peer: 58:3F:54:73:64:C0
I/jxcore-log( 3227): 
I/jxcore-log( 3227): 2016-01-12T12:24:25.972Z SendDataConnector.js: Start called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3227): 
I/jxcore-log( 3227): 2016-01-12T12:24:25.973Z SendDataConnector.js: doConnect called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3227): 
I/jxcore-log( 3227): 2016-01-12T12:24:25.973Z SendDataConnector.js: do connect now
I/jxcore-log( 3227): 
I/io.jxcore.node.ConnectionHelper( 3227): connect: Trying to connect to peer with ID 58:3F:54:73:64:C0
D/io.jxcore.node.ConnectionHelper( 3227): hasConnection: No connection with peer with ID 58:3F:54:73:64:C0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3227): connect: [58:3F:54:73:64:C0 G3-1]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3227): connect: Trying to start connecting to G3-1 in address 58:3F:54:73:64:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3227): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3227): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3227): onConnecting: G3-1 58:3F:54:73:64:C0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3227): connect: Started connecting to G3-1 in address 58:3F:54:73:64:C0
I/io.jxcore.node.ConnectionHelper( 3227): connect: Connection process successfully started (peer ID: 58:3F:54:73:64:C0)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3227): setInsecureRfcommSocketPort: Will use port 1 when trying to connect
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3227): Trying to connect to peer with address 58:3F:54:73:64:C0 (thread ID: 336)
W/BluetoothAdapter( 3227): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2080): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2080): info:x10
,D/        ( 2080): remote version info [58:3f:54:73:64:c0]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1388): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1388): Bluetooth Device Name: G3-1
,E/bt-btm  ( 2080): tBTM_SEC_DEV:0xa41d9414 rs_disc_pending=1
W/bt-btif ( 2080): bta_dm_check_av:0
,W/bt-btif ( 2080): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 2080): process_service_search_attr_rsp
,W/bt-btif ( 2080): new conn_srvc id:26, app_id:1
W/bt-btif ( 2080): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2080): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3227): onSocketConnected: [58:3F:54:73:64:C0 G3-1],
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3227): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 336)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3227): onBytesWritten: 66 bytes successfully written (thread ID: 337)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3227): Outgoing connection initialized (*handshake* thread ID: 337)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3227): Exiting thread (thread ID: 336)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3227): Entering thread (ID: 337)
,E/bt-btm  ( 2080): tBTM_SEC_DEV:0xa41d9414 rs_disc_pending=0
W/bt-btif ( 2080): bta_dm_check_av:0
,W/bt-btif ( 2080): btif_dm_cback : unhandled event (14)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3227): onBytesRead: Read 63 bytes successfully (thread ID: 337)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3227): Handshake succeeded with [58:3F:54:73:64:C0 G3-1]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3227): onHandshakeSucceeded: [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3227): Exiting thread (ID: 337)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3227): onConnected: [58:3F:54:73:64:C0 G3-1]
I/io.jxcore.node.ConnectionHelper( 3227): onConnected: Outgoing connection to peer [58:3F:54:73:64:C0 G3-1]
,D/io.jxcore.node.ConnectionHelper( 3227): hasConnection: No connection with peer with ID 58:3F:54:73:64:C0
W/io.jxcore.node.ConnectionHelper( 3227): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 G3-1] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 3227): onConnected: Outgoing socket thread, for peer [58:3F:54:73:64:C0 G3-1], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3227): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 3227): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 3227): Entering thread (ID: 338)
,D/io.jxcore.node.OutgoingSocketThread( 3227): Server socket local port: 59284
I/io.jxcore.node.OutgoingSocketThread( 3227): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3227): onListeningForIncomingConnections: Outgoing connection is using port 59284 (peer ID: 58:3F:54:73:64:C0)
I/jxcore-log( 3227): 2016-01-12T12:24:29.954Z SendDataConnector.js: CLIENT connected to 59284, error: null
I/jxcore-log( 3227): 
I/jxcore-log( 3227): 2016-01-12T12:24:29.955Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3227): 
,I/io.jxcore.node.OutgoingSocketThread( 3227): Incoming data from address: /127.0.0.1, port: 59284
D/io.jxcore.node.OutgoingSocketThread( 3227): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3227): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3227): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3227): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3227): Exiting thread (ID: 338)
,I/jxcore-log( 3227): 2016-01-12T12:24:29.958Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3227): 
,D/io.jxcore.node.StreamCopyingThread( 3227): Entering thread (ID: 340, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3227): Entering thread (ID: 339, name: Sender)
,E/bt-btm  ( 2080): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2080): aclStateChangeCallback: Device is NULL
,D/        ( 2080): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:72020
,I/jxcore-log( 3227): 2016-01-12T12:24:31.000Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3227): 
,D/        ( 2080): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:62826
,I/jxcore-log( 3227): 2016-01-12T12:24:31.086Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3227): 
,D/        ( 2080): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:52926
,I/jxcore-log( 3227): 2016-01-12T12:24:31.143Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3227): 
,D/        ( 2080): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:42036
,I/jxcore-log( 3227): 2016-01-12T12:24:31.231Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3227): 
,D/        ( 2080): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:33126
,I/jxcore-log( 3227): 2016-01-12T12:24:31.352Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3227): 
,D/        ( 2080): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:23226
,I/jxcore-log( 3227): 2016-01-12T12:24:31.411Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3227): 
,D/        ( 2080): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:12336
,I/jxcore-log( 3227): 2016-01-12T12:24:31.549Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3227): 
,D/        ( 2080): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:1446
,I/jxcore-log( 3227): 2016-01-12T12:24:31.640Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:24:31.684Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:24:31.734Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3227): 
I/jxcore-log( 3227): 2016-01-12T12:24:31.735Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3227): 
I/jxcore-log( 3227): oneRoundDownNow
I/jxcore-log( 3227): 
I/jxcore-log( 3227): 2016-01-12T12:24:31.736Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3227): 
I/jxcore-log( 3227): 2016-01-12T12:24:31.737Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3227): 
D/io.jxcore.node.ConnectionHelper( 3227): disconnectOutgoingConnection: Trying to close connection to peer with ID 58:3F:54:73:64:C0
,I/io.jxcore.node.ConnectionHelper( 3227): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 58:3F:54:73:64:C0
,I/io.jxcore.node.OutgoingSocketThread( 3227): close
D/io.jxcore.node.OutgoingSocketThread( 3227): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3227): doStop: Thread ID: 340
D/io.jxcore.node.OutgoingSocketThread( 3227): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3227): doStop: Thread ID: 339
D/io.jxcore.node.OutgoingSocketThread( 3227): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 3227): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3227): Either failed to read from the output stream or write to the input stream (thread ID: 339, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3227): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3227): onDisconnected: Outgoing connection, peer [58:3F:54:73:64:C0 G3-1] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 3227): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 3227): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3227): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3227): Either failed to read from the output stream or write to the input stream (thread ID: 340, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 3227): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3227): onDisconnected: Outgoing connection, peer [58:3F:54:73:64:C0 G3-1] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3227): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3227): disconnectOutgoingConnection: Successfully disconnected (peer ID: 58:3F:54:73:64:C0
,E/io.jxcore.node.ConnectionHelper( 3227): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 58:3F:54:73:64:C0
D/io.jxcore.node.ConnectionHelper( 3227): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3227): Exiting thread (ID: 339, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 3227): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 58:3F:54:73:64:C0
,D/io.jxcore.node.ConnectionHelper( 3227): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3227): Exiting thread (ID: 340, name: Receiver)
,I/jxcore-log( 3227): 2016-01-12T12:24:31.785Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:3F:54:73:64:C0
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): ---- round done--------
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): startWithNextDevice
I/jxcore-log( 3227): 
I/jxcore-log( 3227): do fake peer & start
I/jxcore-log( 3227): 
I/jxcore-log( 3227): Connect to fake peer: 7C:F9:0E:34:8A:A0
I/jxcore-log( 3227): 
I/jxcore-log( 3227): 2016-01-12T12:24:31.786Z SendDataConnector.js: Start called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3227): 
I/jxcore-log( 3227): 2016-01-12T12:24:31.787Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:24:31.787Z SendDataConnector.js: do connect now
I/jxcore-log( 3227): 
I/io.jxcore.node.ConnectionHelper( 3227): connect: Trying to connect to peer with ID 7C:F9:0E:34:8A:A0
D/io.jxcore.node.ConnectionHelper( 3227): hasConnection: No connection with peer with ID 7C:F9:0E:34:8A:A0
W/io.jxcore.node.ConnectionHelper( 3227): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3227): connect: [7C:F9:0E:34:8A:A0 7C:F9:0E:34:8A:A0]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3227): connect: Trying to start connecting to null in address 7C:F9:0E:34:8A:A0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3227): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3227): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3227): onConnecting: null 7C:F9:0E:34:8A:A0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3227): connect: Started connecting to null in address 7C:F9:0E:34:8A:A0
I/io.jxcore.node.ConnectionHelper( 3227): connect: Connection process successfully started (peer ID: 7C:F9:0E:34:8A:A0)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3227): Trying to connect to peer with address 7C:F9:0E:34:8A:A0 (thread ID: 341)
W/BluetoothAdapter( 3227): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2080): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2080): bta_jv_rfc_port_to_cb(port_handle:0xd):jv handle:0x0 not FOUND
,D/btif_config_util( 2080): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2080): tBTM_SEC_DEV:0xa41d9414 rs_disc_pending=1
W/bt-btif ( 2080): bta_dm_check_av:0
W/bt-btif ( 2080): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant(  986): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 2080): tBTM_SEC_DEV:0xa41d9414 rs_disc_pending=0
W/bt-btif ( 2080): bta_dm_check_av:0
,W/bt-btif ( 2080): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2080): info:x10
,D/        ( 2080): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,E/BluetoothRemoteDevices( 2080): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant(  986): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 2080): tBTM_SEC_DEV:0xa41d9414 rs_disc_pending=1
W/bt-btif ( 2080): bta_dm_check_av:0
,W/bt-btif ( 2080): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant(  986): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  986): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3227): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3227): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3227): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,E/bt-btm  ( 2080): tBTM_SEC_DEV:0xa41d97a4 rs_disc_pending=0
W/bt-btif ( 2080): bta_dm_check_av:0
,W/bt-btif ( 2080): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 2080): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2080): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 1
E/bt-btif ( 2080): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2080): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2080): Entering PendingCommandState State
,E/bt-btm  ( 2080): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2080): onReceive
,I/BTConnectionReceiver( 1388): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1388): Bluetooth Device Name: G3-1
,I/BluetoothBondStateMachine( 2080): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 0
,D/BluetoothAdapterProperties( 2080): Failed to remove device: 7C:F9:0E:34:8A:A0
,I/BluetoothBondStateMachine( 2080): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2080): StableState(): Entering Off State
,W/bt-btif ( 2080): new conn_srvc id:26, app_id:1
W/bt-btif ( 2080): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2080): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3227): onSocketConnected: [7C:F9:0E:34:8A:A0 7C:F9:0E:34:8A:A0]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3227): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 341)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3227): onBytesWritten: 66 bytes successfully written (thread ID: 342)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3227): Outgoing connection initialized (*handshake* thread ID: 342)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3227): Exiting thread (thread ID: 341)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3227): Entering thread (ID: 342)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3227): onBytesRead: Read 63 bytes successfully (thread ID: 342)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3227): Handshake succeeded with [7C:F9:0E:34:8A:A0 S5-1]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3227): onHandshakeSucceeded: [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3227): Exiting thread (ID: 342)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3227): onConnected: [7C:F9:0E:34:8A:A0 S5-1]
I/io.jxcore.node.ConnectionHelper( 3227): onConnected: Outgoing connection to peer [7C:F9:0E:34:8A:A0 S5-1]
,D/io.jxcore.node.ConnectionHelper( 3227): hasConnection: No connection with peer with ID 7C:F9:0E:34:8A:A0
D/io.jxcore.node.ConnectionHelper( 3227): notifyPeerAvailability: Peer [7C:F9:0E:34:8A:A0 S5-1] is available
,I/io.jxcore.node.ConnectionHelper( 3227): onConnected: Outgoing socket thread, for peer [7C:F9:0E:34:8A:A0 S5-1], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3227): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 3227): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 3227): Entering thread (ID: 343)
,D/io.jxcore.node.OutgoingSocketThread( 3227): Server socket local port: 43639
,I/io.jxcore.node.OutgoingSocketThread( 3227): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3227): onListeningForIncomingConnections: Outgoing connection is using port 43639 (peer ID: 7C:F9:0E:34:8A:A0)
I/jxcore-log( 3227): 2016-01-12T12:24:36.435Z SendDataConnector.js: CLIENT connected to 43639, error: null
I/jxcore-log( 3227): 
I/jxcore-log( 3227): 2016-01-12T12:24:36.436Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3227): 
,I/io.jxcore.node.OutgoingSocketThread( 3227): Incoming data from address: /127.0.0.1, port: 43639
D/io.jxcore.node.OutgoingSocketThread( 3227): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3227): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3227): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3227): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3227): Exiting thread (ID: 343)
,D/io.jxcore.node.StreamCopyingThread( 3227): Entering thread (ID: 345, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3227): Entering thread (ID: 344, name: Sender)
,I/jxcore-log( 3227): 2016-01-12T12:24:36.459Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3227): 
,I/wpa_supplicant(  986): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  986): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/WifiP2pManager( 3227): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3227): Service request added successfully
,I/wpa_supplicant(  986): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  986): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  986): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3227): Service discovery started successfully
,D/        ( 2080): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:33300
,I/jxcore-log( 3227): 2016-01-12T12:24:38.531Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:24:38.613Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3227): 
,D/        ( 2080): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:19440
,I/jxcore-log( 3227): 2016-01-12T12:24:38.714Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:24:39.802Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3227): 
,D/btif_config_util( 2080): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3227): 2016-01-12T12:24:41.023Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:24:41.666Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:24:42.626Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:24:43.334Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3227): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3227): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3227): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3227): onServiceDiscovered: [58:3F:54:73:64:C0 G3-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onPeerDiscovered: [58:3F:54:73:64:C0 G3-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 G3-1]
,I/io.jxcore.node.ConnectionHelper( 3227): onPeerDiscovered: [58:3F:54:73:64:C0 G3-1], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper( 3227): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 G3-1] already in the list, will not add again
,I/jxcore-log( 3227): 2016-01-12T12:24:44.049Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:24:44.163Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3227): 
I/jxcore-log( 3227): 2016-01-12T12:24:44.164Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3227): 
I/jxcore-log( 3227): oneRoundDownNow
I/jxcore-log( 3227): 
I/jxcore-log( 3227): 2016-01-12T12:24:44.165Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3227): 
I/jxcore-log( 3227): 2016-01-12T12:24:44.165Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3227): 
D/io.jxcore.node.ConnectionHelper( 3227): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:34:8A:A0
,I/io.jxcore.node.ConnectionHelper( 3227): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 7C:F9:0E:34:8A:A0
I/io.jxcore.node.OutgoingSocketThread( 3227): close
D/io.jxcore.node.OutgoingSocketThread( 3227): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3227): doStop: Thread ID: 345
,D/io.jxcore.node.OutgoingSocketThread( 3227): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3227): doStop: Thread ID: 344
D/io.jxcore.node.OutgoingSocketThread( 3227): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 3227): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3227): Either failed to read from the output stream or write to the input stream (thread ID: 344, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3227): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3227): onDisconnected: Outgoing connection, peer [7C:F9:0E:34:8A:A0 S5-1] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 3227): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 3227): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3227): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3227): Either failed to read from the output stream or write to the input stream (thread ID: 345, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 3227): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3227): onDisconnected: Outgoing connection, peer [7C:F9:0E:34:8A:A0 S5-1] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3227): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,I/io.jxcore.node.ConnectionHelper( 3227): disconnectOutgoingConnection: Successfully disconnected (peer ID: 7C:F9:0E:34:8A:A0
,E/io.jxcore.node.ConnectionHelper( 3227): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:34:8A:A0
D/io.jxcore.node.ConnectionHelper( 3227): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3227): Exiting thread (ID: 344, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 3227): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:34:8A:A0
D/io.jxcore.node.ConnectionHelper( 3227): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3227): Exiting thread (ID: 345, name: Receiver)
,I/jxcore-log( 3227): 2016-01-12T12:24:44.216Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3227): 
I/jxcore-log( 3227): ---- round done--------
I/jxcore-log( 3227): 
I/jxcore-log( 3227): startWithNextDevice
I/jxcore-log( 3227): 
I/jxcore-log( 3227): do fake peer & start
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): Connect to fake peer: 7C:F9:0E:37:96:AB
,I/jxcore-log( 3227): 
I/jxcore-log( 3227): 2016-01-12T12:24:44.224Z SendDataConnector.js: Start called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3227): 
I/jxcore-log( 3227): 2016-01-12T12:24:44.224Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3227): 
I/jxcore-log( 3227): 2016-01-12T12:24:44.225Z SendDataConnector.js: do connect now
I/jxcore-log( 3227): 
I/io.jxcore.node.ConnectionHelper( 3227): connect: Trying to connect to peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 3227): hasConnection: No connection with peer with ID 7C:F9:0E:37:96:AB
W/io.jxcore.node.ConnectionHelper( 3227): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3227): connect: [7C:F9:0E:37:96:AB 7C:F9:0E:37:96:AB]
W/bt-btif ( 2080): bta_jv_rfc_port_to_cb(port_handle:0xe):jv handle:0x0 not FOUND
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3227): connect: Trying to start connecting to null in address 7C:F9:0E:37:96:AB
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3227): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3227): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3227): onConnecting: null 7C:F9:0E:37:96:AB
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3227): connect: Started connecting to null in address 7C:F9:0E:37:96:AB
I/io.jxcore.node.ConnectionHelper( 3227): connect: Connection process successfully started (peer ID: 7C:F9:0E:37:96:AB)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3227): Trying to connect to peer with address 7C:F9:0E:37:96:AB (thread ID: 346)
W/BluetoothAdapter( 3227): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2080): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2080): tBTM_SEC_DEV:0xa41d97a4 rs_disc_pending=1
W/bt-btif ( 2080): bta_dm_check_av:0
,W/bt-btif ( 2080): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2080): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2080): onReceive
,I/BTConnectionReceiver( 1388): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1388): Bluetooth Device Name: S5-1
,I/wpa_supplicant(  986): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  986): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3227): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3227): restart: Restarting...
,D/WifiP2pManager( 3227): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3227): Service request added successfully
,I/wpa_supplicant(  986): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  986): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3227): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
,I/wpa_supplicant(  986): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  986): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3227): Service discovery started successfully
,I/wpa_supplicant(  986): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3227): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3227): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3227): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3227): onServiceDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/io.jxcore.node.ConnectionHelper( 3227): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
W/io.jxcore.node.ConnectionHelper( 3227): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3227): Connection timeout
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3227): onConnectionTimeout: [7C:F9:0E:37:96:AB 7C:F9:0E:37:96:AB]
I/jxcore-log( 3227): 2016-01-12T12:24:59.245Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [7C:F9:0E:37:96:AB 7C:F9:0E:37:96:AB] timed out
I/jxcore-log( 3227): 
I/jxcore-log( 3227): 2016-01-12T12:24:59.246Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [7C:F9:0E:37:96:AB 7C:F9:0E:37:96:AB] timed out
I/jxcore-log( 3227): 
I/jxcore-log( 3227): 2016-01-12T12:24:59.247Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3227): 
,I/ActivityManager(  735): Killing 1994:com.google.android.calendar/u0a31 (adj 15): empty #17
,W/libprocessgroup(  735): failed to open /acct/uid_10031/pid_1994/cgroup.procs: No such file or directory
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3227): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"G4-1","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3227): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3227): onServiceDiscovered: [F8:95:C7:87:3C:51 G4-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onPeerDiscovered: [F8:95:C7:87:3C:51 G4-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 G4-1]
I/io.jxcore.node.ConnectionHelper( 3227): onPeerDiscovered: [F8:95:C7:87:3C:51 G4-1], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3227): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 G4-1] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3227): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"Thali Test (Galaxy A5)","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3227): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3227): onServiceDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)]
I/io.jxcore.node.ConnectionHelper( 3227): onPeerDiscovered: [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
D/io.jxcore.node.ConnectionHelper( 3227): notifyPeerAvailability: Peer [7C:F9:0E:51:18:22 Thali Test (Galaxy A5)] is available
,I/jxcore-log( 3227): 2016-01-12T12:25:04.248Z SendDataConnector.js: re-try now : 7C:F9:0E:37:96:AB
I/jxcore-log( 3227): 
I/jxcore-log( 3227): 2016-01-12T12:25:04.249Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): timeout now
I/jxcore-log( 3227): 
I/jxcore-log( 3227): weAreDoneNow, resultArray.length: 3
I/jxcore-log( 3227): 
I/jxcore-log( 3227): sendReportNow
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): done, now sending data to server
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:25:07.737Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3227): 
D/io.jxcore.node.ConnectionHelper( 3227): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:37:96:AB
E/io.jxcore.node.ConnectionHelper( 3227): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 3227): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3227): disconnectOutgoingConnection: Failed to disconnect (peer ID: 7C:F9:0E:37:96:AB), either no such connection or failed to close the connection
I/jxcore-log( 3227): 2016-01-12T12:25:07.737Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3227): 
,D/io.jxcore.node.ConnectionHelper( 3227): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:37:96:AB
E/io.jxcore.node.ConnectionHelper( 3227): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 3227): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3227): disconnectOutgoingConnection: Failed to disconnect (peer ID: 7C:F9:0E:37:96:AB), either no such connection or failed to close the connection
I/jxcore-log( 3227): 2016-01-12T12:25:09.253Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3227): 
I/jxcore-log( 3227): 2016-01-12T12:25:09.254Z SendDataConnector.js: Connect (retry count 1) to peer 7C:F9:0E:37:96:AB with availability status: true
I/jxcore-log( 3227): 
I/jxcore-log( 3227): 2016-01-12T12:25:09.254Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3227): 
I/jxcore-log( 3227): 2016-01-12T12:25:09.255Z SendDataConnector.js: do connect now
I/jxcore-log( 3227): 
,I/io.jxcore.node.ConnectionHelper( 3227): connect: Trying to connect to peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 3227): hasConnection: No connection with peer with ID 7C:F9:0E:37:96:AB
W/io.jxcore.node.ConnectionHelper( 3227): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3227): connect: [7C:F9:0E:37:96:AB 7C:F9:0E:37:96:AB]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3227): connect: Trying to start connecting to null in address 7C:F9:0E:37:96:AB
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3227): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3227): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3227): onConnecting: null 7C:F9:0E:37:96:AB
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3227): connect: Started connecting to null in address 7C:F9:0E:37:96:AB
I/io.jxcore.node.ConnectionHelper( 3227): connect: Connection process successfully started (peer ID: 7C:F9:0E:37:96:AB)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3227): Trying to connect to peer with address 7C:F9:0E:37:96:AB (thread ID: 348)
W/BluetoothAdapter( 3227): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2080): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2080): SDP - Rcvd conn cnf with error: 0x8  CID 0x44
E/bt-btif ( 2080): DISCOVERY_COMP_EVT slot id:19, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2080): invalid rfc slot id: 19
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3227): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 346)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3227): Maximum number of allowed retries (0) reached, giving up... (thread ID: 346)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3227): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3227): Exiting thread (thread ID: 346)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3227): shutdown (thread ID: 346)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3227): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [7C:F9:0E:37:96:AB 7C:F9:0E:37:96:AB]
,I/jxcore-log( 3227): 2016-01-12T12:25:17.349Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [7C:F9:0E:37:96:AB 7C:F9:0E:37:96:AB] failed
I/jxcore-log( 3227): 
I/jxcore-log( 3227): 2016-01-12T12:25:17.356Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [7C:F9:0E:37:96:AB 7C:F9:0E:37:96:AB] failed
I/jxcore-log( 3227): 
I/jxcore-log( 3227): 2016-01-12T12:25:17.357Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3227): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3227): setInsecureRfcommSocketPort: Will use port 1 when trying to connect
,I/jxcore-log( 3227): 2016-01-12T12:25:22.357Z SendDataConnector.js: re-try now : 7C:F9:0E:37:96:AB
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:25:22.358Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3227): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3227): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3227): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3227): setState: RESTARTING
,I/wpa_supplicant(  986): P2P-FIND-STOPPED 
,I/wpa_supplicant(  986): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant(  986): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant(  986): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant(  986): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant(  986): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant(  986): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3227): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3227): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3227): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3227): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3227): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3227): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3227): onP2pDeviceListChanged: 0 device(s) discovered
,D/io.jxcore.node.ConnectionHelper( 3227): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:37:96:AB
E/io.jxcore.node.ConnectionHelper( 3227): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 3227): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3227): disconnectOutgoingConnection: Failed to disconnect (peer ID: 7C:F9:0E:37:96:AB), either no such connection or failed to close the connection
I/jxcore-log( 3227): 2016-01-12T12:25:27.363Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3227): 
I/jxcore-log( 3227): 2016-01-12T12:25:27.364Z SendDataConnector.js: Connect (retry count 2) to peer 7C:F9:0E:37:96:AB with availability status: true
I/jxcore-log( 3227): 
I/jxcore-log( 3227): 2016-01-12T12:25:27.366Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3227): 
I/jxcore-log( 3227): 2016-01-12T12:25:27.366Z SendDataConnector.js: do connect now
I/jxcore-log( 3227): 
I/io.jxcore.node.ConnectionHelper( 3227): connect: Trying to connect to peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 3227): hasConnection: No connection with peer with ID 7C:F9:0E:37:96:AB
W/io.jxcore.node.ConnectionHelper( 3227): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3227): connect: [7C:F9:0E:37:96:AB 7C:F9:0E:37:96:AB]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3227): connect: Trying to start connecting to null in address 7C:F9:0E:37:96:AB
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3227): setInsecureRfcommSocketPort: Using port 1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3227): setMaxNumberOfRetries: 0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3227): onConnecting: null 7C:F9:0E:37:96:AB
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3227): connect: Started connecting to null in address 7C:F9:0E:37:96:AB
I/io.jxcore.node.ConnectionHelper( 3227): connect: Connection process successfully started (peer ID: 7C:F9:0E:37:96:AB)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3227): Trying to connect to peer with address 7C:F9:0E:37:96:AB (thread ID: 350)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3227): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
,W/BluetoothAdapter( 3227): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2080): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/jxcore-log( 3227): teardown
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): testSendData stopped
I/jxcore-log( 3227): 
I/io.jxcore.node.ConnectionHelper( 3227): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3227): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3227): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3227): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3227): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3227): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3227): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3227): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3227): setState: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3227): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3227): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3227): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3227): release: No more listeners, de-initializing...
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3227): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3227): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3227): setState: NOT_STARTED
I/jxcore-log( 3227): StopBroadcasting went ok
I/jxcore-log( 3227): 
,I/jxcore-log( 3227): 2016-01-12T12:25:27.812Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
I/jxcore-log( 3227): 
I/chromium( 3227): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/io.jxcore.node.ConnectionHelper( 3227): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3227): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3227): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3227): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 3227): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 3227): ****TEST TOOK:  ms ****
I/jxcore-log( 3227): 
I/jxcore-log( 3227): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3227): 
,D/AndroidRuntime( 3717): 
D/AndroidRuntime( 3717): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 3717): CheckJNI is OFF
,D/AndroidRuntime( 3717): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  735): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  735): Killing 3227:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
,I/WindowState(  735): WIN DEATH: Window{228225a u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  735): Client connection lost with reason: 4
,E/bt-btif ( 2080): SOCK_THREAD_FD_RD signaled when rfc is not connected,                                       slot id:21, channel:1
E/bt-btif ( 2080): SOCK_THREAD_FD_RD signaled when rfc is not connected,                                       slot id:20, channel:-1
,W/PackageSettings(  735): Skipping PackageSetting{38f56828 com.example.hello/10278} due to missing metadata
,I/ActivityManager(  735):   Force finishing activity ActivityRecord{274eb0c6 u0 com.test.thalitest/.MainActivity t214}
,W/ActivityManager(  735): Spurious death for ProcessRecord{2960fda 3227:com.test.thalitest/u0a270}, curProc for 3227: null
,I/ActivityManager(  735): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
I/ActivityManager(  735):   Force finishing activity ActivityRecord{274eb0c6 u0 com.test.thalitest/.MainActivity t214 f}
W/ActivityManager(  735): Duplicate finish request for ActivityRecord{274eb0c6 u0 com.test.thalitest/.MainActivity t214 f}
,I/art     ( 1260): Explicit concurrent mark sweep GC freed 3937(293KB) AllocSpace objects, 1(126KB) LOS objects, 23% free, 25MB/33MB, paused 225us total 15.818ms
,I/art     ( 1388): Explicit concurrent mark sweep GC freed 30273(1470KB) AllocSpace objects, 5(80KB) LOS objects, 24% free, 19MB/25MB, paused 307us total 23.867ms
,I/art     ( 1617): Explicit concurrent mark sweep GC freed 11988(573KB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 22MB/30MB, paused 629us total 43.676ms,
,I/InputReader(  735): Reconfiguring input devices.  changes=0x00000010
,I/Keyboard.Facilitator( 1098): resetDictionaries() : en_US
,W/GeofencerStateMachine( 1569): Ignoring removeGeofence because network location is disabled.
,D/VoicemailCleanupService( 1355): Cleaning up data for package: com.test.thalitest
,I/Keyboard.Facilitator.DecoderInitializer( 1098): run()
,I/Decoder ( 1098): createOrResetDecoder
,I/art     (  735): Explicit concurrent mark sweep GC freed 44490(2MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 1.652ms total 65.915ms
I/art     (  735): WaitForGcToComplete blocked for 13.302ms for cause Explicit
,I/UpdateIcingCorporaServi( 1388): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,W/Launcher( 1260): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@20621c7d new=com.google.android.velvet.VelvetApplication@20621c7d
,I/Adreno-EGL(  948): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
I/OpenGLRenderer(  948): Initialized EGL, version 1.4
,I/ActivityManager(  735): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3757 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,D/OpenGLRenderer(  948): Enabling debug mode 0
,I/ConfigService( 1569): onCreate
,W/ContextImpl( 3757): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
,I/UpdateIcingCorporaServi( 1388): UpdateCorporaTask done [took 118 ms] updated apps [took 118 ms] 
,D/BackupManagerService(  735): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  735): Receieved: android.intent.action.PACKAGE_REMOVED
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1098): run()
,D/TaskPersister(  735): removeObsoleteFile: deleting file=214_task.xml
,W/InputMethodManagerService(  735): Focus gain on non-focused client com.android.internal.view.IInputMethodClient$Stub$Proxy@209011fd (uid=10034 pid=948)
D/PackageBroadcastService( 1617): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1617): Clearing selected account for com.test.thalitest
,I/art     (  735): Explicit concurrent mark sweep GC freed 7389(342KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 28MB/42MB, paused 1.296ms total 139.973ms
,D/ChimeraCfgMgr( 1617): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1617): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1617): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1617): Module APK com.google.android.play.games already loaded
,I/LocationSettingsChecker( 1617): Removing dialog suppression flag for package com.test.thalitest
,E/NetworkScheduler.SchedulerReceiver( 1569): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1569): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1098): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1098): run()
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1098): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1098): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1098): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1098): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1098): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1098): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1098): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1098): run()
,I/Keyboard.Facilitator.RecurringTaskScheduler( 1098): run()
,I/StatsUtilsManager( 1098): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1098): shouldRecordStats() = Too Soon
,D/gH_CompatibleDatabase( 1617): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1617): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 1617): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1617): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/gH_CompatibleDatabase( 1617): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1617): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/gH_CompatibleDatabase( 1617): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/gH_CompatibleDatabase( 1617): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1617): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 1617): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1617): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
,D/gH_CompatibleDatabase( 1617): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
,D/gH_CompatibleDatabase( 1617): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,D/AndroidRuntime( 3717): Shutting down VM
,I/ActivityManager(  735): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3792 uid=10039 gids={50039, 9997} abi=armeabi-v7a
,W/BaseAppContext( 1617): Using Auth Proxy for data requests.
,W/BaseAppContext( 1617): Using Auth Proxy for data requests.
,I/GMPM-SVC( 1617): App measurement is starting up, version: 8489
I/GMPM-SVC( 1617): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,I/Launcher( 1260): Deferring update until onResume
,I/Icing   ( 1617): doRemovePackageData com.test.thalitest
,W/ResourcesManager( 1260): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 1260): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  735): Killing 2057:com.google.android.deskclock/u0a38 (adj 15): empty #17
,I/Launcher( 1260): Deferring update until onResume
,I/ActivityManager(  735): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3819 uid=10007 gids={50007, 9997, 1028, 1015, 1023} abi=armeabi-v7a
W/libprocessgroup(  735): failed to open /acct/uid_10038/pid_2057/cgroup.procs: No such file or directory
,I/ActivityManager(  735): Killing 2016:com.android.providers.calendar/u0a2 (adj 15): empty #17
,I/art     ( 1569): Explicit concurrent mark sweep GC freed 99427(5MB) AllocSpace objects, 24(384KB) LOS objects, 39% free, 23MB/39MB, paused 1.010ms total 48.917ms
,E/DataBuffer( 1569): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3a3ef9a1)
,E/DataBuffer( 1569): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@306587c6)
E/DataBuffer( 1569): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@13bd5387)
E/DataBuffer( 1569): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3879e2b4)
,E/DataBuffer( 1569): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3a308edd)
,E/DataBuffer( 1569): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2e225a52)
,W/libprocessgroup(  735): failed to open /acct/uid_10002/pid_2016/cgroup.procs: No such file or directory
,D/ExternalStorage( 3819): After updating volumes, found 1 active roots
,W/ResourcesManager( 3141): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 3141): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/Documents( 3792): Update found 7 roots in 228ms
,D/Documents( 3792): Update found 7 roots in 65ms

```
