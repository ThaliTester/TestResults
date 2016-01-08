#### Test 55467363832a26e_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
I/GAv4    ( 3121): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3121):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3121):   adb logcat -s GAv4
W/GAv4    ( 3121): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3121): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3121): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 3121): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
D/Finsky  ( 2575): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
W/ResourcesManager( 3121): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3121): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  733): Killing 2544:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
V/JNIHelp ( 3121): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/libprocessgroup(  733): failed to open /acct/uid_10069/pid_2544/cgroup.procs: No such file or directory
W/System  ( 3121): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3121): Installed default security provider GmsCore_OpenSSL
V/GLSActivity( 1568): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 1646): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/Icing   ( 1646): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1646): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/Icing   ( 1646): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
,D/AndroidRuntime( 3190): 
D/AndroidRuntime( 3190): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3190): CheckJNI is OFF
D/AndroidRuntime( 3190): Calling main entry com.android.commands.am.Am
I/ActivityManager(  733): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  733): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3211 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3190): Shutting down VM
V/ActivityManager(  733): Display changed displayId=0
I/WebViewFactory( 3211): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3211): Time to load native libraries: 2 ms (timestamps 96-98)
I/LibraryLoader( 3211): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3211): Binding Chromium to main looper Looper (main, tid 1) {312e09c9}
I/LibraryLoader( 3211): Expected native library version number "",actual native library version number ""
I/chromium( 3211): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/ActivityManager(  733): Killing 2495:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,I/BrowserStartupController( 3211): Initializing chromium process, singleProcess=true
W/art     ( 3211): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3211): ApplicationContext is null in ApplicationStatus
,W/chromium( 3211): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3211): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3211): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3211): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/libprocessgroup(  733): failed to open /acct/uid_10045/pid_2495/cgroup.procs: No such file or directory
,D/BluetoothManagerService(  733): Message: 20
,D/BluetoothManagerService(  733): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2c3582bd:true
,W/art     ( 3211): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3211): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3211): CordovaWebView is running on device made by: LGE
,W/art     ( 3211): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 3211): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3211): Render dirty regions requested: true
,D/Atlas   ( 3211): Validating map...
,W/chromium( 3211): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3211): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3211): Enabling debug mode 0
,W/BindingManager( 3211): Cannot call determinedVisibility() - never saw a connection for the pid: 3211
,W/IInputConnectionWrapper( 3211): showStatusIcon on inactive InputConnection
I/ActivityManager(  733): Displayed com.test.thalitest/.MainActivity: +483ms (total +58s294ms)
,D/JsMessageQueue( 3211): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3211): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257332480
,D/JX-Cordova( 3211): jxcore cordova android initializing
,W/jxcore-log( 3211): Initializing JXcore engine
W/jxcore-log( 3211): JXcore engine is ready
,W/jxcore-log( 3211): Starting JXcore engine
,W/.test.thalitest( 3211): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[8032]" dev="sockfs" ino=8032 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/.test.thalitest( 3211): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 3211): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6572]" dev="sockfs" ino=6572 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3211): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[20603]" dev="sockfs" ino=20603 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3211): Platform android
W/jxcore-log( 3211): 
W/jxcore-log( 3211): Process ARCH arm
W/jxcore-log( 3211): 
,I/jxcore-log( 3211): JXcore Cordova bridge is ready!
I/jxcore-log( 3211): 
,W/jxcore-log( 3211): JXcore engine is started
I/Choreographer( 3211): Skipped 105 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3211): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,V/GLSActivity( 1568): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1568): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  733): Killing 2656:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/libprocessgroup(  733): failed to open /acct/uid_10003/pid_2656/cgroup.procs: No such file or directory
,I/jxcore-log( 3211): Toggling radios to true
I/jxcore-log( 3211): 
,D/BluetoothAdapter( 3211): enable(): BT is already enabled..!
,D/WifiService(  733): New client listening to asynchronous messages
,D/WifiService(  733): setWifiEnabled: true pid=3211, uid=10270
E/WifiService(  733): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3211): Radios toggled,
I/jxcore-log( 3211): 
,I/wpa_supplicant(  988): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  733): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  733): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,E/native  (  733): do suspend true
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 3211): Received device characteristics:
I/jxcore-log( 3211): Bluetooth address: 34:FC:EF:11:AE:67
I/jxcore-log( 3211): Bluetooth name: Nexus 5
I/jxcore-log( 3211): Device name: LGE-Nexus 5
I/jxcore-log( 3211): 
D/CommandListener(  180): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1568): Read error: ssl=0xb3d28e00: I/O error during system call, Connection timed out
I/jxcore-log( 3211): Perf Test app loaded loaded
I/jxcore-log( 3211): 
,I/Choreographer( 3211): Skipped 73 frames!  The application may be doing too much work on its main thread.
I/jxcore-log( 3211): check test folder
I/jxcore-log( 3211): 
I/jxcore-log( 3211): found test : ./testFindPeers.js
I/jxcore-log( 3211): 
,V/NativeCrypto( 1568): SSL shutdown failed: ssl=0xb3d28e00: I/O error during system call, Broken pipe
,D/ConnectivityService(  733): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
,D/ConnectivityService(  733): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): ValidatedState{ when=-1ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): DefaultState{ when=-1ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  733): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): Checking http://clients3.google.com/generate_204 on <unknown ssid>
E/WifiConfigStore(  733): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,I/jxcore-log( 3211): found test : ./testSendData.js
I/jxcore-log( 3211): 
,E/WifiStateMachine(  733): Start Disconnecting Watchdog 1
I/wpa_supplicant(  988): wlan0: CTRL-EVENT-SCAN-STARTED 
,E/native  (  733): do suspend true
,D/CommandListener(  180): Clearing all IP addresses on wlan0
,D/ConnectivityService(  733): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler(  898): CM callback handler got msg 524292
,D/ConnectivityManager.CallbackHandler( 1646): CM callback handler got msg 524292
D/Nat464Xlat(  733): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  733): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  733): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): Disconnected - quitting
D/ConnectivityService(  733): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  733): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1239): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WifiNetworkAgent(  733): NetworkAgent: NetworkAgent channel lost
,I/chromium( 3211): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/wpa_supplicant(  988): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant(  988): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant(  988): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant(  988): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  733): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  733): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  733): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  733): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  180): Setting iface cfg
,E/WifiStateMachine(  733): Start Dhcp Watchdog 2
,E/native  (  733): do suspend false
,E/WifiStateMachine(  733): scanCount==0 - aborting
,I/dhcpcd  ( 3336): version 5.5.6 starting
E/dhcpcd  ( 3336): get_duid: Read-only file system
,I/dhcpcd  ( 3336): wlan0: rebinding lease of 192.168.1.114
,I/dhcpcd  ( 3336): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3336): wlan0: leased 192.168.1.114 for 86400 seconds
,E/native  (  733): do suspend true
,D/ConnectivityService(  733): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  733): Adding iface wlan0 to network 101
,E/WifiStateMachine(  733): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  733): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  733): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  733): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  733): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  733): Setting Dns servers for network 101 to [/192.168.1.1]
D/Nat464Xlat(  733): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  733): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  733): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  733): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  733):    accepting network in place of null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/CSLegacyTypeTracker(  733): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  733): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  733): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  733): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  898): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1646): CM callback handler got msg 524290
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 08 Jan 2016 16:52:59 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452271979674], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452271979658]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): Validated
,D/ConnectivityService(  733): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  733): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  733): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  733): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  733): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 1646): CM callback handler got msg 524290
D/ConnectivityManager.CallbackHandler(  898): CM callback handler got msg 524290
,D/TelephonyNetworkFactory( 1239): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/Nat464Xlat(  733): requiresClat: netType=1, connected=true, hasIPv4Address=true
,D/ConnectivityService(  733): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  898): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 1646): CM callback handler got msg 524295
,D/ConnectivityService(  733): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  733): MasterInitialState.processMessage what=3
,D/ConnectivityService(  733): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  733): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2678): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2678): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 2678): type=WIFI subType= reason=null isConnected=true
,I/SystemUpdateService( 1646): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1646): onCreate
,D/SystemUpdateService( 1646): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1646): active receiver: enabled
,I/SystemUpdateService( 1646): showing system update notification
,I/ValidateNoPeople(  733): skipping global notification
,V/SystemUpdateService( 1646): retry (wakeup: false) in 3599981 ms
,I/ActivityManager(  733): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3402 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ConnectivityService(  733): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,D/SystemUpdateService( 1646): onDestroy
,E/GpsLocationProvider(  733): No APN found to select.
,E/GpsLocationProvider(  733): No APN found to select.
,I/GAv4    ( 3402): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3402):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3402):   adb logcat -s GAv4
,W/GAv4    ( 3402): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3402): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3402): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 3402): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3402): Time to load native libraries: 1 ms (timestamps 7498-7499)
,I/LibraryLoader( 3402): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3402): Binding Chromium to main looper Looper (main, tid 1) {1970d953}
I/LibraryLoader( 3402): Expected native library version number "",actual native library version number ""
,I/chromium( 3402): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3402): Initializing chromium process, singleProcess=true
,W/art     ( 3402): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3402): ApplicationContext is null in ApplicationStatus
,W/chromium( 3402): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3402): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 3402): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3402): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/AudioManagerAndroid( 3402): Requires BLUETOOTH permission
,I/NSApplication( 3402): Starting up...
,I/ActivityManager(  733): Killing 2634:com.android.settings/1000 (adj 15): empty #17
,D/WifiService(  733): Client connection lost with reason: 4
,W/libprocessgroup(  733): failed to open /acct/uid_1000/pid_2634/cgroup.procs: No such file or directory
,V/MusicLeanback( 2678): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1646): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1646): onCreate
,D/SystemUpdateService( 1646): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1646): active receiver: enabled
,I/SystemUpdateService( 1646): showing system update notification
,I/ValidateNoPeople(  733): skipping global notification
,V/SystemUpdateService( 1646): retry (wakeup: false) in 3599966 ms
,D/SystemUpdateService( 1646): onDestroy
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 3211): BLE is supported
I/jxcore-log( 3211): 
,D/ConnectivityService(  733): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  733): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2678): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2678): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1646): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,I/art     (  733): Explicit concurrent mark sweep GC freed 45071(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 27MB/41MB, paused 996us total 71.076ms
,D/SystemUpdateService( 1646): onCreate
,E/GpsLocationProvider(  733): No APN found to select.
,D/SystemUpdateService( 1646): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1646): active receiver: enabled
,I/SystemUpdateService( 1646): showing system update notification
,I/ValidateNoPeople(  733): skipping global notification
V/SystemUpdateService( 1646): retry (wakeup: false) in 3599983 ms
,D/SystemUpdateService( 1646): onDestroy
,D/Finsky  ( 2575): [255] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2575): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/GLSActivity( 1568): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1568): Vacuum at: now=1452271991029 tag=VacuumService
,I/PhenotypeConfigurator( 1568): Scheduling Phenotype for one-off execution 4655 seconds from now (1452271991346)
,D/GetConfigurationSnapshotOperation( 1568): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1568): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1568): Using platform SSLCertificateSocketFactory
,I/ClearcutLoggerApiImpl( 1568): disconnect managed GoogleApiClient
,I/jxcore-log( 3211): Connected to the server!
I/jxcore-log( 3211): 
,I/chromium( 3211): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3211): --- start :testFindPeers.js---
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): testFindPeers created [object Object]
I/jxcore-log( 3211): 
I/jxcore-log( 3211): serverPort is 8876
I/jxcore-log( 3211): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): setDiscoveryMode: Mode set to BLE_AND_WIFI
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3211): start: Peer ID: 34:FC:EF:11:AE:67, peer name: Nexus 5
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3211): bind: Binding a new listener
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3211): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3211): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"Nexus 5","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3211): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3211): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3211): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3211): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3211): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3211): start: OK
I/io.jxcore.node.ConnectionHelper( 3211): start: Using peer discovery mode: BLE_AND_WIFI
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): start: Peer ID: 34:FC:EF:11:AE:67, peer name: Nexus 5
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3211): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3211): bind: Binding a new listener
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3211): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3211): createAdvertiseData: From: Nexus 5 b6a44ad1-d319-4b3a-815d-8b805a47fb51 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3211): 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3211): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 52, -4, -17, 17, -82, 103]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3211): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3211): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"Nexus 5","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3211): start: {"pi":"34:FC:EF:11:AE:67","pn":"Nexus 5","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3211): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"Nexus 5","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3211): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3211): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3211): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): setState: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 3211): start: OK
I/jxcore-log( 3211): StartBroadcasting started ok
I/jxcore-log( 3211): 
I/chromium( 3211): [INFO:CONSOLE(63)] "logCallback --- start :testFindPeers.js---", source: file:///android_asset/www/js/thali_main.js (63)
,I/io.jxcore.node.ConnectionHelper( 3211): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): start: Peer ID: 34:FC:EF:11:AE:67, peer name: Nexus 5
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): startBlePeerDiscovery: Already running
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): startBlePeerDiscovery: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): setState: RUNNING_BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3211): Local service added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3211): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3211): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3211): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3211): onDiscoveryManagerStateChanged: RUNNING_WIFI
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/io.jxcore.node.ConnectionHelper( 3211): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  988): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3211): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3211): onP2pDeviceListChanged: 2 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 3211): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3211): Service request added successfully
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3211): onP2pDeviceListChanged: 3 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3211): Service discovery started successfully
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3211): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3211): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3211): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3211): setState: RESTARTING
,I/wpa_supplicant(  988): P2P-FIND-STOPPED 
,I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3211): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3211): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3211): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3211): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3211): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3211): Start timer timeout, starting now...
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3211): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3211): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3211): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3211): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3211): restart: Restarting...
,D/WifiP2pManager( 3211): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3211): Service request added successfully
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3211): Service discovery started successfully
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3211): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3211): restart: Restarting...
,D/WifiP2pManager( 3211): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3211): Service request added successfully
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3211): Service discovery started successfully
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3211): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3211): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"G3s-1","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3211): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3211): onServiceDiscovered: [F8:95:C7:87:85:54 G3s-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): onPeerDiscovered: [F8:95:C7:87:85:54 G3s-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): modifyListOfDiscoveredPeers: Adding a new peer: [F8:95:C7:87:85:54 G3s-1]
I/io.jxcore.node.ConnectionHelper( 3211): onPeerDiscovered: [F8:95:C7:87:85:54 G3s-1], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
,D/io.jxcore.node.ConnectionHelper( 3211): notifyPeerAvailability: Peer [F8:95:C7:87:85:54 G3s-1] is available
I/jxcore-log( 3211): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:85:54","peerName":"G3s-1","peerAvailable":true}]
I/jxcore-log( 3211): 
I/jxcore-log( 3211): Found peer : F8:95:C7:87:85:54, peerAvailable: true
I/jxcore-log( 3211): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3211): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3211): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3211): setState: RESTARTING
,I/wpa_supplicant(  988): P2P-FIND-STOPPED 
,I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3211): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3211): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3211): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3211): Start timer timeout, starting now...
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3211): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3211): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3211): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3211): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3211): restart: Restarting...
,D/WifiP2pManager( 3211): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3211): Service request added successfully
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3211): Service discovery started successfully
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3211): timeout now
I/jxcore-log( 3211): 
I/jxcore-log( 3211): weAreDoneNow
I/jxcore-log( 3211): 
I/jxcore-log( 3211): done, now sending data to server
I/jxcore-log( 3211): 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3211): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3211): restart: Restarting...
,D/WifiP2pManager( 3211): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3211): Service request added successfully
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3211): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3211): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3211): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3211): onServiceDiscovered: [58:3F:54:73:64:C0 G3-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): onPeerDiscovered: [58:3F:54:73:64:C0 G3-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): modifyListOfDiscoveredPeers: Adding a new peer: [58:3F:54:73:64:C0 G3-1]
I/io.jxcore.node.ConnectionHelper( 3211): onPeerDiscovered: [58:3F:54:73:64:C0 G3-1], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
D/io.jxcore.node.ConnectionHelper( 3211): notifyPeerAvailability: Peer [58:3F:54:73:64:C0 G3-1] is available
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3211): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3211): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3211): onServiceDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): onPeerDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): modifyListOfDiscoveredPeers: Adding a new peer: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
I/io.jxcore.node.ConnectionHelper( 3211): onPeerDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
D/io.jxcore.node.ConnectionHelper( 3211): notifyPeerAvailability: Peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)] is available
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3211): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3211): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"G4-1","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3211): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3211): onServiceDiscovered: [F8:95:C7:87:3C:51 G4-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): onPeerDiscovered: [F8:95:C7:87:3C:51 G4-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): modifyListOfDiscoveredPeers: Adding a new peer: [F8:95:C7:87:3C:51 G4-1]
I/io.jxcore.node.ConnectionHelper( 3211): onPeerDiscovered: [F8:95:C7:87:3C:51 G4-1], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
,D/io.jxcore.node.ConnectionHelper( 3211): notifyPeerAvailability: Peer [F8:95:C7:87:3C:51 G4-1] is available
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3211): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"G3s-1","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3211): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3211): onServiceDiscovered: [F8:95:C7:87:85:54 G3s-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): onPeerDiscovered: [F8:95:C7:87:85:54 G3s-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 G3s-1]
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3211): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"S5-1","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3211): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3211): onServiceDiscovered: [7C:F9:0E:34:8A:A0 S5-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): onPeerDiscovered: [7C:F9:0E:34:8A:A0 S5-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): modifyListOfDiscoveredPeers: Adding a new peer: [7C:F9:0E:34:8A:A0 S5-1]
I/io.jxcore.node.ConnectionHelper( 3211): onPeerDiscovered: [7C:F9:0E:34:8A:A0 S5-1], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: , device address: ee:1f:72:63:11:86
D/io.jxcore.node.ConnectionHelper( 3211): notifyPeerAvailability: Peer [7C:F9:0E:34:8A:A0 S5-1] is available
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3211): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3211): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3211): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3211): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3211): onServiceDiscovered: [7C:F9:0E:37:96:AB A5-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): modifyListOfDiscoveredPeers: Adding a new peer: [7C:F9:0E:37:96:AB A5-1]
I/io.jxcore.node.ConnectionHelper( 3211): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1], Bluetooth address: 7C:F9:0E:37:96:AB, device name: , device address: 7e:f9:0e:37:96:ac
D/io.jxcore.node.ConnectionHelper( 3211): notifyPeerAvailability: Peer [7C:F9:0E:37:96:AB A5-1] is available
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3211): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3211): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 A3-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3211): onServiceDiscovered: [08:EC:A9:50:75:41 A3-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 A3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): modifyListOfDiscoveredPeers: Adding a new peer: [08:EC:A9:50:75:41 A3-1]
I/io.jxcore.node.ConnectionHelper( 3211): onPeerDiscovered: [08:EC:A9:50:75:41 A3-1], Bluetooth address: 08:EC:A9:50:75:41, device name: , device address: 0a:ec:a9:50:75:42
D/io.jxcore.node.ConnectionHelper( 3211): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 A3-1] is available
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3211): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3211): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3211): restart: Restarting...
,D/WifiP2pManager( 3211): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3211): Service request added successfully
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3211): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3211): Service discovery started successfully
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  988): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3211): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3211): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
,I/jxcore-log( 3211): teardown
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): testFindPeers stopped
I/jxcore-log( 3211): 
I/io.jxcore.node.ConnectionHelper( 3211): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3211): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3211): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3211): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3211): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3211): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3211): onServerStopped
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3211): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3211): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): stop: Stopping peer discovery...
,D/BluetoothLeScanner( 3211): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3211): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3211): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3211): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3211): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3211): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): setState: NOT_STARTED
,I/jxcore-log( 3211): StopBroadcasting went ok
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): --- start :testSendData.js---
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":19}bt-address length : 18
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): daya100000
I/jxcore-log( 3211): 
I/jxcore-log( 3211): check server
I/jxcore-log( 3211): 
I/jxcore-log( 3211): serverPort is 37026
I/jxcore-log( 3211): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3211): start: Peer ID: 34:FC:EF:11:AE:67, peer name: Nexus 5
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3211): bind: Binding a new listener
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3211): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3211): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"Nexus 5","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3211): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3211): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3211): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3211): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3211): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3211): start: OK
I/io.jxcore.node.ConnectionHelper( 3211): start: Using peer discovery mode: BLE_AND_WIFI
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): start: Peer ID: 34:FC:EF:11:AE:67, peer name: Nexus 5
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3211): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3211): bind: Binding a new listener
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3211): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3211): createAdvertiseData: From: Nexus 5 b6a44ad1-d319-4b3a-815d-8b805a47fb51 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3211): 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3211): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 52, -4, -17, 17, -82, 103]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3211): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3211): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"Nexus 5","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3211): start: {"pi":"34:FC:EF:11:AE:67","pn":"Nexus 5","ra":"34:FC:EF:11:AE:67"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3211): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"Nexus 5","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3211): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3211): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): setState: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 3211): start: OK
,I/jxcore-log( 3211): StartBroadcasting started ok
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): [ { address: 'F8:95:C7:87:3C:51', tryCount: 0 },
I/jxcore-log( 3211):   { address: 'F4:F1:E1:5C:3B:E2', tryCount: 0 },
I/jxcore-log( 3211):   { address: '08:EC:A9:50:76:27', tryCount: 0 },
I/jxcore-log( 3211):   { address: 'B0:C5:59:3F:75:69', tryCount: 0 },
I/jxcore-log( 3211):   { address: '34:FC:EF:11:B1:66', tryCount: 0 },
I/jxcore-log( 3211):   { address: 'E0:DB:10:14:E2:C0', tryCount: 0 },
I/jxcore-log( 3211):   { address: '34:FC:EF:9D:93:0B', tryCount: 0 },
I/jxcore-log( 3211):   { address: '7C:F9:0E:51:18:22', tryCount: 0 },
I/jxcore-log( 3211):   { address: '08:EC:A9:50:75:41', tryCount: 0 },
I/jxcore-log( 3211):   { address: '58:3F:54:73:64:C0', tryCount: 0 },
I/jxcore-log( 3211):   { address: '00:F4:6F:30:E0:6C', tryCount: 0 },
I/jxcore-log( 3211):   { address: '7C:F9:0E:37:96:AB', tryCount: 0 },
I/jxcore-log( 3211):   { address: 'B4:CE:F6:AB:A4:6A', tryCount: 0 },
I/jxcore-log( 3211):   { address: '90:E7:C4:F6:69:77', tryCount: 0 },
I/jxcore-log( 3211):   { address: 'F8:95:C7:87:85:54', tryCount: 0 },
I/jxcore-log( 3211):   { address: '80:01:84:8A:B3:68', tryCount: 0 },
I/jxcore-log( 3211):   { address: '44:80:EB:7B:5A:05', tryCount: 0 },
I/jxcore-log( 3211):   { address: '7C:F9:0E:34:8A:A0', tryCount: 0 } ]
I/jxcore-log( 3211): 
I/jxcore-log( 3211): startWithNextDevice
I/jxcore-log( 3211): 
I/jxcore-log( 3211): do fake peer & start
I/jxcore-log( 3211): 
I/jxcore-log( 3211): Connect to fake peer: F8:95:C7:87:3C:51
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2016-01-08T16:59:11.384Z SendDataConnector.js: Start called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2016-01-08T16:59:11.384Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2016-01-08T16:59:11.384Z SendDataConnector.js: do connect now
I/jxcore-log( 3211): 
I/io.jxcore.node.ConnectionHelper( 3211): connect: Trying to connect to peer with ID F8:95:C7:87:3C:51
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3211): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3211): connect: [F8:95:C7:87:3C:51 G4-1]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3211): connect: Trying to start connecting to null in address F8:95:C7:87:3C:51
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3211): setInsecureRfcommSocketPortNumber: Using port 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3211): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3211): onConnecting: null F8:95:C7:87:3C:51
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3211): connect: Started connecting to null in address F8:95:C7:87:3C:51
I/io.jxcore.node.ConnectionHelper( 3211): connect: Connection process successfully started (peer ID: F8:95:C7:87:3C:51)
I/jxcore-log( 3211): 2016-01-08T16:59:11.390Z SendDataTCPServer.js: TCP/IP server is bound to port: 37026
I/jxcore-log( 3211): 
I/chromium( 3211): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
I/io.jxcore.node.ConnectionHelper( 3211): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3211): onDiscoveryManagerStateChanged: NOT_STARTED
I/chromium( 3211): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
I/io.jxcore.node.ConnectionHelper( 3211): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): start: Peer ID: 34:FC:EF:11:AE:67, peer name: Nexus 5
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): startBlePeerDiscovery: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): setState: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3211): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3211): onDiscoveryManagerStateChanged: RUNNING_WIFI
,I/io.jxcore.node.ConnectionHelper( 3211): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3211): Trying to connect to peer with address F8:95:C7:87:3C:51 (thread ID: 309)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3211): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3211): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2071): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2071): info:x10
,D/        ( 2071): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,E/BluetoothRemoteDevices( 2071): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2071): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2071): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
E/bt-btif ( 2071): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2071): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2071): Entering PendingCommandState State
,I/ActivityManager(  733): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.BluetoothPairingRequest: pid=3572 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,D/BluetoothManagerService(  733): Message: 20
D/BluetoothManagerService(  733): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3ddb5b7e:true
,I/ActivityManager(  733): Killing 2518:com.google.android.gm/u0a70 (adj 15): empty #17
,W/libprocessgroup(  733): failed to open /acct/uid_10070/pid_2518/cgroup.procs: No such file or directory
,I/BluetoothBondStateMachine( 2071): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,D/BluetoothAdapterProperties( 2071): Failed to remove device: F8:95:C7:87:3C:51
,I/BluetoothBondStateMachine( 2071): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2071): StableState(): Entering Off State
,E/bt-btm  ( 2071): tBTM_SEC_DEV:0xa4050ebc rs_disc_pending=0
W/bt-btif ( 2071): bta_dm_check_av:0
,W/bt-btif ( 2071): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3211): Local services cleared successfully
,D/btif_config_util( 2071): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant(  988): P2P-FIND-STOPPED 
,I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3211): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3211): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3211): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3211): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3211): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3211): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3211): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3211): setState: RESTARTING
,I/wpa_supplicant(  988): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3211): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3211): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3211): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3211): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3211): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3211): onP2pDeviceListChanged: 0 device(s) discovered
,W/bt-btif ( 2071): info:x10
,D/        ( 2071): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2071): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 2071): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 1
E/bt-btif ( 2071): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2071): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2071): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2071): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 0
,D/BluetoothAdapterProperties( 2071): Failed to remove device: 7C:F9:0E:37:96:AB
,I/BluetoothBondStateMachine( 2071): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2071): StableState(): Entering Off State
,W/bt-btif ( 2071): new conn_srvc id:26, app_id:255
W/bt-btif ( 2071): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2071): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3211): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3211): Incoming connection initialized (thread ID: 310)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3211): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3211): Entering thread (ID: 310)
,E/bt-btm  ( 2071): tBTM_SEC_DEV:0xa4050ebc rs_disc_pending=1
W/bt-btif ( 2071): bta_dm_check_av:0
,W/bt-btif ( 2071): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2071): tBTM_SEC_DEV:0xa4051084 rs_disc_pending=0
W/bt-btif ( 2071): bta_dm_check_av:0
,W/bt-btif ( 2071): btif_dm_cback : unhandled event (14)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3211): onBytesRead: Read 63 bytes successfully (thread ID: 310)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3211): Got valid identity from [7C:F9:0E:37:96:AB A5-1]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3211): onBytesWritten: 66 bytes successfully written (thread ID: 310)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3211): removeThreadFromList: Removing thread with ID 310
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3211): Handshake thread disposed (thread ID: 310)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3211): onIncomingConnectionConnected: [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3211): Exiting thread (ID: 310)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3211): onConnected: [7C:F9:0E:37:96:AB A5-1]
,I/io.jxcore.node.ConnectionHelper( 3211): onConnected: Incoming connection to peer [7C:F9:0E:37:96:AB A5-1]
D/io.jxcore.node.ConnectionHelper( 3211): hasConnection: No connection with peer with ID 7C:F9:0E:37:96:AB
W/io.jxcore.node.ConnectionHelper( 3211): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB A5-1] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 3211): onConnected: Incoming socket thread, for peer [7C:F9:0E:37:96:AB A5-1], created successfully
D/io.jxcore.node.ConnectionHelper( 3211): onConnected: The total number of connections is now 1
,D/io.jxcore.node.IncomingSocketThread( 3211): Entering thread (ID: 311)
,I/io.jxcore.node.IncomingSocketThread( 3211): Local host address: localhost/127.0.0.1, port: 37026
D/io.jxcore.node.IncomingSocketThread( 3211): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3211): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3211): setBufferSize: Setting buffer size to 8192 bytes
,I/jxcore-log( 3211): 2016-01-08T16:59:24.224Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3211): 
,I/io.jxcore.node.IncomingSocketThread( 3211): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3211): Exiting thread (ID: 311)
,D/io.jxcore.node.StreamCopyingThread( 3211): Entering thread (ID: 312, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 3211): Entering thread (ID: 313, name: Receiver)
,I/jxcore-log( 3211): 2016-01-08T16:59:25.523Z SendDataTCPServer.js: TCP/IP server has received 990 bytes of data
I/jxcore-log( 3211): 
I/io.jxcore.node.ConnectionHelper( 3211): lowerBleDiscoveryPowerAndStartResetTimer: Lowering the power settings
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3211): setAdvertiseMode: 0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3211): applySettings: Advertise mode: 0, advertise TX power level: 1, scan mode: 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3211): setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3211): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3211): setScanMode: 0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3211): applySettings: Advertise mode: 0, advertise TX power level: 1, scan mode: 0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3211): setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3211): setScanSettings: Mode: 0, report delay in milliseconds: 0, scan result type: 0
,W/bt-btif ( 2071): new conn_srvc id:26, app_id:255
W/bt-btif ( 2071): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2071): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3211): Incoming connection accepted
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3211): Incoming connection initialized (thread ID: 314)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3211): Waiting for incoming connections...
,I/jxcore-log( 3211): 2016-01-08T16:59:25.575Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2016-01-08T16:59:25.579Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3211): 
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3211): Entering thread (ID: 314)
,E/bt-btm  ( 2071): tBTM_SEC_DEV:0xa4051084 rs_disc_pending=1
W/bt-btif ( 2071): bta_dm_check_av:0
,W/bt-btif ( 2071): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3211): 2016-01-08T16:59:25.697Z SendDataTCPServer.js: TCP/IP server has received 6930 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:25.707Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:25.754Z SendDataTCPServer.js: TCP/IP server has received 8910 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:25.807Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:25.814Z SendDataTCPServer.js: TCP/IP server has received 10890 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:25.823Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:25.858Z SendDataTCPServer.js: TCP/IP server has received 12870 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:25.862Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:25.871Z SendDataTCPServer.js: TCP/IP server has received 14850 bytes of data
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2016-01-08T16:59:25.873Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:25.899Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:25.909Z SendDataTCPServer.js: TCP/IP server has received 17374 bytes of data
I/jxcore-log( 3211): 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3211): Start timer timeout, starting now...
,I/wpa_supplicant(  988): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3211): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3211): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3211): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/jxcore-log( 3211): 2016-01-08T16:59:26.426Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:26.517Z SendDataTCPServer.js: TCP/IP server has received 19354 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:26.669Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:26.704Z SendDataTCPServer.js: TCP/IP server has received 21334 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:26.993Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:27.180Z SendDataTCPServer.js: TCP/IP server has received 23314 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:27.193Z SendDataTCPServer.js: TCP/IP server has received 25294 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:27.277Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:27.293Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:27.344Z SendDataTCPServer.js: TCP/IP server has received 29254 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:27.352Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:27.426Z SendDataTCPServer.js: TCP/IP server has received 31234 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:27.458Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 3211): 
,W/bt-btif ( 2071): new conn_srvc id:26, app_id:1
W/bt-btif ( 2071): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2071): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2071): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3211): onSocketConnected: [F8:95:C7:87:3C:51 G4-1] (thread ID: 309)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3211): Socket connection succeeded (using port 1), total number of attempts: 1 (thread ID: 309)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3211): onBytesWritten: 66 bytes successfully written (thread ID: 315)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3211): Outgoing connection initialized (*handshake* thread ID: 315)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3211): Exiting thread (thread ID: 309)
,I/jxcore-log( 3211): 2016-01-08T16:59:27.536Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3211): 
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3211): onBytesRead: Read 63 bytes successfully (thread ID: 314)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3211): Got valid identity from [F8:95:C7:87:3C:51 G4-1]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3211): onBytesWritten: 66 bytes successfully written (thread ID: 314)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3211): removeThreadFromList: Removing thread with ID 314
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3211): Handshake thread disposed (thread ID: 314)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3211): onIncomingConnectionConnected: [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3211): Exiting thread (ID: 314)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3211): onConnected: [F8:95:C7:87:3C:51 G4-1]
I/io.jxcore.node.ConnectionHelper( 3211): onConnected: Incoming connection to peer [F8:95:C7:87:3C:51 G4-1]
D/io.jxcore.node.ConnectionHelper( 3211): hasConnection: No connection with peer with ID F8:95:C7:87:3C:51
W/io.jxcore.node.ConnectionHelper( 3211): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 G4-1] already in the list, will not add again
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3211): Entering thread (ID: 315)
,I/io.jxcore.node.ConnectionHelper( 3211): onConnected: Incoming socket thread, for peer [F8:95:C7:87:3C:51 G4-1], created successfully
D/io.jxcore.node.ConnectionHelper( 3211): onConnected: The total number of connections is now 2
,D/io.jxcore.node.IncomingSocketThread( 3211): Entering thread (ID: 316)
,I/io.jxcore.node.IncomingSocketThread( 3211): Local host address: localhost/127.0.0.1, port: 37026
D/io.jxcore.node.IncomingSocketThread( 3211): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3211): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3211): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3211): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3211): Exiting thread (ID: 316)
,I/jxcore-log( 3211): 2016-01-08T16:59:27.567Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3211): 
,D/io.jxcore.node.StreamCopyingThread( 3211): Entering thread (ID: 318, name: Receiver)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3211): onBytesRead: Read 63 bytes successfully (thread ID: 315)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3211): Handshake succeeded with [F8:95:C7:87:3C:51 G4-1]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3211): onHandshakeSucceeded: [F8:95:C7:87:3C:51 G4-1] (thread ID: 309)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3211): Exiting thread (ID: 315)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3211): onConnected: [F8:95:C7:87:3C:51 G4-1]
I/io.jxcore.node.ConnectionHelper( 3211): onConnected: Outgoing connection to peer [F8:95:C7:87:3C:51 G4-1]
D/io.jxcore.node.ConnectionHelper( 3211): hasConnection: We have an incoming connection with peer with ID F8:95:C7:87:3C:51
W/io.jxcore.node.ConnectionHelper( 3211): onConnected: Already connected with peer [F8:95:C7:87:3C:51 G4-1], continuing anyway...
,W/io.jxcore.node.ConnectionHelper( 3211): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 G4-1] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 3211): onConnected: Outgoing socket thread, for peer [F8:95:C7:87:3C:51 G4-1], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3211): setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3211): setConnectionTimeout: 15000
D/io.jxcore.node.ConnectionHelper( 3211): onConnected: The total number of connections is now 3
,D/io.jxcore.node.StreamCopyingThread( 3211): Entering thread (ID: 317, name: Sender)
,D/io.jxcore.node.OutgoingSocketThread( 3211): Entering thread (ID: 319)
,D/io.jxcore.node.OutgoingSocketThread( 3211): Server socket local port: 56758
I/io.jxcore.node.OutgoingSocketThread( 3211): Now accepting connections...
,E/bt-btm  ( 2071): tBTM_SEC_DEV:0xa4051084 rs_disc_pending=1
W/bt-btif ( 2071): bta_dm_check_av:0
,W/bt-btif ( 2071): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3211): 2016-01-08T16:59:27.704Z SendDataTCPServer.js: TCP/IP server has received 37174 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:27.710Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:27.780Z SendDataTCPServer.js: TCP/IP server has received 39154 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:27.796Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:27.804Z SendDataTCPServer.js: TCP/IP server has received 41134 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:27.875Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3211): 
,I/io.jxcore.node.ConnectionHelper( 3211): onListeningForIncomingConnections: Outgoing connection is using port 56758 (peer ID: F8:95:C7:87:3C:51)
,I/jxcore-log( 3211): 2016-01-08T16:59:27.894Z SendDataConnector.js: CLIENT connected to 56758, error: null
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2016-01-08T16:59:27.894Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3211): 
,I/io.jxcore.node.OutgoingSocketThread( 3211): Incoming data from address: /127.0.0.1, port: 56758
D/io.jxcore.node.OutgoingSocketThread( 3211): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3211): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3211): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3211): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3211): Exiting thread (ID: 319)
,D/io.jxcore.node.StreamCopyingThread( 3211): Entering thread (ID: 321, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3211): Entering thread (ID: 320, name: Sender)
,I/jxcore-log( 3211): 2016-01-08T16:59:27.940Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2016-01-08T16:59:27.943Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3211): 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2071): info:x10
,D/        ( 2071): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
E/BluetoothRemoteDevices( 2071): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3211): 2016-01-08T16:59:28.835Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:28.837Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3211): 
,E/bt-btm  ( 2071): tBTM_SEC_DEV:0xa405124c rs_disc_pending=0
W/bt-btif ( 2071): bta_dm_check_av:0
,W/bt-btif ( 2071): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3211): 2016-01-08T16:59:28.997Z SendDataTCPServer.js: TCP/IP server has received 54994 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:29.036Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:29.057Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:29.061Z SendDataTCPServer.js: TCP/IP server has received 56974 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:29.068Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:29.073Z SendDataTCPServer.js: TCP/IP server has received 58954 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:29.079Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3211): 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3211): 2016-01-08T16:59:29.210Z SendDataTCPServer.js: TCP/IP server has received 9182 bytes of data
I/jxcore-log( 3211): 
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/jxcore-log( 3211): 2016-01-08T16:59:29.438Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:29.444Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3211): 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3211): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): onP2pDeviceListChanged: Peer 1: A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 3211): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3211): Service request added successfully
,I/jxcore-log( 3211): 2016-01-08T16:59:29.469Z SendDataTCPServer.js: TCP/IP server has received 11162 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:29.506Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3211): 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3211): 2016-01-08T16:59:29.697Z SendDataTCPServer.js: TCP/IP server has received 62914 bytes of data
I/jxcore-log( 3211): 
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/jxcore-log( 3211): 2016-01-08T16:59:29.778Z SendDataTCPServer.js: TCP/IP server has received 64894 bytes of data
I/jxcore-log( 3211): 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3211): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
,I/BluetoothBondStateMachine( 2071): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1
,E/bt-btif ( 2071): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2071): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2071): Entering PendingCommandState State
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3211): 2016-01-08T16:59:30.036Z SendDataTCPServer.js: TCP/IP server has received 13142 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:30.114Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 3211): 
,I/BluetoothBondStateMachine( 2071): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
,D/BluetoothAdapterProperties( 2071): Failed to remove device: F8:95:C7:87:85:54
,I/BluetoothBondStateMachine( 2071): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2071): StableState(): Entering Off State
,I/jxcore-log( 3211): 2016-01-08T16:59:30.377Z SendDataTCPServer.js: TCP/IP server has received 66874 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:30.383Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 3211): 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3211): Service discovery started successfully
,W/bt-btif ( 2071): new conn_srvc id:26, app_id:255
W/bt-btif ( 2071): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2071): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3211): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3211): Incoming connection initialized (thread ID: 322)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3211): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3211): Entering thread (ID: 322)
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/jxcore-log( 3211): 2016-01-08T16:59:30.665Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3211): 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3211): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3211): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3211): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3211): onServiceDiscovered: [58:3F:54:73:64:C0 G3-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): onPeerDiscovered: [58:3F:54:73:64:C0 G3-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): modifyListOfDiscoveredPeers: Adding a new peer: [58:3F:54:73:64:C0 G3-1]
I/io.jxcore.node.ConnectionHelper( 3211): onPeerDiscovered: [58:3F:54:73:64:C0 G3-1], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper( 3211): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 G3-1] already in the list, will not add again
,E/bt-btm  ( 2071): tBTM_SEC_DEV:0xa405124c rs_disc_pending=1
W/bt-btif ( 2071): bta_dm_check_av:0
,W/bt-btif ( 2071): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3211): 2016-01-08T16:59:30.977Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:30.981Z SendDataTCPServer.js: TCP/IP server has received 15122 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:30.983Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:30.989Z SendDataTCPServer.js: TCP/IP server has received 70834 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:30.995Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3211): 
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3211): onBytesRead: Read 64 bytes successfully (thread ID: 322)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3211): Got valid identity from [F8:95:C7:87:85:54 G3s-1]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3211): onBytesWritten: 66 bytes successfully written (thread ID: 322)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3211): removeThreadFromList: Removing thread with ID 322
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3211): Handshake thread disposed (thread ID: 322)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3211): onIncomingConnectionConnected: [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3211): Exiting thread (ID: 322)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3211): onConnected: [F8:95:C7:87:85:54 G3s-1]
I/io.jxcore.node.ConnectionHelper( 3211): onConnected: Incoming connection to peer [F8:95:C7:87:85:54 G3s-1]
D/io.jxcore.node.ConnectionHelper( 3211): hasConnection: No connection with peer with ID F8:95:C7:87:85:54
W/io.jxcore.node.ConnectionHelper( 3211): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 G3s-1] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 3211): onConnected: Incoming socket thread, for peer [F8:95:C7:87:85:54 G3s-1], created successfully
D/io.jxcore.node.ConnectionHelper( 3211): onConnected: The total number of connections is now 4
,D/io.jxcore.node.IncomingSocketThread( 3211): Entering thread (ID: 323)
,I/jxcore-log( 3211): 2016-01-08T16:59:31.057Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3211): 
,I/io.jxcore.node.IncomingSocketThread( 3211): Local host address: localhost/127.0.0.1, port: 37026
D/io.jxcore.node.IncomingSocketThread( 3211): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3211): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 3211): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3211): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3211): Exiting thread (ID: 323)
,D/io.jxcore.node.StreamCopyingThread( 3211): Entering thread (ID: 325, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3211): Entering thread (ID: 324, name: Sender)
,I/jxcore-log( 3211): 2016-01-08T16:59:31.349Z SendDataTCPServer.js: TCP/IP server has received 72814 bytes of data
I/jxcore-log( 3211): 
,D/        ( 2071): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:41220
,I/jxcore-log( 3211): 2016-01-08T16:59:31.684Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:31.848Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:31.950Z SendDataTCPServer.js: TCP/IP server has received 76774 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:32.008Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:32.174Z SendDataTCPServer.js: TCP/IP server has received 78754 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:32.181Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:32.242Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:32.277Z SendDataTCPServer.js: TCP/IP server has received 80734 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:32.291Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:32.377Z SendDataTCPServer.js: TCP/IP server has received 82714 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:32.434Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:32.443Z SendDataTCPServer.js: TCP/IP server has received 84694 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:32.451Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:32.456Z SendDataTCPServer.js: TCP/IP server has received 86674 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:32.624Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:32.633Z SendDataTCPServer.js: TCP/IP server has received 88654 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:32.640Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:32.784Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:32.946Z SendDataTCPServer.js: TCP/IP server has received 92614 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:32.977Z SendDataTCPServer.js: TCP/IP server has received 94594 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:33.138Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:33.145Z SendDataTCPServer.js: TCP/IP server has received 96574 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:33.360Z SendDataTCPServer.js: TCP/IP server has received 990 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:33.386Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:33.496Z SendDataTCPServer.js: TCP/IP server has received 98554 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:33.517Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:33.582Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:33.590Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:33.603Z SendDataTCPServer.js: TCP/IP server has received 2970 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:33.625Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:33.737Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:33.802Z SendDataTCPServer.js: TCP/IP server has received 4950 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:33.817Z SendDataTCPServer.js: TCP/IP server has received 9182 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:33.874Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:33.922Z SendDataTCPServer.js: TCP/IP server has received 11162 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:33.980Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:34.118Z SendDataTCPServer.js: TCP/IP server has received 13142 bytes of data
I/jxcore-log( 3211): 
,D/        ( 2071): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:19440
,I/jxcore-log( 3211): 2016-01-08T16:59:34.165Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:34.174Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:34.180Z SendDataTCPServer.js: TCP/IP server has received 17374 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:34.223Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:34.232Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:34.249Z SendDataTCPServer.js: TCP/IP server has received 16112 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:34.270Z SendDataTCPServer.js: TCP/IP server has received 23314 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:34.333Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:34.379Z SendDataTCPServer.js: TCP/IP server has received 25294 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:34.387Z SendDataTCPServer.js: TCP/IP server has received 17102 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:34.418Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3211): 
,E/bt-btm  ( 2071): tBTM_SEC_DEV:0xa4051084 rs_disc_pending=0
W/bt-btif ( 2071): bta_dm_check_av:0
,W/bt-btif ( 2071): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3211): 2016-01-08T16:59:34.461Z SendDataTCPServer.js: TCP/IP server has received 18092 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:34.471Z SendDataTCPServer.js: TCP/IP server has received 27274 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:34.481Z SendDataTCPServer.js: TCP/IP server has received 29254 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:34.487Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:34.520Z SendDataTCPServer.js: TCP/IP server has received 19082 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:34.540Z SendDataTCPServer.js: TCP/IP server has received 31234 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:34.577Z SendDataTCPServer.js: TCP/IP server has received 35194 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:34.599Z SendDataTCPServer.js: TCP/IP server has received 20072 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:34.638Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:34.691Z SendDataTCPServer.js: TCP/IP server has received 37174 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:34.701Z SendDataTCPServer.js: TCP/IP server has received 39154 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:34.708Z SendDataTCPServer.js: TCP/IP server has received 41134 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:34.749Z SendDataTCPServer.js: TCP/IP server has received 21062 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:34.769Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:34.810Z SendDataTCPServer.js: TCP/IP server has received 47074 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:34.832Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:34.850Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2016-01-08T16:59:34.853Z SendDataTCPServer.js: TCP/IP server has received 49054 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:34.865Z SendDataTCPServer.js: TCP/IP server has received 51034 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:34.872Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:34.938Z SendDataTCPServer.js: TCP/IP server has received 53014 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:35.039Z SendDataTCPServer.js: TCP/IP server has received 22052 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:35.050Z SendDataTCPServer.js: TCP/IP server has received 23042 bytes of data
I/jxcore-log( 3211): 
,D/btif_config_util( 2071): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3211): 2016-01-08T16:59:35.157Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:35.187Z SendDataTCPServer.js: TCP/IP server has received 24032 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:35.195Z SendDataTCPServer.js: TCP/IP server has received 25022 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:35.208Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:35.214Z SendDataTCPServer.js: TCP/IP server has received 54994 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:35.279Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:35.336Z SendDataTCPServer.js: TCP/IP server has received 56974 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:35.347Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:35.401Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:35.411Z SendDataTCPServer.js: TCP/IP server has received 62914 bytes of data
I/jxcore-log( 3211): 
,E/bt-btm  ( 2071): tBTM_SEC_DEV:0xa4050ebc rs_disc_pending=0
W/bt-btif ( 2071): bta_dm_check_av:0
,W/bt-btif ( 2071): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3211): 2016-01-08T16:59:35.622Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:35.630Z SendDataTCPServer.js: TCP/IP server has received 64894 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:35.685Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:35.742Z SendDataTCPServer.js: TCP/IP server has received 66874 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:35.746Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:35.758Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:36.063Z SendDataTCPServer.js: TCP/IP server has received 70834 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:36.121Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3211): 
,W/bt-btif ( 2071): invalid rfc slot id: 5
,W/io.jxcore.node.StreamCopyingThread( 3211): Either failed to read from the output stream or write to the input stream (thread ID: 313, thread name: Receiver): bt socket closed, read return: -1,
E/io.jxcore.node.IncomingSocketThread( 3211): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3211): onDisconnected: Incoming connection, peer [7C:F9:0E:37:96:AB A5-1] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.StreamCopyingThread( 3211): Exiting thread (ID: 313, name: Receiver)
,I/io.jxcore.node.ConnectionHelper( 3211): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 311
D/io.jxcore.node.IncomingSocketThread( 3211): close: Stopping receiving thread...
,I/io.jxcore.node.StreamCopyingThread( 3211): doStop: Thread ID: 313
D/io.jxcore.node.IncomingSocketThread( 3211): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3211): doStop: Thread ID: 312
,D/io.jxcore.node.IncomingSocketThread( 3211): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 3211): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3211): Either failed to read from the output stream or write to the input stream (thread ID: 312, thread name: Sender): Socket closed
,E/io.jxcore.node.IncomingSocketThread( 3211): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3211): onDisconnected: Incoming connection, peer [7C:F9:0E:37:96:AB A5-1] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.StreamCopyingThread( 3211): Exiting thread (ID: 312, name: Sender)
,D/io.jxcore.node.IncomingSocketThread( 3211): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 3211): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3211): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3211): closeAndRemoveIncomingConnectionThread: 2 incoming connection(s) left
,I/jxcore-log( 3211): 2016-01-08T16:59:36.272Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3211): 
,D/io.jxcore.node.ConnectionHelper( 3211): closeAndRemoveIncomingConnectionThread: 2 incoming connection(s) left
,I/jxcore-log( 3211): 2016-01-08T16:59:36.301Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:36.336Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:36.364Z SendDataTCPServer.js: TCP/IP server has received 74794 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:36.368Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:36.372Z SendDataTCPServer.js: TCP/IP server has received 76774 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:36.423Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:36.432Z SendDataTCPServer.js: TCP/IP server has received 78754 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:36.490Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:36.498Z SendDataTCPServer.js: TCP/IP server has received 80734 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:36.506Z SendDataTCPServer.js: TCP/IP server has received 82714 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:36.537Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:36.548Z SendDataTCPServer.js: TCP/IP server has received 84694 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:36.554Z SendDataTCPServer.js: TCP/IP server has received 86674 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:36.561Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:36.564Z SendDataTCPServer.js: TCP/IP server has received 88654 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:36.610Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:36.624Z SendDataTCPServer.js: TCP/IP server has received 92614 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:36.671Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:36.709Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:36.742Z SendDataTCPServer.js: TCP/IP server has received 96574 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:36.934Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:37.002Z SendDataTCPServer.js: TCP/IP server has received 98554 bytes of data
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2016-01-08T16:59:37.004Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3211): 
,W/bt-rfcomm( 2071): rfc_find_lcid_mcb LCID reused LCID:0x45 current:0x0
W/bt-rfcomm( 2071): RFCOMM_DisconnectInd LCID:0x45
,E/bt-btm  ( 2071): tBTM_SEC_DEV:0xa4051084 rs_disc_pending=1
W/bt-btif ( 2071): bta_dm_check_av:0
,W/bt-btif ( 2071): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2071): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2071): onReceive
,D/BluetoothManagerService(  733): Message: 20
D/BluetoothManagerService(  733): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@26d25ff5:true
,I/BTConnectionReceiver( 1351): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1351): Bluetooth Device Name: A5-1
,E/bt-btm  ( 2071): tBTM_SEC_DEV:0xa405124c rs_disc_pending=0
W/bt-btif ( 2071): bta_dm_check_av:0
,W/bt-btif ( 2071): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2071): invalid rfc slot id: 8
,W/io.jxcore.node.StreamCopyingThread( 3211): Either failed to read from the output stream or write to the input stream (thread ID: 325, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 3211): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3211): onDisconnected: Incoming connection, peer [F8:95:C7:87:85:54 G3s-1] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
D/io.jxcore.node.StreamCopyingThread( 3211): Exiting thread (ID: 325, name: Receiver)
,I/io.jxcore.node.ConnectionHelper( 3211): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 323
D/io.jxcore.node.IncomingSocketThread( 3211): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3211): doStop: Thread ID: 325
D/io.jxcore.node.IncomingSocketThread( 3211): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3211): doStop: Thread ID: 324
D/io.jxcore.node.IncomingSocketThread( 3211): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 3211): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3211): Either failed to read from the output stream or write to the input stream (thread ID: 324, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3211): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3211): onDisconnected: Incoming connection, peer [F8:95:C7:87:85:54 G3s-1] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.StreamCopyingThread( 3211): Exiting thread (ID: 324, name: Sender)
,D/io.jxcore.node.IncomingSocketThread( 3211): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 3211): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3211): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3211): closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,I/jxcore-log( 3211): 2016-01-08T16:59:43.210Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3211): 
D/io.jxcore.node.ConnectionHelper( 3211): closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,E/bt-btm  ( 2071): tBTM_SEC_DEV:0xa4050ebc rs_disc_pending=1
W/bt-btif ( 2071): bta_dm_check_av:0
,W/bt-btif ( 2071): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 2071): rfc_find_lcid_mcb LCID reused LCID:0x47 current:0x0
,W/bt-rfcomm( 2071): RFCOMM_DisconnectInd LCID:0x47
,I/jxcore-log( 3211): 2016-01-08T16:59:44.327Z SendDataTCPServer.js: TCP/IP server has received 26012 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:44.369Z SendDataTCPServer.js: TCP/IP server has received 27002 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:44.533Z SendDataTCPServer.js: TCP/IP server has received 27992 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:44.622Z SendDataTCPServer.js: TCP/IP server has received 28982 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:44.666Z SendDataTCPServer.js: TCP/IP server has received 29972 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:44.707Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:44.819Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:45.230Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:45.780Z SendDataTCPServer.js: TCP/IP server has received 30962 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:45.811Z SendDataTCPServer.js: TCP/IP server has received 31952 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:45.847Z SendDataTCPServer.js: TCP/IP server has received 34922 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:45.857Z SendDataTCPServer.js: TCP/IP server has received 35912 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T16:59:45.867Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2016-01-08T16:59:45.868Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3211): 
I/jxcore-log( 3211): oneRoundDownNow
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2016-01-08T16:59:45.872Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2016-01-08T16:59:45.872Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3211): 
,D/io.jxcore.node.ConnectionHelper( 3211): disconnectOutgoingConnection: Trying to close connection to peer with ID F8:95:C7:87:3C:51
I/io.jxcore.node.ConnectionHelper( 3211): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: F8:95:C7:87:3C:51
I/io.jxcore.node.IncomingSocketThread( 3211): close
,D/io.jxcore.node.IncomingSocketThread( 3211): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3211): doStop: Thread ID: 321
D/io.jxcore.node.IncomingSocketThread( 3211): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3211): doStop: Thread ID: 320
D/io.jxcore.node.IncomingSocketThread( 3211): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 3211): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3211): Either failed to read from the output stream or write to the input stream (thread ID: 320, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3211): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3211): onDisconnected: Outgoing connection, peer [F8:95:C7:87:3C:51 G4-1] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.StreamCopyingThread( 3211): Exiting thread (ID: 320, name: Sender)
,D/io.jxcore.node.IncomingSocketThread( 3211): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 3211): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3211): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3211): Either failed to read from the output stream or write to the input stream (thread ID: 321, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.IncomingSocketThread( 3211): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3211): onDisconnected: Outgoing connection, peer [F8:95:C7:87:3C:51 G4-1] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
D/io.jxcore.node.StreamCopyingThread( 3211): Exiting thread (ID: 321, name: Receiver)
,D/io.jxcore.node.ConnectionHelper( 3211): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3211): disconnectOutgoingConnection: Successfully disconnected (peer ID: F8:95:C7:87:3C:51
I/jxcore-log( 3211): 2016-01-08T16:59:45.918Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 3211): 
I/jxcore-log( 3211): ---- round done--------
I/jxcore-log( 3211): 
I/jxcore-log( 3211): startWithNextDevice
I/jxcore-log( 3211): 
I/jxcore-log( 3211): do fake peer & start
I/jxcore-log( 3211): 
I/jxcore-log( 3211): Connect to fake peer: F4:F1:E1:5C:3B:E2
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2016-01-08T16:59:45.923Z SendDataConnector.js: Start called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2016-01-08T16:59:45.924Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2016-01-08T16:59:45.924Z SendDataConnector.js: do connect now
I/jxcore-log( 3211): 
,I/io.jxcore.node.ConnectionHelper( 3211): connect: Trying to connect to peer with ID F4:F1:E1:5C:3B:E2
W/io.jxcore.node.ConnectionHelper( 3211): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3211): connect: [F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3211): connect: Trying to start connecting to null in address F4:F1:E1:5C:3B:E2
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3211): setInsecureRfcommSocketPortNumber: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3211): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3211): onConnecting: null F4:F1:E1:5C:3B:E2
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3211): connect: Started connecting to null in address F4:F1:E1:5C:3B:E2
I/io.jxcore.node.ConnectionHelper( 3211): connect: Connection process successfully started (peer ID: F4:F1:E1:5C:3B:E2)
E/io.jxcore.node.ConnectionHelper( 3211): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:95:C7:87:3C:51
D/io.jxcore.node.ConnectionHelper( 3211): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
E/io.jxcore.node.ConnectionHelper( 3211): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:95:C7:87:3C:51
D/io.jxcore.node.ConnectionHelper( 3211): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/jxcore-log( 3211): 2016-01-08T16:59:45.941Z SendDataTCPServer.js: TCP/IP server has received 37892 bytes of data
I/jxcore-log( 3211): 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3211): Trying to connect to peer with address F4:F1:E1:5C:3B:E2 (thread ID: 326)
,W/BluetoothAdapter( 3211): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2071): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2071): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2071): onReceive
,I/BTConnectionReceiver( 1351): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1351): Bluetooth Device Name: G3s-1
,W/bt-btif ( 2071): bta_jv_rfc_port_to_cb(port_handle:0x9):jv handle:0x0 not FOUND
,W/bt-btif ( 2071): info:x10
,D/        ( 2071): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 2071): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2071): tBTM_SEC_DEV:0xa4051414 rs_disc_pending=1
W/bt-btif ( 2071): bta_dm_check_av:0
,W/bt-btif ( 2071): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2071): tBTM_SEC_DEV:0xa4051414 rs_disc_pending=0
W/bt-btif ( 2071): bta_dm_check_av:0
,W/bt-btif ( 2071): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2071): btm_sec_disconnected - Clearing Pending flag
,W/bt-btif ( 2071): invalid rfc slot id: 7
,W/io.jxcore.node.StreamCopyingThread( 3211): Either failed to read from the output stream or write to the input stream (thread ID: 318, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 3211): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3211): onDisconnected: Incoming connection, peer [F8:95:C7:87:3C:51 G4-1] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
D/io.jxcore.node.StreamCopyingThread( 3211): Exiting thread (ID: 318, name: Receiver)
,I/io.jxcore.node.ConnectionHelper( 3211): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 316
D/io.jxcore.node.IncomingSocketThread( 3211): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3211): doStop: Thread ID: 318
D/io.jxcore.node.IncomingSocketThread( 3211): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3211): doStop: Thread ID: 317
D/io.jxcore.node.IncomingSocketThread( 3211): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 3211): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3211): Either failed to read from the output stream or write to the input stream (thread ID: 317, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3211): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3211): onDisconnected: Incoming connection, peer [F8:95:C7:87:3C:51 G4-1] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.StreamCopyingThread( 3211): Exiting thread (ID: 317, name: Sender)
,D/io.jxcore.node.IncomingSocketThread( 3211): closeLocalSocketAndStreams: Closing the local output stream...
,D/io.jxcore.node.IncomingSocketThread( 3211): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3211): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3211): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,I/jxcore-log( 3211): 2016-01-08T16:59:51.414Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3211): 
,D/io.jxcore.node.ConnectionHelper( 3211): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/BluetoothMapService( 2071): onReceive
,I/BTConnectionReceiver( 1351): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1351): Bluetooth Device Name: G4-1
,E/bt-btm  ( 2071): tBTM_SEC_DEV:0xa4051414 rs_disc_pending=1
W/bt-btif ( 2071): bta_dm_check_av:0
,W/bt-btif ( 2071): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 2071): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2071): bondStateChangeCallback: Status: 0 Address: F4:F1:E1:5C:3B:E2 newState: 1
E/bt-btif ( 2071): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2071): Bond State Change Intent:F4:F1:E1:5C:3B:E2 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2071): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2071): bondStateChangeCallback: Status: 0 Address: F4:F1:E1:5C:3B:E2 newState: 0
,D/BluetoothAdapterProperties( 2071): Failed to remove device: F4:F1:E1:5C:3B:E2
,I/BluetoothBondStateMachine( 2071): Bond State Change Intent:F4:F1:E1:5C:3B:E2 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2071): StableState(): Entering Off State
,E/bt-btm  ( 2071): tBTM_SEC_DEV:0xa4051414 rs_disc_pending=0
W/bt-btif ( 2071): bta_dm_check_av:0
,W/bt-btif ( 2071): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2071): new conn_srvc id:26, app_id:1
W/bt-btif ( 2071): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2071): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3211): onSocketConnected: [F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2] (thread ID: 326)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3211): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 326)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3211): onBytesWritten: 66 bytes successfully written (thread ID: 327)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3211): Outgoing connection initialized (*handshake* thread ID: 327)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3211): Exiting thread (thread ID: 326)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3211): Entering thread (ID: 327)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3211): onBytesRead: Read 65 bytes successfully (thread ID: 327)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3211): Handshake succeeded with [F4:F1:E1:5C:3B:E2 XT1039]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3211): onHandshakeSucceeded: [F4:F1:E1:5C:3B:E2 XT1039] (thread ID: 326)
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3211): Exiting thread (ID: 327)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3211): onConnected: [F4:F1:E1:5C:3B:E2 XT1039]
I/io.jxcore.node.ConnectionHelper( 3211): onConnected: Outgoing connection to peer [F4:F1:E1:5C:3B:E2 XT1039]
,D/io.jxcore.node.ConnectionHelper( 3211): hasConnection: No connection with peer with ID F4:F1:E1:5C:3B:E2
D/io.jxcore.node.ConnectionHelper( 3211): notifyPeerAvailability: Peer [F4:F1:E1:5C:3B:E2 XT1039] is available
,I/io.jxcore.node.ConnectionHelper( 3211): onConnected: Outgoing socket thread, for peer [F4:F1:E1:5C:3B:E2 XT1039], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3211): setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3211): setConnectionTimeout: 15000
,D/io.jxcore.node.ConnectionHelper( 3211): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 3211): Entering thread (ID: 328)
,D/io.jxcore.node.OutgoingSocketThread( 3211): Server socket local port: 46697
I/io.jxcore.node.OutgoingSocketThread( 3211): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3211): onListeningForIncomingConnections: Outgoing connection is using port 46697 (peer ID: F4:F1:E1:5C:3B:E2)
I/jxcore-log( 3211): 2016-01-08T16:59:53.061Z SendDataConnector.js: CLIENT connected to 46697, error: null
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2016-01-08T16:59:53.062Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3211): 
,I/io.jxcore.node.OutgoingSocketThread( 3211): Incoming data from address: /127.0.0.1, port: 46697
D/io.jxcore.node.OutgoingSocketThread( 3211): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3211): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3211): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.OutgoingSocketThread( 3211): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3211): Exiting thread (ID: 328)
,I/jxcore-log( 3211): 2016-01-08T16:59:53.091Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3211): 
,D/io.jxcore.node.StreamCopyingThread( 3211): Entering thread (ID: 329, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 3211): Entering thread (ID: 330, name: Receiver)
,D/        ( 2071): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:72020
,D/        ( 2071): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:60140
,D/        ( 2071): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:48260
,D/        ( 2071): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:36380
,D/        ( 2071): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:24500
,D/        ( 2071): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:12620
,D/btif_config_util( 2071): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3211): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3211): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3211): setState: RESTARTING
,I/wpa_supplicant(  988): P2P-FIND-STOPPED 
,I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3211): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3211): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3211): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3211): Start timer timeout, starting now...
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3211): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3211): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3211): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3211): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3211): restart: Restarting...
,D/WifiP2pManager( 3211): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3211): Service request added successfully
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3211): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 G3-1]
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/io.jxcore.node.ConnectionHelper( 3211): Powering the BLE discovery back up
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3211): setAdvertiseMode: 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3211): applySettings: Advertise mode: 1, advertise TX power level: 1, scan mode: 0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3211): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3211): setScanSettings: Mode: 0, report delay in milliseconds: 0, scan result type: 0
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3211): setScanMode: 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3211): applySettings: Advertise mode: 1, advertise TX power level: 1, scan mode: 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3211): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3211): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3211): Service discovery started successfully
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3211): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 G3-1]
,I/jxcore-log( 3211): 2016-01-08T17:00:14.017Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2016-01-08T17:00:14.018Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:14.031Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2016-01-08T17:00:14.032Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2016-01-08T17:00:14.033Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3211): 
,E/io.jxcore.node.StreamCopyingThread( 3211): Input stream got -1 on read (thread ID: 329, thread name: Sender)
,E/io.jxcore.node.OutgoingSocketThread( 3211): The sending thread failed with error: Input stream got -1 on read
W/io.jxcore.node.ConnectionHelper( 3211): onDisconnected: Outgoing connection, peer [F4:F1:E1:5C:3B:E2 XT1039] disconnected: Input stream got -1 on read
,D/io.jxcore.node.StreamCopyingThread( 3211): Exiting thread (ID: 329, name: Sender)
,I/io.jxcore.node.ConnectionHelper( 3211): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: F4:F1:E1:5C:3B:E2
I/io.jxcore.node.OutgoingSocketThread( 3211): close
D/io.jxcore.node.OutgoingSocketThread( 3211): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3211): doStop: Thread ID: 330
D/io.jxcore.node.OutgoingSocketThread( 3211): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3211): doStop: Thread ID: 329
D/io.jxcore.node.OutgoingSocketThread( 3211): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 3211): closeLocalSocketAndStreams: Closing the local input stream...
D/io.jxcore.node.OutgoingSocketThread( 3211): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 3211): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3211): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3211): Either failed to read from the output stream or write to the input stream (thread ID: 330, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 3211): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3211): onDisconnected: Outgoing connection, peer [F4:F1:E1:5C:3B:E2 XT1039] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
D/io.jxcore.node.StreamCopyingThread( 3211): Exiting thread (ID: 330, name: Receiver)
,D/io.jxcore.node.ConnectionHelper( 3211): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,E/io.jxcore.node.ConnectionHelper( 3211): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F4:F1:E1:5C:3B:E2
D/io.jxcore.node.ConnectionHelper( 3211): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,I/jxcore-log( 3211): 2016-01-08T17:00:19.034Z SendDataConnector.js: re-try now : F4:F1:E1:5C:3B:E2
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:19.039Z SendDataConnector.js: ReStart called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3211): 
,W/bt-btif ( 2071): info:x10
,D/        ( 2071): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,I/BTConnectionReceiver( 1351): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1351): Bluetooth Device Name: G4-1
,I/BluetoothBondStateMachine( 2071): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
E/bt-btif ( 2071): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2071): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2071): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2071): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,D/BluetoothAdapterProperties( 2071): Failed to remove device: F8:95:C7:87:3C:51
,I/BluetoothBondStateMachine( 2071): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2071): StableState(): Entering Off State
,E/bt-btm  ( 2071): tBTM_SEC_DEV:0xa4051414 rs_disc_pending=1
W/bt-btif ( 2071): bta_dm_check_av:0
,W/bt-btif ( 2071): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2071): new conn_srvc id:26, app_id:255
W/bt-btif ( 2071): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2071): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3211): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3211): Incoming connection initialized (thread ID: 331)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3211): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3211): Entering thread (ID: 331)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3211): onBytesRead: Read 63 bytes successfully (thread ID: 331)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3211): Got valid identity from [F8:95:C7:87:3C:51 G4-1]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3211): onBytesWritten: 66 bytes successfully written (thread ID: 331)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3211): removeThreadFromList: Removing thread with ID 331
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3211): Handshake thread disposed (thread ID: 331)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3211): onIncomingConnectionConnected: [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3211): Exiting thread (ID: 331)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3211): onConnected: [F8:95:C7:87:3C:51 G4-1]
,I/io.jxcore.node.ConnectionHelper( 3211): onConnected: Incoming connection to peer [F8:95:C7:87:3C:51 G4-1]
D/io.jxcore.node.ConnectionHelper( 3211): hasConnection: No connection with peer with ID F8:95:C7:87:3C:51
W/io.jxcore.node.ConnectionHelper( 3211): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 G4-1] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 3211): onConnected: Incoming socket thread, for peer [F8:95:C7:87:3C:51 G4-1], created successfully
D/io.jxcore.node.ConnectionHelper( 3211): onConnected: The total number of connections is now 1
,D/io.jxcore.node.IncomingSocketThread( 3211): Entering thread (ID: 332)
,I/io.jxcore.node.IncomingSocketThread( 3211): Local host address: localhost/127.0.0.1, port: 37026
D/io.jxcore.node.IncomingSocketThread( 3211): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3211): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3211): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3211): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3211): Exiting thread (ID: 332)
,I/jxcore-log( 3211): 2016-01-08T17:00:20.723Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3211): 
,D/io.jxcore.node.StreamCopyingThread( 3211): Entering thread (ID: 333, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 3211): Entering thread (ID: 334, name: Receiver)
,I/jxcore-log( 3211): 2016-01-08T17:00:21.435Z SendDataTCPServer.js: TCP/IP server has received 990 bytes of data
I/jxcore-log( 3211): 
I/io.jxcore.node.ConnectionHelper( 3211): lowerBleDiscoveryPowerAndStartResetTimer: Lowering the power settings
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3211): setAdvertiseMode: 0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3211): applySettings: Advertise mode: 0, advertise TX power level: 1, scan mode: 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3211): setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3211): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3211): setScanMode: 0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3211): applySettings: Advertise mode: 0, advertise TX power level: 1, scan mode: 0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3211): setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3211): setScanSettings: Mode: 0, report delay in milliseconds: 0, scan result type: 0
,I/jxcore-log( 3211): 2016-01-08T17:00:21.479Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2016-01-08T17:00:21.481Z SendDataTCPServer.js: TCP/IP server has received 2970 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:21.530Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:21.600Z SendDataTCPServer.js: TCP/IP server has received 4950 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:21.739Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:21.747Z SendDataTCPServer.js: TCP/IP server has received 6930 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:21.881Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:21.891Z SendDataTCPServer.js: TCP/IP server has received 8910 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:22.032Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:22.040Z SendDataTCPServer.js: TCP/IP server has received 10890 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:22.108Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:22.203Z SendDataTCPServer.js: TCP/IP server has received 12870 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:22.212Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:22.221Z SendDataTCPServer.js: TCP/IP server has received 14850 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:22.232Z SendDataTCPServer.js: TCP/IP server has received 17374 bytes of data
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2016-01-08T17:00:22.234Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:22.268Z SendDataTCPServer.js: TCP/IP server has received 19354 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:22.279Z SendDataTCPServer.js: TCP/IP server has received 21334 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:22.299Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:22.329Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:22.340Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:22.379Z SendDataTCPServer.js: TCP/IP server has received 43114 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:22.395Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:22.428Z SendDataTCPServer.js: TCP/IP server has received 47074 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:22.437Z SendDataTCPServer.js: TCP/IP server has received 49054 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:22.445Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:22.459Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:22.487Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:22.501Z SendDataTCPServer.js: TCP/IP server has received 58954 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:22.510Z SendDataTCPServer.js: TCP/IP server has received 60934 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:22.522Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:22.557Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:22.602Z SendDataTCPServer.js: TCP/IP server has received 66874 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:22.614Z SendDataTCPServer.js: TCP/IP server has received 70000 bytes of data
I/jxcore-log( 3211): 
,W/bt-btif ( 2071): invalid rfc slot id: 9
,W/io.jxcore.node.StreamCopyingThread( 3211): Either failed to read from the output stream or write to the input stream (thread ID: 334, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 3211): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
,W/io.jxcore.node.ConnectionHelper( 3211): onDisconnected: Incoming connection, peer [F8:95:C7:87:3C:51 G4-1] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.StreamCopyingThread( 3211): Exiting thread (ID: 334, name: Receiver)
,I/io.jxcore.node.ConnectionHelper( 3211): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 332
D/io.jxcore.node.IncomingSocketThread( 3211): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3211): doStop: Thread ID: 334
D/io.jxcore.node.IncomingSocketThread( 3211): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3211): doStop: Thread ID: 333
D/io.jxcore.node.IncomingSocketThread( 3211): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 3211): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3211): Either failed to read from the output stream or write to the input stream (thread ID: 333, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3211): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3211): onDisconnected: Incoming connection, peer [F8:95:C7:87:3C:51 G4-1] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.StreamCopyingThread( 3211): Exiting thread (ID: 333, name: Sender)
,D/io.jxcore.node.IncomingSocketThread( 3211): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 3211): closeLocalSocketAndStreams: Closing the localhost socket...
,I/io.jxcore.node.IncomingSocketThread( 3211): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3211): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,I/jxcore-log( 3211): 2016-01-08T17:00:22.753Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3211): 
D/io.jxcore.node.ConnectionHelper( 3211): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.ConnectionHelper( 3211): disconnectOutgoingConnection: Trying to close connection to peer with ID F4:F1:E1:5C:3B:E2
E/io.jxcore.node.ConnectionHelper( 3211): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F4:F1:E1:5C:3B:E2
D/io.jxcore.node.ConnectionHelper( 3211): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3211): disconnectOutgoingConnection: Failed to disconnect (peer ID: F4:F1:E1:5C:3B:E2), either no such connection or failed to close the connection
,I/jxcore-log( 3211): 2016-01-08T17:00:24.050Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:24.051Z SendDataConnector.js: Connect (retry count 1) to peer F4:F1:E1:5C:3B:E2 with availability status: true
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:24.054Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2016-01-08T17:00:24.057Z SendDataConnector.js: do connect now
I/jxcore-log( 3211): 
,I/io.jxcore.node.ConnectionHelper( 3211): connect: Trying to connect to peer with ID F4:F1:E1:5C:3B:E2
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3211): connect: [F4:F1:E1:5C:3B:E2 XT1039]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3211): connect: Trying to start connecting to XT1039 in address F4:F1:E1:5C:3B:E2
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3211): setInsecureRfcommSocketPortNumber: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3211): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3211): onConnecting: XT1039 F4:F1:E1:5C:3B:E2
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3211): connect: Started connecting to XT1039 in address F4:F1:E1:5C:3B:E2
I/io.jxcore.node.ConnectionHelper( 3211): connect: Connection process successfully started (peer ID: F4:F1:E1:5C:3B:E2)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3211): Trying to connect to peer with address F4:F1:E1:5C:3B:E2 (thread ID: 335)
W/BluetoothAdapter( 3211): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2071): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-rfcomm( 2071): rfc_find_lcid_mcb LCID reused LCID:0x4d current:0x0
,W/bt-rfcomm( 2071): RFCOMM_DisconnectInd LCID:0x4d
,W/bt-sdp  ( 2071): process_service_search_attr_rsp
,E/bt-rfcomm( 2071): RFCOMM_CreateConnection - already opened state:2, RFC state:4, MCB state:5
E/bt-btif ( 2071): bta_jv_rfcomm_connect, RFCOMM_CreateConnection failed
,W/bt-btif ( 2071): invalid rfc slot id: 12
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3211): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 335)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3211): Maximum number of allowed retries (0) reached, giving up... (thread ID: 335)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3211): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 335)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3211): shutdownAndRemoveClientThread: Shutting down thread with ID 335
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3211): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [F4:F1:E1:5C:3B:E2 XT1039]
,I/jxcore-log( 3211): 2016-01-08T17:00:24.181Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [F4:F1:E1:5C:3B:E2 XT1039] failed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2016-01-08T17:00:24.181Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [F4:F1:E1:5C:3B:E2 XT1039] failed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2016-01-08T17:00:24.181Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3211): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3211): setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3211): setConnectionTimeout: 15000
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3211): Exiting thread (thread ID: 335)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3211): shutdown (thread ID: 335)
,D/btif_config_util( 2071): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2071): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2071): onReceive
,I/BTConnectionReceiver( 1351): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1351): Bluetooth Device Name: G4-1
,I/jxcore-log( 3211): 2016-01-08T17:00:29.182Z SendDataConnector.js: re-try now : F4:F1:E1:5C:3B:E2
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2016-01-08T17:00:29.183Z SendDataConnector.js: ReStart called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3211): 
,D/io.jxcore.node.ConnectionHelper( 3211): disconnectOutgoingConnection: Trying to close connection to peer with ID F4:F1:E1:5C:3B:E2
,E/io.jxcore.node.ConnectionHelper( 3211): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F4:F1:E1:5C:3B:E2
D/io.jxcore.node.ConnectionHelper( 3211): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3211): disconnectOutgoingConnection: Failed to disconnect (peer ID: F4:F1:E1:5C:3B:E2), either no such connection or failed to close the connection
,I/jxcore-log( 3211): 2016-01-08T17:00:34.193Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2016-01-08T17:00:34.193Z SendDataConnector.js: Connect (retry count 2) to peer F4:F1:E1:5C:3B:E2 with availability status: true
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2016-01-08T17:00:34.194Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2016-01-08T17:00:34.194Z SendDataConnector.js: do connect now
I/jxcore-log( 3211): 
,I/io.jxcore.node.ConnectionHelper( 3211): connect: Trying to connect to peer with ID F4:F1:E1:5C:3B:E2
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3211): connect: [F4:F1:E1:5C:3B:E2 XT1039]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3211): connect: Trying to start connecting to XT1039 in address F4:F1:E1:5C:3B:E2
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3211): setInsecureRfcommSocketPortNumber: Using port 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3211): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3211): onConnecting: XT1039 F4:F1:E1:5C:3B:E2
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3211): connect: Started connecting to XT1039 in address F4:F1:E1:5C:3B:E2
I/io.jxcore.node.ConnectionHelper( 3211): connect: Connection process successfully started (peer ID: F4:F1:E1:5C:3B:E2)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3211): Trying to connect to peer with address F4:F1:E1:5C:3B:E2 (thread ID: 337)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3211): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3211): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2071): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2071): process_service_search_attr_rsp
,E/bt-rfcomm( 2071): RFCOMM_CreateConnection - already opened state:2, RFC state:4, MCB state:5
E/bt-btif ( 2071): bta_jv_rfcomm_connect, RFCOMM_CreateConnection failed
,W/bt-btif ( 2071): invalid rfc slot id: 13
,W/BluetoothAdapter( 3211): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2071): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2071): process_service_search_attr_rsp
,E/bt-rfcomm( 2071): RFCOMM_CreateConnection - already opened state:2, RFC state:4, MCB state:5
E/bt-btif ( 2071): bta_jv_rfcomm_connect, RFCOMM_CreateConnection failed
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3211): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 337)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3211): Maximum number of allowed retries (0) reached, giving up... (thread ID: 337)
,W/bt-btif ( 2071): invalid rfc slot id: 14
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3211): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 337)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3211): shutdownAndRemoveClientThread: Shutting down thread with ID 337
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3211): Exiting thread (thread ID: 337)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3211): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [F4:F1:E1:5C:3B:E2 XT1039]
I/jxcore-log( 3211): 2016-01-08T17:00:34.457Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [F4:F1:E1:5C:3B:E2 XT1039] failed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2016-01-08T17:00:34.458Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [F4:F1:E1:5C:3B:E2 XT1039] failed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2016-01-08T17:00:34.458Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3211): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3211): setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3211): setConnectionTimeout: 15000
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3211): shutdown (thread ID: 337)
,I/io.jxcore.node.ConnectionHelper( 3211): Powering the BLE discovery back up
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3211): setAdvertiseMode: 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3211): applySettings: Advertise mode: 1, advertise TX power level: 1, scan mode: 0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3211): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3211): setScanSettings: Mode: 0, report delay in milliseconds: 0, scan result type: 0
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3211): setScanMode: 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3211): applySettings: Advertise mode: 1, advertise TX power level: 1, scan mode: 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3211): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3211): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,I/jxcore-log( 3211): 2016-01-08T17:00:39.459Z SendDataConnector.js: re-try now : F4:F1:E1:5C:3B:E2
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2016-01-08T17:00:39.459Z SendDataConnector.js: ReStart called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3211): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3211): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3211): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3211): setState: RESTARTING
,I/wpa_supplicant(  988): P2P-FIND-STOPPED 
,I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant(  988): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3211): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3211): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3211): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3211): onP2pDeviceListChanged: 0 device(s) discovered
,D/io.jxcore.node.ConnectionHelper( 3211): disconnectOutgoingConnection: Trying to close connection to peer with ID F4:F1:E1:5C:3B:E2
E/io.jxcore.node.ConnectionHelper( 3211): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F4:F1:E1:5C:3B:E2
D/io.jxcore.node.ConnectionHelper( 3211): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3211): disconnectOutgoingConnection: Failed to disconnect (peer ID: F4:F1:E1:5C:3B:E2), either no such connection or failed to close the connection
I/jxcore-log( 3211): 2016-01-08T17:00:44.463Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2016-01-08T17:00:44.464Z SendDataConnector.js: Connect (retry count 3) to peer F4:F1:E1:5C:3B:E2 with availability status: true
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2016-01-08T17:00:44.464Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:44.465Z SendDataConnector.js: do connect now
I/jxcore-log( 3211): 
,I/io.jxcore.node.ConnectionHelper( 3211): connect: Trying to connect to peer with ID F4:F1:E1:5C:3B:E2
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3211): connect: [F4:F1:E1:5C:3B:E2 XT1039]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3211): connect: Trying to start connecting to XT1039 in address F4:F1:E1:5C:3B:E2
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3211): setInsecureRfcommSocketPortNumber: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3211): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3211): onConnecting: XT1039 F4:F1:E1:5C:3B:E2
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3211): connect: Started connecting to XT1039 in address F4:F1:E1:5C:3B:E2
I/io.jxcore.node.ConnectionHelper( 3211): connect: Connection process successfully started (peer ID: F4:F1:E1:5C:3B:E2)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3211): Trying to connect to peer with address F4:F1:E1:5C:3B:E2 (thread ID: 339)
W/BluetoothAdapter( 3211): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2071): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2071): process_service_search_attr_rsp
,E/bt-rfcomm( 2071): RFCOMM_CreateConnection - already opened state:2, RFC state:4, MCB state:5
E/bt-btif ( 2071): bta_jv_rfcomm_connect, RFCOMM_CreateConnection failed
,W/bt-btif ( 2071): invalid rfc slot id: 15
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3211): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 339)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3211): Maximum number of allowed retries (0) reached, giving up... (thread ID: 339)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3211): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 339)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3211): shutdownAndRemoveClientThread: Shutting down thread with ID 339
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3211): Exiting thread (thread ID: 339)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3211): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [F4:F1:E1:5C:3B:E2 XT1039]
,I/jxcore-log( 3211): 2016-01-08T17:00:45.329Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [F4:F1:E1:5C:3B:E2 XT1039] failed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2016-01-08T17:00:45.330Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [F4:F1:E1:5C:3B:E2 XT1039] failed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2016-01-08T17:00:45.330Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3211): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3211): setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3211): setConnectionTimeout: 15000
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3211): shutdown (thread ID: 339)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3211): Start timer timeout, starting now...
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3211): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3211): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3211): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  988): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3211): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3211): restart: Restarting...
,D/WifiP2pManager( 3211): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3211): Service request added successfully
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3211): Service discovery started successfully
,I/jxcore-log( 3211): 2016-01-08T17:00:50.332Z SendDataConnector.js: re-try now : F4:F1:E1:5C:3B:E2
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2016-01-08T17:00:50.333Z SendDataConnector.js: ReStart called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3211): 
,W/bt-btif ( 2071): info:x10
,D/        ( 2071): remote version info [90:e7:c4:f6:69:77]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2071): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3211): timeout now
I/jxcore-log( 3211): 
I/jxcore-log( 3211): weAreDoneNow, resultArray.length: 1
I/jxcore-log( 3211): 
I/jxcore-log( 3211): sendReportNow
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): done, now sending data to server
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:51.461Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2016-01-08T17:00:51.462Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 3211): 
D/io.jxcore.node.ConnectionHelper( 3211): disconnectOutgoingConnection: Trying to close connection to peer with ID F4:F1:E1:5C:3B:E2
E/io.jxcore.node.ConnectionHelper( 3211): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F4:F1:E1:5C:3B:E2
D/io.jxcore.node.ConnectionHelper( 3211): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3211): disconnectOutgoingConnection: Failed to disconnect (peer ID: F4:F1:E1:5C:3B:E2), either no such connection or failed to close the connection
,I/jxcore-log( 3211): 2016-01-08T17:00:51.473Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3211): 
,I/BluetoothBondStateMachine( 2071): bondStateChangeCallback: Status: 0 Address: 90:E7:C4:F6:69:77 newState: 1
E/bt-btif ( 2071): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2071): Bond State Change Intent:90:E7:C4:F6:69:77 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2071): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2071): bondStateChangeCallback: Status: 0 Address: 90:E7:C4:F6:69:77 newState: 0
,D/BluetoothAdapterProperties( 2071): Failed to remove device: 90:E7:C4:F6:69:77
,I/BluetoothBondStateMachine( 2071): Bond State Change Intent:90:E7:C4:F6:69:77 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2071): StableState(): Entering Off State
,W/bt-btif ( 2071): new conn_srvc id:26, app_id:255
W/bt-btif ( 2071): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2071): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3211): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3211): Incoming connection initialized (thread ID: 341)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3211): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3211): Entering thread (ID: 341)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3211): onBytesRead: Read 70 bytes successfully (thread ID: 341)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3211): Got valid identity from [90:E7:C4:F6:69:77 HTC One M8s]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3211): onBytesWritten: 66 bytes successfully written (thread ID: 341)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3211): removeThreadFromList: Removing thread with ID 341
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3211): Handshake thread disposed (thread ID: 341)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3211): onIncomingConnectionConnected: [90:E7:C4:F6:69:77 HTC One M8s]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3211): Exiting thread (ID: 341)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3211): onConnected: [90:E7:C4:F6:69:77 HTC One M8s]
I/io.jxcore.node.ConnectionHelper( 3211): onConnected: Incoming connection to peer [90:E7:C4:F6:69:77 HTC One M8s]
,D/io.jxcore.node.ConnectionHelper( 3211): hasConnection: No connection with peer with ID 90:E7:C4:F6:69:77
D/io.jxcore.node.ConnectionHelper( 3211): notifyPeerAvailability: Peer [90:E7:C4:F6:69:77 HTC One M8s] is available
,I/io.jxcore.node.ConnectionHelper( 3211): onConnected: Incoming socket thread, for peer [90:E7:C4:F6:69:77 HTC One M8s], created successfully
D/io.jxcore.node.ConnectionHelper( 3211): onConnected: The total number of connections is now 1
,D/io.jxcore.node.IncomingSocketThread( 3211): Entering thread (ID: 342)
,I/jxcore-log( 3211): 2016-01-08T17:00:52.822Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3211): 
,I/io.jxcore.node.IncomingSocketThread( 3211): Local host address: localhost/127.0.0.1, port: 37026
D/io.jxcore.node.IncomingSocketThread( 3211): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3211): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3211): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3211): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3211): Exiting thread (ID: 342)
,D/io.jxcore.node.StreamCopyingThread( 3211): Entering thread (ID: 344, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3211): Entering thread (ID: 343, name: Sender)
,I/jxcore-log( 3211): 2016-01-08T17:00:53.843Z SendDataTCPServer.js: TCP/IP server has received 990 bytes of data
I/jxcore-log( 3211): 
I/io.jxcore.node.ConnectionHelper( 3211): lowerBleDiscoveryPowerAndStartResetTimer: Lowering the power settings
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3211): setAdvertiseMode: 0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3211): applySettings: Advertise mode: 0, advertise TX power level: 1, scan mode: 1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3211): setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3211): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3211): setScanMode: 0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 3211): applySettings: Advertise mode: 0, advertise TX power level: 1, scan mode: 0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3211): setAdvertiseSettings: Mode: 0, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3211): setScanSettings: Mode: 0, report delay in milliseconds: 0, scan result type: 0
,I/jxcore-log( 3211): 2016-01-08T17:00:53.862Z SendDataTCPServer.js: TCP/IP server has received 2970 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:53.870Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:53.872Z SendDataTCPServer.js: TCP/IP server has received 4950 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:53.964Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:53.976Z SendDataTCPServer.js: TCP/IP server has received 6930 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:54.079Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:54.130Z SendDataTCPServer.js: TCP/IP server has received 8910 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:54.137Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:54.150Z SendDataTCPServer.js: TCP/IP server has received 10890 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:54.160Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:54.220Z SendDataTCPServer.js: TCP/IP server has received 12870 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:54.230Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:54.259Z SendDataTCPServer.js: TCP/IP server has received 14850 bytes of data
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2016-01-08T17:00:54.262Z SendDataTCPServer.js: TCP/IP server has received 16830 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:54.313Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:54.323Z SendDataTCPServer.js: TCP/IP server has received 18810 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:54.336Z SendDataTCPServer.js: TCP/IP server has received 20790 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:54.402Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:54.437Z SendDataTCPServer.js: TCP/IP server has received 24750 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:54.532Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:54.630Z SendDataTCPServer.js: TCP/IP server has received 26730 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:54.639Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:54.728Z SendDataTCPServer.js: TCP/IP server has received 28710 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:54.735Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:54.793Z SendDataTCPServer.js: TCP/IP server has received 30690 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:54.805Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:54.837Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:54.880Z SendDataTCPServer.js: TCP/IP server has received 34650 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:54.888Z SendDataTCPServer.js: TCP/IP server has received 35640 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:54.901Z SendDataTCPServer.js: TCP/IP server has received 36630 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:54.911Z SendDataTCPServer.js: TCP/IP server has received 37620 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:54.980Z SendDataTCPServer.js: TCP/IP server has received 38610 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:54.989Z SendDataTCPServer.js: TCP/IP server has received 39600 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:54.996Z SendDataTCPServer.js: TCP/IP server has received 40590 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:55.009Z SendDataTCPServer.js: TCP/IP server has received 41580 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:55.110Z SendDataTCPServer.js: TCP/IP server has received 42570 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:55.205Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:55.260Z SendDataTCPServer.js: TCP/IP server has received 44550 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:55.269Z SendDataTCPServer.js: TCP/IP server has received 45540 bytes of data
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2016-01-08T17:00:55.271Z SendDataTCPServer.js: TCP/IP server has received 46530 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:55.280Z SendDataTCPServer.js: TCP/IP server has received 47520 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:55.286Z SendDataTCPServer.js: TCP/IP server has received 48510 bytes of data
I/jxcore-log( 3211): 
,D/io.jxcore.node.ConnectionHelper( 3211): disconnectOutgoingConnection: Trying to close connection to peer with ID F4:F1:E1:5C:3B:E2
E/io.jxcore.node.ConnectionHelper( 3211): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F4:F1:E1:5C:3B:E2
D/io.jxcore.node.ConnectionHelper( 3211): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3211): disconnectOutgoingConnection: Failed to disconnect (peer ID: F4:F1:E1:5C:3B:E2), either no such connection or failed to close the connection
I/jxcore-log( 3211): 2016-01-08T17:00:55.339Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2016-01-08T17:00:55.340Z SendDataConnector.js: Connect (retry count 4) to peer F4:F1:E1:5C:3B:E2 with availability status: true
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2016-01-08T17:00:55.340Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2016-01-08T17:00:55.341Z SendDataConnector.js: do connect now
I/jxcore-log( 3211): 
I/io.jxcore.node.ConnectionHelper( 3211): connect: Trying to connect to peer with ID F4:F1:E1:5C:3B:E2
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3211): connect: [F4:F1:E1:5C:3B:E2 XT1039]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3211): connect: Trying to start connecting to XT1039 in address F4:F1:E1:5C:3B:E2
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3211): setInsecureRfcommSocketPortNumber: Using port 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3211): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3211): onConnecting: XT1039 F4:F1:E1:5C:3B:E2
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3211): connect: Started connecting to XT1039 in address F4:F1:E1:5C:3B:E2
I/io.jxcore.node.ConnectionHelper( 3211): connect: Connection process successfully started (peer ID: F4:F1:E1:5C:3B:E2)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3211): Trying to connect to peer with address F4:F1:E1:5C:3B:E2 (thread ID: 345)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3211): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3211): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2071): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/jxcore-log( 3211): 2016-01-08T17:00:55.384Z SendDataTCPServer.js: TCP/IP server has received 49500 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:55.396Z SendDataTCPServer.js: TCP/IP server has received 50490 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:55.580Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:55.619Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:55.652Z SendDataTCPServer.js: TCP/IP server has received 54450 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:55.659Z SendDataTCPServer.js: TCP/IP server has received 55440 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:55.669Z SendDataTCPServer.js: TCP/IP server has received 56430 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:55.673Z SendDataTCPServer.js: TCP/IP server has received 57420 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:55.682Z SendDataTCPServer.js: TCP/IP server has received 58410 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:55.690Z SendDataTCPServer.js: TCP/IP server has received 59400 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:55.742Z SendDataTCPServer.js: TCP/IP server has received 60390 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:55.772Z SendDataTCPServer.js: TCP/IP server has received 61380 bytes of data
I/jxcore-log( 3211): 
,W/bt-sdp  ( 2071): process_service_search_attr_rsp
,E/bt-rfcomm( 2071): RFCOMM_CreateConnection - already opened state:2, RFC state:4, MCB state:5
E/bt-btif ( 2071): bta_jv_rfcomm_connect, RFCOMM_CreateConnection failed
,W/BluetoothAdapter( 3211): getBluetoothService() called with no BluetoothManagerCallback
W/bt-btif ( 2071): invalid rfc slot id: 17
,D/BTIF_SOCK( 2071): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/jxcore-log( 3211): 2016-01-08T17:00:55.843Z SendDataTCPServer.js: TCP/IP server has received 62370 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:55.849Z SendDataTCPServer.js: TCP/IP server has received 63360 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:55.862Z SendDataTCPServer.js: TCP/IP server has received 64350 bytes of data
I/jxcore-log( 3211): 
,W/bt-sdp  ( 2071): process_service_search_attr_rsp
,E/bt-rfcomm( 2071): RFCOMM_CreateConnection - already opened state:2, RFC state:4, MCB state:5
E/bt-btif ( 2071): bta_jv_rfcomm_connect, RFCOMM_CreateConnection failed
,W/bt-btif ( 2071): invalid rfc slot id: 18
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3211): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 345)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3211): Maximum number of allowed retries (0) reached, giving up... (thread ID: 345)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3211): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 345)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3211): shutdownAndRemoveClientThread: Shutting down thread with ID 345
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3211): Exiting thread (thread ID: 345)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3211): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [F4:F1:E1:5C:3B:E2 XT1039]
I/jxcore-log( 3211): 2016-01-08T17:00:55.922Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [F4:F1:E1:5C:3B:E2 XT1039] failed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2016-01-08T17:00:55.923Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [F4:F1:E1:5C:3B:E2 XT1039] failed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3211): 
I/jxcore-log( 3211): oneRoundDownNow
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:55.923Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3211): 
D/io.jxcore.node.ConnectionHelper( 3211): disconnectOutgoingConnection: Trying to close connection to peer with ID F4:F1:E1:5C:3B:E2
E/io.jxcore.node.ConnectionHelper( 3211): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F4:F1:E1:5C:3B:E2
D/io.jxcore.node.ConnectionHelper( 3211): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3211): disconnectOutgoingConnection: Failed to disconnect (peer ID: F4:F1:E1:5C:3B:E2), either no such connection or failed to close the connection
I/jxcore-log( 3211): 2016-01-08T17:00:55.924Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3211): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3211): setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3211): setConnectionTimeout: 15000
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3211): shutdown (thread ID: 345)
,I/jxcore-log( 3211): 2016-01-08T17:00:55.954Z SendDataTCPServer.js: TCP/IP server has received 65340 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:55.960Z SendDataTCPServer.js: TCP/IP server has received 66330 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:56.060Z SendDataTCPServer.js: TCP/IP server has received 67320 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:56.150Z SendDataTCPServer.js: TCP/IP server has received 68310 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:56.159Z SendDataTCPServer.js: TCP/IP server has received 69300 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:56.163Z SendDataTCPServer.js: TCP/IP server has received 70290 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:56.233Z SendDataTCPServer.js: TCP/IP server has received 71280 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:56.268Z SendDataTCPServer.js: TCP/IP server has received 72270 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:56.521Z SendDataTCPServer.js: TCP/IP server has received 73260 bytes of data
I/jxcore-log( 3211): 
,D/btif_config_util( 2071): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3211): 2016-01-08T17:00:57.006Z SendDataTCPServer.js: TCP/IP server has received 74250 bytes of data
I/jxcore-log( 3211): 
I/jxcore-log( 3211): 2016-01-08T17:00:57.008Z SendDataTCPServer.js: TCP/IP server has received 75240 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:57.063Z SendDataTCPServer.js: TCP/IP server has received 76230 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:57.075Z SendDataTCPServer.js: TCP/IP server has received 77220 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:57.188Z SendDataTCPServer.js: TCP/IP server has received 78210 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:57.200Z SendDataTCPServer.js: TCP/IP server has received 79200 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:57.386Z SendDataTCPServer.js: TCP/IP server has received 80190 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:57.399Z SendDataTCPServer.js: TCP/IP server has received 81180 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:57.493Z SendDataTCPServer.js: TCP/IP server has received 82170 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:57.591Z SendDataTCPServer.js: TCP/IP server has received 83160 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:57.600Z SendDataTCPServer.js: TCP/IP server has received 84150 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:57.672Z SendDataTCPServer.js: TCP/IP server has received 85140 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:57.679Z SendDataTCPServer.js: TCP/IP server has received 86130 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:57.743Z SendDataTCPServer.js: TCP/IP server has received 87120 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:57.756Z SendDataTCPServer.js: TCP/IP server has received 88110 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:57.767Z SendDataTCPServer.js: TCP/IP server has received 89100 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:57.776Z SendDataTCPServer.js: TCP/IP server has received 90090 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:57.790Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:57.955Z SendDataTCPServer.js: TCP/IP server has received 92070 bytes of data
I/jxcore-log( 3211): 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3211): 2016-01-08T17:00:58.229Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:58.246Z SendDataTCPServer.js: TCP/IP server has received 94050 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:58.254Z SendDataTCPServer.js: TCP/IP server has received 95040 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:58.444Z SendDataTCPServer.js: TCP/IP server has received 96030 bytes of data
I/jxcore-log( 3211): 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3211): 2016-01-08T17:00:58.453Z SendDataTCPServer.js: TCP/IP server has received 97020 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:58.744Z SendDataTCPServer.js: TCP/IP server has received 98010 bytes of data
I/jxcore-log( 3211): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3211): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC One M8s","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3211): onDnsSdServiceAvailable: Resolved peer properties: [90:E7:C4:F6:69:77 HTC One M8s]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3211): onServiceDiscovered: [90:E7:C4:F6:69:77 HTC One M8s]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC One M8s]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC One M8s], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): modifyListOfDiscoveredPeers: Adding a new peer: [90:E7:C4:F6:69:77 HTC One M8s]
I/io.jxcore.node.ConnectionHelper( 3211): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC One M8s], Bluetooth address: 90:E7:C4:F6:69:77, device name: , device address: 92:e7:c4:e6:4c:f8
W/io.jxcore.node.ConnectionHelper( 3211): modifyListOfDiscoveredPeers: Peer [90:E7:C4:F6:69:77 HTC One M8s] already in the list, will not add again
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3211): 2016-01-08T17:00:59.475Z SendDataTCPServer.js: TCP/IP server has received 99000 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:59.600Z SendDataTCPServer.js: TCP/IP server has received 99990 bytes of data
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:00:59.885Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3211): 
,W/bt-btif ( 2071): invalid rfc slot id: 11
,W/io.jxcore.node.StreamCopyingThread( 3211): Either failed to read from the output stream or write to the input stream (thread ID: 344, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.IncomingSocketThread( 3211): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3211): onDisconnected: Incoming connection, peer [90:E7:C4:F6:69:77 HTC One M8s] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.StreamCopyingThread( 3211): Exiting thread (ID: 344, name: Receiver)
,I/io.jxcore.node.ConnectionHelper( 3211): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 342
D/io.jxcore.node.IncomingSocketThread( 3211): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3211): doStop: Thread ID: 344
D/io.jxcore.node.IncomingSocketThread( 3211): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3211): doStop: Thread ID: 343
D/io.jxcore.node.IncomingSocketThread( 3211): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 3211): closeLocalSocketAndStreams: Closing the local input stream...
,W/bt-rfcomm( 2071): rfc_find_lcid_mcb LCID reused LCID:0x43 current:0x0
,W/bt-rfcomm( 2071): RFCOMM_DisconnectInd LCID:0x43
,W/io.jxcore.node.StreamCopyingThread( 3211): Either failed to read from the output stream or write to the input stream (thread ID: 343, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3211): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3211): onDisconnected: Incoming connection, peer [90:E7:C4:F6:69:77 HTC One M8s] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.StreamCopyingThread( 3211): Exiting thread (ID: 343, name: Sender)
,D/io.jxcore.node.IncomingSocketThread( 3211): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 3211): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3211): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3211): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
I/jxcore-log( 3211): 2016-01-08T17:01:00.091Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3211): 
D/io.jxcore.node.ConnectionHelper( 3211): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,E/bt-btm  ( 2071): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2071): onReceive
,I/BTConnectionReceiver( 1351): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=90:E7:C4:F6:69:77, alias=null, name=HTC One M8s, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1351): Bluetooth Device Name: HTC One M8s
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3211): teardown
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): testSendData stopped
I/jxcore-log( 3211): 
I/io.jxcore.node.ConnectionHelper( 3211): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3211): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3211): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3211): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3211): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3211): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3211): onServerStopped
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3211): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3211): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): stop: Stopping peer discovery...
,D/BluetoothLeScanner( 3211): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3211): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3211): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3211): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3211): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3211): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3211): setState: NOT_STARTED
,I/jxcore-log( 3211): StopBroadcasting went ok
I/jxcore-log( 3211): 
,I/jxcore-log( 3211): 2016-01-08T17:01:11.321Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
I/jxcore-log( 3211): 
I/chromium( 3211): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/io.jxcore.node.ConnectionHelper( 3211): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3211): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 3211): ****TEST TOOK:  ms ****
I/jxcore-log( 3211): 
I/jxcore-log( 3211): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3211): 
,D/AndroidRuntime( 3680): 
D/AndroidRuntime( 3680): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 3680): CheckJNI is OFF
,D/AndroidRuntime( 3680): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  733): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  733): Killing 3211:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
,I/WindowState(  733): WIN DEATH: Window{c18acb0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  733): Client connection lost with reason: 4
,W/PackageSettings(  733): Skipping PackageSetting{2d72e9cd com.example.hello/10278} due to missing metadata
,I/ActivityManager(  733):   Force finishing activity ActivityRecord{2a8ef77c u0 com.test.thalitest/.MainActivity t214}
,W/ActivityManager(  733): Spurious death for ProcessRecord{d4db18a 3211:com.test.thalitest/u0a270}, curProc for 3211: null
I/ActivityManager(  733): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
I/ActivityManager(  733):   Force finishing activity ActivityRecord{2a8ef77c u0 com.test.thalitest/.MainActivity t214 f}
W/ActivityManager(  733): Duplicate finish request for ActivityRecord{2a8ef77c u0 com.test.thalitest/.MainActivity t214 f}
,I/art     ( 1351): Explicit concurrent mark sweep GC freed 32116(1759KB) AllocSpace objects, 5(103KB) LOS objects, 24% free, 18MB/25MB, paused 285us total 22.922ms
,I/art     ( 1646): Explicit concurrent mark sweep GC freed 34033(2MB) AllocSpace objects, 7(112KB) LOS objects, 24% free, 22MB/30MB, paused 472us total 45.318ms
,W/GeofencerStateMachine( 1568): Ignoring removeGeofence because network location is disabled.
,I/InputReader(  733): Reconfiguring input devices.  changes=0x00000010
,I/Keyboard.Facilitator( 1089): resetDictionaries() : en_US
,I/art     ( 1284): Explicit concurrent mark sweep GC freed 3958(294KB) AllocSpace objects, 1(126KB) LOS objects, 38% free, 25MB/41MB, paused 223us total 20.196ms
,I/Adreno-EGL(  943): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
I/OpenGLRenderer(  943): Initialized EGL, version 1.4
,I/UpdateIcingCorporaServi( 1351): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
D/OpenGLRenderer(  943): Enabling debug mode 0
,W/Launcher( 1284): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@120b98ce new=com.google.android.velvet.VelvetApplication@120b98ce
I/Keyboard.Facilitator.DecoderInitializer( 1089): run()
,I/ActivityManager(  733): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3723 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
I/art     (  733): Explicit concurrent mark sweep GC freed 38342(1969KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 1.319ms total 107.201ms
,I/art     (  733): WaitForGcToComplete blocked for 25.194ms for cause Explicit
,I/Decoder ( 1089): createOrResetDecoder
,D/VoicemailCleanupService( 2778): Cleaning up data for package: com.test.thalitest
,I/ConfigService( 1568): onCreate
,W/InputMethodManagerService(  733): Got RemoteException sending setActive(false) notification to pid 3211 uid 10270
,I/Keyboard.Facilitator( 1089): onFinishInput()
,W/ContextImpl( 3723): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1089): run()
,D/BackupManagerService(  733): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  733): Receieved: android.intent.action.PACKAGE_REMOVED
,D/ChimeraCfgMgr( 1646): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1646): Module APK com.google.android.play.games already loaded
,D/TaskPersister(  733): removeObsoleteFile: deleting file=214_task.xml
D/ChimeraCfgMgr( 1646): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1646): Module APK com.google.android.play.games already loaded
,E/NetworkScheduler.SchedulerReceiver( 1568): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1568): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,D/PackageBroadcastService( 1646): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
I/UpdateIcingCorporaServi( 1351): UpdateCorporaTask done [took 150 ms] updated apps [took 150 ms] 
,D/AccountUtils( 1646): Clearing selected account for com.test.thalitest
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1089): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1089): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1089): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1089): run() : Missing File = Contacts.dict
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1089): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1089): run() : Loaded File = UserHistory.en_US.dict
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1089): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1089): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1089): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1089): run()
,I/Keyboard.Facilitator.RecurringTaskScheduler( 1089): run()
,I/StatsUtilsManager( 1089): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1089): shouldRecordStats() = Too Soon
,I/LocationSettingsChecker( 1646): Removing dialog suppression flag for package com.test.thalitest
,D/gH_CompatibleDatabase( 1646): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1646): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 1646): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1646): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/gH_CompatibleDatabase( 1646): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1646): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1646): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,I/art     (  733): Explicit concurrent mark sweep GC freed 11080(535KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 1.093ms total 173.080ms
,D/gH_CompatibleDatabase( 1646): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1646): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 1646): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
I/ActivityManager(  733): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3753 uid=10039 gids={50039, 9997} abi=armeabi-v7a
D/gH_CompatibleDatabase( 1646): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1646): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1646): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/Launcher( 1284): Deferring update until onResume
,W/ResourcesManager( 1284): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/GMPM-SVC( 1646): App measurement is starting up, version: 8489
I/GMPM-SVC( 1646): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,W/BaseAppContext( 1646): Using Auth Proxy for data requests.
W/ResourcesManager( 1284): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/BaseAppContext( 1646): Using Auth Proxy for data requests.
,I/Launcher( 1284): Deferring update until onResume
,I/Icing   ( 1646): doRemovePackageData com.test.thalitest
,D/AndroidRuntime( 3680): Shutting down VM
,I/ActivityManager(  733): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3779 uid=10007 gids={50007, 9997, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  733): Killing 1952:com.google.android.calendar/u0a31 (adj 15): empty #17
,W/libprocessgroup(  733): failed to open /acct/uid_10031/pid_1952/cgroup.procs: No such file or directory
,I/ActivityManager(  733): Killing 1987:com.android.providers.calendar/u0a2 (adj 15): empty #17
,W/libprocessgroup(  733): failed to open /acct/uid_10002/pid_1987/cgroup.procs: No such file or directory
,D/ExternalStorage( 3779): After updating volumes, found 1 active roots
,W/ResourcesManager( 3121): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3121): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/Documents( 3753): Update found 7 roots in 385ms
,D/Documents( 3753): Update found 7 roots in 128ms

```
