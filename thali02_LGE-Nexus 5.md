#### Test 564496607226f84_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
I/GAv4    ( 3216): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3216):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3216):   adb logcat -s GAv4
W/GAv4    ( 3216): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3216): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3216): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 3216): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
,D/Finsky  ( 2593): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
W/ResourcesManager( 3216): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3216): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  734): Killing 2558:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
V/JNIHelp ( 3216): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/AndroidRuntime( 3259): 
D/AndroidRuntime( 3259): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3259): CheckJNI is OFF
W/System  ( 3216): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3216): Installed default security provider GmsCore_OpenSSL
W/libprocessgroup(  734): failed to open /acct/uid_10069/pid_2558/cgroup.procs: No such file or directory
V/GLSActivity( 1569): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/AndroidRuntime( 3259): Calling main entry com.android.commands.am.Am
I/ActivityManager(  734): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  734): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3290 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3259): Shutting down VM
V/ActivityManager(  734): Display changed displayId=0
I/Icing   ( 1613): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/WebViewFactory( 3290): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/Icing   ( 1613): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1613): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
,I/LibraryLoader( 3290): Time to load native libraries: 2 ms (timestamps 6266-6268)
I/LibraryLoader( 3290): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3290): Binding Chromium to main looper Looper (main, tid 1) {a0961fb}
I/LibraryLoader( 3290): Expected native library version number "",actual native library version number ""
I/chromium( 3290): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3290): Initializing chromium process, singleProcess=true
W/art     ( 3290): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3290): ApplicationContext is null in ApplicationStatus
I/Icing   ( 1613): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
W/chromium( 3290): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3290): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3290): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3290): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
D/BluetoothManagerService(  734): Message: 20
D/BluetoothManagerService(  734): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e36951f:true
W/art     ( 3290): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 3290): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 3290): CordovaWebView is running on device made by: LGE
W/art     ( 3290): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3290): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 3290): Render dirty regions requested: true
D/Atlas   ( 3290): Validating map...
W/chromium( 3290): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/OpenGLRenderer( 3290): Initialized EGL, version 1.4
D/OpenGLRenderer( 3290): Enabling debug mode 0
I/Keyboard.Facilitator( 1075): onFinishInput()
W/BindingManager( 3290): Cannot call determinedVisibility() - never saw a connection for the pid: 3290
W/IInputConnectionWrapper( 3290): showStatusIcon on inactive InputConnection
I/ActivityManager(  734): Displayed com.test.thalitest/.MainActivity: +482ms (total +55s611ms)
D/JsMessageQueue( 3290): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 3290): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257342720
I/chromium( 3290): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
I/ActivityManager(  734): Killing 2499:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
W/libprocessgroup(  734): failed to open /acct/uid_10045/pid_2499/cgroup.procs: No such file or directory
,W/jxcore-log( 3290): Initializing JXcore engine
W/jxcore-log( 3290): JXcore engine is ready
,W/Thread-306( 3351): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[9503]" dev="sockfs" ino=9503 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/Thread-306( 3351): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-306( 3351): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8019]" dev="sockfs" ino=8019 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/Thread-306( 3351): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[19725]" dev="sockfs" ino=19725 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3290): Starting JXcore engine
,W/jxcore-log( 3290): Platform android
W/jxcore-log( 3290): 
,W/jxcore-log( 3290): Process ARCH arm
W/jxcore-log( 3290): 
,I/jxcore-log( 3290): JXcore Cordova bridge is ready!
I/jxcore-log( 3290): 
,W/jxcore-log( 3290): JXcore engine is started
,I/jxcore-log( 3290): Toggling radios to true
I/jxcore-log( 3290): 
,D/BluetoothAdapter( 3290): enable(): BT is already enabled..!
,D/WifiService(  734): New client listening to asynchronous messages
D/WifiService(  734): setWifiEnabled: true pid=3290, uid=10270
E/WifiService(  734): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3290): Radios toggled
I/jxcore-log( 3290): 
I/jxcore-log( 3290): My device name is: LGE-Nexus 5
I/jxcore-log( 3290): 
,I/wpa_supplicant( 1000): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  734): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  734): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/native  (  734): do suspend true
,D/CommandListener(  181): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1569): Read error: ssl=0xa4334e00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1569): SSL shutdown failed: ssl=0xa4334e00: I/O error during system call, Broken pipe
,D/ConnectivityService(  734): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): ValidatedState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): DefaultState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): Forcing reevaluation
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): EvaluatingState{ when=-1ms what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): Checking http://clients3.google.com/generate_204 on "NG7005g"
,E/WifiConfigStore(  734): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  734): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  734): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
E/WifiStateMachine(  734): Start Disconnecting Watchdog 1
,I/wpa_supplicant( 1000): wlan0: CTRL-EVENT-SCAN-STARTED 
,E/native  (  734): do suspend true
,D/CommandListener(  181): Clearing all IP addresses on wlan0
,D/ConnectivityService(  734): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/Nat464Xlat(  734): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  734): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityManager.CallbackHandler(  898): CM callback handler got msg 524292
,D/ConnectivityManager.CallbackHandler( 1613): CM callback handler got msg 524292
D/ConnectivityService(  734): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): Disconnected - quitting
,D/ConnectivityService(  734): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  734): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1260): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WifiNetworkAgent(  734): NetworkAgent: NetworkAgent channel lost
,I/wpa_supplicant( 1000): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant( 1000): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1000): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1000): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  734): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  734): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  734): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  734): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  181): Setting iface cfg
E/WifiStateMachine(  734): Start Dhcp Watchdog 2
,E/native  (  734): do suspend false
,E/WifiStateMachine(  734): scanCount==0 - aborting
,I/dhcpcd  ( 3390): version 5.5.6 starting
E/dhcpcd  ( 3390): get_duid: Read-only file system
,I/dhcpcd  ( 3390): wlan0: rebinding lease of 192.168.1.114
,I/dhcpcd  ( 3390): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3390): wlan0: leased 192.168.1.114 for 86400 seconds
,E/native  (  734): do suspend true
,E/WifiStateMachine(  734): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/ConnectivityService(  734): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService(  734): Adding iface wlan0 to network 101
,E/ConnectivityService(  734): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  734): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  734): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/ConnectivityService(  734): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/ConnectivityService(  734): Setting Dns servers for network 101 to [/192.168.1.1]
D/Nat464Xlat(  734): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  734): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  734): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  734): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  734):    accepting network in place of null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/CSLegacyTypeTracker(  734): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,D/ConnectivityService(  734): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  734): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  734): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  898): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1613): CM callback handler got msg 524290
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 19 Jan 2016 11:13:06 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1453201986039], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1453201986022]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): Validated
D/ConnectivityService(  734): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  734): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  734): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  734): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  734): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/TelephonyNetworkFactory( 1260): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 1613): CM callback handler got msg 524290
D/ConnectivityManager.CallbackHandler(  898): CM callback handler got msg 524290
,D/Nat464Xlat(  734): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  734): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  898): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 1613): CM callback handler got msg 524295
,D/ConnectivityService(  734): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  734): MasterInitialState.processMessage what=3
,D/ConnectivityService(  734): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  734): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2710): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2710): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 2710): type=WIFI subType= reason=null isConnected=true
,I/SystemUpdateService( 1613): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1613): onCreate
,D/SystemUpdateService( 1613): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1613): active receiver: enabled
,I/SystemUpdateService( 1613): showing system update notification
,E/GpsLocationProvider(  734): No APN found to select.
,I/ValidateNoPeople(  734): skipping global notification
,V/SystemUpdateService( 1613): retry (wakeup: false) in 3599978 ms
,I/ActivityManager(  734): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3448 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/SystemUpdateService( 1613): onDestroy
,D/ConnectivityService(  734): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,E/GpsLocationProvider(  734): No APN found to select.
,I/GAv4    ( 3448): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3448):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3448):   adb logcat -s GAv4
,W/GAv4    ( 3448): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3448): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3448): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 3448): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3448): Time to load native libraries: 1 ms (timestamps 2364-2365)
,I/LibraryLoader( 3448): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3448): Binding Chromium to main looper Looper (main, tid 1) {332fe7b5}
I/LibraryLoader( 3448): Expected native library version number "",actual native library version number ""
,I/chromium( 3448): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3448): Initializing chromium process, singleProcess=true
,W/art     ( 3448): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3448): ApplicationContext is null in ApplicationStatus
,W/chromium( 3448): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3448): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3448): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3448): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/AudioManagerAndroid( 3448): Requires BLUETOOTH permission
,I/NSApplication( 3448): Starting up...
,I/ActivityManager(  734): Killing 2690:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,I/jxcore-log( 3290): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3290): 
,W/libprocessgroup(  734): failed to open /acct/uid_10003/pid_2690/cgroup.procs: No such file or directory
,V/MusicLeanback( 2710): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1613): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1613): onCreate
,D/SystemUpdateService( 1613): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1613): active receiver: enabled
,I/SystemUpdateService( 1613): showing system update notification
,I/ValidateNoPeople(  734): skipping global notification
,V/SystemUpdateService( 1613): retry (wakeup: false) in 3599982 ms
,D/SystemUpdateService( 1613): onDestroy
,I/jxcore-log( 3290): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 3290): 
,I/jxcore-log( 3290): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 3290): 
,I/jxcore-log( 3290): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 3290): 
,I/jxcore-log( 3290): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 3290): 
I/jxcore-log( 3290): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 3290): 
,I/jxcore-log( 3290): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3290): 
,I/art     (  734): Explicit concurrent mark sweep GC freed 45014(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 27MB/41MB, paused 1.189ms total 87.087ms
,I/GCM     ( 1613): Message from null null
E/GCM     ( 1613): Dropping message from null
,D/ConnectivityService(  734): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  734): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2710): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2710): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,E/GpsLocationProvider(  734): No APN found to select.
,I/SystemUpdateService( 1613): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1613): onCreate
,D/SystemUpdateService( 1613): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1613): active receiver: enabled
,I/SystemUpdateService( 1613): showing system update notification
,I/ValidateNoPeople(  734): skipping global notification
,V/SystemUpdateService( 1613): retry (wakeup: false) in 3599968 ms
,D/SystemUpdateService( 1613): onDestroy
,I/jxcore-log( 3290): Test app app.js loaded
I/jxcore-log( 3290): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3290): setDiscoveryMode: Mode set to BLE
I/jxcore-log( 3290): BLE advertisement is supported
I/jxcore-log( 3290): 
,I/chromium( 3290): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/Finsky  ( 2593): [255] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2593): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/GLSActivity( 1569): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1569): Vacuum at: now=1453202001758 tag=VacuumService
,I/PhenotypeConfigurator( 1569): Scheduling Phenotype for one-off execution 5142 seconds from now (1453202002169)
,D/GetConfigurationSnapshotOperation( 1569): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1569): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1569): Using platform SSLCertificateSocketFactory
,V/GLSActivity( 1569): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1569): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Keyboard.Facilitator.LanguageModelFlusher( 1075): run()
I/Keyboard.Facilitator( 1075): flushDynamicLanguageModels()
,I/ConfigService( 1569): onCreate
,I/ConfigService( 1569): onDestroy
,I/ClearcutLoggerApiImpl( 1569): disconnect managed GoogleApiClient
,I/ActivityManager(  734): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=3655 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,I/GAv4    ( 3655): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3655):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3655):   adb logcat -s GAv4
,W/GAv4    ( 3655): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3655): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3655): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  734): Killing 2671:com.android.settings/1000 (adj 15): empty #17
,D/WifiService(  734): Client connection lost with reason: 4
,W/libprocessgroup(  734): failed to open /acct/uid_1000/pid_2671/cgroup.procs: No such file or directory
,I/EventLogService( 1613): Aggregate from 1453200301092 (log), 1453200301092 (data)
,I/jxcore-log( 3290): --= Surplus to requirements =--
I/jxcore-log( 3290): 
I/jxcore-log( 3290): ****TEST TOOK:  ms ****
I/jxcore-log( 3290): 
I/jxcore-log( 3290): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3290): 
,D/AndroidRuntime( 3725): 
D/AndroidRuntime( 3725): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 3725): CheckJNI is OFF
,D/AndroidRuntime( 3725): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  734): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  734): Killing 3290:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
,I/WindowState(  734): WIN DEATH: Window{184e0a7a u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  734): Client connection lost with reason: 4
,W/PackageSettings(  734): Skipping PackageSetting{3ae362df com.example.hello/10278} due to missing metadata
,I/ActivityManager(  734):   Force finishing activity ActivityRecord{22bac827 u0 com.test.thalitest/.MainActivity t216}
,W/ActivityManager(  734): Spurious death for ProcessRecord{33503066 3290:com.test.thalitest/u0a270}, curProc for 3290: null
,I/ActivityManager(  734): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
,I/ActivityManager(  734):   Force finishing activity ActivityRecord{22bac827 u0 com.test.thalitest/.MainActivity t216 f}
,W/ActivityManager(  734): Duplicate finish request for ActivityRecord{22bac827 u0 com.test.thalitest/.MainActivity t216 f}
,I/InputReader(  734): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 1569): Ignoring removeGeofence because network location is disabled.
,I/Keyboard.Facilitator( 1075): resetDictionaries() : en_US
,I/art     ( 1307): Explicit concurrent mark sweep GC freed 3947(293KB) AllocSpace objects, 1(126KB) LOS objects, 38% free, 25MB/41MB, paused 672us total 30.898ms
,I/Adreno-EGL(  945): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
I/OpenGLRenderer(  945): Initialized EGL, version 1.4
,D/VoicemailCleanupService( 2880): Cleaning up data for package: com.test.thalitest
,I/Keyboard.Facilitator.DecoderInitializer( 1075): run()
,I/Decoder ( 1075): createOrResetDecoder
D/OpenGLRenderer(  945): Enabling debug mode 0
,I/art     (  734): Explicit concurrent mark sweep GC freed 28513(1545KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 1.241ms total 105.010ms
I/ConfigService( 1569): onCreate
,I/art     ( 1399): Explicit concurrent mark sweep GC freed 11706(883KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 19MB/25MB, paused 752us total 108.534ms
,I/art     ( 1613): Explicit concurrent mark sweep GC freed 13700(711KB) AllocSpace objects, 3(48KB) LOS objects, 24% free, 22MB/30MB, paused 613us total 132.765ms
,I/UpdateIcingCorporaServi( 1399): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,W/Launcher( 1307): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@24fb6218 new=com.google.android.velvet.VelvetApplication@24fb6218
,W/InputMethodManagerService(  734): Got RemoteException sending setActive(false) notification to pid 3290 uid 10270
,I/Keyboard.Facilitator( 1075): onFinishInput()
,I/ActivityManager(  734): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3766 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,D/BackupManagerService(  734): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  734): Receieved: android.intent.action.PACKAGE_REMOVED
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1075): run()
,D/TaskPersister(  734): removeObsoleteFile: deleting file=216_task.xml
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1075): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1075): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1075): run() : Loading LM = contacts
,I/UpdateIcingCorporaServi( 1399): UpdateCorporaTask done [took 111 ms] updated apps [took 111 ms] 
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1075): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1075): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1075): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1075): run() : Loading LM = user
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1075): run() : Missing File = Personal.en_US.dict
,I/Keyboard.Facilitator.PersonalDictionaryLoader( 1075): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1075): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1075): run()
I/StatsUtilsManager( 1075): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1075): shouldRecordStats() = Too Soon
,W/ContextImpl( 3766): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
,D/PackageBroadcastService( 1613): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1613): Clearing selected account for com.test.thalitest
,I/art     (  734): Explicit concurrent mark sweep GC freed 6567(356KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 1.775ms total 160.518ms
D/ChimeraCfgMgr( 1613): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1613): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1613): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1613): Module APK com.google.android.play.games already loaded
,I/Keyboard.Facilitator( 1075): onFinishInput()
,E/NetworkScheduler.SchedulerReceiver( 1569): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1569): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,W/IInputConnectionWrapper( 1307): showStatusIcon on inactive InputConnection
,I/ActivityManager(  734): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3795 uid=10039 gids={50039, 9997} abi=armeabi-v7a
,I/LocationSettingsChecker( 1613): Removing dialog suppression flag for package com.test.thalitest
I/Launcher( 1307): Deferring update until onResume
D/AndroidRuntime( 3725): Shutting down VM
,I/ActivityManager(  734): Killing 2528:com.google.android.gm/u0a70 (adj 15): empty #17
,W/ResourcesManager( 1307): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/gH_CompatibleDatabase( 1613): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1613): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 1613): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1613): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/gH_CompatibleDatabase( 1613): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1613): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/gH_CompatibleDatabase( 1613): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/gH_CompatibleDatabase( 1613): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1613): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 1613): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1613): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
,D/gH_CompatibleDatabase( 1613): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1613): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,W/ResourcesManager( 1307): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Launcher( 1307): Deferring update until onResume
,W/libprocessgroup(  734): failed to open /acct/uid_10070/pid_2528/cgroup.procs: No such file or directory
,W/BaseAppContext( 1613): Using Auth Proxy for data requests.
,W/BaseAppContext( 1613): Using Auth Proxy for data requests.
I/GMPM-SVC( 1613): App measurement is starting up, version: 8489
I/GMPM-SVC( 1613): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,I/Icing   ( 1613): doRemovePackageData com.test.thalitest
,I/ActivityManager(  734): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3832 uid=10007 gids={50007, 9997, 1028, 1015, 1023} abi=armeabi-v7a
I/ActivityManager(  734): Killing 1961:com.google.android.calendar/u0a31 (adj 15): empty #17
,W/libprocessgroup(  734): failed to open /acct/uid_10031/pid_1961/cgroup.procs: No such file or directory
,I/ActivityManager(  734): Killing 1981:com.android.providers.calendar/u0a2 (adj 15): empty #17
,W/libprocessgroup(  734): failed to open /acct/uid_10002/pid_1981/cgroup.procs: No such file or directory
,E/SQLiteLog( 1613): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/GMPM-SVC( 1613): Task exception on worker thread: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850): com.google.android.gms.measurement.internal.e.b(SourceFile:321)

```
