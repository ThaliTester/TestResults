#### Test 573480784751f5c_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
I/GAv4    ( 3257): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3257):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3257):   adb logcat -s GAv4
W/GAv4    ( 3257): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3257): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3257): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 3257): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
,D/Finsky  ( 2721): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
I/ActivityManager(  760): Killing 2663:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
W/ResourcesManager( 3257): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3257): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/AndroidRuntime( 3305): 
D/AndroidRuntime( 3305): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3305): CheckJNI is OFF
W/libprocessgroup(  760): failed to open /acct/uid_10069/pid_2663/cgroup.procs: No such file or directory
V/JNIHelp ( 3257): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/AndroidRuntime( 3305): Calling main entry com.android.commands.am.Am
I/ActivityManager(  760): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
W/System  ( 3257): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3257): Installed default security provider GmsCore_OpenSSL
I/ActivityManager(  760): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3332 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3305): Shutting down VM
V/GLSActivity( 1628): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/ActivityManager(  760): Display changed displayId=0
I/Icing   ( 1670): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/Icing   ( 1670): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1670): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/Icing   ( 1670): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
I/WebViewFactory( 3332): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3332): Time to load native libraries: 1 ms (timestamps 6976-6977)
I/LibraryLoader( 3332): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3332): Binding Chromium to main looper Looper (main, tid 1) {2a67a2a3}
I/LibraryLoader( 3332): Expected native library version number "",actual native library version number ""
I/chromium( 3332): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3332): Initializing chromium process, singleProcess=true
W/art     ( 3332): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3332): ApplicationContext is null in ApplicationStatus
W/chromium( 3332): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3332): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3332): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3332): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
D/BluetoothManagerService(  760): Message: 20
D/BluetoothManagerService(  760): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3eaf6c6a:true
W/art     ( 3332): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 3332): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 3332): CordovaWebView is running on device made by: LGE
W/art     ( 3332): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3332): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 3332): Render dirty regions requested: true
D/Atlas   ( 3332): Validating map...
W/chromium( 3332): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/OpenGLRenderer( 3332): Initialized EGL, version 1.4
D/OpenGLRenderer( 3332): Enabling debug mode 0
I/ActivityManager(  760): Displayed com.test.thalitest/.MainActivity: +496ms (total +54s547ms)
W/IInputConnectionWrapper( 3332): showStatusIcon on inactive InputConnection
I/ActivityManager(  760): Killing 2595:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
W/BindingManager( 3332): Cannot call determinedVisibility() - never saw a connection for the pid: 3332
W/libprocessgroup(  760): failed to open /acct/uid_10045/pid_2595/cgroup.procs: No such file or directory
D/JsMessageQueue( 3332): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 3332): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257340160
I/chromium( 3332): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 3332): Initializing JXcore engine
W/jxcore-log( 3332): JXcore engine is ready
,W/Thread-313( 3385): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[9397]" dev="sockfs" ino=9397 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-313( 3385): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-313( 3385): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8474]" dev="sockfs" ino=8474 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-313( 3385): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[19150]" dev="sockfs" ino=19150 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3332): Starting JXcore engine
,W/jxcore-log( 3332): Platform android
W/jxcore-log( 3332): 
,W/jxcore-log( 3332): Process ARCH arm
W/jxcore-log( 3332): 
,I/jxcore-log( 3332): JXcore Cordova bridge is ready!
I/jxcore-log( 3332): 
,W/jxcore-log( 3332): JXcore engine is started
,I/jxcore-log( 3332): Toggling radios to true
I/jxcore-log( 3332): 
D/BluetoothAdapter( 3332): enable(): BT is already enabled..!
D/WifiService(  760): New client listening to asynchronous messages
D/WifiService(  760): setWifiEnabled: true pid=3332, uid=10270
E/WifiService(  760): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3332): Radios toggled
I/jxcore-log( 3332): 
I/jxcore-log( 3332): My device name is: LGE-Nexus 5
I/jxcore-log( 3332): 
,I/wpa_supplicant( 1024): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  760): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  760): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/native  (  760): do suspend true
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1628): Read error: ssl=0x9d475400: I/O error during system call, Connection timed out
,V/NativeCrypto( 1628): SSL shutdown failed: ssl=0x9d475400: I/O error during system call, Broken pipe
,D/ConnectivityService(  760): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): ValidatedState{ when=-27ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): DefaultState{ when=-27ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Checking http://clients3.google.com/generate_204 on "NG7005g"
E/WifiConfigStore(  760): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  760): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  760): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,E/WifiStateMachine(  760): Start Disconnecting Watchdog 1
I/wpa_supplicant( 1024): wlan0: CTRL-EVENT-SCAN-STARTED 
,E/native  (  760): do suspend true
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/ConnectivityService(  760): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler(  897): CM callback handler got msg 524292
,D/Nat464Xlat(  760): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/CSLegacyTypeTracker(  760): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityManager.CallbackHandler( 1670): CM callback handler got msg 524292
D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Disconnected - quitting
,D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  760): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1295): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WifiNetworkAgent(  760): NetworkAgent: NetworkAgent channel lost
,I/wpa_supplicant( 1024): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant( 1024): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1024): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 1024): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  760): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  760): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  760): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  760): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  179): Setting iface cfg
,E/WifiStateMachine(  760): Start Dhcp Watchdog 2
,E/native  (  760): do suspend false
,E/WifiStateMachine(  760): scanCount==0 - aborting
,I/dhcpcd  ( 3420): version 5.5.6 starting
E/dhcpcd  ( 3420): get_duid: Read-only file system
,I/dhcpcd  ( 3420): wlan0: rebinding lease of 192.168.1.114
,I/dhcpcd  ( 3420): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3420): wlan0: leased 192.168.1.114 for 86400 seconds
,E/native  (  760): do suspend true
,D/ConnectivityService(  760): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  760): Adding iface wlan0 to network 101
,E/WifiStateMachine(  760): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  760): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  760): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  760): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  760): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  760): Setting Dns servers for network 101 to [/192.168.1.1]
D/Nat464Xlat(  760): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  760): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  760): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  760): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  760):    accepting network in place of null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Checking http://clients3.google.com/generate_204 on "NG7005g"
,W/NetworkUtils( 1455): OkHttp exception
,W/EventLoggerService( 1455): Unable to send logs Error code: 262146
,D/CSLegacyTypeTracker(  760): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  760): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  760): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1670): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler(  897): CM callback handler got msg 524290
,V/GLSActivity( 1628): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1628): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 28 Jan 2016 12:52:25 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1453985545700], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1453985545683]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Validated
,D/ConnectivityService(  760): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  760): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  760): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  760): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler(  897): CM callback handler got msg 524290
D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/TelephonyNetworkFactory( 1295): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 1670): CM callback handler got msg 524290
,D/Nat464Xlat(  760): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  760): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler(  897): CM callback handler got msg 524295
D/ConnectivityManager.CallbackHandler( 1670): CM callback handler got msg 524295
,D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  760): MasterInitialState.processMessage what=3
D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering(  760): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2829): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2829): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 2829): type=WIFI subType= reason=null isConnected=true
,I/SystemUpdateService( 1670): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
D/SystemUpdateService( 1670): onCreate
,E/GpsLocationProvider(  760): No APN found to select.
,D/SystemUpdateService( 1670): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1670): active receiver: enabled
,I/SystemUpdateService( 1670): showing system update notification
,I/ValidateNoPeople(  760): skipping global notification
,V/SystemUpdateService( 1670): retry (wakeup: false) in 3599982 ms
,I/ActivityManager(  760): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3494 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/GpsLocationProvider(  760): No APN found to select.
,D/ConnectivityService(  760): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,D/SystemUpdateService( 1670): onDestroy
,I/GAv4    ( 3494): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3494):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3494):   adb logcat -s GAv4
,W/GAv4    ( 3494): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3494): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3494): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 3494): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3494): Time to load native libraries: 1 ms (timestamps 3323-3324)
I/LibraryLoader( 3494): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3494): Binding Chromium to main looper Looper (main, tid 1) {2947261d}
I/LibraryLoader( 3494): Expected native library version number "",actual native library version number ""
I/chromium( 3494): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3494): Initializing chromium process, singleProcess=true
W/art     ( 3494): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3494): ApplicationContext is null in ApplicationStatus
,W/chromium( 3494): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3494): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3494): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3494): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/AudioManagerAndroid( 3494): Requires BLUETOOTH permission
,I/NSApplication( 3494): Starting up...
,I/ActivityManager(  760): Killing 2806:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10003/pid_2806/cgroup.procs: No such file or directory
,V/MusicLeanback( 2829): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1670): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1670): onCreate
D/SystemUpdateService( 1670): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1670): active receiver: enabled
,I/SystemUpdateService( 1670): showing system update notification
,I/ValidateNoPeople(  760): skipping global notification
,V/SystemUpdateService( 1670): retry (wakeup: false) in 3599969 ms
,D/SystemUpdateService( 1670): onDestroy
,I/jxcore-log( 3332): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3332): 
,I/jxcore-log( 3332): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 3332): 
,I/jxcore-log( 3332): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 3332): 
,I/jxcore-log( 3332): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 3332): 
,I/jxcore-log( 3332): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 3332): 
,I/jxcore-log( 3332): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 3332): 
,I/jxcore-log( 3332): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 3332): 
,I/jxcore-log( 3332): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3332): 
,D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  760): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2829): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2829): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/art     (  760): Explicit concurrent mark sweep GC freed 43128(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 27MB/41MB, paused 897us total 78.394ms
,E/GpsLocationProvider(  760): No APN found to select.
,I/SystemUpdateService( 1670): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1670): onCreate
,D/SystemUpdateService( 1670): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1670): active receiver: enabled
,I/SystemUpdateService( 1670): showing system update notification
,I/ValidateNoPeople(  760): skipping global notification
,V/SystemUpdateService( 1670): retry (wakeup: false) in 3599970 ms
,D/SystemUpdateService( 1670): onDestroy
,I/jxcore-log( 3332): Test app app.js loaded
I/jxcore-log( 3332): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3332): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 3332): BLE advertisement is supported
I/jxcore-log( 3332): 
,I/chromium( 3332): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/Finsky  ( 2721): [260] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2721): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/GLSActivity( 1628): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1628): Vacuum at: now=1453985563407 tag=VacuumService
,I/ClearcutLoggerApiImpl( 1628): disconnect managed GoogleApiClient
,I/jxcore-log( 3332): --= Surplus to requirements =--
I/jxcore-log( 3332): 
I/jxcore-log( 3332): ****TEST TOOK:  ms ****
I/jxcore-log( 3332): 
I/jxcore-log( 3332): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3332): 
,D/AndroidRuntime( 3650): 
D/AndroidRuntime( 3650): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 3650): CheckJNI is OFF
,D/AndroidRuntime( 3650): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  760): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  760): Killing 3332:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
,I/WindowState(  760): WIN DEATH: Window{1ab3c41a u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  760): Client connection lost with reason: 4
,W/PackageSettings(  760): Skipping PackageSetting{2103e907 com.example.hello/10278} due to missing metadata
,I/ActivityManager(  760):   Force finishing activity ActivityRecord{7970b6b u0 com.test.thalitest/.MainActivity t216}
,W/ActivityManager(  760): Spurious death for ProcessRecord{3eac06c4 3332:com.test.thalitest/u0a270}, curProc for 3332: null
I/ActivityManager(  760): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
,I/art     ( 1670): Explicit concurrent mark sweep GC freed 11912(569KB) AllocSpace objects, 1(16KB) LOS objects, 25% free, 22MB/30MB, paused 437us total 30.787ms
,I/art     ( 1455): Explicit concurrent mark sweep GC freed 9094(578KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 19MB/25MB, paused 321us total 56.506ms
,I/art     ( 1329): Explicit concurrent mark sweep GC freed 3932(293KB) AllocSpace objects, 1(126KB) LOS objects, 38% free, 25MB/41MB, paused 918us total 37.631ms
,W/GeofencerStateMachine( 1628): Ignoring removeGeofence because network location is disabled.
,I/InputReader(  760): Reconfiguring input devices.  changes=0x00000010
,I/Keyboard.Facilitator( 1107): resetDictionaries() : en_US
,I/Keyboard.Facilitator.DecoderInitializer( 1107): run()
,I/Decoder ( 1107): createOrResetDecoder
,D/VoicemailCleanupService( 2927): Cleaning up data for package: com.test.thalitest
,D/NetworkChangeNotifierAutoDetect(  944): Network connectivity changed, type is: 2
,I/ConfigService( 1628): onCreate
,I/UpdateIcingCorporaServi( 1455): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/art     (  760): Explicit concurrent mark sweep GC freed 17647(1064KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 1.027ms total 88.596ms
,I/art     (  760): WaitForGcToComplete blocked for 29.622ms for cause Explicit
,I/LibraryLoader( 1393): Loading chrome directly from within /data/app/com.android.chrome-1/base.apk
,W/Launcher( 1329): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@ec019a0 new=com.google.android.velvet.VelvetApplication@ec019a0
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1107): run()
I/ActivityManager(  760): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3691 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/LibraryLoader( 1393): Time to load native libraries: 68 ms (timestamps 8669-8737)
,I/LibraryLoader( 1393): Expected native library version number "44.0.2403.133",actual native library version number "44.0.2403.133"
I/chromium( 1393): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,W/art     ( 1393): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 1393): Attempt to remove local handle scope entry from IRT, ignoring
,D/BackupManagerService(  760): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  760): Receieved: android.intent.action.PACKAGE_REMOVED
,I/OpenGLRenderer(  944): Initialized EGL, version 1.4
,D/OpenGLRenderer(  944): Enabling debug mode 0
,D/TaskPersister(  760): removeObsoleteFile: deleting file=216_task.xml
,I/art     (  760): Explicit concurrent mark sweep GC freed 4605(244KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 3.163ms total 137.566ms
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1107): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1107): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1107): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1107): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1107): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1107): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1107): run() : Loading LM = user
,W/ContextImpl( 3691): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1107): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1107): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1107): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1107): run()
I/StatsUtilsManager( 1107): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1107): shouldRecordStats() = Too Soon
,D/PackageBroadcastService( 1670): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1670): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 1670): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1670): Module APK com.google.android.play.games already loaded
,W/InputMethodManagerService(  760): Focus gain on non-focused client com.android.internal.view.IInputMethodClient$Stub$Proxy@16bd1423 (uid=10034 pid=944)
,D/ChimeraCfgMgr( 1670): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1670): Module APK com.google.android.play.games already loaded
,I/UpdateIcingCorporaServi( 1455): UpdateCorporaTask done [took 193 ms] updated apps [took 193 ms] 
,E/NetworkScheduler.SchedulerReceiver( 1628): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1628): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/LocationSettingsChecker( 1670): Removing dialog suppression flag for package com.test.thalitest
,D/gH_CompatibleDatabase( 1670): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1670): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1670): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1670): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,I/ActivityManager(  760): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3731 uid=10039 gids={50039, 9997} abi=armeabi-v7a
,D/gH_CompatibleDatabase( 1670): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1670): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1670): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/gH_CompatibleDatabase( 1670): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1670): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 1670): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1670): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1670): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1670): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/Launcher( 1329): Deferring update until onResume
,W/ResourcesManager( 1329): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  760): Killing 2786:com.android.settings/1000 (adj 15): empty #17
,W/ResourcesManager( 1329): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/GMPM-SVC( 1670): App measurement is starting up, version: 8489
I/GMPM-SVC( 1670): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,D/WifiService(  760): Client connection lost with reason: 4
,I/Launcher( 1329): Deferring update until onResume
,D/AndroidRuntime( 3650): Shutting down VM
,W/libprocessgroup(  760): failed to open /acct/uid_1000/pid_2786/cgroup.procs: No such file or directory
,W/BaseAppContext( 1670): Using Auth Proxy for data requests.
,W/BaseAppContext( 1670): Using Auth Proxy for data requests.
,I/Icing   ( 1670): doRemovePackageData com.test.thalitest
,I/ActivityManager(  760): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3756 uid=10007 gids={50007, 9997, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  760): Killing 2622:com.google.android.gm/u0a70 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10070/pid_2622/cgroup.procs: No such file or directory
,I/ActivityManager(  760): Killing 2055:com.google.android.calendar/u0a31 (adj 15): empty #17
,D/ExternalStorage( 3756): After updating volumes, found 1 active roots
,W/libprocessgroup(  760): failed to open /acct/uid_10031/pid_2055/cgroup.procs: No such file or directory
,W/ResourcesManager( 3257): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3257): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/Documents( 3731): Update found 7 roots in 220ms
,D/Documents( 3731): Update found 7 roots in 120ms

```
