#### Test 575312431be71d2_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
I/GAv4    ( 3040): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3040):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3040):   adb logcat -s GAv4
D/ChimeraCfgMgr( 1648): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1648): Module APK com.google.android.play.games already loaded
W/GAv4    ( 3040): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3040): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3040): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 3040): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
D/Finsky  ( 2655): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
W/ResourcesManager( 3040): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3040): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  760): Killing 2362:com.lge.SprintHiddenMenu/1000 (adj 15): empty #17
V/JNIHelp ( 3040): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/System  ( 3040): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3040): Installed default security provider GmsCore_OpenSSL
W/libprocessgroup(  760): failed to open /acct/uid_1000/pid_2362/cgroup.procs: No such file or directory
V/GLSActivity( 1602): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 1648): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/Icing   ( 1648): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1648): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/Icing   ( 1648): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
,D/AndroidRuntime( 3090): 
D/AndroidRuntime( 3090): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3090): CheckJNI is OFF
D/AndroidRuntime( 3090): Calling main entry com.android.commands.am.Am
I/ActivityManager(  760): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  760): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3116 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3090): Shutting down VM
I/art     (  195): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 386us total 16.351ms
I/art     (  195): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 361us total 14.940ms
I/art     (  195): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 360us total 15.586ms
V/ActivityManager(  760): Display changed displayId=0
I/WebViewFactory( 3116): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3116): Time to load native libraries: 2 ms (timestamps 8394-8396)
I/LibraryLoader( 3116): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3116): Binding Chromium to main looper Looper (main, tid 1) {17acc202}
I/LibraryLoader( 3116): Expected native library version number "",actual native library version number ""
I/chromium( 3116): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3116): Initializing chromium process, singleProcess=true
W/art     ( 3116): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3116): ApplicationContext is null in ApplicationStatus
W/chromium( 3116): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3116): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3116): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3116): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  760): Message: 20
D/BluetoothManagerService(  760): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2bdb940d:true
,W/art     ( 3116): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3116): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3116): CordovaWebView is running on device made by: LGE
,W/art     ( 3116): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3116): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3116): Render dirty regions requested: true
,D/Atlas   ( 3116): Validating map...
,W/chromium( 3116): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3116): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3116): Enabling debug mode 0
,W/BindingManager( 3116): Cannot call determinedVisibility() - never saw a connection for the pid: 3116
,W/IInputConnectionWrapper( 3116): showStatusIcon on inactive InputConnection
,I/ActivityManager(  760): Displayed com.test.thalitest/.MainActivity: +384ms (total +46s566ms)
,D/JsMessageQueue( 3116): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3116): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257332480
,I/chromium( 3116): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/ActivityManager(  760): Killing 2459:com.google.android.youtube/u0a80 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10080/pid_2459/cgroup.procs: No such file or directory
,I/ActivityManager(  760): Killing 2079:com.google.android.deskclock/u0a38 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10038/pid_2079/cgroup.procs: No such file or directory
,W/jxcore-log( 3116): Initializing JXcore engine
W/jxcore-log( 3116): JXcore engine is ready
,W/Thread-296( 3165): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[9354]" dev="sockfs" ino=9354 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/Thread-296( 3165): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3095 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-296( 3165): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[10367]" dev="sockfs" ino=10367 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-296( 3165): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[18876]" dev="sockfs" ino=18876 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3116): Starting JXcore engine
,W/jxcore-log( 3116): Platform android
W/jxcore-log( 3116): 
W/jxcore-log( 3116): Process ARCH arm
W/jxcore-log( 3116): 
,I/jxcore-log( 3116): JXcore Cordova bridge is ready!
I/jxcore-log( 3116): 
,W/jxcore-log( 3116): JXcore engine is started
,I/jxcore-log( 3116): Toggling radios to true
I/jxcore-log( 3116): 
,D/BluetoothAdapter( 3116): enable(): BT is already enabled..!
,D/WifiService(  760): New client listening to asynchronous messages
,D/WifiService(  760): setWifiEnabled: true pid=3116, uid=10270
E/WifiService(  760): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3116): Radios toggled
I/jxcore-log( 3116): 
I/jxcore-log( 3116): My device name is: LGE-Nexus 5
I/jxcore-log( 3116): 
,I/wpa_supplicant( 1004): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  760): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  760): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/native  (  760): do suspend true
,D/CommandListener(  180): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1602): Read error: ssl=0x9b660e00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1602): SSL shutdown failed: ssl=0x9b660e00: I/O error during system call, Broken pipe
D/ConnectivityService(  760): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): ValidatedState{ when=-5ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): DefaultState{ when=-5ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/ConnectivityService(  760): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  760): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,E/WifiConfigStore(  760): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiStateMachine(  760): Start Disconnecting Watchdog 1
,I/wpa_supplicant( 1004): wlan0: CTRL-EVENT-SCAN-STARTED 
,E/native  (  760): do suspend true
,D/ConnectivityService(  760): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/Nat464Xlat(  760): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  760): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Disconnected - quitting
D/ConnectivityManager.CallbackHandler(  898): CM callback handler got msg 524292
,D/ConnectivityManager.CallbackHandler( 1648): CM callback handler got msg 524292
,D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  760): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  760): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,D/CommandListener(  180): Clearing all IP addresses on wlan0
,D/TelephonyNetworkFactory( 1266): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WifiNetworkAgent(  760): NetworkAgent: NetworkAgent channel lost
,I/wpa_supplicant( 1004): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant( 1004): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1004): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1004): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  760): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  760): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  760): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  760): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  180): Setting iface cfg
E/WifiStateMachine(  760): Start Dhcp Watchdog 2
,E/native  (  760): do suspend false
,E/WifiStateMachine(  760): scanCount==0 - aborting
,I/dhcpcd  ( 3211): version 5.5.6 starting
E/dhcpcd  ( 3211): get_duid: Read-only file system
,I/dhcpcd  ( 3211): wlan0: rebinding lease of 192.168.1.114
,I/dhcpcd  ( 3211): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3211): wlan0: leased 192.168.1.114 for 86400 seconds
,D/Finsky  ( 2655): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/GLSActivity( 1602): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1602): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1602): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1602): Explicit concurrent mark sweep GC freed 32786(2029KB) AllocSpace objects, 19(304KB) LOS objects, 39% free, 21MB/35MB, paused 783us total 32.077ms
,E/native  (  760): do suspend true
,D/ConnectivityService(  760): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,E/WifiStateMachine(  760): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/ConnectivityService(  760): Adding iface wlan0 to network 101
,E/ConnectivityService(  760): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  760): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  760): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  760): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  760): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  760): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  760): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  760): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  760): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  760):    accepting network in place of null
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/CSLegacyTypeTracker(  760): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/ConnectivityService(  760): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.114/24,fe80::5255:27ff:fef0:fd0b/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  760): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  898): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1648): CM callback handler got msg 524290
,D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  760): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2748): type=WIFI subType= reason=null isConnected=true
,D/Tethering(  760): MasterInitialState.processMessage what=3
,V/MusicLeanback( 2748): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,E/GpsLocationProvider(  760): No APN found to select.
,I/NetworkMonitor( 2748): type=WIFI subType= reason=null isConnected=true
,I/SystemUpdateService( 1648): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1648): onCreate
,D/SystemUpdateService( 1648): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
I/SystemUpdateService( 1648): active receiver: enabled
,I/SystemUpdateService( 1648): showing system update notification
,E/GpsLocationProvider(  760): No APN found to select.
,I/ValidateNoPeople(  760): skipping global notification
,V/SystemUpdateService( 1648): retry (wakeup: false) in 3599977 ms
,I/ActivityManager(  760): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3267 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/SystemUpdateService( 1648): onDestroy
,V/GLSActivity( 1602): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 2655): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 2655): Untagging socket 37 failed errno=-22
,W/NetworkManagementSocketTagger( 2655): untagSocket(37) failed with errno -22
,D/Finsky  ( 2655): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,V/GLSActivity( 1602): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  760): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=3288 uid=10008 gids={50008, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/GAv4    ( 3267): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3267):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3267):   adb logcat -s GAv4
,W/GAv4    ( 3267): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/ResourcesManager( 3288): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3288): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/GAv4    ( 3267): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,I/MultiDex( 3288): VM with version 2.1.0 has multidex support
I/MultiDex( 3288): install
I/MultiDex( 3288): VM has multidex support, MultiDex support library is disabled.
,W/GAv4    ( 3267): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,V/JNIHelp ( 3288): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 3288): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 3288): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@25fb974: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3288): Installed default security provider GmsCore_OpenSSL
,I/qtaguid ( 2655): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 2655): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 2655): untagSocket(37) failed with errno -22
,D/ChimeraCfgMgr( 3288): Reading stored module config
,D/ChimeraCfgMgr( 3288): Loading module com.google.android.gms.car from APK com.google.android.gms
,I/art     (  760): Explicit concurrent mark sweep GC freed 41605(2030KB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 27MB/41MB, paused 1.038ms total 83.479ms
,D/CAR.SERVICE( 3288): Connecting to CarCallService...
,I/art     ( 3288): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 3288): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/NativeLibraryUtils( 3288): Install completed successfully. count=14 extracted=0
,I/WebViewFactory( 3267): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,D/CAR.SERVICE( 3288): com.google.android.projection.gearhead isn't installed.
,I/LibraryLoader( 3267): Time to load native libraries: 9 ms (timestamps 4136-4145)
I/LibraryLoader( 3267): Expected native library version number "",actual native library version number ""
D/CAR.TEL.Service( 3288): Creating a new CarCallService.
D/CAR.TEL.PhoneAdapter( 3288): Creating a new PhoneAdapter instance
W/ActivityManager(  760): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 3288): setListener: com.google.android.gms.car.dn@1bb3ded3
V/WebViewChromiumFactoryProvider( 3267): Binding Chromium to main looper Looper (main, tid 1) {301e67a4}
W/ActivityManager(  760): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 3288): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 3288): Starting CarCallService with initial phone null
I/LibraryLoader( 3267): Expected native library version number "",actual native library version number ""
I/chromium( 3267): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3267): Initializing chromium process, singleProcess=true
W/art     ( 3267): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3267): ApplicationContext is null in ApplicationStatus
,W/chromium( 3267): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3267): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3267): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3267): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/CAR.SERVICE( 3288): Package validated; name: com.android.vending
,W/AudioManagerAndroid( 3267): Requires BLUETOOTH permission
,I/NSApplication( 3267): Starting up...
,V/Finsky  ( 2655): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,V/MusicLeanback( 2748): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1648): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1648): onCreate
,D/SystemUpdateService( 1648): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1648): active receiver: enabled
D/ConnectivityService(  760): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/SystemUpdateService( 1648): showing system update notification
,I/ValidateNoPeople(  760): skipping global notification
,V/SystemUpdateService( 1648): retry (wakeup: false) in 3599968 ms
,D/WearableService( 1602): callingUid 10008, callindPid: 1602
,D/SystemUpdateService( 1648): onDestroy
,E/MDM     ( 1602): [224] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1602): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 1648): Restart initialization of location
,V/GLSActivity( 1602): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1602): No location to return for getLastLocation()
W/FusedLocationProvider( 1602): location=null
,I/jxcore-log( 3116): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3116): 
,V/GLSActivity( 1602): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 2655): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 2655): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 2655): untagSocket(37) failed with errno -22
,W/ResourcesManager( 2655): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2655): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 2655): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/Finsky  ( 2655): [1] DailyHygiene.access$600: Logging device features
,D/DeviceConnectionService( 1602): client connected with version: 8296000
,D/Finsky  ( 2655): [265] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,V/GLSActivity( 1602): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2655): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 2655): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,I/jxcore-log( 3116): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 3116): 
,I/jxcore-log( 3116): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 3116): 
,I/jxcore-log( 3116): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
I/jxcore-log( 3116): 
,I/jxcore-log( 3116): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3116): 
,I/ActivityManager(  760): Killing 2567:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,I/ActivityManager(  760): Killing 2620:com.google.android.gm.exchange/u0a69 (adj 15): empty #18
,W/libprocessgroup(  760): failed to open /acct/uid_10045/pid_2567/cgroup.procs: No such file or directory
W/libprocessgroup(  760): failed to open /acct/uid_10069/pid_2620/cgroup.procs: No such file or directory
,D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  760): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2748): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2748): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1648): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1648): onCreate
,D/SystemUpdateService( 1648): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1648): active receiver: enabled
,E/GpsLocationProvider(  760): No APN found to select.
,I/SystemUpdateService( 1648): showing system update notification
,I/ValidateNoPeople(  760): skipping global notification
,V/SystemUpdateService( 1648): retry (wakeup: false) in 3599960 ms
,D/SystemUpdateService( 1648): onDestroy
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): EvaluatingState{ when=-2ms what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 02 Feb 2016 13:17:36 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454419056840], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454419056746]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Validated
,D/ConnectivityService(  760): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  760): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  760): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  760): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  898): CM callback handler got msg 524290
,D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 1648): CM callback handler got msg 524290
,D/TelephonyNetworkFactory( 1266): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/CAR.SERVICE( 3288): mConnectedToCar = false, abort
,E/ActivityThread( 3288): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@3c1adf5b that was originally bound here
E/ActivityThread( 3288): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@3c1adf5b that was originally bound here
E/ActivityThread( 3288): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3288): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3288): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3288): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3288): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3288): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3288): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3288): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3288): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3288): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 3288): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 3288): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 3288): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 3288): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2731)
E/ActivityThread( 3288): 	at android.app.ActivityThread.access$1800(ActivityThread.java:144)
E/ActivityThread( 3288): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1361)
E/ActivityThread( 3288): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3288): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3288): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3288): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3288): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3288): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3288): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
,E/ActivityThread( 3288): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@387540c2 that was originally bound here
E/ActivityThread( 3288): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@387540c2 that was originally bound here
E/ActivityThread( 3288): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3288): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3288): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3288): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3288): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3288): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3288): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3288): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 3288): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 3288): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 3288): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 3288): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 3288): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2758)
E/ActivityThread( 3288): 	at android.app.ActivityThread.access$1900(ActivityThread.java:144)
E/ActivityThread( 3288): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
E/ActivityThread( 3288): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3288): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3288): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3288): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3288): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3288): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3288): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
W/ActivityManager(  760): Unbind failed: could not find connection for android.os.BinderProxy@3efbe9a1
,I/jxcore-log( 3116): Test app app.js loaded
I/jxcore-log( 3116): 
,I/chromium( 3116): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3116): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3116): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3116): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3116): 	Bluetooth MAC address: 34:FC:EF:11:AE:67, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3116): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3116): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3116): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3116): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3116): 	Scan mode: 1
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3116): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12b4b905 added. We now have 1 listener(s)
,I/jxcore-log( 3116): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 3116): 
,D/Finsky  ( 2655): [255] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 2655): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/GLSActivity( 1602): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1602): Vacuum at: now=1454419082889 tag=VacuumService
,I/PhenotypeConfigurator( 1602): Scheduling Phenotype for one-off execution 13485 seconds from now (1454419083242)
,D/GetConfigurationSnapshotOperation( 1602): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1602): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1602): Using platform SSLCertificateSocketFactory
,D/HeadsetStateMachine( 2111): Disconnected process message: 10, size: 0
,I/ClearcutLoggerApiImpl( 1602): disconnect managed GoogleApiClient
,I/ActivityManager(  760): Killing 2728:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10003/pid_2728/cgroup.procs: No such file or directory
,I/art     (  760): Explicit concurrent mark sweep GC freed 36950(1649KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 27MB/41MB, paused 985us total 51.489ms
,I/ActivityManager(  760): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=3511 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,I/GAv4    ( 3511): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3511):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3511):   adb logcat -s GAv4
,W/GAv4    ( 3511): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3511): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3511): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  760): Killing 2709:com.android.settings/1000 (adj 15): empty #17
,D/WifiService(  760): Client connection lost with reason: 4
,W/libprocessgroup(  760): failed to open /acct/uid_1000/pid_2709/cgroup.procs: No such file or directory
,W/bt-smp  ( 2111): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2111): Plain text(LSB ~ MSB) = 40 e7 70 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2111): Encrypted text(LSB ~ MSB) = 58 5b 79 89 d1 e7 ad 25 f3 66 39 6c 24 66 47 67 
,W/bt-btm  ( 2111): Stopping oneshot timer
,I/UsageStatsService(  760): User[0] Flushing usage stats to disk
,TIME-OUT KILL (timeout was 1200000ms)
```
