#### Test 54970261fc259e9_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
D/ChimeraCfgMgr( 1619): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1619): Module APK com.google.android.play.games already loaded
,I/GAv4    ( 3132): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3132):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3132):   adb logcat -s GAv4
W/GAv4    ( 3132): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3132): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3132): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 3132): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
--------- beginning of system
W/ResourcesManager( 3132): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3132): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/Finsky  ( 2603): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
D/AndroidRuntime( 3181): 
D/AndroidRuntime( 3181): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3181): CheckJNI is OFF
V/JNIHelp ( 3132): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/ActivityManager(  759): Killing 2572:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
W/System  ( 3132): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3132): Installed default security provider GmsCore_OpenSSL
D/AndroidRuntime( 3181): Calling main entry com.android.commands.am.Am
I/ActivityManager(  759): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  759): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3212 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3181): Shutting down VM
W/libprocessgroup(  759): failed to open /acct/uid_10069/pid_2572/cgroup.procs: No such file or directory
I/art     (  195): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 227us total 10.597ms
I/art     (  195): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 212us total 9.089ms
V/GLSActivity( 1572): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/art     (  195): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 216us total 9.210ms
V/ActivityManager(  759): Display changed displayId=0
I/WebViewFactory( 3212): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3212): Time to load native libraries: 1 ms (timestamps 8397-8398)
I/LibraryLoader( 3212): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3212): Binding Chromium to main looper Looper (main, tid 1) {57bad51}
I/LibraryLoader( 3212): Expected native library version number "",actual native library version number ""
I/chromium( 3212): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/Icing   ( 1619): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/BrowserStartupController( 3212): Initializing chromium process, singleProcess=true
W/art     ( 3212): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3212): ApplicationContext is null in ApplicationStatus
,W/chromium( 3212): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3212): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3212): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3212): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
I/Icing   ( 1619): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1619): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/Icing   ( 1619): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
D/BluetoothManagerService(  759): Message: 20
D/BluetoothManagerService(  759): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@28fad4d2:true
W/art     ( 3212): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 3212): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 3212): CordovaWebView is running on device made by: LGE
W/art     ( 3212): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3212): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 3212): Render dirty regions requested: true
D/Atlas   ( 3212): Validating map...
W/chromium( 3212): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/OpenGLRenderer( 3212): Initialized EGL, version 1.4
D/OpenGLRenderer( 3212): Enabling debug mode 0
W/BindingManager( 3212): Cannot call determinedVisibility() - never saw a connection for the pid: 3212
W/IInputConnectionWrapper( 3212): showStatusIcon on inactive InputConnection
I/ActivityManager(  759): Displayed com.test.thalitest/.MainActivity: +457ms (total +57s67ms)
D/JsMessageQueue( 3212): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 3212): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257332480
D/JX-Cordova( 3212): jxcore cordova android initializing
I/ActivityManager(  759): Killing 2520:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
W/libprocessgroup(  759): failed to open /acct/uid_10045/pid_2520/cgroup.procs: No such file or directory
,W/jxcore-log( 3212): Initializing JXcore engine
W/jxcore-log( 3212): JXcore engine is ready
,W/jxcore-log( 3212): Starting JXcore engine
,W/.test.thalitest( 3212): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[6414]" dev="sockfs" ino=6414 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3212): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
,W/.test.thalitest( 3212): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[9610]" dev="sockfs" ino=9610 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/.test.thalitest( 3212): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[19750]" dev="sockfs" ino=19750 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3212): Platform android
W/jxcore-log( 3212): 
,W/jxcore-log( 3212): Process ARCH arm
W/jxcore-log( 3212): 
,I/jxcore-log( 3212): JXcore Cordova bridge is ready!
I/jxcore-log( 3212): 
W/jxcore-log( 3212): JXcore engine is started
I/Choreographer( 3212): Skipped 115 frames!  The application may be doing too much work on its main thread.
I/chromium( 3212): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3212): Toggling radios to true
I/jxcore-log( 3212): 
,D/BluetoothAdapter( 3212): enable(): BT is already enabled..!
,D/WifiService(  759): New client listening to asynchronous messages
,D/WifiService(  759): setWifiEnabled: true pid=3212, uid=10270
E/WifiService(  759): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3212): Radios toggled
I/jxcore-log( 3212): 
,I/wpa_supplicant( 1025): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  759): WifiStateMachine: Leaving Connected state
,E/WifiConfigStore(  759): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/native  (  759): do suspend true
,D/CommandListener(  180): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1572): Read error: ssl=0xb3b62e00: I/O error during system call, Connection timed out
V/NativeCrypto( 1572): SSL shutdown failed: ssl=0xb3b62e00: I/O error during system call, Broken pipe
,D/ConnectivityService(  759): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): ValidatedState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): DefaultState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/ConnectivityService(  759): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,D/ConnectivityService(  759): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,E/WifiConfigStore(  759): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiStateMachine(  759): Start Disconnecting Watchdog 1
E/native  (  759): do suspend true
I/wpa_supplicant( 1025): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/CommandListener(  180): Clearing all IP addresses on wlan0
D/ConnectivityService(  759): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/Nat464Xlat(  759): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  759): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  759): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler(  899): CM callback handler got msg 524292
D/ConnectivityService(  759): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  759): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1619): CM callback handler got msg 524292
D/TelephonyNetworkFactory( 1242): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/ConnectivityService(  759): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): EvaluatingState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Disconnected - quitting
,D/WifiNetworkAgent(  759): NetworkAgent: NetworkAgent channel lost
,V/GLSActivity( 1572): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1572): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/wpa_supplicant( 1025): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,W/NetworkUtils( 1364): OkHttp exception
W/EventLoggerService( 1364): Unable to send logs Error code: 262146
,I/wpa_supplicant( 1025): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1025): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1025): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  759): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  759): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  759): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  759): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  180): Setting iface cfg
,E/WifiStateMachine(  759): Start Dhcp Watchdog 2
,E/native  (  759): do suspend false
,E/WifiStateMachine(  759): scanCount==0 - aborting
,I/dhcpcd  ( 3306): version 5.5.6 starting
,E/dhcpcd  ( 3306): get_duid: Read-only file system
,I/dhcpcd  ( 3306): wlan0: rebinding lease of 192.168.1.114
,D/ConnectivityService(  759): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  759): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  759): MasterInitialState.processMessage what=3
,D/Tethering(  759): MasterInitialState.processMessage what=3
,V/MusicLeanback( 2745): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1619): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1619): onCreate
D/SystemUpdateService( 1619): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.Environment( 1619): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/dhcpcd  ( 3306): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/iu.UploadsManager( 1619): num queued entries: 0
I/iu.UploadsManager( 1619): num updated entries: 0
I/iu.SyncManager( 1619): NEXT; no task
,I/ActivityManager(  759): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3319 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SystemUpdateService( 1619): active receiver: enabled
,I/SystemUpdateService( 1619): showing system update notification
I/Babel   ( 1889): connection state changed from CONNECTED to DISCONNECTED
I/dhcpcd  ( 3306): wlan0: leased 192.168.1.114 for 86400 seconds
,E/GpsLocationProvider(  759): No APN found to select.
,I/ValidateNoPeople(  759): skipping global notification
,V/SystemUpdateService( 1619): retry (wakeup: false) in 3599945 ms
,D/SystemUpdateService( 1619): onDestroy
,E/GpsLocationProvider(  759): No APN found to select.
,I/GAv4    ( 3319): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3319):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3319):   adb logcat -s GAv4
,W/GAv4    ( 3319): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3319): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3319): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,E/native  (  759): do suspend true
,D/ConnectivityService(  759): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  759): Adding iface wlan0 to network 101
,E/WifiStateMachine(  759): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  759): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  759): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  759): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  759): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  759): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  759): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  759): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  759): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  759): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  759):    accepting network in place of null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/CSLegacyTypeTracker(  759): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  759): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  759): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.114/24,fe80::5255:27ff:fef0:fd0b/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService(  759): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler(  899): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1619): CM callback handler got msg 524290
,I/WebViewFactory( 3319): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3319): Time to load native libraries: 1 ms (timestamps 4477-4478)
I/LibraryLoader( 3319): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3319): Binding Chromium to main looper Looper (main, tid 1) {3e966295}
I/LibraryLoader( 3319): Expected native library version number "",actual native library version number ""
I/chromium( 3319): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3319): Initializing chromium process, singleProcess=true
,W/art     ( 3319): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3319): ApplicationContext is null in ApplicationStatus
,W/chromium( 3319): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3319): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 05 Jan 2016 16:25:53 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452011153884], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452011153859]}
E/libEGL  ( 3319): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Validated
D/ConnectivityService(  759): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  759): rematching NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  759): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  759): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler(  899): CM callback handler got msg 524290
D/ConnectivityManager.CallbackHandler( 1619): CM callback handler got msg 524290
D/ConnectivityService(  759): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/TelephonyNetworkFactory( 1242): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/Adreno-EGL( 3319): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/AudioManagerAndroid( 3319): Requires BLUETOOTH permission
,I/NSApplication( 3319): Starting up...
,I/ActivityManager(  759): Killing 2714:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/libprocessgroup(  759): failed to open /acct/uid_10003/pid_2714/cgroup.procs: No such file or directory
,V/MusicLeanback( 2745): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1619): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1619): onCreate
,D/SystemUpdateService( 1619): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1619): active receiver: enabled
,I/iu.Environment( 1619): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/SystemUpdateService( 1619): showing system update notification
,I/iu.UploadsManager( 1619): num queued entries: 0
,I/iu.UploadsManager( 1619): num updated entries: 0
I/iu.SyncManager( 1619): NEXT; no task
,I/ValidateNoPeople(  759): skipping global notification
,V/SystemUpdateService( 1619): retry (wakeup: false) in 3599972 ms
,D/SystemUpdateService( 1619): onDestroy
,I/Babel   ( 1889): connection state changed from DISCONNECTED to CONNECTED
,I/art     (  759): Explicit concurrent mark sweep GC freed 39916(1972KB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 27MB/41MB, paused 1.975ms total 100.072ms
,D/ConnectivityService(  759): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/jxcore-log( 3212): Test app app.js loaded
I/jxcore-log( 3212): 
,I/chromium( 3212): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/ConnectivityService(  759): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  759): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2745): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2745): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1619): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1619): onCreate
,D/SystemUpdateService( 1619): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,E/GpsLocationProvider(  759): No APN found to select.
,I/SystemUpdateService( 1619): active receiver: enabled
,I/SystemUpdateService( 1619): showing system update notification
,I/ValidateNoPeople(  759): skipping global notification
,V/SystemUpdateService( 1619): retry (wakeup: false) in 3599980 ms
,D/SystemUpdateService( 1619): onDestroy
,D/Finsky  ( 2603): [256] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2603): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/GLSActivity( 1572): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1572): Vacuum at: now=1452011166752 tag=VacuumService
,I/PhenotypeConfigurator( 1572): Scheduling Phenotype for one-off execution 5845 seconds from now (1452011166999)
,D/GetConfigurationSnapshotOperation( 1572): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1572): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1572): Using platform SSLCertificateSocketFactory
,V/GLSActivity( 1572): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1572): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ClearcutLoggerApiImpl( 1572): disconnect managed GoogleApiClient
,I/ActivityManager(  759): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=3499 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,I/GAv4    ( 3499): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3499):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3499):   adb logcat -s GAv4
,W/GAv4    ( 3499): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3499): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3499): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  759): Killing 2677:com.android.settings/1000 (adj 15): empty #17
,D/WifiService(  759): Client connection lost with reason: 4
,W/libprocessgroup(  759): failed to open /acct/uid_1000/pid_2677/cgroup.procs: No such file or directory
,I/ActivityManager(  759): Killing 2543:com.google.android.gm/u0a70 (adj 15): empty #17
,W/libprocessgroup(  759): failed to open /acct/uid_10070/pid_2543/cgroup.procs: No such file or directory
,W/bt-smp  ( 2068): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2068): Plain text(LSB ~ MSB) = 94 a4 73 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2068): Encrypted text(LSB ~ MSB) = cb 98 e1 b8 9e cf a2 1e 7a 3a 01 8f b9 35 75 7a 
W/bt-btm  ( 2068): Stopping oneshot timer
,I/EventLogService( 1619): Aggregate from 1452009601260 (log), 1452009601260 (data)
,I/UsageStatsService(  759): User[0] Flushing usage stats to disk
,I/ProcessStatsService(  759): Prepared write state in 3ms
,I/ProcessStatsService(  759): Prepared write state in 3ms
,W/bt-smp  ( 2068): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2068): Plain text(LSB ~ MSB) = 4e d6 63 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2068): Encrypted text(LSB ~ MSB) = 3c c1 97 96 48 94 ed d3 f9 c5 de 1c 9b cd fb 88 
W/bt-btm  ( 2068): Stopping oneshot timer
,I/ProcessStatsService(  759): Pruning old procstats: /data/system/procstats/state-2016-01-04-17-34-14.bin
,I/ActivityManager(  759): Killing 3099:com.android.musicfx/u0a15 (adj 13): empty for 1808s
,I/ActivityManager(  759): Killing 1477:com.google.android.partnersetup/u0a13 (adj 13): empty for 1808s
,I/ActivityManager(  759): Killing 1351:android.process.acore/u0a4 (adj 13): empty for 1808s
,I/ActivityManager(  759): Killing 1994:com.android.providers.calendar/u0a2 (adj 13): empty for 1817s
,I/ActivityManager(  759): Killing 2954:com.google.android.gms:car/u0a8 (adj 15): empty for 1817s
,I/ActivityManager(  759): Killing 1967:com.google.android.calendar/u0a31 (adj 15): empty for 1847s
,W/libprocessgroup(  759): failed to open /acct/uid_10015/pid_3099/cgroup.procs: No such file or directory
,W/libprocessgroup(  759): failed to open /acct/uid_10004/pid_1351/cgroup.procs: No such file or directory
,W/libprocessgroup(  759): failed to open /acct/uid_10002/pid_1994/cgroup.procs: No such file or directory
,W/libprocessgroup(  759): failed to open /acct/uid_10008/pid_2954/cgroup.procs: No such file or directory
,W/libprocessgroup(  759): failed to open /acct/uid_10031/pid_1967/cgroup.procs: No such file or directory
,W/libprocessgroup(  759): failed to open /acct/uid_10013/pid_1477/cgroup.procs: No such file or directory
,V/GLSActivity( 1572): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1572): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  759): Killing 3132:com.google.android.apps.docs/u0a40 (adj 15): empty for 1808s
,W/libprocessgroup(  759): failed to open /acct/uid_10040/pid_3132/cgroup.procs: No such file or directory
,TIME-OUT KILL (timeout was 1800000ms)
```
