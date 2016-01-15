#### Test 56204092c98eeae_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
I/GAv4    ( 3163): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3163):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3163):   adb logcat -s GAv4
W/GAv4    ( 3163): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3163): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3163): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 3163): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
D/Finsky  ( 2643): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
W/ResourcesManager( 3163): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3163): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  760): Killing 2061:com.google.android.deskclock/u0a38 (adj 15): empty #17
V/JNIHelp ( 3163): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/System  ( 3163): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3163): Installed default security provider GmsCore_OpenSSL
W/libprocessgroup(  760): failed to open /acct/uid_10038/pid_2061/cgroup.procs: No such file or directory
V/GLSActivity( 1601): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 1640): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/Icing   ( 1640): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/Icing   ( 1640): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1640): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
,I/ActivityManager(  760): Killing 2603:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
W/libprocessgroup(  760): failed to open /acct/uid_10069/pid_2603/cgroup.procs: No such file or directory
D/AndroidRuntime( 3221): 
D/AndroidRuntime( 3221): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3221): CheckJNI is OFF
D/AndroidRuntime( 3221): Calling main entry com.android.commands.am.Am
I/ActivityManager(  760): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  760): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3242 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3221): Shutting down VM
V/ActivityManager(  760): Display changed displayId=0
I/WebViewFactory( 3242): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3242): Time to load native libraries: 1 ms (timestamps 2523-2524)
I/LibraryLoader( 3242): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3242): Binding Chromium to main looper Looper (main, tid 1) {299df117}
I/LibraryLoader( 3242): Expected native library version number "",actual native library version number ""
I/chromium( 3242): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3242): Initializing chromium process, singleProcess=true
W/art     ( 3242): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3242): ApplicationContext is null in ApplicationStatus
W/chromium( 3242): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3242): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3242): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3242): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  760): Message: 20
D/BluetoothManagerService(  760): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@10cfb86f:true
,W/art     ( 3242): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3242): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3242): CordovaWebView is running on device made by: LGE
,W/art     ( 3242): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3242): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3242): Render dirty regions requested: true
,D/Atlas   ( 3242): Validating map...
,W/chromium( 3242): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3242): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3242): Enabling debug mode 0
,I/Keyboard.Facilitator( 1107): onFinishInput()
,W/IInputConnectionWrapper( 3242): showStatusIcon on inactive InputConnection
,I/ActivityManager(  760): Displayed com.test.thalitest/.MainActivity: +423ms (total +60s860ms)
,W/BindingManager( 3242): Cannot call determinedVisibility() - never saw a connection for the pid: 3242
,D/JsMessageQueue( 3242): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3242): JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1258391936
D/JX-Cordova( 3242): jxcore cordova android initializing
,W/jxcore-log( 3242): Initializing JXcore engine
W/jxcore-log( 3242): JXcore engine is ready
,W/jxcore-log( 3242): Starting JXcore engine
,W/.test.thalitest( 3242): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[8410]" dev="sockfs" ino=8410 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3242): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 3242): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[7741]" dev="sockfs" ino=7741 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3242): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[20462]" dev="sockfs" ino=20462 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3242): Platform android
W/jxcore-log( 3242): 
,W/jxcore-log( 3242): Process ARCH arm
W/jxcore-log( 3242): 
,I/jxcore-log( 3242): JXcore Cordova bridge is ready!
I/jxcore-log( 3242): 
W/jxcore-log( 3242): JXcore engine is started
I/Choreographer( 3242): Skipped 120 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3242): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3242): Toggling radios to true
I/jxcore-log( 3242): 
,D/BluetoothAdapter( 3242): enable(): BT is already enabled..!
,D/WifiService(  760): New client listening to asynchronous messages
,D/WifiService(  760): setWifiEnabled: true pid=3242, uid=10270
E/WifiService(  760): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3242): Radios toggled
I/jxcore-log( 3242): 
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 3242): Got Device Bluetooth address: 34:FC:EF:11:AE:67
I/jxcore-log( 3242): 
,I/jxcore-log( 3242): Perf Test app loaded loaded
I/jxcore-log( 3242): 
,I/wpa_supplicant(  990): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  760): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  760): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/native  (  760): do suspend true
,I/Choreographer( 3242): Skipped 67 frames!  The application may be doing too much work on its main thread.
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,I/jxcore-log( 3242): check test folder
I/jxcore-log( 3242): 
I/jxcore-log( 3242): found test : ./testFindPeers.js
I/jxcore-log( 3242): 
,V/NativeCrypto( 1601): Read error: ssl=0xb3b31600: I/O error during system call, Connection timed out
,D/ConnectivityService(  760): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,D/ConnectivityService(  760): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,E/WifiConfigStore(  760): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiStateMachine(  760): Start Disconnecting Watchdog 1
,V/NativeCrypto( 1601): SSL shutdown failed: ssl=0xb3b31600: I/O error during system call, Broken pipe
,D/ConnectivityService(  760): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): ValidatedState{ when=-1ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): DefaultState{ when=-1ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Checking http://clients3.google.com/generate_204 on <unknown ssid>
I/wpa_supplicant(  990): wlan0: CTRL-EVENT-SCAN-STARTED 
,E/native  (  760): do suspend true
,I/jxcore-log( 3242): found test : ./testSendData.js
I/jxcore-log( 3242): 
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,D/ConnectivityService(  760): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityManager.CallbackHandler(  907): CM callback handler got msg 524292
D/Nat464Xlat(  760): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  760): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Disconnected - quitting
D/ConnectivityManager.CallbackHandler( 1640): CM callback handler got msg 524292
,D/ConnectivityService(  760): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1252): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/ConnectivityService(  760): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,D/WifiNetworkAgent(  760): NetworkAgent: NetworkAgent channel lost
,I/chromium( 3242): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/wpa_supplicant(  990): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant(  990): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant(  990): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant(  990): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  760): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  760): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  760): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiConfigStore(  760): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  179): Setting iface cfg
,E/WifiStateMachine(  760): Start Dhcp Watchdog 2
,E/native  (  760): do suspend false
,E/WifiStateMachine(  760): scanCount==0 - aborting
,I/dhcpcd  ( 3341): version 5.5.6 starting
,E/dhcpcd  ( 3341): get_duid: Read-only file system
,I/dhcpcd  ( 3341): wlan0: rebinding lease of 192.168.1.114
,I/dhcpcd  ( 3341): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3341): wlan0: leased 192.168.1.114 for 86400 seconds
,E/native  (  760): do suspend true
,D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  760): MasterInitialState.processMessage what=3
,D/Tethering(  760): MasterInitialState.processMessage what=3
,D/ConnectivityService(  760): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  760): Adding iface wlan0 to network 101
,E/WifiStateMachine(  760): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,V/MusicLeanback( 2747): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
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
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/CSLegacyTypeTracker(  760): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  760): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::5255:27ff:fef0:fd0b/64,192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  760): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  907): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1640): CM callback handler got msg 524290
,E/GpsLocationProvider(  760): No APN found to select.
,I/SystemUpdateService( 1640): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1640): onCreate
,D/SystemUpdateService( 1640): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1640): active receiver: enabled
,E/GpsLocationProvider(  760): No APN found to select.
,I/SystemUpdateService( 1640): showing system update notification
,I/ActivityManager(  760): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3392 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ValidateNoPeople(  760): skipping global notification
,V/SystemUpdateService( 1640): retry (wakeup: false) in 3599940 ms
,D/SystemUpdateService( 1640): onDestroy
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 15 Jan 2016 18:44:37 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452883477014], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452883476974]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Validated
D/ConnectivityService(  760): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  760): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  760): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  760): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler(  907): CM callback handler got msg 524290
D/ConnectivityManager.CallbackHandler( 1640): CM callback handler got msg 524290
D/TelephonyNetworkFactory( 1252): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/GAv4    ( 3392): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3392):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3392):   adb logcat -s GAv4
,W/GAv4    ( 3392): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3392): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3392): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 3392): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3392): Time to load native libraries: 3 ms (timestamps 9778-9781)
,I/LibraryLoader( 3392): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3392): Binding Chromium to main looper Looper (main, tid 1) {eaf9e71}
I/LibraryLoader( 3392): Expected native library version number "",actual native library version number ""
I/chromium( 3392): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3392): Initializing chromium process, singleProcess=true
,W/art     ( 3392): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3392): ApplicationContext is null in ApplicationStatus
,W/chromium( 3392): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3392): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3392): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3392): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/AudioManagerAndroid( 3392): Requires BLUETOOTH permission
,I/NSApplication( 3392): Starting up...
,I/ActivityManager(  760): Killing 2542:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10045/pid_2542/cgroup.procs: No such file or directory
,V/MusicLeanback( 2747): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1640): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1640): onCreate
,D/SystemUpdateService( 1640): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1640): active receiver: enabled
,I/SystemUpdateService( 1640): showing system update notification
,I/ValidateNoPeople(  760): skipping global notification
,V/SystemUpdateService( 1640): retry (wakeup: false) in 3599973 ms
,D/SystemUpdateService( 1640): onDestroy
,D/ConnectivityService(  760): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): setDiscoveryMode: Mode set to WIFI
,I/jxcore-log( 3242): BLE supported!!
I/jxcore-log( 3242): 
,D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  760): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2747): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2747): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1640): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1640): onCreate
,D/SystemUpdateService( 1640): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1640): active receiver: enabled
,I/SystemUpdateService( 1640): showing system update notification
,E/GpsLocationProvider(  760): No APN found to select.
,I/ValidateNoPeople(  760): skipping global notification
,V/SystemUpdateService( 1640): retry (wakeup: false) in 3599980 ms
,D/SystemUpdateService( 1640): onDestroy
,I/art     (  760): Explicit concurrent mark sweep GC freed 44444(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 27MB/41MB, paused 1.310ms total 60.926ms
,D/Finsky  ( 2643): [255] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 2643): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/GLSActivity( 1601): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1601): Vacuum at: now=1452883490308 tag=VacuumService
,I/ActivityManager(  760): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=3538 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,I/GAv4    ( 3538): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3538):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3538):   adb logcat -s GAv4
,W/GAv4    ( 3538): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3538): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3538): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  760): Killing 2727:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10003/pid_2727/cgroup.procs: No such file or directory
,I/Keyboard.Facilitator.LanguageModelFlusher( 1107): run()
I/Keyboard.Facilitator( 1107): flushDynamicLanguageModels()
,I/ConfigService( 1601): onCreate
,I/ConfigService( 1601): onDestroy
,I/ClearcutLoggerApiImpl( 1601): disconnect managed GoogleApiClient
,I/EventLogService( 1640): Aggregate from 1452881701085 (log), 1452881701085 (data)
,I/jxcore-log( 3242): Connected to the server!
I/jxcore-log( 3242): 
,I/chromium( 3242): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3242): --- start :testFindPeers.js---
I/jxcore-log( 3242): 
,I/jxcore-log( 3242): testFindPeers created [object Object]
I/jxcore-log( 3242): 
I/jxcore-log( 3242): serverPort is 8876
I/jxcore-log( 3242): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): setDiscoveryMode: Mode set to WIFI
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3242): start: Peer ID: 34:FC:EF:11:AE:67, peer name: LGE-Nexus 5_PT4558
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3242): bind: Binding a new listener
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3242): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3242): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4558","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3242): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3242): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3242): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3242): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3242): setState: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3242): start: OK
I/io.jxcore.node.ConnectionHelper( 3242): start: Using peer discovery mode: WIFI
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): start: Peer ID: 34:FC:EF:11:AE:67, peer name: LGE-Nexus 5_PT4558
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3242): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4558","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3242): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3242): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4558","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3242): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4558","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3242): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3242): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3242): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3242): start: OK
I/jxcore-log( 3242): StartBroadcasting started ok
I/jxcore-log( 3242): 
I/chromium( 3242): [INFO:CONSOLE(63)] "logCallback --- start :testFindPeers.js---", source: file:///android_asset/www/js/thali_main.js (63)
,I/io.jxcore.node.ConnectionHelper( 3242): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3242): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3242): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3242): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3242): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3242): onDiscoveryManagerStateChanged: RUNNING
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3242): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
,D/WifiP2pManager( 3242): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3242): Service request added successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3242): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3242): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3242): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT4798","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3242): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3242): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
I/io.jxcore.node.ConnectionHelper( 3242): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798], Bluetooth address: 7C:F9:0E:51:18:22, device name: , device address: 7e:f9:0e:51:18:23
D/io.jxcore.node.ConnectionHelper( 3242): notifyPeerAvailability: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798] is available
,I/jxcore-log( 3242): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:51:18:22","peerName":"samsung-SM-A500FU_PT4798","peerAvailable":true}]
I/jxcore-log( 3242): 
,I/jxcore-log( 3242): Found peer : 7C:F9:0E:51:18:22, peerAvailable: true
I/jxcore-log( 3242): 
I/jxcore-log( 3242): weAreDoneNow
I/jxcore-log( 3242): 
I/jxcore-log( 3242): done, now sending data to server
I/jxcore-log( 3242): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3242): Got discovery timeout, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3242): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3242): setState: RESTARTING
,I/wpa_supplicant(  990): P2P-FIND-STOPPED 
,I/wpa_supplicant(  990): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant(  990): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3242): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3242): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3242): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3242): Start timer timeout, starting now...
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3242): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3242): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3242): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3242): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3242): restart: Restarting...
,D/WifiP2pManager( 3242): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3242): Service request added successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3242): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3242): Service discovery started successfully,
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  990): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3242): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT3714","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3242): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3242): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3242): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3242): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
I/io.jxcore.node.ConnectionHelper( 3242): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
D/io.jxcore.node.ConnectionHelper( 3242): notifyPeerAvailability: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714] is available
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3242): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT8999","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3242): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3242): onServiceDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): modifyListOfDiscoveredPeers: Adding new peer: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999]
I/io.jxcore.node.ConnectionHelper( 3242): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 92:b6:86:43:73:1c
D/io.jxcore.node.ConnectionHelper( 3242): notifyPeerAvailability: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999] is available
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3242): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT4771","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3242): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4771]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3242): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4771]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4771]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4771], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4771]
I/io.jxcore.node.ConnectionHelper( 3242): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4771], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: a2:39:f7:6f:c9:5d
D/io.jxcore.node.ConnectionHelper( 3242): notifyPeerAvailability: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4771] is available
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3242): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT4798","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3242): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3242): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
I/io.jxcore.node.ConnectionHelper( 3242): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798], Bluetooth address: 7C:F9:0E:51:18:22, device name: , device address: 7e:f9:0e:51:18:23
W/io.jxcore.node.ConnectionHelper( 3242): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798] already in the list, will not add again
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3242): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4771], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4771]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3242): restart: Restarting...
,D/WifiP2pManager( 3242): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3242): Service request added successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3242): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4771], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4771]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3242): Service discovery started successfully
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3242): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4771], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4771]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3242): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT4798","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3242): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3242): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
I/io.jxcore.node.ConnectionHelper( 3242): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
W/io.jxcore.node.ConnectionHelper( 3242): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3242): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3242): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3242): setState: RESTARTING
,I/wpa_supplicant(  990): P2P-FIND-STOPPED 
,I/wpa_supplicant(  990): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant(  990): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant(  990): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant(  990): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant(  990): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
I/wpa_supplicant(  990): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant(  990): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3242): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3242): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3242): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3242): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3242): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3242): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3242): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3242): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3242): Start timer timeout, starting now...
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3242): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3242): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3242): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant(  990): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3242): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3242): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3242): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
,D/WifiP2pManager( 3242): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3242): Service request added successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3242): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3242): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3242): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT8254","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3242): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT8254]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3242): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT8254]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT8254]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT8254], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT8254]
I/io.jxcore.node.ConnectionHelper( 3242): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT8254], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
D/io.jxcore.node.ConnectionHelper( 3242): notifyPeerAvailability: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT8254] is available
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3242): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onP2pDeviceListChanged: Peer 4: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT8254], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT8254]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3242): restart: Restarting...
,D/WifiP2pManager( 3242): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3242): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3242): Service discovery started successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3242): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onP2pDeviceListChanged: Peer 4: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT8254], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT8254]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3242): restart: Restarting...
,D/WifiP2pManager( 3242): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3242): Service request added successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant(  990): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3242): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT8254], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT8254]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3242): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT8254], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT8254]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3242): Service discovery started successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3242): teardown
I/jxcore-log( 3242): 
,I/jxcore-log( 3242): testFindPeers stopped
I/jxcore-log( 3242): 
,I/io.jxcore.node.ConnectionHelper( 3242): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3242): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3242): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3242): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3242): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3242): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3242): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3242): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3242): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3242): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3242): stop: Stopping P2P device discovery...
I/wpa_supplicant(  990): P2P-FIND-STOPPED 
,I/wpa_supplicant(  990): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant(  990): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant(  990): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant(  990): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant(  990): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3242): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3242): release: No more listeners, de-initializing...
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3242): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3242): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): setState: NOT_STARTED
I/jxcore-log( 3242): StopBroadcasting went ok
I/jxcore-log( 3242): 
,I/jxcore-log( 3242): --- start :testSendData.js---
I/jxcore-log( 3242): 
,I/jxcore-log( 3242): testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":15}bt-address length : 0
I/jxcore-log( 3242): 
,I/jxcore-log( 3242): daya100000
I/jxcore-log( 3242): 
I/jxcore-log( 3242): check server
I/jxcore-log( 3242): 
I/jxcore-log( 3242): serverPort is 35632
I/jxcore-log( 3242): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): setDiscoveryMode: Mode set to WIFI
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3242): start: Peer ID: 34:FC:EF:11:AE:67, peer name: LGE-Nexus 5_PT4558
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3242): bind: Binding a new listener
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3242): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3242): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4558","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3242): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3242): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3242): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 3242): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3242): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3242): start: OK
I/io.jxcore.node.ConnectionHelper( 3242): start: Using peer discovery mode: WIFI
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): start: Peer ID: 34:FC:EF:11:AE:67, peer name: LGE-Nexus 5_PT4558
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3242): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4558","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3242): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3242): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4558","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3242): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4558","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3242): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3242): start: Starting P2P device discovery...
,I/wpa_supplicant(  990): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3242): start: OK
I/jxcore-log( 3242): StartBroadcasting started ok
I/jxcore-log( 3242): 
,I/jxcore-log( 3242): null
I/jxcore-log( 3242): 
,I/jxcore-log( 3242): 2016-01-15T18:52:17.721Z SendDataTCPServer.js: TCP/IP server is bound to port: 35632
I/jxcore-log( 3242): 
,I/chromium( 3242): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/io.jxcore.node.ConnectionHelper( 3242): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3242): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3242): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3242): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 3242): onDiscoveryManagerStateChanged: NOT_STARTED
I/chromium( 3242): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
I/io.jxcore.node.ConnectionHelper( 3242): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3242): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3242): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3242): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3242): setState: RESTARTING
,I/wpa_supplicant(  990): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3242): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3242): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3242): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3242): onDiscoveryManagerStateChanged: RUNNING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3242): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3242): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3242): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3242): setState: RESTARTING
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3242): Waiting for incoming connections...
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant(  990): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3242): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3242): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiP2pManager( 3242): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3242): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3242): Service discovery started successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3242): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3242): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3242): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3242): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  990): p2p0: P2P: Reject scan trigger since one is already pending
I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3242): onP2pDeviceListChanged: 3 device(s) discovered,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3242): restart: Restarting...
,D/WifiP2pManager( 3242): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3242): Service request added successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3242): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3242): Service discovery started successfully
,W/bt-btif ( 2084): info:x10
,D/        ( 2084): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
E/BluetoothRemoteDevices( 2084): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 2084): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 1
E/bt-btif ( 2084): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2084): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2084): Entering PendingCommandState State
,W/BluetoothEventManager( 2708): CachedBluetoothDevice for device 08:EC:A9:50:75:41 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2708): Got bonding state changed for 08:EC:A9:50:75:41, but we have no record of that device.
,I/BluetoothBondStateMachine( 2084): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 0
,D/BluetoothAdapterProperties( 2084): Failed to remove device: 08:EC:A9:50:75:41
,I/BluetoothBondStateMachine( 2084): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 11 NewState: 10
,W/BluetoothEventManager( 2708): CachedBluetoothDevice for device 08:EC:A9:50:75:41 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2708): Got bonding state changed for 08:EC:A9:50:75:41, but we have no record of that device.
,I/BluetoothBondStateMachine( 2084): StableState(): Entering Off State
,W/bt-btif ( 2084): new conn_srvc id:26, app_id:255
W/bt-btif ( 2084): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2084): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3242): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3242): Incoming connection initialized (thread ID: 305)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3242): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3242): Entering thread (ID: 305)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3242): onBytesRead: Read 83 bytes successfully (thread ID: 305)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3242): Got valid identity from [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3242): onBytesWritten: 77 bytes successfully written (thread ID: 305)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3242): removeThreadFromList: Removing thread with ID 305
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3242): Handshake thread disposed (thread ID: 305)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3242): onIncomingConnectionConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3242): onConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033]
I/io.jxcore.node.ConnectionHelper( 3242): onConnected: Incoming connection to peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033]
D/io.jxcore.node.ConnectionHelper( 3242): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 3242): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033] is available
,I/jxcore-log( 3242): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:75:41","peerName":"samsung-SM-A300FU_PT2033","peerAvailable":true}]
I/jxcore-log( 3242): 
I/jxcore-log( 3242): Found peer : samsung-SM-A300FU_PT2033, Available: true
I/jxcore-log( 3242): 
I/jxcore-log( 3242): startWithNextDevice
I/jxcore-log( 3242): 
I/jxcore-log( 3242): device[1]: 08:EC:A9:50:75:41
I/jxcore-log( 3242): 
,I/jxcore-log( 3242): 2016-01-15T18:52:33.819Z SendDataConnector.js: Start called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3242): 
I/jxcore-log( 3242): 2016-01-15T18:52:33.819Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3242): 
I/jxcore-log( 3242): 2016-01-15T18:52:33.819Z SendDataConnector.js: do connect now
I/jxcore-log( 3242): 
I/io.jxcore.node.ConnectionHelper( 3242): connect: Trying to connect to peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 3242): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3242): connect: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3242): connect: Trying to start connecting to A3-1 in address 08:EC:A9:50:75:41
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3242): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3242): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3242): onConnecting: A3-1 08:EC:A9:50:75:41
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3242): connect: Started connecting to A3-1 in address 08:EC:A9:50:75:41
I/io.jxcore.node.ConnectionHelper( 3242): connect: Connection process successfully started (peer ID: 08:EC:A9:50:75:41)
,I/io.jxcore.node.ConnectionHelper( 3242): onConnected: Incoming socket thread, for peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033], created successfully
D/io.jxcore.node.ConnectionHelper( 3242): onConnected: The total number of connections is now 1
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3242): Exiting thread (ID: 305)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3242): Trying to connect to peer with address 08:EC:A9:50:75:41 (thread ID: 306)
W/BluetoothAdapter( 3242): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2084): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/io.jxcore.node.IncomingSocketThread( 3242): Entering thread (ID: 307)
,I/io.jxcore.node.IncomingSocketThread( 3242): Local host address: localhost/127.0.0.1, port: 35632
D/io.jxcore.node.IncomingSocketThread( 3242): Setting local streams and starting stream copying threads...
,I/jxcore-log( 3242): 2016-01-15T18:52:33.834Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3242): 
,I/io.jxcore.node.StreamCopyingThread( 3242): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3242): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3242): startStreamCopyingThreads: OK
,D/io.jxcore.node.IncomingSocketThread( 3242): Exiting thread (ID: 307)
,D/io.jxcore.node.StreamCopyingThread( 3242): Entering thread (ID: 309, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3242): Entering thread (ID: 308, name: Sender)
,W/bt-sdp  ( 2084): process_service_search_attr_rsp
,W/bt-btif ( 2084): new conn_srvc id:26, app_id:1
W/bt-btif ( 2084): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2084): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2084): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3242): onSocketConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3242): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 306)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3242): onBytesWritten: 77 bytes successfully written (thread ID: 310)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3242): Outgoing connection initialized (*handshake* thread ID: 310)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3242): Exiting thread (thread ID: 306)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3242): Entering thread (ID: 310)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3242): onBytesRead: Read 83 bytes successfully (thread ID: 310)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3242): Handshake succeeded with [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3242): onHandshakeSucceeded: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3242): onConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033]
I/io.jxcore.node.ConnectionHelper( 3242): onConnected: Outgoing connection to peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033]
D/io.jxcore.node.ConnectionHelper( 3242): hasConnection: We have an incoming connection with peer with ID 08:EC:A9:50:75:41
,W/io.jxcore.node.ConnectionHelper( 3242): onConnected: Already connected with peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033], continuing anyway...
W/io.jxcore.node.ConnectionHelper( 3242): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033] already in the list, will not add again
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/io.jxcore.node.ConnectionHelper( 3242): onConnected: Outgoing socket thread, for peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3242): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 3242): onConnected: The total number of connections is now 2
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3242): onP2pDeviceListChanged: 5 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3242): Exiting thread (ID: 310)
,D/io.jxcore.node.OutgoingSocketThread( 3242): Entering thread (ID: 311)
,D/io.jxcore.node.OutgoingSocketThread( 3242): Server socket local port: 60710
I/io.jxcore.node.OutgoingSocketThread( 3242): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3242): onListeningForIncomingConnections: Outgoing connection is using port 60710 (peer ID: 08:EC:A9:50:75:41)
,I/jxcore-log( 3242): 2016-01-15T18:52:34.322Z SendDataConnector.js: CLIENT connected to 60710, error: null
I/jxcore-log( 3242): 
I/jxcore-log( 3242): 2016-01-15T18:52:34.322Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3242): 
,I/io.jxcore.node.OutgoingSocketThread( 3242): Incoming data from address: /127.0.0.1, port: 60710
D/io.jxcore.node.OutgoingSocketThread( 3242): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3242): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3242): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3242): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3242): Exiting thread (ID: 311)
,D/io.jxcore.node.StreamCopyingThread( 3242): Entering thread (ID: 313, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3242): Entering thread (ID: 312, name: Sender)
,I/jxcore-log( 3242): 2016-01-15T18:52:34.368Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3242): 
,I/jxcore-log( 3242): 2016-01-15T18:52:34.778Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3242): 
,I/jxcore-log( 3242): 2016-01-15T18:52:34.797Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 3242): 
,I/jxcore-log( 3242): 2016-01-15T18:52:34.832Z SendDataTCPServer.js: TCP/IP server has received 35640 bytes of data
I/jxcore-log( 3242): 
,I/jxcore-log( 3242): 2016-01-15T18:52:34.888Z SendDataTCPServer.js: TCP/IP server has received 37620 bytes of data
I/jxcore-log( 3242): 
,I/jxcore-log( 3242): 2016-01-15T18:52:34.905Z SendDataTCPServer.js: TCP/IP server has received 39600 bytes of data
I/jxcore-log( 3242): 
,I/jxcore-log( 3242): 2016-01-15T18:52:34.916Z SendDataTCPServer.js: TCP/IP server has received 41580 bytes of data
I/jxcore-log( 3242): 
,I/jxcore-log( 3242): 2016-01-15T18:52:34.927Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data
I/jxcore-log( 3242): 
,D/        ( 2084): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23716
,I/jxcore-log( 3242): 2016-01-15T18:52:34.934Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3242): 
,I/jxcore-log( 3242): 2016-01-15T18:52:34.986Z SendDataTCPServer.js: TCP/IP server has received 45540 bytes of data
I/jxcore-log( 3242): 
,I/jxcore-log( 3242): 2016-01-15T18:52:35.057Z SendDataTCPServer.js: TCP/IP server has received 47520 bytes of data
I/jxcore-log( 3242): 
,I/jxcore-log( 3242): 2016-01-15T18:52:35.068Z SendDataTCPServer.js: TCP/IP server has received 49500 bytes of data
I/jxcore-log( 3242): 
,I/jxcore-log( 3242): 2016-01-15T18:52:35.078Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 3242): 
,I/jxcore-log( 3242): 2016-01-15T18:52:35.140Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 3242): 
,I/jxcore-log( 3242): 2016-01-15T18:52:35.180Z SendDataTCPServer.js: TCP/IP server has received 55440 bytes of data
I/jxcore-log( 3242): 
,I/jxcore-log( 3242): 2016-01-15T18:52:35.209Z SendDataTCPServer.js: TCP/IP server has received 57420 bytes of data
I/jxcore-log( 3242): 
,I/jxcore-log( 3242): 2016-01-15T18:52:35.258Z SendDataTCPServer.js: TCP/IP server has received 59400 bytes of data
I/jxcore-log( 3242): 
,I/jxcore-log( 3242): 2016-01-15T18:52:35.282Z SendDataTCPServer.js: TCP/IP server has received 61380 bytes of data
I/jxcore-log( 3242): 
,I/jxcore-log( 3242): 2016-01-15T18:52:35.296Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3242): 
I/jxcore-log( 3242): 2016-01-15T18:52:35.297Z SendDataTCPServer.js: TCP/IP server has received 63360 bytes of data
I/jxcore-log( 3242): 
,I/jxcore-log( 3242): 2016-01-15T18:52:35.358Z SendDataTCPServer.js: TCP/IP server has received 65340 bytes of data
I/jxcore-log( 3242): 
,I/jxcore-log( 3242): 2016-01-15T18:52:35.369Z SendDataTCPServer.js: TCP/IP server has received 67320 bytes of data
I/jxcore-log( 3242): 
,I/jxcore-log( 3242): 2016-01-15T18:52:35.380Z SendDataTCPServer.js: TCP/IP server has received 69300 bytes of data
I/jxcore-log( 3242): 
,I/jxcore-log( 3242): 2016-01-15T18:52:35.447Z SendDataTCPServer.js: TCP/IP server has received 71280 bytes of data
I/jxcore-log( 3242): 
,D/        ( 2084): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:13816
,I/jxcore-log( 3242): 2016-01-15T18:52:35.480Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3242): 
,I/jxcore-log( 3242): 2016-01-15T18:52:35.506Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3242): 
,I/jxcore-log( 3242): 2016-01-15T18:52:35.532Z SendDataTCPServer.js: TCP/IP server has received 73260 bytes of data
I/jxcore-log( 3242): 
,I/jxcore-log( 3242): 2016-01-15T18:52:35.572Z SendDataTCPServer.js: TCP/IP server has received 75240 bytes of data
I/jxcore-log( 3242): 
,I/jxcore-log( 3242): 2016-01-15T18:52:35.580Z SendDataTCPServer.js: TCP/IP server has received 77220 bytes of data
I/jxcore-log( 3242): 
,I/jxcore-log( 3242): 2016-01-15T18:52:35.644Z SendDataTCPServer.js: TCP/IP server has received 79200 bytes of data
I/jxcore-log( 3242): 
,I/jxcore-log( 3242): 2016-01-15T18:52:35.678Z SendDataTCPServer.js: TCP/IP server has received 81180 bytes of data
I/jxcore-log( 3242): 
,I/jxcore-log( 3242): 2016-01-15T18:52:35.767Z SendDataTCPServer.js: TCP/IP server has received 83160 bytes of data
I/jxcore-log( 3242): 
,I/jxcore-log( 3242): 2016-01-15T18:52:35.823Z SendDataTCPServer.js: TCP/IP server has received 85140 bytes of data
I/jxcore-log( 3242): 
,I/jxcore-log( 3242): 2016-01-15T18:52:35.870Z SendDataTCPServer.js: TCP/IP server has received 87120 bytes of data
I/jxcore-log( 3242): 
,I/jxcore-log( 3242): 2016-01-15T18:52:35.925Z SendDataTCPServer.js: TCP/IP server has received 89100 bytes of data
I/jxcore-log( 3242): 
,I/jxcore-log( 3242): 2016-01-15T18:52:35.957Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log( 3242): 
,D/        ( 2084): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:3916
,I/jxcore-log( 3242): 2016-01-15T18:52:35.990Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3242): 
,I/jxcore-log( 3242): 2016-01-15T18:52:36.022Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3242): 
,I/jxcore-log( 3242): 2016-01-15T18:52:36.033Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 3242): 
,I/jxcore-log( 3242): 2016-01-15T18:52:36.065Z SendDataTCPServer.js: TCP/IP server has received 97020 bytes of data
I/jxcore-log( 3242): 
,I/jxcore-log( 3242): 2016-01-15T18:52:36.076Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3242): 
,I/jxcore-log( 3242): 2016-01-15T18:52:36.088Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3242): 
,I/jxcore-log( 3242): 2016-01-15T18:52:36.105Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3242): 
,W/bt-btif ( 2084): invalid rfc slot id: 5
,W/io.jxcore.node.StreamCopyingThread( 3242): Either failed to read from the output stream or write to the input stream (thread ID: 309, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 3242): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3242): onDisconnected: Incoming connection, peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3242): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 307
D/io.jxcore.node.OutgoingSocketThread( 3242): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3242): doStop: Thread ID: 309
D/io.jxcore.node.OutgoingSocketThread( 3242): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3242): doStop: Thread ID: 308
,D/io.jxcore.node.OutgoingSocketThread( 3242): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 3242): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3242): Either failed to read from the output stream or write to the input stream (thread ID: 308, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3242): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3242): onDisconnected: Incoming connection, peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 3242): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 3242): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3242): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3242): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.ConnectionHelper( 3242): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.StreamCopyingThread( 3242): Exiting thread (ID: 308, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 3242): Exiting thread (ID: 309, name: Receiver)
,I/jxcore-log( 3242): 2016-01-15T18:52:36.187Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3242): 
,I/jxcore-log( 3242): 2016-01-15T18:52:36.426Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3242): 
,I/jxcore-log( 3242): 2016-01-15T18:52:36.745Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3242): 
I/jxcore-log( 3242): 2016-01-15T18:52:36.746Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3242): 
,I/jxcore-log( 3242): oneRoundDownNow
I/jxcore-log( 3242): 
I/jxcore-log( 3242): 2016-01-15T18:52:36.757Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3242): 
,I/jxcore-log( 3242): 2016-01-15T18:52:36.758Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3242): 
D/io.jxcore.node.ConnectionHelper( 3242): disconnectOutgoingConnection: Trying to close connection to peer with ID 08:EC:A9:50:75:41
I/io.jxcore.node.ConnectionHelper( 3242): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 08:EC:A9:50:75:41
I/io.jxcore.node.OutgoingSocketThread( 3242): close
D/io.jxcore.node.OutgoingSocketThread( 3242): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3242): doStop: Thread ID: 313
D/io.jxcore.node.OutgoingSocketThread( 3242): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3242): doStop: Thread ID: 312
D/io.jxcore.node.OutgoingSocketThread( 3242): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 3242): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3242): Either failed to read from the output stream or write to the input stream (thread ID: 312, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3242): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3242): onDisconnected: Outgoing connection, peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 3242): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 3242): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3242): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3242): Either failed to read from the output stream or write to the input stream (thread ID: 313, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.OutgoingSocketThread( 3242): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3242): onDisconnected: Outgoing connection, peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3242): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,I/io.jxcore.node.ConnectionHelper( 3242): disconnectOutgoingConnection: Successfully disconnected (peer ID: 08:EC:A9:50:75:41
,E/io.jxcore.node.ConnectionHelper( 3242): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 3242): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3242): Exiting thread (ID: 312, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 3242): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 3242): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3242): Exiting thread (ID: 313, name: Receiver)
,I/jxcore-log( 3242): 2016-01-15T18:52:36.798Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3242): 
I/jxcore-log( 3242): ---- round done--------
I/jxcore-log( 3242): 
I/jxcore-log( 3242): startWithNextDevice
I/jxcore-log( 3242): 
,W/bt-btif ( 2084): bta_jv_rfc_port_to_cb(port_handle:0xa):jv handle:0x0 not FOUND
,D/btif_config_util( 2084): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2084): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2084): onReceive
,D/BluetoothManagerService(  760): Message: 20
D/BluetoothManagerService(  760): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@14bcf1d0:true
,I/BTConnectionReceiver( 1381): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1381): Bluetooth Device Name: A3-1
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3242): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3242): restart: Restarting...
,D/WifiP2pManager( 3242): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3242): Service request added successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3242): Service discovery started successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  990): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3242): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3242): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3242): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3242): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3242): setState: RESTARTING
,I/wpa_supplicant(  990): P2P-FIND-STOPPED 
,I/wpa_supplicant(  990): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant(  990): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant(  990): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant(  990): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant(  990): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant(  990): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3242): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3242): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3242): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3242): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3242): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3242): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3242): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3242): Start timer timeout, starting now...
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3242): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3242): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3242): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3242): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3242): restart: Restarting...
,D/WifiP2pManager( 3242): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3242): Service request added successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3242): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3242): Service discovery started successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3242): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT3213","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3242): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3242): onServiceDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): modifyListOfDiscoveredPeers: Adding new peer: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
I/io.jxcore.node.ConnectionHelper( 3242): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
D/io.jxcore.node.ConnectionHelper( 3242): notifyPeerAvailability: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213] is available
I/jxcore-log( 3242): peerAvailabilityChanged [{"peerIdentifier":"B0:C5:59:3F:75:69","peerName":"samsung-SM-G900F_PT3213","peerAvailable":true}]
I/jxcore-log( 3242): 
I/jxcore-log( 3242): Found peer : samsung-SM-G900F_PT3213, Available: true
I/jxcore-log( 3242): 
I/jxcore-log( 3242): startWithNextDevice
I/jxcore-log( 3242): 
I/jxcore-log( 3242): device[2]: B0:C5:59:3F:75:69
I/jxcore-log( 3242): 
I/jxcore-log( 3242): 2016-01-15T18:53:44.290Z SendDataConnector.js: Start called with peer B0:C5:59:3F:75:69
I/jxcore-log( 3242): 
,I/jxcore-log( 3242): 2016-01-15T18:53:44.291Z SendDataConnector.js: doConnect called with peer B0:C5:59:3F:75:69
I/jxcore-log( 3242): 
I/jxcore-log( 3242): 2016-01-15T18:53:44.300Z SendDataConnector.js: do connect now
I/jxcore-log( 3242): 
,I/io.jxcore.node.ConnectionHelper( 3242): connect: Trying to connect to peer with ID B0:C5:59:3F:75:69
D/io.jxcore.node.ConnectionHelper( 3242): hasConnection: No connection with peer with ID B0:C5:59:3F:75:69
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3242): connect: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3242): connect: Trying to start connecting to null in address B0:C5:59:3F:75:69
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3242): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3242): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3242): onConnecting: null B0:C5:59:3F:75:69
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3242): connect: Started connecting to null in address B0:C5:59:3F:75:69
I/io.jxcore.node.ConnectionHelper( 3242): connect: Connection process successfully started (peer ID: B0:C5:59:3F:75:69)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3242): Trying to connect to peer with address B0:C5:59:3F:75:69 (thread ID: 314)
W/BluetoothAdapter( 3242): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2084): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2084): info:x10
,D/        ( 2084): remote version info [b0:c5:59:3f:75:69]: 7, f, 610c
,E/BluetoothRemoteDevices( 2084): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2084): process_service_search_attr_rsp
,D/btif_config_util( 2084): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btif ( 2084): check_cod: remote_cod = 0x5a020c
I/BluetoothBondStateMachine( 2084): No record of the device:null
I/BluetoothBondStateMachine( 2084): bondStateChangeCallback: Status: 9 Address: B0:C5:59:3F:75:69 newState: 0
,E/BluetoothBondStateMachine( 2084): In stable state, received invalid newState: 10
,W/bt-rfcomm( 2084): PORT_StartCnf failed result:5
E/bt-btm  ( 2084): btm_sec_disconnected - Clearing Pending flag
E/bt-btif ( 2084): Do not find the bg connection mask for the remote device
,W/bt-btif ( 2084): invalid rfc slot id: 8
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3242): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 314)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3242): Maximum number of allowed retries (0) reached, giving up... (thread ID: 314)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3242): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
E/BluetoothRemoteDevices( 2084): aclStateChangeCallback: Device is NULL
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3242): Exiting thread (thread ID: 314)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3242): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
,I/jxcore-log( 3242): 2016-01-15T18:53:46.277Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213] failed
I/jxcore-log( 3242): 
I/jxcore-log( 3242): 2016-01-15T18:53:46.277Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213] failed
I/jxcore-log( 3242): 
I/jxcore-log( 3242): 2016-01-15T18:53:46.278Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3242): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3242): setInsecureRfcommSocketPort: Will use port 1 when trying to connect
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3242): shutdown (thread ID: 314)
,I/ActivityManager(  760): Killing 2563:com.google.android.gm/u0a70 (adj 15): empty #17
,I/jxcore-log( 3242): 2016-01-15T18:53:51.279Z SendDataConnector.js: re-try now : B0:C5:59:3F:75:69
I/jxcore-log( 3242): 
I/jxcore-log( 3242): 2016-01-15T18:53:51.281Z SendDataConnector.js: ReStart called with peer B0:C5:59:3F:75:69
I/jxcore-log( 3242): 
,W/libprocessgroup(  760): failed to open /acct/uid_10070/pid_2563/cgroup.procs: No such file or directory
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3242): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3242): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3242): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT2033","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3242): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3242): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033]
,I/io.jxcore.node.ConnectionHelper( 3242): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper( 3242): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT2033] already in the list, will not add again
D/WifiP2pManager( 3242): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3242): Service request added successfully
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  990): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3242): Service discovery started successfully
,D/io.jxcore.node.ConnectionHelper( 3242): disconnectOutgoingConnection: Trying to close connection to peer with ID B0:C5:59:3F:75:69
E/io.jxcore.node.ConnectionHelper( 3242): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID B0:C5:59:3F:75:69
D/io.jxcore.node.ConnectionHelper( 3242): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3242): disconnectOutgoingConnection: Failed to disconnect (peer ID: B0:C5:59:3F:75:69), either no such connection or failed to close the connection
,I/jxcore-log( 3242): 2016-01-15T18:53:56.291Z SendDataConnector.js: Mobile.Disconnect() callback with peer B0:C5:59:3F:75:69
I/jxcore-log( 3242): 
I/jxcore-log( 3242): 2016-01-15T18:53:56.295Z SendDataConnector.js: Connect (retry count 1) to peer B0:C5:59:3F:75:69 with availability status: true
I/jxcore-log( 3242): 
,I/jxcore-log( 3242): 2016-01-15T18:53:56.298Z SendDataConnector.js: doConnect called with peer B0:C5:59:3F:75:69
I/jxcore-log( 3242): 
,I/jxcore-log( 3242): 2016-01-15T18:53:56.299Z SendDataConnector.js: do connect now
I/jxcore-log( 3242): 
,I/io.jxcore.node.ConnectionHelper( 3242): connect: Trying to connect to peer with ID B0:C5:59:3F:75:69
D/io.jxcore.node.ConnectionHelper( 3242): hasConnection: No connection with peer with ID B0:C5:59:3F:75:69
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3242): connect: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3242): connect: Trying to start connecting to null in address B0:C5:59:3F:75:69
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3242): setInsecureRfcommSocketPort: Using port 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3242): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3242): onConnecting: null B0:C5:59:3F:75:69
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3242): connect: Started connecting to null in address B0:C5:59:3F:75:69
I/io.jxcore.node.ConnectionHelper( 3242): connect: Connection process successfully started (peer ID: B0:C5:59:3F:75:69)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3242): Trying to connect to peer with address B0:C5:59:3F:75:69 (thread ID: 316)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3242): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3242): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2084): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2084): info:x10
,D/        ( 2084): remote version info [b0:c5:59:3f:75:69]: 7, f, 610c
,E/BluetoothRemoteDevices( 2084): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2084): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2084): bondStateChangeCallback: Status: 0 Address: B0:C5:59:3F:75:69 newState: 1
E/bt-btif ( 2084): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2084): Bond State Change Intent:B0:C5:59:3F:75:69 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2084): Entering PendingCommandState State
,W/BluetoothEventManager( 2708): CachedBluetoothDevice for device B0:C5:59:3F:75:69 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2708): Got bonding state changed for B0:C5:59:3F:75:69, but we have no record of that device.
,I/BluetoothBondStateMachine( 2084): bondStateChangeCallback: Status: 0 Address: B0:C5:59:3F:75:69 newState: 0
,D/BluetoothAdapterProperties( 2084): Failed to remove device: B0:C5:59:3F:75:69
,I/BluetoothBondStateMachine( 2084): Bond State Change Intent:B0:C5:59:3F:75:69 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2084): StableState(): Entering Off State
,W/BluetoothEventManager( 2708): CachedBluetoothDevice for device B0:C5:59:3F:75:69 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2708): Got bonding state changed for B0:C5:59:3F:75:69, but we have no record of that device.
,I/jxcore-log( 3242): timeout now
I/jxcore-log( 3242): 
I/jxcore-log( 3242): weAreDoneNow, resultArray.length: 1
I/jxcore-log( 3242): 
I/jxcore-log( 3242): sendReportNow
I/jxcore-log( 3242): 
I/jxcore-log( 3242): done, now sending data to server
I/jxcore-log( 3242): 
,I/jxcore-log( 3242): 2016-01-15T18:53:57.729Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3242): 
D/io.jxcore.node.ConnectionHelper( 3242): disconnectOutgoingConnection: Trying to close connection to peer with ID B0:C5:59:3F:75:69
E/io.jxcore.node.ConnectionHelper( 3242): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID B0:C5:59:3F:75:69
D/io.jxcore.node.ConnectionHelper( 3242): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3242): disconnectOutgoingConnection: Failed to disconnect (peer ID: B0:C5:59:3F:75:69), either no such connection or failed to close the connection
I/jxcore-log( 3242): 2016-01-15T18:53:57.730Z SendDataConnector.js: Mobile.Disconnect() callback with peer B0:C5:59:3F:75:69
I/jxcore-log( 3242): 
,W/bt-btif ( 2084): new conn_srvc id:26, app_id:1
W/bt-btif ( 2084): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2084): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3242): onSocketConnected: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3242): Socket connection succeeded (using port 1), total number of attempts: 1 (thread ID: 316)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3242): onBytesWritten: 77 bytes successfully written (thread ID: 317)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3242): Outgoing connection initialized (*handshake* thread ID: 317)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3242): Exiting thread (thread ID: 316)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3242): Entering thread (ID: 317)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3242): onBytesRead: Read 82 bytes successfully (thread ID: 317)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3242): Handshake succeeded with [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3242): onHandshakeSucceeded: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3242): Exiting thread (ID: 317)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3242): onConnected: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
I/io.jxcore.node.ConnectionHelper( 3242): onConnected: Outgoing connection to peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
D/io.jxcore.node.ConnectionHelper( 3242): hasConnection: No connection with peer with ID B0:C5:59:3F:75:69
W/io.jxcore.node.ConnectionHelper( 3242): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 3242): onConnected: Outgoing socket thread, for peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3242): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 3242): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 3242): Entering thread (ID: 318)
D/io.jxcore.node.OutgoingSocketThread( 3242): Server socket local port: 35115
I/io.jxcore.node.OutgoingSocketThread( 3242): Now accepting connections...
,W/bt-btif ( 2084): new conn_srvc id:26, app_id:255
W/bt-btif ( 2084): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2084): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2084): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3242): Incoming connection accepted
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3242): Incoming connection initialized (thread ID: 319)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3242): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3242): Entering thread (ID: 319)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3242): onBytesRead: Read 82 bytes successfully (thread ID: 319)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3242): Got valid identity from [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3242): onBytesWritten: 77 bytes successfully written (thread ID: 319)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3242): removeThreadFromList: Removing thread with ID 319
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3242): Handshake thread disposed (thread ID: 319)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3242): onIncomingConnectionConnected: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3242): Exiting thread (ID: 319)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3242): onConnected: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
,I/io.jxcore.node.ConnectionHelper( 3242): onConnected: Incoming connection to peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
D/io.jxcore.node.ConnectionHelper( 3242): hasConnection: We have an outgoing connection with peer with ID B0:C5:59:3F:75:69
,W/io.jxcore.node.ConnectionHelper( 3242): onConnected: Already connected with peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213], continuing anyway...
W/io.jxcore.node.ConnectionHelper( 3242): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 3242): onConnected: Incoming socket thread, for peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213], created successfully
D/io.jxcore.node.ConnectionHelper( 3242): onConnected: The total number of connections is now 2
,D/io.jxcore.node.IncomingSocketThread( 3242): Entering thread (ID: 320)
,I/jxcore-log( 3242): 2016-01-15T18:53:58.113Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3242): 
,I/io.jxcore.node.IncomingSocketThread( 3242): Local host address: localhost/127.0.0.1, port: 35632
D/io.jxcore.node.IncomingSocketThread( 3242): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3242): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3242): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3242): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3242): Exiting thread (ID: 320)
,D/io.jxcore.node.StreamCopyingThread( 3242): Entering thread (ID: 321, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 3242): Entering thread (ID: 322, name: Receiver)
,I/io.jxcore.node.ConnectionHelper( 3242): onListeningForIncomingConnections: Outgoing connection is using port 35115 (peer ID: B0:C5:59:3F:75:69)
I/jxcore-log( 3242): 2016-01-15T18:53:58.138Z SendDataConnector.js: CLIENT connected to 35115, error: null
I/jxcore-log( 3242): 
I/jxcore-log( 3242): 2016-01-15T18:53:58.138Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3242): 
,I/io.jxcore.node.IncomingSocketThread( 3242): Incoming data from address: /127.0.0.1, port: 35115
D/io.jxcore.node.IncomingSocketThread( 3242): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3242): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3242): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3242): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3242): Exiting thread (ID: 318)
,I/jxcore-log( 3242): 2016-01-15T18:53:58.142Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3242): 
,D/io.jxcore.node.StreamCopyingThread( 3242): Entering thread (ID: 324, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3242): Entering thread (ID: 323, name: Sender)
,I/jxcore-log( 3242): 2016-01-15T18:53:58.925Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3242): 
,I/jxcore-log( 3242): 2016-01-15T18:53:58.934Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3242): 
,I/jxcore-log( 3242): 2016-01-15T18:53:58.944Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3242): 
,I/jxcore-log( 3242): 2016-01-15T18:53:58.955Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3242): 
,I/jxcore-log( 3242): 2016-01-15T18:53:58.962Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3242): 
,I/jxcore-log( 3242): 2016-01-15T18:53:58.972Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3242): 
,I/jxcore-log( 3242): 2016-01-15T18:53:59.002Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 3242): 
,I/jxcore-log( 3242): 2016-01-15T18:53:59.014Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3242): 
,I/jxcore-log( 3242): 2016-01-15T18:53:59.065Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3242): 
,I/jxcore-log( 3242): 2016-01-15T18:53:59.094Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3242): 
,I/jxcore-log( 3242): 2016-01-15T18:53:59.102Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3242): 
,I/jxcore-log( 3242): 2016-01-15T18:53:59.106Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3242): 
,I/jxcore-log( 3242): 2016-01-15T18:53:59.141Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3242): 
I/jxcore-log( 3242): 2016-01-15T18:53:59.141Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3242): 
I/jxcore-log( 3242): oneRoundDownNow
I/jxcore-log( 3242): 
,I/jxcore-log( 3242): 2016-01-15T18:53:59.141Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3242): 
I/jxcore-log( 3242): 2016-01-15T18:53:59.142Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3242): 
,D/io.jxcore.node.ConnectionHelper( 3242): disconnectOutgoingConnection: Trying to close connection to peer with ID B0:C5:59:3F:75:69
I/io.jxcore.node.ConnectionHelper( 3242): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: B0:C5:59:3F:75:69
I/io.jxcore.node.IncomingSocketThread( 3242): close
D/io.jxcore.node.IncomingSocketThread( 3242): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3242): doStop: Thread ID: 324
D/io.jxcore.node.IncomingSocketThread( 3242): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3242): doStop: Thread ID: 323
D/io.jxcore.node.IncomingSocketThread( 3242): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 3242): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3242): Either failed to read from the output stream or write to the input stream (thread ID: 323, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3242): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3242): onDisconnected: Outgoing connection, peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.IncomingSocketThread( 3242): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 3242): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3242): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3242): Either failed to read from the output stream or write to the input stream (thread ID: 324, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 3242): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3242): onDisconnected: Outgoing connection, peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3242): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3242): disconnectOutgoingConnection: Successfully disconnected (peer ID: B0:C5:59:3F:75:69
,E/io.jxcore.node.ConnectionHelper( 3242): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID B0:C5:59:3F:75:69
D/io.jxcore.node.ConnectionHelper( 3242): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3242): Exiting thread (ID: 323, name: Sender)
E/io.jxcore.node.ConnectionHelper( 3242): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID B0:C5:59:3F:75:69
D/io.jxcore.node.ConnectionHelper( 3242): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3242): Exiting thread (ID: 324, name: Receiver)
,I/jxcore-log( 3242): 2016-01-15T18:53:59.148Z SendDataConnector.js: Mobile.Disconnect() callback with peer B0:C5:59:3F:75:69
I/jxcore-log( 3242): 
,I/jxcore-log( 3242): 2016-01-15T18:53:59.170Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3242): 
,I/jxcore-log( 3242): 2016-01-15T18:53:59.181Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3242): 
,I/jxcore-log( 3242): 2016-01-15T18:53:59.212Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 3242): 
,I/jxcore-log( 3242): 2016-01-15T18:53:59.216Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 3242): 
,I/jxcore-log( 3242): 2016-01-15T18:53:59.242Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 3242): 
,I/jxcore-log( 3242): 2016-01-15T18:53:59.247Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3242): 
,I/jxcore-log( 3242): 2016-01-15T18:53:59.271Z SendDataTCPServer.js: TCP/IP server has received 32768 bytes of data
I/jxcore-log( 3242): 
,W/bt-btif ( 2084): bta_jv_rfc_port_to_cb(port_handle:0xc):jv handle:0x0 not FOUND
,I/jxcore-log( 3242): 2016-01-15T18:53:59.306Z SendDataTCPServer.js: TCP/IP server has received 34748 bytes of data
I/jxcore-log( 3242): 
,I/jxcore-log( 3242): 2016-01-15T18:53:59.333Z SendDataTCPServer.js: TCP/IP server has received 36728 bytes of data
I/jxcore-log( 3242): 
,I/jxcore-log( 3242): 2016-01-15T18:53:59.360Z SendDataTCPServer.js: TCP/IP server has received 38708 bytes of data
I/jxcore-log( 3242): 
,I/jxcore-log( 3242): 2016-01-15T18:53:59.367Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data
I/jxcore-log( 3242): 
,I/jxcore-log( 3242): 2016-01-15T18:53:59.389Z SendDataTCPServer.js: TCP/IP server has received 42668 bytes of data
I/jxcore-log( 3242): 
,I/jxcore-log( 3242): 2016-01-15T18:53:59.425Z SendDataTCPServer.js: TCP/IP server has received 48608 bytes of data
I/jxcore-log( 3242): 
I/jxcore-log( 3242): 2016-01-15T18:53:59.427Z SendDataTCPServer.js: TCP/IP server has received 50588 bytes of data
I/jxcore-log( 3242): 
,I/jxcore-log( 3242): 2016-01-15T18:53:59.440Z SendDataTCPServer.js: TCP/IP server has received 52568 bytes of data
I/jxcore-log( 3242): 
,I/jxcore-log( 3242): 2016-01-15T18:53:59.475Z SendDataTCPServer.js: TCP/IP server has received 70388 bytes of data
I/jxcore-log( 3242): 
,I/jxcore-log( 3242): 2016-01-15T18:53:59.485Z SendDataTCPServer.js: TCP/IP server has received 72368 bytes of data
I/jxcore-log( 3242): 
,I/jxcore-log( 3242): 2016-01-15T18:53:59.501Z SendDataTCPServer.js: TCP/IP server has received 76328 bytes of data
I/jxcore-log( 3242): 
,I/jxcore-log( 3242): 2016-01-15T18:53:59.537Z SendDataTCPServer.js: TCP/IP server has received 98108 bytes of data
I/jxcore-log( 3242): 
,I/jxcore-log( 3242): 2016-01-15T18:53:59.549Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3242): 
,W/bt-btif ( 2084): invalid rfc slot id: 6
,W/io.jxcore.node.StreamCopyingThread( 3242): Either failed to read from the output stream or write to the input stream (thread ID: 322, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 3242): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3242): onDisconnected: Incoming connection, peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3242): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 320
D/io.jxcore.node.IncomingSocketThread( 3242): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3242): doStop: Thread ID: 322
D/io.jxcore.node.IncomingSocketThread( 3242): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3242): doStop: Thread ID: 321
D/io.jxcore.node.IncomingSocketThread( 3242): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 3242): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3242): Either failed to read from the output stream or write to the input stream (thread ID: 321, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3242): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3242): onDisconnected: Incoming connection, peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.IncomingSocketThread( 3242): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 3242): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3242): closeBluetoothSocketAndStreams
,D/io.jxcore.node.ConnectionHelper( 3242): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3242): Exiting thread (ID: 322, name: Receiver)
,D/io.jxcore.node.ConnectionHelper( 3242): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3242): Exiting thread (ID: 321, name: Sender)
,I/jxcore-log( 3242): 2016-01-15T18:53:59.700Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3242): 
,D/btif_config_util( 2084): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2084): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2084): onReceive
,I/BTConnectionReceiver( 1381): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1381): Bluetooth Device Name: Thali Test (Galaxy S5)
,I/jxcore-log( 3242): teardown
I/jxcore-log( 3242): 
,I/jxcore-log( 3242): testSendData stopped
I/jxcore-log( 3242): 
,I/io.jxcore.node.ConnectionHelper( 3242): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3242): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3242): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3242): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3242): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3242): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3242): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3242): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3242): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3242): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3242): stop: Stopping P2P device discovery...
,I/wpa_supplicant(  990): P2P-FIND-STOPPED 
,I/wpa_supplicant(  990): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant(  990): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant(  990): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3242): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3242): release: No more listeners, de-initializing...
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3242): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3242): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3242): setState: NOT_STARTED
I/jxcore-log( 3242): StopBroadcasting went ok
I/jxcore-log( 3242): 
,I/jxcore-log( 3242): 2016-01-15T18:54:17.833Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
I/jxcore-log( 3242): 
I/chromium( 3242): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/io.jxcore.node.ConnectionHelper( 3242): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3242): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3242): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3242): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 3242): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 3242): ****TEST TOOK:  ms ****
I/jxcore-log( 3242): 
I/jxcore-log( 3242): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3242): 
,D/AndroidRuntime( 3660): 
D/AndroidRuntime( 3660): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 3660): CheckJNI is OFF
,D/AndroidRuntime( 3660): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  760): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
,I/ActivityManager(  760): Killing 3242:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
,W/PackageSettings(  760): Skipping PackageSetting{2e08b83b com.example.hello/10278} due to missing metadata
,I/WindowState(  760): WIN DEATH: Window{3c7df675 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  760): Client connection lost with reason: 4
,I/ActivityManager(  760):   Force finishing activity ActivityRecord{183d5a38 u0 com.test.thalitest/.MainActivity t216}
,W/ActivityManager(  760): Spurious death for ProcessRecord{3d0085c9 3242:com.test.thalitest/u0a270}, curProc for 3242: null
,I/ActivityManager(  760): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
,W/GeofencerStateMachine( 1601): Ignoring removeGeofence because network location is disabled.
,I/InputReader(  760): Reconfiguring input devices.  changes=0x00000010
,I/art     ( 1305): Explicit concurrent mark sweep GC freed 3978(295KB) AllocSpace objects, 1(126KB) LOS objects, 38% free, 25MB/41MB, paused 1.105ms total 21.626ms
,I/Keyboard.Facilitator( 1107): resetDictionaries() : en_US
,D/VoicemailCleanupService( 1353): Cleaning up data for package: com.test.thalitest
I/Adreno-EGL(  944): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
I/OpenGLRenderer(  944): Initialized EGL, version 1.4
I/Keyboard.Facilitator.DecoderInitializer( 1107): run()
,I/Decoder ( 1107): createOrResetDecoder
D/OpenGLRenderer(  944): Enabling debug mode 0
,I/art     ( 1381): Explicit concurrent mark sweep GC freed 21049(1250KB) AllocSpace objects, 2(32KB) LOS objects, 24% free, 19MB/25MB, paused 337us total 72.892ms
,I/ConfigService( 1601): onCreate
I/UpdateIcingCorporaServi( 1381): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,W/Launcher( 1305): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@267ed904 new=com.google.android.velvet.VelvetApplication@267ed904
,I/art     (  760): Explicit concurrent mark sweep GC freed 32909(1777KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 1.385ms total 97.579ms
I/art     (  760): WaitForGcToComplete blocked for 83.000ms for cause Explicit
,I/art     ( 1640): Explicit concurrent mark sweep GC freed 12478(654KB) AllocSpace objects, 3(48KB) LOS objects, 24% free, 22MB/30MB, paused 2.219ms total 109.237ms
,I/ActivityManager(  760): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3704 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1107): run()
,W/InputMethodManagerService(  760): Focus gain on non-focused client com.android.internal.view.IInputMethodClient$Stub$Proxy@30783d48 (uid=10034 pid=944)
,W/InputMethodManagerService(  760): Got RemoteException sending setActive(false) notification to pid 3242 uid 10270
,I/Keyboard.Facilitator( 1107): onFinishInput()
,W/ContextImpl( 3704): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
,D/BackupManagerService(  760): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  760): Receieved: android.intent.action.PACKAGE_REMOVED
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1107): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1107): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1107): run() : Loading LM = contacts
,D/PackageBroadcastService( 1640): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/AccountUtils( 1640): Clearing selected account for com.test.thalitest
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1107): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1107): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1107): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1107): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1107): run() : Missing File = Personal.en_US.dict
,I/Keyboard.Facilitator.PersonalDictionaryLoader( 1107): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1107): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1107): run()
I/StatsUtilsManager( 1107): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1107): shouldRecordStats() = Too Soon
,D/ChimeraCfgMgr( 1640): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1640): Module APK com.google.android.play.games already loaded
,I/UpdateIcingCorporaServi( 1381): UpdateCorporaTask done [took 156 ms] updated apps [took 156 ms] 
,D/ChimeraCfgMgr( 1640): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1640): Module APK com.google.android.play.games already loaded
,D/TaskPersister(  760): removeObsoleteFile: deleting file=216_task.xml
I/LocationSettingsChecker( 1640): Removing dialog suppression flag for package com.test.thalitest
,E/NetworkScheduler.SchedulerReceiver( 1601): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1601): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,D/gH_CompatibleDatabase( 1640): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,D/gH_CompatibleDatabase( 1640): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 1640): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1640): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/gH_CompatibleDatabase( 1640): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1640): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/gH_CompatibleDatabase( 1640): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/gH_CompatibleDatabase( 1640): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1640): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 1640): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1640): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
,D/gH_CompatibleDatabase( 1640): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1640): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/art     (  760): Explicit concurrent mark sweep GC freed 10072(507KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 1.704ms total 200.432ms
,I/ActivityManager(  760): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3734 uid=10039 gids={50039, 9997} abi=armeabi-v7a
,I/Launcher( 1305): Deferring update until onResume
,W/BaseAppContext( 1640): Using Auth Proxy for data requests.
,W/BaseAppContext( 1640): Using Auth Proxy for data requests.
,W/ResourcesManager( 1305): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/GMPM-SVC( 1640): App measurement is starting up, version: 8489
I/GMPM-SVC( 1640): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,W/ResourcesManager( 1305): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Icing   ( 1640): doRemovePackageData com.test.thalitest
,I/Launcher( 1305): Deferring update until onResume
,D/AndroidRuntime( 3660): Shutting down VM
,I/ActivityManager(  760): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3760 uid=10007 gids={50007, 9997, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  760): Killing 1988:com.google.android.calendar/u0a31 (adj 15): empty #17
,I/ActivityManager(  760): Killing 2018:com.android.providers.calendar/u0a2 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10031/pid_1988/cgroup.procs: No such file or directory
,W/libprocessgroup(  760): failed to open /acct/uid_10002/pid_2018/cgroup.procs: No such file or directory
,D/ExternalStorage( 3760): After updating volumes, found 1 active roots
,W/ResourcesManager( 3163): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 3163): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/Documents( 3734): Update found 7 roots in 385ms
,D/Documents( 3734): Update found 7 roots in 176ms

```
