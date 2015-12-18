#### Test 50650278d76d9c3_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
I/GAv4    ( 3208): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3208):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3208):   adb logcat -s GAv4
W/GAv4    ( 3208): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3208): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3208): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 3208): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
,D/Finsky  ( 2654): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
W/ResourcesManager( 3208): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3208): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  759): Killing 2621:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
V/JNIHelp ( 3208): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/System  ( 3208): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3208): Installed default security provider GmsCore_OpenSSL
W/libprocessgroup(  759): failed to open /acct/uid_10069/pid_2621/cgroup.procs: No such file or directory
V/GLSActivity( 1553): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/AndroidRuntime( 3261): 
D/AndroidRuntime( 3261): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3261): CheckJNI is OFF
D/AndroidRuntime( 3261): Calling main entry com.android.commands.am.Am
I/ActivityManager(  759): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  759): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3288 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3261): Shutting down VM
V/ActivityManager(  759): Display changed displayId=0
I/Icing   ( 1650): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/Icing   ( 1650): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1650): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/WebViewFactory( 3288): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/Icing   ( 1650): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
I/LibraryLoader( 3288): Time to load native libraries: 2 ms (timestamps 6739-6741)
I/LibraryLoader( 3288): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3288): Binding Chromium to main looper Looper (main, tid 1) {a35532e}
I/LibraryLoader( 3288): Expected native library version number "",actual native library version number ""
I/chromium( 3288): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3288): Initializing chromium process, singleProcess=true
W/art     ( 3288): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3288): ApplicationContext is null in ApplicationStatus
W/chromium( 3288): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3288): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3288): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3288): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
D/BluetoothManagerService(  759): Message: 20
D/BluetoothManagerService(  759): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@22d59415:true
W/art     ( 3288): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 3288): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 3288): CordovaWebView is running on device made by: LGE
W/art     ( 3288): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3288): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 3288): Render dirty regions requested: true
D/Atlas   ( 3288): Validating map...
W/chromium( 3288): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/OpenGLRenderer( 3288): Initialized EGL, version 1.4
D/OpenGLRenderer( 3288): Enabling debug mode 0
I/Keyboard.Facilitator( 1071): onFinishInput()
W/BindingManager( 3288): Cannot call determinedVisibility() - never saw a connection for the pid: 3288
I/ActivityManager(  759): Displayed com.test.thalitest/.MainActivity: +490ms (total +55s13ms)
W/IInputConnectionWrapper( 3288): showStatusIcon on inactive InputConnection
D/JsMessageQueue( 3288): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 3288): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257332480
D/JX-Cordova( 3288): jxcore cordova android initializing
I/ActivityManager(  759): Killing 2577:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
W/libprocessgroup(  759): failed to open /acct/uid_10045/pid_2577/cgroup.procs: No such file or directory
,W/jxcore-log( 3288): Initializing JXcore engine
W/jxcore-log( 3288): JXcore engine is ready
,W/jxcore-log( 3288): Starting JXcore engine
,W/.test.thalitest( 3288): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[9390]" dev="sockfs" ino=9390 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3288): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 3288): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[9484]" dev="sockfs" ino=9484 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3288): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[19962]" dev="sockfs" ino=19962 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3288): Platform android
W/jxcore-log( 3288): 
,W/jxcore-log( 3288): Process ARCH arm
W/jxcore-log( 3288): 
,I/jxcore-log( 3288): JXcore Cordova bridge is ready!
I/jxcore-log( 3288): 
,W/jxcore-log( 3288): JXcore engine is started
,I/Choreographer( 3288): Skipped 111 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3288): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3288): Toggling radios to true
I/jxcore-log( 3288): 
,D/BluetoothAdapter( 3288): enable(): BT is already enabled..!
,D/WifiService(  759): New client listening to asynchronous messages
,D/WifiService(  759): setWifiEnabled: true pid=3288, uid=10270
E/WifiService(  759): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3288): Radios toggled
I/jxcore-log( 3288): 
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 3288): Got Device Bluetooth address: 34:FC:EF:11:AE:67
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): Perf Test app loaded loaded
I/jxcore-log( 3288): 
I/jxcore-log( 3288): check test folder
I/jxcore-log( 3288): 
I/jxcore-log( 3288): found test : ./testFindPeers.js
I/jxcore-log( 3288): 
I/wpa_supplicant(  991): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  759): WifiStateMachine: Leaving Connected state
,E/WifiConfigStore(  759): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/native  (  759): do suspend true
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,I/jxcore-log( 3288): found test : ./testSendData.js
I/jxcore-log( 3288): 
,V/NativeCrypto( 1553): Read error: ssl=0xafe47e00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1553): SSL shutdown failed: ssl=0xafe47e00: I/O error during system call, Broken pipe
,D/ConnectivityService(  759): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): ValidatedState{ when=-1ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): DefaultState{ when=-1ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Checking http://clients3.google.com/generate_204 on "NG7005g"
,E/WifiConfigStore(  759): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  759): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  759): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/ConnectivityService(  759): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/Nat464Xlat(  759): requiresClat: netType=1, connected=false, hasIPv4Address=true
,D/ConnectivityManager.CallbackHandler(  896): CM callback handler got msg 524292
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): EvaluatingState{ when=-3ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): DefaultState{ when=-3ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityManager.CallbackHandler( 1650): CM callback handler got msg 524292
D/CSLegacyTypeTracker(  759): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Disconnected - quitting
E/WifiStateMachine(  759): Start Disconnecting Watchdog 1
D/ConnectivityService(  759): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  759): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  759): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory( 1154): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/wpa_supplicant(  991): wlan0: CTRL-EVENT-SCAN-STARTED 
,E/native  (  759): do suspend true
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,I/Choreographer( 3288): Skipped 66 frames!  The application may be doing too much work on its main thread.
I/chromium( 3288): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/WifiNetworkAgent(  759): NetworkAgent: NetworkAgent channel lost
,I/ActivityManager(  759): Killing 2747:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/libprocessgroup(  759): failed to open /acct/uid_10003/pid_2747/cgroup.procs: No such file or directory
,I/wpa_supplicant(  991): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant(  991): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant(  991): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant(  991): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  759): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  759): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  759): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  759): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  179): Setting iface cfg
,E/WifiStateMachine(  759): Start Dhcp Watchdog 2
,E/native  (  759): do suspend false
,E/WifiStateMachine(  759): scanCount==0 - aborting
,I/dhcpcd  ( 3398): version 5.5.6 starting
,E/dhcpcd  ( 3398): get_duid: Read-only file system
,I/dhcpcd  ( 3398): wlan0: rebinding lease of 192.168.1.114
,V/GLSActivity( 1553): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1553): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/NetworkUtils( 1375): OkHttp exception
,W/EventLoggerService( 1375): Unable to send logs Error code: 262146
,I/dhcpcd  ( 3398): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3398): wlan0: leased 192.168.1.114 for 86400 seconds
,D/ConnectivityService(  759): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  759): MasterInitialState.processMessage what=3
,D/ConnectivityService(  759): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  759): MasterInitialState.processMessage what=3
,V/MusicLeanback( 2770): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1650): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,E/GpsLocationProvider(  759): No APN found to select.
,D/SystemUpdateService( 1650): onCreate
,D/SystemUpdateService( 1650): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1650): active receiver: enabled
,E/GpsLocationProvider(  759): No APN found to select.
,I/iu.Environment( 1650): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/SystemUpdateService( 1650): showing system update notification
,I/iu.UploadsManager( 1650): num queued entries: 0
I/iu.UploadsManager( 1650): num updated entries: 0
,I/iu.SyncManager( 1650): NEXT; no task
,I/Babel   ( 1936): connection state changed from CONNECTED to DISCONNECTED
,I/ValidateNoPeople(  759): skipping global notification
,V/SystemUpdateService( 1650): retry (wakeup: false) in 3599979 ms
,I/ActivityManager(  759): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3446 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/SystemUpdateService( 1650): onDestroy
,E/native  (  759): do suspend true
,D/ConnectivityService(  759): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  759): Adding iface wlan0 to network 101
E/WifiStateMachine(  759): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  759): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  759): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  759): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  759): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  759): Setting Dns servers for network 101 to [/192.168.1.1]
D/Nat464Xlat(  759): requiresClat: netType=1, connected=true, hasIPv4Address=true
,D/ConnectivityService(  759): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  759): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  759): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  759):    accepting network in place of null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/CSLegacyTypeTracker(  759): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,D/ConnectivityService(  759): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  759): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::5255:27ff:fef0:fd0b/64,192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  759): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  896): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1650): CM callback handler got msg 524290
,I/GAv4    ( 3446): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3446):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3446):   adb logcat -s GAv4
,W/GAv4    ( 3446): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3446): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3446): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 18 Dec 2015 18:33:55 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450463634859], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450463634839]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Validated
D/ConnectivityService(  759): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  759): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  759): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  759): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  896): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1650): CM callback handler got msg 524290
,D/TelephonyNetworkFactory( 1154): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  759): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,I/WebViewFactory( 3446): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3446): Time to load native libraries: 1 ms (timestamps 3795-3796)
I/LibraryLoader( 3446): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3446): Binding Chromium to main looper Looper (main, tid 1) {17c93df0}
,I/LibraryLoader( 3446): Expected native library version number "",actual native library version number ""
,I/chromium( 3446): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3446): Initializing chromium process, singleProcess=true
,W/art     ( 3446): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3446): ApplicationContext is null in ApplicationStatus
,W/chromium( 3446): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3446): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3446): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3446): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/AudioManagerAndroid( 3446): Requires BLUETOOTH permission
,I/NSApplication( 3446): Starting up...
,I/ActivityManager(  759): Killing 2722:com.android.settings/1000 (adj 15): empty #17
,D/WifiService(  759): Client connection lost with reason: 4
,W/libprocessgroup(  759): failed to open /acct/uid_1000/pid_2722/cgroup.procs: No such file or directory
,V/MusicLeanback( 2770): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1650): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1650): onCreate
,D/SystemUpdateService( 1650): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1650): active receiver: enabled
,I/SystemUpdateService( 1650): showing system update notification
,I/iu.Environment( 1650): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1650): num queued entries: 0
I/iu.UploadsManager( 1650): num updated entries: 0
,I/iu.SyncManager( 1650): NEXT; no task
,I/ValidateNoPeople(  759): skipping global notification
,V/SystemUpdateService( 1650): retry (wakeup: false) in 3599984 ms
,D/SystemUpdateService( 1650): onDestroy
,I/Babel   ( 1936): connection state changed from DISCONNECTED to CONNECTED
,D/ConnectivityService(  759): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network,
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): setDiscoveryMode: Mode set to WIFI
,I/jxcore-log( 3288): BLE supported!!
I/jxcore-log( 3288): 
,D/ConnectivityService(  759): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  759): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2770): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2770): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1650): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1650): onCreate
,D/SystemUpdateService( 1650): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1650): active receiver: enabled
,I/SystemUpdateService( 1650): showing system update notification
,I/ValidateNoPeople(  759): skipping global notification
,V/SystemUpdateService( 1650): retry (wakeup: false) in 3599962 ms
,I/art     (  759): Explicit concurrent mark sweep GC freed 43152(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 27MB/41MB, paused 873us total 78.809ms
,D/SystemUpdateService( 1650): onDestroy
,E/GpsLocationProvider(  759): No APN found to select.
,D/Finsky  ( 2654): [255] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2654): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/HeadsetStateMachine( 2142): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 2142): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
D/HeadsetStateMachine( 2142): Disconnected process message: 11, size: 0
,I/Keyboard.Facilitator.LanguageModelFlusher( 1071): run()
I/Keyboard.Facilitator( 1071): flushDynamicLanguageModels()
,I/ConfigService( 1553): onCreate
,I/ConfigService( 1553): onDestroy
,I/EventLogService( 1650): Aggregate from 1450461851426 (log), 1450461851426 (data)
,V/GLSActivity( 1553): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1553): Vacuum at: now=1450463700205 tag=VacuumService
,I/PhenotypeConfigurator( 1553): Scheduling Phenotype for one-off execution 12876 seconds from now (1450463700442)
,D/GetConfigurationSnapshotOperation( 1553): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1553): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1553): Using platform SSLCertificateSocketFactory
,V/GLSActivity( 1553): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1553): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ClearcutLoggerApiImpl( 1553): disconnect managed GoogleApiClient
,I/jxcore-log( 3288): Connected to the server!
I/jxcore-log( 3288): 
,I/chromium( 3288): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3288): --- start :testSendData.js---
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): testSendData created {"name":"testSendData.js","serverTimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":15}bt-address length : 0
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): daya100000
I/jxcore-log( 3288): 
I/jxcore-log( 3288): check server
I/jxcore-log( 3288): 
I/jxcore-log( 3288): serverPort is 60252
I/jxcore-log( 3288): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): setDiscoveryMode: Mode set to WIFI
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3288): start: Peer ID: 34:FC:EF:11:AE:67, peer name: LGE-Nexus 5_PT491
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3288): bind: Binding a new listener
D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3288): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3288): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT491","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3288): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3288): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3288): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3288): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3288): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3288): start: OK
I/io.jxcore.node.ConnectionHelper( 3288): start: Using peer discovery mode: WIFI
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): start: Peer ID: 34:FC:EF:11:AE:67, peer name: LGE-Nexus 5_PT491
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3288): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT491","ra":"34:FC:EF:11:AE:67"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3288): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT491","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3288): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT491","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3288): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3288): start: OK
I/jxcore-log( 3288): StartBroadcasting started ok
I/jxcore-log( 3288): 
I/jxcore-log( 3288): null
I/jxcore-log( 3288): 
I/jxcore-log( 3288): 2015-12-18T18:40:06.178Z SendDataTCPServer.js: TCP/IP server is bound to port: 60252
I/jxcore-log( 3288): 
I/chromium( 3288): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
I/io.jxcore.node.ConnectionHelper( 3288): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3288): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3288): onDiscoveryManagerStateChanged: RUNNING
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  991): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/WifiP2pManager( 3288): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): Service request added successfully
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): Service discovery started successfully
,W/bt-btif ( 2142): info:x10
,D/        ( 2142): remote version info [58:3f:54:73:64:c0]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 2142): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 2142): bondStateChangeCallback: Status: 0 Address: 58:3F:54:73:64:C0 newState: 1
E/bt-btif ( 2142): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2142): Bond State Change Intent:58:3F:54:73:64:C0 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 2142): Entering PendingCommandState State
,I/ActivityManager(  759): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.BluetoothPairingRequest: pid=3639 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,D/BluetoothManagerService(  759): Message: 20
D/BluetoothManagerService(  759): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5875038:true
,I/ActivityManager(  759): Killing 2595:com.google.android.gm/u0a70 (adj 15): empty #17
,I/BluetoothBondStateMachine( 2142): bondStateChangeCallback: Status: 0 Address: 58:3F:54:73:64:C0 newState: 0
,D/BluetoothAdapterProperties( 2142): Failed to remove device: 58:3F:54:73:64:C0
,W/bt-btif ( 2142): new conn_srvc id:26, app_id:255
W/bt-btif ( 2142): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2142): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3288): Incoming connection accepted
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3288): Incoming connection initialized (thread ID: 308)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3288): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3288): Entering thread (ID: 308)
,W/libprocessgroup(  759): failed to open /acct/uid_10070/pid_2595/cgroup.procs: No such file or directory
I/BluetoothBondStateMachine( 2142): Bond State Change Intent:58:3F:54:73:64:C0 OldState: 11 NewState: 10
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3288): onBytesRead: Read 77 bytes successfully (thread ID: 308)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3288): Got valid identity from [58:3F:54:73:64:C0 LGE-LG-D855_PT7178]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3288): onBytesWritten: 76 bytes successfully written (thread ID: 308)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3288): removeThreadFromList: Removing thread with ID 308
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3288): Handshake thread disposed (thread ID: 308)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3288): onIncomingConnectionConnected: [58:3F:54:73:64:C0 LGE-LG-D855_PT7178]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3288): Exiting thread (ID: 308)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3288): onConnected: [58:3F:54:73:64:C0 LGE-LG-D855_PT7178]
,I/io.jxcore.node.ConnectionHelper( 3288): onConnected: Incoming connection to peer [58:3F:54:73:64:C0 LGE-LG-D855_PT7178]
,D/io.jxcore.node.ConnectionHelper( 3288): hasConnection: No connection with peer with ID 58:3F:54:73:64:C0
,D/io.jxcore.node.ConnectionHelper( 3288): notifyPeerAvailability: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT7178] is available
,I/jxcore-log( 3288): peerAvailabilityChanged [{"peerIdentifier":"58:3F:54:73:64:C0","peerName":"LGE-LG-D855_PT7178","peerAvailable":true}]
I/jxcore-log( 3288): 
I/jxcore-log( 3288): Found peer : LGE-LG-D855_PT7178, Available: true
I/jxcore-log( 3288): 
I/jxcore-log( 3288): startWithNextDevice
I/jxcore-log( 3288): 
I/jxcore-log( 3288): device[1]: 58:3F:54:73:64:C0
I/jxcore-log( 3288): 
I/jxcore-log( 3288): 2015-12-18T18:40:11.738Z SendDataConnector.js: Start called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:11.739Z SendDataConnector.js: doConnect called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3288): 
I/jxcore-log( 3288): 2015-12-18T18:40:11.739Z SendDataConnector.js: do connect now
I/jxcore-log( 3288): 
I/io.jxcore.node.ConnectionHelper( 3288): connect: Trying to connect to peer with ID 58:3F:54:73:64:C0
D/io.jxcore.node.ConnectionHelper( 3288): hasConnection: No connection with peer with ID 58:3F:54:73:64:C0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3288): connect: [58:3F:54:73:64:C0 LGE-LG-D855_PT7178]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3288): connect: Trying to start connecting to G3-1 in address 58:3F:54:73:64:C0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): setInsecureRfcommSocketPort: Using port -1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3288): onConnecting: G3-1 58:3F:54:73:64:C0
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3288): connect: Started connecting to G3-1 in address 58:3F:54:73:64:C0
I/io.jxcore.node.ConnectionHelper( 3288): connect: Connection process successfully started (peer ID: 58:3F:54:73:64:C0)
,I/io.jxcore.node.ConnectionHelper( 3288): onConnected: Incoming socket thread, for peer [58:3F:54:73:64:C0 LGE-LG-D855_PT7178], created successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): Trying to connect to peer with address 58:3F:54:73:64:C0 (thread ID: 309)
D/io.jxcore.node.ConnectionHelper( 3288): onConnected: The total number of connections is now 1
W/BluetoothAdapter( 3288): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2142): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/io.jxcore.node.IncomingSocketThread( 3288): Entering thread (ID: 310)
,I/io.jxcore.node.IncomingSocketThread( 3288): Local host address: localhost/127.0.0.1, port: 60252
,D/io.jxcore.node.IncomingSocketThread( 3288): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3288): setBufferSize: Setting buffer size to 8192 bytes
I/jxcore-log( 3288): 2015-12-18T18:40:11.753Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3288): 
,I/io.jxcore.node.StreamCopyingThread( 3288): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3288): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3288): Exiting thread (ID: 310)
,D/io.jxcore.node.StreamCopyingThread( 3288): Entering thread (ID: 312, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3288): Entering thread (ID: 311, name: Sender)
,I/BluetoothBondStateMachine( 2142): StableState(): Entering Off State
,W/bt-sdp  ( 2142): process_service_search_attr_rsp
,W/bt-btif ( 2142): new conn_srvc id:26, app_id:1
W/bt-btif ( 2142): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2142): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2142): bta_dm_pm_ssr:2, lat:1200
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3288): onSocketConnected: [58:3F:54:73:64:C0 LGE-LG-D855_PT7178]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 309)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): onBytesWritten: 76 bytes successfully written (thread ID: 313)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): Outgoing connection initialized (*handshake* thread ID: 313)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): Exiting thread (thread ID: 309)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3288): Entering thread (ID: 313)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): onBytesRead: Read 77 bytes successfully (thread ID: 313)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): Handshake succeeded with [58:3F:54:73:64:C0 LGE-LG-D855_PT7178]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3288): onHandshakeSucceeded: [58:3F:54:73:64:C0 LGE-LG-D855_PT7178]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3288): Exiting thread (ID: 313)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3288): onConnected: [58:3F:54:73:64:C0 LGE-LG-D855_PT7178]
I/io.jxcore.node.ConnectionHelper( 3288): onConnected: Outgoing connection to peer [58:3F:54:73:64:C0 LGE-LG-D855_PT7178]
D/io.jxcore.node.ConnectionHelper( 3288): hasConnection: We have an incoming connection with peer with ID 58:3F:54:73:64:C0
W/io.jxcore.node.ConnectionHelper( 3288): onConnected: Already connected with peer [58:3F:54:73:64:C0 LGE-LG-D855_PT7178], continuing anyway...
,W/io.jxcore.node.ConnectionHelper( 3288): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT7178] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 3288): onConnected: Outgoing socket thread, for peer [58:3F:54:73:64:C0 LGE-LG-D855_PT7178], created successfully
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3288): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 3288): onConnected: The total number of connections is now 2
D/io.jxcore.node.OutgoingSocketThread( 3288): Entering thread (ID: 314)
,D/io.jxcore.node.OutgoingSocketThread( 3288): Server socket local port: 55997
I/io.jxcore.node.OutgoingSocketThread( 3288): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3288): onListeningForIncomingConnections: Outgoing connection is using port 55997 (peer ID: 58:3F:54:73:64:C0)
I/jxcore-log( 3288): 2015-12-18T18:40:12.185Z SendDataConnector.js: CLIENT connected to 55997, error: null
I/jxcore-log( 3288): 
I/jxcore-log( 3288): 2015-12-18T18:40:12.186Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3288): 
,I/io.jxcore.node.OutgoingSocketThread( 3288): Incoming data from address: /127.0.0.1, port: 55997
D/io.jxcore.node.OutgoingSocketThread( 3288): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3288): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3288): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3288): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3288): Exiting thread (ID: 314)
,D/io.jxcore.node.StreamCopyingThread( 3288): Entering thread (ID: 315, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 3288): Entering thread (ID: 316, name: Receiver)
,I/jxcore-log( 3288): 2015-12-18T18:40:12.237Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:12.709Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:12.742Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:12.773Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:12.781Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:12.796Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:12.916Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:12.991Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:13.028Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
,I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:13.036Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:13.092Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3288): 
,D/        ( 2142): PORT_WriteDataCO: tx queue is full,tx.queue_size:10172,tx.queue.count:11,available:24706
,I/jxcore-log( 3288): 2015-12-18T18:40:13.183Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:13.234Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:13.250Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:13.285Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:13.312Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:13.351Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:13.414Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:13.424Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:13.435Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:13.476Z SendDataTCPServer.js: TCP/IP server has received 32768 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:13.515Z SendDataTCPServer.js: TCP/IP server has received 34748 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:13.637Z SendDataTCPServer.js: TCP/IP server has received 36728 bytes of data
I/jxcore-log( 3288): 
,D/        ( 2142): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:14806
,I/jxcore-log( 3288): 2015-12-18T18:40:13.701Z SendDataTCPServer.js: TCP/IP server has received 38708 bytes of data
I/jxcore-log( 3288): 
I/jxcore-log( 3288): 2015-12-18T18:40:13.704Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:13.810Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:13.822Z SendDataTCPServer.js: TCP/IP server has received 42668 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:13.854Z SendDataTCPServer.js: TCP/IP server has received 46628 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:13.871Z SendDataTCPServer.js: TCP/IP server has received 48608 bytes of data
I/jxcore-log( 3288): 
I/jxcore-log( 3288): 2015-12-18T18:40:13.874Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:13.882Z SendDataTCPServer.js: TCP/IP server has received 50588 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:13.938Z SendDataTCPServer.js: TCP/IP server has received 52568 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:14.014Z SendDataTCPServer.js: TCP/IP server has received 54548 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:14.092Z SendDataTCPServer.js: TCP/IP server has received 56528 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:14.118Z SendDataTCPServer.js: TCP/IP server has received 58508 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:14.189Z SendDataTCPServer.js: TCP/IP server has received 60488 bytes of data
I/jxcore-log( 3288): 
,D/        ( 2142): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:3916
,I/jxcore-log( 3288): 2015-12-18T18:40:14.242Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:14.319Z SendDataTCPServer.js: TCP/IP server has received 62468 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:14.389Z SendDataTCPServer.js: TCP/IP server has received 64448 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:14.462Z SendDataTCPServer.js: TCP/IP server has received 66428 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:14.493Z SendDataTCPServer.js: TCP/IP server has received 68408 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:14.500Z SendDataTCPServer.js: TCP/IP server has received 70388 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:14.511Z SendDataTCPServer.js: TCP/IP server has received 72368 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:14.546Z SendDataTCPServer.js: TCP/IP server has received 74348 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:14.584Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3288): 
I/jxcore-log( 3288): 2015-12-18T18:40:14.587Z SendDataTCPServer.js: TCP/IP server has received 82268 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:14.600Z SendDataTCPServer.js: TCP/IP server has received 84248 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:14.607Z SendDataTCPServer.js: TCP/IP server has received 86228 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:14.644Z SendDataTCPServer.js: TCP/IP server has received 88208 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:14.653Z SendDataTCPServer.js: TCP/IP server has received 90188 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:14.708Z SendDataTCPServer.js: TCP/IP server has received 92168 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:14.821Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:14.876Z SendDataTCPServer.js: TCP/IP server has received 94148 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:14.892Z SendDataTCPServer.js: TCP/IP server has received 96128 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:14.925Z SendDataTCPServer.js: TCP/IP server has received 98108 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:14.938Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:14.949Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:15.113Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3288): 
I/jxcore-log( 3288): 2015-12-18T18:40:15.114Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): oneRoundDownNow
I/jxcore-log( 3288): 
I/jxcore-log( 3288): 2015-12-18T18:40:15.125Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3288): 
I/jxcore-log( 3288): 2015-12-18T18:40:15.126Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3288): 
,W/io.jxcore.node.StreamCopyingThread( 3288): Either failed to read from the output stream or write to the input stream (thread ID: 312, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 3288): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3288): onDisconnected: Incoming connection, peer [58:3F:54:73:64:C0 LGE-LG-D855_PT7178] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3288): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 310
D/io.jxcore.node.OutgoingSocketThread( 3288): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3288): doStop: Thread ID: 312
D/io.jxcore.node.OutgoingSocketThread( 3288): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3288): doStop: Thread ID: 311
D/io.jxcore.node.OutgoingSocketThread( 3288): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 3288): closeLocalSocketAndStreams: Closing the local input stream...
,W/bt-btif ( 2142): invalid rfc slot id: 4
,W/io.jxcore.node.StreamCopyingThread( 3288): Either failed to read from the output stream or write to the input stream (thread ID: 311, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3288): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3288): onDisconnected: Incoming connection, peer [58:3F:54:73:64:C0 LGE-LG-D855_PT7178] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 3288): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 3288): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3288): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3288): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.ConnectionHelper( 3288): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3288): Exiting thread (ID: 311, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 3288): Exiting thread (ID: 312, name: Receiver)
,D/io.jxcore.node.ConnectionHelper( 3288): disconnectOutgoingConnection: Trying to close connection to peer with ID 58:3F:54:73:64:C0
I/io.jxcore.node.ConnectionHelper( 3288): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 58:3F:54:73:64:C0
I/io.jxcore.node.OutgoingSocketThread( 3288): close
D/io.jxcore.node.OutgoingSocketThread( 3288): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3288): doStop: Thread ID: 316
D/io.jxcore.node.OutgoingSocketThread( 3288): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3288): doStop: Thread ID: 315
D/io.jxcore.node.OutgoingSocketThread( 3288): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 3288): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3288): Either failed to read from the output stream or write to the input stream (thread ID: 315, thread name: Sender): Socket closed
,E/io.jxcore.node.OutgoingSocketThread( 3288): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3288): onDisconnected: Outgoing connection, peer [58:3F:54:73:64:C0 LGE-LG-D855_PT7178] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 3288): closeLocalSocketAndStreams: Closing the local output stream...
,D/io.jxcore.node.OutgoingSocketThread( 3288): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3288): closeBluetoothSocketAndStreams
W/io.jxcore.node.StreamCopyingThread( 3288): Either failed to read from the output stream or write to the input stream (thread ID: 316, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 3288): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3288): onDisconnected: Outgoing connection, peer [58:3F:54:73:64:C0 LGE-LG-D855_PT7178] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3288): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3288): disconnectOutgoingConnection: Successfully disconnected (peer ID: 58:3F:54:73:64:C0
,E/io.jxcore.node.ConnectionHelper( 3288): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 58:3F:54:73:64:C0
D/io.jxcore.node.ConnectionHelper( 3288): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3288): Exiting thread (ID: 315, name: Sender)
E/io.jxcore.node.ConnectionHelper( 3288): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 58:3F:54:73:64:C0
D/io.jxcore.node.ConnectionHelper( 3288): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3288): Exiting thread (ID: 316, name: Receiver)
,I/jxcore-log( 3288): 2015-12-18T18:40:15.189Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:3F:54:73:64:C0
I/jxcore-log( 3288): 
I/jxcore-log( 3288): ---- round done--------
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): startWithNextDevice
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:15.194Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3288): 
,W/bt-btif ( 2142): bta_jv_rfc_port_to_cb(port_handle:0x9):jv handle:0x0 not FOUND
,D/btif_config_util( 2142): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2142): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2142): onReceive
,D/BluetoothManagerService(  759): Message: 20
D/BluetoothManagerService(  759): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@320dad76:true
,I/BTConnectionReceiver( 1375): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1375): Bluetooth Device Name: G3-1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): Got discovery timeout, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): setState: RESTARTING
,I/wpa_supplicant(  991): P2P-FIND-STOPPED 
,I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): Start timer timeout, starting now...
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant(  991): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  991): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
,D/WifiP2pManager( 3288): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): Service request added successfully
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): Service discovery started successfully
,W/bt-btif ( 2142): info:x10
,D/        ( 2142): remote version info [b0:c5:59:3f:75:69]: 7, f, 610c
,E/BluetoothRemoteDevices( 2142): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 4: G3-1 02:9a:02:7b:60:ac
,I/BluetoothBondStateMachine( 2142): bondStateChangeCallback: Status: 0 Address: B0:C5:59:3F:75:69 newState: 1
E/bt-btif ( 2142): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2142): Bond State Change Intent:B0:C5:59:3F:75:69 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2142): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2142): bondStateChangeCallback: Status: 0 Address: B0:C5:59:3F:75:69 newState: 0
,D/BluetoothAdapterProperties( 2142): Failed to remove device: B0:C5:59:3F:75:69
,I/BluetoothBondStateMachine( 2142): Bond State Change Intent:B0:C5:59:3F:75:69 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2142): StableState(): Entering Off State
,W/bt-btif ( 2142): new conn_srvc id:26, app_id:255
W/bt-btif ( 2142): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2142): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3288): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3288): Incoming connection initialized (thread ID: 317)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3288): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3288): Entering thread (ID: 317)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3288): onBytesRead: Read 82 bytes successfully (thread ID: 317)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3288): Got valid identity from [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3288): onBytesWritten: 76 bytes successfully written (thread ID: 317)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3288): removeThreadFromList: Removing thread with ID 317
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3288): Handshake thread disposed (thread ID: 317)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3288): onIncomingConnectionConnected: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3288): Exiting thread (ID: 317)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3288): onConnected: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691]
I/io.jxcore.node.ConnectionHelper( 3288): onConnected: Incoming connection to peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691]
D/io.jxcore.node.ConnectionHelper( 3288): hasConnection: No connection with peer with ID B0:C5:59:3F:75:69
D/io.jxcore.node.ConnectionHelper( 3288): notifyPeerAvailability: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691] is available
,I/jxcore-log( 3288): peerAvailabilityChanged [{"peerIdentifier":"B0:C5:59:3F:75:69","peerName":"samsung-SM-G900F_PT1691","peerAvailable":true}]
I/jxcore-log( 3288): 
I/jxcore-log( 3288): Found peer : samsung-SM-G900F_PT1691, Available: true
I/jxcore-log( 3288): 
I/jxcore-log( 3288): startWithNextDevice
I/jxcore-log( 3288): 
I/jxcore-log( 3288): device[2]: B0:C5:59:3F:75:69
I/jxcore-log( 3288): 
I/jxcore-log( 3288): 2015-12-18T18:40:49.659Z SendDataConnector.js: Start called with peer B0:C5:59:3F:75:69
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:49.659Z SendDataConnector.js: doConnect called with peer B0:C5:59:3F:75:69
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:49.660Z SendDataConnector.js: do connect now
I/jxcore-log( 3288): 
,I/io.jxcore.node.ConnectionHelper( 3288): connect: Trying to connect to peer with ID B0:C5:59:3F:75:69
D/io.jxcore.node.ConnectionHelper( 3288): hasConnection: No connection with peer with ID B0:C5:59:3F:75:69
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3288): connect: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3288): connect: Trying to start connecting to Thali Test (Galaxy S5) in address B0:C5:59:3F:75:69
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3288): onConnecting: Thali Test (Galaxy S5) B0:C5:59:3F:75:69
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3288): connect: Started connecting to Thali Test (Galaxy S5) in address B0:C5:59:3F:75:69
I/io.jxcore.node.ConnectionHelper( 3288): connect: Connection process successfully started (peer ID: B0:C5:59:3F:75:69)
I/io.jxcore.node.ConnectionHelper( 3288): onConnected: Incoming socket thread, for peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691], created successfully
D/io.jxcore.node.ConnectionHelper( 3288): onConnected: The total number of connections is now 1
,D/io.jxcore.node.IncomingSocketThread( 3288): Entering thread (ID: 319)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): Trying to connect to peer with address B0:C5:59:3F:75:69 (thread ID: 318)
W/BluetoothAdapter( 3288): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2142): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/io.jxcore.node.IncomingSocketThread( 3288): Local host address: localhost/127.0.0.1, port: 60252
D/io.jxcore.node.IncomingSocketThread( 3288): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3288): setBufferSize: Setting buffer size to 8192 bytes
,I/jxcore-log( 3288): 2015-12-18T18:40:49.681Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3288): 
,I/io.jxcore.node.StreamCopyingThread( 3288): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.IncomingSocketThread( 3288): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3288): Exiting thread (ID: 319)
,D/io.jxcore.node.StreamCopyingThread( 3288): Entering thread (ID: 321, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3288): Entering thread (ID: 320, name: Sender)
,W/bt-sdp  ( 2142): process_service_search_attr_rsp
,W/bt-btif ( 2142): new conn_srvc id:26, app_id:1
W/bt-btif ( 2142): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2142): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2142): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3288): onSocketConnected: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 318)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): onBytesWritten: 76 bytes successfully written (thread ID: 322)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): Outgoing connection initialized (*handshake* thread ID: 322)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): Exiting thread (thread ID: 318)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3288): Entering thread (ID: 322)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): onBytesRead: Read 82 bytes successfully (thread ID: 322)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): Handshake succeeded with [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3288): onHandshakeSucceeded: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691]
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3288): Exiting thread (ID: 322)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3288): onConnected: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691]
I/io.jxcore.node.ConnectionHelper( 3288): onConnected: Outgoing connection to peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691]
D/io.jxcore.node.ConnectionHelper( 3288): hasConnection: We have an incoming connection with peer with ID B0:C5:59:3F:75:69
W/io.jxcore.node.ConnectionHelper( 3288): onConnected: Already connected with peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691], continuing anyway...
W/io.jxcore.node.ConnectionHelper( 3288): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 3288): onConnected: Outgoing socket thread, for peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3288): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 3288): onConnected: The total number of connections is now 2
,D/io.jxcore.node.OutgoingSocketThread( 3288): Entering thread (ID: 323)
D/io.jxcore.node.OutgoingSocketThread( 3288): Server socket local port: 48359
I/io.jxcore.node.OutgoingSocketThread( 3288): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3288): onListeningForIncomingConnections: Outgoing connection is using port 48359 (peer ID: B0:C5:59:3F:75:69)
,I/jxcore-log( 3288): 2015-12-18T18:40:50.518Z SendDataConnector.js: CLIENT connected to 48359, error: null
I/jxcore-log( 3288): 
I/jxcore-log( 3288): 2015-12-18T18:40:50.518Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3288): 
,I/io.jxcore.node.OutgoingSocketThread( 3288): Incoming data from address: /127.0.0.1, port: 48359
D/io.jxcore.node.OutgoingSocketThread( 3288): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3288): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3288): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3288): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3288): Exiting thread (ID: 323)
,D/io.jxcore.node.StreamCopyingThread( 3288): Entering thread (ID: 325, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3288): Entering thread (ID: 324, name: Sender)
,I/jxcore-log( 3288): 2015-12-18T18:40:50.563Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:51.036Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:51.176Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:51.375Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:51.389Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:51.394Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:51.408Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:51.447Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:51.627Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:52.982Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:53.044Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:53.163Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:53.684Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:54.278Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:54.288Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:54.374Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:54.412Z SendDataTCPServer.js: TCP/IP server has received 34748 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:54.435Z SendDataTCPServer.js: TCP/IP server has received 36728 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:54.443Z SendDataTCPServer.js: TCP/IP server has received 38708 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:54.472Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:54.501Z SendDataTCPServer.js: TCP/IP server has received 42668 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:54.537Z SendDataTCPServer.js: TCP/IP server has received 44648 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:54.549Z SendDataTCPServer.js: TCP/IP server has received 46628 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:54.566Z SendDataTCPServer.js: TCP/IP server has received 48608 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:54.575Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:54.614Z SendDataTCPServer.js: TCP/IP server has received 50588 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:54.640Z SendDataTCPServer.js: TCP/IP server has received 52568 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:54.673Z SendDataTCPServer.js: TCP/IP server has received 54548 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:54.683Z SendDataTCPServer.js: TCP/IP server has received 56528 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:54.689Z SendDataTCPServer.js: TCP/IP server has received 58508 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:54.704Z SendDataTCPServer.js: TCP/IP server has received 60488 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:54.714Z SendDataTCPServer.js: TCP/IP server has received 62468 bytes of data
I/jxcore-log( 3288): 
,D/btif_config_util( 2142): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3288): 2015-12-18T18:40:54.802Z SendDataTCPServer.js: TCP/IP server has received 64448 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:54.814Z SendDataTCPServer.js: TCP/IP server has received 66428 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:54.824Z SendDataTCPServer.js: TCP/IP server has received 68408 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:54.904Z SendDataTCPServer.js: TCP/IP server has received 70388 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:54.912Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3288): 
I/jxcore-log( 3288): 2015-12-18T18:40:54.913Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3288): 
I/jxcore-log( 3288): oneRoundDownNow
I/jxcore-log( 3288): 
I/jxcore-log( 3288): 2015-12-18T18:40:54.915Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3288): 
I/jxcore-log( 3288): 2015-12-18T18:40:54.915Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3288): 
D/io.jxcore.node.ConnectionHelper( 3288): disconnectOutgoingConnection: Trying to close connection to peer with ID B0:C5:59:3F:75:69
I/io.jxcore.node.ConnectionHelper( 3288): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: B0:C5:59:3F:75:69
I/io.jxcore.node.OutgoingSocketThread( 3288): close
D/io.jxcore.node.OutgoingSocketThread( 3288): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3288): doStop: Thread ID: 325
D/io.jxcore.node.OutgoingSocketThread( 3288): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3288): doStop: Thread ID: 324
D/io.jxcore.node.OutgoingSocketThread( 3288): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 3288): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3288): Either failed to read from the output stream or write to the input stream (thread ID: 324, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3288): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3288): onDisconnected: Outgoing connection, peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 3288): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 3288): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3288): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3288): Either failed to read from the output stream or write to the input stream (thread ID: 325, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.OutgoingSocketThread( 3288): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3288): onDisconnected: Outgoing connection, peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3288): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3288): disconnectOutgoingConnection: Successfully disconnected (peer ID: B0:C5:59:3F:75:69
,E/io.jxcore.node.ConnectionHelper( 3288): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID B0:C5:59:3F:75:69
D/io.jxcore.node.ConnectionHelper( 3288): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,D/io.jxcore.node.StreamCopyingThread( 3288): Exiting thread (ID: 324, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 3288): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID B0:C5:59:3F:75:69
D/io.jxcore.node.ConnectionHelper( 3288): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3288): Exiting thread (ID: 325, name: Receiver)
,I/jxcore-log( 3288): 2015-12-18T18:40:54.957Z SendDataConnector.js: Mobile.Disconnect() callback with peer B0:C5:59:3F:75:69
I/jxcore-log( 3288): 
I/jxcore-log( 3288): ---- round done--------
I/jxcore-log( 3288): 
I/jxcore-log( 3288): startWithNextDevice
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:54.960Z SendDataTCPServer.js: TCP/IP server has received 72368 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:54.991Z SendDataTCPServer.js: TCP/IP server has received 74348 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:55.021Z SendDataTCPServer.js: TCP/IP server has received 76328 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:55.026Z SendDataTCPServer.js: TCP/IP server has received 78308 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:55.092Z SendDataTCPServer.js: TCP/IP server has received 80288 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:55.206Z SendDataTCPServer.js: TCP/IP server has received 82268 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:55.242Z SendDataTCPServer.js: TCP/IP server has received 84248 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:55.272Z SendDataTCPServer.js: TCP/IP server has received 86228 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:55.315Z SendDataTCPServer.js: TCP/IP server has received 88208 bytes of data
I/jxcore-log( 3288): 
,W/bt-btif ( 2142): bta_jv_rfc_port_to_cb(port_handle:0xb):jv handle:0x0 not FOUND
,I/jxcore-log( 3288): 2015-12-18T18:40:55.327Z SendDataTCPServer.js: TCP/IP server has received 90188 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:55.343Z SendDataTCPServer.js: TCP/IP server has received 92168 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:40:55.374Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3288): 
,W/bt-btif ( 2142): invalid rfc slot id: 5
,W/io.jxcore.node.StreamCopyingThread( 3288): Either failed to read from the output stream or write to the input stream (thread ID: 321, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.OutgoingSocketThread( 3288): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3288): onDisconnected: Incoming connection, peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,I/io.jxcore.node.ConnectionHelper( 3288): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 319
D/io.jxcore.node.OutgoingSocketThread( 3288): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3288): doStop: Thread ID: 321
D/io.jxcore.node.OutgoingSocketThread( 3288): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3288): doStop: Thread ID: 320
D/io.jxcore.node.OutgoingSocketThread( 3288): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 3288): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3288): Either failed to read from the output stream or write to the input stream (thread ID: 320, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3288): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3288): onDisconnected: Incoming connection, peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 3288): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 3288): closeLocalSocketAndStreams: Closing the localhost socket...
,I/io.jxcore.node.OutgoingSocketThread( 3288): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3288): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.ConnectionHelper( 3288): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3288): Exiting thread (ID: 320, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 3288): Exiting thread (ID: 321, name: Receiver)
,I/jxcore-log( 3288): 2015-12-18T18:40:55.503Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3288): 
,W/bt-rfcomm( 2142): rfc_find_lcid_mcb LCID reused LCID:0x44 current:0x0
W/bt-rfcomm( 2142): RFCOMM_DisconnectInd LCID:0x44
,E/bt-btm  ( 2142): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2142): onReceive
,I/BTConnectionReceiver( 1375): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1375): Bluetooth Device Name: Thali Test (Galaxy S5)
,W/bt-btif ( 2142): info:x10
,D/        ( 2142): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 2142): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 2142): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 1
E/bt-btif ( 2142): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2142): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2142): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2142): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 0
,D/BluetoothAdapterProperties( 2142): Failed to remove device: 44:80:EB:7B:5A:05
,I/BluetoothBondStateMachine( 2142): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2142): StableState(): Entering Off State
,W/bt-btif ( 2142): new conn_srvc id:26, app_id:255
W/bt-btif ( 2142): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2142): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3288): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3288): Incoming connection initialized (thread ID: 326)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3288): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3288): Entering thread (ID: 326)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3288): onBytesRead: Read 81 bytes successfully (thread ID: 326)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3288): Got valid identity from [44:80:EB:7B:5A:05 motorola-XT1072_PT7387]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3288): onBytesWritten: 76 bytes successfully written (thread ID: 326)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3288): removeThreadFromList: Removing thread with ID 326
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3288): Handshake thread disposed (thread ID: 326)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3288): onIncomingConnectionConnected: [44:80:EB:7B:5A:05 motorola-XT1072_PT7387]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3288): Exiting thread (ID: 326)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3288): onConnected: [44:80:EB:7B:5A:05 motorola-XT1072_PT7387]
I/io.jxcore.node.ConnectionHelper( 3288): onConnected: Incoming connection to peer [44:80:EB:7B:5A:05 motorola-XT1072_PT7387]
D/io.jxcore.node.ConnectionHelper( 3288): hasConnection: No connection with peer with ID 44:80:EB:7B:5A:05
D/io.jxcore.node.ConnectionHelper( 3288): notifyPeerAvailability: Peer [44:80:EB:7B:5A:05 motorola-XT1072_PT7387] is available
,I/jxcore-log( 3288): peerAvailabilityChanged [{"peerIdentifier":"44:80:EB:7B:5A:05","peerName":"motorola-XT1072_PT7387","peerAvailable":true}]
I/jxcore-log( 3288): 
I/jxcore-log( 3288): Found peer : motorola-XT1072_PT7387, Available: true
I/jxcore-log( 3288): 
I/jxcore-log( 3288): startWithNextDevice
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): device[3]: 44:80:EB:7B:5A:05
I/jxcore-log( 3288): 
I/jxcore-log( 3288): 2015-12-18T18:41:16.852Z SendDataConnector.js: Start called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3288): 
I/jxcore-log( 3288): 2015-12-18T18:41:16.852Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:41:16.853Z SendDataConnector.js: do connect now
I/jxcore-log( 3288): 
,I/io.jxcore.node.ConnectionHelper( 3288): connect: Trying to connect to peer with ID 44:80:EB:7B:5A:05
D/io.jxcore.node.ConnectionHelper( 3288): hasConnection: No connection with peer with ID 44:80:EB:7B:5A:05
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3288): connect: [44:80:EB:7B:5A:05 motorola-XT1072_PT7387]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3288): connect: Trying to start connecting to XT1072 in address 44:80:EB:7B:5A:05
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3288): onConnecting: XT1072 44:80:EB:7B:5A:05
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3288): connect: Started connecting to XT1072 in address 44:80:EB:7B:5A:05
I/io.jxcore.node.ConnectionHelper( 3288): connect: Connection process successfully started (peer ID: 44:80:EB:7B:5A:05)
I/io.jxcore.node.ConnectionHelper( 3288): onConnected: Incoming socket thread, for peer [44:80:EB:7B:5A:05 motorola-XT1072_PT7387], created successfully
D/io.jxcore.node.ConnectionHelper( 3288): onConnected: The total number of connections is now 1
,D/io.jxcore.node.IncomingSocketThread( 3288): Entering thread (ID: 328)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): Trying to connect to peer with address 44:80:EB:7B:5A:05 (thread ID: 327)
,W/BluetoothAdapter( 3288): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2142): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/io.jxcore.node.IncomingSocketThread( 3288): Local host address: localhost/127.0.0.1, port: 60252
D/io.jxcore.node.IncomingSocketThread( 3288): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3288): setBufferSize: Setting buffer size to 8192 bytes
,I/jxcore-log( 3288): 2015-12-18T18:41:16.863Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3288): 
,I/io.jxcore.node.StreamCopyingThread( 3288): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3288): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3288): Exiting thread (ID: 328)
,D/io.jxcore.node.StreamCopyingThread( 3288): Entering thread (ID: 330, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3288): Entering thread (ID: 329, name: Sender)
,W/bt-sdp  ( 2142): process_service_search_attr_rsp
,W/bt-btif ( 2142): new conn_srvc id:26, app_id:1
W/bt-btif ( 2142): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2142): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2142): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3288): onSocketConnected: [44:80:EB:7B:5A:05 motorola-XT1072_PT7387]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 327)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): onBytesWritten: 76 bytes successfully written (thread ID: 331)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): Outgoing connection initialized (*handshake* thread ID: 331)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): Exiting thread (thread ID: 327)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3288): Entering thread (ID: 331)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): onBytesRead: Read 81 bytes successfully (thread ID: 331)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): Handshake succeeded with [44:80:EB:7B:5A:05 motorola-XT1072_PT7387]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3288): onHandshakeSucceeded: [44:80:EB:7B:5A:05 motorola-XT1072_PT7387]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3288): Exiting thread (ID: 331)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3288): onConnected: [44:80:EB:7B:5A:05 motorola-XT1072_PT7387]
I/io.jxcore.node.ConnectionHelper( 3288): onConnected: Outgoing connection to peer [44:80:EB:7B:5A:05 motorola-XT1072_PT7387]
D/io.jxcore.node.ConnectionHelper( 3288): hasConnection: We have an incoming connection with peer with ID 44:80:EB:7B:5A:05
W/io.jxcore.node.ConnectionHelper( 3288): onConnected: Already connected with peer [44:80:EB:7B:5A:05 motorola-XT1072_PT7387], continuing anyway...
W/io.jxcore.node.ConnectionHelper( 3288): modifyListOfDiscoveredPeers: Peer [44:80:EB:7B:5A:05 motorola-XT1072_PT7387] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 3288): onConnected: Outgoing socket thread, for peer [44:80:EB:7B:5A:05 motorola-XT1072_PT7387], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3288): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 3288): onConnected: The total number of connections is now 2
,D/io.jxcore.node.OutgoingSocketThread( 3288): Entering thread (ID: 332)
D/io.jxcore.node.OutgoingSocketThread( 3288): Server socket local port: 34471
I/io.jxcore.node.OutgoingSocketThread( 3288): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3288): onListeningForIncomingConnections: Outgoing connection is using port 34471 (peer ID: 44:80:EB:7B:5A:05)
I/jxcore-log( 3288): 2015-12-18T18:41:17.225Z SendDataConnector.js: CLIENT connected to 34471, error: null
I/jxcore-log( 3288): 
I/jxcore-log( 3288): 2015-12-18T18:41:17.226Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3288): 
,I/io.jxcore.node.OutgoingSocketThread( 3288): Incoming data from address: /127.0.0.1, port: 34471
D/io.jxcore.node.OutgoingSocketThread( 3288): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3288): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3288): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3288): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3288): Exiting thread (ID: 332)
,D/io.jxcore.node.StreamCopyingThread( 3288): Entering thread (ID: 334, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3288): Entering thread (ID: 333, name: Sender)
,I/jxcore-log( 3288): 2015-12-18T18:41:17.267Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:41:17.744Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:41:17.755Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:41:17.791Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:41:17.837Z SendDataTCPServer.js: TCP/IP server has received 32768 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:41:17.871Z SendDataTCPServer.js: TCP/IP server has received 36728 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:41:17.880Z SendDataTCPServer.js: TCP/IP server has received 38708 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:41:17.892Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data
I/jxcore-log( 3288): 
,D/        ( 2142): PORT_WriteDataCO: tx queue is full,tx.queue_size:10172,tx.queue.count:11,available:24706
,I/jxcore-log( 3288): 2015-12-18T18:41:17.897Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:41:18.204Z SendDataTCPServer.js: TCP/IP server has received 42668 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:41:18.232Z SendDataTCPServer.js: TCP/IP server has received 44648 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:41:18.263Z SendDataTCPServer.js: TCP/IP server has received 46628 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:41:18.281Z SendDataTCPServer.js: TCP/IP server has received 48608 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:41:18.304Z SendDataTCPServer.js: TCP/IP server has received 50588 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:41:18.317Z SendDataTCPServer.js: TCP/IP server has received 52568 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:41:18.352Z SendDataTCPServer.js: TCP/IP server has received 58508 bytes of data
I/jxcore-log( 3288): 
,D/        ( 2142): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:14806
,I/jxcore-log( 3288): 2015-12-18T18:41:18.370Z SendDataTCPServer.js: TCP/IP server has received 60488 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:41:18.379Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:41:18.396Z SendDataTCPServer.js: TCP/IP server has received 62468 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:41:18.433Z SendDataTCPServer.js: TCP/IP server has received 66428 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:41:18.439Z SendDataTCPServer.js: TCP/IP server has received 68408 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:41:18.457Z SendDataTCPServer.js: TCP/IP server has received 70388 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:41:18.489Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:41:18.495Z SendDataTCPServer.js: TCP/IP server has received 74348 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:41:18.524Z SendDataTCPServer.js: TCP/IP server has received 82268 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:41:18.549Z SendDataTCPServer.js: TCP/IP server has received 84248 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:41:18.607Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:41:18.615Z SendDataTCPServer.js: TCP/IP server has received 98108 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:41:18.627Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:41:18.694Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:41:18.696Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3288): 
,W/bt-btif ( 2142): invalid rfc slot id: 7
,W/io.jxcore.node.StreamCopyingThread( 3288): Either failed to read from the output stream or write to the input stream (thread ID: 330, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 3288): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3288): onDisconnected: Incoming connection, peer [44:80:EB:7B:5A:05 motorola-XT1072_PT7387] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3288): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 328
D/io.jxcore.node.OutgoingSocketThread( 3288): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3288): doStop: Thread ID: 330
D/io.jxcore.node.OutgoingSocketThread( 3288): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3288): doStop: Thread ID: 329
D/io.jxcore.node.OutgoingSocketThread( 3288): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 3288): closeLocalSocketAndStreams: Closing the local input stream...
D/io.jxcore.node.OutgoingSocketThread( 3288): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 3288): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3288): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3288): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3288): Exiting thread (ID: 330, name: Receiver)
,W/io.jxcore.node.StreamCopyingThread( 3288): Either failed to read from the output stream or write to the input stream (thread ID: 329, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3288): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3288): onDisconnected: Incoming connection, peer [44:80:EB:7B:5A:05 motorola-XT1072_PT7387] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.ConnectionHelper( 3288): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3288): Exiting thread (ID: 329, name: Sender)
I/jxcore-log( 3288): 2015-12-18T18:41:18.729Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3288): 
I/jxcore-log( 3288): 2015-12-18T18:41:18.743Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:41:18.780Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3288): 
I/jxcore-log( 3288): 2015-12-18T18:41:18.781Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3288): 
I/jxcore-log( 3288): oneRoundDownNow
I/jxcore-log( 3288): 
I/jxcore-log( 3288): 2015-12-18T18:41:18.781Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3288): 
I/jxcore-log( 3288): 2015-12-18T18:41:18.781Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3288): 
D/io.jxcore.node.ConnectionHelper( 3288): disconnectOutgoingConnection: Trying to close connection to peer with ID 44:80:EB:7B:5A:05
I/io.jxcore.node.ConnectionHelper( 3288): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 44:80:EB:7B:5A:05
I/io.jxcore.node.OutgoingSocketThread( 3288): close
D/io.jxcore.node.OutgoingSocketThread( 3288): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3288): doStop: Thread ID: 334
D/io.jxcore.node.OutgoingSocketThread( 3288): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3288): doStop: Thread ID: 333
D/io.jxcore.node.OutgoingSocketThread( 3288): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 3288): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3288): Either failed to read from the output stream or write to the input stream (thread ID: 333, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3288): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3288): onDisconnected: Outgoing connection, peer [44:80:EB:7B:5A:05 motorola-XT1072_PT7387] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.OutgoingSocketThread( 3288): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 3288): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3288): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3288): Either failed to read from the output stream or write to the input stream (thread ID: 334, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 3288): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3288): onDisconnected: Outgoing connection, peer [44:80:EB:7B:5A:05 motorola-XT1072_PT7387] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
D/io.jxcore.node.ConnectionHelper( 3288): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3288): disconnectOutgoingConnection: Successfully disconnected (peer ID: 44:80:EB:7B:5A:05
,E/io.jxcore.node.ConnectionHelper( 3288): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 44:80:EB:7B:5A:05
D/io.jxcore.node.ConnectionHelper( 3288): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3288): Exiting thread (ID: 333, name: Sender)
E/io.jxcore.node.ConnectionHelper( 3288): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 44:80:EB:7B:5A:05
D/io.jxcore.node.ConnectionHelper( 3288): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3288): Exiting thread (ID: 334, name: Receiver)
,I/jxcore-log( 3288): 2015-12-18T18:41:18.787Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3288): 
I/jxcore-log( 3288): ---- round done--------
I/jxcore-log( 3288): 
I/jxcore-log( 3288): startWithNextDevice
I/jxcore-log( 3288): 
,W/bt-btif ( 2142): bta_jv_rfc_port_to_cb(port_handle:0xd):jv handle:0x0 not FOUND
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): setState: RESTARTING
,I/wpa_supplicant(  991): P2P-FIND-STOPPED 
,I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
,D/btif_config_util( 2142): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2142): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2142): onReceive
,I/BTConnectionReceiver( 1375): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1375): Bluetooth Device Name: XT1072
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): Start timer timeout, starting now...
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): restart: Restarting...
,D/WifiP2pManager( 3288): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): Service request added successfully
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT7601","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
I/io.jxcore.node.ConnectionHelper( 3288): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
D/io.jxcore.node.ConnectionHelper( 3288): notifyPeerAvailability: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601] is available
I/jxcore-log( 3288): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:51:18:22","peerName":"samsung-SM-A500FU_PT7601","peerAvailable":true}]
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): Found peer : samsung-SM-A500FU_PT7601, Available: true
I/jxcore-log( 3288): 
I/jxcore-log( 3288): startWithNextDevice
I/jxcore-log( 3288): 
I/jxcore-log( 3288): device[4]: 7C:F9:0E:51:18:22
I/jxcore-log( 3288): 
I/jxcore-log( 3288): 2015-12-18T18:41:30.880Z SendDataConnector.js: Start called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:41:30.883Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3288): 
I/jxcore-log( 3288): 2015-12-18T18:41:30.884Z SendDataConnector.js: do connect now
I/jxcore-log( 3288): 
I/io.jxcore.node.ConnectionHelper( 3288): connect: Trying to connect to peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 3288): hasConnection: No connection with peer with ID 7C:F9:0E:51:18:22
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3288): connect: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3288): connect: Trying to start connecting to null in address 7C:F9:0E:51:18:22
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3288): onConnecting: null 7C:F9:0E:51:18:22
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3288): connect: Started connecting to null in address 7C:F9:0E:51:18:22
I/io.jxcore.node.ConnectionHelper( 3288): connect: Connection process successfully started (peer ID: 7C:F9:0E:51:18:22)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): Trying to connect to peer with address 7C:F9:0E:51:18:22 (thread ID: 335)
W/BluetoothAdapter( 3288): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2142): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2142): SDP - Rcvd conn cnf with error: 0x4  CID 0x49
E/bt-btif ( 2142): DISCOVERY_COMP_EVT slot id:11, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2142): invalid rfc slot id: 11
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 335)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): Maximum number of allowed retries (0) reached, giving up... (thread ID: 335)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3288): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): Exiting thread (thread ID: 335)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3288): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
,I/jxcore-log( 3288): 2015-12-18T18:41:36.034Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601] failed
I/jxcore-log( 3288): 
I/jxcore-log( 3288): 2015-12-18T18:41:36.034Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601] failed
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:41:36.035Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3288): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3288): setInsecureRfcommSocketPort: Will use port 1 when trying to connect
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): shutdown (thread ID: 335)
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1864","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
,I/io.jxcore.node.ConnectionHelper( 3288): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: a2:39:f7:6f:c9:5d
D/io.jxcore.node.ConnectionHelper( 3288): notifyPeerAvailability: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864] is available
,I/jxcore-log( 3288): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:3C:51","peerName":"LGE-LG-H815_PT1864","peerAvailable":true}]
I/jxcore-log( 3288): 
I/jxcore-log( 3288): Found peer : LGE-LG-H815_PT1864, Available: true
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:41:41.036Z SendDataConnector.js: re-try now : 7C:F9:0E:51:18:22
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:41:41.037Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3288): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT7178","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT7178]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT7178]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT7178]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT7178], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT7178]
I/io.jxcore.node.ConnectionHelper( 3288): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT7178], Bluetooth address: 58:3F:54:73:64:C0, device name: , device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper( 3288): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT7178] already in the list, will not add again
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/io.jxcore.node.ConnectionHelper( 3288): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:51:18:22
E/io.jxcore.node.ConnectionHelper( 3288): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 3288): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3288): disconnectOutgoingConnection: Failed to disconnect (peer ID: 7C:F9:0E:51:18:22), either no such connection or failed to close the connection
I/jxcore-log( 3288): 2015-12-18T18:41:46.045Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3288): 
I/jxcore-log( 3288): 2015-12-18T18:41:46.046Z SendDataConnector.js: Connect (retry count 1) to peer 7C:F9:0E:51:18:22 with availability status: true
I/jxcore-log( 3288): 
I/jxcore-log( 3288): 2015-12-18T18:41:46.047Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3288): 
I/jxcore-log( 3288): 2015-12-18T18:41:46.047Z SendDataConnector.js: do connect now
I/jxcore-log( 3288): 
I/io.jxcore.node.ConnectionHelper( 3288): connect: Trying to connect to peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 3288): hasConnection: No connection with peer with ID 7C:F9:0E:51:18:22
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3288): connect: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3288): connect: Trying to start connecting to null in address 7C:F9:0E:51:18:22
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): setInsecureRfcommSocketPort: Using port 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3288): onConnecting: null 7C:F9:0E:51:18:22
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3288): connect: Started connecting to null in address 7C:F9:0E:51:18:22
I/io.jxcore.node.ConnectionHelper( 3288): connect: Connection process successfully started (peer ID: 7C:F9:0E:51:18:22)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): Trying to connect to peer with address 7C:F9:0E:51:18:22 (thread ID: 337)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3288): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3288): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2142): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2142): info:x10
,D/        ( 2142): remote version info [7c:f9:0e:51:18:22]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2142): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2142): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2142): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:51:18:22 newState: 1
E/bt-btif ( 2142): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2142): Bond State Change Intent:7C:F9:0E:51:18:22 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2142): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2142): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:51:18:22 newState: 0
,D/BluetoothAdapterProperties( 2142): Failed to remove device: 7C:F9:0E:51:18:22
,I/BluetoothBondStateMachine( 2142): Bond State Change Intent:7C:F9:0E:51:18:22 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2142): StableState(): Entering Off State
,W/bt-btif ( 2142): new conn_srvc id:26, app_id:1
W/bt-btif ( 2142): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2142): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3288): onSocketConnected: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): Socket connection succeeded (using port 1), total number of attempts: 1 (thread ID: 337)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): onBytesWritten: 76 bytes successfully written (thread ID: 338)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): Outgoing connection initialized (*handshake* thread ID: 338)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): Exiting thread (thread ID: 337)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3288): Entering thread (ID: 338)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): onBytesRead: Read 83 bytes successfully (thread ID: 338)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): Handshake succeeded with [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3288): onHandshakeSucceeded: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3288): Exiting thread (ID: 338)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3288): onConnected: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
I/io.jxcore.node.ConnectionHelper( 3288): onConnected: Outgoing connection to peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
D/io.jxcore.node.ConnectionHelper( 3288): hasConnection: No connection with peer with ID 7C:F9:0E:51:18:22
W/io.jxcore.node.ConnectionHelper( 3288): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 3288): onConnected: Outgoing socket thread, for peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3288): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 3288): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 3288): Entering thread (ID: 339)
D/io.jxcore.node.OutgoingSocketThread( 3288): Server socket local port: 41961
I/io.jxcore.node.OutgoingSocketThread( 3288): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3288): onListeningForIncomingConnections: Outgoing connection is using port 41961 (peer ID: 7C:F9:0E:51:18:22)
,I/jxcore-log( 3288): 2015-12-18T18:41:47.576Z SendDataConnector.js: CLIENT connected to 41961, error: null
I/jxcore-log( 3288): 
I/jxcore-log( 3288): 2015-12-18T18:41:47.577Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3288): 
,I/io.jxcore.node.OutgoingSocketThread( 3288): Incoming data from address: /127.0.0.1, port: 41961
D/io.jxcore.node.OutgoingSocketThread( 3288): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3288): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 3288): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3288): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3288): Exiting thread (ID: 339)
,I/jxcore-log( 3288): 2015-12-18T18:41:47.604Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3288): 
,D/io.jxcore.node.StreamCopyingThread( 3288): Entering thread (ID: 341, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3288): Entering thread (ID: 340, name: Sender)
,D/        ( 2142): PORT_WriteDataCO: tx queue is full,tx.queue_size:10172,tx.queue.count:11,available:24706
,I/jxcore-log( 3288): 2015-12-18T18:41:48.180Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:41:48.246Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3288): 
,D/        ( 2142): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:14806
,I/jxcore-log( 3288): 2015-12-18T18:41:48.367Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:41:48.412Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3288): 
,D/        ( 2142): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:3916
,I/jxcore-log( 3288): 2015-12-18T18:41:48.549Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:41:48.570Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:41:48.616Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:41:48.660Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:41:48.703Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:41:48.757Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3288): 
I/jxcore-log( 3288): 2015-12-18T18:41:48.757Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3288): 
I/jxcore-log( 3288): oneRoundDownNow
I/jxcore-log( 3288): 
I/jxcore-log( 3288): 2015-12-18T18:41:48.757Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3288): 
I/jxcore-log( 3288): 2015-12-18T18:41:48.757Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3288): 
D/io.jxcore.node.ConnectionHelper( 3288): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:51:18:22
I/io.jxcore.node.ConnectionHelper( 3288): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 7C:F9:0E:51:18:22
I/io.jxcore.node.OutgoingSocketThread( 3288): close
D/io.jxcore.node.OutgoingSocketThread( 3288): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3288): doStop: Thread ID: 341
D/io.jxcore.node.OutgoingSocketThread( 3288): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3288): doStop: Thread ID: 340
D/io.jxcore.node.OutgoingSocketThread( 3288): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 3288): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3288): Either failed to read from the output stream or write to the input stream (thread ID: 340, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3288): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3288): onDisconnected: Outgoing connection, peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.OutgoingSocketThread( 3288): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 3288): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3288): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3288): Either failed to read from the output stream or write to the input stream (thread ID: 341, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.OutgoingSocketThread( 3288): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3288): onDisconnected: Outgoing connection, peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3288): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3288): disconnectOutgoingConnection: Successfully disconnected (peer ID: 7C:F9:0E:51:18:22
,E/io.jxcore.node.ConnectionHelper( 3288): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 3288): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3288): Exiting thread (ID: 340, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 3288): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 3288): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3288): Exiting thread (ID: 341, name: Receiver)
,W/bt-btif ( 2142): bta_jv_rfc_port_to_cb(port_handle:0xe):jv handle:0x0 not FOUND
,I/jxcore-log( 3288): 2015-12-18T18:41:48.779Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): ---- round done--------
I/jxcore-log( 3288): 
I/jxcore-log( 3288): startWithNextDevice
I/jxcore-log( 3288): 
I/jxcore-log( 3288): device[5]: F8:95:C7:87:3C:51
I/jxcore-log( 3288): 
I/jxcore-log( 3288): 2015-12-18T18:41:48.788Z SendDataConnector.js: Start called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3288): 
I/jxcore-log( 3288): 2015-12-18T18:41:48.788Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3288): 
I/jxcore-log( 3288): 2015-12-18T18:41:48.789Z SendDataConnector.js: do connect now
I/jxcore-log( 3288): 
I/io.jxcore.node.ConnectionHelper( 3288): connect: Trying to connect to peer with ID F8:95:C7:87:3C:51
,D/io.jxcore.node.ConnectionHelper( 3288): hasConnection: No connection with peer with ID F8:95:C7:87:3C:51
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3288): connect: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3288): connect: Trying to start connecting to null in address F8:95:C7:87:3C:51
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3288): onConnecting: null F8:95:C7:87:3C:51
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3288): connect: Started connecting to null in address F8:95:C7:87:3C:51
I/io.jxcore.node.ConnectionHelper( 3288): connect: Connection process successfully started (peer ID: F8:95:C7:87:3C:51)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): Trying to connect to peer with address F8:95:C7:87:3C:51 (thread ID: 342)
W/BluetoothAdapter( 3288): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2142): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2142): info:x10
,D/        ( 2142): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,E/BluetoothRemoteDevices( 2142): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2142): tBTM_SEC_DEV:0xa40515dc rs_disc_pending=1
W/bt-btif ( 2142): bta_dm_check_av:0
,W/bt-btif ( 2142): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2142): process_service_search_attr_rsp
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BluetoothBondStateMachine( 2142): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
E/bt-btif ( 2142): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2142): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2142): Entering PendingCommandState State
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BluetoothBondStateMachine( 2142): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,D/BluetoothAdapterProperties( 2142): Failed to remove device: F8:95:C7:87:3C:51
,I/BluetoothBondStateMachine( 2142): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2142): StableState(): Entering Off State
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): restart: Restarting...
,D/WifiP2pManager( 3288): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): Service request added successfully
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 2142): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2142): onReceive
,I/BTConnectionReceiver( 1375): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:51:18:22, alias=null, name=Thali Test (Galaxy A5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1375): Bluetooth Device Name: Thali Test (Galaxy A5)
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3288): onSocketConnected: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 342)
,W/bt-btif ( 2142): new conn_srvc id:26, app_id:1
W/bt-btif ( 2142): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2142): bta_dm_pm_ssr:2, lat:1200
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): onBytesWritten: 76 bytes successfully written (thread ID: 343)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): Outgoing connection initialized (*handshake* thread ID: 343)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): Exiting thread (thread ID: 342)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3288): Entering thread (ID: 343)
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): Service discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): onBytesRead: Read 77 bytes successfully (thread ID: 343)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): Handshake succeeded with [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3288): onHandshakeSucceeded: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3288): Exiting thread (ID: 343)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3288): onConnected: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
I/io.jxcore.node.ConnectionHelper( 3288): onConnected: Outgoing connection to peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
D/io.jxcore.node.ConnectionHelper( 3288): hasConnection: No connection with peer with ID F8:95:C7:87:3C:51
,W/io.jxcore.node.ConnectionHelper( 3288): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 3288): onConnected: Outgoing socket thread, for peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3288): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 3288): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 3288): Entering thread (ID: 344)
,D/io.jxcore.node.OutgoingSocketThread( 3288): Server socket local port: 38887
I/io.jxcore.node.OutgoingSocketThread( 3288): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3288): onListeningForIncomingConnections: Outgoing connection is using port 38887 (peer ID: F8:95:C7:87:3C:51)
I/jxcore-log( 3288): 2015-12-18T18:41:53.534Z SendDataConnector.js: CLIENT connected to 38887, error: null
I/jxcore-log( 3288): 
I/jxcore-log( 3288): 2015-12-18T18:41:53.535Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3288): 
,I/io.jxcore.node.OutgoingSocketThread( 3288): Incoming data from address: /127.0.0.1, port: 38887
D/io.jxcore.node.OutgoingSocketThread( 3288): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3288): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3288): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3288): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3288): Exiting thread (ID: 344)
,D/io.jxcore.node.StreamCopyingThread( 3288): Entering thread (ID: 346, name: Receiver)
,I/jxcore-log( 3288): 2015-12-18T18:41:53.567Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3288): 
,D/io.jxcore.node.StreamCopyingThread( 3288): Entering thread (ID: 345, name: Sender)
,E/bt-btm  ( 2142): tBTM_SEC_DEV:0xa40515dc rs_disc_pending=0
W/bt-btif ( 2142): bta_dm_check_av:0
,W/bt-btif ( 2142): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3288): 2015-12-18T18:41:54.195Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:41:54.293Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:41:54.375Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:41:54.493Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:41:54.746Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:41:55.565Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3288): 
,D/btif_config_util( 2142): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3288): 2015-12-18T18:41:56.028Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:41:56.138Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:41:56.559Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:41:56.969Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3288): 
I/jxcore-log( 3288): 2015-12-18T18:41:56.970Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): oneRoundDownNow
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:41:56.977Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3288): 
I/jxcore-log( 3288): 2015-12-18T18:41:56.977Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3288): 
D/io.jxcore.node.ConnectionHelper( 3288): disconnectOutgoingConnection: Trying to close connection to peer with ID F8:95:C7:87:3C:51
I/io.jxcore.node.ConnectionHelper( 3288): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: F8:95:C7:87:3C:51
I/io.jxcore.node.OutgoingSocketThread( 3288): close
D/io.jxcore.node.OutgoingSocketThread( 3288): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3288): doStop: Thread ID: 346
,D/io.jxcore.node.OutgoingSocketThread( 3288): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3288): doStop: Thread ID: 345
D/io.jxcore.node.OutgoingSocketThread( 3288): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 3288): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3288): Either failed to read from the output stream or write to the input stream (thread ID: 345, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3288): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3288): onDisconnected: Outgoing connection, peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 3288): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 3288): closeLocalSocketAndStreams: Closing the localhost socket...
,I/io.jxcore.node.OutgoingSocketThread( 3288): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3288): Either failed to read from the output stream or write to the input stream (thread ID: 346, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.OutgoingSocketThread( 3288): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3288): onDisconnected: Outgoing connection, peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3288): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3288): disconnectOutgoingConnection: Successfully disconnected (peer ID: F8:95:C7:87:3C:51
,E/io.jxcore.node.ConnectionHelper( 3288): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:95:C7:87:3C:51
D/io.jxcore.node.ConnectionHelper( 3288): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,D/io.jxcore.node.StreamCopyingThread( 3288): Exiting thread (ID: 345, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 3288): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:95:C7:87:3C:51
,D/io.jxcore.node.ConnectionHelper( 3288): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3288): Exiting thread (ID: 346, name: Receiver)
,I/jxcore-log( 3288): 2015-12-18T18:41:57.029Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): ---- round done--------
I/jxcore-log( 3288): 
I/jxcore-log( 3288): startWithNextDevice
I/jxcore-log( 3288): 
,W/bt-btif ( 2142): bta_jv_rfc_port_to_cb(port_handle:0xf):jv handle:0x0 not FOUND
,E/bt-btm  ( 2142): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2142): onReceive
,I/BTConnectionReceiver( 1375): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1375): Bluetooth Device Name: G4-1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): Got discovery timeout, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): setState: RESTARTING
,I/wpa_supplicant(  991): P2P-FIND-STOPPED 
,I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,W/bt-btif ( 2142): info:x10
,D/        ( 2142): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,E/BluetoothRemoteDevices( 2142): aclStateChangeCallback: Device is NULL
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
,I/BluetoothBondStateMachine( 2142): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 1
E/bt-btif ( 2142): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2142): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 2142): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2142): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 0
,D/BluetoothAdapterProperties( 2142): Failed to remove device: E0:DB:10:14:E2:C0
,I/BluetoothBondStateMachine( 2142): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2142): StableState(): Entering Off State
,W/bt-btif ( 2142): new conn_srvc id:26, app_id:255
W/bt-btif ( 2142): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2142): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3288): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3288): Incoming connection initialized (thread ID: 347)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3288): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3288): Entering thread (ID: 347)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3288): onBytesRead: Read 82 bytes successfully (thread ID: 347)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3288): Got valid identity from [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3591]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3288): onBytesWritten: 76 bytes successfully written (thread ID: 347)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3288): removeThreadFromList: Removing thread with ID 347
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3288): Handshake thread disposed (thread ID: 347)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3288): onIncomingConnectionConnected: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3591]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3288): Exiting thread (ID: 347)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3288): onConnected: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3591]
I/io.jxcore.node.ConnectionHelper( 3288): onConnected: Incoming connection to peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3591]
D/io.jxcore.node.ConnectionHelper( 3288): hasConnection: No connection with peer with ID E0:DB:10:14:E2:C0
D/io.jxcore.node.ConnectionHelper( 3288): notifyPeerAvailability: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3591] is available
,I/jxcore-log( 3288): peerAvailabilityChanged [{"peerIdentifier":"E0:DB:10:14:E2:C0","peerName":"samsung-SM-N910C_PT3591","peerAvailable":true}]
I/jxcore-log( 3288): 
I/jxcore-log( 3288): Found peer : samsung-SM-N910C_PT3591, Available: true
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): startWithNextDevice
I/jxcore-log( 3288): 
I/jxcore-log( 3288): device[6]: E0:DB:10:14:E2:C0
I/jxcore-log( 3288): 
I/jxcore-log( 3288): 2015-12-18T18:42:22.366Z SendDataConnector.js: Start called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:42:22.366Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3288): 
I/jxcore-log( 3288): 2015-12-18T18:42:22.367Z SendDataConnector.js: do connect now
I/jxcore-log( 3288): 
I/io.jxcore.node.ConnectionHelper( 3288): connect: Trying to connect to peer with ID E0:DB:10:14:E2:C0
,D/io.jxcore.node.ConnectionHelper( 3288): hasConnection: No connection with peer with ID E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3288): connect: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3591]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3288): connect: Trying to start connecting to Note4-1 in address E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3288): onConnecting: Note4-1 E0:DB:10:14:E2:C0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3288): connect: Started connecting to Note4-1 in address E0:DB:10:14:E2:C0
I/io.jxcore.node.ConnectionHelper( 3288): connect: Connection process successfully started (peer ID: E0:DB:10:14:E2:C0)
I/io.jxcore.node.ConnectionHelper( 3288): onConnected: Incoming socket thread, for peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3591], created successfully
D/io.jxcore.node.ConnectionHelper( 3288): onConnected: The total number of connections is now 1
,D/io.jxcore.node.IncomingSocketThread( 3288): Entering thread (ID: 349)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): Trying to connect to peer with address E0:DB:10:14:E2:C0 (thread ID: 348)
W/BluetoothAdapter( 3288): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2142): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/jxcore-log( 3288): 2015-12-18T18:42:22.376Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3288): 
,I/io.jxcore.node.IncomingSocketThread( 3288): Local host address: localhost/127.0.0.1, port: 60252
D/io.jxcore.node.IncomingSocketThread( 3288): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3288): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3288): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3288): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3288): Exiting thread (ID: 349)
,D/io.jxcore.node.StreamCopyingThread( 3288): Entering thread (ID: 351, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3288): Entering thread (ID: 350, name: Sender)
,W/bt-sdp  ( 2142): process_service_search_attr_rsp
,W/bt-btif ( 2142): new conn_srvc id:26, app_id:1
W/bt-btif ( 2142): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2142): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2142): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3288): onSocketConnected: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3591]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 348)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): onBytesWritten: 76 bytes successfully written (thread ID: 352)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): Outgoing connection initialized (*handshake* thread ID: 352)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): Exiting thread (thread ID: 348)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3288): Entering thread (ID: 352)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): onBytesRead: Read 82 bytes successfully (thread ID: 352)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): Handshake succeeded with [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3591]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3288): onHandshakeSucceeded: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3591]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3288): Exiting thread (ID: 352)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3288): onConnected: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3591]
I/io.jxcore.node.ConnectionHelper( 3288): onConnected: Outgoing connection to peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3591]
D/io.jxcore.node.ConnectionHelper( 3288): hasConnection: We have an incoming connection with peer with ID E0:DB:10:14:E2:C0
W/io.jxcore.node.ConnectionHelper( 3288): onConnected: Already connected with peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3591], continuing anyway...
W/io.jxcore.node.ConnectionHelper( 3288): modifyListOfDiscoveredPeers: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3591] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 3288): onConnected: Outgoing socket thread, for peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3591], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3288): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 3288): onConnected: The total number of connections is now 2
,D/io.jxcore.node.OutgoingSocketThread( 3288): Entering thread (ID: 353)
,D/io.jxcore.node.OutgoingSocketThread( 3288): Server socket local port: 38052
I/io.jxcore.node.OutgoingSocketThread( 3288): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3288): onListeningForIncomingConnections: Outgoing connection is using port 38052 (peer ID: E0:DB:10:14:E2:C0)
I/jxcore-log( 3288): 2015-12-18T18:42:22.756Z SendDataConnector.js: CLIENT connected to 38052, error: null
I/jxcore-log( 3288): 
I/jxcore-log( 3288): 2015-12-18T18:42:22.757Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3288): 
,I/io.jxcore.node.OutgoingSocketThread( 3288): Incoming data from address: /127.0.0.1, port: 38052
D/io.jxcore.node.OutgoingSocketThread( 3288): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3288): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3288): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3288): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3288): Exiting thread (ID: 353)
,I/jxcore-log( 3288): 2015-12-18T18:42:22.783Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3288): 
,D/io.jxcore.node.StreamCopyingThread( 3288): Entering thread (ID: 355, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3288): Entering thread (ID: 354, name: Sender)
,I/jxcore-log( 3288): 2015-12-18T18:42:23.295Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:42:23.303Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:42:23.341Z SendDataTCPServer.js: TCP/IP server has received 35640 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:42:23.359Z SendDataTCPServer.js: TCP/IP server has received 37620 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:42:23.368Z SendDataTCPServer.js: TCP/IP server has received 39600 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:42:23.373Z SendDataTCPServer.js: TCP/IP server has received 41580 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:42:23.379Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:42:23.402Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:42:23.516Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:42:23.854Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:42:23.992Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:42:24.128Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:42:24.231Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:42:24.529Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:42:24.600Z SendDataTCPServer.js: TCP/IP server has received 45540 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:42:24.609Z SendDataTCPServer.js: TCP/IP server has received 47520 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:42:24.618Z SendDataTCPServer.js: TCP/IP server has received 49500 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:42:24.628Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:42:24.672Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:42:24.702Z SendDataTCPServer.js: TCP/IP server has received 55440 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:42:24.715Z SendDataTCPServer.js: TCP/IP server has received 57420 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:42:24.729Z SendDataTCPServer.js: TCP/IP server has received 59400 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:42:24.754Z SendDataTCPServer.js: TCP/IP server has received 61380 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:42:24.765Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:42:24.818Z SendDataTCPServer.js: TCP/IP server has received 63360 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:42:24.854Z SendDataTCPServer.js: TCP/IP server has received 65340 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:42:24.861Z SendDataTCPServer.js: TCP/IP server has received 67320 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:42:24.872Z SendDataTCPServer.js: TCP/IP server has received 69300 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:42:24.906Z SendDataTCPServer.js: TCP/IP server has received 73260 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:42:25.105Z SendDataTCPServer.js: TCP/IP server has received 75240 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:42:25.144Z SendDataTCPServer.js: TCP/IP server has received 77220 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:42:25.167Z SendDataTCPServer.js: TCP/IP server has received 79200 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:42:25.302Z SendDataTCPServer.js: TCP/IP server has received 81180 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:42:25.310Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3288): 
I/jxcore-log( 3288): 2015-12-18T18:42:25.311Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3288): 
I/jxcore-log( 3288): oneRoundDownNow
I/jxcore-log( 3288): 
I/jxcore-log( 3288): 2015-12-18T18:42:25.313Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3288): 
I/jxcore-log( 3288): 2015-12-18T18:42:25.313Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3288): 
D/io.jxcore.node.ConnectionHelper( 3288): disconnectOutgoingConnection: Trying to close connection to peer with ID E0:DB:10:14:E2:C0
I/io.jxcore.node.ConnectionHelper( 3288): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: E0:DB:10:14:E2:C0
I/io.jxcore.node.OutgoingSocketThread( 3288): close
D/io.jxcore.node.OutgoingSocketThread( 3288): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3288): doStop: Thread ID: 355
D/io.jxcore.node.OutgoingSocketThread( 3288): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3288): doStop: Thread ID: 354
D/io.jxcore.node.OutgoingSocketThread( 3288): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 3288): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3288): Either failed to read from the output stream or write to the input stream (thread ID: 354, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3288): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3288): onDisconnected: Outgoing connection, peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3591] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 3288): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 3288): closeLocalSocketAndStreams: Closing the localhost socket...
,I/io.jxcore.node.OutgoingSocketThread( 3288): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3288): Either failed to read from the output stream or write to the input stream (thread ID: 355, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.OutgoingSocketThread( 3288): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3288): onDisconnected: Outgoing connection, peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3591] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3288): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3288): disconnectOutgoingConnection: Successfully disconnected (peer ID: E0:DB:10:14:E2:C0
,E/io.jxcore.node.ConnectionHelper( 3288): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID E0:DB:10:14:E2:C0
D/io.jxcore.node.ConnectionHelper( 3288): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3288): Exiting thread (ID: 354, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 3288): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID E0:DB:10:14:E2:C0
D/io.jxcore.node.ConnectionHelper( 3288): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3288): Exiting thread (ID: 355, name: Receiver)
,I/jxcore-log( 3288): 2015-12-18T18:42:25.349Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3288): 
I/jxcore-log( 3288): ---- round done--------
I/jxcore-log( 3288): 
I/jxcore-log( 3288): startWithNextDevice
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:42:25.372Z SendDataTCPServer.js: TCP/IP server has received 83160 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:42:25.429Z SendDataTCPServer.js: TCP/IP server has received 85140 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:42:25.437Z SendDataTCPServer.js: TCP/IP server has received 87120 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:42:25.441Z SendDataTCPServer.js: TCP/IP server has received 89100 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:42:25.485Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:42:25.490Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 3288): 
,W/bt-btif ( 2142): bta_jv_rfc_port_to_cb(port_handle:0x11):jv handle:0x0 not FOUND
,I/jxcore-log( 3288): 2015-12-18T18:42:25.521Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3288): 
,W/bt-btif ( 2142): invalid rfc slot id: 9
,W/io.jxcore.node.StreamCopyingThread( 3288): Either failed to read from the output stream or write to the input stream (thread ID: 351, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 3288): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3288): onDisconnected: Incoming connection, peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3591] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,I/io.jxcore.node.ConnectionHelper( 3288): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 349
D/io.jxcore.node.OutgoingSocketThread( 3288): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3288): doStop: Thread ID: 351
D/io.jxcore.node.OutgoingSocketThread( 3288): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3288): doStop: Thread ID: 350
D/io.jxcore.node.OutgoingSocketThread( 3288): closeLocalSocketAndStreams: Closing...
,D/io.jxcore.node.OutgoingSocketThread( 3288): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3288): Either failed to read from the output stream or write to the input stream (thread ID: 350, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3288): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3288): onDisconnected: Incoming connection, peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3591] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 3288): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 3288): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3288): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3288): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3288): Exiting thread (ID: 351, name: Receiver)
,D/io.jxcore.node.ConnectionHelper( 3288): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3288): Exiting thread (ID: 350, name: Sender)
,W/bt-rfcomm( 2142): rfc_find_lcid_mcb LCID reused LCID:0x4f current:0x0
W/bt-rfcomm( 2142): RFCOMM_DisconnectInd LCID:0x4f
,I/jxcore-log( 3288): 2015-12-18T18:42:25.599Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3288): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): setState: STARTED
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,D/btif_config_util( 2142): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): restart: Restarting...
,D/WifiP2pManager( 3288): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): Service request added successfully
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 2142): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2142): onReceive
,I/BTConnectionReceiver( 1375): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1375): Bluetooth Device Name: Note4-1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): Service discovery started successfully
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT7601","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
I/io.jxcore.node.ConnectionHelper( 3288): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601], Bluetooth address: 7C:F9:0E:51:18:22, device name: , device address: 7e:f9:0e:51:18:23
W/io.jxcore.node.ConnectionHelper( 3288): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT6677","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677]
I/io.jxcore.node.ConnectionHelper( 3288): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
D/io.jxcore.node.ConnectionHelper( 3288): notifyPeerAvailability: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677] is available
I/jxcore-log( 3288): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:34:8A:A0","peerName":"samsung-SM-G900F_PT6677","peerAvailable":true}]
I/jxcore-log( 3288): 
I/jxcore-log( 3288): Found peer : samsung-SM-G900F_PT6677, Available: true
I/jxcore-log( 3288): 
I/jxcore-log( 3288): startWithNextDevice
I/jxcore-log( 3288): 
I/jxcore-log( 3288): device[7]: 7C:F9:0E:34:8A:A0
I/jxcore-log( 3288): 
I/jxcore-log( 3288): 2015-12-18T18:42:32.227Z SendDataConnector.js: Start called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3288): 
I/jxcore-log( 3288): 2015-12-18T18:42:32.228Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3288): 
I/jxcore-log( 3288): 2015-12-18T18:42:32.229Z SendDataConnector.js: do connect now
I/jxcore-log( 3288): 
,I/io.jxcore.node.ConnectionHelper( 3288): connect: Trying to connect to peer with ID 7C:F9:0E:34:8A:A0
D/io.jxcore.node.ConnectionHelper( 3288): hasConnection: No connection with peer with ID 7C:F9:0E:34:8A:A0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3288): connect: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3288): connect: Trying to start connecting to null in address 7C:F9:0E:34:8A:A0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3288): onConnecting: null 7C:F9:0E:34:8A:A0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3288): connect: Started connecting to null in address 7C:F9:0E:34:8A:A0
I/io.jxcore.node.ConnectionHelper( 3288): connect: Connection process successfully started (peer ID: 7C:F9:0E:34:8A:A0)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): Trying to connect to peer with address 7C:F9:0E:34:8A:A0 (thread ID: 356)
W/BluetoothAdapter( 3288): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2142): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2142): info:x10
,D/        ( 2142): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,E/BluetoothRemoteDevices( 2142): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2142): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2142): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 1
E/bt-btif ( 2142): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2142): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2142): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2142): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 0
,D/BluetoothAdapterProperties( 2142): Failed to remove device: 7C:F9:0E:34:8A:A0
,I/BluetoothBondStateMachine( 2142): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2142): StableState(): Entering Off State
,W/bt-btif ( 2142): new conn_srvc id:26, app_id:1
W/bt-btif ( 2142): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2142): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3288): onSocketConnected: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 356)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): onBytesWritten: 76 bytes successfully written (thread ID: 357)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): Outgoing connection initialized (*handshake* thread ID: 357)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): Exiting thread (thread ID: 356)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3288): Entering thread (ID: 357)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): onBytesRead: Read 82 bytes successfully (thread ID: 357)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): Handshake succeeded with [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3288): onHandshakeSucceeded: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3288): Exiting thread (ID: 357)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3288): onConnected: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677]
I/io.jxcore.node.ConnectionHelper( 3288): onConnected: Outgoing connection to peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677]
D/io.jxcore.node.ConnectionHelper( 3288): hasConnection: No connection with peer with ID 7C:F9:0E:34:8A:A0
W/io.jxcore.node.ConnectionHelper( 3288): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 3288): onConnected: Outgoing socket thread, for peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3288): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 3288): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 3288): Entering thread (ID: 358)
D/io.jxcore.node.OutgoingSocketThread( 3288): Server socket local port: 33527
I/io.jxcore.node.OutgoingSocketThread( 3288): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3288): onListeningForIncomingConnections: Outgoing connection is using port 33527 (peer ID: 7C:F9:0E:34:8A:A0)
I/jxcore-log( 3288): 2015-12-18T18:42:36.608Z SendDataConnector.js: CLIENT connected to 33527, error: null
I/jxcore-log( 3288): 
I/jxcore-log( 3288): 2015-12-18T18:42:36.609Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3288): 
,I/io.jxcore.node.OutgoingSocketThread( 3288): Incoming data from address: /127.0.0.1, port: 33527
D/io.jxcore.node.OutgoingSocketThread( 3288): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3288): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 3288): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.OutgoingSocketThread( 3288): startStreamCopyingThreads: OK
,D/io.jxcore.node.OutgoingSocketThread( 3288): Exiting thread (ID: 358)
,I/jxcore-log( 3288): 2015-12-18T18:42:36.636Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3288): 
,D/io.jxcore.node.StreamCopyingThread( 3288): Entering thread (ID: 360, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3288): Entering thread (ID: 359, name: Sender)
,I/jxcore-log( 3288): 2015-12-18T18:42:37.196Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:42:37.250Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3288): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT3591","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3591]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onServiceDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3591]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3591]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3591], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Adding new peer: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3591]
,I/io.jxcore.node.ConnectionHelper( 3288): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3591], Bluetooth address: E0:DB:10:14:E2:C0, device name: Note4-1, device address: 92:b6:86:43:73:1c
W/io.jxcore.node.ConnectionHelper( 3288): modifyListOfDiscoveredPeers: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3591] already in the list, will not add again
,I/jxcore-log( 3288): 2015-12-18T18:42:37.446Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:42:37.529Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3288): 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3288): 2015-12-18T18:42:37.687Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:42:37.781Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:42:37.836Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3288): 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3591], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3591]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
,I/jxcore-log( 3288): 2015-12-18T18:42:38.043Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:42:38.107Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3288): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT1294","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294]
,I/jxcore-log( 3288): 2015-12-18T18:42:38.139Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3288): 
I/jxcore-log( 3288): 2015-12-18T18:42:38.144Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3288): 
I/jxcore-log( 3288): oneRoundDownNow
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:42:38.173Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3288): 
I/jxcore-log( 3288): 2015-12-18T18:42:38.173Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3288): 
,D/io.jxcore.node.ConnectionHelper( 3288): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:34:8A:A0
I/io.jxcore.node.ConnectionHelper( 3288): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 7C:F9:0E:34:8A:A0
I/io.jxcore.node.OutgoingSocketThread( 3288): close
,D/io.jxcore.node.OutgoingSocketThread( 3288): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3288): doStop: Thread ID: 360
D/io.jxcore.node.OutgoingSocketThread( 3288): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3288): doStop: Thread ID: 359
D/io.jxcore.node.OutgoingSocketThread( 3288): closeLocalSocketAndStreams: Closing...
,D/io.jxcore.node.OutgoingSocketThread( 3288): closeLocalSocketAndStreams: Closing the local input stream...
W/io.jxcore.node.StreamCopyingThread( 3288): Either failed to read from the output stream or write to the input stream (thread ID: 359, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3288): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
,W/io.jxcore.node.ConnectionHelper( 3288): onDisconnected: Outgoing connection, peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.OutgoingSocketThread( 3288): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 3288): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3288): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3288): Either failed to read from the output stream or write to the input stream (thread ID: 360, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 3288): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3288): onDisconnected: Outgoing connection, peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3288): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3288): disconnectOutgoingConnection: Successfully disconnected (peer ID: 7C:F9:0E:34:8A:A0
,E/io.jxcore.node.ConnectionHelper( 3288): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:34:8A:A0
D/io.jxcore.node.ConnectionHelper( 3288): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3288): Exiting thread (ID: 359, name: Sender)
E/io.jxcore.node.ConnectionHelper( 3288): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:34:8A:A0
D/io.jxcore.node.ConnectionHelper( 3288): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3288): Exiting thread (ID: 360, name: Receiver)
,I/jxcore-log( 3288): 2015-12-18T18:42:38.202Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3288): 
I/jxcore-log( 3288): ---- round done--------
I/jxcore-log( 3288): 
I/jxcore-log( 3288): startWithNextDevice
I/jxcore-log( 3288): 
I/io.jxcore.node.ConnectionHelper( 3288): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294], Bluetooth address: 08:EC:A9:50:75:41, device name: , device address: 0a:ec:a9:50:75:42
D/io.jxcore.node.ConnectionHelper( 3288): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294] is available
I/jxcore-log( 3288): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:75:41","peerName":"samsung-SM-A300FU_PT1294","peerAvailable":true}]
I/jxcore-log( 3288): 
I/jxcore-log( 3288): Found peer : samsung-SM-A300FU_PT1294, Available: true
I/jxcore-log( 3288): 
I/jxcore-log( 3288): startWithNextDevice
I/jxcore-log( 3288): 
I/jxcore-log( 3288): device[8]: 08:EC:A9:50:75:41
I/jxcore-log( 3288): 
I/jxcore-log( 3288): 2015-12-18T18:42:38.203Z SendDataConnector.js: Start called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3288): 
I/jxcore-log( 3288): 2015-12-18T18:42:38.203Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3288): 
I/jxcore-log( 3288): 2015-12-18T18:42:38.203Z SendDataConnector.js: do connect now
I/jxcore-log( 3288): 
I/io.jxcore.node.ConnectionHelper( 3288): connect: Trying to connect to peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 3288): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3288): connect: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3288): connect: Trying to start connecting to null in address 08:EC:A9:50:75:41
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3288): onConnecting: null 08:EC:A9:50:75:41
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3288): connect: Started connecting to null in address 08:EC:A9:50:75:41
I/io.jxcore.node.ConnectionHelper( 3288): connect: Connection process successfully started (peer ID: 08:EC:A9:50:75:41)
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT7096","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT7096]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT7096]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT7096]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT7096], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT7096]
,I/io.jxcore.node.ConnectionHelper( 3288): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT7096], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
D/io.jxcore.node.ConnectionHelper( 3288): notifyPeerAvailability: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT7096] is available
I/jxcore-log( 3288): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:85:54","peerName":"LGE-LG-D722_PT7096","peerAvailable":true}]
I/jxcore-log( 3288): 
I/jxcore-log( 3288): Found peer : LGE-LG-D722_PT7096, Available: true
I/jxcore-log( 3288): 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): Trying to connect to peer with address 08:EC:A9:50:75:41 (thread ID: 361)
W/BluetoothAdapter( 3288): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2142): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2142): bta_jv_rfc_port_to_cb(port_handle:0x12):jv handle:0x0 not FOUND
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 2142): tBTM_SEC_DEV:0xa405196c rs_disc_pending=1
W/bt-btif ( 2142): bta_dm_check_av:0
,W/bt-btif ( 2142): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2142): info:x10
,D/        ( 2142): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2142): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2142): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2142): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 1
E/bt-btif ( 2142): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2142): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2142): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2142): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 0
,D/BluetoothAdapterProperties( 2142): Failed to remove device: 08:EC:A9:50:75:41
,I/BluetoothBondStateMachine( 2142): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2142): StableState(): Entering Off State
,W/bt-btif ( 2142): new conn_srvc id:26, app_id:1
W/bt-btif ( 2142): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2142): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3288): onSocketConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 361)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): onBytesWritten: 76 bytes successfully written (thread ID: 362)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): Outgoing connection initialized (*handshake* thread ID: 362)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): Exiting thread (thread ID: 361)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3288): Entering thread (ID: 362)
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): onBytesRead: Read 83 bytes successfully (thread ID: 362)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): Handshake succeeded with [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3288): onHandshakeSucceeded: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3288): onConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294]
I/io.jxcore.node.ConnectionHelper( 3288): onConnected: Outgoing connection to peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294]
D/io.jxcore.node.ConnectionHelper( 3288): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
,W/io.jxcore.node.ConnectionHelper( 3288): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 3288): onConnected: Outgoing socket thread, for peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3288): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 3288): onConnected: The total number of connections is now 1
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3288): Exiting thread (ID: 362)
,D/io.jxcore.node.OutgoingSocketThread( 3288): Entering thread (ID: 363)
,D/io.jxcore.node.OutgoingSocketThread( 3288): Server socket local port: 46367
I/io.jxcore.node.OutgoingSocketThread( 3288): Now accepting connections...
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/io.jxcore.node.ConnectionHelper( 3288): onListeningForIncomingConnections: Outgoing connection is using port 46367 (peer ID: 08:EC:A9:50:75:41)
I/jxcore-log( 3288): 2015-12-18T18:42:40.255Z SendDataConnector.js: CLIENT connected to 46367, error: null
I/jxcore-log( 3288): 
I/jxcore-log( 3288): 2015-12-18T18:42:40.255Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3288): 
,I/io.jxcore.node.OutgoingSocketThread( 3288): Incoming data from address: /127.0.0.1, port: 46367
D/io.jxcore.node.OutgoingSocketThread( 3288): Setting local streams and starting stream copying threads...
,I/io.jxcore.node.StreamCopyingThread( 3288): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3288): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3288): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3288): Exiting thread (ID: 363)
,D/io.jxcore.node.StreamCopyingThread( 3288): Entering thread (ID: 365, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3288): Entering thread (ID: 364, name: Sender)
,I/jxcore-log( 3288): 2015-12-18T18:42:40.280Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3288): 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/        ( 2142): PORT_WriteDataCO: tx queue is full,tx.queue_size:10172,tx.queue.count:11,available:24706
,I/jxcore-log( 3288): 2015-12-18T18:42:41.091Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:42:41.125Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3288): 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3591], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3591]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT7096], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT7096]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): restart: Restarting...
,D/        ( 2142): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:14806
,I/jxcore-log( 3288): 2015-12-18T18:42:41.381Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3288): 
,D/WifiP2pManager( 3288): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): Service request added successfully
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3288): 2015-12-18T18:42:41.689Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3288): 
,D/        ( 2142): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:2926
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3288): 2015-12-18T18:42:42.028Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3288): 
,E/bt-btm  ( 2142): tBTM_SEC_DEV:0xa405196c rs_disc_pending=0
W/bt-btif ( 2142): bta_dm_check_av:0
,W/bt-btif ( 2142): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3288): 2015-12-18T18:42:42.059Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3288): 
,E/bt-btm  ( 2142): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2142): onReceive
,I/BTConnectionReceiver( 1375): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1375): Bluetooth Device Name: S5-1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): Service discovery started successfully
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3288): 2015-12-18T18:42:42.501Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:42:42.632Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:42:42.692Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:42:42.796Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3288): 
I/jxcore-log( 3288): 2015-12-18T18:42:42.797Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3288): 
I/jxcore-log( 3288): oneRoundDownNow
I/jxcore-log( 3288): 
I/jxcore-log( 3288): 2015-12-18T18:42:42.798Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3288): 
I/jxcore-log( 3288): 2015-12-18T18:42:42.799Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3288): 
,D/io.jxcore.node.ConnectionHelper( 3288): disconnectOutgoingConnection: Trying to close connection to peer with ID 08:EC:A9:50:75:41
I/io.jxcore.node.ConnectionHelper( 3288): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 08:EC:A9:50:75:41
I/io.jxcore.node.OutgoingSocketThread( 3288): close
D/io.jxcore.node.OutgoingSocketThread( 3288): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3288): doStop: Thread ID: 365
D/io.jxcore.node.OutgoingSocketThread( 3288): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3288): doStop: Thread ID: 364
D/io.jxcore.node.OutgoingSocketThread( 3288): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 3288): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3288): Either failed to read from the output stream or write to the input stream (thread ID: 364, thread name: Sender): Socket closed
,E/io.jxcore.node.OutgoingSocketThread( 3288): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3288): onDisconnected: Outgoing connection, peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 3288): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 3288): closeLocalSocketAndStreams: Closing the localhost socket...
,I/io.jxcore.node.OutgoingSocketThread( 3288): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3288): Either failed to read from the output stream or write to the input stream (thread ID: 365, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.OutgoingSocketThread( 3288): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3288): onDisconnected: Outgoing connection, peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3288): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3288): disconnectOutgoingConnection: Successfully disconnected (peer ID: 08:EC:A9:50:75:41
,E/io.jxcore.node.ConnectionHelper( 3288): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 3288): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,W/bt-btif ( 2142): bta_jv_rfc_port_to_cb(port_handle:0x13):jv handle:0x0 not FOUND
,E/io.jxcore.node.ConnectionHelper( 3288): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:75:41
,D/io.jxcore.node.StreamCopyingThread( 3288): Exiting thread (ID: 364, name: Sender)
,D/io.jxcore.node.ConnectionHelper( 3288): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3288): Exiting thread (ID: 365, name: Receiver)
,I/jxcore-log( 3288): 2015-12-18T18:42:42.856Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3288): 
I/jxcore-log( 3288): ---- round done--------
I/jxcore-log( 3288): 
I/jxcore-log( 3288): startWithNextDevice
I/jxcore-log( 3288): 
I/jxcore-log( 3288): device[9]: F8:95:C7:87:85:54
I/jxcore-log( 3288): 
I/jxcore-log( 3288): 2015-12-18T18:42:42.856Z SendDataConnector.js: Start called with peer F8:95:C7:87:85:54
I/jxcore-log( 3288): 
I/jxcore-log( 3288): 2015-12-18T18:42:42.856Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3288): 
I/jxcore-log( 3288): 2015-12-18T18:42:42.856Z SendDataConnector.js: do connect now
I/jxcore-log( 3288): 
I/io.jxcore.node.ConnectionHelper( 3288): connect: Trying to connect to peer with ID F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 3288): hasConnection: No connection with peer with ID F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3288): connect: [F8:95:C7:87:85:54 LGE-LG-D722_PT7096]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3288): connect: Trying to start connecting to null in address F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3288): onConnecting: null F8:95:C7:87:85:54
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3288): connect: Started connecting to null in address F8:95:C7:87:85:54
I/io.jxcore.node.ConnectionHelper( 3288): connect: Connection process successfully started (peer ID: F8:95:C7:87:85:54)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): Trying to connect to peer with address F8:95:C7:87:85:54 (thread ID: 366)
W/BluetoothAdapter( 3288): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2142): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/btif_config_util( 2142): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 2142): info:x10
,D/        ( 2142): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,E/BluetoothRemoteDevices( 2142): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2142): tBTM_SEC_DEV:0xa4051cfc rs_disc_pending=1
W/bt-btif ( 2142): bta_dm_check_av:0
,W/bt-btif ( 2142): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 2142): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2142): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1
E/bt-btif ( 2142): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2142): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2142): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2142): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
D/BluetoothAdapterProperties( 2142): Failed to remove device: F8:95:C7:87:85:54
,I/BluetoothBondStateMachine( 2142): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2142): StableState(): Entering Off State
,E/bt-btm  ( 2142): tBTM_SEC_DEV:0xa4051cfc rs_disc_pending=0
W/bt-btif ( 2142): bta_dm_check_av:0
W/bt-btif ( 2142): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2142): new conn_srvc id:26, app_id:1
W/bt-btif ( 2142): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2142): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3288): onSocketConnected: [F8:95:C7:87:85:54 LGE-LG-D722_PT7096]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 366)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): onBytesWritten: 76 bytes successfully written (thread ID: 367)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): Outgoing connection initialized (*handshake* thread ID: 367)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): Exiting thread (thread ID: 366)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3288): Entering thread (ID: 367)
,E/bt-btm  ( 2142): tBTM_SEC_DEV:0xa4051cfc rs_disc_pending=1
W/bt-btif ( 2142): bta_dm_check_av:0
,W/bt-btif ( 2142): btif_dm_cback : unhandled event (14)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): onBytesRead: Read 77 bytes successfully (thread ID: 367)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): Handshake succeeded with [F8:95:C7:87:85:54 LGE-LG-D722_PT7096]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3288): onHandshakeSucceeded: [F8:95:C7:87:85:54 LGE-LG-D722_PT7096]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3288): Exiting thread (ID: 367)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3288): onConnected: [F8:95:C7:87:85:54 LGE-LG-D722_PT7096]
I/io.jxcore.node.ConnectionHelper( 3288): onConnected: Outgoing connection to peer [F8:95:C7:87:85:54 LGE-LG-D722_PT7096]
D/io.jxcore.node.ConnectionHelper( 3288): hasConnection: No connection with peer with ID F8:95:C7:87:85:54
W/io.jxcore.node.ConnectionHelper( 3288): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT7096] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 3288): onConnected: Outgoing socket thread, for peer [F8:95:C7:87:85:54 LGE-LG-D722_PT7096], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3288): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 3288): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 3288): Entering thread (ID: 368)
,D/io.jxcore.node.OutgoingSocketThread( 3288): Server socket local port: 39487
I/io.jxcore.node.OutgoingSocketThread( 3288): Now accepting connections...
,W/bt-btif ( 2142): new conn_srvc id:26, app_id:255
W/bt-btif ( 2142): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2142): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2142): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3288): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3288): Incoming connection initialized (thread ID: 369)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3288): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3288): Entering thread (ID: 369)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3288): onBytesRead: Read 77 bytes successfully (thread ID: 369)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3288): Got valid identity from [F8:95:C7:87:85:54 LGE-LG-D722_PT7096]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3288): onBytesWritten: 76 bytes successfully written (thread ID: 369)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3288): removeThreadFromList: Removing thread with ID 369
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3288): Handshake thread disposed (thread ID: 369)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3288): onIncomingConnectionConnected: [F8:95:C7:87:85:54 LGE-LG-D722_PT7096]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3288): Exiting thread (ID: 369)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3288): onConnected: [F8:95:C7:87:85:54 LGE-LG-D722_PT7096]
I/io.jxcore.node.ConnectionHelper( 3288): onConnected: Incoming connection to peer [F8:95:C7:87:85:54 LGE-LG-D722_PT7096]
D/io.jxcore.node.ConnectionHelper( 3288): hasConnection: We have an outgoing connection with peer with ID F8:95:C7:87:85:54
W/io.jxcore.node.ConnectionHelper( 3288): onConnected: Already connected with peer [F8:95:C7:87:85:54 LGE-LG-D722_PT7096], continuing anyway...
W/io.jxcore.node.ConnectionHelper( 3288): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT7096] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 3288): onConnected: Incoming socket thread, for peer [F8:95:C7:87:85:54 LGE-LG-D722_PT7096], created successfully
D/io.jxcore.node.ConnectionHelper( 3288): onConnected: The total number of connections is now 2
,D/io.jxcore.node.IncomingSocketThread( 3288): Entering thread (ID: 370)
,I/io.jxcore.node.ConnectionHelper( 3288): onListeningForIncomingConnections: Outgoing connection is using port 39487 (peer ID: F8:95:C7:87:85:54)
I/jxcore-log( 3288): 2015-12-18T18:42:45.067Z SendDataConnector.js: CLIENT connected to 39487, error: null
I/jxcore-log( 3288): 
I/jxcore-log( 3288): 2015-12-18T18:42:45.067Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3288): 
,I/io.jxcore.node.IncomingSocketThread( 3288): Incoming data from address: /127.0.0.1, port: 39487
D/io.jxcore.node.IncomingSocketThread( 3288): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3288): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3288): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3288): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3288): Exiting thread (ID: 368)
,I/jxcore-log( 3288): 2015-12-18T18:42:45.080Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3288): 
,I/io.jxcore.node.IncomingSocketThread( 3288): Local host address: localhost/127.0.0.1, port: 60252
D/io.jxcore.node.IncomingSocketThread( 3288): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3288): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 3288): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3288): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3288): Exiting thread (ID: 370)
,D/io.jxcore.node.StreamCopyingThread( 3288): Entering thread (ID: 372, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3288): Entering thread (ID: 371, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 3288): Entering thread (ID: 374, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3288): Entering thread (ID: 373, name: Sender)
,I/jxcore-log( 3288): 2015-12-18T18:42:45.485Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:42:46.139Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:42:46.151Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:42:46.157Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:42:46.165Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:42:46.172Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:42:46.183Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:42:46.211Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:42:46.217Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:42:46.219Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:42:46.220Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:42:46.222Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:42:46.224Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:42:46.226Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:42:46.227Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:42:46.230Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:42:46.232Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:42:46.236Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:42:46.241Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:42:46.265Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:42:46.266Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3288): 
I/jxcore-log( 3288): oneRoundDownNow
I/jxcore-log( 3288): 
I/jxcore-log( 3288): 2015-12-18T18:42:46.266Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:42:46.267Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3288): 
,D/io.jxcore.node.ConnectionHelper( 3288): disconnectOutgoingConnection: Trying to close connection to peer with ID F8:95:C7:87:85:54
I/io.jxcore.node.ConnectionHelper( 3288): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: F8:95:C7:87:85:54
I/io.jxcore.node.IncomingSocketThread( 3288): close
D/io.jxcore.node.IncomingSocketThread( 3288): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3288): doStop: Thread ID: 372
D/io.jxcore.node.IncomingSocketThread( 3288): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3288): doStop: Thread ID: 371
D/io.jxcore.node.IncomingSocketThread( 3288): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 3288): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3288): Either failed to read from the output stream or write to the input stream (thread ID: 371, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3288): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3288): onDisconnected: Outgoing connection, peer [F8:95:C7:87:85:54 LGE-LG-D722_PT7096] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.IncomingSocketThread( 3288): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 3288): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3288): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3288): Either failed to read from the output stream or write to the input stream (thread ID: 372, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 3288): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3288): onDisconnected: Outgoing connection, peer [F8:95:C7:87:85:54 LGE-LG-D722_PT7096] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3288): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3288): disconnectOutgoingConnection: Successfully disconnected (peer ID: F8:95:C7:87:85:54
,E/io.jxcore.node.ConnectionHelper( 3288): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 3288): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3288): Exiting thread (ID: 371, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 3288): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 3288): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3288): Exiting thread (ID: 372, name: Receiver)
,I/jxcore-log( 3288): 2015-12-18T18:42:46.274Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): ---- round done--------
I/jxcore-log( 3288): 
I/jxcore-log( 3288): startWithNextDevice
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:42:46.277Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:42:46.427Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:42:46.574Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:42:46.579Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:42:46.634Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:42:46.672Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:42:46.692Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 3288): 
,W/bt-btif ( 2142): bta_jv_rfc_port_to_cb(port_handle:0x14):jv handle:0x0 not FOUND
,I/jxcore-log( 3288): 2015-12-18T18:42:46.705Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:42:46.727Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:42:46.765Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:42:46.781Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:42:46.789Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:42:46.837Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3288): 
,E/bt-btm  ( 2142): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2142): onReceive
,I/BTConnectionReceiver( 1375): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1375): Bluetooth Device Name: A3-1
,W/io.jxcore.node.StreamCopyingThread( 3288): Either failed to read from the output stream or write to the input stream (thread ID: 374, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 3288): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3288): onDisconnected: Incoming connection, peer [F8:95:C7:87:85:54 LGE-LG-D722_PT7096] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3288): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 370
D/io.jxcore.node.IncomingSocketThread( 3288): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3288): doStop: Thread ID: 374
D/io.jxcore.node.IncomingSocketThread( 3288): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3288): doStop: Thread ID: 373
D/io.jxcore.node.IncomingSocketThread( 3288): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 3288): closeLocalSocketAndStreams: Closing the local input stream...
D/io.jxcore.node.IncomingSocketThread( 3288): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 3288): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3288): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3288): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3288): Exiting thread (ID: 374, name: Receiver)
,W/io.jxcore.node.StreamCopyingThread( 3288): Either failed to read from the output stream or write to the input stream (thread ID: 373, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3288): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3288): onDisconnected: Incoming connection, peer [F8:95:C7:87:85:54 LGE-LG-D722_PT7096] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.ConnectionHelper( 3288): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3288): Exiting thread (ID: 373, name: Sender)
,W/bt-btif ( 2142): invalid rfc slot id: 14
,I/jxcore-log( 3288): 2015-12-18T18:42:46.911Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3288): 
,D/btif_config_util( 2142): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2142): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2142): onReceive
,I/BTConnectionReceiver( 1375): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1375): Bluetooth Device Name: G3s-1
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT7178], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT7178]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3591], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3591]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT7096], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT7096]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): restart: Restarting...
,D/WifiP2pManager( 3288): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): Service request added successfully
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): Service discovery started successfully
,W/bt-btif ( 2142): info:x10
,D/        ( 2142): remote version info [f8:95:c7:87:3c:51]: 6, f, 410d
,I/BTConnectionReceiver( 1375): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1375): Bluetooth Device Name: G4-1
,I/BluetoothBondStateMachine( 2142): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
E/bt-btif ( 2142): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2142): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2142): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2142): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,D/BluetoothAdapterProperties( 2142): Failed to remove device: F8:95:C7:87:3C:51
,I/BluetoothBondStateMachine( 2142): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2142): StableState(): Entering Off State
,W/bt-btif ( 2142): new conn_srvc id:26, app_id:255
W/bt-btif ( 2142): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2142): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3288): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3288): Incoming connection initialized (thread ID: 375)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3288): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3288): Entering thread (ID: 375)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3288): onBytesRead: Read 77 bytes successfully (thread ID: 375)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3288): Got valid identity from [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3288): onBytesWritten: 76 bytes successfully written (thread ID: 375)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3288): removeThreadFromList: Removing thread with ID 375
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3288): Handshake thread disposed (thread ID: 375)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3288): onIncomingConnectionConnected: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3288): Exiting thread (ID: 375)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3288): onConnected: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
I/io.jxcore.node.ConnectionHelper( 3288): onConnected: Incoming connection to peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
D/io.jxcore.node.ConnectionHelper( 3288): hasConnection: No connection with peer with ID F8:95:C7:87:3C:51
W/io.jxcore.node.ConnectionHelper( 3288): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 3288): onConnected: Incoming socket thread, for peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], created successfully
D/io.jxcore.node.ConnectionHelper( 3288): onConnected: The total number of connections is now 1
,D/io.jxcore.node.IncomingSocketThread( 3288): Entering thread (ID: 376)
,I/io.jxcore.node.IncomingSocketThread( 3288): Local host address: localhost/127.0.0.1, port: 60252
D/io.jxcore.node.IncomingSocketThread( 3288): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3288): setBufferSize: Setting buffer size to 8192 bytes
,I/jxcore-log( 3288): 2015-12-18T18:42:59.266Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3288): 
,I/io.jxcore.node.StreamCopyingThread( 3288): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3288): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3288): Exiting thread (ID: 376)
,D/io.jxcore.node.StreamCopyingThread( 3288): Entering thread (ID: 378, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3288): Entering thread (ID: 377, name: Sender)
,I/jxcore-log( 3288): 2015-12-18T18:42:59.927Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:42:59.935Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:42:59.956Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:42:59.967Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:42:59.989Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:43:00.001Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:43:00.010Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:43:00.029Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:43:00.067Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:43:00.077Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:43:00.115Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:43:00.133Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:43:00.138Z SendDataTCPServer.js: TCP/IP server has received 32768 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:43:00.172Z SendDataTCPServer.js: TCP/IP server has received 34748 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:43:00.202Z SendDataTCPServer.js: TCP/IP server has received 36728 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:43:00.214Z SendDataTCPServer.js: TCP/IP server has received 38708 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:43:00.227Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:43:00.270Z SendDataTCPServer.js: TCP/IP server has received 42668 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:43:00.302Z SendDataTCPServer.js: TCP/IP server has received 48608 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:43:00.318Z SendDataTCPServer.js: TCP/IP server has received 50588 bytes of data
I/jxcore-log( 3288): ,
,I/jxcore-log( 3288): 2015-12-18T18:43:00.334Z SendDataTCPServer.js: TCP/IP server has received 56528 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:43:00.367Z SendDataTCPServer.js: TCP/IP server has received 62468 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:43:00.394Z SendDataTCPServer.js: TCP/IP server has received 64448 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:43:00.440Z SendDataTCPServer.js: TCP/IP server has received 68408 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:43:00.448Z SendDataTCPServer.js: TCP/IP server has received 72368 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:43:00.474Z SendDataTCPServer.js: TCP/IP server has received 74348 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:43:00.513Z SendDataTCPServer.js: TCP/IP server has received 80288 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:43:00.522Z SendDataTCPServer.js: TCP/IP server has received 82268 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:43:00.555Z SendDataTCPServer.js: TCP/IP server has received 84248 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:43:00.559Z SendDataTCPServer.js: TCP/IP server has received 86228 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:43:00.569Z SendDataTCPServer.js: TCP/IP server has received 88208 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:43:00.595Z SendDataTCPServer.js: TCP/IP server has received 92168 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:43:00.606Z SendDataTCPServer.js: TCP/IP server has received 94148 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:43:00.644Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3288): 
,W/bt-btif ( 2142): invalid rfc slot id: 19
,W/io.jxcore.node.StreamCopyingThread( 3288): Either failed to read from the output stream or write to the input stream (thread ID: 378, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.IncomingSocketThread( 3288): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3288): onDisconnected: Incoming connection, peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,I/io.jxcore.node.ConnectionHelper( 3288): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 376
D/io.jxcore.node.IncomingSocketThread( 3288): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3288): doStop: Thread ID: 378
D/io.jxcore.node.IncomingSocketThread( 3288): close: Stopping sending thread...
,I/io.jxcore.node.StreamCopyingThread( 3288): doStop: Thread ID: 377
D/io.jxcore.node.IncomingSocketThread( 3288): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 3288): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3288): Either failed to read from the output stream or write to the input stream (thread ID: 377, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3288): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3288): onDisconnected: Incoming connection, peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.IncomingSocketThread( 3288): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 3288): closeLocalSocketAndStreams: Closing the localhost socket...
,I/io.jxcore.node.IncomingSocketThread( 3288): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3288): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.ConnectionHelper( 3288): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3288): Exiting thread (ID: 377, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 3288): Exiting thread (ID: 378, name: Receiver)
,I/jxcore-log( 3288): 2015-12-18T18:43:00.742Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3288): 
,W/bt-rfcomm( 2142): rfc_find_lcid_mcb LCID reused LCID:0x4b current:0x0
,W/bt-rfcomm( 2142): RFCOMM_DisconnectInd LCID:0x4b
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): checkListForExpiredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Removed [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
,I/io.jxcore.node.ConnectionHelper( 3288): onPeerLost: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
D/io.jxcore.node.ConnectionHelper( 3288): hasConnection: No connection with peer with ID F8:95:C7:87:3C:51
,D/io.jxcore.node.ConnectionHelper( 3288): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864] removed
D/io.jxcore.node.ConnectionHelper( 3288): notifyPeerAvailability: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864] not available
,I/jxcore-log( 3288): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:3C:51","peerName":"LGE-LG-H815_PT1864","peerAvailable":false}]
I/jxcore-log( 3288): 
I/jxcore-log( 3288): startWithNextDevice
I/jxcore-log( 3288): 
,E/bt-btm  ( 2142): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2142): onReceive
,I/BTConnectionReceiver( 1375): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1375): Bluetooth Device Name: G4-1
,D/btif_config_util( 2142): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 2142): info:x10
,D/        ( 2142): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 6109
,I/BTConnectionReceiver( 1375): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1375): Bluetooth Device Name: S5-1
,W/bt-btif ( 2142): new conn_srvc id:26, app_id:255
W/bt-btif ( 2142): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2142): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3288): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3288): Incoming connection initialized (thread ID: 379)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3288): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3288): Entering thread (ID: 379)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3288): onBytesRead: Read 82 bytes successfully (thread ID: 379)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3288): Got valid identity from [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3288): onBytesWritten: 76 bytes successfully written (thread ID: 379)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3288): removeThreadFromList: Removing thread with ID 379
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3288): Handshake thread disposed (thread ID: 379)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3288): onIncomingConnectionConnected: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3288): Exiting thread (ID: 379)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3288): onConnected: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677]
I/io.jxcore.node.ConnectionHelper( 3288): onConnected: Incoming connection to peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677]
,D/io.jxcore.node.ConnectionHelper( 3288): hasConnection: No connection with peer with ID 7C:F9:0E:34:8A:A0
,W/io.jxcore.node.ConnectionHelper( 3288): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 3288): onConnected: Incoming socket thread, for peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677], created successfully
D/io.jxcore.node.ConnectionHelper( 3288): onConnected: The total number of connections is now 1
,D/io.jxcore.node.IncomingSocketThread( 3288): Entering thread (ID: 380)
,I/io.jxcore.node.IncomingSocketThread( 3288): Local host address: localhost/127.0.0.1, port: 60252
D/io.jxcore.node.IncomingSocketThread( 3288): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3288): setBufferSize: Setting buffer size to 8192 bytes
,I/jxcore-log( 3288): 2015-12-18T18:43:13.557Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3288): 
,I/io.jxcore.node.StreamCopyingThread( 3288): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3288): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3288): Exiting thread (ID: 380)
,D/io.jxcore.node.StreamCopyingThread( 3288): Entering thread (ID: 382, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3288): Entering thread (ID: 381, name: Sender)
,I/jxcore-log( 3288): 2015-12-18T18:43:14.499Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:43:14.508Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:43:14.518Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:43:14.525Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:43:14.535Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:43:14.541Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:43:14.556Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:43:14.581Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:43:14.585Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:43:14.592Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:43:14.631Z SendDataTCPServer.js: TCP/IP server has received 42668 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:43:14.633Z SendDataTCPServer.js: TCP/IP server has received 44648 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:43:14.635Z SendDataTCPServer.js: TCP/IP server has received 46628 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:43:14.671Z SendDataTCPServer.js: TCP/IP server has received 60488 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:43:14.674Z SendDataTCPServer.js: TCP/IP server has received 62468 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:43:14.679Z SendDataTCPServer.js: TCP/IP server has received 64448 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:43:14.711Z SendDataTCPServer.js: TCP/IP server has received 72368 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:43:14.724Z SendDataTCPServer.js: TCP/IP server has received 74348 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:43:14.762Z SendDataTCPServer.js: TCP/IP server has received 84248 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:43:14.768Z SendDataTCPServer.js: TCP/IP server has received 86228 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:43:14.782Z SendDataTCPServer.js: TCP/IP server has received 88208 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:43:14.811Z SendDataTCPServer.js: TCP/IP server has received 92168 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:43:14.918Z SendDataTCPServer.js: TCP/IP server has received 94148 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:43:14.954Z SendDataTCPServer.js: TCP/IP server has received 98108 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:43:14.980Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3288): 
,W/bt-btif ( 2142): invalid rfc slot id: 20
,W/io.jxcore.node.StreamCopyingThread( 3288): Either failed to read from the output stream or write to the input stream (thread ID: 382, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.IncomingSocketThread( 3288): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3288): onDisconnected: Incoming connection, peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3288): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 380
,D/io.jxcore.node.IncomingSocketThread( 3288): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3288): doStop: Thread ID: 382
D/io.jxcore.node.IncomingSocketThread( 3288): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3288): doStop: Thread ID: 381
D/io.jxcore.node.IncomingSocketThread( 3288): closeLocalSocketAndStreams: Closing...
,D/io.jxcore.node.IncomingSocketThread( 3288): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3288): Either failed to read from the output stream or write to the input stream (thread ID: 381, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3288): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3288): onDisconnected: Incoming connection, peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.IncomingSocketThread( 3288): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 3288): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3288): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3288): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3288): Exiting thread (ID: 382, name: Receiver)
,D/io.jxcore.node.ConnectionHelper( 3288): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3288): Exiting thread (ID: 381, name: Sender)
,I/jxcore-log( 3288): 2015-12-18T18:43:15.133Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3288): 
,W/bt-rfcomm( 2142): rfc_find_lcid_mcb LCID reused LCID:0x4d current:0x0
W/bt-rfcomm( 2142): RFCOMM_DisconnectInd LCID:0x4d
,D/btif_config_util( 2142): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2142): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2142): onReceive
,I/BTConnectionReceiver( 1375): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1375): Bluetooth Device Name: S5-1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): setState: RESTARTING
,I/wpa_supplicant(  991): P2P-FIND-STOPPED 
,I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): Start timer timeout, starting now...
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): restart: Restarting...
,D/WifiP2pManager( 3288): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): Service request added successfully
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): Service discovery started successfully
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): restart: Restarting...
,D/WifiP2pManager( 3288): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): Service request added successfully
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294]
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT6677","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677]
I/io.jxcore.node.ConnectionHelper( 3288): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
W/io.jxcore.node.ConnectionHelper( 3288): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT7601","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
I/io.jxcore.node.ConnectionHelper( 3288): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601], Bluetooth address: 7C:F9:0E:51:18:22, device name: , device address: 7e:f9:0e:51:18:23
W/io.jxcore.node.ConnectionHelper( 3288): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601] already in the list, will not add again
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): restart: Restarting...
,D/WifiP2pManager( 3288): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): Service request added successfully
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT2896","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896]
,I/io.jxcore.node.ConnectionHelper( 3288): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896], Bluetooth address: 7C:F9:0E:37:96:AB, device name: , device address: 7e:f9:0e:37:96:ac
,D/io.jxcore.node.ConnectionHelper( 3288): notifyPeerAvailability: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896] is available
,I/jxcore-log( 3288): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:37:96:AB","peerName":"samsung-SM-A500FU_PT2896","peerAvailable":true}]
I/jxcore-log( 3288): 
I/jxcore-log( 3288): Found peer : samsung-SM-A500FU_PT2896, Available: true
I/jxcore-log( 3288): 
I/jxcore-log( 3288): startWithNextDevice
I/jxcore-log( 3288): 
I/jxcore-log( 3288): device[10]: 7C:F9:0E:37:96:AB
I/jxcore-log( 3288): 
I/jxcore-log( 3288): 2015-12-18T18:43:55.059Z SendDataConnector.js: Start called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:43:55.064Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:43:55.067Z SendDataConnector.js: do connect now
I/jxcore-log( 3288): 
,I/io.jxcore.node.ConnectionHelper( 3288): connect: Trying to connect to peer with ID 7C:F9:0E:37:96:AB
,D/io.jxcore.node.ConnectionHelper( 3288): hasConnection: No connection with peer with ID 7C:F9:0E:37:96:AB
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3288): connect: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3288): connect: Trying to start connecting to null in address 7C:F9:0E:37:96:AB
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3288): onConnecting: null 7C:F9:0E:37:96:AB
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3288): connect: Started connecting to null in address 7C:F9:0E:37:96:AB
I/io.jxcore.node.ConnectionHelper( 3288): connect: Connection process successfully started (peer ID: 7C:F9:0E:37:96:AB)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): Trying to connect to peer with address 7C:F9:0E:37:96:AB (thread ID: 383)
W/BluetoothAdapter( 3288): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2142): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2142): info:x10
,D/        ( 2142): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2142): aclStateChangeCallback: Device is NULL
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): checkListForExpiredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT7096] expired
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): checkListForExpiredPeers: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3591] expired
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): checkListForExpiredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT7178] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT7096], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Removed [F8:95:C7:87:85:54 LGE-LG-D722_PT7096]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3591], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Removed [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3591]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT7178], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Removed [58:3F:54:73:64:C0 LGE-LG-D855_PT7178]
I/io.jxcore.node.ConnectionHelper( 3288): onPeerLost: [F8:95:C7:87:85:54 LGE-LG-D722_PT7096]
D/io.jxcore.node.ConnectionHelper( 3288): hasConnection: No connection with peer with ID F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 3288): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT7096] removed
D/io.jxcore.node.ConnectionHelper( 3288): notifyPeerAvailability: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT7096] not available
I/jxcore-log( 3288): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:85:54","peerName":"LGE-LG-D722_PT7096","peerAvailable":false}]
I/jxcore-log( 3288): 
I/io.jxcore.node.ConnectionHelper( 3288): onPeerLost: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3591]
D/io.jxcore.node.ConnectionHelper( 3288): hasConnection: No connection with peer with ID E0:DB:10:14:E2:C0
D/io.jxcore.node.ConnectionHelper( 3288): modifyListOfDiscoveredPeers: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3591] removed
D/io.jxcore.node.ConnectionHelper( 3288): notifyPeerAvailability: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3591] not available
I/jxcore-log( 3288): peerAvailabilityChanged [{"peerIdentifier":"E0:DB:10:14:E2:C0","peerName":"samsung-SM-N910C_PT3591","peerAvailable":false}]
I/jxcore-log( 3288): 
I/io.jxcore.node.ConnectionHelper( 3288): onPeerLost: [58:3F:54:73:64:C0 LGE-LG-D855_PT7178]
D/io.jxcore.node.ConnectionHelper( 3288): hasConnection: No connection with peer with ID 58:3F:54:73:64:C0
D/io.jxcore.node.ConnectionHelper( 3288): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT7178] removed
D/io.jxcore.node.ConnectionHelper( 3288): notifyPeerAvailability: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT7178] not available
I/jxcore-log( 3288): peerAvailabilityChanged [{"peerIdentifier":"58:3F:54:73:64:C0","peerName":"LGE-LG-D855_PT7178","peerAvailable":false}]
I/jxcore-log( 3288): 
,D/btif_config_util( 2142): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3288): Connection timeout
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3288): onConnectionTimeout: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896]
,I/jxcore-log( 3288): 2015-12-18T18:44:10.098Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896] timed out
I/jxcore-log( 3288): 
I/jxcore-log( 3288): 2015-12-18T18:44:10.099Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896] timed out
I/jxcore-log( 3288): 
I/jxcore-log( 3288): 2015-12-18T18:44:10.100Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:44:15.104Z SendDataConnector.js: re-try now : 7C:F9:0E:37:96:AB
I/jxcore-log( 3288): 
I/jxcore-log( 3288): 2015-12-18T18:44:15.105Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3288): 
,D/io.jxcore.node.ConnectionHelper( 3288): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:37:96:AB
E/io.jxcore.node.ConnectionHelper( 3288): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 3288): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3288): disconnectOutgoingConnection: Failed to disconnect (peer ID: 7C:F9:0E:37:96:AB), either no such connection or failed to close the connection
I/jxcore-log( 3288): 2015-12-18T18:44:20.110Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:44:20.120Z SendDataConnector.js: Connect (retry count 1) to peer 7C:F9:0E:37:96:AB with availability status: true
I/jxcore-log( 3288): 
I/jxcore-log( 3288): 2015-12-18T18:44:20.120Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3288): 
I/jxcore-log( 3288): 2015-12-18T18:44:20.121Z SendDataConnector.js: do connect now
I/jxcore-log( 3288): 
I/io.jxcore.node.ConnectionHelper( 3288): connect: Trying to connect to peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 3288): hasConnection: No connection with peer with ID 7C:F9:0E:37:96:AB
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3288): connect: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3288): connect: Trying to start connecting to null in address 7C:F9:0E:37:96:AB
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3288): onConnecting: null 7C:F9:0E:37:96:AB
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3288): connect: Started connecting to null in address 7C:F9:0E:37:96:AB
I/io.jxcore.node.ConnectionHelper( 3288): connect: Connection process successfully started (peer ID: 7C:F9:0E:37:96:AB)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): Trying to connect to peer with address 7C:F9:0E:37:96:AB (thread ID: 385)
W/BluetoothAdapter( 3288): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2142): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): setState: RESTARTING
,I/wpa_supplicant(  991): P2P-FIND-STOPPED 
,I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): Start timer timeout, starting now...
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): restart: Restarting...
,D/WifiP2pManager( 3288): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): Service request added successfully
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  991): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294]
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): Service discovery started successfully
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT1294","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294]
I/io.jxcore.node.ConnectionHelper( 3288): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper( 3288): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT1691","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onServiceDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Adding new peer: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691]
I/io.jxcore.node.ConnectionHelper( 3288): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
W/io.jxcore.node.ConnectionHelper( 3288): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3288): Connection timeout
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3288): onConnectionTimeout: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896]
I/jxcore-log( 3288): 2015-12-18T18:44:35.134Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896] timed out
I/jxcore-log( 3288): 
I/jxcore-log( 3288): 2015-12-18T18:44:35.134Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896] timed out
I/jxcore-log( 3288): 
I/jxcore-log( 3288): 2015-12-18T18:44:35.135Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3288): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT7601","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
I/io.jxcore.node.ConnectionHelper( 3288): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
W/io.jxcore.node.ConnectionHelper( 3288): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601] already in the list, will not add again
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294]
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294]
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294]
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3288): 2015-12-18T18:44:40.136Z SendDataConnector.js: re-try now : 7C:F9:0E:37:96:AB
I/jxcore-log( 3288): 
I/jxcore-log( 3288): 2015-12-18T18:44:40.137Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3288): 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): restart: Restarting...
,D/WifiP2pManager( 3288): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): Service request added successfully
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): Service discovery started successfully
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/io.jxcore.node.ConnectionHelper( 3288): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:37:96:AB
E/io.jxcore.node.ConnectionHelper( 3288): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 3288): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3288): disconnectOutgoingConnection: Failed to disconnect (peer ID: 7C:F9:0E:37:96:AB), either no such connection or failed to close the connection
,I/jxcore-log( 3288): 2015-12-18T18:44:45.150Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3288): 
I/jxcore-log( 3288): 2015-12-18T18:44:45.151Z SendDataConnector.js: Connect (retry count 2) to peer 7C:F9:0E:37:96:AB with availability status: true
I/jxcore-log( 3288): 
I/jxcore-log( 3288): 2015-12-18T18:44:45.151Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3288): 
I/jxcore-log( 3288): 2015-12-18T18:44:45.152Z SendDataConnector.js: do connect now
I/jxcore-log( 3288): 
I/io.jxcore.node.ConnectionHelper( 3288): connect: Trying to connect to peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 3288): hasConnection: No connection with peer with ID 7C:F9:0E:37:96:AB
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3288): connect: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3288): connect: Trying to start connecting to null in address 7C:F9:0E:37:96:AB
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3288): onConnecting: null 7C:F9:0E:37:96:AB
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3288): connect: Started connecting to null in address 7C:F9:0E:37:96:AB
I/io.jxcore.node.ConnectionHelper( 3288): connect: Connection process successfully started (peer ID: 7C:F9:0E:37:96:AB)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): Trying to connect to peer with address 7C:F9:0E:37:96:AB (thread ID: 387)
W/BluetoothAdapter( 3288): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2142): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1864","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
I/io.jxcore.node.ConnectionHelper( 3288): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
D/io.jxcore.node.ConnectionHelper( 3288): notifyPeerAvailability: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864] is available
I/jxcore-log( 3288): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:3C:51","peerName":"LGE-LG-H815_PT1864","peerAvailable":true}]
I/jxcore-log( 3288): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT1294","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294]
I/io.jxcore.node.ConnectionHelper( 3288): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper( 3288): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT1691","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onServiceDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Adding new peer: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691]
,I/io.jxcore.node.ConnectionHelper( 3288): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
W/io.jxcore.node.ConnectionHelper( 3288): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT3591","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3591]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onServiceDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3591]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3591]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3591], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Adding new peer: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3591]
I/io.jxcore.node.ConnectionHelper( 3288): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3591], Bluetooth address: E0:DB:10:14:E2:C0, device name: Note4-1, device address: 92:b6:86:43:73:1c
D/io.jxcore.node.ConnectionHelper( 3288): notifyPeerAvailability: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3591] is available
,I/jxcore-log( 3288): peerAvailabilityChanged [{"peerIdentifier":"E0:DB:10:14:E2:C0","peerName":"samsung-SM-N910C_PT3591","peerAvailable":true}]
I/jxcore-log( 3288): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT7601","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
I/io.jxcore.node.ConnectionHelper( 3288): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
W/io.jxcore.node.ConnectionHelper( 3288): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601] already in the list, will not add again
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3591], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3591]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT6677","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677]
I/io.jxcore.node.ConnectionHelper( 3288): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
W/io.jxcore.node.ConnectionHelper( 3288): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677] already in the list, will not add again
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  991): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 6 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294]
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294]
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): restart: Restarting...
,D/WifiP2pManager( 3288): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): Service request added successfully
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT6677","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677]
I/io.jxcore.node.ConnectionHelper( 3288): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
W/io.jxcore.node.ConnectionHelper( 3288): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1864","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
I/io.jxcore.node.ConnectionHelper( 3288): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3288): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT1294","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294]
I/io.jxcore.node.ConnectionHelper( 3288): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
,W/io.jxcore.node.ConnectionHelper( 3288): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3288): Connection timeout
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3288): onConnectionTimeout: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896]
I/jxcore-log( 3288): 2015-12-18T18:45:00.167Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896] timed out
I/jxcore-log( 3288): 
I/jxcore-log( 3288): 2015-12-18T18:45:00.167Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896] timed out
I/jxcore-log( 3288): 
I/jxcore-log( 3288): 2015-12-18T18:45:00.168Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3288): 
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): checkListForExpiredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Removed [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896]
I/io.jxcore.node.ConnectionHelper( 3288): onPeerLost: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896]
D/io.jxcore.node.ConnectionHelper( 3288): hasConnection: No connection with peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 3288): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896] removed
D/io.jxcore.node.ConnectionHelper( 3288): notifyPeerAvailability: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896] not available
I/jxcore-log( 3288): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:37:96:AB","peerName":"samsung-SM-A500FU_PT2896","peerAvailable":false}]
I/jxcore-log( 3288): 
,E/bt-btm  ( 2142): btm_sec_disconnected - Clearing Pending flag
,W/bt-sdp  ( 2142): SDP - Rcvd conn cnf with error: 0xeeee  CID 0x4e
E/bt-btif ( 2142): DISCOVERY_COMP_EVT slot id:22, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2142): invalid rfc slot id: 22
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): shutdown (thread ID: 383)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 383)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): Maximum number of allowed retries (0) reached, giving up... (thread ID: 383)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3288): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): Exiting thread (thread ID: 383)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3288): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896]
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3288): setInsecureRfcommSocketPort: Will use port 1 when trying to connect
,I/jxcore-log( 3288): 2015-12-18T18:45:05.169Z SendDataConnector.js: re-try now : 7C:F9:0E:37:96:AB
I/jxcore-log( 3288): 
I/jxcore-log( 3288): 2015-12-18T18:45:05.170Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3288): 
,W/bt-sdp  ( 2142): SDP - Rcvd conn cnf with error: 0x4  CID 0x40
E/bt-btif ( 2142): DISCOVERY_COMP_EVT slot id:23, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2142): invalid rfc slot id: 23
,E/BluetoothRemoteDevices( 2142): aclStateChangeCallback: Device is NULL
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): shutdown (thread ID: 385)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): Exiting thread (thread ID: 385)
,D/io.jxcore.node.ConnectionHelper( 3288): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:37:96:AB
E/io.jxcore.node.ConnectionHelper( 3288): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 3288): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3288): disconnectOutgoingConnection: Failed to disconnect (peer ID: 7C:F9:0E:37:96:AB), either no such connection or failed to close the connection
I/jxcore-log( 3288): 2015-12-18T18:45:10.178Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3288): 
I/jxcore-log( 3288): 2015-12-18T18:45:10.178Z SendDataConnector.js: Connect (retry count 3) to peer 7C:F9:0E:37:96:AB with availability status: true
I/jxcore-log( 3288): 
I/jxcore-log( 3288): 2015-12-18T18:45:10.179Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3288): 
I/jxcore-log( 3288): 2015-12-18T18:45:10.179Z SendDataConnector.js: do connect now
I/jxcore-log( 3288): 
,I/io.jxcore.node.ConnectionHelper( 3288): connect: Trying to connect to peer with ID 7C:F9:0E:37:96:AB
,D/io.jxcore.node.ConnectionHelper( 3288): hasConnection: No connection with peer with ID 7C:F9:0E:37:96:AB
W/io.jxcore.node.ConnectionHelper( 3288): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3288): connect: [7C:F9:0E:37:96:AB 7C:F9:0E:37:96:AB]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3288): connect: Trying to start connecting to null in address 7C:F9:0E:37:96:AB
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): setInsecureRfcommSocketPort: Using port 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3288): onConnecting: null 7C:F9:0E:37:96:AB
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3288): connect: Started connecting to null in address 7C:F9:0E:37:96:AB
I/io.jxcore.node.ConnectionHelper( 3288): connect: Connection process successfully started (peer ID: 7C:F9:0E:37:96:AB)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): Trying to connect to peer with address 7C:F9:0E:37:96:AB (thread ID: 389)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3288): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3288): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2142): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2142): SDP - Rcvd conn cnf with error: 0xf  CID 0x4f
E/bt-btif ( 2142): DISCOVERY_COMP_EVT slot id:24, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2142): invalid rfc slot id: 24
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): shutdown (thread ID: 387)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 387)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): Maximum number of allowed retries (0) reached, giving up... (thread ID: 387)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3288): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): Exiting thread (thread ID: 387)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3288): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896]
I/jxcore-log( 3288): 2015-12-18T18:45:12.007Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896] failed
I/jxcore-log( 3288): 
I/jxcore-log( 3288): 2015-12-18T18:45:12.007Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896] failed
I/jxcore-log( 3288): 
I/jxcore-log( 3288): 2015-12-18T18:45:12.008Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3288): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3288): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2142): info:x10
,D/        ( 2142): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2142): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3288): 2015-12-18T18:45:17.010Z SendDataConnector.js: re-try now : 7C:F9:0E:37:96:AB
I/jxcore-log( 3288): 
I/jxcore-log( 3288): 2015-12-18T18:45:17.010Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3288): 
,W/bt-sdp  ( 2142): process_service_search_attr_rsp
,D/btif_config_util( 2142): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/BluetoothBondStateMachine( 2142): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 1
E/bt-btif ( 2142): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2142): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2142): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 2142): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 0
,D/BluetoothAdapterProperties( 2142): Failed to remove device: 7C:F9:0E:37:96:AB
,I/BluetoothBondStateMachine( 2142): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2142): StableState(): Entering Off State
,D/io.jxcore.node.ConnectionHelper( 3288): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:37:96:AB
E/io.jxcore.node.ConnectionHelper( 3288): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 3288): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,W/io.jxcore.node.ConnectionHelper( 3288): disconnectOutgoingConnection: Failed to disconnect (peer ID: 7C:F9:0E:37:96:AB), either no such connection or failed to close the connection
I/jxcore-log( 3288): 2015-12-18T18:45:22.016Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3288): 
I/jxcore-log( 3288): 2015-12-18T18:45:22.016Z SendDataConnector.js: Connect (retry count 4) to peer 7C:F9:0E:37:96:AB with availability status: true
I/jxcore-log( 3288): 
I/jxcore-log( 3288): 2015-12-18T18:45:22.017Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3288): 
I/jxcore-log( 3288): 2015-12-18T18:45:22.017Z SendDataConnector.js: do connect now
I/jxcore-log( 3288): 
I/io.jxcore.node.ConnectionHelper( 3288): connect: Trying to connect to peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 3288): hasConnection: No connection with peer with ID 7C:F9:0E:37:96:AB
W/io.jxcore.node.ConnectionHelper( 3288): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3288): connect: [7C:F9:0E:37:96:AB 7C:F9:0E:37:96:AB]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3288): connect: Trying to start connecting to A5-1 in address 7C:F9:0E:37:96:AB
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3288): onConnecting: A5-1 7C:F9:0E:37:96:AB
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3288): connect: Started connecting to A5-1 in address 7C:F9:0E:37:96:AB
I/io.jxcore.node.ConnectionHelper( 3288): connect: Connection process successfully started (peer ID: 7C:F9:0E:37:96:AB)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): Trying to connect to peer with address 7C:F9:0E:37:96:AB (thread ID: 391)
W/BluetoothAdapter( 3288): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2142): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/btif_config_util( 2142): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): setState: RESTARTING
,I/wpa_supplicant(  991): P2P-FIND-STOPPED 
,I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
,W/bt-rfcomm( 2142): PORT_StartCnf failed result:5
E/bt-btif ( 2142): DISCOVERY_COMP_EVT slot id:26, failed to find channle,                                       status:1, scn:0
E/bt-btm  ( 2142): btm_sec_disconnected - Clearing Pending flag
,W/bt-btif ( 2142): invalid rfc slot id: 25
W/bt-btif ( 2142): invalid rfc slot id: 26
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 391)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): Maximum number of allowed retries (0) reached, giving up... (thread ID: 391)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3288): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
,W/BluetoothAdapter( 3288): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): Exiting thread (thread ID: 391)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3288): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [7C:F9:0E:37:96:AB 7C:F9:0E:37:96:AB]
,I/jxcore-log( 3288): 2015-12-18T18:45:25.603Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [7C:F9:0E:37:96:AB 7C:F9:0E:37:96:AB] failed
I/jxcore-log( 3288): 
I/jxcore-log( 3288): 2015-12-18T18:45:25.604Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [7C:F9:0E:37:96:AB 7C:F9:0E:37:96:AB] failed
I/jxcore-log( 3288): 
I/jxcore-log( 3288): oneRoundDownNow
I/jxcore-log( 3288): 
I/jxcore-log( 3288): 2015-12-18T18:45:25.606Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3288): 
D/io.jxcore.node.ConnectionHelper( 3288): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:37:96:AB
E/io.jxcore.node.ConnectionHelper( 3288): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 3288): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3288): disconnectOutgoingConnection: Failed to disconnect (peer ID: 7C:F9:0E:37:96:AB), either no such connection or failed to close the connection
I/jxcore-log( 3288): 2015-12-18T18:45:25.609Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3288): 
I/jxcore-log( 3288): ---- round done--------
I/jxcore-log( 3288): 
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): shutdown (thread ID: 391)
,I/jxcore-log( 3288): startWithNextDevice
I/jxcore-log( 3288): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3288): setInsecureRfcommSocketPort: Will use port 1 when trying to connect
,D/BluetoothMapService( 2142): onReceive
,D/BTIF_SOCK( 2142): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/BTConnectionReceiver( 1375): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1375): Bluetooth Device Name: A5-1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): Start timer timeout, starting now...
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): restart: Restarting...
,D/WifiP2pManager( 3288): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): Service request added successfully
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): Service discovery started successfully
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): restart: Restarting...
,D/WifiP2pManager( 3288): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): Service request added successfully
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): Service discovery started successfully
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1864","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
I/io.jxcore.node.ConnectionHelper( 3288): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3288): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864] already in the list, will not add again
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/ActivityManager(  759): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=3852 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,I/GAv4    ( 3852): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3852):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3852):   adb logcat -s GAv4
,W/GAv4    ( 3852): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3852): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3852): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  759): Killing 2033:com.google.android.calendar/u0a31 (adj 15): empty #17
,W/libprocessgroup(  759): failed to open /acct/uid_10031/pid_2033/cgroup.procs: No such file or directory
,W/bt-sdp  ( 2142): SDP - Rcvd conn cnf with error: 0x22  CID 0x45
E/bt-btif ( 2142): DISCOVERY_COMP_EVT slot id:27, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2142): invalid rfc slot id: 27
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): shutdown (thread ID: 389)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 389)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): Maximum number of allowed retries (0) reached, giving up... (thread ID: 389)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3288): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3288): Exiting thread (thread ID: 389)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3288): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [7C:F9:0E:37:96:AB 7C:F9:0E:37:96:AB]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3288): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): restart: Restarting...
,D/WifiP2pManager( 3288): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): checkListForExpiredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677] expired
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): checkListForExpiredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Removed [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Removed [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294]
I/io.jxcore.node.ConnectionHelper( 3288): onPeerLost: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677]
D/io.jxcore.node.ConnectionHelper( 3288): hasConnection: No connection with peer with ID 7C:F9:0E:34:8A:A0
D/io.jxcore.node.ConnectionHelper( 3288): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677] removed
D/io.jxcore.node.ConnectionHelper( 3288): notifyPeerAvailability: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677] not available
I/jxcore-log( 3288): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:34:8A:A0","peerName":"samsung-SM-G900F_PT6677","peerAvailable":false}]
I/jxcore-log( 3288): 
I/jxcore-log( 3288): startWithNextDevice
I/jxcore-log( 3288): 
I/io.jxcore.node.ConnectionHelper( 3288): onPeerLost: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294]
D/io.jxcore.node.ConnectionHelper( 3288): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
,D/io.jxcore.node.ConnectionHelper( 3288): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294] removed
D/io.jxcore.node.ConnectionHelper( 3288): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294] not available
,I/jxcore-log( 3288): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:75:41","peerName":"samsung-SM-A300FU_PT1294","peerAvailable":false}]
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): startWithNextDevice
I/jxcore-log( 3288): 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): Service discovery started successfully
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT3591","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3591]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onServiceDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3591]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3591]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3591], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Adding new peer: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3591]
I/io.jxcore.node.ConnectionHelper( 3288): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3591], Bluetooth address: E0:DB:10:14:E2:C0, device name: Note4-1, device address: 92:b6:86:43:73:1c
,W/io.jxcore.node.ConnectionHelper( 3288): modifyListOfDiscoveredPeers: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3591] already in the list, will not add again
,W/bt-btif ( 2142): info:x10
,D/        ( 2142): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1375): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1375): Bluetooth Device Name: A5-1
,W/bt-btif ( 2142): new conn_srvc id:26, app_id:255
W/bt-btif ( 2142): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2142): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3288): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3288): Incoming connection initialized (thread ID: 393)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3288): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3288): Entering thread (ID: 393)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3288): onBytesRead: Read 83 bytes successfully (thread ID: 393)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3288): Got valid identity from [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3288): onBytesWritten: 76 bytes successfully written (thread ID: 393)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3288): removeThreadFromList: Removing thread with ID 393
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3288): Handshake thread disposed (thread ID: 393)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3288): onIncomingConnectionConnected: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3288): onConnected: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896]
I/io.jxcore.node.ConnectionHelper( 3288): onConnected: Incoming connection to peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896]
D/io.jxcore.node.ConnectionHelper( 3288): hasConnection: No connection with peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 3288): notifyPeerAvailability: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896] is available
I/jxcore-log( 3288): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:37:96:AB","peerName":"samsung-SM-A500FU_PT2896","peerAvailable":true}]
I/jxcore-log( 3288): 
I/jxcore-log( 3288): startWithNextDevice
I/jxcore-log( 3288): 
I/io.jxcore.node.ConnectionHelper( 3288): onConnected: Incoming socket thread, for peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896], created successfully
D/io.jxcore.node.ConnectionHelper( 3288): onConnected: The total number of connections is now 1
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3288): Exiting thread (ID: 393)
,D/io.jxcore.node.IncomingSocketThread( 3288): Entering thread (ID: 394)
,I/io.jxcore.node.IncomingSocketThread( 3288): Local host address: localhost/127.0.0.1, port: 60252
D/io.jxcore.node.IncomingSocketThread( 3288): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3288): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3288): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3288): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3288): Exiting thread (ID: 394)
,I/jxcore-log( 3288): 2015-12-18T18:46:06.462Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3288): 
,D/io.jxcore.node.StreamCopyingThread( 3288): Entering thread (ID: 395, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 3288): Entering thread (ID: 396, name: Receiver)
,I/jxcore-log( 3288): 2015-12-18T18:46:07.175Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:46:07.181Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:46:07.205Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:46:07.223Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:46:07.233Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:46:07.278Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:46:07.290Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:46:07.328Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:46:07.342Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:46:07.379Z SendDataTCPServer.js: TCP/IP server has received 45540 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:46:07.396Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:46:07.435Z SendDataTCPServer.js: TCP/IP server has received 55440 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:46:07.443Z SendDataTCPServer.js: TCP/IP server has received 59400 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:46:07.452Z SendDataTCPServer.js: TCP/IP server has received 65340 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:46:07.476Z SendDataTCPServer.js: TCP/IP server has received 73260 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:46:07.504Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:46:07.530Z SendDataTCPServer.js: TCP/IP server has received 99000 bytes of data
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:46:07.552Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3288): 
,W/bt-btif ( 2142): invalid rfc slot id: 21
,W/io.jxcore.node.StreamCopyingThread( 3288): Either failed to read from the output stream or write to the input stream (thread ID: 396, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.IncomingSocketThread( 3288): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3288): onDisconnected: Incoming connection, peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,I/io.jxcore.node.ConnectionHelper( 3288): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 394
D/io.jxcore.node.IncomingSocketThread( 3288): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3288): doStop: Thread ID: 396
D/io.jxcore.node.IncomingSocketThread( 3288): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3288): doStop: Thread ID: 395
,D/io.jxcore.node.IncomingSocketThread( 3288): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 3288): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3288): Either failed to read from the output stream or write to the input stream (thread ID: 395, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3288): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3288): onDisconnected: Incoming connection, peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.IncomingSocketThread( 3288): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 3288): closeLocalSocketAndStreams: Closing the localhost socket...
,I/io.jxcore.node.IncomingSocketThread( 3288): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3288): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.ConnectionHelper( 3288): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.StreamCopyingThread( 3288): Exiting thread (ID: 395, name: Sender)
,W/bt-rfcomm( 2142): rfc_find_lcid_mcb LCID reused LCID:0x48 current:0x0
W/bt-rfcomm( 2142): RFCOMM_DisconnectInd LCID:0x48
,D/io.jxcore.node.StreamCopyingThread( 3288): Exiting thread (ID: 396, name: Receiver)
,I/jxcore-log( 3288): 2015-12-18T18:46:07.655Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3288): 
,D/btif_config_util( 2142): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2142): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2142): onReceive
,I/BTConnectionReceiver( 1375): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1375): Bluetooth Device Name: A5-1
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3591], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3591]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): restart: Restarting...
,D/WifiP2pManager( 3288): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): Service request added successfully
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): Service discovery started successfully
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3591], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3591]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT7601","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
I/io.jxcore.node.ConnectionHelper( 3288): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601], Bluetooth address: 7C:F9:0E:51:18:22, device name: , device address: 7e:f9:0e:51:18:23
W/io.jxcore.node.ConnectionHelper( 3288): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): setState: RESTARTING
,I/wpa_supplicant(  991): P2P-FIND-STOPPED 
,I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): Start timer timeout, starting now...
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): restart: Restarting...
,D/WifiP2pManager( 3288): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): Service request added successfully
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): Service discovery started successfully
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1864","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
I/io.jxcore.node.ConnectionHelper( 3288): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3288): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT7601","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
I/io.jxcore.node.ConnectionHelper( 3288): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
W/io.jxcore.node.ConnectionHelper( 3288): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601] already in the list, will not add again
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  991): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  991): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
,D/WifiP2pManager( 3288): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): Service request added successfully
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  991): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): Service discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  991): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], add/update: true,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT6677","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677]
I/io.jxcore.node.ConnectionHelper( 3288): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
D/io.jxcore.node.ConnectionHelper( 3288): notifyPeerAvailability: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677] is available
I/jxcore-log( 3288): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:34:8A:A0","peerName":"samsung-SM-G900F_PT6677","peerAvailable":true}]
I/jxcore-log( 3288): 
I/jxcore-log( 3288): startWithNextDevice
I/jxcore-log( 3288): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT7096","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT7096]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT7096]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT7096]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT7096], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT7096]
I/io.jxcore.node.ConnectionHelper( 3288): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT7096], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
D/io.jxcore.node.ConnectionHelper( 3288): notifyPeerAvailability: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT7096] is available
I/jxcore-log( 3288): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:85:54","peerName":"LGE-LG-D722_PT7096","peerAvailable":true}]
I/jxcore-log( 3288): 
I/jxcore-log( 3288): startWithNextDevice
I/jxcore-log( 3288): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT2896","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896]
I/io.jxcore.node.ConnectionHelper( 3288): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
,W/io.jxcore.node.ConnectionHelper( 3288): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896] already in the list, will not add again
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): checkListForExpiredPeers: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3591] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3591], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Removed [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3591]
I/io.jxcore.node.ConnectionHelper( 3288): onPeerLost: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3591]
D/io.jxcore.node.ConnectionHelper( 3288): hasConnection: No connection with peer with ID E0:DB:10:14:E2:C0
D/io.jxcore.node.ConnectionHelper( 3288): modifyListOfDiscoveredPeers: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3591] removed
D/io.jxcore.node.ConnectionHelper( 3288): notifyPeerAvailability: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3591] not available
I/jxcore-log( 3288): peerAvailabilityChanged [{"peerIdentifier":"E0:DB:10:14:E2:C0","peerName":"samsung-SM-N910C_PT3591","peerAvailable":false}]
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): startWithNextDevice
I/jxcore-log( 3288): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): setState: RESTARTING
,I/wpa_supplicant(  991): P2P-FIND-STOPPED 
,I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): setState: STARTED
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  991): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT7096], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT7096]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
,D/WifiP2pManager( 3288): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): Service request added successfully
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  991): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): Service discovery started successfully
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  991): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT1691","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onServiceDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Adding new peer: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691]
I/io.jxcore.node.ConnectionHelper( 3288): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
W/io.jxcore.node.ConnectionHelper( 3288): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT6677","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677]
I/io.jxcore.node.ConnectionHelper( 3288): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
W/io.jxcore.node.ConnectionHelper( 3288): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT2896","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896]
I/io.jxcore.node.ConnectionHelper( 3288): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 3288): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896] already in the list, will not add again
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): restart: Restarting...
,D/WifiP2pManager( 3288): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): Service request added successfully
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): Service discovery started successfully
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): setState: RESTARTING
,I/wpa_supplicant(  991): P2P-FIND-STOPPED 
,I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): Start timer timeout, starting now...
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  991): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  991): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
,D/WifiP2pManager( 3288): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): Service request added successfully
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): Service discovery started successfully
,I/wpa_supplicant(  991): p2p0: P2P: Reject scan trigger since one is already pending
I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT7601","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
,I/io.jxcore.node.ConnectionHelper( 3288): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601], Bluetooth address: 7C:F9:0E:51:18:22, device name: , device address: 7e:f9:0e:51:18:23
W/io.jxcore.node.ConnectionHelper( 3288): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT3591","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3591]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onServiceDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3591]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3591]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3591], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Adding new peer: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3591]
,I/io.jxcore.node.ConnectionHelper( 3288): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3591], Bluetooth address: E0:DB:10:14:E2:C0, device name: Note4-1, device address: 92:b6:86:43:73:1c
D/io.jxcore.node.ConnectionHelper( 3288): notifyPeerAvailability: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3591] is available
I/jxcore-log( 3288): peerAvailabilityChanged [{"peerIdentifier":"E0:DB:10:14:E2:C0","peerName":"samsung-SM-N910C_PT3591","peerAvailable":true}]
I/jxcore-log( 3288): 
I/jxcore-log( 3288): startWithNextDevice
I/jxcore-log( 3288): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT1294","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294]
,I/io.jxcore.node.ConnectionHelper( 3288): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294], Bluetooth address: 08:EC:A9:50:75:41, device name: , device address: 0a:ec:a9:50:75:42
D/io.jxcore.node.ConnectionHelper( 3288): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294] is available
I/jxcore-log( 3288): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:75:41","peerName":"samsung-SM-A300FU_PT1294","peerAvailable":true}]
I/jxcore-log( 3288): 
I/jxcore-log( 3288): startWithNextDevice
I/jxcore-log( 3288): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT1691","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onServiceDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691]
I/io.jxcore.node.ConnectionHelper( 3288): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691], Bluetooth address: B0:C5:59:3F:75:69, device name: , device address: ee:1f:72:18:8b:78
W/io.jxcore.node.ConnectionHelper( 3288): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): setState: RESTARTING
,I/wpa_supplicant(  991): P2P-FIND-STOPPED 
,I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): checkListForExpiredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Removed [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677]
I/io.jxcore.node.ConnectionHelper( 3288): onPeerLost: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677]
D/io.jxcore.node.ConnectionHelper( 3288): hasConnection: No connection with peer with ID 7C:F9:0E:34:8A:A0
D/io.jxcore.node.ConnectionHelper( 3288): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677] removed
D/io.jxcore.node.ConnectionHelper( 3288): notifyPeerAvailability: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677] not available
I/jxcore-log( 3288): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:34:8A:A0","peerName":"samsung-SM-G900F_PT6677","peerAvailable":false}]
I/jxcore-log( 3288): 
I/jxcore-log( 3288): startWithNextDevice
I/jxcore-log( 3288): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): Start timer timeout, starting now...
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): restart: Restarting...
,D/WifiP2pManager( 3288): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): Service request added successfully
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294]
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): Service discovery started successfully
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  991): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT1294","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294]
I/io.jxcore.node.ConnectionHelper( 3288): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper( 3288): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT2896","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896],
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896]
,I/io.jxcore.node.ConnectionHelper( 3288): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 3288): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT7096","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT7096]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT7096]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT7096]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT7096], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT7096]
,I/io.jxcore.node.ConnectionHelper( 3288): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT7096], Bluetooth address: F8:95:C7:87:85:54, device name: , device address: a2:39:f7:70:12:80
,W/io.jxcore.node.ConnectionHelper( 3288): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT7096] already in the list, will not add again
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1864","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
I/io.jxcore.node.ConnectionHelper( 3288): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3288): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864] already in the list, will not add again
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294]
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT7096], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT7096]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294]
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT7096], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT7096]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): restart: Restarting...
,D/WifiP2pManager( 3288): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): Service discovery started successfully
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3591], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3591]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): restart: Restarting...
,D/WifiP2pManager( 3288): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): Service request added successfully
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  991): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3591], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3591]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3591], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3591]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): Service discovery started successfully
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3591], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3591]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT7601","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
I/io.jxcore.node.ConnectionHelper( 3288): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
W/io.jxcore.node.ConnectionHelper( 3288): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT1691","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onServiceDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Adding new peer: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691]
I/io.jxcore.node.ConnectionHelper( 3288): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
W/io.jxcore.node.ConnectionHelper( 3288): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): setState: RESTARTING
,I/wpa_supplicant(  991): P2P-FIND-STOPPED 
,I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): Start timer timeout, starting now...
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  991): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294]
,D/WifiP2pManager( 3288): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): Service request added successfully
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294]
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1864","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
I/io.jxcore.node.ConnectionHelper( 3288): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3288): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT6677","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677]
I/io.jxcore.node.ConnectionHelper( 3288): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
D/io.jxcore.node.ConnectionHelper( 3288): notifyPeerAvailability: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677] is available
I/jxcore-log( 3288): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:34:8A:A0","peerName":"samsung-SM-G900F_PT6677","peerAvailable":true}]
I/jxcore-log( 3288): 
I/jxcore-log( 3288): startWithNextDevice
I/jxcore-log( 3288): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT1294","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294]
I/io.jxcore.node.ConnectionHelper( 3288): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper( 3288): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT7178","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT7178]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT7178]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT7178]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT7178], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT7178]
I/io.jxcore.node.ConnectionHelper( 3288): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT7178], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
D/io.jxcore.node.ConnectionHelper( 3288): notifyPeerAvailability: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT7178] is available
I/jxcore-log( 3288): peerAvailabilityChanged [{"peerIdentifier":"58:3F:54:73:64:C0","peerName":"LGE-LG-D855_PT7178","peerAvailable":true}]
I/jxcore-log( 3288): 
I/jxcore-log( 3288): startWithNextDevice
I/jxcore-log( 3288): 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3591], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3591]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT7178], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT7178]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294], add/update: true,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294]
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294]
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677],
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT2896","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896]
I/io.jxcore.node.ConnectionHelper( 3288): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 3288): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896] already in the list, will not add again
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT7601","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
I/io.jxcore.node.ConnectionHelper( 3288): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601], Bluetooth address: 7C:F9:0E:51:18:22, device name: , device address: 7e:f9:0e:51:18:23
,W/io.jxcore.node.ConnectionHelper( 3288): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601] already in the list, will not add again
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): restart: Restarting...
,D/WifiP2pManager( 3288): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): Service request added successfully
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): Service discovery started successfully
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT7601","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
I/io.jxcore.node.ConnectionHelper( 3288): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601], Bluetooth address: 7C:F9:0E:51:18:22, device name: , device address: 7e:f9:0e:51:18:23
W/io.jxcore.node.ConnectionHelper( 3288): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT2896","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896]
I/io.jxcore.node.ConnectionHelper( 3288): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 3288): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1864","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
I/io.jxcore.node.ConnectionHelper( 3288): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3288): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT6677","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677]
I/io.jxcore.node.ConnectionHelper( 3288): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
W/io.jxcore.node.ConnectionHelper( 3288): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677] already in the list, will not add again
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): checkListForExpiredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Removed [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691]
I/io.jxcore.node.ConnectionHelper( 3288): onPeerLost: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691]
D/io.jxcore.node.ConnectionHelper( 3288): hasConnection: No connection with peer with ID B0:C5:59:3F:75:69
D/io.jxcore.node.ConnectionHelper( 3288): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691] removed
D/io.jxcore.node.ConnectionHelper( 3288): notifyPeerAvailability: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691] not available
I/jxcore-log( 3288): peerAvailabilityChanged [{"peerIdentifier":"B0:C5:59:3F:75:69","peerName":"samsung-SM-G900F_PT1691","peerAvailable":false}]
I/jxcore-log( 3288): 
I/jxcore-log( 3288): startWithNextDevice
I/jxcore-log( 3288): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): setState: RESTARTING
,I/wpa_supplicant(  991): P2P-FIND-STOPPED 
,I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): setState: STARTED
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  991): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 3288): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): Service request added successfully
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): Service discovery started successfully
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1864","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
I/io.jxcore.node.ConnectionHelper( 3288): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3288): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): setState: RESTARTING
,I/wpa_supplicant(  991): P2P-FIND-STOPPED 
,I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): Start timer timeout, starting now...
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): restart: Restarting...
,D/WifiP2pManager( 3288): Ignored { when=-4ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): Service request added successfully
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT1294","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294]
,I/io.jxcore.node.ConnectionHelper( 3288): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper( 3288): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT2896","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896]
I/io.jxcore.node.ConnectionHelper( 3288): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 3288): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896] already in the list, will not add again
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT1691","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onServiceDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Adding new peer: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691]
I/io.jxcore.node.ConnectionHelper( 3288): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691], Bluetooth address: B0:C5:59:3F:75:69, device name: , device address: ee:1f:72:18:8b:78
D/io.jxcore.node.ConnectionHelper( 3288): notifyPeerAvailability: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691] is available
I/jxcore-log( 3288): peerAvailabilityChanged [{"peerIdentifier":"B0:C5:59:3F:75:69","peerName":"samsung-SM-G900F_PT1691","peerAvailable":true}]
I/jxcore-log( 3288): 
I/jxcore-log( 3288): startWithNextDevice
I/jxcore-log( 3288): 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1864","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
I/io.jxcore.node.ConnectionHelper( 3288): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
,W/io.jxcore.node.ConnectionHelper( 3288): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864] already in the list, will not add again
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294]
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294]
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): checkListForExpiredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Removed [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677]
I/io.jxcore.node.ConnectionHelper( 3288): onPeerLost: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677]
D/io.jxcore.node.ConnectionHelper( 3288): hasConnection: No connection with peer with ID 7C:F9:0E:34:8A:A0
D/io.jxcore.node.ConnectionHelper( 3288): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677] removed
D/io.jxcore.node.ConnectionHelper( 3288): notifyPeerAvailability: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677] not available
I/jxcore-log( 3288): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:34:8A:A0","peerName":"samsung-SM-G900F_PT6677","peerAvailable":false}]
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): startWithNextDevice
I/jxcore-log( 3288): 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): restart: Restarting...
,D/WifiP2pManager( 3288): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): Service request added successfully
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): Service discovery started successfully
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT7601","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
I/io.jxcore.node.ConnectionHelper( 3288): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601], Bluetooth address: 7C:F9:0E:51:18:22, device name: , device address: 7e:f9:0e:51:18:23
W/io.jxcore.node.ConnectionHelper( 3288): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601] already in the list, will not add again
,I/UsageStatsService(  759): User[0] Flushing usage stats to disk
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): setState: RESTARTING
,I/wpa_supplicant(  991): P2P-FIND-STOPPED 
,I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): Start timer timeout, starting now...
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  991): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
,D/WifiP2pManager( 3288): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): Service request added successfully
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): Service discovery started successfully
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT7601","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
I/io.jxcore.node.ConnectionHelper( 3288): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
W/io.jxcore.node.ConnectionHelper( 3288): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601] already in the list, will not add again
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): restart: Restarting...
,D/WifiP2pManager( 3288): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): Service discovery started successfully
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT2896","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896]
I/io.jxcore.node.ConnectionHelper( 3288): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 3288): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT7601","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
I/io.jxcore.node.ConnectionHelper( 3288): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
W/io.jxcore.node.ConnectionHelper( 3288): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601] already in the list, will not add again
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1864","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
,I/io.jxcore.node.ConnectionHelper( 3288): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3288): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT1691","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onServiceDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Adding new peer: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691]
I/io.jxcore.node.ConnectionHelper( 3288): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691], Bluetooth address: B0:C5:59:3F:75:69, device name: , device address: ee:1f:72:18:8b:78
W/io.jxcore.node.ConnectionHelper( 3288): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691] already in the list, will not add again
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT7178","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT7178]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT7178]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT7178]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT7178], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT7178]
I/io.jxcore.node.ConnectionHelper( 3288): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT7178], Bluetooth address: 58:3F:54:73:64:C0, device name: , device address: 02:9a:02:7b:60:ac
,W/io.jxcore.node.ConnectionHelper( 3288): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT7178] already in the list, will not add again
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  991): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  991): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT7178], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT7178]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294]
,D/WifiP2pManager( 3288): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): Service request added successfully
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): Service discovery started successfully
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  991): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  991): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT7178","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT7178]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT7178]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT7178]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT7178], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT7178],
I/io.jxcore.node.ConnectionHelper( 3288): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT7178], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper( 3288): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT7178] already in the list, will not add again
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  991): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  991): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 8 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT7178], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT7178]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT7178], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT7178]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT7178], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT7178]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 3288): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): Service discovery started successfully
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT7096","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT7096]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT7096]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT7096]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT7096], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT7096]
I/io.jxcore.node.ConnectionHelper( 3288): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT7096], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 3288): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT7096] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): setState: RESTARTING
,I/wpa_supplicant(  991): P2P-FIND-STOPPED 
,I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): Start timer timeout, starting now...
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  991): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  991): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT7096], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT7096]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT7096], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT7096]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT7096], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT7096]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3288): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): Service request added successfully
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): Service discovery started successfully
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  991): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT7096], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT7096]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT7096], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT7096]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT7601","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
,I/io.jxcore.node.ConnectionHelper( 3288): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
W/io.jxcore.node.ConnectionHelper( 3288): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1864","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
I/io.jxcore.node.ConnectionHelper( 3288): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3288): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864] already in the list, will not add again
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT7096], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT7096]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): restart: Restarting...
,D/WifiP2pManager( 3288): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): Service request added successfully
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): Service discovery started successfully
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): setState: RESTARTING
,I/wpa_supplicant(  991): P2P-FIND-STOPPED 
,I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): Start timer timeout, starting now...
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): restart: Restarting...
,D/WifiP2pManager( 3288): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): Service request added successfully
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): checkListForExpiredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT7178] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT7178], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Removed [58:3F:54:73:64:C0 LGE-LG-D855_PT7178]
I/io.jxcore.node.ConnectionHelper( 3288): onPeerLost: [58:3F:54:73:64:C0 LGE-LG-D855_PT7178]
D/io.jxcore.node.ConnectionHelper( 3288): hasConnection: No connection with peer with ID 58:3F:54:73:64:C0
D/io.jxcore.node.ConnectionHelper( 3288): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT7178] removed
D/io.jxcore.node.ConnectionHelper( 3288): notifyPeerAvailability: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT7178] not available
I/jxcore-log( 3288): peerAvailabilityChanged [{"peerIdentifier":"58:3F:54:73:64:C0","peerName":"LGE-LG-D855_PT7178","peerAvailable":false}]
I/jxcore-log( 3288): 
I/jxcore-log( 3288): startWithNextDevice
I/jxcore-log( 3288): 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  991): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  991): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): Service discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 5 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT3591","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3591]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onServiceDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3591]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3591]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3591], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Adding new peer: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3591]
I/io.jxcore.node.ConnectionHelper( 3288): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3591], Bluetooth address: E0:DB:10:14:E2:C0, device name: Note4-1, device address: 92:b6:86:43:73:1c
W/io.jxcore.node.ConnectionHelper( 3288): modifyListOfDiscoveredPeers: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3591] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1864","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
I/io.jxcore.node.ConnectionHelper( 3288): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3288): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT1691","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onServiceDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Adding new peer: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691]
I/io.jxcore.node.ConnectionHelper( 3288): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
W/io.jxcore.node.ConnectionHelper( 3288): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT7178","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT7178]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT7178]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT7178]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT7178], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT7178]
I/io.jxcore.node.ConnectionHelper( 3288): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT7178], Bluetooth address: 58:3F:54:73:64:C0, device name: , device address: 02:9a:02:7b:60:ac
D/io.jxcore.node.ConnectionHelper( 3288): notifyPeerAvailability: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT7178] is available
,I/jxcore-log( 3288): peerAvailabilityChanged [{"peerIdentifier":"58:3F:54:73:64:C0","peerName":"LGE-LG-D855_PT7178","peerAvailable":true}]
I/jxcore-log( 3288): 
I/jxcore-log( 3288): startWithNextDevice
I/jxcore-log( 3288): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT7601","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
I/io.jxcore.node.ConnectionHelper( 3288): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
W/io.jxcore.node.ConnectionHelper( 3288): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601] already in the list, will not add again
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3591], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3591]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1691]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT6677","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677]
I/io.jxcore.node.ConnectionHelper( 3288): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
D/io.jxcore.node.ConnectionHelper( 3288): notifyPeerAvailability: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677] is available
I/jxcore-log( 3288): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:34:8A:A0","peerName":"samsung-SM-G900F_PT6677","peerAvailable":true}]
I/jxcore-log( 3288): 
I/jxcore-log( 3288): startWithNextDevice
I/jxcore-log( 3288): 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): restart: Restarting...
,D/WifiP2pManager( 3288): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): Service request added successfully
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): Service discovery started successfully
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 6 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT1294","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294]
I/io.jxcore.node.ConnectionHelper( 3288): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294], Bluetooth address: 08:EC:A9:50:75:41, device name: , device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper( 3288): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): setState: RESTARTING
,I/wpa_supplicant(  991): P2P-FIND-STOPPED 
,I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): Start timer timeout, starting now...
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  991): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
,D/WifiP2pManager( 3288): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): Service request added successfully
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): Service discovery started successfully
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT2896","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896]
I/io.jxcore.node.ConnectionHelper( 3288): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 3288): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1864","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
I/io.jxcore.node.ConnectionHelper( 3288): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
,W/io.jxcore.node.ConnectionHelper( 3288): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864] already in the list, will not add again
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT7178","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT7178]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT7178]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT7178]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT7178], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT7178]
I/io.jxcore.node.ConnectionHelper( 3288): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT7178], Bluetooth address: 58:3F:54:73:64:C0, device name: , device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper( 3288): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT7178] already in the list, will not add again
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT7178], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT7178]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): restart: Restarting...
,D/WifiP2pManager( 3288): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): Service request added successfully
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): Service discovery started successfully
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
,I/jxcore-log( 3288): timeout now
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): weAreDoneNow, resultArray.length: 10
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): sendReportNow
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): done, now sending data to server
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T18:56:46.234Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3288): 
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): checkListForExpiredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294] expired
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): checkListForExpiredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601] expired
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): checkListForExpiredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Removed [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Removed [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Removed [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677]
I/io.jxcore.node.ConnectionHelper( 3288): onPeerLost: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294]
D/io.jxcore.node.ConnectionHelper( 3288): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 3288): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294] removed
D/io.jxcore.node.ConnectionHelper( 3288): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294] not available
I/jxcore-log( 3288): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:75:41","peerName":"samsung-SM-A300FU_PT1294","peerAvailable":false}]
I/jxcore-log( 3288): 
I/jxcore-log( 3288): startWithNextDevice
I/jxcore-log( 3288): 
I/io.jxcore.node.ConnectionHelper( 3288): onPeerLost: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
D/io.jxcore.node.ConnectionHelper( 3288): hasConnection: No connection with peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 3288): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601] removed
D/io.jxcore.node.ConnectionHelper( 3288): notifyPeerAvailability: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601] not available
I/jxcore-log( 3288): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:51:18:22","peerName":"samsung-SM-A500FU_PT7601","peerAvailable":false}]
I/jxcore-log( 3288): 
I/jxcore-log( 3288): startWithNextDevice
I/jxcore-log( 3288): 
I/io.jxcore.node.ConnectionHelper( 3288): onPeerLost: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677]
D/io.jxcore.node.ConnectionHelper( 3288): hasConnection: No connection with peer with ID 7C:F9:0E:34:8A:A0
D/io.jxcore.node.ConnectionHelper( 3288): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677] removed
D/io.jxcore.node.ConnectionHelper( 3288): notifyPeerAvailability: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677] not available
,I/jxcore-log( 3288): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:34:8A:A0","peerName":"samsung-SM-G900F_PT6677","peerAvailable":false}]
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): startWithNextDevice
I/jxcore-log( 3288): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): setState: RESTARTING
,I/wpa_supplicant(  991): P2P-FIND-STOPPED 
,I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): Start timer timeout, starting now...
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
,D/WifiP2pManager( 3288): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): Service request added successfully
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): Service discovery started successfully
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT6677","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677]
I/io.jxcore.node.ConnectionHelper( 3288): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
D/io.jxcore.node.ConnectionHelper( 3288): notifyPeerAvailability: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677] is available
,I/jxcore-log( 3288): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:34:8A:A0","peerName":"samsung-SM-G900F_PT6677","peerAvailable":true}]
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): startWithNextDevice
I/jxcore-log( 3288): 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT7601","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
I/io.jxcore.node.ConnectionHelper( 3288): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
D/io.jxcore.node.ConnectionHelper( 3288): notifyPeerAvailability: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601] is available
I/jxcore-log( 3288): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:51:18:22","peerName":"samsung-SM-A500FU_PT7601","peerAvailable":true}]
I/jxcore-log( 3288): 
I/jxcore-log( 3288): startWithNextDevice
I/jxcore-log( 3288): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT7178","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT7178]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT7178]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT7178]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT7178], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT7178]
,I/io.jxcore.node.ConnectionHelper( 3288): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT7178], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper( 3288): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT7178] already in the list, will not add again
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6677]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT7178], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT7178]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT7178], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT7178]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): restart: Restarting...
,D/WifiP2pManager( 3288): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): Service request added successfully
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 6 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): Service discovery started successfully
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT1294","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294]
I/io.jxcore.node.ConnectionHelper( 3288): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294], Bluetooth address: 08:EC:A9:50:75:41, device name: , device address: 0a:ec:a9:50:75:42
D/io.jxcore.node.ConnectionHelper( 3288): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294] is available
I/jxcore-log( 3288): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:75:41","peerName":"samsung-SM-A300FU_PT1294","peerAvailable":true}]
I/jxcore-log( 3288): 
I/jxcore-log( 3288): startWithNextDevice
I/jxcore-log( 3288): 
,W/bt-smp  ( 2142): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2142): Plain text(LSB ~ MSB) = 32 51 53 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2142): Encrypted text(LSB ~ MSB) = fc 6f 12 a0 69 9f 27 78 17 c8 91 ee 24 47 df b4 
,W/bt-btm  ( 2142): Stopping oneshot timer
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): setState: RESTARTING
,I/wpa_supplicant(  991): P2P-FIND-STOPPED 
,I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): Start timer timeout, starting now...
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  991): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 2 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 3288): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): Service request added successfully
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  991): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 4 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1294]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): Service discovery started successfully
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  991): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1864","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
I/io.jxcore.node.ConnectionHelper( 3288): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3288): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864] already ,in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT7096","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT7096]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT7096]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT7096]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT7096], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT7096]
,I/io.jxcore.node.ConnectionHelper( 3288): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT7096], Bluetooth address: F8:95:C7:87:85:54, device name: , device address: a2:39:f7:70:12:80
,W/io.jxcore.node.ConnectionHelper( 3288): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT7096] already in the list, will not add again
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): checkListForExpiredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Removed [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
I/io.jxcore.node.ConnectionHelper( 3288): onPeerLost: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601]
D/io.jxcore.node.ConnectionHelper( 3288): hasConnection: No connection with peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 3288): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601] removed
D/io.jxcore.node.ConnectionHelper( 3288): notifyPeerAvailability: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7601] not available
I/jxcore-log( 3288): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:51:18:22","peerName":"samsung-SM-A500FU_PT7601","peerAvailable":false}]
I/jxcore-log( 3288): 
I/jxcore-log( 3288): startWithNextDevice
I/jxcore-log( 3288): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): Got discovery timeout, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): setState: RESTARTING
,I/wpa_supplicant(  991): P2P-FIND-STOPPED 
,I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): Start timer timeout, starting now...
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): restart: Restarting...
,D/WifiP2pManager( 3288): Ignored { when=-3ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): Service request added successfully
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  991): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT7096], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT7096]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT7096], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT7096]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): Service discovery started successfully
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  991): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT7096], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT7096]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT7096], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT7096]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT7178","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT7178]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT7178]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT7178]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT7178], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT7178]
I/io.jxcore.node.ConnectionHelper( 3288): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT7178], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper( 3288): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT7178] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): setState: RESTARTING
,I/wpa_supplicant(  991): P2P-FIND-STOPPED 
,I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): Start timer timeout, starting now...
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT7178], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT7178]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): restart: Restarting...
,D/WifiP2pManager( 3288): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): Service request added successfully
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT7178], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT7178]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): Service discovery started successfully
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  991): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT2896","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896]
I/io.jxcore.node.ConnectionHelper( 3288): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 3288): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2896] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): setState: RESTARTING
,I/wpa_supplicant(  991): P2P-FIND-STOPPED 
,I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): checkListForExpiredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT7096] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT7096], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Removed [F8:95:C7:87:85:54 LGE-LG-D722_PT7096]
I/io.jxcore.node.ConnectionHelper( 3288): onPeerLost: [F8:95:C7:87:85:54 LGE-LG-D722_PT7096]
,D/io.jxcore.node.ConnectionHelper( 3288): hasConnection: No connection with peer with ID F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 3288): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT7096] removed
D/io.jxcore.node.ConnectionHelper( 3288): notifyPeerAvailability: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT7096] not available
,I/jxcore-log( 3288): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:85:54","peerName":"LGE-LG-D722_PT7096","peerAvailable":false}]
I/jxcore-log( 3288): 
I/jxcore-log( 3288): startWithNextDevice
I/jxcore-log( 3288): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): Start timer timeout, starting now...
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onP2pDeviceListChanged: Peer 1: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): restart: Restarting...
,D/WifiP2pManager( 3288): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): Service request added successfully
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): Service discovery started successfully
,I/wpa_supplicant(  991): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3288): teardown
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): testSendData stopped
I/jxcore-log( 3288): 
I/io.jxcore.node.ConnectionHelper( 3288): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3288): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3288): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3288): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3288): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3288): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3288): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3288): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3288): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3288): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): stop: Stopping P2P device discovery...
,I/wpa_supplicant(  991): P2P-FIND-STOPPED 
I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3288): release: No more listeners, de-initializing...
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3288): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3288): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3288): setState: NOT_STARTED
I/jxcore-log( 3288): StopBroadcasting went ok
I/jxcore-log( 3288): 
,I/jxcore-log( 3288): 2015-12-18T19:00:05.930Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
I/jxcore-log( 3288): 
I/chromium( 3288): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/io.jxcore.node.ConnectionHelper( 3288): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3288): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3288): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3288): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 3288): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 3288): --- start :testReConnect.js---
I/jxcore-log( 3288): 
,I/chromium( 3288): [INFO:CONSOLE(63)] "logCallback --- start :testReConnect.js---", source: file:///android_asset/www/js/thali_main.js (63)
,I/wpa_supplicant(  991): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  991): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
,D/HeadsetStateMachine( 2142): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 2142): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 2142): Disconnected process message: 11, size: 0
,I/ActivityManager(  759): Killing 3049:com.android.defcontainer/u0a5 (adj 13): empty for 1806s
,I/ActivityManager(  759): Killing 3208:com.google.android.apps.docs/u0a40 (adj 13): empty for 1808s
,I/ActivityManager(  759): Killing 3177:com.android.musicfx/u0a15 (adj 13): empty for 1809s
,I/ActivityManager(  759): Killing 1443:com.google.android.partnersetup/u0a13 (adj 13): empty for 1809s
,I/ActivityManager(  759): Killing 2916:android.process.acore/u0a4 (adj 15): empty for 1809s
,I/ActivityManager(  759): Killing 2838:com.android.providers.calendar/u0a2 (adj 15): empty for 1814s
,I/ActivityManager(  759): Killing 3072:com.google.android.gms:car/u0a8 (adj 15): empty for 1814s
,I/ProcessStatsService(  759): Prepared write state in 4ms
,W/libprocessgroup(  759): failed to open /acct/uid_10004/pid_2916/cgroup.procs: No such file or directory
,W/libprocessgroup(  759): failed to open /acct/uid_10015/pid_3177/cgroup.procs: No such file or directory
,W/libprocessgroup(  759): failed to open /acct/uid_10013/pid_1443/cgroup.procs: No such file or directory
,W/libprocessgroup(  759): failed to open /acct/uid_10002/pid_2838/cgroup.procs: No such file or directory
,W/libprocessgroup(  759): failed to open /acct/uid_10008/pid_3072/cgroup.procs: No such file or directory
,W/libprocessgroup(  759): failed to open /acct/uid_10040/pid_3208/cgroup.procs: No such file or directory
,W/libprocessgroup(  759): failed to open /acct/uid_10005/pid_3049/cgroup.procs: No such file or directory
,V/GLSActivity( 1553): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1553): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ProcessStatsService(  759): Pruning old procstats: /data/system/procstats/state-2015-12-18-00-38-51.bin
,TIME-OUT KILL (timeout was 1800000ms)
```
