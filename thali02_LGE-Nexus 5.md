#### Test 563583788793eb6_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
I/GAv4    ( 3137): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3137):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3137):   adb logcat -s GAv4
W/GAv4    ( 3137): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3137): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3137): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 3137): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
D/Finsky  ( 2585): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
W/ResourcesManager( 3137): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3137): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  738): Killing 2556:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
V/JNIHelp ( 3137): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/libprocessgroup(  738): failed to open /acct/uid_10069/pid_2556/cgroup.procs: No such file or directory
W/System  ( 3137): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3137): Installed default security provider GmsCore_OpenSSL
V/GLSActivity( 1573): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 1632): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/Icing   ( 1632): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1632): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/Icing   ( 1632): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
,D/AndroidRuntime( 3191): 
D/AndroidRuntime( 3191): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3191): CheckJNI is OFF
I/ActivityManager(  738): Killing 2511:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
D/AndroidRuntime( 3191): Calling main entry com.android.commands.am.Am
W/libprocessgroup(  738): failed to open /acct/uid_10045/pid_2511/cgroup.procs: No such file or directory
I/ActivityManager(  738): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  738): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3214 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3191): Shutting down VM
V/ActivityManager(  738): Display changed displayId=0
I/WebViewFactory( 3214): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3214): Time to load native libraries: 1 ms (timestamps 9155-9156)
I/LibraryLoader( 3214): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3214): Binding Chromium to main looper Looper (main, tid 1) {35519c46}
,I/LibraryLoader( 3214): Expected native library version number "",actual native library version number ""
,I/chromium( 3214): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3214): Initializing chromium process, singleProcess=true
W/art     ( 3214): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3214): ApplicationContext is null in ApplicationStatus
,W/chromium( 3214): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3214): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3214): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3214): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  738): Message: 20
,D/BluetoothManagerService(  738): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@19c3669b:true
,W/art     ( 3214): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3214): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3214): CordovaWebView is running on device made by: LGE
,W/art     ( 3214): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3214): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3214): Render dirty regions requested: true
,D/Atlas   ( 3214): Validating map...
,W/chromium( 3214): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3214): Initialized EGL, version 1.4
D/OpenGLRenderer( 3214): Enabling debug mode 0
,I/ActivityManager(  738): Displayed com.test.thalitest/.MainActivity: +494ms (total +57s864ms)
,W/IInputConnectionWrapper( 3214): showStatusIcon on inactive InputConnection
,W/BindingManager( 3214): Cannot call determinedVisibility() - never saw a connection for the pid: 3214
,D/JsMessageQueue( 3214): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3214): JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1405526272
,I/chromium( 3214): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 3214): Initializing JXcore engine
W/jxcore-log( 3214): JXcore engine is ready
,W/Thread-311( 3263): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[7933]" dev="sockfs" ino=7933 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/Thread-311( 3263): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-311( 3263): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6594]" dev="sockfs" ino=6594 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/Thread-311( 3263): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[20491]" dev="sockfs" ino=20491 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3214): Starting JXcore engine
,W/jxcore-log( 3214): Platform android
W/jxcore-log( 3214): 
,W/jxcore-log( 3214): Process ARCH arm
W/jxcore-log( 3214): 
,I/jxcore-log( 3214): JXcore Cordova bridge is ready!
I/jxcore-log( 3214): 
W/jxcore-log( 3214): JXcore engine is started
,I/jxcore-log( 3214): Toggling radios to true
I/jxcore-log( 3214): 
,D/BluetoothAdapter( 3214): enable(): BT is already enabled..!
,D/WifiService(  738): setWifiEnabled: true pid=3214, uid=10270
E/WifiService(  738): Invoking mWifiStateMachine.setWifiEnabled
,D/WifiService(  738): New client listening to asynchronous messages
,I/jxcore-log( 3214): Radios toggled
I/jxcore-log( 3214): 
I/jxcore-log( 3214): My device name is: LGE-Nexus 5
I/jxcore-log( 3214): 
,I/wpa_supplicant(  986): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  738): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  738): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/native  (  738): do suspend true
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1573): Read error: ssl=0x9af1de00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1573): SSL shutdown failed: ssl=0x9af1de00: I/O error during system call, Broken pipe
D/ConnectivityService(  738): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  738): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
E/WifiConfigStore(  738): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
E/WifiStateMachine(  738): Start Disconnecting Watchdog 1
I/wpa_supplicant(  986): wlan0: CTRL-EVENT-SCAN-STARTED 
E/native  (  738): do suspend true
,D/ConnectivityService(  738): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  738): ValidatedState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  738): DefaultState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  738): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  738): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  738): Checking http://clients3.google.com/generate_204 on <unknown ssid>
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,D/ConnectivityService(  738): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler(  897): CM callback handler got msg 524292
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  738): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  738): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  738): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  738): Disconnected - quitting
D/Nat464Xlat(  738): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  738): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,D/ConnectivityService(  738): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  738): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  738): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1219): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WifiNetworkAgent(  738): NetworkAgent: NetworkAgent channel lost
,D/ConnectivityManager.CallbackHandler( 1632): CM callback handler got msg 524292
,V/GLSActivity( 1573): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1573): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/NetworkUtils( 1355): OkHttp exception
W/EventLoggerService( 1355): Unable to send logs Error code: 262146
,I/wpa_supplicant(  986): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant(  986): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant(  986): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant(  986): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  738): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  738): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  738): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiConfigStore(  738): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/CommandListener(  179): Setting iface cfg
E/WifiStateMachine(  738): Start Dhcp Watchdog 2
,E/native  (  738): do suspend false
,E/WifiStateMachine(  738): scanCount==0 - aborting
,I/dhcpcd  ( 3293): version 5.5.6 starting
E/dhcpcd  ( 3293): get_duid: Read-only file system
,I/dhcpcd  ( 3293): wlan0: rebinding lease of 192.168.1.114
,I/dhcpcd  ( 3293): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3293): wlan0: leased 192.168.1.114 for 86400 seconds
,D/ConnectivityService(  738): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  738): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering(  738): MasterInitialState.processMessage what=3
D/Tethering(  738): MasterInitialState.processMessage what=3
,V/MusicLeanback( 2700): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1632): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1632): onCreate
,D/SystemUpdateService( 1632): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.Environment( 1632): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1632): num queued entries: 0
I/iu.UploadsManager( 1632): num updated entries: 0
I/iu.SyncManager( 1632): NEXT; no task
,I/ActivityManager(  738): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3319 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/GpsLocationProvider(  738): No APN found to select.
,I/SystemUpdateService( 1632): active receiver: enabled
,I/Babel   ( 1888): connection state changed from CONNECTED to DISCONNECTED
,I/SystemUpdateService( 1632): showing system update notification
,E/GpsLocationProvider(  738): No APN found to select.
,E/native  (  738): do suspend true
,I/ValidateNoPeople(  738): skipping global notification
,V/SystemUpdateService( 1632): retry (wakeup: false) in 3599954 ms
,D/SystemUpdateService( 1632): onDestroy
,D/ConnectivityService(  738): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  738): Adding iface wlan0 to network 101
,E/WifiStateMachine(  738): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  738): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  738): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  738): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/ConnectivityService(  738): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  738): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  738): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  738): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  738): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  738): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  738):    accepting network in place of null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  738): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  738): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  738): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  738): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/CSLegacyTypeTracker(  738): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  738): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  738): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  738): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler(  897): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1632): CM callback handler got msg 524290
,D/Nat464Xlat(  738): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  738): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler(  897): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 1632): CM callback handler got msg 524295
,I/GAv4    ( 3319): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3319):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3319):   adb logcat -s GAv4
,W/GAv4    ( 3319): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3319): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3319): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  738): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 18 Jan 2016 16:23:40 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1453134220691], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1453134220673]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  738): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  738): Validated
D/ConnectivityService(  738): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  738): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  738): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  738): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler(  897): CM callback handler got msg 524290
D/ConnectivityService(  738): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/TelephonyNetworkFactory( 1219): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 1632): CM callback handler got msg 524290
,I/WebViewFactory( 3319): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3319): Time to load native libraries: 1 ms (timestamps 5251-5252)
I/LibraryLoader( 3319): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3319): Binding Chromium to main looper Looper (main, tid 1) {4c74348}
I/LibraryLoader( 3319): Expected native library version number "",actual native library version number ""
I/chromium( 3319): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3319): Initializing chromium process, singleProcess=true
,W/art     ( 3319): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3319): ApplicationContext is null in ApplicationStatus
,W/chromium( 3319): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3319): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3319): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3319): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/AudioManagerAndroid( 3319): Requires BLUETOOTH permission
,I/NSApplication( 3319): Starting up...
,I/ActivityManager(  738): Killing 2679:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,I/jxcore-log( 3214): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3214): 
,W/libprocessgroup(  738): failed to open /acct/uid_10003/pid_2679/cgroup.procs: No such file or directory
,V/MusicLeanback( 2700): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1632): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1632): onCreate
,D/SystemUpdateService( 1632): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.Environment( 1632): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1632): num queued entries: 0
,I/iu.UploadsManager( 1632): num updated entries: 0
,I/iu.SyncManager( 1632): NEXT; no task
,I/SystemUpdateService( 1632): active receiver: enabled
,I/SystemUpdateService( 1632): showing system update notification
,I/ValidateNoPeople(  738): skipping global notification
,V/SystemUpdateService( 1632): retry (wakeup: false) in 3599965 ms
,D/SystemUpdateService( 1632): onDestroy
,I/Babel   ( 1888): connection state changed from DISCONNECTED to CONNECTED
,D/ConnectivityService(  738): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/jxcore-log( 3214): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 3214): 
,I/jxcore-log( 3214): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 3214): 
,I/jxcore-log( 3214): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 3214): 
,I/jxcore-log( 3214): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 3214): 
,I/jxcore-log( 3214): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 3214): 
,I/jxcore-log( 3214): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3214): 
,I/jxcore-log( 3214): Test app app.js loaded
I/jxcore-log( 3214): 
,I/chromium( 3214): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3214): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 3214): BLE advertisement is supported
I/jxcore-log( 3214): 
,D/ConnectivityService(  738): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  738): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2700): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2700): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1632): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1632): onCreate
,D/SystemUpdateService( 1632): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1632): active receiver: enabled
,I/SystemUpdateService( 1632): showing system update notification
,I/ValidateNoPeople(  738): skipping global notification
,V/SystemUpdateService( 1632): retry (wakeup: false) in 3599983 ms
,I/art     (  738): Explicit concurrent mark sweep GC freed 43918(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 27MB/41MB, paused 896us total 68.699ms
,D/SystemUpdateService( 1632): onDestroy
,E/GpsLocationProvider(  738): No APN found to select.
,D/Finsky  ( 2585): [260] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2585): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/GLSActivity( 1573): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1573): Vacuum at: now=1453134232427 tag=VacuumService
,I/PhenotypeConfigurator( 1573): Scheduling Phenotype for one-off execution 9744 seconds from now (1453134232792)
,D/GetConfigurationSnapshotOperation( 1573): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1573): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1573): Using platform SSLCertificateSocketFactory
,I/ClearcutLoggerApiImpl( 1573): disconnect managed GoogleApiClient
,I/jxcore-log( 3214): --= Surplus to requirements =--
I/jxcore-log( 3214): 
I/jxcore-log( 3214): ****TEST TOOK:  ms ****
I/jxcore-log( 3214): 
I/jxcore-log( 3214): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3214): 
,D/AndroidRuntime( 3501): 
D/AndroidRuntime( 3501): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 3501): CheckJNI is OFF
,D/AndroidRuntime( 3501): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  738): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  738): Killing 3214:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
,I/WindowState(  738): WIN DEATH: Window{2d072c8b u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  738): Client connection lost with reason: 4
,W/PackageSettings(  738): Skipping PackageSetting{1643ee7a com.example.hello/10278} due to missing metadata
,I/ActivityManager(  738):   Force finishing activity ActivityRecord{1985b887 u0 com.test.thalitest/.MainActivity t216}
,W/ActivityManager(  738): Spurious death for ProcessRecord{f33ee0f 3214:com.test.thalitest/u0a270}, curProc for 3214: null
,I/ActivityManager(  738): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
I/ActivityManager(  738):   Force finishing activity ActivityRecord{1985b887 u0 com.test.thalitest/.MainActivity t216 f}
W/ActivityManager(  738): Duplicate finish request for ActivityRecord{1985b887 u0 com.test.thalitest/.MainActivity t216 f}
,I/art     ( 1355): Explicit concurrent mark sweep GC freed 8609(587KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 18MB/25MB, paused 300us total 19.656ms
,I/InputReader(  738): Reconfiguring input devices.  changes=0x00000010
,I/art     ( 1279): Explicit concurrent mark sweep GC freed 3934(293KB) AllocSpace objects, 1(126KB) LOS objects, 38% free, 25MB/41MB, paused 222us total 16.812ms
,I/Keyboard.Facilitator( 1085): resetDictionaries() : en_US
,W/GeofencerStateMachine( 1573): Ignoring removeGeofence because network location is disabled.
,I/Keyboard.Facilitator.DecoderInitializer( 1085): run()
I/Decoder ( 1085): createOrResetDecoder
,I/art     (  738): Explicit concurrent mark sweep GC freed 18669(1059KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 5.203ms total 81.086ms
,I/art     ( 1632): Explicit concurrent mark sweep GC freed 33460(2MB) AllocSpace objects, 7(112KB) LOS objects, 24% free, 22MB/30MB, paused 994us total 101.438ms
,D/VoicemailCleanupService( 2799): Cleaning up data for package: com.test.thalitest
,I/UpdateIcingCorporaServi( 1355): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/ConfigService( 1573): onCreate
,W/Launcher( 1279): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@35810e07 new=com.google.android.velvet.VelvetApplication@35810e07
,I/Adreno-EGL(  944): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
I/OpenGLRenderer(  944): Initialized EGL, version 1.4
,D/OpenGLRenderer(  944): Enabling debug mode 0
,I/ActivityManager(  738): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3542 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/art     (  738): Explicit concurrent mark sweep GC freed 4494(236KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 27MB/41MB, paused 1.393ms total 89.657ms
,W/InputMethodManagerService(  738): Focus gain on non-focused client com.android.internal.view.IInputMethodClient$Stub$Proxy@356142ad (uid=10034 pid=944)
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1085): run()
,D/BackupManagerService(  738): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService(  738): Receieved: android.intent.action.PACKAGE_REMOVED
W/ContextImpl( 3542): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
,D/TaskPersister(  738): removeObsoleteFile: deleting file=216_task.xml
I/UpdateIcingCorporaServi( 1355): UpdateCorporaTask done [took 123 ms] updated apps [took 123 ms] 
,D/PackageBroadcastService( 1632): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1632): Clearing selected account for com.test.thalitest
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1085): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1085): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1085): run() : Loading LM = contacts
I/LocationSettingsChecker( 1632): Removing dialog suppression flag for package com.test.thalitest
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1085): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1085): run() : Loading LM = history
D/ChimeraCfgMgr( 1632): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1632): Module APK com.google.android.play.games already loaded
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1085): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1085): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1085): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1085): run() : Loaded (exit)
,I/Keyboard.Facilitator.Delight2FileSweeper( 1085): run()
,I/Keyboard.Facilitator.RecurringTaskScheduler( 1085): run()
I/StatsUtilsManager( 1085): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1085): shouldRecordStats() = Too Soon
,D/ChimeraCfgMgr( 1632): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1632): Module APK com.google.android.play.games already loaded
,E/NetworkScheduler.SchedulerReceiver( 1573): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1573): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,D/gH_CompatibleDatabase( 1632): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1632): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1632): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1632): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/gH_CompatibleDatabase( 1632): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
,D/gH_CompatibleDatabase( 1632): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1632): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 1632): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1632): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1632): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1632): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1632): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1632): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/ActivityManager(  738): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3574 uid=10039 gids={50039, 9997} abi=armeabi-v7a
,I/Launcher( 1279): Deferring update until onResume
,D/AndroidRuntime( 3501): Shutting down VM
,I/ActivityManager(  738): Killing 2655:com.android.settings/1000 (adj 15): empty #17
,D/WifiService(  738): Client connection lost with reason: 4
,W/ResourcesManager( 1279): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 1279): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Launcher( 1279): Deferring update until onResume
,W/libprocessgroup(  738): failed to open /acct/uid_1000/pid_2655/cgroup.procs: No such file or directory
,W/BaseAppContext( 1632): Using Auth Proxy for data requests.
,I/GMPM-SVC( 1632): App measurement is starting up, version: 8489
,I/GMPM-SVC( 1632): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,W/BaseAppContext( 1632): Using Auth Proxy for data requests.
,I/Icing   ( 1632): doRemovePackageData com.test.thalitest
,I/ActivityManager(  738): Killing 2530:com.google.android.gm/u0a70 (adj 15): empty #17
,I/ActivityManager(  738): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3602 uid=10007 gids={50007, 9997, 1028, 1015, 1023} abi=armeabi-v7a
,W/libprocessgroup(  738): failed to open /acct/uid_10070/pid_2530/cgroup.procs: No such file or directory
,I/ActivityManager(  738): Killing 1950:com.google.android.calendar/u0a31 (adj 15): empty #17
,W/libprocessgroup(  738): failed to open /acct/uid_10031/pid_1950/cgroup.procs: No such file or directory
,D/ExternalStorage( 3602): After updating volumes, found 1 active roots

```
