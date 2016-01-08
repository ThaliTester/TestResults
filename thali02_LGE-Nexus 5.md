#### Test 549702610b97681_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
I/GAv4    ( 3109): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3109):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3109):   adb logcat -s GAv4
W/GAv4    ( 3109): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3109): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3109): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 3109): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
D/Finsky  ( 2580): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
W/ResourcesManager( 3109): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3109): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  752): Killing 2539:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
V/JNIHelp ( 3109): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/libprocessgroup(  752): failed to open /acct/uid_10069/pid_2539/cgroup.procs: No such file or directory
W/System  ( 3109): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3109): Installed default security provider GmsCore_OpenSSL
V/GLSActivity( 1597): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 1577): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/Icing   ( 1577): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/Icing   ( 1577): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1577): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
,D/AndroidRuntime( 3175): 
D/AndroidRuntime( 3175): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3175): CheckJNI is OFF
D/AndroidRuntime( 3175): Calling main entry com.android.commands.am.Am
I/ActivityManager(  752): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  752): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3199 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3175): Shutting down VM
V/ActivityManager(  752): Display changed displayId=0
I/ActivityManager(  752): Killing 2493:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
I/WebViewFactory( 3199): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
W/libprocessgroup(  752): failed to open /acct/uid_10045/pid_2493/cgroup.procs: No such file or directory
I/LibraryLoader( 3199): Time to load native libraries: 1 ms (timestamps 7453-7454)
I/LibraryLoader( 3199): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3199): Binding Chromium to main looper Looper (main, tid 1) {37e903e8}
I/LibraryLoader( 3199): Expected native library version number "",actual native library version number ""
I/chromium( 3199): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3199): Initializing chromium process, singleProcess=true
W/art     ( 3199): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3199): ApplicationContext is null in ApplicationStatus
W/chromium( 3199): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3199): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3199): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3199): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  752): Message: 20
D/BluetoothManagerService(  752): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3ce1d2fe:true
,W/art     ( 3199): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3199): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3199): CordovaWebView is running on device made by: LGE
,W/art     ( 3199): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3199): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3199): Render dirty regions requested: true
,D/Atlas   ( 3199): Validating map...
,W/chromium( 3199): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3199): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3199): Enabling debug mode 0
,I/Keyboard.Facilitator( 1087): onFinishInput()
,W/IInputConnectionWrapper( 3199): showStatusIcon on inactive InputConnection
,I/ActivityManager(  752): Displayed com.test.thalitest/.MainActivity: +404ms (total +57s402ms)
,W/BindingManager( 3199): Cannot call determinedVisibility() - never saw a connection for the pid: 3199
,D/JsMessageQueue( 3199): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3199): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257342720
D/JX-Cordova( 3199): jxcore cordova android initializing
,W/jxcore-log( 3199): Initializing JXcore engine
W/jxcore-log( 3199): JXcore engine is ready
,W/jxcore-log( 3199): Starting JXcore engine
,W/.test.thalitest( 3199): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[7927]" dev="sockfs" ino=7927 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3199): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 3199): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6906]" dev="sockfs" ino=6906 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3199): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[18166]" dev="sockfs" ino=18166 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3199): Platform android
W/jxcore-log( 3199): 
,W/jxcore-log( 3199): Process ARCH arm
W/jxcore-log( 3199): 
,I/jxcore-log( 3199): JXcore Cordova bridge is ready!
I/jxcore-log( 3199): 
W/jxcore-log( 3199): JXcore engine is started
,I/Choreographer( 3199): Skipped 108 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3199): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3199): Toggling radios to true
I/jxcore-log( 3199): 
,D/BluetoothAdapter( 3199): enable(): BT is already enabled..!
,D/WifiService(  752): New client listening to asynchronous messages
,D/WifiService(  752): setWifiEnabled: true pid=3199, uid=10270
E/WifiService(  752): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3199): Radios toggled
I/jxcore-log( 3199): 
,I/jxcore-log( 3199): My device name is: LGE-Nexus 5
I/jxcore-log( 3199): 
,I/wpa_supplicant( 1047): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  752): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  752): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
E/native  (  752): do suspend true
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1597): Read error: ssl=0x9b43be00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1597): SSL shutdown failed: ssl=0x9b43be00: I/O error during system call, Broken pipe
,D/ConnectivityService(  752): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  752): ValidatedState{ when=-1ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  752): DefaultState{ when=-1ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  752): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  752): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  752): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  752): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,E/WifiConfigStore(  752): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  752): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  752): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,E/WifiStateMachine(  752): Start Disconnecting Watchdog 1
,I/wpa_supplicant( 1047): wlan0: CTRL-EVENT-SCAN-STARTED 
,E/native  (  752): do suspend true
,W/ProcessCpuTracker(  752): Skipping unknown process pid 3259
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,D/ConnectivityService(  752): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/Nat464Xlat(  752): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  752): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityManager.CallbackHandler(  901): CM callback handler got msg 524292
D/ConnectivityService(  752): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  752): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  752): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  752): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  752): Disconnected - quitting
D/ConnectivityManager.CallbackHandler( 1577): CM callback handler got msg 524292
,D/ConnectivityService(  752): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1221): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WifiNetworkAgent(  752): NetworkAgent: NetworkAgent channel lost
,V/GLSActivity( 1597): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1597): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/NetworkUtils( 1367): OkHttp exception
,W/EventLoggerService( 1367): Unable to send logs Error code: 262146
,I/wpa_supplicant( 1047): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant( 1047): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1047): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1047): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  752): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  752): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  752): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  752): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  179): Setting iface cfg
,E/WifiStateMachine(  752): Start Dhcp Watchdog 2
,E/native  (  752): do suspend false
,E/WifiStateMachine(  752): scanCount==0 - aborting
,I/dhcpcd  ( 3279): version 5.5.6 starting
E/dhcpcd  ( 3279): get_duid: Read-only file system
,I/dhcpcd  ( 3279): wlan0: rebinding lease of 192.168.1.114
,I/dhcpcd  ( 3279): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,D/ConnectivityService(  752): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  752): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  752): MasterInitialState.processMessage what=3
,D/Tethering(  752): MasterInitialState.processMessage what=3
,I/dhcpcd  ( 3279): wlan0: leased 192.168.1.114 for 86400 seconds
,V/MusicLeanback( 2683): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1577): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1577): onCreate
,D/SystemUpdateService( 1577): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1577): active receiver: enabled
,I/SystemUpdateService( 1577): showing system update notification
,I/iu.Environment( 1577): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
I/iu.UploadsManager( 1577): num queued entries: 0
I/iu.UploadsManager( 1577): num updated entries: 0
I/iu.SyncManager( 1577): NEXT; no task
,I/Babel   ( 1895): connection state changed from CONNECTED to DISCONNECTED
,I/ValidateNoPeople(  752): skipping global notification
,V/SystemUpdateService( 1577): retry (wakeup: false) in 3599972 ms
,I/ActivityManager(  752): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3315 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/SystemUpdateService( 1577): onDestroy
,E/GpsLocationProvider(  752): No APN found to select.
,E/GpsLocationProvider(  752): No APN found to select.
,I/GAv4    ( 3315): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3315):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3315):   adb logcat -s GAv4
,W/GAv4    ( 3315): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3315): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3315): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,E/native  (  752): do suspend true
,D/ConnectivityService(  752): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  752): Adding iface wlan0 to network 101
,E/WifiStateMachine(  752): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
E/ConnectivityService(  752): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  752): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/ConnectivityService(  752): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  752): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/ConnectivityService(  752): Setting Dns servers for network 101 to [/192.168.1.1]
D/Nat464Xlat(  752): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  752): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  752): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  752): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  752):    accepting network in place of null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  752): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  752): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  752): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  752): Checking http://clients3.google.com/generate_204 on "NG7005g"
D/CSLegacyTypeTracker(  752): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  752): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  752): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::5255:27ff:fef0:fd0b/64,192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  752): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  901): CM callback handler got msg 524290
D/ConnectivityManager.CallbackHandler( 1577): CM callback handler got msg 524290
,I/WebViewFactory( 3315): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  752): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 08 Jan 2016 23:04:52 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452294292782], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452294292766]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  752): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  752): Validated
D/ConnectivityService(  752): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  752): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  752): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  752): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  752): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/TelephonyNetworkFactory( 1221): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler(  901): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1577): CM callback handler got msg 524290
,I/LibraryLoader( 3315): Time to load native libraries: 1 ms (timestamps 3538-3539)
I/LibraryLoader( 3315): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3315): Binding Chromium to main looper Looper (main, tid 1) {2e3facbc}
,I/LibraryLoader( 3315): Expected native library version number "",actual native library version number ""
I/chromium( 3315): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3315): Initializing chromium process, singleProcess=true
,W/art     ( 3315): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3315): ApplicationContext is null in ApplicationStatus
,W/chromium( 3315): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3315): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 3315): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3315): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/AudioManagerAndroid( 3315): Requires BLUETOOTH permission
,I/NSApplication( 3315): Starting up...
,I/ActivityManager(  752): Killing 2661:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/libprocessgroup(  752): failed to open /acct/uid_10003/pid_2661/cgroup.procs: No such file or directory
,V/MusicLeanback( 2683): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1577): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1577): onCreate
,D/SystemUpdateService( 1577): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1577): active receiver: enabled
,I/SystemUpdateService( 1577): showing system update notification
,I/iu.Environment( 1577): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1577): num queued entries: 0
I/iu.UploadsManager( 1577): num updated entries: 0
I/iu.SyncManager( 1577): NEXT; no task
,I/ValidateNoPeople(  752): skipping global notification
,V/SystemUpdateService( 1577): retry (wakeup: false) in 3599961 ms
,D/SystemUpdateService( 1577): onDestroy
,I/Babel   ( 1895): connection state changed from DISCONNECTED to CONNECTED
,D/ConnectivityService(  752): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/jxcore-log( 3199): Test app app.js loaded
I/jxcore-log( 3199): 
,I/Choreographer( 3199): Skipped 373 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3199): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/ConnectivityService(  752): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  752): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2683): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2683): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1577): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1577): onCreate
,D/SystemUpdateService( 1577): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1577): active receiver: enabled
,I/SystemUpdateService( 1577): showing system update notification
,I/ValidateNoPeople(  752): skipping global notification
,V/SystemUpdateService( 1577): retry (wakeup: false) in 3599990 ms
,D/SystemUpdateService( 1577): onDestroy
,I/art     (  752): Explicit concurrent mark sweep GC freed 46515(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 27MB/41MB, paused 1.065ms total 110.055ms
,E/GpsLocationProvider(  752): No APN found to select.
,D/Finsky  ( 2580): [255] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2580): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/GLSActivity( 1597): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1597): Vacuum at: now=1452294304862 tag=VacuumService
,I/Keyboard.Facilitator.LanguageModelFlusher( 1087): run()
I/Keyboard.Facilitator( 1087): flushDynamicLanguageModels()
,I/ConfigService( 1597): onCreate
,I/ConfigService( 1597): onDestroy
,I/ClearcutLoggerApiImpl( 1597): disconnect managed GoogleApiClient
,I/jxcore-log( 3199): --= Surplus to requirements =--
I/jxcore-log( 3199): 
I/jxcore-log( 3199): ****TEST TOOK:  ms ****
I/jxcore-log( 3199): 
I/jxcore-log( 3199): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3199): 
,D/AndroidRuntime( 3505): 
D/AndroidRuntime( 3505): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 3505): CheckJNI is OFF
,D/AndroidRuntime( 3505): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  752): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  752): Killing 3199:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
,I/WindowState(  752): WIN DEATH: Window{24a6f7ae u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  752): Client connection lost with reason: 4
,I/ActivityManager(  752):   Force finishing activity ActivityRecord{37b5ad5a u0 com.test.thalitest/.MainActivity t214}
,W/PackageSettings(  752): Skipping PackageSetting{211c5ffc com.example.hello/10278} due to missing metadata
,W/ActivityManager(  752): Spurious death for ProcessRecord{314c8c91 3199:com.test.thalitest/u0a270}, curProc for 3199: null
,I/ActivityManager(  752): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
I/ActivityManager(  752):   Force finishing activity ActivityRecord{37b5ad5a u0 com.test.thalitest/.MainActivity t214 f}
W/ActivityManager(  752): Duplicate finish request for ActivityRecord{37b5ad5a u0 com.test.thalitest/.MainActivity t214 f}
,I/art     ( 1275): Explicit concurrent mark sweep GC freed 3970(295KB) AllocSpace objects, 1(126KB) LOS objects, 23% free, 25MB/33MB, paused 479us total 31.553ms
,I/art     ( 1367): Explicit concurrent mark sweep GC freed 8700(592KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 18MB/25MB, paused 308us total 64.336ms
,W/GeofencerStateMachine( 1597): Ignoring removeGeofence because network location is disabled.
,I/InputReader(  752): Reconfiguring input devices.  changes=0x00000010
,I/Keyboard.Facilitator( 1087): resetDictionaries() : en_US
,I/art     (  752): Explicit concurrent mark sweep GC freed 15776(961KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 1.905ms total 73.266ms
,I/art     ( 1577): Explicit concurrent mark sweep GC freed 25412(1551KB) AllocSpace objects, 5(80KB) LOS objects, 24% free, 22MB/30MB, paused 443us total 95.324ms
,I/Keyboard.Facilitator.DecoderInitializer( 1087): run()
,D/VoicemailCleanupService( 2805): Cleaning up data for package: com.test.thalitest
,I/Decoder ( 1087): createOrResetDecoder
,I/UpdateIcingCorporaServi( 1367): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,W/Launcher( 1275): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@3ad78a01 new=com.google.android.velvet.VelvetApplication@3ad78a01
,I/Adreno-EGL(  946): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/OpenGLRenderer(  946): Initialized EGL, version 1.4
,D/OpenGLRenderer(  946): Enabling debug mode 0
,I/ActivityManager(  752): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3544 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,D/BackupManagerService(  752): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  752): Receieved: android.intent.action.PACKAGE_REMOVED
I/ConfigService( 1597): onCreate
,D/TaskPersister(  752): removeObsoleteFile: deleting file=214_task.xml
,I/art     (  752): Explicit concurrent mark sweep GC freed 6025(335KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 3.337ms total 135.560ms
,W/InputMethodManagerService(  752): Focus gain on non-focused client com.android.internal.view.IInputMethodClient$Stub$Proxy@1c245b78 (uid=10034 pid=946)
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1087): run()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1087): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1087): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1087): run() : Loading LM = contacts
,W/ContextImpl( 3544): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
I/UpdateIcingCorporaServi( 1367): UpdateCorporaTask done [took 130 ms] updated apps [took 130 ms] 
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1087): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1087): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1087): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1087): run() : Loading LM = user
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1087): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1087): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1087): run()
,I/Keyboard.Facilitator.RecurringTaskScheduler( 1087): run()
I/StatsUtilsManager( 1087): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1087): shouldRecordStats() = Too Soon
,D/PackageBroadcastService( 1577): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1577): Clearing selected account for com.test.thalitest
,I/LocationSettingsChecker( 1577): Removing dialog suppression flag for package com.test.thalitest
,I/ActivityManager(  752): Killing 2631:com.android.settings/1000 (adj 15): empty #17
,D/WifiService(  752): Client connection lost with reason: 4
,W/InputMethodManagerService(  752): Got RemoteException sending setActive(false) notification to pid 3199 uid 10270
D/gH_CompatibleDatabase( 1577): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1577): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
I/Keyboard.Facilitator( 1087): onFinishInput()
D/gH_MetricsDatabase( 1577): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1577): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/gH_CompatibleDatabase( 1577): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1577): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/gH_CompatibleDatabase( 1577): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/gH_CompatibleDatabase( 1577): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1577): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 1577): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,D/gH_CompatibleDatabase( 1577): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1577): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1577): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,D/AndroidRuntime( 3505): Shutting down VM
,D/ChimeraCfgMgr( 1577): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1577): Module APK com.google.android.play.games already loaded
,W/libprocessgroup(  752): failed to open /acct/uid_1000/pid_2631/cgroup.procs: No such file or directory
,I/Launcher( 1275): Deferring update until onResume
,W/ResourcesManager( 1275): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/ChimeraCfgMgr( 1577): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1577): Module APK com.google.android.play.games already loaded
E/NetworkScheduler.SchedulerReceiver( 1597): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1597): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,W/ResourcesManager( 1275): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Launcher( 1275): Deferring update until onResume
,W/FileUtils( 1577): Failed to chmod(/data/data/com.google.android.gms/databases/phenotype.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,E/SQLiteLog( 1577): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,--------- beginning of crash
E/AndroidRuntime( 1577): FATAL EXCEPTION: PlayGamesAsyncThread1
E/AndroidRuntime( 1577): Process: com.google.android.gms, PID: 1577
E/AndroidRuntime( 1577): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1577): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 1577): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AndroidRuntime( 1577): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 1577): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 1577): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AndroidRuntime( 1577): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
E/AndroidRuntime( 1577): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 1577): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 1577): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 1577): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:309)
E/AndroidRuntime( 1577): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
E/AndroidRuntime( 1577): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3146)
E/AndroidRuntime( 1577): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 1577): 	at com.google.android.gms.games.service.operations.GamesOperationAdapter.execute(GamesOperationAdapter.java:23)
E/AndroidRuntime( 1577): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 1577): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 1577): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 1577): 	at java.lang.Thread.run(Thread.java:818)
,I/ActivityManager(  752): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3591 uid=10039 gids={50039, 9997} abi=armeabi-v7a
,I/Process ( 1577): Sending signal. PID: 1577 SIG: 9
,E/DropBoxManagerService(  752): Can't write: system_app_crash
E/DropBoxManagerService(  752): java.io.FileNotFoundException: /data/system/dropbox/drop95.tmp: open failed: EROFS (Read-only file system),
E/DropBoxManagerService(  752): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  752): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  752): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  752): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  752): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  752): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12006)
E/DropBoxManagerService(  752): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  752): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  752): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  752): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  752): 	... 5 more

```
