#### Test 50650278bcecc5c_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
I/GAv4    ( 3164): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3164):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3164):   adb logcat -s GAv4
W/GAv4    ( 3164): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3164): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3164): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 3164): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
,D/Finsky  ( 2663): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
I/ActivityManager(  750): Killing 2071:com.google.android.deskclock/u0a38 (adj 15): empty #17
W/ResourcesManager( 3164): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3164): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/AndroidRuntime( 3208): 
D/AndroidRuntime( 3208): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3208): CheckJNI is OFF
W/libprocessgroup(  750): failed to open /acct/uid_10038/pid_2071/cgroup.procs: No such file or directory
V/JNIHelp ( 3164): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/System  ( 3164): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3164): Installed default security provider GmsCore_OpenSSL
V/GLSActivity( 1601): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/AndroidRuntime( 3208): Calling main entry com.android.commands.am.Am
I/ActivityManager(  750): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  750): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3244 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3208): Shutting down VM
I/art     (  194): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 372us total 16.327ms
I/art     (  194): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 168us total 9.966ms
I/Icing   ( 1628): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/art     (  194): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 170us total 7.422ms
V/ActivityManager(  750): Display changed displayId=0
I/Icing   ( 1628): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1628): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/WebViewFactory( 3244): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3244): Time to load native libraries: 2 ms (timestamps 8254-8256)
I/LibraryLoader( 3244): Expected native library version number "",actual native library version number ""
I/Icing   ( 1628): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
V/WebViewChromiumFactoryProvider( 3244): Binding Chromium to main looper Looper (main, tid 1) {2517e1d}
I/LibraryLoader( 3244): Expected native library version number "",actual native library version number ""
,I/chromium( 3244): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3244): Initializing chromium process, singleProcess=true
W/art     ( 3244): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3244): ApplicationContext is null in ApplicationStatus
W/chromium( 3244): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3244): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3244): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3244): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
D/BluetoothManagerService(  750): Message: 20
D/BluetoothManagerService(  750): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1d9c92da:true
W/art     ( 3244): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 3244): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 3244): CordovaWebView is running on device made by: LGE
W/art     ( 3244): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3244): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 3244): Render dirty regions requested: true
D/Atlas   ( 3244): Validating map...
W/chromium( 3244): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/OpenGLRenderer( 3244): Initialized EGL, version 1.4
D/OpenGLRenderer( 3244): Enabling debug mode 0
I/Keyboard.Facilitator( 1084): onFinishInput()
W/BindingManager( 3244): Cannot call determinedVisibility() - never saw a connection for the pid: 3244
W/IInputConnectionWrapper( 3244): showStatusIcon on inactive InputConnection
I/ActivityManager(  750): Displayed com.test.thalitest/.MainActivity: +466ms (total +57s876ms)
D/JsMessageQueue( 3244): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 3244): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257332480
D/JX-Cordova( 3244): jxcore cordova android initializing
I/ActivityManager(  750): Killing 2619:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
W/libprocessgroup(  750): failed to open /acct/uid_10069/pid_2619/cgroup.procs: No such file or directory
,W/jxcore-log( 3244): Initializing JXcore engine
W/jxcore-log( 3244): JXcore engine is ready
,W/jxcore-log( 3244): Starting JXcore engine
,W/.test.thalitest( 3244): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[9471]" dev="sockfs" ino=9471 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3244): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 3244): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8640]" dev="sockfs" ino=8640 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3244): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[17393]" dev="sockfs" ino=17393 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3244): Platform android
W/jxcore-log( 3244): 
,W/jxcore-log( 3244): Process ARCH arm
W/jxcore-log( 3244): 
,I/jxcore-log( 3244): JXcore Cordova bridge is ready!
I/jxcore-log( 3244): 
W/jxcore-log( 3244): JXcore engine is started
,I/chromium( 3244): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3244): Toggling radios to true
I/jxcore-log( 3244): 
,D/BluetoothAdapter( 3244): enable(): BT is already enabled..!
,D/WifiService(  750): New client listening to asynchronous messages
,D/WifiService(  750): setWifiEnabled: true pid=3244, uid=10270
E/WifiService(  750): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3244): Radios toggled
I/jxcore-log( 3244): 
,D/BluetoothManagerService(  750): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 3244): Got Device Bluetooth address: 34:FC:EF:11:AE:67
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): Perf Test app loaded loaded
I/jxcore-log( 3244): 
I/wpa_supplicant(  984): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
I/jxcore-log( 3244): check test folder
I/jxcore-log( 3244): 
,E/WifiStateMachine(  750): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  750): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,I/jxcore-log( 3244): found test : ./testFindPeers.js
I/jxcore-log( 3244): 
E/native  (  750): do suspend true
,D/CommandListener(  178): Clearing all IP addresses on wlan0
I/jxcore-log( 3244): found test : ./testSendData.js
I/jxcore-log( 3244): 
,V/NativeCrypto( 1601): Read error: ssl=0xb3f35e00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1601): SSL shutdown failed: ssl=0xb3f35e00: I/O error during system call, Broken pipe
,D/ConnectivityService(  750): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  750): ValidatedState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  750): DefaultState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  750): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  750): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  750): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  750): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,E/WifiConfigStore(  750): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  750): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  750): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,E/WifiStateMachine(  750): Start Disconnecting Watchdog 1
,E/native  (  750): do suspend true
,I/wpa_supplicant(  984): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/CommandListener(  178): Clearing all IP addresses on wlan0
,D/ConnectivityService(  750): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/Nat464Xlat(  750): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  750): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  750): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  750): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler(  896): CM callback handler got msg 524292
D/ConnectivityService(  750): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory( 1250): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  750): EvaluatingState{ when=-7ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  750): DefaultState{ when=-7ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  750): Disconnected - quitting
D/ConnectivityManager.CallbackHandler( 1628): CM callback handler got msg 524292
,I/chromium( 3244): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/WifiNetworkAgent(  750): NetworkAgent: NetworkAgent channel lost
,I/wpa_supplicant(  984): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant(  984): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant(  984): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant(  984): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  750): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  750): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  750): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  750): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  178): Setting iface cfg
,E/WifiStateMachine(  750): Start Dhcp Watchdog 2
,E/native  (  750): do suspend false
,E/WifiStateMachine(  750): scanCount==0 - aborting
,I/dhcpcd  ( 3354): version 5.5.6 starting
,E/dhcpcd  ( 3354): get_duid: Read-only file system
,I/dhcpcd  ( 3354): wlan0: rebinding lease of 192.168.1.114
,I/dhcpcd  ( 3354): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3354): wlan0: leased 192.168.1.114 for 86400 seconds
,D/ConnectivityService(  750): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  750): MasterInitialState.processMessage what=3
,D/ConnectivityService(  750): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  750): MasterInitialState.processMessage what=3
,V/MusicLeanback( 2768): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1628): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1628): onCreate
D/SystemUpdateService( 1628): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1628): active receiver: enabled
,I/SystemUpdateService( 1628): showing system update notification
,I/iu.Environment( 1628): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1628): num queued entries: 0
I/iu.UploadsManager( 1628): num updated entries: 0
,I/iu.SyncManager( 1628): NEXT; no task
,I/ValidateNoPeople(  750): skipping global notification
,V/SystemUpdateService( 1628): retry (wakeup: false) in 3599982 ms
I/Babel   ( 1928): connection state changed from CONNECTED to DISCONNECTED
,I/ActivityManager(  750): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3404 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/SystemUpdateService( 1628): onDestroy
,E/GpsLocationProvider(  750): No APN found to select.
,E/GpsLocationProvider(  750): No APN found to select.
,E/native  (  750): do suspend true
,D/ConnectivityService(  750): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  750): Adding iface wlan0 to network 101
,E/WifiStateMachine(  750): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  750): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  750): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  750): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  750): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/ConnectivityService(  750): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  750): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  750): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  750): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  750): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  750):    accepting network in place of null
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  750): DefaultState{ when=-3ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  750): Connected
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  750): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  750): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/CSLegacyTypeTracker(  750): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,D/ConnectivityService(  750): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  750): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.114/24,fe80::5255:27ff:fef0:fd0b/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  750): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler(  896): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1628): CM callback handler got msg 524290
,I/GAv4    ( 3404): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3404):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3404):   adb logcat -s GAv4
,W/GAv4    ( 3404): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  750): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 18 Dec 2015 17:52:15 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450461135063], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450461135044]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  750): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  750): Validated
D/ConnectivityService(  750): Validated NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  750): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  750): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  750): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  896): CM callback handler got msg 524290
,D/ConnectivityService(  750): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/TelephonyNetworkFactory( 1250): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 1628): CM callback handler got msg 524290
,W/GAv4    ( 3404): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3404): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 3404): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3404): Time to load native libraries: 2 ms (timestamps 5383-5385)
,I/LibraryLoader( 3404): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3404): Binding Chromium to main looper Looper (main, tid 1) {34cfac87}
,I/LibraryLoader( 3404): Expected native library version number "",actual native library version number ""
,I/chromium( 3404): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3404): Initializing chromium process, singleProcess=true
,W/art     ( 3404): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3404): ApplicationContext is null in ApplicationStatus
,W/chromium( 3404): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3404): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3404): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3404): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/AudioManagerAndroid( 3404): Requires BLUETOOTH permission
,I/NSApplication( 3404): Starting up...
,I/ActivityManager(  750): Killing 2557:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,W/libprocessgroup(  750): failed to open /acct/uid_10045/pid_2557/cgroup.procs: No such file or directory
,V/MusicLeanback( 2768): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1628): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1628): onCreate
,D/SystemUpdateService( 1628): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1628): active receiver: enabled
,I/iu.Environment( 1628): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/SystemUpdateService( 1628): showing system update notification
,I/iu.UploadsManager( 1628): num queued entries: 0
I/iu.UploadsManager( 1628): num updated entries: 0
,I/iu.SyncManager( 1628): NEXT; no task
,I/ValidateNoPeople(  750): skipping global notification
,V/SystemUpdateService( 1628): retry (wakeup: false) in 3599961 ms
,D/SystemUpdateService( 1628): onDestroy
,I/Babel   ( 1928): connection state changed from DISCONNECTED to CONNECTED
,D/ConnectivityService(  750): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): setDiscoveryMode: Mode set to WIFI
,I/jxcore-log( 3244): BLE supported!!
I/jxcore-log( 3244): 
,D/ConnectivityService(  750): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  750): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2768): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2768): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1628): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1628): onCreate
,D/SystemUpdateService( 1628): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1628): active receiver: enabled
,I/SystemUpdateService( 1628): showing system update notification
,I/ValidateNoPeople(  750): skipping global notification
,V/SystemUpdateService( 1628): retry (wakeup: false) in 3599969 ms
,D/SystemUpdateService( 1628): onDestroy
,E/GpsLocationProvider(  750): No APN found to select.
,D/Finsky  ( 2663): [255] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2663): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/VacuumService( 1601): Vacuum at: now=1450461152414 tag=VacuumService
,I/art     (  750): Explicit concurrent mark sweep GC freed 46535(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 27MB/41MB, paused 1.102ms total 74.270ms
,V/GLSActivity( 1601): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Keyboard.Facilitator.LanguageModelFlusher( 1084): run()
I/Keyboard.Facilitator( 1084): flushDynamicLanguageModels()
,I/ClearcutLoggerApiImpl( 1601): disconnect managed GoogleApiClient
,I/PhenotypeConfigurator( 1601): Scheduling Phenotype for one-off execution 10471 seconds from now (1450461249598)
,D/GetConfigurationSnapshotOperation( 1601): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1601): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1601): Using platform SSLCertificateSocketFactory
,V/GLSActivity( 1601): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1601): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 3244): Connected to the server!
I/jxcore-log( 3244): 
,I/chromium( 3244): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3244): --- start :testSendData.js---
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): testSendData created {"name":"testSendData.js","serverTimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":15}bt-address length : 0
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): daya100000
I/jxcore-log( 3244): 
I/jxcore-log( 3244): check server
I/jxcore-log( 3244): 
I/jxcore-log( 3244): serverPort is 32844
I/jxcore-log( 3244): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService(  750): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3244): start: Peer ID: 34:FC:EF:11:AE:67, peer name: LGE-Nexus 5_PT5924
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3244): bind: Binding a new listener
,D/BluetoothManagerService(  750): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3244): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  750): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3244): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5924","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3244): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3244): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3244): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  750): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3244): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3244): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3244): start: OK
I/io.jxcore.node.ConnectionHelper( 3244): start: Using peer discovery mode: WIFI
,D/BluetoothManagerService(  750): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): start: Peer ID: 34:FC:EF:11:AE:67, peer name: LGE-Nexus 5_PT5924
,D/BluetoothManagerService(  750): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3244): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5924","ra":"34:FC:EF:11:AE:67"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3244): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5924","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3244): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5924","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3244): start: OK
I/jxcore-log( 3244): StartBroadcasting started ok
I/jxcore-log( 3244): 
I/jxcore-log( 3244): null
I/jxcore-log( 3244): 
I/jxcore-log( 3244): 2015-12-18T17:58:22.244Z SendDataTCPServer.js: TCP/IP server is bound to port: 32844
I/jxcore-log( 3244): 
I/chromium( 3244): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
I/io.jxcore.node.ConnectionHelper( 3244): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3244): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3244): onDiscoveryManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3244): Waiting for incoming connections...
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3244): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service request added successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT8506","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT8506]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onServiceDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT8506]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT8506]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT8506], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT8506]
,I/io.jxcore.node.ConnectionHelper( 3244): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT8506], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
D/io.jxcore.node.ConnectionHelper( 3244): notifyPeerAvailability: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT8506] is available
I/jxcore-log( 3244): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:76:27","peerName":"samsung-SM-A300FU_PT8506","peerAvailable":true}]
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): Found peer : samsung-SM-A300FU_PT8506, Available: true
I/jxcore-log( 3244): 
I/jxcore-log( 3244): startWithNextDevice
I/jxcore-log( 3244): 
I/jxcore-log( 3244): device[1]: 08:EC:A9:50:76:27
I/jxcore-log( 3244): 
I/jxcore-log( 3244): 2015-12-18T17:58:29.083Z SendDataConnector.js: Start called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3244): 
I/jxcore-log( 3244): 2015-12-18T17:58:29.085Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T17:58:29.085Z SendDataConnector.js: do connect now
I/jxcore-log( 3244): 
I/io.jxcore.node.ConnectionHelper( 3244): connect: Trying to connect to peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 3244): hasConnection: No connection with peer with ID 08:EC:A9:50:76:27
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3244): connect: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT8506]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3244): connect: Trying to start connecting to null in address 08:EC:A9:50:76:27
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3244): onConnecting: null 08:EC:A9:50:76:27
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3244): connect: Started connecting to null in address 08:EC:A9:50:76:27
I/io.jxcore.node.ConnectionHelper( 3244): connect: Connection process successfully started (peer ID: 08:EC:A9:50:76:27)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): Trying to connect to peer with address 08:EC:A9:50:76:27 (thread ID: 298)
W/BluetoothAdapter( 3244): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2094): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2094): info:x10
,D/        ( 2094): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2094): aclStateChangeCallback: Device is NULL
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT8213","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
I/io.jxcore.node.ConnectionHelper( 3244): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213], Bluetooth address: F8:95:C7:87:85:54, device name: , device address: a2:39:f7:70:12:80
D/io.jxcore.node.ConnectionHelper( 3244): notifyPeerAvailability: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8213] is available
,I/jxcore-log( 3244): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:85:54","peerName":"LGE-LG-D722_PT8213","peerAvailable":true}]
I/jxcore-log( 3244): 
I/jxcore-log( 3244): Found peer : LGE-LG-D722_PT8213, Available: true
I/jxcore-log( 3244): 
,W/bt-sdp  ( 2094): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2094): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:76:27 newState: 1
E/bt-btif ( 2094): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2094): Bond State Change Intent:08:EC:A9:50:76:27 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2094): Entering PendingCommandState State
,W/BluetoothEventManager( 2726): CachedBluetoothDevice for device 08:EC:A9:50:76:27 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2726): Got bonding state changed for 08:EC:A9:50:76:27, but we have no record of that device.
,I/BluetoothBondStateMachine( 2094): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:76:27 newState: 0
,D/BluetoothAdapterProperties( 2094): Failed to remove device: 08:EC:A9:50:76:27
,I/BluetoothBondStateMachine( 2094): Bond State Change Intent:08:EC:A9:50:76:27 OldState: 11 NewState: 10
,W/BluetoothEventManager( 2726): CachedBluetoothDevice for device 08:EC:A9:50:76:27 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2726): Got bonding state changed for 08:EC:A9:50:76:27, but we have no record of that device.
,I/BluetoothBondStateMachine( 2094): StableState(): Entering Off State
,W/bt-btif ( 2094): new conn_srvc id:26, app_id:1
W/bt-btif ( 2094): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2094): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3244): onSocketConnected: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT8506]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 298)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): onBytesWritten: 77 bytes successfully written (thread ID: 299)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): Outgoing connection initialized (*handshake* thread ID: 299)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): Exiting thread (thread ID: 298)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3244): Entering thread (ID: 299)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): onBytesRead: Read 83 bytes successfully (thread ID: 299)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): Handshake succeeded with [08:EC:A9:50:76:27 samsung-SM-A300FU_PT8506]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3244): onHandshakeSucceeded: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT8506]
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3244): Exiting thread (ID: 299)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3244): onConnected: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT8506]
,I/io.jxcore.node.ConnectionHelper( 3244): onConnected: Outgoing connection to peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT8506]
D/io.jxcore.node.ConnectionHelper( 3244): hasConnection: No connection with peer with ID 08:EC:A9:50:76:27
W/io.jxcore.node.ConnectionHelper( 3244): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT8506] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 3244): onConnected: Outgoing socket thread, for peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT8506], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3244): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 3244): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 3244): Entering thread (ID: 300)
,D/io.jxcore.node.OutgoingSocketThread( 3244): Server socket local port: 40781
I/io.jxcore.node.OutgoingSocketThread( 3244): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3244): onListeningForIncomingConnections: Outgoing connection is using port 40781 (peer ID: 08:EC:A9:50:76:27)
I/jxcore-log( 3244): 2015-12-18T17:58:32.081Z SendDataConnector.js: CLIENT connected to 40781, error: null
I/jxcore-log( 3244): 
I/jxcore-log( 3244): 2015-12-18T17:58:32.081Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3244): 
,I/io.jxcore.node.OutgoingSocketThread( 3244): Incoming data from address: /127.0.0.1, port: 40781
D/io.jxcore.node.OutgoingSocketThread( 3244): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3244): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3244): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3244): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3244): Exiting thread (ID: 300)
,D/io.jxcore.node.StreamCopyingThread( 3244): Entering thread (ID: 302, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3244): Entering thread (ID: 301, name: Sender)
,I/jxcore-log( 3244): 2015-12-18T17:58:32.152Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3244): 
,D/        ( 2094): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23716
,I/jxcore-log( 3244): 2015-12-18T17:58:32.804Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T17:58:32.965Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3244): 
,D/        ( 2094): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:12826
,I/jxcore-log( 3244): 2015-12-18T17:58:33.013Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3244): 
,D/        ( 2094): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:5896
,I/jxcore-log( 3244): 2015-12-18T17:58:33.043Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T17:58:33.087Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T17:58:33.094Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T17:58:33.194Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T17:58:33.270Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T17:58:33.290Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T17:58:33.547Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3244): 
I/jxcore-log( 3244): 2015-12-18T17:58:33.548Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3244): 
I/jxcore-log( 3244): oneRoundDownNow
I/jxcore-log( 3244): 
I/jxcore-log( 3244): 2015-12-18T17:58:33.552Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3244): 
I/jxcore-log( 3244): 2015-12-18T17:58:33.553Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3244): 
,D/io.jxcore.node.ConnectionHelper( 3244): disconnectOutgoingConnection: Trying to close connection to peer with ID 08:EC:A9:50:76:27
I/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 08:EC:A9:50:76:27
I/io.jxcore.node.OutgoingSocketThread( 3244): close
D/io.jxcore.node.OutgoingSocketThread( 3244): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3244): doStop: Thread ID: 302
D/io.jxcore.node.OutgoingSocketThread( 3244): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3244): doStop: Thread ID: 301
D/io.jxcore.node.OutgoingSocketThread( 3244): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 3244): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3244): Either failed to read from the output stream or write to the input stream (thread ID: 301, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3244): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3244): onDisconnected: Outgoing connection, peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT8506] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 3244): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 3244): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3244): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3244): Either failed to read from the output stream or write to the input stream (thread ID: 302, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.OutgoingSocketThread( 3244): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3244): onDisconnected: Outgoing connection, peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT8506] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3244): disconnectOutgoingConnection: Successfully disconnected (peer ID: 08:EC:A9:50:76:27
,E/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3244): Exiting thread (ID: 301, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3244): Exiting thread (ID: 302, name: Receiver)
,I/jxcore-log( 3244): 2015-12-18T17:58:33.592Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): ---- round done--------
I/jxcore-log( 3244): 
I/jxcore-log( 3244): startWithNextDevice
I/jxcore-log( 3244): 
I/jxcore-log( 3244): device[2]: F8:95:C7:87:85:54
I/jxcore-log( 3244): 
I/jxcore-log( 3244): 2015-12-18T17:58:33.593Z SendDataConnector.js: Start called with peer F8:95:C7:87:85:54
I/jxcore-log( 3244): 
I/jxcore-log( 3244): 2015-12-18T17:58:33.594Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3244): 
W/bt-btif ( 2094): bta_jv_rfc_port_to_cb(port_handle:0x8):jv handle:0x0 not FOUND
,I/jxcore-log( 3244): 2015-12-18T17:58:33.594Z SendDataConnector.js: do connect now
I/jxcore-log( 3244): 
I/io.jxcore.node.ConnectionHelper( 3244): connect: Trying to connect to peer with ID F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 3244): hasConnection: No connection with peer with ID F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3244): connect: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3244): connect: Trying to start connecting to null in address F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3244): onConnecting: null F8:95:C7:87:85:54
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3244): connect: Started connecting to null in address F8:95:C7:87:85:54
I/io.jxcore.node.ConnectionHelper( 3244): connect: Connection process successfully started (peer ID: F8:95:C7:87:85:54)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): Trying to connect to peer with address F8:95:C7:87:85:54 (thread ID: 303)
W/BluetoothAdapter( 3244): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2094): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2094): tBTM_SEC_DEV:0xa3e50ebc rs_disc_pending=1
,W/bt-btif ( 2094): bta_dm_check_av:0
W/bt-btif ( 2094): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2094): info:x10
,D/        ( 2094): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,E/BluetoothRemoteDevices( 2094): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2094): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2094): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1
E/bt-btif ( 2094): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2094): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 2094): Entering PendingCommandState State
,W/BluetoothEventManager( 2726): CachedBluetoothDevice for device F8:95:C7:87:85:54 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2726): Got bonding state changed for F8:95:C7:87:85:54, but we have no record of that device.
,I/BluetoothBondStateMachine( 2094): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
,D/BluetoothAdapterProperties( 2094): Failed to remove device: F8:95:C7:87:85:54
,I/BluetoothBondStateMachine( 2094): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2094): StableState(): Entering Off State
,W/BluetoothEventManager( 2726): CachedBluetoothDevice for device F8:95:C7:87:85:54 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2726): Got bonding state changed for F8:95:C7:87:85:54, but we have no record of that device.
,W/bt-btif ( 2094): new conn_srvc id:26, app_id:1
W/bt-btif ( 2094): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2094): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3244): onSocketConnected: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 303)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): onBytesWritten: 77 bytes successfully written (thread ID: 304)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): Outgoing connection initialized (*handshake* thread ID: 304)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): Exiting thread (thread ID: 303)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3244): Entering thread (ID: 304)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): onBytesRead: Read 77 bytes successfully (thread ID: 304)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): Handshake succeeded with [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3244): onHandshakeSucceeded: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3244): onConnected: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
I/io.jxcore.node.ConnectionHelper( 3244): onConnected: Outgoing connection to peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
D/io.jxcore.node.ConnectionHelper( 3244): hasConnection: No connection with peer with ID F8:95:C7:87:85:54
W/io.jxcore.node.ConnectionHelper( 3244): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8213] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 3244): onConnected: Outgoing socket thread, for peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8213], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3244): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 3244): onConnected: The total number of connections is now 1
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3244): Exiting thread (ID: 304)
,D/io.jxcore.node.OutgoingSocketThread( 3244): Entering thread (ID: 305)
,D/io.jxcore.node.OutgoingSocketThread( 3244): Server socket local port: 54170
I/io.jxcore.node.OutgoingSocketThread( 3244): Now accepting connections...
,W/bt-btif ( 2094): new conn_srvc id:26, app_id:255
W/bt-btif ( 2094): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2094): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2094): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3244): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3244): Incoming connection initialized (thread ID: 306)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3244): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3244): Entering thread (ID: 306)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3244): onBytesRead: Read 77 bytes successfully (thread ID: 306)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3244): Got valid identity from [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3244): onBytesWritten: 77 bytes successfully written (thread ID: 306)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3244): removeThreadFromList: Removing thread with ID 306
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3244): Handshake thread disposed (thread ID: 306)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3244): onIncomingConnectionConnected: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3244): Exiting thread (ID: 306)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3244): onConnected: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
I/io.jxcore.node.ConnectionHelper( 3244): onConnected: Incoming connection to peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
D/io.jxcore.node.ConnectionHelper( 3244): hasConnection: We have an outgoing connection with peer with ID F8:95:C7:87:85:54
W/io.jxcore.node.ConnectionHelper( 3244): onConnected: Already connected with peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8213], continuing anyway...
W/io.jxcore.node.ConnectionHelper( 3244): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8213] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 3244): onConnected: Incoming socket thread, for peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8213], created successfully
D/io.jxcore.node.ConnectionHelper( 3244): onConnected: The total number of connections is now 2
,D/io.jxcore.node.IncomingSocketThread( 3244): Entering thread (ID: 307)
,I/io.jxcore.node.IncomingSocketThread( 3244): Local host address: localhost/127.0.0.1, port: 32844
D/io.jxcore.node.IncomingSocketThread( 3244): Setting local streams and starting stream copying threads...
,I/jxcore-log( 3244): 2015-12-18T17:58:35.433Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3244): 
,I/io.jxcore.node.StreamCopyingThread( 3244): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3244): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3244): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3244): Exiting thread (ID: 307)
,D/io.jxcore.node.StreamCopyingThread( 3244): Entering thread (ID: 309, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3244): Entering thread (ID: 308, name: Sender)
,I/io.jxcore.node.ConnectionHelper( 3244): onListeningForIncomingConnections: Outgoing connection is using port 54170 (peer ID: F8:95:C7:87:85:54)
,I/jxcore-log( 3244): 2015-12-18T17:58:35.568Z SendDataConnector.js: CLIENT connected to 54170, error: null
I/jxcore-log( 3244): 
I/jxcore-log( 3244): 2015-12-18T17:58:35.569Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3244): 
,I/io.jxcore.node.IncomingSocketThread( 3244): Incoming data from address: /127.0.0.1, port: 54170
D/io.jxcore.node.IncomingSocketThread( 3244): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3244): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3244): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3244): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3244): Exiting thread (ID: 305)
,I/jxcore-log( 3244): 2015-12-18T17:58:35.591Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3244): 
,D/io.jxcore.node.StreamCopyingThread( 3244): Entering thread (ID: 311, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3244): Entering thread (ID: 310, name: Sender)
,I/jxcore-log( 3244): 2015-12-18T17:58:36.443Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T17:58:36.449Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T17:58:36.455Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T17:58:36.463Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T17:58:36.471Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T17:58:36.491Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T17:58:36.493Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3244): 
I/jxcore-log( 3244): 2015-12-18T17:58:36.493Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3244): 
I/jxcore-log( 3244): oneRoundDownNow
I/jxcore-log( 3244): 
I/jxcore-log( 3244): 2015-12-18T17:58:36.494Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3244): 
I/jxcore-log( 3244): 2015-12-18T17:58:36.494Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3244): 
D/io.jxcore.node.ConnectionHelper( 3244): disconnectOutgoingConnection: Trying to close connection to peer with ID F8:95:C7:87:85:54
I/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: F8:95:C7:87:85:54
I/io.jxcore.node.IncomingSocketThread( 3244): close
D/io.jxcore.node.IncomingSocketThread( 3244): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3244): doStop: Thread ID: 311
D/io.jxcore.node.IncomingSocketThread( 3244): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3244): doStop: Thread ID: 310
D/io.jxcore.node.IncomingSocketThread( 3244): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 3244): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3244): Either failed to read from the output stream or write to the input stream (thread ID: 310, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3244): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3244): onDisconnected: Outgoing connection, peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8213] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.IncomingSocketThread( 3244): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 3244): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3244): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3244): Either failed to read from the output stream or write to the input stream (thread ID: 311, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 3244): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3244): onDisconnected: Outgoing connection, peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8213] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
D/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3244): disconnectOutgoingConnection: Successfully disconnected (peer ID: F8:95:C7:87:85:54
,E/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3244): Exiting thread (ID: 310, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3244): Exiting thread (ID: 311, name: Receiver)
,I/jxcore-log( 3244): 2015-12-18T17:58:36.500Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3244): 
I/jxcore-log( 3244): ---- round done--------
I/jxcore-log( 3244): 
I/jxcore-log( 3244): startWithNextDevice
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T17:58:36.516Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3244): 
,W/bt-btif ( 2094): bta_jv_rfc_port_to_cb(port_handle:0x9):jv handle:0x0 not FOUND
,I/jxcore-log( 3244): 2015-12-18T17:58:36.763Z SendDataTCPServer.js: TCP/IP server has received 32768 bytes of data
I/jxcore-log( 3244): 
,E/bt-btm  ( 2094): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2094): onReceive
,D/BluetoothManagerService(  750): Message: 20
D/BluetoothManagerService(  750): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2d9a9302:true
,I/BTConnectionReceiver( 1405): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1405): Bluetooth Device Name: Thali Test (Galaxy A3)
,I/jxcore-log( 3244): 2015-12-18T17:58:37.388Z SendDataTCPServer.js: TCP/IP server has received 34748 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T17:58:37.401Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T17:58:37.418Z SendDataTCPServer.js: TCP/IP server has received 50588 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T17:58:37.431Z SendDataTCPServer.js: TCP/IP server has received 56528 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T17:58:37.469Z SendDataTCPServer.js: TCP/IP server has received 74348 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T17:58:37.484Z SendDataTCPServer.js: TCP/IP server has received 76328 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T17:58:37.493Z SendDataTCPServer.js: TCP/IP server has received 78308 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T17:58:37.532Z SendDataTCPServer.js: TCP/IP server has received 80288 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T17:58:37.544Z SendDataTCPServer.js: TCP/IP server has received 84248 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T17:58:37.583Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3244): 
,W/bt-btif ( 2094): invalid rfc slot id: 4
,W/io.jxcore.node.StreamCopyingThread( 3244): Either failed to read from the output stream or write to the input stream (thread ID: 309, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 3244): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3244): onDisconnected: Incoming connection, peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8213] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 307
D/io.jxcore.node.IncomingSocketThread( 3244): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3244): doStop: Thread ID: 309
D/io.jxcore.node.IncomingSocketThread( 3244): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3244): doStop: Thread ID: 308
,D/io.jxcore.node.IncomingSocketThread( 3244): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 3244): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3244): Either failed to read from the output stream or write to the input stream (thread ID: 308, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3244): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3244): onDisconnected: Incoming connection, peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8213] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.IncomingSocketThread( 3244): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 3244): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3244): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3244): Exiting thread (ID: 308, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 3244): Exiting thread (ID: 309, name: Receiver)
,I/jxcore-log( 3244): 2015-12-18T17:58:37.711Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3244): 
,D/btif_config_util( 2094): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2094): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2094): onReceive
,I/BTConnectionReceiver( 1405): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1405): Bluetooth Device Name: G3s-1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): setState: RESTARTING
,I/wpa_supplicant(  984): P2P-FIND-STOPPED 
,I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): P2P device discovery started successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): restart: Restarting...
,D/WifiP2pManager( 3244): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service request added successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  984): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT8506], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT8506]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT8506], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT8506]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): setState: RESTARTING
,I/wpa_supplicant(  984): P2P-FIND-STOPPED 
,I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): Start timer timeout, starting now...
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): restart: Restarting...
,D/WifiP2pManager( 3244): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service request added successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Identity: "{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT598","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Resolved peer properties: [44:80:EB:7B:5A:05 motorola-XT1072_PT598]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onServiceDiscovered: [44:80:EB:7B:5A:05 motorola-XT1072_PT598]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onPeerDiscovered: [44:80:EB:7B:5A:05 motorola-XT1072_PT598]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 motorola-XT1072_PT598], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Adding new peer: [44:80:EB:7B:5A:05 motorola-XT1072_PT598]
I/io.jxcore.node.ConnectionHelper( 3244): onPeerDiscovered: [44:80:EB:7B:5A:05 motorola-XT1072_PT598], Bluetooth address: 44:80:EB:7B:5A:05, device name: XT1072_23d5, device address: 44:80:eb:7b:5a:07
D/io.jxcore.node.ConnectionHelper( 3244): notifyPeerAvailability: Peer [44:80:EB:7B:5A:05 motorola-XT1072_PT598] is available
I/jxcore-log( 3244): peerAvailabilityChanged [{"peerIdentifier":"44:80:EB:7B:5A:05","peerName":"motorola-XT1072_PT598","peerAvailable":true}]
I/jxcore-log( 3244): 
I/jxcore-log( 3244): Found peer : motorola-XT1072_PT598, Available: true
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): startWithNextDevice
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): device[3]: 44:80:EB:7B:5A:05
I/jxcore-log( 3244): 
I/jxcore-log( 3244): 2015-12-18T17:59:43.358Z SendDataConnector.js: Start called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3244): 
I/jxcore-log( 3244): 2015-12-18T17:59:43.359Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3244): 
I/jxcore-log( 3244): 2015-12-18T17:59:43.360Z SendDataConnector.js: do connect now
I/jxcore-log( 3244): 
I/io.jxcore.node.ConnectionHelper( 3244): connect: Trying to connect to peer with ID 44:80:EB:7B:5A:05
D/io.jxcore.node.ConnectionHelper( 3244): hasConnection: No connection with peer with ID 44:80:EB:7B:5A:05
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3244): connect: [44:80:EB:7B:5A:05 motorola-XT1072_PT598]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3244): connect: Trying to start connecting to null in address 44:80:EB:7B:5A:05
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3244): onConnecting: null 44:80:EB:7B:5A:05
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3244): connect: Started connecting to null in address 44:80:EB:7B:5A:05
I/io.jxcore.node.ConnectionHelper( 3244): connect: Connection process successfully started (peer ID: 44:80:EB:7B:5A:05)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): Trying to connect to peer with address 44:80:EB:7B:5A:05 (thread ID: 312)
W/BluetoothAdapter( 3244): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2094): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2094): info:x10
,D/        ( 2094): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 2094): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2094): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2094): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 1
E/bt-btif ( 2094): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2094): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2094): Entering PendingCommandState State
,W/BluetoothEventManager( 2726): CachedBluetoothDevice for device 44:80:EB:7B:5A:05 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2726): Got bonding state changed for 44:80:EB:7B:5A:05, but we have no record of that device.
,I/BluetoothBondStateMachine( 2094): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 0
,D/BluetoothAdapterProperties( 2094): Failed to remove device: 44:80:EB:7B:5A:05
,I/BluetoothBondStateMachine( 2094): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2094): StableState(): Entering Off State
,W/BluetoothEventManager( 2726): CachedBluetoothDevice for device 44:80:EB:7B:5A:05 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2726): Got bonding state changed for 44:80:EB:7B:5A:05, but we have no record of that device.
,W/bt-btif ( 2094): new conn_srvc id:26, app_id:1
W/bt-btif ( 2094): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2094): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3244): onSocketConnected: [44:80:EB:7B:5A:05 motorola-XT1072_PT598]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 312)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): onBytesWritten: 77 bytes successfully written (thread ID: 313)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): Outgoing connection initialized (*handshake* thread ID: 313)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): Exiting thread (thread ID: 312)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3244): Entering thread (ID: 313)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): onBytesRead: Read 80 bytes successfully (thread ID: 313)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): Handshake succeeded with [44:80:EB:7B:5A:05 motorola-XT1072_PT598]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3244): onHandshakeSucceeded: [44:80:EB:7B:5A:05 motorola-XT1072_PT598]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3244): onConnected: [44:80:EB:7B:5A:05 motorola-XT1072_PT598]
I/io.jxcore.node.ConnectionHelper( 3244): onConnected: Outgoing connection to peer [44:80:EB:7B:5A:05 motorola-XT1072_PT598]
D/io.jxcore.node.ConnectionHelper( 3244): hasConnection: No connection with peer with ID 44:80:EB:7B:5A:05
W/io.jxcore.node.ConnectionHelper( 3244): modifyListOfDiscoveredPeers: Peer [44:80:EB:7B:5A:05 motorola-XT1072_PT598] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 3244): onConnected: Outgoing socket thread, for peer [44:80:EB:7B:5A:05 motorola-XT1072_PT598], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3244): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 3244): onConnected: The total number of connections is now 1
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3244): Exiting thread (ID: 313)
,D/io.jxcore.node.OutgoingSocketThread( 3244): Entering thread (ID: 314)
D/io.jxcore.node.OutgoingSocketThread( 3244): Server socket local port: 47235
I/io.jxcore.node.OutgoingSocketThread( 3244): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3244): onListeningForIncomingConnections: Outgoing connection is using port 47235 (peer ID: 44:80:EB:7B:5A:05)
I/jxcore-log( 3244): 2015-12-18T17:59:45.363Z SendDataConnector.js: CLIENT connected to 47235, error: null
I/jxcore-log( 3244): 
I/jxcore-log( 3244): 2015-12-18T17:59:45.364Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3244): 
,I/io.jxcore.node.OutgoingSocketThread( 3244): Incoming data from address: /127.0.0.1, port: 47235
D/io.jxcore.node.OutgoingSocketThread( 3244): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3244): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3244): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3244): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3244): Exiting thread (ID: 314)
,W/bt-btif ( 2094): new conn_srvc id:26, app_id:255
W/bt-btif ( 2094): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2094): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2094): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3244): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3244): Incoming connection initialized (thread ID: 317)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3244): Waiting for incoming connections...
,D/io.jxcore.node.StreamCopyingThread( 3244): Entering thread (ID: 316, name: Receiver)
,I/jxcore-log( 3244): 2015-12-18T17:59:45.390Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3244): 
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3244): Entering thread (ID: 317)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3244): onBytesRead: Read 80 bytes successfully (thread ID: 317)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3244): Got valid identity from [44:80:EB:7B:5A:05 motorola-XT1072_PT598]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3244): onBytesWritten: 77 bytes successfully written (thread ID: 317)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3244): removeThreadFromList: Removing thread with ID 317
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3244): Handshake thread disposed (thread ID: 317)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3244): onIncomingConnectionConnected: [44:80:EB:7B:5A:05 motorola-XT1072_PT598]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3244): Exiting thread (ID: 317)
D/io.jxcore.node.StreamCopyingThread( 3244): Entering thread (ID: 315, name: Sender)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3244): onConnected: [44:80:EB:7B:5A:05 motorola-XT1072_PT598]
I/io.jxcore.node.ConnectionHelper( 3244): onConnected: Incoming connection to peer [44:80:EB:7B:5A:05 motorola-XT1072_PT598]
D/io.jxcore.node.ConnectionHelper( 3244): hasConnection: We have an outgoing connection with peer with ID 44:80:EB:7B:5A:05
W/io.jxcore.node.ConnectionHelper( 3244): onConnected: Already connected with peer [44:80:EB:7B:5A:05 motorola-XT1072_PT598], continuing anyway...
W/io.jxcore.node.ConnectionHelper( 3244): modifyListOfDiscoveredPeers: Peer [44:80:EB:7B:5A:05 motorola-XT1072_PT598] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 3244): onConnected: Incoming socket thread, for peer [44:80:EB:7B:5A:05 motorola-XT1072_PT598], created successfully
D/io.jxcore.node.ConnectionHelper( 3244): onConnected: The total number of connections is now 2
,D/io.jxcore.node.IncomingSocketThread( 3244): Entering thread (ID: 318)
,I/io.jxcore.node.IncomingSocketThread( 3244): Local host address: localhost/127.0.0.1, port: 32844
D/io.jxcore.node.IncomingSocketThread( 3244): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3244): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3244): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.IncomingSocketThread( 3244): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3244): Exiting thread (ID: 318)
,I/jxcore-log( 3244): 2015-12-18T17:59:45.830Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3244): 
,D/io.jxcore.node.StreamCopyingThread( 3244): Entering thread (ID: 319, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 3244): Entering thread (ID: 320, name: Receiver)
,D/        ( 2094): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23716
,I/jxcore-log( 3244): 2015-12-18T17:59:46.323Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T17:59:46.510Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T17:59:46.544Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T17:59:46.563Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T17:59:46.622Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T17:59:46.675Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3244): 
,D/        ( 2094): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:13816
,I/jxcore-log( 3244): 2015-12-18T17:59:46.704Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T17:59:46.724Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3244): 
I/jxcore-log( 3244): 2015-12-18T17:59:46.725Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T17:59:46.726Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T17:59:46.762Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T17:59:46.799Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T17:59:46.801Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T17:59:46.819Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T17:59:46.830Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T17:59:46.847Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T17:59:46.866Z SendDataTCPServer.js: TCP/IP server has received 36728 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T17:59:46.870Z SendDataTCPServer.js: TCP/IP server has received 38708 bytes of data
I/jxcore-log( 3244): 
,D/        ( 2094): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:3916
,I/jxcore-log( 3244): 2015-12-18T17:59:46.919Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T17:59:46.928Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T17:59:46.946Z SendDataTCPServer.js: TCP/IP server has received 42668 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T17:59:46.977Z SendDataTCPServer.js: TCP/IP server has received 46628 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T17:59:47.067Z SendDataTCPServer.js: TCP/IP server has received 50588 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T17:59:47.079Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T17:59:47.085Z SendDataTCPServer.js: TCP/IP server has received 52568 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T17:59:47.117Z SendDataTCPServer.js: TCP/IP server has received 54548 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T17:59:47.174Z SendDataTCPServer.js: TCP/IP server has received 56528 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T17:59:47.182Z SendDataTCPServer.js: TCP/IP server has received 58508 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T17:59:47.192Z SendDataTCPServer.js: TCP/IP server has received 60488 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T17:59:47.202Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T17:59:47.208Z SendDataTCPServer.js: TCP/IP server has received 62468 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T17:59:47.239Z SendDataTCPServer.js: TCP/IP server has received 64448 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T17:59:47.289Z SendDataTCPServer.js: TCP/IP server has received 66428 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T17:59:47.304Z SendDataTCPServer.js: TCP/IP server has received 68408 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T17:59:47.335Z SendDataTCPServer.js: TCP/IP server has received 72368 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T17:59:47.344Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T17:59:47.351Z SendDataTCPServer.js: TCP/IP server has received 74348 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T17:59:47.389Z SendDataTCPServer.js: TCP/IP server has received 78308 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T17:59:47.393Z SendDataTCPServer.js: TCP/IP server has received 80288 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T17:59:47.440Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T17:59:47.459Z SendDataTCPServer.js: TCP/IP server has received 82268 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T17:59:47.501Z SendDataTCPServer.js: TCP/IP server has received 92168 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T17:59:47.512Z SendDataTCPServer.js: TCP/IP server has received 94148 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T17:59:47.530Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T17:59:47.537Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3244): 
I/jxcore-log( 3244): oneRoundDownNow
I/jxcore-log( 3244): 
I/jxcore-log( 3244): 2015-12-18T17:59:47.539Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3244): 
I/jxcore-log( 3244): 2015-12-18T17:59:47.539Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3244): 
,D/io.jxcore.node.ConnectionHelper( 3244): disconnectOutgoingConnection: Trying to close connection to peer with ID 44:80:EB:7B:5A:05
I/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 44:80:EB:7B:5A:05
I/io.jxcore.node.IncomingSocketThread( 3244): close
D/io.jxcore.node.IncomingSocketThread( 3244): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3244): doStop: Thread ID: 316
D/io.jxcore.node.IncomingSocketThread( 3244): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3244): doStop: Thread ID: 315
D/io.jxcore.node.IncomingSocketThread( 3244): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 3244): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3244): Either failed to read from the output stream or write to the input stream (thread ID: 315, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3244): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3244): onDisconnected: Outgoing connection, peer [44:80:EB:7B:5A:05 motorola-XT1072_PT598] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.IncomingSocketThread( 3244): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 3244): closeLocalSocketAndStreams: Closing the localhost socket...
,I/io.jxcore.node.IncomingSocketThread( 3244): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3244): Either failed to read from the output stream or write to the input stream (thread ID: 316, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.IncomingSocketThread( 3244): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3244): onDisconnected: Outgoing connection, peer [44:80:EB:7B:5A:05 motorola-XT1072_PT598] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3244): disconnectOutgoingConnection: Successfully disconnected (peer ID: 44:80:EB:7B:5A:05
,W/bt-btif ( 2094): bta_jv_rfc_port_to_cb(port_handle:0xb):jv handle:0x0 not FOUND
,E/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 44:80:EB:7B:5A:05
D/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,E/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 44:80:EB:7B:5A:05
D/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3244): Exiting thread (ID: 316, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3244): Exiting thread (ID: 315, name: Sender)
,I/jxcore-log( 3244): 2015-12-18T17:59:47.590Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
,I/jxcore-log( 3244): 
I/jxcore-log( 3244): ---- round done--------
I/jxcore-log( 3244): 
I/jxcore-log( 3244): startWithNextDevice
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T17:59:47.602Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3244): 
,W/bt-btif ( 2094): invalid rfc slot id: 7
,W/io.jxcore.node.StreamCopyingThread( 3244): Either failed to read from the output stream or write to the input stream (thread ID: 320, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 3244): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3244): onDisconnected: Incoming connection, peer [44:80:EB:7B:5A:05 motorola-XT1072_PT598] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 318
D/io.jxcore.node.IncomingSocketThread( 3244): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3244): doStop: Thread ID: 320
D/io.jxcore.node.IncomingSocketThread( 3244): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3244): doStop: Thread ID: 319
D/io.jxcore.node.IncomingSocketThread( 3244): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 3244): closeLocalSocketAndStreams: Closing the local input stream...
D/io.jxcore.node.IncomingSocketThread( 3244): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 3244): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3244): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3244): Exiting thread (ID: 320, name: Receiver)
,W/io.jxcore.node.StreamCopyingThread( 3244): Either failed to read from the output stream or write to the input stream (thread ID: 319, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3244): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3244): onDisconnected: Incoming connection, peer [44:80:EB:7B:5A:05 motorola-XT1072_PT598] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3244): Exiting thread (ID: 319, name: Sender)
I/jxcore-log( 3244): 2015-12-18T17:59:47.642Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3244): 
,D/btif_config_util( 2094): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2094): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2094): onReceive,
,I/BTConnectionReceiver( 1405): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1405): Bluetooth Device Name: XT1072
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): checkListForExpiredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8213] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Removed [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
I/io.jxcore.node.ConnectionHelper( 3244): onPeerLost: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
D/io.jxcore.node.ConnectionHelper( 3244): hasConnection: No connection with peer with ID F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 3244): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8213] removed
D/io.jxcore.node.ConnectionHelper( 3244): notifyPeerAvailability: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8213] not available
I/jxcore-log( 3244): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:85:54","peerName":"LGE-LG-D722_PT8213","peerAvailable":false}]
I/jxcore-log( 3244): 
I/jxcore-log( 3244): startWithNextDevice
I/jxcore-log( 3244): 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 motorola-XT1072_PT598], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [44:80:EB:7B:5A:05 motorola-XT1072_PT598]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): restart: Restarting...
,D/WifiP2pManager( 3244): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service request added successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 4 device(s) discovered
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 motorola-XT1072_PT598], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [44:80:EB:7B:5A:05 motorola-XT1072_PT598]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): checkListForExpiredPeers: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT8506] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT8506], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Removed [08:EC:A9:50:76:27 samsung-SM-A300FU_PT8506]
I/io.jxcore.node.ConnectionHelper( 3244): onPeerLost: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT8506]
D/io.jxcore.node.ConnectionHelper( 3244): hasConnection: No connection with peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 3244): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT8506] removed
D/io.jxcore.node.ConnectionHelper( 3244): notifyPeerAvailability: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT8506] not available
I/jxcore-log( 3244): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:76:27","peerName":"samsung-SM-A300FU_PT8506","peerAvailable":false}]
I/jxcore-log( 3244): 
I/jxcore-log( 3244): startWithNextDevice
I/jxcore-log( 3244): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): setState: RESTARTING
,I/wpa_supplicant(  984): P2P-FIND-STOPPED 
,I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): P2P device discovery started successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): restart: Restarting...
,D/WifiP2pManager( 3244): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service request added successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service discovery started successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT633","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onServiceDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Adding new peer: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633]
,I/io.jxcore.node.ConnectionHelper( 3244): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
,D/io.jxcore.node.ConnectionHelper( 3244): notifyPeerAvailability: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633] is available
,I/jxcore-log( 3244): peerAvailabilityChanged [{"peerIdentifier":"B0:C5:59:3F:75:69","peerName":"samsung-SM-G900F_PT633","peerAvailable":true}]
I/jxcore-log( 3244): 
I/jxcore-log( 3244): Found peer : samsung-SM-G900F_PT633, Available: true
I/jxcore-log( 3244): 
I/jxcore-log( 3244): startWithNextDevice
I/jxcore-log( 3244): 
I/jxcore-log( 3244): device[4]: B0:C5:59:3F:75:69
I/jxcore-log( 3244): 
I/jxcore-log( 3244): 2015-12-18T18:00:49.033Z SendDataConnector.js: Start called with peer B0:C5:59:3F:75:69
I/jxcore-log( 3244): 
I/jxcore-log( 3244): 2015-12-18T18:00:49.033Z SendDataConnector.js: doConnect called with peer B0:C5:59:3F:75:69
I/jxcore-log( 3244): 
I/jxcore-log( 3244): 2015-12-18T18:00:49.034Z SendDataConnector.js: do connect now
I/jxcore-log( 3244): 
,I/io.jxcore.node.ConnectionHelper( 3244): connect: Trying to connect to peer with ID B0:C5:59:3F:75:69
D/io.jxcore.node.ConnectionHelper( 3244): hasConnection: No connection with peer with ID B0:C5:59:3F:75:69
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3244): connect: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3244): connect: Trying to start connecting to null in address B0:C5:59:3F:75:69
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3244): onConnecting: null B0:C5:59:3F:75:69
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3244): connect: Started connecting to null in address B0:C5:59:3F:75:69
I/io.jxcore.node.ConnectionHelper( 3244): connect: Connection process successfully started (peer ID: B0:C5:59:3F:75:69)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT8213","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
I/io.jxcore.node.ConnectionHelper( 3244): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213], Bluetooth address: F8:95:C7:87:85:54, device name: , device address: a2:39:f7:70:12:80
D/io.jxcore.node.ConnectionHelper( 3244): notifyPeerAvailability: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8213] is available
I/jxcore-log( 3244): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:85:54","peerName":"LGE-LG-D722_PT8213","peerAvailable":true}]
I/jxcore-log( 3244): 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): Trying to connect to peer with address B0:C5:59:3F:75:69 (thread ID: 321)
W/BluetoothAdapter( 3244): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2094): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2094): info:x10
,D/        ( 2094): remote version info [b0:c5:59:3f:75:69]: 7, f, 610c
,E/BluetoothRemoteDevices( 2094): aclStateChangeCallback: Device is NULL
,W/bt-l2cap( 2094): L2CAP - con rsp - bad ID. Exp: 5 Got: 3
,W/bt-sdp  ( 2094): process_service_search_attr_rsp
,D/btif_config_util( 2094): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/BluetoothBondStateMachine( 2094): bondStateChangeCallback: Status: 0 Address: B0:C5:59:3F:75:69 newState: 1
E/bt-btif ( 2094): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2094): Bond State Change Intent:B0:C5:59:3F:75:69 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2094): Entering PendingCommandState State
,W/BluetoothEventManager( 2726): CachedBluetoothDevice for device B0:C5:59:3F:75:69 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2726): Got bonding state changed for B0:C5:59:3F:75:69, but we have no record of that device.
,I/BluetoothBondStateMachine( 2094): bondStateChangeCallback: Status: 0 Address: B0:C5:59:3F:75:69 newState: 0
,D/BluetoothAdapterProperties( 2094): Failed to remove device: B0:C5:59:3F:75:69
,I/BluetoothBondStateMachine( 2094): Bond State Change Intent:B0:C5:59:3F:75:69 OldState: 11 NewState: 10
,W/BluetoothEventManager( 2726): CachedBluetoothDevice for device B0:C5:59:3F:75:69 not found, calling readPairedDevices().
,I/BluetoothBondStateMachine( 2094): StableState(): Entering Off State
,E/BluetoothEventManager( 2726): Got bonding state changed for B0:C5:59:3F:75:69, but we have no record of that device.
,W/bt-btif ( 2094): new conn_srvc id:26, app_id:1
W/bt-btif ( 2094): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2094): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3244): onSocketConnected: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 321)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): onBytesWritten: 77 bytes successfully written (thread ID: 322)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): Outgoing connection initialized (*handshake* thread ID: 322)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): Exiting thread (thread ID: 321)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3244): Entering thread (ID: 322)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): onBytesRead: Read 81 bytes successfully (thread ID: 322)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): Handshake succeeded with [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3244): onHandshakeSucceeded: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3244): Exiting thread (ID: 322)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3244): onConnected: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633]
I/io.jxcore.node.ConnectionHelper( 3244): onConnected: Outgoing connection to peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633]
,D/io.jxcore.node.ConnectionHelper( 3244): hasConnection: No connection with peer with ID B0:C5:59:3F:75:69
W/io.jxcore.node.ConnectionHelper( 3244): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 3244): onConnected: Outgoing socket thread, for peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633], created successfully
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3244): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 3244): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 3244): Entering thread (ID: 323)
,D/io.jxcore.node.OutgoingSocketThread( 3244): Server socket local port: 48525
I/io.jxcore.node.OutgoingSocketThread( 3244): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3244): onListeningForIncomingConnections: Outgoing connection is using port 48525 (peer ID: B0:C5:59:3F:75:69)
,I/jxcore-log( 3244): 2015-12-18T18:00:56.665Z SendDataConnector.js: CLIENT connected to 48525, error: null
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:00:56.668Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3244): 
,I/io.jxcore.node.OutgoingSocketThread( 3244): Incoming data from address: /127.0.0.1, port: 48525
D/io.jxcore.node.OutgoingSocketThread( 3244): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3244): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3244): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.OutgoingSocketThread( 3244): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3244): Exiting thread (ID: 323)
,I/jxcore-log( 3244): 2015-12-18T18:00:56.694Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3244): 
,D/io.jxcore.node.StreamCopyingThread( 3244): Entering thread (ID: 324, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 3244): Entering thread (ID: 325, name: Receiver)
,D/        ( 2094): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:1392
,D/btif_config_util( 2094): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3244): 2015-12-18T18:00:57.960Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:00:58.411Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:00:59.249Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:00:59.829Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:00:59.902Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:00:59.955Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:01:00.019Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:01:00.079Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:01:00.155Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:01:00.221Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3244): 
I/jxcore-log( 3244): 2015-12-18T18:01:00.222Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3244): 
I/jxcore-log( 3244): oneRoundDownNow
I/jxcore-log( 3244): 
I/jxcore-log( 3244): 2015-12-18T18:01:00.224Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3244): 
I/jxcore-log( 3244): 2015-12-18T18:01:00.224Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3244): 
,D/io.jxcore.node.ConnectionHelper( 3244): disconnectOutgoingConnection: Trying to close connection to peer with ID B0:C5:59:3F:75:69
I/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: B0:C5:59:3F:75:69
I/io.jxcore.node.OutgoingSocketThread( 3244): close
D/io.jxcore.node.OutgoingSocketThread( 3244): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3244): doStop: Thread ID: 325
D/io.jxcore.node.OutgoingSocketThread( 3244): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3244): doStop: Thread ID: 324
D/io.jxcore.node.OutgoingSocketThread( 3244): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 3244): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3244): Either failed to read from the output stream or write to the input stream (thread ID: 324, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3244): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3244): onDisconnected: Outgoing connection, peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 3244): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 3244): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3244): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3244): Either failed to read from the output stream or write to the input stream (thread ID: 325, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 3244): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3244): onDisconnected: Outgoing connection, peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3244): disconnectOutgoingConnection: Successfully disconnected (peer ID: B0:C5:59:3F:75:69
,E/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID B0:C5:59:3F:75:69
D/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3244): Exiting thread (ID: 324, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID B0:C5:59:3F:75:69
,D/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,D/io.jxcore.node.StreamCopyingThread( 3244): Exiting thread (ID: 325, name: Receiver)
,I/jxcore-log( 3244): 2015-12-18T18:01:00.274Z SendDataConnector.js: Mobile.Disconnect() callback with peer B0:C5:59:3F:75:69
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): ---- round done--------
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): startWithNextDevice
I/jxcore-log( 3244): 
,W/bt-btif ( 2094): bta_jv_rfc_port_to_cb(port_handle:0xd):jv handle:0x0 not FOUND
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): restart: Restarting...
,D/WifiP2pManager( 3244): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service request added successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service discovery started successfully
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633]
,E/bt-btm  ( 2094): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2094): onReceive
,I/BTConnectionReceiver( 1405): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1405): Bluetooth Device Name: Thali Test (Galaxy S5)
,W/bt-btif ( 2094): info:x10
,D/        ( 2094): remote version info [08:ec:a9:50:76:27]: 7, f, 610c
,I/BTConnectionReceiver( 1405): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1405): Bluetooth Device Name: Thali Test (Galaxy A3)
,W/bt-btif ( 2094): new conn_srvc id:26, app_id:255
W/bt-btif ( 2094): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2094): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3244): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3244): Incoming connection initialized (thread ID: 326)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3244): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3244): Entering thread (ID: 326)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3244): onBytesRead: Read 83 bytes successfully (thread ID: 326)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3244): Got valid identity from [08:EC:A9:50:76:27 samsung-SM-A300FU_PT8506]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3244): onBytesWritten: 77 bytes successfully written (thread ID: 326)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3244): removeThreadFromList: Removing thread with ID 326
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3244): Handshake thread disposed (thread ID: 326)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3244): onIncomingConnectionConnected: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT8506]
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3244): Exiting thread (ID: 326)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3244): onConnected: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT8506]
I/io.jxcore.node.ConnectionHelper( 3244): onConnected: Incoming connection to peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT8506]
D/io.jxcore.node.ConnectionHelper( 3244): hasConnection: No connection with peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 3244): notifyPeerAvailability: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT8506] is available
I/jxcore-log( 3244): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:76:27","peerName":"samsung-SM-A300FU_PT8506","peerAvailable":true}]
I/jxcore-log( 3244): 
I/jxcore-log( 3244): startWithNextDevice
I/jxcore-log( 3244): 
I/io.jxcore.node.ConnectionHelper( 3244): onConnected: Incoming socket thread, for peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT8506], created successfully
D/io.jxcore.node.ConnectionHelper( 3244): onConnected: The total number of connections is now 1
,D/io.jxcore.node.IncomingSocketThread( 3244): Entering thread (ID: 327)
,I/io.jxcore.node.IncomingSocketThread( 3244): Local host address: localhost/127.0.0.1, port: 32844
D/io.jxcore.node.IncomingSocketThread( 3244): Setting local streams and starting stream copying threads...
,I/jxcore-log( 3244): 2015-12-18T18:01:16.881Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3244): 
,I/io.jxcore.node.StreamCopyingThread( 3244): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3244): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3244): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3244): Exiting thread (ID: 327)
,D/io.jxcore.node.StreamCopyingThread( 3244): Entering thread (ID: 329, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3244): Entering thread (ID: 328, name: Sender)
,I/jxcore-log( 3244): 2015-12-18T18:01:17.610Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:01:17.618Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:01:17.629Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:01:17.646Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:01:17.657Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:01:17.691Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:01:17.703Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:01:17.710Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:01:17.747Z SendDataTCPServer.js: TCP/IP server has received 36728 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:01:17.760Z SendDataTCPServer.js: TCP/IP server has received 38708 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:01:17.767Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:01:17.780Z SendDataTCPServer.js: TCP/IP server has received 42668 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:01:17.811Z SendDataTCPServer.js: TCP/IP server has received 56528 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:01:17.828Z SendDataTCPServer.js: TCP/IP server has received 64448 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:01:17.871Z SendDataTCPServer.js: TCP/IP server has received 86228 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:01:17.881Z SendDataTCPServer.js: TCP/IP server has received 88208 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:01:17.914Z SendDataTCPServer.js: TCP/IP server has received 90188 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:01:17.948Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3244): 
,W/bt-btif ( 2094): invalid rfc slot id: 9
,W/io.jxcore.node.StreamCopyingThread( 3244): Either failed to read from the output stream or write to the input stream (thread ID: 329, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 3244): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3244): onDisconnected: Incoming connection, peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT8506] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 327
D/io.jxcore.node.IncomingSocketThread( 3244): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3244): doStop: Thread ID: 329
D/io.jxcore.node.IncomingSocketThread( 3244): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3244): doStop: Thread ID: 328
D/io.jxcore.node.IncomingSocketThread( 3244): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 3244): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3244): Either failed to read from the output stream or write to the input stream (thread ID: 328, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3244): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3244): onDisconnected: Incoming connection, peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT8506] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.IncomingSocketThread( 3244): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 3244): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3244): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3244): Exiting thread (ID: 329, name: Receiver)
,D/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.StreamCopyingThread( 3244): Exiting thread (ID: 328, name: Sender)
,I/jxcore-log( 3244): 2015-12-18T18:01:18.350Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3244): 
,D/btif_config_util( 2094): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-rfcomm( 2094): rfc_find_lcid_mcb LCID reused LCID:0x4b current:0x0
,W/bt-rfcomm( 2094): RFCOMM_DisconnectInd LCID:0x4b
,E/bt-btm  ( 2094): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2094): onReceive
,I/BTConnectionReceiver( 1405): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1405): Bluetooth Device Name: Thali Test (Galaxy A3)
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): checkListForExpiredPeers: Peer [44:80:EB:7B:5A:05 motorola-XT1072_PT598] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 motorola-XT1072_PT598], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Removed [44:80:EB:7B:5A:05 motorola-XT1072_PT598]
I/io.jxcore.node.ConnectionHelper( 3244): onPeerLost: [44:80:EB:7B:5A:05 motorola-XT1072_PT598]
D/io.jxcore.node.ConnectionHelper( 3244): hasConnection: No connection with peer with ID 44:80:EB:7B:5A:05
D/io.jxcore.node.ConnectionHelper( 3244): modifyListOfDiscoveredPeers: Peer [44:80:EB:7B:5A:05 motorola-XT1072_PT598] removed
D/io.jxcore.node.ConnectionHelper( 3244): notifyPeerAvailability: Peer [44:80:EB:7B:5A:05 motorola-XT1072_PT598] not available
,I/jxcore-log( 3244): peerAvailabilityChanged [{"peerIdentifier":"44:80:EB:7B:5A:05","peerName":"motorola-XT1072_PT598","peerAvailable":false}]
I/jxcore-log( 3244): 
I/jxcore-log( 3244): startWithNextDevice
I/jxcore-log( 3244): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): setState: RESTARTING
,I/wpa_supplicant(  984): P2P-FIND-STOPPED 
,I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 0 device(s) discovered
,I/ActivityManager(  750): Killing 2744:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/libprocessgroup(  750): failed to open /acct/uid_10003/pid_2744/cgroup.procs: No such file or directory
,W/bt-btif ( 2094): info:x10
,D/        ( 2094): remote version info [b0:c5:59:3f:75:69]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1405): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1405): Bluetooth Device Name: Thali Test (Galaxy S5)
,W/bt-btif ( 2094): new conn_srvc id:26, app_id:255
W/bt-btif ( 2094): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2094): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3244): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3244): Incoming connection initialized (thread ID: 330)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3244): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3244): Entering thread (ID: 330)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3244): onBytesRead: Read 81 bytes successfully (thread ID: 330)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3244): Got valid identity from [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3244): onBytesWritten: 77 bytes successfully written (thread ID: 330)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3244): removeThreadFromList: Removing thread with ID 330
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3244): Handshake thread disposed (thread ID: 330)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3244): onIncomingConnectionConnected: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3244): Exiting thread (ID: 330)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3244): onConnected: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633]
,I/io.jxcore.node.ConnectionHelper( 3244): onConnected: Incoming connection to peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633]
D/io.jxcore.node.ConnectionHelper( 3244): hasConnection: No connection with peer with ID B0:C5:59:3F:75:69
W/io.jxcore.node.ConnectionHelper( 3244): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 3244): onConnected: Incoming socket thread, for peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633], created successfully
D/io.jxcore.node.ConnectionHelper( 3244): onConnected: The total number of connections is now 1
,D/io.jxcore.node.IncomingSocketThread( 3244): Entering thread (ID: 331)
,I/jxcore-log( 3244): 2015-12-18T18:01:36.534Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3244): 
,I/io.jxcore.node.IncomingSocketThread( 3244): Local host address: localhost/127.0.0.1, port: 32844
D/io.jxcore.node.IncomingSocketThread( 3244): Setting local streams and starting stream copying threads...
,I/io.jxcore.node.StreamCopyingThread( 3244): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 3244): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3244): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3244): Exiting thread (ID: 331)
,D/io.jxcore.node.StreamCopyingThread( 3244): Entering thread (ID: 333, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3244): Entering thread (ID: 332, name: Sender)
,I/jxcore-log( 3244): 2015-12-18T18:01:37.560Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:01:37.564Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:01:37.591Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3244): 
,D/btif_config_util( 2094): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3244): 2015-12-18T18:01:37.630Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3244): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): setState: STARTED
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/jxcore-log( 3244): 2015-12-18T18:01:37.960Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:01:38.172Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:01:38.243Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:01:38.462Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:01:38.808Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:01:38.889Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:01:38.938Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:01:38.992Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:01:39.003Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:01:39.035Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:01:39.042Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:01:39.118Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:01:39.227Z SendDataTCPServer.js: TCP/IP server has received 32768 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:01:39.273Z SendDataTCPServer.js: TCP/IP server has received 34748 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:01:39.275Z SendDataTCPServer.js: TCP/IP server has received 36728 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:01:39.307Z SendDataTCPServer.js: TCP/IP server has received 38708 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:01:39.311Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:01:39.345Z SendDataTCPServer.js: TCP/IP server has received 42668 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:01:39.382Z SendDataTCPServer.js: TCP/IP server has received 44648 bytes of data
I/jxcore-log( 3244): 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  984): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
,I/jxcore-log( 3244): 2015-12-18T18:01:39.733Z SendDataTCPServer.js: TCP/IP server has received 46628 bytes of data
I/jxcore-log( 3244): 
D/WifiP2pManager( 3244): Ignored { when=-3ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service request added successfully
,I/jxcore-log( 3244): 2015-12-18T18:01:39.735Z SendDataTCPServer.js: TCP/IP server has received 48608 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:01:39.785Z SendDataTCPServer.js: TCP/IP server has received 50588 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:01:39.792Z SendDataTCPServer.js: TCP/IP server has received 52568 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:01:39.847Z SendDataTCPServer.js: TCP/IP server has received 54548 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:01:39.960Z SendDataTCPServer.js: TCP/IP server has received 56528 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:01:40.017Z SendDataTCPServer.js: TCP/IP server has received 58508 bytes of data
I/jxcore-log( 3244): 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3244): 2015-12-18T18:01:40.126Z SendDataTCPServer.js: TCP/IP server has received 60488 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:01:40.159Z SendDataTCPServer.js: TCP/IP server has received 62468 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:01:40.197Z SendDataTCPServer.js: TCP/IP server has received 64448 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:01:40.212Z SendDataTCPServer.js: TCP/IP server has received 66428 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:01:40.220Z SendDataTCPServer.js: TCP/IP server has received 68408 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:01:40.297Z SendDataTCPServer.js: TCP/IP server has received 72368 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:01:40.324Z SendDataTCPServer.js: TCP/IP server has received 74348 bytes of data
I/jxcore-log( 3244): 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3244): 2015-12-18T18:01:40.430Z SendDataTCPServer.js: TCP/IP server has received 76328 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:01:40.487Z SendDataTCPServer.js: TCP/IP server has received 78308 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:01:40.551Z SendDataTCPServer.js: TCP/IP server has received 80288 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:01:40.560Z SendDataTCPServer.js: TCP/IP server has received 82268 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:01:40.566Z SendDataTCPServer.js: TCP/IP server has received 84248 bytes of data
I/jxcore-log( 3244): 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3244): 2015-12-18T18:01:40.759Z SendDataTCPServer.js: TCP/IP server has received 88208 bytes of data
I/jxcore-log( 3244): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service discovery started successfully
,I/jxcore-log( 3244): 2015-12-18T18:01:40.793Z SendDataTCPServer.js: TCP/IP server has received 90188 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:01:40.959Z SendDataTCPServer.js: TCP/IP server has received 92168 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:01:40.999Z SendDataTCPServer.js: TCP/IP server has received 96128 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:01:41.083Z SendDataTCPServer.js: TCP/IP server has received 98108 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:01:41.151Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3244): 
,W/bt-btif ( 2094): invalid rfc slot id: 11
,W/io.jxcore.node.StreamCopyingThread( 3244): Either failed to read from the output stream or write to the input stream (thread ID: 333, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 3244): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3244): onDisconnected: Incoming connection, peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 331
D/io.jxcore.node.IncomingSocketThread( 3244): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3244): doStop: Thread ID: 333
D/io.jxcore.node.IncomingSocketThread( 3244): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3244): doStop: Thread ID: 332
D/io.jxcore.node.IncomingSocketThread( 3244): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 3244): closeLocalSocketAndStreams: Closing the local input stream...
,D/io.jxcore.node.IncomingSocketThread( 3244): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 3244): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3244): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3244): Exiting thread (ID: 333, name: Receiver)
,W/io.jxcore.node.StreamCopyingThread( 3244): Either failed to read from the output stream or write to the input stream (thread ID: 332, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3244): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3244): onDisconnected: Incoming connection, peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3244): Exiting thread (ID: 332, name: Sender)
,I/jxcore-log( 3244): 2015-12-18T18:01:41.340Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3244): 
,W/bt-rfcomm( 2094): rfc_find_lcid_mcb LCID reused LCID:0x4d current:0x0
,W/bt-rfcomm( 2094): RFCOMM_DisconnectInd LCID:0x4d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1532","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
I/io.jxcore.node.ConnectionHelper( 3244): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532], Bluetooth address: 7C:F9:0E:37:96:AB, device name: , device address: 7e:f9:0e:37:96:ac
D/io.jxcore.node.ConnectionHelper( 3244): notifyPeerAvailability: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532] is available
I/jxcore-log( 3244): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:37:96:AB","peerName":"samsung-SM-A500FU_PT1532","peerAvailable":true}]
I/jxcore-log( 3244): 
I/jxcore-log( 3244): Found peer : samsung-SM-A500FU_PT1532, Available: true
I/jxcore-log( 3244): 
I/jxcore-log( 3244): startWithNextDevice
I/jxcore-log( 3244): 
I/jxcore-log( 3244): device[5]: 7C:F9:0E:37:96:AB
I/jxcore-log( 3244): 
I/jxcore-log( 3244): 2015-12-18T18:01:44.213Z SendDataConnector.js: Start called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3244): 
I/jxcore-log( 3244): 2015-12-18T18:01:44.214Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3244): 
I/jxcore-log( 3244): 2015-12-18T18:01:44.215Z SendDataConnector.js: do connect now
I/jxcore-log( 3244): 
,I/io.jxcore.node.ConnectionHelper( 3244): connect: Trying to connect to peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 3244): hasConnection: No connection with peer with ID 7C:F9:0E:37:96:AB
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3244): connect: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3244): connect: Trying to start connecting to null in address 7C:F9:0E:37:96:AB
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3244): onConnecting: null 7C:F9:0E:37:96:AB
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3244): connect: Started connecting to null in address 7C:F9:0E:37:96:AB
I/io.jxcore.node.ConnectionHelper( 3244): connect: Connection process successfully started (peer ID: 7C:F9:0E:37:96:AB)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): Trying to connect to peer with address 7C:F9:0E:37:96:AB (thread ID: 334)
W/BluetoothAdapter( 3244): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2094): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btm  ( 2094): btm_acl_role_changed -> Issuing delayed HCI_Disconnect!!!
E/bt-btm  ( 2094): tBTM_SEC_DEV:0xa3e51414 rs_disc_pending=2
E/bt-btm  ( 2094): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 2094): bta_dm_check_av:0
,W/bt-btif ( 2094): btif_dm_cback : unhandled event (14)
,D/BluetoothMapService( 2094): onReceive
,I/BTConnectionReceiver( 1405): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1405): Bluetooth Device Name: Thali Test (Galaxy S5)
,W/bt-sdp  ( 2094): SDP - Rcvd conn cnf with error: 0x4  CID 0x4e
E/bt-btif ( 2094): DISCOVERY_COMP_EVT slot id:13, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2094): invalid rfc slot id: 13
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 334)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): Maximum number of allowed retries (0) reached, giving up... (thread ID: 334)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3244): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): Exiting thread (thread ID: 334)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3244): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
,I/jxcore-log( 3244): 2015-12-18T18:01:50.642Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532] failed
I/jxcore-log( 3244): 
I/jxcore-log( 3244): 2015-12-18T18:01:50.642Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532] failed
I/jxcore-log( 3244): 
I/jxcore-log( 3244): 2015-12-18T18:01:50.644Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3244): 
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): shutdown (thread ID: 334)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3244): setInsecureRfcommSocketPort: Will use port 1 when trying to connect
,I/jxcore-log( 3244): 2015-12-18T18:01:55.645Z SendDataConnector.js: re-try now : 7C:F9:0E:37:96:AB
I/jxcore-log( 3244): 
I/jxcore-log( 3244): 2015-12-18T18:01:55.647Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3244): 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): checkListForExpiredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8213] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Removed [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
D/WifiP2pManager( 3244): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service request added successfully
I/io.jxcore.node.ConnectionHelper( 3244): onPeerLost: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
D/io.jxcore.node.ConnectionHelper( 3244): hasConnection: No connection with peer with ID F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 3244): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8213] removed
D/io.jxcore.node.ConnectionHelper( 3244): notifyPeerAvailability: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8213] not available
I/jxcore-log( 3244): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:85:54","peerName":"LGE-LG-D722_PT8213","peerAvailable":false}]
I/jxcore-log( 3244): 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service discovery started successfully
,D/io.jxcore.node.ConnectionHelper( 3244): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:37:96:AB
E/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3244): disconnectOutgoingConnection: Failed to disconnect (peer ID: 7C:F9:0E:37:96:AB), either no such connection or failed to close the connection
I/jxcore-log( 3244): 2015-12-18T18:02:00.652Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3244): 
I/jxcore-log( 3244): 2015-12-18T18:02:00.653Z SendDataConnector.js: Connect (retry count 1) to peer 7C:F9:0E:37:96:AB with availability status: true
I/jxcore-log( 3244): 
I/jxcore-log( 3244): 2015-12-18T18:02:00.654Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3244): 
I/jxcore-log( 3244): 2015-12-18T18:02:00.654Z SendDataConnector.js: do connect now
I/jxcore-log( 3244): 
,I/io.jxcore.node.ConnectionHelper( 3244): connect: Trying to connect to peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 3244): hasConnection: No connection with peer with ID 7C:F9:0E:37:96:AB
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3244): connect: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3244): connect: Trying to start connecting to null in address 7C:F9:0E:37:96:AB
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): setInsecureRfcommSocketPort: Using port 1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3244): onConnecting: null 7C:F9:0E:37:96:AB
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3244): connect: Started connecting to null in address 7C:F9:0E:37:96:AB
I/io.jxcore.node.ConnectionHelper( 3244): connect: Connection process successfully started (peer ID: 7C:F9:0E:37:96:AB)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): Trying to connect to peer with address 7C:F9:0E:37:96:AB (thread ID: 336)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3244): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3244): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2094): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): restart: Restarting...
,D/WifiP2pManager( 3244): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service request added successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2094): info:x10
,D/        ( 2094): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2094): aclStateChangeCallback: Device is NULL
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service discovery started successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2094): process_service_search_attr_rsp
,D/btif_config_util( 2094): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/BluetoothBondStateMachine( 2094): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 1
E/bt-btif ( 2094): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2094): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2094): Entering PendingCommandState State
,W/BluetoothEventManager( 2726): CachedBluetoothDevice for device 7C:F9:0E:37:96:AB not found, calling readPairedDevices().
,E/BluetoothEventManager( 2726): Got bonding state changed for 7C:F9:0E:37:96:AB, but we have no record of that device.
,I/BluetoothBondStateMachine( 2094): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 0
,D/BluetoothAdapterProperties( 2094): Failed to remove device: 7C:F9:0E:37:96:AB
,W/BluetoothEventManager( 2726): CachedBluetoothDevice for device 7C:F9:0E:37:96:AB not found, calling readPairedDevices().
,I/BluetoothBondStateMachine( 2094): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2094): StableState(): Entering Off State
,E/BluetoothEventManager( 2726): Got bonding state changed for 7C:F9:0E:37:96:AB, but we have no record of that device.
,D/btif_config_util( 2094): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3244): Connection timeout
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3244): onConnectionTimeout: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
,I/jxcore-log( 3244): 2015-12-18T18:02:15.684Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532] timed out
I/jxcore-log( 3244): 
I/jxcore-log( 3244): 2015-12-18T18:02:15.684Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532] timed out
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:02:15.685Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3244): 
,W/bt-btif ( 2094): new conn_srvc id:26, app_id:1,
W/bt-btif ( 2094): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2094): bta_dm_pm_ssr:2, lat:1200
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): shutdown (thread ID: 336)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3244): onSocketConnected: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): Socket connection succeeded (using port 1), total number of attempts: 1 (thread ID: 336)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): Exiting thread (thread ID: 336)
,W/bt-btif ( 2094): bta_jv_rfc_port_to_cb(port_handle:0x10):jv handle:0x0 not FOUND
,E/bt-btm  ( 2094): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2094): onReceive
,I/jxcore-log( 3244): 2015-12-18T18:02:20.691Z SendDataConnector.js: re-try now : 7C:F9:0E:37:96:AB
I/jxcore-log( 3244): 
I/jxcore-log( 3244): 2015-12-18T18:02:20.691Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3244): 
,I/BTConnectionReceiver( 1405): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1405): Bluetooth Device Name: A5-1
,D/io.jxcore.node.ConnectionHelper( 3244): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:37:96:AB
E/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3244): disconnectOutgoingConnection: Failed to disconnect (peer ID: 7C:F9:0E:37:96:AB), either no such connection or failed to close the connection
I/jxcore-log( 3244): 2015-12-18T18:02:25.695Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:02:25.695Z SendDataConnector.js: Connect (retry count 2) to peer 7C:F9:0E:37:96:AB with availability status: true
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:02:25.700Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:02:25.703Z SendDataConnector.js: do connect now
I/jxcore-log( 3244): 
,I/io.jxcore.node.ConnectionHelper( 3244): connect: Trying to connect to peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 3244): hasConnection: No connection with peer with ID 7C:F9:0E:37:96:AB
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3244): connect: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3244): connect: Trying to start connecting to A5-1 in address 7C:F9:0E:37:96:AB
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): setInsecureRfcommSocketPort: Using port 1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3244): onConnecting: A5-1 7C:F9:0E:37:96:AB
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3244): connect: Started connecting to A5-1 in address 7C:F9:0E:37:96:AB
I/io.jxcore.node.ConnectionHelper( 3244): connect: Connection process successfully started (peer ID: 7C:F9:0E:37:96:AB)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): Trying to connect to peer with address 7C:F9:0E:37:96:AB (thread ID: 338)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3244): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3244): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2094): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): checkListForExpiredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Removed [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633]
I/io.jxcore.node.ConnectionHelper( 3244): onPeerLost: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633]
D/io.jxcore.node.ConnectionHelper( 3244): hasConnection: No connection with peer with ID B0:C5:59:3F:75:69
D/io.jxcore.node.ConnectionHelper( 3244): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633] removed
D/io.jxcore.node.ConnectionHelper( 3244): notifyPeerAvailability: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633] not available
I/jxcore-log( 3244): peerAvailabilityChanged [{"peerIdentifier":"B0:C5:59:3F:75:69","peerName":"samsung-SM-G900F_PT633","peerAvailable":false}]
I/jxcore-log( 3244): 
,W/bt-btif ( 2094): info:x10
,D/        ( 2094): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,W/bt-sdp  ( 2094): process_service_search_attr_rsp
,I/BTConnectionReceiver( 1405): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1405): Bluetooth Device Name: A5-1
,W/bt-btif ( 2094): new conn_srvc id:26, app_id:1
W/bt-btif ( 2094): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2094): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3244): onSocketConnected: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): Socket connection succeeded (using port 1), total number of attempts: 1 (thread ID: 338)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): onBytesWritten: 77 bytes successfully written (thread ID: 339)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): Outgoing connection initialized (*handshake* thread ID: 339)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): Exiting thread (thread ID: 338)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3244): Entering thread (ID: 339)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): onBytesRead: Read 83 bytes successfully (thread ID: 339)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): Handshake succeeded with [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3244): onHandshakeSucceeded: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3244): Exiting thread (ID: 339)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3244): onConnected: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
I/io.jxcore.node.ConnectionHelper( 3244): onConnected: Outgoing connection to peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
D/io.jxcore.node.ConnectionHelper( 3244): hasConnection: No connection with peer with ID 7C:F9:0E:37:96:AB
W/io.jxcore.node.ConnectionHelper( 3244): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 3244): onConnected: Outgoing socket thread, for peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3244): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 3244): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 3244): Entering thread (ID: 340)
D/io.jxcore.node.OutgoingSocketThread( 3244): Server socket local port: 59629
I/io.jxcore.node.OutgoingSocketThread( 3244): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3244): onListeningForIncomingConnections: Outgoing connection is using port 59629 (peer ID: 7C:F9:0E:37:96:AB)
I/jxcore-log( 3244): 2015-12-18T18:02:35.973Z SendDataConnector.js: CLIENT connected to 59629, error: null
I/jxcore-log( 3244): 
I/jxcore-log( 3244): 2015-12-18T18:02:35.974Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3244): 
,I/io.jxcore.node.OutgoingSocketThread( 3244): Incoming data from address: /127.0.0.1, port: 59629
D/io.jxcore.node.OutgoingSocketThread( 3244): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3244): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3244): setBufferSize: Setting buffer size to 8192 bytes
,I/jxcore-log( 3244): 2015-12-18T18:02:35.993Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3244): 
,I/io.jxcore.node.OutgoingSocketThread( 3244): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3244): Exiting thread (ID: 340)
,D/io.jxcore.node.StreamCopyingThread( 3244): Entering thread (ID: 341, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 3244): Entering thread (ID: 342, name: Receiver)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): setState: RESTARTING
I/wpa_supplicant(  984): P2P-FIND-STOPPED 
,I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 0 device(s) discovered
,D/        ( 2094): PORT_WriteDataCO: tx queue is full,tx.queue_size:10172,tx.queue.count:11,available:24706
,I/jxcore-log( 3244): 2015-12-18T18:02:36.879Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:02:36.940Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3244): 
,D/        ( 2094): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:14806
,I/jxcore-log( 3244): 2015-12-18T18:02:37.024Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:02:37.071Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3244): 
,D/        ( 2094): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:3916
,I/jxcore-log( 3244): 2015-12-18T18:02:37.151Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:02:37.235Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:02:37.330Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:02:37.393Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:02:37.438Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:02:37.552Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3244): 
I/jxcore-log( 3244): 2015-12-18T18:02:37.553Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3244): 
I/jxcore-log( 3244): oneRoundDownNow
I/jxcore-log( 3244): 
I/jxcore-log( 3244): 2015-12-18T18:02:37.554Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3244): 
I/jxcore-log( 3244): 2015-12-18T18:02:37.555Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3244): 
,D/io.jxcore.node.ConnectionHelper( 3244): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:37:96:AB
I/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 7C:F9:0E:37:96:AB
I/io.jxcore.node.OutgoingSocketThread( 3244): close
D/io.jxcore.node.OutgoingSocketThread( 3244): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3244): doStop: Thread ID: 342
D/io.jxcore.node.OutgoingSocketThread( 3244): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3244): doStop: Thread ID: 341
D/io.jxcore.node.OutgoingSocketThread( 3244): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 3244): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3244): Either failed to read from the output stream or write to the input stream (thread ID: 341, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3244): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3244): onDisconnected: Outgoing connection, peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 3244): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 3244): closeLocalSocketAndStreams: Closing the localhost socket...
,I/io.jxcore.node.OutgoingSocketThread( 3244): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3244): Either failed to read from the output stream or write to the input stream (thread ID: 342, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.OutgoingSocketThread( 3244): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3244): onDisconnected: Outgoing connection, peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3244): disconnectOutgoingConnection: Successfully disconnected (peer ID: 7C:F9:0E:37:96:AB
,E/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,E/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3244): Exiting thread (ID: 342, name: Receiver)
,W/bt-btif ( 2094): bta_jv_rfc_port_to_cb(port_handle:0x11):jv handle:0x0 not FOUND
D/io.jxcore.node.StreamCopyingThread( 3244): Exiting thread (ID: 341, name: Sender)
,I/jxcore-log( 3244): 2015-12-18T18:02:37.603Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): ---- round done--------
I/jxcore-log( 3244): 
I/jxcore-log( 3244): startWithNextDevice
I/jxcore-log( 3244): 
,D/btif_config_util( 2094): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2094): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2094): onReceive
,I/BTConnectionReceiver( 1405): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1405): Bluetooth Device Name: A5-1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): P2P device discovery started successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): restart: Restarting...
,D/WifiP2pManager( 3244): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service request added successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service discovery started successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT5572","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572]
I/io.jxcore.node.ConnectionHelper( 3244): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
D/io.jxcore.node.ConnectionHelper( 3244): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572] is available
,I/jxcore-log( 3244): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:75:41","peerName":"samsung-SM-A300FU_PT5572","peerAvailable":true}]
I/jxcore-log( 3244): 
I/jxcore-log( 3244): Found peer : samsung-SM-A300FU_PT5572, Available: true
I/jxcore-log( 3244): 
I/jxcore-log( 3244): startWithNextDevice
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): device[6]: 08:EC:A9:50:75:41
,I/jxcore-log( 3244): 
I/jxcore-log( 3244): 2015-12-18T18:02:46.314Z SendDataConnector.js: Start called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3244): 
I/jxcore-log( 3244): 2015-12-18T18:02:46.315Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3244): 
I/jxcore-log( 3244): 2015-12-18T18:02:46.322Z SendDataConnector.js: do connect now
I/jxcore-log( 3244): 
I/io.jxcore.node.ConnectionHelper( 3244): connect: Trying to connect to peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 3244): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3244): connect: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3244): connect: Trying to start connecting to null in address 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3244): onConnecting: null 08:EC:A9:50:75:41
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3244): connect: Started connecting to null in address 08:EC:A9:50:75:41
I/io.jxcore.node.ConnectionHelper( 3244): connect: Connection process successfully started (peer ID: 08:EC:A9:50:75:41)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): Trying to connect to peer with address 08:EC:A9:50:75:41 (thread ID: 343)
W/BluetoothAdapter( 3244): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2094): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2094): info:x10
,D/        ( 2094): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2094): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2094): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2094): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 1
E/bt-btif ( 2094): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2094): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2094): Entering PendingCommandState State
,W/BluetoothEventManager( 2726): CachedBluetoothDevice for device 08:EC:A9:50:75:41 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2726): Got bonding state changed for 08:EC:A9:50:75:41, but we have no record of that device.
,I/BluetoothBondStateMachine( 2094): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 0
,D/BluetoothAdapterProperties( 2094): Failed to remove device: 08:EC:A9:50:75:41
,I/BluetoothBondStateMachine( 2094): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2094): StableState(): Entering Off State
,W/BluetoothEventManager( 2726): CachedBluetoothDevice for device 08:EC:A9:50:75:41 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2726): Got bonding state changed for 08:EC:A9:50:75:41, but we have no record of that device.
,W/bt-btif ( 2094): new conn_srvc id:26, app_id:1
W/bt-btif ( 2094): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2094): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3244): onSocketConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 343)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): onBytesWritten: 77 bytes successfully written (thread ID: 344)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): Outgoing connection initialized (*handshake* thread ID: 344)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): Exiting thread (thread ID: 343)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3244): Entering thread (ID: 344)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): onBytesRead: Read 83 bytes successfully (thread ID: 344)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): Handshake succeeded with [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3244): onHandshakeSucceeded: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3244): onConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572]
I/io.jxcore.node.ConnectionHelper( 3244): onConnected: Outgoing connection to peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572]
D/io.jxcore.node.ConnectionHelper( 3244): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
W/io.jxcore.node.ConnectionHelper( 3244): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 3244): onConnected: Outgoing socket thread, for peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3244): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 3244): onConnected: The total number of connections is now 1
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3244): Exiting thread (ID: 344)
,D/io.jxcore.node.OutgoingSocketThread( 3244): Entering thread (ID: 345)
,D/io.jxcore.node.OutgoingSocketThread( 3244): Server socket local port: 52951
I/io.jxcore.node.OutgoingSocketThread( 3244): Now accepting connections...
,W/bt-btif ( 2094): new conn_srvc id:26, app_id:255
W/bt-btif ( 2094): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2094): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2094): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3244): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3244): Incoming connection initialized (thread ID: 346)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3244): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3244): Entering thread (ID: 346)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3244): onBytesRead: Read 83 bytes successfully (thread ID: 346)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3244): Got valid identity from [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3244): onBytesWritten: 77 bytes successfully written (thread ID: 346)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3244): removeThreadFromList: Removing thread with ID 346
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3244): Handshake thread disposed (thread ID: 346)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3244): onIncomingConnectionConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3244): Exiting thread (ID: 346)
,I/io.jxcore.node.ConnectionHelper( 3244): onListeningForIncomingConnections: Outgoing connection is using port 52951 (peer ID: 08:EC:A9:50:75:41)
I/jxcore-log( 3244): 2015-12-18T18:02:48.330Z SendDataConnector.js: CLIENT connected to 52951, error: null
I/jxcore-log( 3244): 
I/jxcore-log( 3244): 2015-12-18T18:02:48.331Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3244): 
,I/io.jxcore.node.OutgoingSocketThread( 3244): Incoming data from address: /127.0.0.1, port: 52951
D/io.jxcore.node.OutgoingSocketThread( 3244): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3244): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3244): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3244): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3244): Exiting thread (ID: 345)
,D/io.jxcore.node.StreamCopyingThread( 3244): Entering thread (ID: 348, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3244): Entering thread (ID: 347, name: Sender)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3244): onConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572]
I/jxcore-log( 3244): 2015-12-18T18:02:48.363Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3244): 
,I/io.jxcore.node.ConnectionHelper( 3244): onConnected: Incoming connection to peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572]
D/io.jxcore.node.ConnectionHelper( 3244): hasConnection: We have an outgoing connection with peer with ID 08:EC:A9:50:75:41
W/io.jxcore.node.ConnectionHelper( 3244): onConnected: Already connected with peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572], continuing anyway...
W/io.jxcore.node.ConnectionHelper( 3244): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 3244): onConnected: Incoming socket thread, for peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572], created successfully
D/io.jxcore.node.ConnectionHelper( 3244): onConnected: The total number of connections is now 2
,D/io.jxcore.node.IncomingSocketThread( 3244): Entering thread (ID: 349)
,I/io.jxcore.node.IncomingSocketThread( 3244): Local host address: localhost/127.0.0.1, port: 32844
D/io.jxcore.node.IncomingSocketThread( 3244): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3244): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3244): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.IncomingSocketThread( 3244): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3244): Exiting thread (ID: 349)
,I/jxcore-log( 3244): 2015-12-18T18:02:48.799Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3244): 
D/io.jxcore.node.StreamCopyingThread( 3244): Entering thread (ID: 350, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 3244): Entering thread (ID: 351, name: Receiver)
,D/        ( 2094): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23716
,I/jxcore-log( 3244): 2015-12-18T18:02:49.276Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:02:49.285Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:02:49.297Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:02:49.303Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:02:49.315Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:02:49.322Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:02:49.337Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3244): 
,D/        ( 2094): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:8866
,I/jxcore-log( 3244): 2015-12-18T18:02:49.380Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3244): 
I/jxcore-log( 3244): 2015-12-18T18:02:49.383Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:02:49.491Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:02:49.528Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:02:49.608Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:02:49.689Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:02:49.727Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:02:49.760Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:02:49.825Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:02:49.842Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:02:49.878Z SendDataTCPServer.js: TCP/IP server has received 37620 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:02:49.922Z SendDataTCPServer.js: TCP/IP server has received 39600 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:02:49.945Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:02:50.001Z SendDataTCPServer.js: TCP/IP server has received 45540 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:02:50.045Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:02:50.053Z SendDataTCPServer.js: TCP/IP server has received 61380 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:02:50.069Z SendDataTCPServer.js: TCP/IP server has received 63360 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:02:50.092Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:02:50.142Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:02:50.143Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3244): 
I/jxcore-log( 3244): oneRoundDownNow
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:02:50.157Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3244): 
I/jxcore-log( 3244): 2015-12-18T18:02:50.157Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3244): 
,D/io.jxcore.node.ConnectionHelper( 3244): disconnectOutgoingConnection: Trying to close connection to peer with ID 08:EC:A9:50:75:41
I/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 08:EC:A9:50:75:41
I/io.jxcore.node.IncomingSocketThread( 3244): close
D/io.jxcore.node.IncomingSocketThread( 3244): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3244): doStop: Thread ID: 348
D/io.jxcore.node.IncomingSocketThread( 3244): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3244): doStop: Thread ID: 347
D/io.jxcore.node.IncomingSocketThread( 3244): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 3244): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3244): Either failed to read from the output stream or write to the input stream (thread ID: 347, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3244): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3244): onDisconnected: Outgoing connection, peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.IncomingSocketThread( 3244): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 3244): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3244): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3244): Either failed to read from the output stream or write to the input stream (thread ID: 348, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 3244): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3244): onDisconnected: Outgoing connection, peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3244): disconnectOutgoingConnection: Successfully disconnected (peer ID: 08:EC:A9:50:75:41
,E/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3244): Exiting thread (ID: 347, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3244): Exiting thread (ID: 348, name: Receiver)
,I/jxcore-log( 3244): 2015-12-18T18:02:50.204Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3244): 
I/jxcore-log( 3244): ---- round done--------
I/jxcore-log( 3244): 
I/jxcore-log( 3244): startWithNextDevice
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:02:50.207Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:02:50.210Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:02:50.211Z SendDataTCPServer.js: TCP/IP server has received 95040 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:02:50.215Z SendDataTCPServer.js: TCP/IP server has received 97020 bytes of data
I/jxcore-log( 3244): 
,W/bt-btif ( 2094): bta_jv_rfc_port_to_cb(port_handle:0x12):jv handle:0x0 not FOUND
,I/jxcore-log( 3244): 2015-12-18T18:02:50.246Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3244): 
,W/bt-btif ( 2094): invalid rfc slot id: 12
,W/io.jxcore.node.StreamCopyingThread( 3244): Either failed to read from the output stream or write to the input stream (thread ID: 351, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 3244): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3244): onDisconnected: Incoming connection, peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 349
D/io.jxcore.node.IncomingSocketThread( 3244): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3244): doStop: Thread ID: 351
D/io.jxcore.node.IncomingSocketThread( 3244): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3244): doStop: Thread ID: 350
D/io.jxcore.node.IncomingSocketThread( 3244): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 3244): closeLocalSocketAndStreams: Closing the local input stream...
D/io.jxcore.node.IncomingSocketThread( 3244): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 3244): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3244): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3244): Exiting thread (ID: 351, name: Receiver)
,W/io.jxcore.node.StreamCopyingThread( 3244): Either failed to read from the output stream or write to the input stream (thread ID: 350, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3244): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3244): onDisconnected: Incoming connection, peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3244): Exiting thread (ID: 350, name: Sender)
,I/jxcore-log( 3244): 2015-12-18T18:02:50.306Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3244): 
,D/btif_config_util( 2094): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2094): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2094): onReceive
,I/BTConnectionReceiver( 1405): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1405): Bluetooth Device Name: A3-1
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): restart: Restarting...
,D/WifiP2pManager( 3244): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service request added successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service discovery started successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): checkListForExpiredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532] expired
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Removed [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
I/io.jxcore.node.ConnectionHelper( 3244): onPeerLost: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
D/io.jxcore.node.ConnectionHelper( 3244): hasConnection: No connection with peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 3244): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532] removed
D/io.jxcore.node.ConnectionHelper( 3244): notifyPeerAvailability: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532] not available
I/jxcore-log( 3244): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:37:96:AB","peerName":"samsung-SM-A500FU_PT1532","peerAvailable":false}]
I/jxcore-log( 3244): 
I/jxcore-log( 3244): startWithNextDevice
I/jxcore-log( 3244): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT589","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT589]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT589]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT589]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT589], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT589]
I/io.jxcore.node.ConnectionHelper( 3244): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT589], Bluetooth address: 58:3F:54:73:64:C0, device name: , device address: 02:9a:02:7b:60:ac
D/io.jxcore.node.ConnectionHelper( 3244): notifyPeerAvailability: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT589] is available
I/jxcore-log( 3244): peerAvailabilityChanged [{"peerIdentifier":"58:3F:54:73:64:C0","peerName":"LGE-LG-D855_PT589","peerAvailable":true}]
I/jxcore-log( 3244): 
I/jxcore-log( 3244): Found peer : LGE-LG-D855_PT589, Available: true
I/jxcore-log( 3244): 
I/jxcore-log( 3244): startWithNextDevice
I/jxcore-log( 3244): 
I/jxcore-log( 3244): device[7]: 58:3F:54:73:64:C0
I/jxcore-log( 3244): 
I/jxcore-log( 3244): 2015-12-18T18:03:00.193Z SendDataConnector.js: Start called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3244): 
I/jxcore-log( 3244): 2015-12-18T18:03:00.193Z SendDataConnector.js: doConnect called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3244): 
I/jxcore-log( 3244): 2015-12-18T18:03:00.194Z SendDataConnector.js: do connect now
I/jxcore-log( 3244): 
,I/io.jxcore.node.ConnectionHelper( 3244): connect: Trying to connect to peer with ID 58:3F:54:73:64:C0
,D/io.jxcore.node.ConnectionHelper( 3244): hasConnection: No connection with peer with ID 58:3F:54:73:64:C0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3244): connect: [58:3F:54:73:64:C0 LGE-LG-D855_PT589]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3244): connect: Trying to start connecting to null in address 58:3F:54:73:64:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): setMaxNumberOfRetries: 0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3244): onConnecting: null 58:3F:54:73:64:C0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3244): connect: Started connecting to null in address 58:3F:54:73:64:C0
,I/io.jxcore.node.ConnectionHelper( 3244): connect: Connection process successfully started (peer ID: 58:3F:54:73:64:C0)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): Trying to connect to peer with address 58:3F:54:73:64:C0 (thread ID: 352)
W/BluetoothAdapter( 3244): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2094): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2094): info:x10
,D/        ( 2094): remote version info [58:3f:54:73:64:c0]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 2094): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2094): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2094): bondStateChangeCallback: Status: 0 Address: 58:3F:54:73:64:C0 newState: 1
E/bt-btif ( 2094): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2094): Bond State Change Intent:58:3F:54:73:64:C0 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2094): Entering PendingCommandState State
,W/BluetoothEventManager( 2726): CachedBluetoothDevice for device 58:3F:54:73:64:C0 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2726): Got bonding state changed for 58:3F:54:73:64:C0, but we have no record of that device.
,I/BluetoothBondStateMachine( 2094): bondStateChangeCallback: Status: 0 Address: 58:3F:54:73:64:C0 newState: 0
,D/BluetoothAdapterProperties( 2094): Failed to remove device: 58:3F:54:73:64:C0
,I/BluetoothBondStateMachine( 2094): Bond State Change Intent:58:3F:54:73:64:C0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2094): StableState(): Entering Off State
,W/BluetoothEventManager( 2726): CachedBluetoothDevice for device 58:3F:54:73:64:C0 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2726): Got bonding state changed for 58:3F:54:73:64:C0, but we have no record of that device.
,W/bt-btif ( 2094): new conn_srvc id:26, app_id:1
W/bt-btif ( 2094): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2094): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3244): onSocketConnected: [58:3F:54:73:64:C0 LGE-LG-D855_PT589]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 352)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): onBytesWritten: 77 bytes successfully written (thread ID: 353)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): Outgoing connection initialized (*handshake* thread ID: 353)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): Exiting thread (thread ID: 352)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3244): Entering thread (ID: 353)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): onBytesRead: Read 76 bytes successfully (thread ID: 353)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): Handshake succeeded with [58:3F:54:73:64:C0 LGE-LG-D855_PT589]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3244): onHandshakeSucceeded: [58:3F:54:73:64:C0 LGE-LG-D855_PT589]
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3244): onConnected: [58:3F:54:73:64:C0 LGE-LG-D855_PT589]
I/io.jxcore.node.ConnectionHelper( 3244): onConnected: Outgoing connection to peer [58:3F:54:73:64:C0 LGE-LG-D855_PT589]
D/io.jxcore.node.ConnectionHelper( 3244): hasConnection: No connection with peer with ID 58:3F:54:73:64:C0
W/io.jxcore.node.ConnectionHelper( 3244): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT589] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 3244): onConnected: Outgoing socket thread, for peer [58:3F:54:73:64:C0 LGE-LG-D855_PT589], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3244): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 3244): onConnected: The total number of connections is now 1
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3244): Exiting thread (ID: 353)
,D/io.jxcore.node.OutgoingSocketThread( 3244): Entering thread (ID: 354)
D/io.jxcore.node.OutgoingSocketThread( 3244): Server socket local port: 46533
I/io.jxcore.node.OutgoingSocketThread( 3244): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3244): onListeningForIncomingConnections: Outgoing connection is using port 46533 (peer ID: 58:3F:54:73:64:C0)
,I/jxcore-log( 3244): 2015-12-18T18:03:01.998Z SendDataConnector.js: CLIENT connected to 46533, error: null
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:03:02.001Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3244): 
,I/io.jxcore.node.OutgoingSocketThread( 3244): Incoming data from address: /127.0.0.1, port: 46533
D/io.jxcore.node.OutgoingSocketThread( 3244): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3244): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3244): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3244): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3244): Exiting thread (ID: 354)
,D/io.jxcore.node.StreamCopyingThread( 3244): Entering thread (ID: 356, name: Receiver)
,I/jxcore-log( 3244): 2015-12-18T18:03:02.036Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3244): 
,D/io.jxcore.node.StreamCopyingThread( 3244): Entering thread (ID: 355, name: Sender)
,W/bt-btif ( 2094): new conn_srvc id:26, app_id:255
W/bt-btif ( 2094): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2094): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2094): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3244): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3244): Incoming connection initialized (thread ID: 357)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3244): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3244): Entering thread (ID: 357)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3244): onBytesRead: Read 76 bytes successfully (thread ID: 357)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3244): Got valid identity from [58:3F:54:73:64:C0 LGE-LG-D855_PT589]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3244): onBytesWritten: 77 bytes successfully written (thread ID: 357)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3244): removeThreadFromList: Removing thread with ID 357
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3244): Handshake thread disposed (thread ID: 357)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3244): onIncomingConnectionConnected: [58:3F:54:73:64:C0 LGE-LG-D855_PT589]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3244): Exiting thread (ID: 357)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3244): onConnected: [58:3F:54:73:64:C0 LGE-LG-D855_PT589]
I/io.jxcore.node.ConnectionHelper( 3244): onConnected: Incoming connection to peer [58:3F:54:73:64:C0 LGE-LG-D855_PT589]
D/io.jxcore.node.ConnectionHelper( 3244): hasConnection: We have an outgoing connection with peer with ID 58:3F:54:73:64:C0
W/io.jxcore.node.ConnectionHelper( 3244): onConnected: Already connected with peer [58:3F:54:73:64:C0 LGE-LG-D855_PT589], continuing anyway...
W/io.jxcore.node.ConnectionHelper( 3244): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT589] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 3244): onConnected: Incoming socket thread, for peer [58:3F:54:73:64:C0 LGE-LG-D855_PT589], created successfully
D/io.jxcore.node.ConnectionHelper( 3244): onConnected: The total number of connections is now 2
,D/io.jxcore.node.IncomingSocketThread( 3244): Entering thread (ID: 358)
,I/io.jxcore.node.IncomingSocketThread( 3244): Local host address: localhost/127.0.0.1, port: 32844
D/io.jxcore.node.IncomingSocketThread( 3244): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3244): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3244): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.IncomingSocketThread( 3244): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3244): Exiting thread (ID: 358)
,I/jxcore-log( 3244): 2015-12-18T18:03:02.459Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3244): 
,D/io.jxcore.node.StreamCopyingThread( 3244): Entering thread (ID: 359, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 3244): Entering thread (ID: 360, name: Receiver)
,D/        ( 2094): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23716
,I/jxcore-log( 3244): 2015-12-18T18:03:02.576Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3244): 
,D/        ( 2094): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:16786
,I/jxcore-log( 3244): 2015-12-18T18:03:02.634Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:03:02.721Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3244): 
,D/        ( 2094): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:9856
,I/jxcore-log( 3244): 2015-12-18T18:03:03.258Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:03:03.305Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:03:03.312Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:03:03.320Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:03:03.328Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:03:03.337Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:03:03.347Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:03:03.380Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:03:03.402Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:03:03.482Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3244): 
I/jxcore-log( 3244): 2015-12-18T18:03:03.483Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:03:03.681Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:03:03.793Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:03:03.822Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3244): 
I/jxcore-log( 3244): 2015-12-18T18:03:03.823Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3244): 
I/jxcore-log( 3244): oneRoundDownNow
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:03:03.832Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:03:03.833Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3244): 
D/io.jxcore.node.ConnectionHelper( 3244): disconnectOutgoingConnection: Trying to close connection to peer with ID 58:3F:54:73:64:C0
I/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 58:3F:54:73:64:C0
I/io.jxcore.node.IncomingSocketThread( 3244): close
D/io.jxcore.node.IncomingSocketThread( 3244): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3244): doStop: Thread ID: 356
D/io.jxcore.node.IncomingSocketThread( 3244): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3244): doStop: Thread ID: 355
D/io.jxcore.node.IncomingSocketThread( 3244): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 3244): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3244): Either failed to read from the output stream or write to the input stream (thread ID: 355, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3244): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
,W/io.jxcore.node.ConnectionHelper( 3244): onDisconnected: Outgoing connection, peer [58:3F:54:73:64:C0 LGE-LG-D855_PT589] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.IncomingSocketThread( 3244): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 3244): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3244): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3244): Either failed to read from the output stream or write to the input stream (thread ID: 356, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 3244): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,W/io.jxcore.node.ConnectionHelper( 3244): onDisconnected: Outgoing connection, peer [58:3F:54:73:64:C0 LGE-LG-D855_PT589] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3244): disconnectOutgoingConnection: Successfully disconnected (peer ID: 58:3F:54:73:64:C0
,E/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 58:3F:54:73:64:C0
D/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3244): Exiting thread (ID: 355, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 58:3F:54:73:64:C0
D/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3244): Exiting thread (ID: 356, name: Receiver)
,I/jxcore-log( 3244): 2015-12-18T18:03:03.892Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:3F:54:73:64:C0
I/jxcore-log( 3244): 
I/jxcore-log( 3244): ---- round done--------
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): startWithNextDevice
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:03:03.895Z SendDataTCPServer.js: TCP/IP server has received 60488 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:03:03.923Z SendDataTCPServer.js: TCP/IP server has received 62468 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:03:03.959Z SendDataTCPServer.js: TCP/IP server has received 64448 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:03:04.016Z SendDataTCPServer.js: TCP/IP server has received 66428 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:03:04.038Z SendDataTCPServer.js: TCP/IP server has received 68408 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:03:04.077Z SendDataTCPServer.js: TCP/IP server has received 70388 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:03:04.084Z SendDataTCPServer.js: TCP/IP server has received 72368 bytes of data
I/jxcore-log( 3244): 
,W/bt-btif ( 2094): bta_jv_rfc_port_to_cb(port_handle:0x14):jv handle:0x0 not FOUND
,I/jxcore-log( 3244): 2015-12-18T18:03:04.117Z SendDataTCPServer.js: TCP/IP server has received 74348 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:03:04.127Z SendDataTCPServer.js: TCP/IP server has received 76328 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:03:04.184Z SendDataTCPServer.js: TCP/IP server has received 78308 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:03:04.304Z SendDataTCPServer.js: TCP/IP server has received 80288 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:03:04.323Z SendDataTCPServer.js: TCP/IP server has received 82268 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:03:04.359Z SendDataTCPServer.js: TCP/IP server has received 86228 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:03:04.373Z SendDataTCPServer.js: TCP/IP server has received 88208 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:03:04.380Z SendDataTCPServer.js: TCP/IP server has received 90188 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:03:04.391Z SendDataTCPServer.js: TCP/IP server has received 92168 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:03:04.427Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3244): 
,W/bt-btif ( 2094): invalid rfc slot id: 17
,W/io.jxcore.node.StreamCopyingThread( 3244): Either failed to read from the output stream or write to the input stream (thread ID: 360, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 3244): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3244): onDisconnected: Incoming connection, peer [58:3F:54:73:64:C0 LGE-LG-D855_PT589] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 358
D/io.jxcore.node.IncomingSocketThread( 3244): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3244): doStop: Thread ID: 360
D/io.jxcore.node.IncomingSocketThread( 3244): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3244): doStop: Thread ID: 359
D/io.jxcore.node.IncomingSocketThread( 3244): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 3244): closeLocalSocketAndStreams: Closing the local input stream...
D/io.jxcore.node.IncomingSocketThread( 3244): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 3244): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3244): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3244): Exiting thread (ID: 360, name: Receiver)
,W/io.jxcore.node.StreamCopyingThread( 3244): Either failed to read from the output stream or write to the input stream (thread ID: 359, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3244): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
,W/io.jxcore.node.ConnectionHelper( 3244): onDisconnected: Incoming connection, peer [58:3F:54:73:64:C0 LGE-LG-D855_PT589] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3244): Exiting thread (ID: 359, name: Sender)
,I/jxcore-log( 3244): 2015-12-18T18:03:04.499Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3244): 
,D/btif_config_util( 2094): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2094): btm_sec_disconnected - Clearing Pending flag,
,D/BluetoothMapService( 2094): onReceive
,I/BTConnectionReceiver( 1405): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1405): Bluetooth Device Name: G3-1
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  984): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT589], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT589]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT589], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT589]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572]
,D/WifiP2pManager( 3244): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service request added successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT589], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT589]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572]
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service discovery started successfully
,W/bt-btif ( 2094): info:x10
,D/        ( 2094): remote version info [7c:f9:0e:37:96:ab]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1405): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1405): Bluetooth Device Name: A5-1
,W/bt-btif ( 2094): new conn_srvc id:26, app_id:255
W/bt-btif ( 2094): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2094): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3244): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3244): Incoming connection initialized (thread ID: 361)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3244): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3244): Entering thread (ID: 361)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3244): onBytesRead: Read 83 bytes successfully (thread ID: 361)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3244): Got valid identity from [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3244): onBytesWritten: 77 bytes successfully written (thread ID: 361)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3244): removeThreadFromList: Removing thread with ID 361
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3244): Handshake thread disposed (thread ID: 361)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3244): onIncomingConnectionConnected: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3244): onConnected: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
I/io.jxcore.node.ConnectionHelper( 3244): onConnected: Incoming connection to peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
D/io.jxcore.node.ConnectionHelper( 3244): hasConnection: No connection with peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 3244): notifyPeerAvailability: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532] is available
I/jxcore-log( 3244): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:37:96:AB","peerName":"samsung-SM-A500FU_PT1532","peerAvailable":true}]
I/jxcore-log( 3244): 
I/jxcore-log( 3244): startWithNextDevice
I/jxcore-log( 3244): 
I/io.jxcore.node.ConnectionHelper( 3244): onConnected: Incoming socket thread, for peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532], created successfully
D/io.jxcore.node.ConnectionHelper( 3244): onConnected: The total number of connections is now 1
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3244): Exiting thread (ID: 361)
,D/io.jxcore.node.IncomingSocketThread( 3244): Entering thread (ID: 362)
,I/io.jxcore.node.IncomingSocketThread( 3244): Local host address: localhost/127.0.0.1, port: 32844
D/io.jxcore.node.IncomingSocketThread( 3244): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3244): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3244): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3244): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3244): Exiting thread (ID: 362)
,I/jxcore-log( 3244): 2015-12-18T18:03:29.979Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3244): 
,D/io.jxcore.node.StreamCopyingThread( 3244): Entering thread (ID: 364, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3244): Entering thread (ID: 363, name: Sender)
,I/jxcore-log( 3244): 2015-12-18T18:03:30.706Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:03:30.714Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:03:30.749Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:03:30.756Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:03:30.764Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:03:30.783Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:03:30.807Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:03:30.822Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:03:30.860Z SendDataTCPServer.js: TCP/IP server has received 47520 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:03:30.869Z SendDataTCPServer.js: TCP/IP server has received 49500 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:03:30.930Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:03:30.967Z SendDataTCPServer.js: TCP/IP server has received 55440 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:03:31.004Z SendDataTCPServer.js: TCP/IP server has received 57420 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:03:31.021Z SendDataTCPServer.js: TCP/IP server has received 59400 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:03:31.029Z SendDataTCPServer.js: TCP/IP server has received 63360 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:03:31.040Z SendDataTCPServer.js: TCP/IP server has received 65340 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:03:31.099Z SendDataTCPServer.js: TCP/IP server has received 67320 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:03:31.108Z SendDataTCPServer.js: TCP/IP server has received 69300 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:03:31.118Z SendDataTCPServer.js: TCP/IP server has received 71280 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:03:31.129Z SendDataTCPServer.js: TCP/IP server has received 73260 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:03:31.158Z SendDataTCPServer.js: TCP/IP server has received 79200 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:03:31.165Z SendDataTCPServer.js: TCP/IP server has received 81180 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:03:31.183Z SendDataTCPServer.js: TCP/IP server has received 85140 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:03:31.219Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:03:31.232Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:03:31.269Z SendDataTCPServer.js: TCP/IP server has received 97020 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:03:31.282Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3244): 
,W/bt-btif ( 2094): invalid rfc slot id: 19
,W/io.jxcore.node.StreamCopyingThread( 3244): Either failed to read from the output stream or write to the input stream (thread ID: 364, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.IncomingSocketThread( 3244): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3244): onDisconnected: Incoming connection, peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 362
D/io.jxcore.node.IncomingSocketThread( 3244): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3244): doStop: Thread ID: 364
D/io.jxcore.node.IncomingSocketThread( 3244): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3244): doStop: Thread ID: 363
D/io.jxcore.node.IncomingSocketThread( 3244): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 3244): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3244): Either failed to read from the output stream or write to the input stream (thread ID: 363, thread name: Sender): Socket closed
,E/io.jxcore.node.IncomingSocketThread( 3244): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3244): onDisconnected: Incoming connection, peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.IncomingSocketThread( 3244): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 3244): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3244): closeBluetoothSocketAndStreams
,D/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3244): Exiting thread (ID: 363, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 3244): Exiting thread (ID: 364, name: Receiver)
,I/jxcore-log( 3244): 2015-12-18T18:03:31.357Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3244): 
,D/btif_config_util( 2094): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-rfcomm( 2094): rfc_find_lcid_mcb LCID reused LCID:0x4a current:0x0
W/bt-rfcomm( 2094): RFCOMM_DisconnectInd LCID:0x4a
,E/bt-btm  ( 2094): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2094): onReceive
,I/BTConnectionReceiver( 1405): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1405): Bluetooth Device Name: A5-1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): setState: RESTARTING
,I/wpa_supplicant(  984): P2P-FIND-STOPPED 
,I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): setState: STARTED
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): restart: Restarting...
,D/WifiP2pManager( 3244): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service request added successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  984): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT589], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT589]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT589], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT589]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service discovery started successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  984): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT589], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT589]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT589], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT589]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
,I/ActivityManager(  750): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=3737 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,I/GAv4    ( 3737): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3737):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3737):   adb logcat -s GAv4
,I/EventLogService( 1628): Aggregate from 1450459738452 (log), 1450459738452 (data)
,W/GAv4    ( 3737): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3737): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3737): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  750): Killing 2595:com.google.android.gm/u0a70 (adj 15): empty #17
,W/libprocessgroup(  750): failed to open /acct/uid_10070/pid_2595/cgroup.procs: No such file or directory
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): setState: RESTARTING
,I/wpa_supplicant(  984): P2P-FIND-STOPPED 
,I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): Start timer timeout, starting now...
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): checkListForExpiredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Removed [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572]
I/io.jxcore.node.ConnectionHelper( 3244): onPeerLost: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572]
D/io.jxcore.node.ConnectionHelper( 3244): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 3244): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572] removed
D/io.jxcore.node.ConnectionHelper( 3244): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572] not available
I/jxcore-log( 3244): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:75:41","peerName":"samsung-SM-A300FU_PT5572","peerAvailable":false}]
I/jxcore-log( 3244): 
I/jxcore-log( 3244): startWithNextDevice
I/jxcore-log( 3244): 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  984): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
,D/WifiP2pManager( 3244): Ignored { when=-4ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service request added successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service discovery started successfully
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1532","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
I/io.jxcore.node.ConnectionHelper( 3244): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532], Bluetooth address: 7C:F9:0E:37:96:AB, device name: , device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 3244): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT3826","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
I/io.jxcore.node.ConnectionHelper( 3244): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826], Bluetooth address: 7C:F9:0E:51:18:22, device name: , device address: 7e:f9:0e:51:18:23
D/io.jxcore.node.ConnectionHelper( 3244): notifyPeerAvailability: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826] is available
,I/jxcore-log( 3244): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:51:18:22","peerName":"samsung-SM-A500FU_PT3826","peerAvailable":true}]
I/jxcore-log( 3244): 
I/jxcore-log( 3244): Found peer : samsung-SM-A500FU_PT3826, Available: true
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): startWithNextDevice
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): device[8]: 7C:F9:0E:51:18:22
I/jxcore-log( 3244): 
I/jxcore-log( 3244): 2015-12-18T18:04:38.540Z SendDataConnector.js: Start called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3244): 
I/jxcore-log( 3244): 2015-12-18T18:04:38.540Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3244): 
I/jxcore-log( 3244): 2015-12-18T18:04:38.540Z SendDataConnector.js: do connect now
I/jxcore-log( 3244): 
,I/io.jxcore.node.ConnectionHelper( 3244): connect: Trying to connect to peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 3244): hasConnection: No connection with peer with ID 7C:F9:0E:51:18:22
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3244): connect: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3244): connect: Trying to start connecting to null in address 7C:F9:0E:51:18:22
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3244): onConnecting: null 7C:F9:0E:51:18:22
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3244): connect: Started connecting to null in address 7C:F9:0E:51:18:22
I/io.jxcore.node.ConnectionHelper( 3244): connect: Connection process successfully started (peer ID: 7C:F9:0E:51:18:22)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): Trying to connect to peer with address 7C:F9:0E:51:18:22 (thread ID: 365)
W/BluetoothAdapter( 3244): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2094): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2094): info:x10
,D/        ( 2094): remote version info [7c:f9:0e:51:18:22]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2094): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2094): process_service_search_attr_rsp
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
,I/BluetoothBondStateMachine( 2094): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:51:18:22 newState: 1
E/bt-btif ( 2094): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2094): Bond State Change Intent:7C:F9:0E:51:18:22 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2094): Entering PendingCommandState State
,W/BluetoothEventManager( 2726): CachedBluetoothDevice for device 7C:F9:0E:51:18:22 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2726): Got bonding state changed for 7C:F9:0E:51:18:22, but we have no record of that device.
,I/BluetoothBondStateMachine( 2094): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:51:18:22 newState: 0
,D/BluetoothAdapterProperties( 2094): Failed to remove device: 7C:F9:0E:51:18:22
,I/BluetoothBondStateMachine( 2094): Bond State Change Intent:7C:F9:0E:51:18:22 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2094): StableState(): Entering Off State
,W/BluetoothEventManager( 2726): CachedBluetoothDevice for device 7C:F9:0E:51:18:22 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2726): Got bonding state changed for 7C:F9:0E:51:18:22, but we have no record of that device.
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2094): new conn_srvc id:26, app_id:1
W/bt-btif ( 2094): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2094): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3244): onSocketConnected: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 365)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): onBytesWritten: 77 bytes successfully written (thread ID: 366)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): Outgoing connection initialized (*handshake* thread ID: 366)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): Exiting thread (thread ID: 365)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3244): Entering thread (ID: 366)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): onBytesRead: Read 83 bytes successfully (thread ID: 366)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): Handshake succeeded with [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3244): onHandshakeSucceeded: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3244): onConnected: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
,I/io.jxcore.node.ConnectionHelper( 3244): onConnected: Outgoing connection to peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
D/io.jxcore.node.ConnectionHelper( 3244): hasConnection: No connection with peer with ID 7C:F9:0E:51:18:22
,W/io.jxcore.node.ConnectionHelper( 3244): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 3244): onConnected: Outgoing socket thread, for peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3244): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 3244): onConnected: The total number of connections is now 1
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3244): Exiting thread (ID: 366)
,D/io.jxcore.node.OutgoingSocketThread( 3244): Entering thread (ID: 367)
,D/io.jxcore.node.OutgoingSocketThread( 3244): Server socket local port: 48925
I/io.jxcore.node.OutgoingSocketThread( 3244): Now accepting connections...
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/io.jxcore.node.ConnectionHelper( 3244): onListeningForIncomingConnections: Outgoing connection is using port 48925 (peer ID: 7C:F9:0E:51:18:22)
,I/jxcore-log( 3244): 2015-12-18T18:04:40.405Z SendDataConnector.js: CLIENT connected to 48925, error: null
I/jxcore-log( 3244): 
I/jxcore-log( 3244): 2015-12-18T18:04:40.412Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3244): 
,I/io.jxcore.node.OutgoingSocketThread( 3244): Incoming data from address: /127.0.0.1, port: 48925
D/io.jxcore.node.OutgoingSocketThread( 3244): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3244): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3244): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3244): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3244): Exiting thread (ID: 367)
,D/io.jxcore.node.StreamCopyingThread( 3244): Entering thread (ID: 369, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3244): Entering thread (ID: 368, name: Sender)
,I/jxcore-log( 3244): 2015-12-18T18:04:40.451Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3244): 
,W/bt-btif ( 2094): new conn_srvc id:26, app_id:255
W/bt-btif ( 2094): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2094): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2094): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3244): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3244): Incoming connection initialized (thread ID: 370)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3244): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3244): Entering thread (ID: 370)
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3244): onBytesRead: Read 83 bytes successfully (thread ID: 370)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3244): Got valid identity from [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3244): onBytesWritten: 77 bytes successfully written (thread ID: 370)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3244): removeThreadFromList: Removing thread with ID 370
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3244): Handshake thread disposed (thread ID: 370)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3244): onIncomingConnectionConnected: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3244): Exiting thread (ID: 370)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3244): onConnected: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT589], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT589]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
I/io.jxcore.node.ConnectionHelper( 3244): onConnected: Incoming connection to peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
D/io.jxcore.node.ConnectionHelper( 3244): hasConnection: We have an outgoing connection with peer with ID 7C:F9:0E:51:18:22
W/io.jxcore.node.ConnectionHelper( 3244): onConnected: Already connected with peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826], continuing anyway...
W/io.jxcore.node.ConnectionHelper( 3244): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 3244): onConnected: Incoming socket thread, for peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826], created successfully
D/io.jxcore.node.ConnectionHelper( 3244): onConnected: The total number of connections is now 2
,D/io.jxcore.node.IncomingSocketThread( 3244): Entering thread (ID: 371)
,I/jxcore-log( 3244): 2015-12-18T18:04:40.864Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3244): 
,I/io.jxcore.node.IncomingSocketThread( 3244): Local host address: localhost/127.0.0.1, port: 32844
D/io.jxcore.node.IncomingSocketThread( 3244): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3244): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3244): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.IncomingSocketThread( 3244): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3244): Exiting thread (ID: 371)
,D/io.jxcore.node.StreamCopyingThread( 3244): Entering thread (ID: 372, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 3244): Entering thread (ID: 373, name: Receiver)
,D/        ( 2094): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23716
,D/        ( 2094): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:11836
,I/jxcore-log( 3244): 2015-12-18T18:04:41.369Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:04:41.385Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:04:41.544Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:04:41.720Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:04:41.757Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:04:41.771Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:04:41.783Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:04:41.788Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:04:41.824Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:04:41.832Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:04:41.838Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:04:41.848Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:04:41.953Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:04:41.975Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:04:41.994Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:04:42.027Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3244): 
I/jxcore-log( 3244): 2015-12-18T18:04:42.030Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:04:42.047Z SendDataTCPServer.js: TCP/IP server has received 34748 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:04:42.150Z SendDataTCPServer.js: TCP/IP server has received 36728 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:04:42.289Z SendDataTCPServer.js: TCP/IP server has received 38708 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:04:42.296Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:04:42.309Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:04:42.318Z SendDataTCPServer.js: TCP/IP server has received 42668 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:04:42.373Z SendDataTCPServer.js: TCP/IP server has received 44648 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:04:42.507Z SendDataTCPServer.js: TCP/IP server has received 46628 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:04:42.552Z SendDataTCPServer.js: TCP/IP server has received 48608 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:04:42.561Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:04:42.565Z SendDataTCPServer.js: TCP/IP server has received 50588 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:04:42.758Z SendDataTCPServer.js: TCP/IP server has received 52568 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:04:42.891Z SendDataTCPServer.js: TCP/IP server has received 54548 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:04:42.901Z SendDataTCPServer.js: TCP/IP server has received 56528 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:04:42.908Z SendDataTCPServer.js: TCP/IP server has received 58508 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:04:42.916Z SendDataTCPServer.js: TCP/IP server has received 60488 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:04:42.929Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3244): 
I/jxcore-log( 3244): 2015-12-18T18:04:42.931Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3244): 
I/jxcore-log( 3244): oneRoundDownNow
I/jxcore-log( 3244): 
I/jxcore-log( 3244): 2015-12-18T18:04:42.932Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3244): 
I/jxcore-log( 3244): 2015-12-18T18:04:42.933Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3244): 
,D/io.jxcore.node.ConnectionHelper( 3244): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:51:18:22
I/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 7C:F9:0E:51:18:22
I/io.jxcore.node.IncomingSocketThread( 3244): close
D/io.jxcore.node.IncomingSocketThread( 3244): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3244): doStop: Thread ID: 369
D/io.jxcore.node.IncomingSocketThread( 3244): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3244): doStop: Thread ID: 368
D/io.jxcore.node.IncomingSocketThread( 3244): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 3244): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3244): Either failed to read from the output stream or write to the input stream (thread ID: 368, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3244): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3244): onDisconnected: Outgoing connection, peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.IncomingSocketThread( 3244): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 3244): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3244): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3244): Either failed to read from the output stream or write to the input stream (thread ID: 369, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 3244): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3244): onDisconnected: Outgoing connection, peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3244): disconnectOutgoingConnection: Successfully disconnected (peer ID: 7C:F9:0E:51:18:22
,E/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,D/io.jxcore.node.StreamCopyingThread( 3244): Exiting thread (ID: 368, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:51:18:22
,D/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3244): Exiting thread (ID: 369, name: Receiver)
,I/jxcore-log( 3244): 2015-12-18T18:04:42.982Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): ---- round done--------
I/jxcore-log( 3244): 
I/jxcore-log( 3244): startWithNextDevice
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:04:42.985Z SendDataTCPServer.js: TCP/IP server has received 72368 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:04:42.988Z SendDataTCPServer.js: TCP/IP server has received 74348 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:04:43.026Z SendDataTCPServer.js: TCP/IP server has received 78308 bytes of data
I/jxcore-log( 3244): 
,W/bt-btif ( 2094): bta_jv_rfc_port_to_cb(port_handle:0x17):jv handle:0x0 not FOUND
,I/jxcore-log( 3244): 2015-12-18T18:04:43.099Z SendDataTCPServer.js: TCP/IP server has received 80288 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:04:43.111Z SendDataTCPServer.js: TCP/IP server has received 82268 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:04:43.147Z SendDataTCPServer.js: TCP/IP server has received 88208 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:04:43.152Z SendDataTCPServer.js: TCP/IP server has received 90188 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:04:43.158Z SendDataTCPServer.js: TCP/IP server has received 92168 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:04:43.197Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3244): 
,W/bt-btif ( 2094): invalid rfc slot id: 20
,W/io.jxcore.node.StreamCopyingThread( 3244): Either failed to read from the output stream or write to the input stream (thread ID: 373, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 3244): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3244): onDisconnected: Incoming connection, peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 371
D/io.jxcore.node.IncomingSocketThread( 3244): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3244): doStop: Thread ID: 373
D/io.jxcore.node.IncomingSocketThread( 3244): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3244): doStop: Thread ID: 372
D/io.jxcore.node.IncomingSocketThread( 3244): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 3244): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3244): Either failed to read from the output stream or write to the input stream (thread ID: 372, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3244): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3244): onDisconnected: Incoming connection, peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.IncomingSocketThread( 3244): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 3244): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3244): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3244): Exiting thread (ID: 372, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 3244): Exiting thread (ID: 373, name: Receiver)
,I/jxcore-log( 3244): 2015-12-18T18:04:43.383Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3244): 
,D/btif_config_util( 2094): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2094): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2094): onReceive
,I/BTConnectionReceiver( 1405): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:51:18:22, alias=null, name=Thali Test (Galaxy A5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1405): Bluetooth Device Name: Thali Test (Galaxy A5)
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  984): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT589], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT589]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT589], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT589]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3244): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service discovery started successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  984): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  984): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT589], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT589]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT589], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT589]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT589], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT589]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3244): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service request added successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT589], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT589]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service discovery started successfully
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8280","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280]
I/io.jxcore.node.ConnectionHelper( 3244): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
D/io.jxcore.node.ConnectionHelper( 3244): notifyPeerAvailability: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280] is available
,I/jxcore-log( 3244): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:34:8A:A0","peerName":"samsung-SM-G900F_PT8280","peerAvailable":true}]
I/jxcore-log( 3244): 
I/jxcore-log( 3244): Found peer : samsung-SM-G900F_PT8280, Available: true
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): startWithNextDevice
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): device[9]: 7C:F9:0E:34:8A:A0
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:05:05.239Z SendDataConnector.js: Start called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:05:05.247Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3244): 
I/jxcore-log( 3244): 2015-12-18T18:05:05.247Z SendDataConnector.js: do connect now
I/jxcore-log( 3244): 
I/io.jxcore.node.ConnectionHelper( 3244): connect: Trying to connect to peer with ID 7C:F9:0E:34:8A:A0
D/io.jxcore.node.ConnectionHelper( 3244): hasConnection: No connection with peer with ID 7C:F9:0E:34:8A:A0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3244): connect: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3244): connect: Trying to start connecting to null in address 7C:F9:0E:34:8A:A0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3244): onConnecting: null 7C:F9:0E:34:8A:A0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3244): connect: Started connecting to null in address 7C:F9:0E:34:8A:A0
I/io.jxcore.node.ConnectionHelper( 3244): connect: Connection process successfully started (peer ID: 7C:F9:0E:34:8A:A0)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): Trying to connect to peer with address 7C:F9:0E:34:8A:A0 (thread ID: 374)
W/BluetoothAdapter( 3244): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2094): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2094): info:x10
,D/        ( 2094): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,E/BluetoothRemoteDevices( 2094): aclStateChangeCallback: Device is NULL
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1532","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
I/io.jxcore.node.ConnectionHelper( 3244): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 3244): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT633","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onServiceDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Adding new peer: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633]
I/io.jxcore.node.ConnectionHelper( 3244): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
D/io.jxcore.node.ConnectionHelper( 3244): notifyPeerAvailability: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633] is available
I/jxcore-log( 3244): peerAvailabilityChanged [{"peerIdentifier":"B0:C5:59:3F:75:69","peerName":"samsung-SM-G900F_PT633","peerAvailable":true}]
I/jxcore-log( 3244): 
,W/bt-sdp  ( 2094): process_service_search_attr_rsp
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT8213","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
I/io.jxcore.node.ConnectionHelper( 3244): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
D/io.jxcore.node.ConnectionHelper( 3244): notifyPeerAvailability: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8213] is available
,I/jxcore-log( 3244): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:85:54","peerName":"LGE-LG-D722_PT8213","peerAvailable":true}]
I/jxcore-log( 3244): 
,I/BluetoothBondStateMachine( 2094): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 1
E/bt-btif ( 2094): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2094): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2094): Entering PendingCommandState State
,W/BluetoothEventManager( 2726): CachedBluetoothDevice for device 7C:F9:0E:34:8A:A0 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2726): Got bonding state changed for 7C:F9:0E:34:8A:A0, but we have no record of that device.
,I/BluetoothBondStateMachine( 2094): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 0
,D/BluetoothAdapterProperties( 2094): Failed to remove device: 7C:F9:0E:34:8A:A0
,I/BluetoothBondStateMachine( 2094): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2094): StableState(): Entering Off State
,W/BluetoothEventManager( 2726): CachedBluetoothDevice for device 7C:F9:0E:34:8A:A0 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2726): Got bonding state changed for 7C:F9:0E:34:8A:A0, but we have no record of that device.
,W/bt-btif ( 2094): new conn_srvc id:26, app_id:1
W/bt-btif ( 2094): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2094): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3244): onSocketConnected: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 374)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): onBytesWritten: 77 bytes successfully written (thread ID: 375)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): Outgoing connection initialized (*handshake* thread ID: 375)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): Exiting thread (thread ID: 374)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3244): Entering thread (ID: 375)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): onBytesRead: Read 82 bytes successfully (thread ID: 375)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): Handshake succeeded with [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3244): onHandshakeSucceeded: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3244): Exiting thread (ID: 375)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3244): onConnected: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280]
I/io.jxcore.node.ConnectionHelper( 3244): onConnected: Outgoing connection to peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280]
D/io.jxcore.node.ConnectionHelper( 3244): hasConnection: No connection with peer with ID 7C:F9:0E:34:8A:A0
W/io.jxcore.node.ConnectionHelper( 3244): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 3244): onConnected: Outgoing socket thread, for peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3244): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 3244): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 3244): Entering thread (ID: 376)
,D/io.jxcore.node.OutgoingSocketThread( 3244): Server socket local port: 56837
I/io.jxcore.node.OutgoingSocketThread( 3244): Now accepting connections...
,W/bt-btif ( 2094): new conn_srvc id:26, app_id:255
W/bt-btif ( 2094): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2094): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2094): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3244): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3244): Incoming connection initialized (thread ID: 377)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3244): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3244): Entering thread (ID: 377)
,I/io.jxcore.node.ConnectionHelper( 3244): onListeningForIncomingConnections: Outgoing connection is using port 56837 (peer ID: 7C:F9:0E:34:8A:A0)
,I/jxcore-log( 3244): 2015-12-18T18:05:07.331Z SendDataConnector.js: CLIENT connected to 56837, error: null
I/jxcore-log( 3244): 
I/jxcore-log( 3244): 2015-12-18T18:05:07.332Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3244): 
,I/io.jxcore.node.OutgoingSocketThread( 3244): Incoming data from address: /127.0.0.1, port: 56837
D/io.jxcore.node.OutgoingSocketThread( 3244): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3244): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3244): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3244): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3244): Exiting thread (ID: 376)
,I/jxcore-log( 3244): 2015-12-18T18:05:07.354Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3244): 
,D/io.jxcore.node.StreamCopyingThread( 3244): Entering thread (ID: 378, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 3244): Entering thread (ID: 379, name: Receiver)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3244): onBytesRead: Read 82 bytes successfully (thread ID: 377)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3244): Got valid identity from [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3244): onBytesWritten: 77 bytes successfully written (thread ID: 377)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3244): removeThreadFromList: Removing thread with ID 377
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3244): Handshake thread disposed (thread ID: 377)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3244): onIncomingConnectionConnected: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3244): Exiting thread (ID: 377)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3244): onConnected: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280]
I/io.jxcore.node.ConnectionHelper( 3244): onConnected: Incoming connection to peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280]
D/io.jxcore.node.ConnectionHelper( 3244): hasConnection: We have an outgoing connection with peer with ID 7C:F9:0E:34:8A:A0
W/io.jxcore.node.ConnectionHelper( 3244): onConnected: Already connected with peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280], continuing anyway...
W/io.jxcore.node.ConnectionHelper( 3244): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 3244): onConnected: Incoming socket thread, for peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280], created successfully
D/io.jxcore.node.ConnectionHelper( 3244): onConnected: The total number of connections is now 2
,D/io.jxcore.node.IncomingSocketThread( 3244): Entering thread (ID: 380)
,I/io.jxcore.node.IncomingSocketThread( 3244): Local host address: localhost/127.0.0.1, port: 32844
,D/io.jxcore.node.IncomingSocketThread( 3244): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3244): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3244): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.IncomingSocketThread( 3244): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3244): Exiting thread (ID: 380)
,I/jxcore-log( 3244): 2015-12-18T18:05:07.788Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3244): 
D/io.jxcore.node.StreamCopyingThread( 3244): Entering thread (ID: 381, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 3244): Entering thread (ID: 382, name: Receiver)
,I/jxcore-log( 3244): 2015-12-18T18:05:08.465Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:05:08.475Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:05:08.485Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:05:08.493Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:05:08.499Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:05:08.509Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:05:08.547Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:05:08.577Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:05:08.590Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:05:08.603Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:05:08.610Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3244): 
I/jxcore-log( 3244): 2015-12-18T18:05:08.612Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:05:08.622Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:05:08.710Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:05:08.781Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:05:08.804Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:05:08.880Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:05:08.928Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:05:08.936Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:05:08.943Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:05:09.005Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:05:09.010Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:05:09.015Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:05:09.065Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3244): 
I/jxcore-log( 3244): 2015-12-18T18:05:09.066Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3244): 
I/jxcore-log( 3244): oneRoundDownNow
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:05:09.067Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3244): 
I/jxcore-log( 3244): 2015-12-18T18:05:09.068Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3244): 
D/io.jxcore.node.ConnectionHelper( 3244): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:34:8A:A0
I/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 7C:F9:0E:34:8A:A0
I/io.jxcore.node.IncomingSocketThread( 3244): close
D/io.jxcore.node.IncomingSocketThread( 3244): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3244): doStop: Thread ID: 379
D/io.jxcore.node.IncomingSocketThread( 3244): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3244): doStop: Thread ID: 378
D/io.jxcore.node.IncomingSocketThread( 3244): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 3244): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3244): Either failed to read from the output stream or write to the input stream (thread ID: 378, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3244): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3244): onDisconnected: Outgoing connection, peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.IncomingSocketThread( 3244): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 3244): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3244): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3244): Either failed to read from the output stream or write to the input stream (thread ID: 379, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 3244): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3244): onDisconnected: Outgoing connection, peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3244): disconnectOutgoingConnection: Successfully disconnected (peer ID: 7C:F9:0E:34:8A:A0
,E/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:34:8A:A0
D/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3244): Exiting thread (ID: 378, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:34:8A:A0
,D/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,D/io.jxcore.node.StreamCopyingThread( 3244): Exiting thread (ID: 379, name: Receiver)
,I/jxcore-log( 3244): 2015-12-18T18:05:09.121Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): ---- round done--------
I/jxcore-log( 3244): 
I/jxcore-log( 3244): startWithNextDevice
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:05:09.132Z SendDataTCPServer.js: TCP/IP server has received 34748 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:05:09.156Z SendDataTCPServer.js: TCP/IP server has received 36728 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:05:09.159Z SendDataTCPServer.js: TCP/IP server has received 38708 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:05:09.163Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:05:09.171Z SendDataTCPServer.js: TCP/IP server has received 42668 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:05:09.292Z SendDataTCPServer.js: TCP/IP server has received 44648 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:05:09.300Z SendDataTCPServer.js: TCP/IP server has received 46628 bytes of data
I/jxcore-log( 3244): 
,W/bt-btif ( 2094): bta_jv_rfc_port_to_cb(port_handle:0x19):jv handle:0x0 not FOUND
,I/jxcore-log( 3244): 2015-12-18T18:05:09.304Z SendDataTCPServer.js: TCP/IP server has received 48608 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:05:09.339Z SendDataTCPServer.js: TCP/IP server has received 50588 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:05:09.398Z SendDataTCPServer.js: TCP/IP server has received 52568 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:05:09.427Z SendDataTCPServer.js: TCP/IP server has received 54548 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:05:09.480Z SendDataTCPServer.js: TCP/IP server has received 56528 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:05:09.537Z SendDataTCPServer.js: TCP/IP server has received 58508 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:05:09.565Z SendDataTCPServer.js: TCP/IP server has received 60488 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:05:09.618Z SendDataTCPServer.js: TCP/IP server has received 62468 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:05:09.627Z SendDataTCPServer.js: TCP/IP server has received 66428 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:05:09.654Z SendDataTCPServer.js: TCP/IP server has received 68408 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:05:09.657Z SendDataTCPServer.js: TCP/IP server has received 70388 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:05:09.665Z SendDataTCPServer.js: TCP/IP server has received 72368 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:05:09.696Z SendDataTCPServer.js: TCP/IP server has received 86228 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:05:09.703Z SendDataTCPServer.js: TCP/IP server has received 88208 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:05:09.707Z SendDataTCPServer.js: TCP/IP server has received 90188 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:05:09.747Z SendDataTCPServer.js: TCP/IP server has received 92168 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:05:09.811Z SendDataTCPServer.js: TCP/IP server has received 94148 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:05:09.815Z SendDataTCPServer.js: TCP/IP server has received 96128 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:05:09.823Z SendDataTCPServer.js: TCP/IP server has received 98108 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:05:09.831Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3244): 
,W/bt-btif ( 2094): invalid rfc slot id: 22
,W/io.jxcore.node.StreamCopyingThread( 3244): Either failed to read from the output stream or write to the input stream (thread ID: 382, thread name: Receiver): bt socket closed, read return: -1,
E/io.jxcore.node.IncomingSocketThread( 3244): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3244): onDisconnected: Incoming connection, peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 380
D/io.jxcore.node.IncomingSocketThread( 3244): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3244): doStop: Thread ID: 382
D/io.jxcore.node.IncomingSocketThread( 3244): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3244): doStop: Thread ID: 381
D/io.jxcore.node.IncomingSocketThread( 3244): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 3244): closeLocalSocketAndStreams: Closing the local input stream...
D/io.jxcore.node.IncomingSocketThread( 3244): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 3244): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3244): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,W/io.jxcore.node.StreamCopyingThread( 3244): Either failed to read from the output stream or write to the input stream (thread ID: 381, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3244): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3244): onDisconnected: Incoming connection, peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3244): Exiting thread (ID: 381, name: Sender)
D/io.jxcore.node.StreamCopyingThread( 3244): Exiting thread (ID: 382, name: Receiver)
I/jxcore-log( 3244): 2015-12-18T18:05:09.983Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3244): 
,D/btif_config_util( 2094): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2094): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2094): onReceive
,I/BTConnectionReceiver( 1405): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1405): Bluetooth Device Name: S5-1
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT5572","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572]
I/io.jxcore.node.ConnectionHelper( 3244): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572], Bluetooth address: 08:EC:A9:50:75:41, device name: , device address: 0a:ec:a9:50:75:42
D/io.jxcore.node.ConnectionHelper( 3244): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572] is available
,I/jxcore-log( 3244): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:75:41","peerName":"samsung-SM-A300FU_PT5572","peerAvailable":true}]
I/jxcore-log( 3244): 
I/jxcore-log( 3244): startWithNextDevice
I/jxcore-log( 3244): 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): restart: Restarting...
,D/WifiP2pManager( 3244): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service request added successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service discovery started successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633]
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  984): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT6460","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onServiceDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Adding new peer: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460]
I/io.jxcore.node.ConnectionHelper( 3244): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460], Bluetooth address: E0:DB:10:14:E2:C0, device name: Note4-1, device address: 92:b6:86:43:73:1c
D/io.jxcore.node.ConnectionHelper( 3244): notifyPeerAvailability: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460] is available
I/jxcore-log( 3244): peerAvailabilityChanged [{"peerIdentifier":"E0:DB:10:14:E2:C0","peerName":"samsung-SM-N910C_PT6460","peerAvailable":true}]
I/jxcore-log( 3244): 
I/jxcore-log( 3244): Found peer : samsung-SM-N910C_PT6460, Available: true
I/jxcore-log( 3244): 
I/jxcore-log( 3244): startWithNextDevice
I/jxcore-log( 3244): 
I/jxcore-log( 3244): device[10]: E0:DB:10:14:E2:C0
I/jxcore-log( 3244): 
I/jxcore-log( 3244): 2015-12-18T18:05:20.199Z SendDataConnector.js: Start called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3244): 
I/jxcore-log( 3244): 2015-12-18T18:05:20.199Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3244): 
I/jxcore-log( 3244): 2015-12-18T18:05:20.199Z SendDataConnector.js: do connect now
I/jxcore-log( 3244): 
I/io.jxcore.node.ConnectionHelper( 3244): connect: Trying to connect to peer with ID E0:DB:10:14:E2:C0
D/io.jxcore.node.ConnectionHelper( 3244): hasConnection: No connection with peer with ID E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3244): connect: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3244): connect: Trying to start connecting to null in address E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3244): onConnecting: null E0:DB:10:14:E2:C0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3244): connect: Started connecting to null in address E0:DB:10:14:E2:C0
I/io.jxcore.node.ConnectionHelper( 3244): connect: Connection process successfully started (peer ID: E0:DB:10:14:E2:C0)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): Trying to connect to peer with address E0:DB:10:14:E2:C0 (thread ID: 383)
W/BluetoothAdapter( 3244): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2094): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2094): info:x10
,D/        ( 2094): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,E/BluetoothRemoteDevices( 2094): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2094): process_service_search_attr_rsp
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BluetoothBondStateMachine( 2094): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 1
E/bt-btif ( 2094): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2094): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 2094): Entering PendingCommandState State
,W/BluetoothEventManager( 2726): CachedBluetoothDevice for device E0:DB:10:14:E2:C0 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2726): Got bonding state changed for E0:DB:10:14:E2:C0, but we have no record of that device.
,I/BluetoothBondStateMachine( 2094): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 0
,D/BluetoothAdapterProperties( 2094): Failed to remove device: E0:DB:10:14:E2:C0
,I/BluetoothBondStateMachine( 2094): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2094): StableState(): Entering Off State
,W/BluetoothEventManager( 2726): CachedBluetoothDevice for device E0:DB:10:14:E2:C0 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2726): Got bonding state changed for E0:DB:10:14:E2:C0, but we have no record of that device.
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2094): new conn_srvc id:26, app_id:1
W/bt-btif ( 2094): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2094): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3244): onSocketConnected: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 383)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): onBytesWritten: 77 bytes successfully written (thread ID: 384)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): Outgoing connection initialized (*handshake* thread ID: 384)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): Exiting thread (thread ID: 383)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3244): Entering thread (ID: 384)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): onBytesRead: Read 82 bytes successfully (thread ID: 384)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): Handshake succeeded with [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3244): onHandshakeSucceeded: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3244): Exiting thread (ID: 384)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3244): onConnected: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460]
,I/io.jxcore.node.ConnectionHelper( 3244): onConnected: Outgoing connection to peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460]
D/io.jxcore.node.ConnectionHelper( 3244): hasConnection: No connection with peer with ID E0:DB:10:14:E2:C0
W/io.jxcore.node.ConnectionHelper( 3244): modifyListOfDiscoveredPeers: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460] already in the list, will not add again
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/io.jxcore.node.ConnectionHelper( 3244): onConnected: Outgoing socket thread, for peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3244): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 3244): onConnected: The total number of connections is now 1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633]
,D/io.jxcore.node.OutgoingSocketThread( 3244): Entering thread (ID: 385)
D/io.jxcore.node.OutgoingSocketThread( 3244): Server socket local port: 32860
I/io.jxcore.node.OutgoingSocketThread( 3244): Now accepting connections...
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/io.jxcore.node.ConnectionHelper( 3244): onListeningForIncomingConnections: Outgoing connection is using port 32860 (peer ID: E0:DB:10:14:E2:C0)
I/jxcore-log( 3244): 2015-12-18T18:05:23.068Z SendDataConnector.js: CLIENT connected to 32860, error: null
I/jxcore-log( 3244): 
I/jxcore-log( 3244): 2015-12-18T18:05:23.068Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3244): 
,I/io.jxcore.node.OutgoingSocketThread( 3244): Incoming data from address: /127.0.0.1, port: 32860
D/io.jxcore.node.OutgoingSocketThread( 3244): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3244): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3244): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3244): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3244): Exiting thread (ID: 385)
,D/io.jxcore.node.StreamCopyingThread( 3244): Entering thread (ID: 387, name: Receiver)
,I/jxcore-log( 3244): 2015-12-18T18:05:23.107Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3244): 
,D/io.jxcore.node.StreamCopyingThread( 3244): Entering thread (ID: 386, name: Sender)
,W/bt-btif ( 2094): new conn_srvc id:26, app_id:255
W/bt-btif ( 2094): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2094): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2094): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3244): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3244): Incoming connection initialized (thread ID: 388)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3244): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3244): Entering thread (ID: 388)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3244): onBytesRead: Read 82 bytes successfully (thread ID: 388)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3244): Got valid identity from [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3244): onBytesWritten: 77 bytes successfully written (thread ID: 388)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3244): removeThreadFromList: Removing thread with ID 388
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3244): Handshake thread disposed (thread ID: 388)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3244): onIncomingConnectionConnected: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3244): Exiting thread (ID: 388)
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3244): onConnected: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460]
I/io.jxcore.node.ConnectionHelper( 3244): onConnected: Incoming connection to peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460]
D/io.jxcore.node.ConnectionHelper( 3244): hasConnection: We have an outgoing connection with peer with ID E0:DB:10:14:E2:C0
,W/io.jxcore.node.ConnectionHelper( 3244): onConnected: Already connected with peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460], continuing anyway...
,W/io.jxcore.node.ConnectionHelper( 3244): modifyListOfDiscoveredPeers: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 3244): onConnected: Incoming socket thread, for peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460], created successfully
D/io.jxcore.node.ConnectionHelper( 3244): onConnected: The total number of connections is now 2
D/io.jxcore.node.IncomingSocketThread( 3244): Entering thread (ID: 389)
,I/io.jxcore.node.IncomingSocketThread( 3244): Local host address: localhost/127.0.0.1, port: 32844
D/io.jxcore.node.IncomingSocketThread( 3244): Setting local streams and starting stream copying threads...
,I/io.jxcore.node.StreamCopyingThread( 3244): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3244): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3244): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3244): Exiting thread (ID: 389)
,I/jxcore-log( 3244): 2015-12-18T18:05:23.546Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3244): 
,D/io.jxcore.node.StreamCopyingThread( 3244): Entering thread (ID: 390, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 3244): Entering thread (ID: 391, name: Receiver)
,I/jxcore-log( 3244): 2015-12-18T18:05:23.660Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3244): 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633]
,I/jxcore-log( 3244): 2015-12-18T18:05:24.358Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3244): 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3244): 2015-12-18T18:05:24.491Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:05:24.628Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:05:24.779Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:05:24.849Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:05:24.931Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:05:24.983Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:05:25.019Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:05:25.034Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:05:25.054Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:05:25.060Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:05:25.096Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:05:25.103Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3244): 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3244): 2015-12-18T18:05:25.170Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:05:25.189Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:05:25.409Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:05:25.420Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:05:25.457Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 3244): 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3244): 2015-12-18T18:05:25.582Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:05:25.630Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3244): 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3244): 2015-12-18T18:05:26.054Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:05:26.143Z SendDataTCPServer.js: TCP/IP server has received 35640 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:05:26.242Z SendDataTCPServer.js: TCP/IP server has received 37620 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:05:26.267Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3244): 
I/jxcore-log( 3244): 2015-12-18T18:05:26.267Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3244): 
I/jxcore-log( 3244): oneRoundDownNow
I/jxcore-log( 3244): 
I/jxcore-log( 3244): 2015-12-18T18:05:26.269Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3244): 
I/jxcore-log( 3244): 2015-12-18T18:05:26.269Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3244): 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/io.jxcore.node.ConnectionHelper( 3244): disconnectOutgoingConnection: Trying to close connection to peer with ID E0:DB:10:14:E2:C0
I/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: E0:DB:10:14:E2:C0
,I/io.jxcore.node.IncomingSocketThread( 3244): close
D/io.jxcore.node.IncomingSocketThread( 3244): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3244): doStop: Thread ID: 387
D/io.jxcore.node.IncomingSocketThread( 3244): close: Stopping sending thread...,
I/io.jxcore.node.StreamCopyingThread( 3244): doStop: Thread ID: 386
D/io.jxcore.node.IncomingSocketThread( 3244): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 3244): closeLocalSocketAndStreams: Closing the local input stream...
W/io.jxcore.node.StreamCopyingThread( 3244): Either failed to read from the output stream or write to the input stream (thread ID: 386, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3244): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3244): onDisconnected: Outgoing connection, peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.IncomingSocketThread( 3244): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 3244): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3244): closeBluetoothSocketAndStreams
W/io.jxcore.node.StreamCopyingThread( 3244): Either failed to read from the output stream or write to the input stream (thread ID: 387, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 3244): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3244): onDisconnected: Outgoing connection, peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3244): disconnectOutgoingConnection: Successfully disconnected (peer ID: E0:DB:10:14:E2:C0
E/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID E0:DB:10:14:E2:C0
D/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3244): Exiting thread (ID: 386, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID E0:DB:10:14:E2:C0
D/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3244): Exiting thread (ID: 387, name: Receiver)
,I/jxcore-log( 3244): 2015-12-18T18:05:26.297Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3244): 
I/jxcore-log( 3244): ---- round done--------
I/jxcore-log( 3244): 
I/jxcore-log( 3244): startWithNextDevice
I/jxcore-log( 3244): 
I/jxcore-log( 3244): 2015-12-18T18:05:26.298Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:05:26.320Z SendDataTCPServer.js: TCP/IP server has received 45540 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:05:26.356Z SendDataTCPServer.js: TCP/IP server has received 47520 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:05:26.363Z SendDataTCPServer.js: TCP/IP server has received 49500 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:05:26.377Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:05:26.381Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 3244): 
,W/bt-btif ( 2094): bta_jv_rfc_port_to_cb(port_handle:0x1b):jv handle:0x0 not FOUND
,I/jxcore-log( 3244): 2015-12-18T18:05:26.416Z SendDataTCPServer.js: TCP/IP server has received 71280 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:05:26.420Z SendDataTCPServer.js: TCP/IP server has received 73260 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:05:26.423Z SendDataTCPServer.js: TCP/IP server has received 75240 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:05:26.456Z SendDataTCPServer.js: TCP/IP server has received 81180 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:05:26.469Z SendDataTCPServer.js: TCP/IP server has received 83160 bytes of data
I/jxcore-log( 3244): 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): restart: Restarting...
,I/jxcore-log( 3244): 2015-12-18T18:05:26.509Z SendDataTCPServer.js: TCP/IP server has received 85140 bytes of data
I/jxcore-log( 3244): 
D/WifiP2pManager( 3244): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service request added successfully
,I/jxcore-log( 3244): 2015-12-18T18:05:26.522Z SendDataTCPServer.js: TCP/IP server has received 87120 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:05:26.582Z SendDataTCPServer.js: TCP/IP server has received 89100 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:05:26.610Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:05:26.704Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 3244): 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3244): 2015-12-18T18:05:26.737Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3244): 
,W/bt-btif ( 2094): invalid rfc slot id: 24
,W/io.jxcore.node.StreamCopyingThread( 3244): Either failed to read from the output stream or write to the input stream (thread ID: 391, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 3244): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3244): onDisconnected: Incoming connection, peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 389
D/io.jxcore.node.IncomingSocketThread( 3244): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3244): doStop: Thread ID: 391
D/io.jxcore.node.IncomingSocketThread( 3244): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3244): doStop: Thread ID: 390
D/io.jxcore.node.IncomingSocketThread( 3244): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 3244): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3244): Either failed to read from the output stream or write to the input stream (thread ID: 390, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3244): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3244): onDisconnected: Incoming connection, peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.IncomingSocketThread( 3244): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 3244): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3244): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3244): Exiting thread (ID: 391, name: Receiver)
,D/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3244): Exiting thread (ID: 390, name: Sender)
,I/jxcore-log( 3244): 2015-12-18T18:05:26.862Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3244): 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/btif_config_util( 2094): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service discovery started successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633]
,E/bt-btm  ( 2094): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2094): onReceive
,I/BTConnectionReceiver( 1405): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1405): Bluetooth Device Name: Note4-1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): setState: RESTARTING
,I/wpa_supplicant(  984): P2P-FIND-STOPPED 
,I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): Start timer timeout, starting now...
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  984): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
,D/WifiP2pManager( 3244): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service request added successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service discovery started successfully
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT3826","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
I/io.jxcore.node.ConnectionHelper( 3244): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
W/io.jxcore.node.ConnectionHelper( 3244): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826] already in the list, will not add again
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1532","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
I/io.jxcore.node.ConnectionHelper( 3244): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532], Bluetooth address: 7C:F9:0E:37:96:AB, device name: , device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 3244): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532] already in the list, will not add again
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): restart: Restarting...
,D/WifiP2pManager( 3244): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service request added successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633]
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): checkListForExpiredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8213] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Removed [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
I/io.jxcore.node.ConnectionHelper( 3244): onPeerLost: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
D/io.jxcore.node.ConnectionHelper( 3244): hasConnection: No connection with peer with ID F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 3244): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8213] removed
D/io.jxcore.node.ConnectionHelper( 3244): notifyPeerAvailability: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8213] not available
,I/jxcore-log( 3244): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:85:54","peerName":"LGE-LG-D722_PT8213","peerAvailable":false}]
I/jxcore-log( 3244): 
I/jxcore-log( 3244): startWithNextDevice
I/jxcore-log( 3244): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): setState: RESTARTING
,I/wpa_supplicant(  984): P2P-FIND-STOPPED 
,I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): P2P device discovery started successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
,D/WifiP2pManager( 3244): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service request added successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  984): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service discovery started successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8280","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280]
I/io.jxcore.node.ConnectionHelper( 3244): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
W/io.jxcore.node.ConnectionHelper( 3244): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1532","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
I/io.jxcore.node.ConnectionHelper( 3244): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 3244): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532] already in the list, will not add again
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  984): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  984): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 3244): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service request added successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service discovery started successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  984): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT589","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT589]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT589]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT589]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT589], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT589]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/io.jxcore.node.ConnectionHelper( 3244): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT589], Bluetooth address: 58:3F:54:73:64:C0, device name: , device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper( 3244): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT589] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT8213","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
I/io.jxcore.node.ConnectionHelper( 3244): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
D/io.jxcore.node.ConnectionHelper( 3244): notifyPeerAvailability: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8213] is available
I/jxcore-log( 3244): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:85:54","peerName":"LGE-LG-D722_PT8213","peerAvailable":true}]
I/jxcore-log( 3244): 
I/jxcore-log( 3244): startWithNextDevice
I/jxcore-log( 3244): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8280","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280]
I/io.jxcore.node.ConnectionHelper( 3244): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
,W/io.jxcore.node.ConnectionHelper( 3244): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT633","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onServiceDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Adding new peer: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633]
,I/io.jxcore.node.ConnectionHelper( 3244): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
,W/io.jxcore.node.ConnectionHelper( 3244): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT6460","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onServiceDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Adding new peer: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460]
I/io.jxcore.node.ConnectionHelper( 3244): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460], Bluetooth address: E0:DB:10:14:E2:C0, device name: Note4-1, device address: 92:b6:86:43:73:1c
W/io.jxcore.node.ConnectionHelper( 3244): modifyListOfDiscoveredPeers: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1532","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
I/io.jxcore.node.ConnectionHelper( 3244): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 3244): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532] already in the list, will not add again
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9219","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219]
I/io.jxcore.node.ConnectionHelper( 3244): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: a2:39:f7:6f:c9:5d
D/io.jxcore.node.ConnectionHelper( 3244): notifyPeerAvailability: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219] is available
I/jxcore-log( 3244): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:3C:51","peerName":"LGE-LG-H815_PT9219","peerAvailable":true}]
I/jxcore-log( 3244): 
I/jxcore-log( 3244): Found peer : LGE-LG-H815_PT9219, Available: true
I/jxcore-log( 3244): 
I/jxcore-log( 3244): startWithNextDevice
I/jxcore-log( 3244): 
I/jxcore-log( 3244): device[11]: F8:95:C7:87:3C:51
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:07:27.513Z SendDataConnector.js: Start called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3244): 
I/jxcore-log( 3244): 2015-12-18T18:07:27.514Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3244): 
I/jxcore-log( 3244): 2015-12-18T18:07:27.515Z SendDataConnector.js: do connect now
I/jxcore-log( 3244): 
,I/io.jxcore.node.ConnectionHelper( 3244): connect: Trying to connect to peer with ID F8:95:C7:87:3C:51
D/io.jxcore.node.ConnectionHelper( 3244): hasConnection: No connection with peer with ID F8:95:C7:87:3C:51
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3244): connect: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3244): connect: Trying to start connecting to null in address F8:95:C7:87:3C:51
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3244): onConnecting: null F8:95:C7:87:3C:51
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3244): connect: Started connecting to null in address F8:95:C7:87:3C:51
I/io.jxcore.node.ConnectionHelper( 3244): connect: Connection process successfully started (peer ID: F8:95:C7:87:3C:51)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): Trying to connect to peer with address F8:95:C7:87:3C:51 (thread ID: 392)
W/BluetoothAdapter( 3244): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2094): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2094): info:x10
,D/        ( 2094): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,E/BluetoothRemoteDevices( 2094): aclStateChangeCallback: Device is NULL
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT3826","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
,I/io.jxcore.node.ConnectionHelper( 3244): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826], Bluetooth address: 7C:F9:0E:51:18:22, device name: , device address: 7e:f9:0e:51:18:23
W/io.jxcore.node.ConnectionHelper( 3244): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826] already in the list, will not add again
,W/bt-sdp  ( 2094): process_service_search_attr_rsp
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BluetoothBondStateMachine( 2094): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
E/bt-btif ( 2094): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2094): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2094): Entering PendingCommandState State
,W/BluetoothEventManager( 2726): CachedBluetoothDevice for device F8:95:C7:87:3C:51 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2726): Got bonding state changed for F8:95:C7:87:3C:51, but we have no record of that device.
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): restart: Restarting...
,D/WifiP2pManager( 3244): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service request added successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BluetoothBondStateMachine( 2094): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,D/BluetoothAdapterProperties( 2094): Failed to remove device: F8:95:C7:87:3C:51
,W/BluetoothEventManager( 2726): CachedBluetoothDevice for device F8:95:C7:87:3C:51 not found, calling readPairedDevices().
,I/BluetoothBondStateMachine( 2094): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2094): StableState(): Entering Off State
,E/BluetoothEventManager( 2726): Got bonding state changed for F8:95:C7:87:3C:51, but we have no record of that device.
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2094): new conn_srvc id:26, app_id:1
W/bt-btif ( 2094): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2094): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3244): onSocketConnected: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 392)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): onBytesWritten: 77 bytes successfully written (thread ID: 393)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): Outgoing connection initialized (*handshake* thread ID: 393)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): Exiting thread (thread ID: 392)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3244): Entering thread (ID: 393)
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): onBytesRead: Read 77 bytes successfully (thread ID: 393)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3244): Handshake succeeded with [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3244): onHandshakeSucceeded: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3244): Exiting thread (ID: 393)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3244): onConnected: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219]
I/io.jxcore.node.ConnectionHelper( 3244): onConnected: Outgoing connection to peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219]
D/io.jxcore.node.ConnectionHelper( 3244): hasConnection: No connection with peer with ID F8:95:C7:87:3C:51
W/io.jxcore.node.ConnectionHelper( 3244): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 3244): onConnected: Outgoing socket thread, for peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3244): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 3244): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 3244): Entering thread (ID: 394)
D/io.jxcore.node.OutgoingSocketThread( 3244): Server socket local port: 54603
I/io.jxcore.node.OutgoingSocketThread( 3244): Now accepting connections...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service discovery started successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/io.jxcore.node.ConnectionHelper( 3244): onListeningForIncomingConnections: Outgoing connection is using port 54603 (peer ID: F8:95:C7:87:3C:51)
I/jxcore-log( 3244): 2015-12-18T18:07:30.763Z SendDataConnector.js: CLIENT connected to 54603, error: null
I/jxcore-log( 3244): 
I/jxcore-log( 3244): 2015-12-18T18:07:30.763Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3244): 
,I/io.jxcore.node.OutgoingSocketThread( 3244): Incoming data from address: /127.0.0.1, port: 54603
D/io.jxcore.node.OutgoingSocketThread( 3244): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3244): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3244): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3244): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3244): Exiting thread (ID: 394)
,D/io.jxcore.node.StreamCopyingThread( 3244): Entering thread (ID: 395, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 3244): Entering thread (ID: 396, name: Receiver)
,I/jxcore-log( 3244): 2015-12-18T18:07:30.800Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3244): 
,W/bt-btif ( 2094): new conn_srvc id:26, app_id:255
W/bt-btif ( 2094): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2094): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2094): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3244): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3244): Incoming connection initialized (thread ID: 397)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3244): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3244): Entering thread (ID: 397)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3244): onBytesRead: Read 77 bytes successfully (thread ID: 397)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3244): Got valid identity from [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3244): onBytesWritten: 77 bytes successfully written (thread ID: 397)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3244): removeThreadFromList: Removing thread with ID 397
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3244): Handshake thread disposed (thread ID: 397)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3244): onIncomingConnectionConnected: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3244): Exiting thread (ID: 397)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3244): onConnected: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219]
I/io.jxcore.node.ConnectionHelper( 3244): onConnected: Incoming connection to peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219]
D/io.jxcore.node.ConnectionHelper( 3244): hasConnection: We have an outgoing connection with peer with ID F8:95:C7:87:3C:51
W/io.jxcore.node.ConnectionHelper( 3244): onConnected: Already connected with peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219], continuing anyway...
W/io.jxcore.node.ConnectionHelper( 3244): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 3244): onConnected: Incoming socket thread, for peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219], created successfully
D/io.jxcore.node.ConnectionHelper( 3244): onConnected: The total number of connections is now 2
,D/io.jxcore.node.IncomingSocketThread( 3244): Entering thread (ID: 398)
,I/io.jxcore.node.IncomingSocketThread( 3244): Local host address: localhost/127.0.0.1, port: 32844
D/io.jxcore.node.IncomingSocketThread( 3244): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3244): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 3244): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3244): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3244): Exiting thread (ID: 398)
,D/io.jxcore.node.StreamCopyingThread( 3244): Entering thread (ID: 400, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3244): Entering thread (ID: 399, name: Sender)
,I/jxcore-log( 3244): 2015-12-18T18:07:31.191Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:07:31.299Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:07:31.377Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:07:31.736Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:07:31.743Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:07:31.752Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:07:31.759Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:07:31.813Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data,
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:07:31.827Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:07:31.857Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:07:31.880Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:07:31.888Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:07:31.904Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:07:31.916Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:07:31.933Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:07:31.970Z SendDataTCPServer.js: TCP/IP server has received 45540 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:07:31.989Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:07:31.990Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3244): 
I/jxcore-log( 3244): oneRoundDownNow
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:07:32.009Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3244): 
I/jxcore-log( 3244): 2015-12-18T18:07:32.010Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3244): 
D/io.jxcore.node.ConnectionHelper( 3244): disconnectOutgoingConnection: Trying to close connection to peer with ID F8:95:C7:87:3C:51
I/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: F8:95:C7:87:3C:51
I/io.jxcore.node.IncomingSocketThread( 3244): close
D/io.jxcore.node.IncomingSocketThread( 3244): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3244): doStop: Thread ID: 396
D/io.jxcore.node.IncomingSocketThread( 3244): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3244): doStop: Thread ID: 395
D/io.jxcore.node.IncomingSocketThread( 3244): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 3244): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3244): Either failed to read from the output stream or write to the input stream (thread ID: 395, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3244): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3244): onDisconnected: Outgoing connection, peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.IncomingSocketThread( 3244): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 3244): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3244): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3244): Either failed to read from the output stream or write to the input stream (thread ID: 396, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 3244): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3244): onDisconnected: Outgoing connection, peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3244): disconnectOutgoingConnection: Successfully disconnected (peer ID: F8:95:C7:87:3C:51
,E/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:95:C7:87:3C:51
D/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3244): Exiting thread (ID: 395, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:95:C7:87:3C:51
D/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3244): Exiting thread (ID: 396, name: Receiver)
,I/jxcore-log( 3244): 2015-12-18T18:07:32.033Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): ---- round done--------
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): startWithNextDevice
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:07:32.036Z SendDataTCPServer.js: TCP/IP server has received 57420 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:07:32.066Z SendDataTCPServer.js: TCP/IP server has received 59400 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:07:32.094Z SendDataTCPServer.js: TCP/IP server has received 61380 bytes of data
I/jxcore-log( 3244): 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 7 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219]
I/jxcore-log( 3244): 2015-12-18T18:07:32.432Z SendDataTCPServer.js: TCP/IP server has received 63360 bytes of data
I/jxcore-log( 3244): 
,W/bt-btif ( 2094): bta_jv_rfc_port_to_cb(port_handle:0x1d):jv handle:0x0 not FOUND
,I/jxcore-log( 3244): 2015-12-18T18:07:32.457Z SendDataTCPServer.js: TCP/IP server has received 75240 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:07:32.459Z SendDataTCPServer.js: TCP/IP server has received 77220 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:07:32.461Z SendDataTCPServer.js: TCP/IP server has received 79200 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:07:32.497Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:07:32.518Z SendDataTCPServer.js: TCP/IP server has received 95040 bytes of data
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:07:32.566Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3244): 
,W/bt-btif ( 2094): invalid rfc slot id: 26
,W/io.jxcore.node.StreamCopyingThread( 3244): Either failed to read from the output stream or write to the input stream (thread ID: 400, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 3244): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3244): onDisconnected: Incoming connection, peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 398
D/io.jxcore.node.IncomingSocketThread( 3244): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3244): doStop: Thread ID: 400
D/io.jxcore.node.IncomingSocketThread( 3244): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3244): doStop: Thread ID: 399
D/io.jxcore.node.IncomingSocketThread( 3244): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 3244): closeLocalSocketAndStreams: Closing the local input stream...
D/io.jxcore.node.IncomingSocketThread( 3244): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 3244): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3244): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3244): Exiting thread (ID: 400, name: Receiver)
,W/io.jxcore.node.StreamCopyingThread( 3244): Either failed to read from the output stream or write to the input stream (thread ID: 399, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3244): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3244): onDisconnected: Incoming connection, peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.ConnectionHelper( 3244): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3244): Exiting thread (ID: 399, name: Sender)
,I/jxcore-log( 3244): 2015-12-18T18:07:32.616Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3244): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9219","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219]
I/io.jxcore.node.ConnectionHelper( 3244): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3244): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219] already in the list, will not add again
,D/btif_config_util( 2094): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT3826","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
I/io.jxcore.node.ConnectionHelper( 3244): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826], Bluetooth address: 7C:F9:0E:51:18:22, device name: , device address: 7e:f9:0e:51:18:23
W/io.jxcore.node.ConnectionHelper( 3244): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826] already in the list, will not add again
,E/bt-btm  ( 2094): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2094): onReceive
,I/BTConnectionReceiver( 1405): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1405): Bluetooth Device Name: G4-1
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): restart: Restarting...
,D/WifiP2pManager( 3244): Ignored { when=-4ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service request added successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service discovery started successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9219","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219]
I/io.jxcore.node.ConnectionHelper( 3244): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3244): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT3826","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
I/io.jxcore.node.ConnectionHelper( 3244): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
W/io.jxcore.node.ConnectionHelper( 3244): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT589","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT589]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT589]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT589]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT589], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT589]
I/io.jxcore.node.ConnectionHelper( 3244): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT589], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper( 3244): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT589] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT8213","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
,I/io.jxcore.node.ConnectionHelper( 3244): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 3244): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8213] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8280","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280]
I/io.jxcore.node.ConnectionHelper( 3244): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
W/io.jxcore.node.ConnectionHelper( 3244): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): setState: RESTARTING
,I/wpa_supplicant(  984): P2P-FIND-STOPPED 
,I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): P2P device discovery started successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): restart: Restarting...
,D/WifiP2pManager( 3244): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service request added successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service discovery started successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT5572","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572]
,I/io.jxcore.node.ConnectionHelper( 3244): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572], Bluetooth address: 08:EC:A9:50:75:41, device name: , device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper( 3244): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572] already in the list, will not add again
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9219","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219]
I/io.jxcore.node.ConnectionHelper( 3244): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3244): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219] already in the list, will not add again
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT589], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT589]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): restart: Restarting...
,D/WifiP2pManager( 3244): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service discovery started successfully
,I/wpa_supplicant(  984): p2p0: P2P: Reject scan trigger since one is already pending
I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT589], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT589]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): restart: Restarting...
,D/WifiP2pManager( 3244): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service discovery started successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 4 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT589], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT589]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): restart: Restarting...
,D/WifiP2pManager( 3244): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service request added successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT589], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT589]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572]
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): checkListForExpiredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Removed [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280]
I/io.jxcore.node.ConnectionHelper( 3244): onPeerLost: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280]
D/io.jxcore.node.ConnectionHelper( 3244): hasConnection: No connection with peer with ID 7C:F9:0E:34:8A:A0
D/io.jxcore.node.ConnectionHelper( 3244): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280] removed
,D/io.jxcore.node.ConnectionHelper( 3244): notifyPeerAvailability: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280] not available
,I/jxcore-log( 3244): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:34:8A:A0","peerName":"samsung-SM-G900F_PT8280","peerAvailable":false}]
I/jxcore-log( 3244): 
I/jxcore-log( 3244): startWithNextDevice
I/jxcore-log( 3244): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT8213","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
I/io.jxcore.node.ConnectionHelper( 3244): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 3244): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8213] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1532","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
I/io.jxcore.node.ConnectionHelper( 3244): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 3244): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): setState: RESTARTING
,I/wpa_supplicant(  984): P2P-FIND-STOPPED 
,I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): P2P device discovery started successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): restart: Restarting...
,D/WifiP2pManager( 3244): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service request added successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  984): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT589], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT589]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT589], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT589]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572]
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service discovery started successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  984): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572]
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  984): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572]
,D/WifiP2pManager( 3244): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service request added successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service discovery started successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): setState: RESTARTING
,I/wpa_supplicant(  984): P2P-FIND-STOPPED 
,I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): Start timer timeout, starting now...
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  984): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3244): Ignored { when=-3ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service request added successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service discovery started successfully
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): checkListForExpiredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8213] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Removed [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
I/io.jxcore.node.ConnectionHelper( 3244): onPeerLost: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
D/io.jxcore.node.ConnectionHelper( 3244): hasConnection: No connection with peer with ID F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 3244): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8213] removed
D/io.jxcore.node.ConnectionHelper( 3244): notifyPeerAvailability: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8213] not available
I/jxcore-log( 3244): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:85:54","peerName":"LGE-LG-D722_PT8213","peerAvailable":false}]
I/jxcore-log( 3244): 
I/jxcore-log( 3244): startWithNextDevice
I/jxcore-log( 3244): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT589","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT589]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT589]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT589]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT589], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT589]
I/io.jxcore.node.ConnectionHelper( 3244): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT589], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper( 3244): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT589] already in the list, will not add again
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8280","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280]
I/io.jxcore.node.ConnectionHelper( 3244): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: , device address: ee:1f:72:63:11:86
D/io.jxcore.node.ConnectionHelper( 3244): notifyPeerAvailability: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280] is available
I/jxcore-log( 3244): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:34:8A:A0","peerName":"samsung-SM-G900F_PT8280","peerAvailable":true}]
I/jxcore-log( 3244): 
I/jxcore-log( 3244): startWithNextDevice
I/jxcore-log( 3244): 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  984): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT589], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT589]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT589], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT589]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3244): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service request added successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT589], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT589]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service discovery started successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  984): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT589], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT589]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT589], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT589]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT589], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT589]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT589], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT589]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT589], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT589]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT589], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT589]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1532","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
I/io.jxcore.node.ConnectionHelper( 3244): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 3244): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532] already in the list, will not add again
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT6460","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onServiceDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Adding new peer: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460]
I/io.jxcore.node.ConnectionHelper( 3244): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 92:b6:86:43:73:1c
W/io.jxcore.node.ConnectionHelper( 3244): modifyListOfDiscoveredPeers: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460] already in the list, will not add again
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT589], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT589]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): restart: Restarting...
,D/WifiP2pManager( 3244): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service request added successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT589], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT589]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT589], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT589]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service discovery started successfully
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT589], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT589]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1532","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
I/io.jxcore.node.ConnectionHelper( 3244): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 3244): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT589","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT589]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT589]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT589]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT589], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT589]
I/io.jxcore.node.ConnectionHelper( 3244): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT589], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper( 3244): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT589] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT633","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onServiceDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Adding new peer: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633]
I/io.jxcore.node.ConnectionHelper( 3244): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
W/io.jxcore.node.ConnectionHelper( 3244): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9219","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219]
I/io.jxcore.node.ConnectionHelper( 3244): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3244): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219] already in the list, will not add again
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  984): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT589], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT589]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633]
,D/WifiP2pManager( 3244): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service request added successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633]
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service discovery started successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/UsageStatsService(  750): User[0] Flushing usage stats to disk
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  984): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): setState: RESTARTING
,I/wpa_supplicant(  984): P2P-FIND-STOPPED 
,I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): setState: STARTED
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): restart: Restarting...
,D/WifiP2pManager( 3244): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service request added successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 2 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1532","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
I/io.jxcore.node.ConnectionHelper( 3244): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532], Bluetooth address: 7C:F9:0E:37:96:AB, device name: , device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 3244): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): setState: RESTARTING
,I/wpa_supplicant(  984): P2P-FIND-STOPPED 
,I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): Start timer timeout, starting now...
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): restart: Restarting...
,D/WifiP2pManager( 3244): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service request added successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service discovery started successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8280","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280]
I/io.jxcore.node.ConnectionHelper( 3244): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: , device address: ee:1f:72:63:11:86
W/io.jxcore.node.ConnectionHelper( 3244): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT3826","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
I/io.jxcore.node.ConnectionHelper( 3244): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
W/io.jxcore.node.ConnectionHelper( 3244): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826] already in the list, will not add again
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): checkListForExpiredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Removed [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633]
I/io.jxcore.node.ConnectionHelper( 3244): onPeerLost: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633]
D/io.jxcore.node.ConnectionHelper( 3244): hasConnection: No connection with peer with ID B0:C5:59:3F:75:69
D/io.jxcore.node.ConnectionHelper( 3244): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633] removed
D/io.jxcore.node.ConnectionHelper( 3244): notifyPeerAvailability: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633] not available
I/jxcore-log( 3244): peerAvailabilityChanged [{"peerIdentifier":"B0:C5:59:3F:75:69","peerName":"samsung-SM-G900F_PT633","peerAvailable":false}]
I/jxcore-log( 3244): 
I/jxcore-log( 3244): startWithNextDevice
I/jxcore-log( 3244): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9219","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219]
I/io.jxcore.node.ConnectionHelper( 3244): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3244): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219] already in the list, will not add again
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT589","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT589]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT589]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT589]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT589], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT589]
I/io.jxcore.node.ConnectionHelper( 3244): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT589], Bluetooth address: 58:3F:54:73:64:C0, device name: , device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper( 3244): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT589] already in the list, will not add again
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219]
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219]
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  984): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219]
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219]
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): restart: Restarting...
,D/WifiP2pManager( 3244): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service request added successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service discovery started successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT5572","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 6 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219]
I/io.jxcore.node.ConnectionHelper( 3244): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper( 3244): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT8213","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
I/io.jxcore.node.ConnectionHelper( 3244): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
D/io.jxcore.node.ConnectionHelper( 3244): notifyPeerAvailability: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8213] is available
I/jxcore-log( 3244): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:85:54","peerName":"LGE-LG-D722_PT8213","peerAvailable":true}]
I/jxcore-log( 3244): 
I/jxcore-log( 3244): startWithNextDevice
I/jxcore-log( 3244): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9219","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219]
I/io.jxcore.node.ConnectionHelper( 3244): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3244): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219] already in the list, will not add again
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  984): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 6 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  984): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d,
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  984): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT589], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT589]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT589], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT589]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3244): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service request added successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT5572","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572]
I/io.jxcore.node.ConnectionHelper( 3244): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper( 3244): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572] already in the list, will not add again
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): checkListForExpiredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Removed [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
I/io.jxcore.node.ConnectionHelper( 3244): onPeerLost: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
D/io.jxcore.node.ConnectionHelper( 3244): hasConnection: No connection with peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 3244): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532] removed
D/io.jxcore.node.ConnectionHelper( 3244): notifyPeerAvailability: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532] not available
I/jxcore-log( 3244): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:37:96:AB","peerName":"samsung-SM-A500FU_PT1532","peerAvailable":false}]
I/jxcore-log( 3244): 
I/jxcore-log( 3244): startWithNextDevice
I/jxcore-log( 3244): 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT6460","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onServiceDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Adding new peer: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460]
I/io.jxcore.node.ConnectionHelper( 3244): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 92:b6:86:43:73:1c
W/io.jxcore.node.ConnectionHelper( 3244): modifyListOfDiscoveredPeers: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460] already in the list, will not add again
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): restart: Restarting...
,D/WifiP2pManager( 3244): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service request added successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service discovery started successfully
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  984): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT6460","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onServiceDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460]
I/io.jxcore.node.ConnectionHelper( 3244): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460], Bluetooth address: E0:DB:10:14:E2:C0, device name: Note4-1, device address: 92:b6:86:43:73:1c
W/io.jxcore.node.ConnectionHelper( 3244): modifyListOfDiscoveredPeers: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8280","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280]
I/io.jxcore.node.ConnectionHelper( 3244): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
W/io.jxcore.node.ConnectionHelper( 3244): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT3826","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
I/io.jxcore.node.ConnectionHelper( 3244): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
W/io.jxcore.node.ConnectionHelper( 3244): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT633","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onServiceDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Adding new peer: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633]
,I/io.jxcore.node.ConnectionHelper( 3244): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
D/io.jxcore.node.ConnectionHelper( 3244): notifyPeerAvailability: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633] is available
,I/jxcore-log( 3244): peerAvailabilityChanged [{"peerIdentifier":"B0:C5:59:3F:75:69","peerName":"samsung-SM-G900F_PT633","peerAvailable":true}]
I/jxcore-log( 3244): 
I/jxcore-log( 3244): startWithNextDevice
I/jxcore-log( 3244): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT8213","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
I/io.jxcore.node.ConnectionHelper( 3244): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 3244): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8213] already in the list, will not add again
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): restart: Restarting...
,D/WifiP2pManager( 3244): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service request added successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service discovery started successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  984): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 8 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8280","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280]
I/io.jxcore.node.ConnectionHelper( 3244): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
W/io.jxcore.node.ConnectionHelper( 3244): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT3826","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
I/io.jxcore.node.ConnectionHelper( 3244): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
W/io.jxcore.node.ConnectionHelper( 3244): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT633","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onServiceDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633]
,I/io.jxcore.node.ConnectionHelper( 3244): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
W/io.jxcore.node.ConnectionHelper( 3244): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT8213","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
I/io.jxcore.node.ConnectionHelper( 3244): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 3244): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8213] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9219","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219]
I/io.jxcore.node.ConnectionHelper( 3244): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3244): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219] already in the list, will not add again
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): restart: Restarting...
,D/WifiP2pManager( 3244): Ignored { when=-7ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service request added successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633]
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service discovery started successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT3826","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
I/io.jxcore.node.ConnectionHelper( 3244): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
W/io.jxcore.node.ConnectionHelper( 3244): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT633","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onServiceDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633]
I/io.jxcore.node.ConnectionHelper( 3244): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
W/io.jxcore.node.ConnectionHelper( 3244): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633] already in the list, will not add again
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): restart: Restarting...
,D/WifiP2pManager( 3244): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service request added successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633]
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service discovery started successfully
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633]
,I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): restart: Restarting...
,D/WifiP2pManager( 3244): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service discovery started successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1532","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
I/io.jxcore.node.ConnectionHelper( 3244): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532], Bluetooth address: 7C:F9:0E:37:96:AB, device name: , device address: 7e:f9:0e:37:96:ac
D/io.jxcore.node.ConnectionHelper( 3244): notifyPeerAvailability: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532] is available
I/jxcore-log( 3244): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:37:96:AB","peerName":"samsung-SM-A500FU_PT1532","peerAvailable":true}]
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): startWithNextDevice
I/jxcore-log( 3244): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT6460","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onServiceDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Adding new peer: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460]
,I/io.jxcore.node.ConnectionHelper( 3244): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460], Bluetooth address: E0:DB:10:14:E2:C0, device name: Note4-1, device address: 92:b6:86:43:73:1c
W/io.jxcore.node.ConnectionHelper( 3244): modifyListOfDiscoveredPeers: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT3826","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
I/io.jxcore.node.ConnectionHelper( 3244): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
W/io.jxcore.node.ConnectionHelper( 3244): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826] already in the list, will not add again
,I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3244): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service discovery started successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8280","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280]
I/io.jxcore.node.ConnectionHelper( 3244): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
,W/io.jxcore.node.ConnectionHelper( 3244): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280] already in the list, will not add again
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3244): timeout now
I/jxcore-log( 3244): 
I/jxcore-log( 3244): weAreDoneNow, resultArray.length: 11
I/jxcore-log( 3244): 
I/jxcore-log( 3244): sendReportNow
I/jxcore-log( 3244): 
I/jxcore-log( 3244): done, now sending data to server
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:15:02.293Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3244): 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): restart: Restarting...
,D/WifiP2pManager( 3244): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service request added successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service discovery started successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  984): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1532","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
I/io.jxcore.node.ConnectionHelper( 3244): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 3244): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532] already in the list, will not add again
,I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
,D/WifiP2pManager( 3244): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service discovery started successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): checkListForExpiredPeers: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Removed [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460]
I/io.jxcore.node.ConnectionHelper( 3244): onPeerLost: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460]
D/io.jxcore.node.ConnectionHelper( 3244): hasConnection: No connection with peer with ID E0:DB:10:14:E2:C0
D/io.jxcore.node.ConnectionHelper( 3244): modifyListOfDiscoveredPeers: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460] removed
D/io.jxcore.node.ConnectionHelper( 3244): notifyPeerAvailability: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6460] not available
I/jxcore-log( 3244): peerAvailabilityChanged [{"peerIdentifier":"E0:DB:10:14:E2:C0","peerName":"samsung-SM-N910C_PT6460","peerAvailable":false}]
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): startWithNextDevice
I/jxcore-log( 3244): 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  984): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/WifiP2pManager( 3244): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service request added successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service discovery started successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): setState: RESTARTING
,I/wpa_supplicant(  984): P2P-FIND-STOPPED 
,I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): Start timer timeout, starting now...
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  984): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 2 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
,D/WifiP2pManager( 3244): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service request added successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): checkListForExpiredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633] expired
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Removed [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633]
I/io.jxcore.node.ConnectionHelper( 3244): onPeerLost: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633]
,D/io.jxcore.node.ConnectionHelper( 3244): hasConnection: No connection with peer with ID B0:C5:59:3F:75:69
D/io.jxcore.node.ConnectionHelper( 3244): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633] removed
D/io.jxcore.node.ConnectionHelper( 3244): notifyPeerAvailability: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633] not available
,I/jxcore-log( 3244): peerAvailabilityChanged [{"peerIdentifier":"B0:C5:59:3F:75:69","peerName":"samsung-SM-G900F_PT633","peerAvailable":false}]
I/jxcore-log( 3244): 
I/jxcore-log( 3244): startWithNextDevice
I/jxcore-log( 3244): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): setState: RESTARTING
,I/wpa_supplicant(  984): P2P-FIND-STOPPED 
,I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): P2P device discovery started successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  984): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 3244): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service request added successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  984): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service discovery started successfully
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9219","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219]
,I/io.jxcore.node.ConnectionHelper( 3244): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3244): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219] already in the list, will not add again
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): checkListForExpiredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Removed [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
I/io.jxcore.node.ConnectionHelper( 3244): onPeerLost: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
D/io.jxcore.node.ConnectionHelper( 3244): hasConnection: No connection with peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 3244): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826] removed
D/io.jxcore.node.ConnectionHelper( 3244): notifyPeerAvailability: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826] not available
I/jxcore-log( 3244): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:51:18:22","peerName":"samsung-SM-A500FU_PT3826","peerAvailable":false}]
I/jxcore-log( 3244): 
I/jxcore-log( 3244): startWithNextDevice
I/jxcore-log( 3244): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): setState: RESTARTING
,I/wpa_supplicant(  984): P2P-FIND-STOPPED 
,I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): Start timer timeout, starting now...
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): restart: Restarting...
,D/WifiP2pManager( 3244): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service request added successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service discovery started successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT3826","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
,I/io.jxcore.node.ConnectionHelper( 3244): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
D/io.jxcore.node.ConnectionHelper( 3244): notifyPeerAvailability: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826] is available
,I/jxcore-log( 3244): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:51:18:22","peerName":"samsung-SM-A500FU_PT3826","peerAvailable":true}]
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): startWithNextDevice
I/jxcore-log( 3244): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT5572","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572]
I/io.jxcore.node.ConnectionHelper( 3244): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper( 3244): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT8213","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
I/io.jxcore.node.ConnectionHelper( 3244): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 3244): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8213] already in the list, will not add again
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3826]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1532","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
I/io.jxcore.node.ConnectionHelper( 3244): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532], Bluetooth address: 7C:F9:0E:37:96:AB, device name: , device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 3244): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9219","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219]
I/io.jxcore.node.ConnectionHelper( 3244): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3244): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219] already in the list, will not add again
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9219]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT589","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT589]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT589]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT589]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT589], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT589]
,I/io.jxcore.node.ConnectionHelper( 3244): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT589], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper( 3244): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT589] already in the list, will not add again
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT633","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onServiceDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Adding new peer: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633]
I/io.jxcore.node.ConnectionHelper( 3244): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633], Bluetooth address: B0:C5:59:3F:75:69, device name: , device address: ee:1f:72:18:8b:78
D/io.jxcore.node.ConnectionHelper( 3244): notifyPeerAvailability: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT633] is available
I/jxcore-log( 3244): peerAvailabilityChanged [{"peerIdentifier":"B0:C5:59:3F:75:69","peerName":"samsung-SM-G900F_PT633","peerAvailable":true}]
I/jxcore-log( 3244): 
I/jxcore-log( 3244): startWithNextDevice
I/jxcore-log( 3244): 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  984): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT589], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT589]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8213], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8213]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT589], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT589]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8280","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280]
I/io.jxcore.node.ConnectionHelper( 3244): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
W/io.jxcore.node.ConnectionHelper( 3244): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280] already in the list, will not add again
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT589], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT589]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5572]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): restart: Restarting...
,D/WifiP2pManager( 3244): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service request added successfully
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  984): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8280","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280]
,I/io.jxcore.node.ConnectionHelper( 3244): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
W/io.jxcore.node.ConnectionHelper( 3244): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT8280] already in the list, will not add again
,I/jxcore-log( 3244): teardown
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): testSendData stopped
I/jxcore-log( 3244): 
I/io.jxcore.node.ConnectionHelper( 3244): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3244): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3244): Shutting down...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3244): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3244): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3244): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3244): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3244): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3244): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3244): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): stop: Stopping P2P device discovery...
,I/wpa_supplicant(  984): P2P-FIND-STOPPED 
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant(  984): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3244): release: No more listeners, de-initializing...
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3244): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3244): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3244): setState: NOT_STARTED
I/jxcore-log( 3244): StopBroadcasting went ok
I/jxcore-log( 3244): 
,I/jxcore-log( 3244): 2015-12-18T18:18:21.805Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
I/jxcore-log( 3244): 
I/chromium( 3244): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
I/io.jxcore.node.ConnectionHelper( 3244): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3244): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3244): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3244): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 3244): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 3244): --- start :testReConnect.js---
I/jxcore-log( 3244): 
,I/chromium( 3244): [INFO:CONSOLE(63)] "logCallback --- start :testReConnect.js---", source: file:///android_asset/www/js/thali_main.js (63)
,W/bt-smp  ( 2094): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2094): Plain text(LSB ~ MSB) = 2f 36 49 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2094): Encrypted text(LSB ~ MSB) = 46 d5 f5 53 b4 a7 0e c0 75 c3 74 57 b8 7d c8 d6 
,W/bt-btm  ( 2094): Stopping oneshot timer
,I/ActivityManager(  750): Killing 3005:com.android.defcontainer/u0a5 (adj 13): empty for 1806s
,I/ActivityManager(  750): Killing 3164:com.google.android.apps.docs/u0a40 (adj 13): empty for 1808s
,I/ActivityManager(  750): Killing 3134:com.android.musicfx/u0a15 (adj 13): empty for 1809s
,I/ActivityManager(  750): Killing 1507:com.google.android.partnersetup/u0a13 (adj 13): empty for 1809s
,I/ActivityManager(  750): Killing 2029:com.android.providers.calendar/u0a2 (adj 15): empty for 1813s
,I/ActivityManager(  750): Killing 3029:com.google.android.gms:car/u0a8 (adj 15): empty for 1813s
,I/ActivityManager(  750): Killing 2009:com.google.android.calendar/u0a31 (adj 15): empty for 1843s
,W/libprocessgroup(  750): failed to open /acct/uid_10005/pid_3005/cgroup.procs: No such file or directory
,W/libprocessgroup(  750): failed to open /acct/uid_10002/pid_2029/cgroup.procs: No such file or directory
,W/libprocessgroup(  750): failed to open /acct/uid_10008/pid_3029/cgroup.procs: No such file or directory
,W/libprocessgroup(  750): failed to open /acct/uid_10031/pid_2009/cgroup.procs: No such file or directory
,I/ProcessStatsService(  750): Prepared write state in 3ms
,W/libprocessgroup(  750): failed to open /acct/uid_10040/pid_3164/cgroup.procs: No such file or directory
,W/libprocessgroup(  750): failed to open /acct/uid_10015/pid_3134/cgroup.procs: No such file or directory
,W/libprocessgroup(  750): failed to open /acct/uid_10013/pid_1507/cgroup.procs: No such file or directory
,I/ProcessStatsService(  750): Prepared write state in 3ms
,I/ProcessStatsService(  750): Prepared write state in 4ms
,I/ProcessStatsService(  750): Prepared write state in 3ms
,I/ProcessStatsService(  750): Prepared write state in 5ms
,I/ProcessStatsService(  750): Prepared write state in 5ms
,V/GLSActivity( 1601): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1601): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1601): Explicit concurrent mark sweep GC freed 93383(5MB) AllocSpace objects, 29(487KB) LOS objects, 40% free, 23MB/38MB, paused 869us total 62.690ms
,E/DataBuffer( 1601): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1e170e4b)
E/DataBuffer( 1601): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2f2e2028)
E/DataBuffer( 1601): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2b601141)
E/DataBuffer( 1601): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@166f56e6)
E/DataBuffer( 1601): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@15c64427)
,I/ProcessStatsService(  750): Pruning old procstats: /data/system/procstats/state-2015-12-17-21-38-44.bin
,TIME-OUT KILL (timeout was 1800000ms)
```
