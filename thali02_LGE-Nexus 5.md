#### Test 549702617e2936d_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
I/GAv4    ( 3236): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3236):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3236):   adb logcat -s GAv4
W/GAv4    ( 3236): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
D/ChimeraCfgMgr( 1671): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1671): Module APK com.google.android.play.games already loaded
W/GAv4    ( 3236): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3236): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 3236): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
D/Finsky  ( 2551): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
W/ResourcesManager( 3236): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3236): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/JNIHelp ( 3236): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/ActivityManager(  762): Killing 2806:com.qualcomm.timeservice/u0a76 (adj 15): empty #17
W/System  ( 3236): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3236): Installed default security provider GmsCore_OpenSSL
W/libprocessgroup(  762): failed to open /acct/uid_10076/pid_2806/cgroup.procs: No such file or directory
V/GLSActivity( 1606): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 1671): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/Icing   ( 1671): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1671): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/Icing   ( 1671): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
,D/AndroidRuntime( 3316): 
D/AndroidRuntime( 3316): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3316): CheckJNI is OFF
D/AndroidRuntime( 3316): Calling main entry com.android.commands.am.Am
I/ActivityManager(  762): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  762): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3332 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3316): Shutting down VM
V/ActivityManager(  762): Display changed displayId=0
I/ActivityManager(  762): Killing 2467:com.google.android.deskclock/u0a38 (adj 15): empty #17
W/libprocessgroup(  762): failed to open /acct/uid_10038/pid_2467/cgroup.procs: No such file or directory
I/WebViewFactory( 3332): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3332): Time to load native libraries: 2 ms (timestamps 9624-9626)
I/LibraryLoader( 3332): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3332): Binding Chromium to main looper Looper (main, tid 1) {2508f5b5}
I/LibraryLoader( 3332): Expected native library version number "",actual native library version number ""
I/chromium( 3332): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3332): Initializing chromium process, singleProcess=true
W/art     ( 3332): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3332): ApplicationContext is null in ApplicationStatus
,W/chromium( 3332): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3332): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3332): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3332): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  762): Message: 20
D/BluetoothManagerService(  762): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3d7243a6:true
,W/art     ( 3332): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3332): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3332): CordovaWebView is running on device made by: LGE
,W/art     ( 3332): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3332): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3332): Render dirty regions requested: true
,D/Atlas   ( 3332): Validating map...
,W/chromium( 3332): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3332): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3332): Enabling debug mode 0
,I/Keyboard.Facilitator( 1082): onFinishInput()
,W/BindingManager( 3332): Cannot call determinedVisibility() - never saw a connection for the pid: 3332
,W/IInputConnectionWrapper( 3332): showStatusIcon on inactive InputConnection
,I/ActivityManager(  762): Displayed com.test.thalitest/.MainActivity: +503ms (total +56s902ms)
,D/JsMessageQueue( 3332): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3332): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257343360
,D/JX-Cordova( 3332): jxcore cordova android initializing
,W/jxcore-log( 3332): Initializing JXcore engine
W/jxcore-log( 3332): JXcore engine is ready
,W/jxcore-log( 3332): Starting JXcore engine
,W/.test.thalitest( 3332): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[8457]" dev="sockfs" ino=8457 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/.test.thalitest( 3332): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 3332): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8541]" dev="sockfs" ino=8541 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3332): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[19454]" dev="sockfs" ino=19454 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3332): Platform android
W/jxcore-log( 3332): 
W/jxcore-log( 3332): Process ARCH arm
W/jxcore-log( 3332): 
,I/jxcore-log( 3332): JXcore Cordova bridge is ready!
I/jxcore-log( 3332): 
,W/jxcore-log( 3332): JXcore engine is started
,I/chromium( 3332): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3332): Toggling radios to true
I/jxcore-log( 3332): 
,D/BluetoothAdapter( 3332): enable(): BT is already enabled..!
,D/WifiService(  762): New client listening to asynchronous messages
,D/WifiService(  762): setWifiEnabled: true pid=3332, uid=10270
E/WifiService(  762): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3332): Radios toggled
I/jxcore-log( 3332): 
,I/jxcore-log( 3332): My device name is: LGE-Nexus 5
I/jxcore-log( 3332): 
,I/wpa_supplicant( 1048): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  762): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  762): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
E/native  (  762): do suspend true
,D/CommandListener(  179): Clearing all IP addresses on wlan0
E/WifiConfigStore(  762): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  762): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  762): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,E/WifiStateMachine(  762): Start Disconnecting Watchdog 1
,E/native  (  762): do suspend true
,V/NativeCrypto( 1606): Read error: ssl=0xb3d90e00: I/O error during system call, Connection timed out
I/wpa_supplicant( 1048): wlan0: CTRL-EVENT-SCAN-STARTED 
,V/NativeCrypto( 1606): SSL shutdown failed: ssl=0xb3d90e00: I/O error during system call, Broken pipe
,D/ConnectivityService(  762): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): ValidatedState{ when=-1ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): DefaultState{ when=-1ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): Checking http://clients3.google.com/generate_204 on <unknown ssid>
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/ConnectivityService(  762): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler(  902): CM callback handler got msg 524292
,D/Nat464Xlat(  762): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  762): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): Disconnected - quitting
D/ConnectivityService(  762): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  762): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  762): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory( 1213): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 1671): CM callback handler got msg 524292
,D/WifiNetworkAgent(  762): NetworkAgent: NetworkAgent channel lost
,V/GLSActivity( 1606): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1606): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/NetworkUtils( 1390): OkHttp exception
W/EventLoggerService( 1390): Unable to send logs Error code: 262146
,I/wpa_supplicant( 1048): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant( 1048): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1048): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1048): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  762): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,E/WifiConfigStore(  762): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  762): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  762): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  179): Setting iface cfg
,E/WifiStateMachine(  762): Start Dhcp Watchdog 2
,E/native  (  762): do suspend false
,E/WifiStateMachine(  762): scanCount==0 - aborting
,I/dhcpcd  ( 3418): version 5.5.6 starting
E/dhcpcd  ( 3418): get_duid: Read-only file system
,I/dhcpcd  ( 3418): wlan0: rebinding lease of 192.168.1.114
,I/dhcpcd  ( 3418): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3418): wlan0: leased 192.168.1.114 for 86400 seconds
,E/native  (  762): do suspend true
,E/WifiStateMachine(  762): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/ConnectivityService(  762): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  762): Adding iface wlan0 to network 101
,E/ConnectivityService(  762): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  762): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  762): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/ConnectivityService(  762): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/ConnectivityService(  762): Setting Dns servers for network 101 to [/192.168.1.1]
D/Nat464Xlat(  762): requiresClat: netType=1, connected=true, hasIPv4Address=true
,D/ConnectivityService(  762): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  762): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  762): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  762):    accepting network in place of null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/CSLegacyTypeTracker(  762): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  762): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  762): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  762): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  902): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1671): CM callback handler got msg 524290
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 11 Jan 2016 15:20:37 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452525637709], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452525637689]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): Validated
,D/ConnectivityService(  762): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  762): rematching NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  762): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  762): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler(  902): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1671): CM callback handler got msg 524290
D/TelephonyNetworkFactory( 1213): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  762): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityService(  762): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  762): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  762): MasterInitialState.processMessage what=3
,D/Tethering(  762): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2640): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 2640): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2640): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1671): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1671): onCreate
,D/SystemUpdateService( 1671): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1671): active receiver: enabled
,I/SystemUpdateService( 1671): showing system update notification
,I/ValidateNoPeople(  762): skipping global notification
,V/SystemUpdateService( 1671): retry (wakeup: false) in 3599972 ms
,I/ActivityManager(  762): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3482 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/GpsLocationProvider(  762): No APN found to select.
,D/Nat464Xlat(  762): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  762): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  902): CM callback handler got msg 524295
,D/SystemUpdateService( 1671): onDestroy
,D/ConnectivityManager.CallbackHandler( 1671): CM callback handler got msg 524295
,D/ConnectivityService(  762): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
E/GpsLocationProvider(  762): No APN found to select.
,I/GAv4    ( 3482): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3482):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3482):   adb logcat -s GAv4
,W/GAv4    ( 3482): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3482): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3482): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 3482): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3482): Time to load native libraries: 2 ms (timestamps 5944-5946)
,I/LibraryLoader( 3482): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3482): Binding Chromium to main looper Looper (main, tid 1) {3e971c5f}
,I/LibraryLoader( 3482): Expected native library version number "",actual native library version number ""
,I/chromium( 3482): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3482): Initializing chromium process, singleProcess=true
W/art     ( 3482): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3482): ApplicationContext is null in ApplicationStatus
,W/chromium( 3482): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3482): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3482): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3482): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/AudioManagerAndroid( 3482): Requires BLUETOOTH permission
,I/NSApplication( 3482): Starting up...
,I/ActivityManager(  762): Killing 2851:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/libprocessgroup(  762): failed to open /acct/uid_10003/pid_2851/cgroup.procs: No such file or directory
,V/MusicLeanback( 2640): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1671): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1671): onCreate
,D/SystemUpdateService( 1671): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1671): active receiver: enabled
,I/SystemUpdateService( 1671): showing system update notification
,I/ValidateNoPeople(  762): skipping global notification
,V/SystemUpdateService( 1671): retry (wakeup: false) in 3599976 ms
,D/SystemUpdateService( 1671): onDestroy
,D/ConnectivityService(  762): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  762): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2640): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2640): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/art     (  762): Explicit concurrent mark sweep GC freed 44450(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 27MB/41MB, paused 1.114ms total 91.104ms
,I/SystemUpdateService( 1671): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1671): onCreate
,D/SystemUpdateService( 1671): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1671): active receiver: enabled
,E/GpsLocationProvider(  762): No APN found to select.
,I/SystemUpdateService( 1671): showing system update notification
,I/ValidateNoPeople(  762): skipping global notification
,V/SystemUpdateService( 1671): retry (wakeup: false) in 3599975 ms
,D/SystemUpdateService( 1671): onDestroy
,I/jxcore-log( 3332): Test app app.js loaded
I/jxcore-log( 3332): 
,I/chromium( 3332): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/Finsky  ( 2551): [240] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2551): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/GLSActivity( 1606): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1606): Vacuum at: now=1452525652688 tag=VacuumService
,I/Keyboard.Facilitator.LanguageModelFlusher( 1082): run()
I/Keyboard.Facilitator( 1082): flushDynamicLanguageModels()
,I/ConfigService( 1606): onCreate
,I/ConfigService( 1606): onDestroy
,I/ClearcutLoggerApiImpl( 1606): disconnect managed GoogleApiClient
,I/jxcore-log( 3332): --= Surplus to requirements =--
I/jxcore-log( 3332): 
I/jxcore-log( 3332): ****TEST TOOK:  ms ****
I/jxcore-log( 3332): 
I/jxcore-log( 3332): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3332): 
,D/AndroidRuntime( 3634): 
D/AndroidRuntime( 3634): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 3634): CheckJNI is OFF
,D/AndroidRuntime( 3634): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  762): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  762): Killing 3332:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
,I/WindowState(  762): WIN DEATH: Window{6a8e256 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  762): Client connection lost with reason: 4
,W/PackageSettings(  762): Skipping PackageSetting{1ec6ef9 com.example.hello/10278} due to missing metadata
,I/ActivityManager(  762):   Force finishing activity ActivityRecord{86be682 u0 com.test.thalitest/.MainActivity t214}
,W/ActivityManager(  762): Spurious death for ProcessRecord{204f2923 3332:com.test.thalitest/u0a270}, curProc for 3332: null
I/ActivityManager(  762): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
,W/GeofencerStateMachine( 1606): Ignoring removeGeofence because network location is disabled.
,I/InputReader(  762): Reconfiguring input devices.  changes=0x00000010
,D/NetworkChangeNotifierAutoDetect(  948): Network connectivity changed, type is: 2
,I/art     ( 1262): Explicit concurrent mark sweep GC freed 3948(293KB) AllocSpace objects, 1(126KB) LOS objects, 38% free, 25MB/41MB, paused 453us total 41.810ms
I/Keyboard.Facilitator( 1082): resetDictionaries() : en_US
,I/Keyboard.Facilitator.DecoderInitializer( 1082): run()
I/art     ( 1390): Explicit concurrent mark sweep GC freed 7607(525KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 19MB/25MB, paused 350us total 101.248ms
,I/LibraryLoader( 1517): Loading chrome directly from within /data/app/com.android.chrome-1/base.apk
I/Decoder ( 1082): createOrResetDecoder
,I/art     ( 1671): Explicit concurrent mark sweep GC freed 21371(1218KB) AllocSpace objects, 5(80KB) LOS objects, 24% free, 22MB/30MB, paused 452us total 112.475ms
,D/VoicemailCleanupService( 2784): Cleaning up data for package: com.test.thalitest
,I/art     (  762): Explicit concurrent mark sweep GC freed 18238(1085KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 3.971ms total 107.671ms
,I/art     (  762): WaitForGcToComplete blocked for 18.208ms for cause Explicit
,I/UpdateIcingCorporaServi( 1390): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
W/Launcher( 1262): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@3eabf44a new=com.google.android.velvet.VelvetApplication@3eabf44a
I/OpenGLRenderer(  948): Initialized EGL, version 1.4
,D/OpenGLRenderer(  948): Enabling debug mode 0
,I/ActivityManager(  762): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3673 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/LibraryLoader( 1517): Time to load native libraries: 74 ms (timestamps 2816-2890)
,I/LibraryLoader( 1517): Expected native library version number "44.0.2403.133",actual native library version number "44.0.2403.133"
I/chromium( 1517): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,W/art     ( 1517): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 1517): Attempt to remove local handle scope entry from IRT, ignoring
,I/ConfigService( 1606): onCreate
,W/art     (  948): Attempt to remove local handle scope entry from IRT, ignoring
,D/BackupManagerService(  762): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService(  762): Receieved: android.intent.action.PACKAGE_REMOVED
,D/TaskPersister(  762): removeObsoleteFile: deleting file=214_task.xml
,W/InputMethodManagerService(  762): Focus gain on non-focused client com.android.internal.view.IInputMethodClient$Stub$Proxy@e522c2 (uid=10034 pid=948)
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1082): run()
,W/ContextImpl( 3673): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1082): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1082): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1082): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1082): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1082): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1082): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1082): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1082): run() : Missing File = Personal.en_US.dict
,W/InputMethodManagerService(  762): Got RemoteException sending setActive(false) notification to pid 3332 uid 10270
,I/Keyboard.Facilitator( 1082): onFinishInput()
,I/art     (  762): Explicit concurrent mark sweep GC freed 6325(320KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 3.639ms total 174.214ms
,D/ChimeraCfgMgr( 1671): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1671): Module APK com.google.android.play.games already loaded
,D/PackageBroadcastService( 1671): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1671): Clearing selected account for com.test.thalitest
,I/Keyboard.Facilitator.PersonalDictionaryLoader( 1082): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1082): run()
D/ChimeraCfgMgr( 1671): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1671): Module APK com.google.android.play.games already loaded
I/Keyboard.Facilitator.RecurringTaskScheduler( 1082): run()
I/StatsUtilsManager( 1082): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1082): shouldRecordStats() = Too Soon
,I/UpdateIcingCorporaServi( 1390): UpdateCorporaTask done [took 185 ms] updated apps [took 185 ms] 
,E/NetworkScheduler.SchedulerReceiver( 1606): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1606): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/LocationSettingsChecker( 1671): Removing dialog suppression flag for package com.test.thalitest
,D/gH_CompatibleDatabase( 1671): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1671): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 1671): 0 metrics were deleted when clearing package com.test.thalitest.
,D/gH_CompatibleDatabase( 1671): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,I/ActivityManager(  762): Delay finish: com.google.android.apps.plus/.service.PhotosAppTransitionMonitor
I/ActivityManager(  762): Resuming delayed broadcast
,D/gH_CompatibleDatabase( 1671): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1671): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1671): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/gH_CompatibleDatabase( 1671): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1671): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 1671): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1671): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1671): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1671): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/ActivityManager(  762): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3714 uid=10039 gids={50039, 9997} abi=armeabi-v7a
,I/Launcher( 1262): Deferring update until onResume
,W/BaseAppContext( 1671): Using Auth Proxy for data requests.
,D/AndroidRuntime( 3634): Shutting down VM
,W/ResourcesManager( 1262): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/BaseAppContext( 1671): Using Auth Proxy for data requests.
,I/ActivityManager(  762): Killing 2619:com.android.settings/1000 (adj 15): empty #17
,I/GMPM-SVC( 1671): App measurement is starting up, version: 8489
I/GMPM-SVC( 1671): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,D/WifiService(  762): Client connection lost with reason: 4
,W/ResourcesManager( 1262): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Launcher( 1262): Deferring update until onResume
,W/libprocessgroup(  762): failed to open /acct/uid_1000/pid_2619/cgroup.procs: No such file or directory
,I/Icing   ( 1671): doRemovePackageData com.test.thalitest
,I/ActivityManager(  762): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3740 uid=10007 gids={50007, 9997, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  762): Killing 2490:com.google.android.gm/u0a70 (adj 15): empty #17
,W/libprocessgroup(  762): failed to open /acct/uid_10070/pid_2490/cgroup.procs: No such file or directory
,I/ActivityManager(  762): Killing 2159:com.google.android.calendar/u0a31 (adj 15): empty #17
,W/libprocessgroup(  762): failed to open /acct/uid_10031/pid_2159/cgroup.procs: No such file or directory
,D/ExternalStorage( 3740): After updating volumes, found 1 active roots
,W/ResourcesManager( 3236): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 3236): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/Documents( 3714): Update found 7 roots in 254ms
,D/Documents( 3714): Update found 7 roots in 92ms

```
