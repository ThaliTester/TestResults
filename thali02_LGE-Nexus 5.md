#### Test 549702619369e5e_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
I/GAv4    ( 3123): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3123):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3123):   adb logcat -s GAv4
W/GAv4    ( 3123): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3123): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3123): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 3123): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
D/Finsky  ( 2580): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
W/ResourcesManager( 3123): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3123): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  732): Killing 2550:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
V/JNIHelp ( 3123): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/libprocessgroup(  732): failed to open /acct/uid_10069/pid_2550/cgroup.procs: No such file or directory
W/System  ( 3123): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3123): Installed default security provider GmsCore_OpenSSL
V/GLSActivity( 1574): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 1643): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/Icing   ( 1643): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/Icing   ( 1643): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1643): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
,D/AndroidRuntime( 3189): 
D/AndroidRuntime( 3189): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3189): CheckJNI is OFF
D/AndroidRuntime( 3189): Calling main entry com.android.commands.am.Am
I/ActivityManager(  732): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  732): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3213 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3189): Shutting down VM
,V/ActivityManager(  732): Display changed displayId=0
,I/ActivityManager(  732): Killing 2468:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,W/libprocessgroup(  732): failed to open /acct/uid_10045/pid_2468/cgroup.procs: No such file or directory
,I/WebViewFactory( 3213): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3213): Time to load native libraries: 3 ms (timestamps 9065-9068)
,I/LibraryLoader( 3213): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3213): Binding Chromium to main looper Looper (main, tid 1) {13ac0858}
I/LibraryLoader( 3213): Expected native library version number "",actual native library version number ""
,I/chromium( 3213): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3213): Initializing chromium process, singleProcess=true
,W/art     ( 3213): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3213): ApplicationContext is null in ApplicationStatus
,W/chromium( 3213): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3213): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3213): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3213): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  732): Message: 20
,D/BluetoothManagerService(  732): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@306ef39e:true
,W/art     ( 3213): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3213): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3213): CordovaWebView is running on device made by: LGE
,W/art     ( 3213): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 3213): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3213): Render dirty regions requested: true
,D/Atlas   ( 3213): Validating map...
,W/chromium( 3213): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3213): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3213): Enabling debug mode 0
,I/ActivityManager(  732): Displayed com.test.thalitest/.MainActivity: +530ms (total +58s429ms)
,W/IInputConnectionWrapper( 3213): showStatusIcon on inactive InputConnection
,W/BindingManager( 3213): Cannot call determinedVisibility() - never saw a connection for the pid: 3213
,D/JsMessageQueue( 3213): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3213): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257332480
,D/JX-Cordova( 3213): jxcore cordova android initializing
,W/jxcore-log( 3213): Initializing JXcore engine
W/jxcore-log( 3213): JXcore engine is ready
,W/jxcore-log( 3213): Starting JXcore engine
,W/.test.thalitest( 3213): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[8380]" dev="sockfs" ino=8380 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3213): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 3213): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[9528]" dev="sockfs" ino=9528 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3213): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[19569]" dev="sockfs" ino=19569 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3213): Platform android
W/jxcore-log( 3213): 
W/jxcore-log( 3213): Process ARCH arm
W/jxcore-log( 3213): 
,I/jxcore-log( 3213): JXcore Cordova bridge is ready!
I/jxcore-log( 3213): 
W/jxcore-log( 3213): JXcore engine is started
,I/Choreographer( 3213): Skipped 109 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3213): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3213): Toggling radios to true
I/jxcore-log( 3213): 
,D/BluetoothAdapter( 3213): enable(): BT is already enabled..!
,D/WifiService(  732): setWifiEnabled: true pid=3213, uid=10270
E/WifiService(  732): Invoking mWifiStateMachine.setWifiEnabled
,D/WifiService(  732): New client listening to asynchronous messages
,I/jxcore-log( 3213): Radios toggled
I/jxcore-log( 3213): 
I/wpa_supplicant(  992): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  732): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  732): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
E/native  (  732): do suspend true
,D/CommandListener(  181): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1574): Read error: ssl=0xaf362e00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1574): SSL shutdown failed: ssl=0xaf362e00: I/O error during system call, Broken pipe
D/ConnectivityService(  732): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  732): ValidatedState{ when=-7ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  732): DefaultState{ when=-7ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  732): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  732): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  732): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  732): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,V/GLSActivity( 1574): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1574): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/WifiConfigStore(  732): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  732): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  732): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,E/WifiStateMachine(  732): Start Disconnecting Watchdog 1
,I/wpa_supplicant(  992): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/ConnectivityService(  732): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
E/native  (  732): do suspend true
,D/ConnectivityManager.CallbackHandler(  900): CM callback handler got msg 524292
D/Nat464Xlat(  732): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  732): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  732): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  732): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  732): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  732): Disconnected - quitting
,D/ConnectivityService(  732): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  732): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1239): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/CommandListener(  181): Clearing all IP addresses on wlan0
,D/ConnectivityManager.CallbackHandler( 1643): CM callback handler got msg 524292
,D/WifiNetworkAgent(  732): NetworkAgent: NetworkAgent channel lost
,I/wpa_supplicant(  992): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant(  992): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant(  992): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant(  992): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  732): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  732): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  732): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  732): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  181): Setting iface cfg
,E/WifiStateMachine(  732): Start Dhcp Watchdog 2
,E/native  (  732): do suspend false
,E/WifiStateMachine(  732): scanCount==0 - aborting
,I/dhcpcd  ( 3300): version 5.5.6 starting
E/dhcpcd  ( 3300): get_duid: Read-only file system
,I/dhcpcd  ( 3300): wlan0: rebinding lease of 192.168.1.114
,D/ConnectivityService(  732): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  732): MasterInitialState.processMessage what=3
,D/ConnectivityService(  732): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  732): MasterInitialState.processMessage what=3
,V/MusicLeanback( 2696): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/dhcpcd  ( 3300): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/SystemUpdateService( 1643): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1643): onCreate
,D/SystemUpdateService( 1643): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.Environment( 1643): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1643): num queued entries: 0
I/iu.UploadsManager( 1643): num updated entries: 0
I/iu.SyncManager( 1643): NEXT; no task
,I/Babel   ( 1892): connection state changed from CONNECTED to DISCONNECTED
,I/SystemUpdateService( 1643): active receiver: enabled
,I/SystemUpdateService( 1643): showing system update notification
,I/dhcpcd  ( 3300): wlan0: leased 192.168.1.114 for 86400 seconds
,I/ActivityManager(  732): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3318 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/GpsLocationProvider(  732): No APN found to select.
,V/SystemUpdateService( 1643): retry (wakeup: false) in 3599912 ms
I/ValidateNoPeople(  732): skipping global notification
,D/SystemUpdateService( 1643): onDestroy
,E/GpsLocationProvider(  732): No APN found to select.
,I/GAv4    ( 3318): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3318):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3318):   adb logcat -s GAv4
,W/GAv4    ( 3318): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3318): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3318): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,E/native  (  732): do suspend true
,D/ConnectivityService(  732): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  732): Adding iface wlan0 to network 101
,E/WifiStateMachine(  732): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  732): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  732): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  732): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  732): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  732): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  732): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  732): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  732): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  732): rematching NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  732): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  732): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  732): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  732): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/ConnectivityService(  732):    accepting network in place of null
,D/CSLegacyTypeTracker(  732): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,D/ConnectivityService(  732): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  732): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::5255:27ff:fef0:fd0b/64,192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService(  732): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler(  900): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1643): CM callback handler got msg 524290
,I/WebViewFactory( 3318): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  732): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 08 Jan 2016 22:27:18 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452292037685], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452292037671]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  732): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  732): Validated
D/ConnectivityService(  732): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  732): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  732): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  732): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  732): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler(  900): CM callback handler got msg 524290
,D/TelephonyNetworkFactory( 1239): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 1643): CM callback handler got msg 524290
,I/LibraryLoader( 3318): Time to load native libraries: 2 ms (timestamps 5234-5236)
I/LibraryLoader( 3318): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3318): Binding Chromium to main looper Looper (main, tid 1) {25f13a2c}
,I/LibraryLoader( 3318): Expected native library version number "",actual native library version number ""
I/chromium( 3318): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3318): Initializing chromium process, singleProcess=true
W/art     ( 3318): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3318): ApplicationContext is null in ApplicationStatus
,W/chromium( 3318): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3318): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3318): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3318): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/AudioManagerAndroid( 3318): Requires BLUETOOTH permission
,I/NSApplication( 3318): Starting up...
,I/ActivityManager(  732): Killing 2672:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/libprocessgroup(  732): failed to open /acct/uid_10003/pid_2672/cgroup.procs: No such file or directory
,V/MusicLeanback( 2696): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1643): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1643): onCreate
,D/SystemUpdateService( 1643): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1643): active receiver: enabled
,I/iu.Environment( 1643): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/SystemUpdateService( 1643): showing system update notification
,I/iu.UploadsManager( 1643): num queued entries: 0
,I/iu.UploadsManager( 1643): num updated entries: 0
I/iu.SyncManager( 1643): NEXT; no task
,I/ValidateNoPeople(  732): skipping global notification
,V/SystemUpdateService( 1643): retry (wakeup: false) in 3599962 ms
,D/SystemUpdateService( 1643): onDestroy
,I/Babel   ( 1892): connection state changed from DISCONNECTED to CONNECTED
,D/ConnectivityService(  732): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,W/NetworkUtils( 1485): OkHttp exception
W/EventLoggerService( 1485): Unable to send logs Error code: 262146
,I/jxcore-log( 3213): Test app app.js loaded
I/jxcore-log( 3213): 
,I/chromium( 3213): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/ConnectivityService(  732): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  732): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2696): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2696): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1643): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1643): onCreate
,D/SystemUpdateService( 1643): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1643): active receiver: enabled
,I/SystemUpdateService( 1643): showing system update notification
,I/ValidateNoPeople(  732): skipping global notification
,V/SystemUpdateService( 1643): retry (wakeup: false) in 3599975 ms
,I/art     (  732): Explicit concurrent mark sweep GC freed 44908(2MB) AllocSpace objects, 8(128KB) LOS objects, 33% free, 27MB/41MB, paused 1.040ms total 88.868ms
,D/SystemUpdateService( 1643): onDestroy
,E/GpsLocationProvider(  732): No APN found to select.
,V/GLSActivity( 1574): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1574): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/art     ( 2856): Attempt to remove local handle scope entry from IRT, ignoring
,D/Finsky  ( 2580): [250] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2580): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/GLSActivity( 1574): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1574): Vacuum at: now=1452292050229 tag=VacuumService
,I/PhenotypeConfigurator( 1574): Scheduling Phenotype for one-off execution 9429 seconds from now (1452292050651)
,D/GetConfigurationSnapshotOperation( 1574): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1574): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1574): Using platform SSLCertificateSocketFactory
,V/GLSActivity( 1574): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1574): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ClearcutLoggerApiImpl( 1574): disconnect managed GoogleApiClient
,D/AlarmManagerService(  732): Setting time of day to sec=1452292121
,W/AlarmManagerService(  732): Unable to set rtc to 1452292121: Invalid argument
,I/ActivityManager(  732): Start proc com.google.android.keep for broadcast com.google.android.keep/.notification.AlertReceiver: pid=3528 uid=10071 gids={50071, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  732): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=3570 uid=10076 gids={50076, 9997} abi=armeabi-v7a
,I/ActivityManager(  732): Killing 2640:com.android.settings/1000 (adj 15): empty #17
,D/WifiService(  732): Client connection lost with reason: 4
,W/libprocessgroup(  732): failed to open /acct/uid_1000/pid_2640/cgroup.procs: No such file or directory
,D/TimeService( 3570): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1452292121809
D/        ( 3570): TimeServiceNative: User Time to be set is 1452292121809
D/QC-time-services( 3570): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 3570): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 3570): Lib:time_genoff_operation: pargs->ts_val = 1452292121809
D/QC-time-services(  199): Daemon: Connection accepted:time_genoff
D/QC-time-services( 3570): Lib:time_genoff_operation: Send to server  passed!!
,D/QC-time-services(  199): Daemon:Received base = 2, unit = 1, operation = 0,value = 1452292121809
D/QC-time-services(  199): Daemon:genoff_opr: Base = 2, val = 1452292121809, operation = 0
D/QC-time-services(  199): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS4/13/70 4:19:12
D/QC-time-services(  199): Daemon:Value read from RTC seconds = 11420352000
D/QC-time-services(  199): Daemon:new time 1452292121809 
D/QC-time-services(  199): Daemon: delta 1440871769809 genoff 1440871769809 
D/QC-time-services(  199): Daemon:genoff_persistent_update: Writing genoff = 1440871769809 to memory
D/QC-time-services(  199): Daemon:Opening File: /data/system/time/ats_2
D/QC-time-services(  199): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  199): Updating the TOD offset
D/QC-time-services(  199): Daemon:genoff_persistent_update: Writing genoff = 1440871769809 to memory
D/QC-time-services(  199): Daemon:Opening File: /data/system/time/ats_1
D/QC-time-services(  199): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  199): Daemon:Update to modem bit set
,D/QC-time-services(  199): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  199): Daemon: Base = 2, Value being sent to MODEM = 1136327321809
E/QC-time-services( 3570): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,I/ActivityManager(  732): Killing 2514:com.google.android.gm/u0a70 (adj 15): empty #17
,D/QC-time-services(  199): Daemon: Time-services: Waiting to acceptconnection
D/QC-time-services(  199): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,W/libprocessgroup(  732): failed to open /acct/uid_10070/pid_2514/cgroup.procs: No such file or directory
,I/CheckinService( 1643): Checkin interval check for package: unspecified last checkin: 1452262505743 min interval config: 0 actual interval: 29616125
,I/ActivityManager(  732): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver: pid=3595 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,I/GAv4    ( 3595): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3595):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3595):   adb logcat -s GAv4
,W/GAv4    ( 3595): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3595): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3595): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  732): Killing 2968:com.google.android.gms:car/u0a8 (adj 15): empty #17
,W/libprocessgroup(  732): failed to open /acct/uid_10008/pid_2968/cgroup.procs: No such file or directory
,I/jxcore-log( 3213): --= Surplus to requirements =--
I/jxcore-log( 3213): 
I/jxcore-log( 3213): ****TEST TOOK:  ms ****
I/jxcore-log( 3213): 
I/jxcore-log( 3213): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3213): 
,D/AndroidRuntime( 3630): 
D/AndroidRuntime( 3630): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 3630): CheckJNI is OFF
,D/AndroidRuntime( 3630): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  732): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  732): Killing 3213:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
,I/WindowState(  732): WIN DEATH: Window{e8d804e u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  732): Client connection lost with reason: 4
,W/PackageSettings(  732): Skipping PackageSetting{3ea5fd6c com.example.hello/10278} due to missing metadata
,I/ActivityManager(  732):   Force finishing activity ActivityRecord{23c64ffa u0 com.test.thalitest/.MainActivity t214}
,W/ActivityManager(  732): Spurious death for ProcessRecord{1ae690a6 3213:com.test.thalitest/u0a270}, curProc for 3213: null
I/ActivityManager(  732): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
I/ActivityManager(  732):   Force finishing activity ActivityRecord{23c64ffa u0 com.test.thalitest/.MainActivity t214 f}
W/ActivityManager(  732): Duplicate finish request for ActivityRecord{23c64ffa u0 com.test.thalitest/.MainActivity t214 f}
,I/art     ( 1485): Explicit concurrent mark sweep GC freed 9138(581KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 19MB/25MB, paused 318us total 44.443ms
,I/art     ( 1298): Explicit concurrent mark sweep GC freed 4007(296KB) AllocSpace objects, 1(126KB) LOS objects, 23% free, 25MB/33MB, paused 223us total 16.187ms
,I/InputReader(  732): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 1574): Ignoring removeGeofence because network location is disabled.
,I/Keyboard.Facilitator( 1103): resetDictionaries() : en_US
,I/Adreno-EGL(  948): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
I/OpenGLRenderer(  948): Initialized EGL, version 1.4
,D/OpenGLRenderer(  948): Enabling debug mode 0
,I/art     (  732): Explicit concurrent mark sweep GC freed 32157(1671KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 27MB/41MB, paused 1.253ms total 80.651ms
,D/VoicemailCleanupService( 2822): Cleaning up data for package: com.test.thalitest
,I/Keyboard.Facilitator.DecoderInitializer( 1103): run()
,I/art     ( 1643): Explicit concurrent mark sweep GC freed 18343(970KB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 22MB/30MB, paused 455us total 46.594ms
,I/UpdateIcingCorporaServi( 1485): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/Decoder ( 1103): createOrResetDecoder
,W/Launcher( 1298): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@16da8db1 new=com.google.android.velvet.VelvetApplication@16da8db1
,I/ActivityManager(  732): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3671 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,W/InputMethodManagerService(  732): Focus gain on non-focused client com.android.internal.view.IInputMethodClient$Stub$Proxy@169da3de (uid=10034 pid=948)
,D/BackupManagerService(  732): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  732): Receieved: android.intent.action.PACKAGE_REMOVED
,I/ConfigService( 1574): onCreate
,D/TaskPersister(  732): removeObsoleteFile: deleting file=214_task.xml
,I/art     (  732): Explicit concurrent mark sweep GC freed 4889(256KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 27MB/41MB, paused 4.359ms total 108.113ms
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1103): run()
,W/ContextImpl( 3671): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
,D/PackageBroadcastService( 1643): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1643): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 1643): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1643): Module APK com.google.android.play.games already loaded
,I/UpdateIcingCorporaServi( 1485): UpdateCorporaTask done [took 165 ms] updated apps [took 165 ms] 
,I/ActivityManager(  732): Killing 1524:com.google.android.partnersetup/u0a13 (adj 15): empty #17
,D/ChimeraCfgMgr( 1643): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1643): Module APK com.google.android.play.games already loaded
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1103): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1103): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1103): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1103): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1103): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1103): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1103): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1103): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1103): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1103): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1103): run()
I/StatsUtilsManager( 1103): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1103): shouldRecordStats() = Too Soon
,D/AndroidRuntime( 3630): Shutting down VM
,W/libprocessgroup(  732): failed to open /acct/uid_10013/pid_1524/cgroup.procs: No such file or directory
,I/Launcher( 1298): Deferring update until onResume
,I/LocationSettingsChecker( 1643): Removing dialog suppression flag for package com.test.thalitest
,W/ResourcesManager( 1298): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/gH_CompatibleDatabase( 1643): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1643): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1643): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1643): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/gH_CompatibleDatabase( 1643): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1643): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/gH_CompatibleDatabase( 1643): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/gH_CompatibleDatabase( 1643): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
,D/gH_CompatibleDatabase( 1643): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 1643): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1643): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
W/ResourcesManager( 1298): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/gH_CompatibleDatabase( 1643): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1643): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/GMPM-SVC( 1643): App measurement is starting up, version: 8489
I/GMPM-SVC( 1643): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,E/DataBuffer( 1574): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@272fd195)
,W/BaseAppContext( 1643): Using Auth Proxy for data requests.
,I/Launcher( 1298): Deferring update until onResume
,I/art     ( 1574): Explicit concurrent mark sweep GC freed 92753(5MB) AllocSpace objects, 31(496KB) LOS objects, 39% free, 23MB/38MB, paused 831us total 49.832ms
,E/DataBuffer( 1574): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2f75d2aa)
,E/DataBuffer( 1574): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@34d6ae9b)
,E/DataBuffer( 1574): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@f7dc238)
,E/DataBuffer( 1574): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1908f211)
E/DataBuffer( 1574): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2cb66f76)
E/NetworkScheduler.SchedulerReceiver( 1574): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1574): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,W/BaseAppContext( 1643): Using Auth Proxy for data requests.
,I/ActivityManager(  732): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,I/Icing   ( 1643): doRemovePackageData com.test.thalitest
,I/ActivityManager(  732): Resuming delayed broadcast
I/ActivityManager(  732): Delay finish: com.google.android.apps.plus/.service.PhotosAppTransitionMonitor
I/ActivityManager(  732): Resuming delayed broadcast
,I/ActivityManager(  732): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3710 uid=10039 gids={50039, 9997} abi=armeabi-v7a
,I/ActivityManager(  732): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3730 uid=10007 gids={50007, 9997, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  732): Killing 3030:com.android.defcontainer/u0a5 (adj 15): empty #17
,I/ActivityManager(  732): Killing 2696:com.google.android.music:main/u0a60 (adj 15): empty #17
,W/libprocessgroup(  732): failed to open /acct/uid_10005/pid_3030/cgroup.procs: No such file or directory
,W/libprocessgroup(  732): failed to open /acct/uid_10060/pid_2696/cgroup.procs: No such file or directory
,D/ExternalStorage( 3730): After updating volumes, found 1 active roots

```
