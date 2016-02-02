#### Test 575312435db8e90_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
E/Sensors (  190): sns_acm_mr.c(432):Transport error -45
--------- beginning of system
I/DisplayManagerService(  761): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 442.451 x 443.345 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/SurfaceFlinger(  171): Set power mode=0, type=0 flinger=0xb6962000
D/qdhwcomposer(  171): hwc_blank: Blanking display: 0
V/ActivityManager(  761): Display changed displayId=0
D/ChimeraCfgMgr( 1652): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1652): Module APK com.google.android.play.games already loaded
I/GAv4    ( 3067): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3067):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3067):   adb logcat -s GAv4
W/GAv4    ( 3067): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3067): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3067): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 3067): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
E/SQLiteLog( 3067): (283) recovered 25 frames from WAL file /data/data/com.google.android.apps.docs/databases/DocList.db-wal
D/Finsky  ( 2688): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
W/ResourcesManager( 3067): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3067): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  761): Killing 2175:com.google.android.videos/u0a77 (adj 15): empty #17
D/qdhwcomposer(  171): hwc_blank: Done blanking display: 0
D/SurfaceControl(  761): Excessive delay in setPowerMode(): 283ms
V/JNIHelp ( 3067): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/libprocessgroup(  761): failed to open /acct/uid_10077/pid_2175/cgroup.procs: No such file or directory
W/System  ( 3067): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3067): Installed default security provider GmsCore_OpenSSL
V/GLSActivity( 1605): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 1652): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/Icing   ( 1652): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1652): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/Icing   ( 1652): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
,D/AndroidRuntime( 3128): 
D/AndroidRuntime( 3128): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3128): CheckJNI is OFF
D/AndroidRuntime( 3128): Calling main entry com.android.commands.am.Am
I/ActivityManager(  761): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  761): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3148 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3128): Shutting down VM
I/art     (  194): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 405us total 16.888ms
I/art     (  194): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 170us total 13.784ms
I/art     (  194): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 174us total 7.394ms
V/ActivityManager(  761): Display changed displayId=0
I/WebViewFactory( 3148): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3148): Time to load native libraries: 2 ms (timestamps 8044-8046)
I/LibraryLoader( 3148): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3148): Binding Chromium to main looper Looper (main, tid 1) {2064586a}
I/LibraryLoader( 3148): Expected native library version number "",actual native library version number ""
I/chromium( 3148): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3148): Initializing chromium process, singleProcess=true
W/art     ( 3148): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3148): ApplicationContext is null in ApplicationStatus
,W/chromium( 3148): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3148): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 3148): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3148): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  761): Message: 20
D/BluetoothManagerService(  761): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@dbce1c6:true
,W/art     ( 3148): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3148): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3148): CordovaWebView is running on device made by: LGE
,W/art     ( 3148): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3148): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3148): Render dirty regions requested: true
,D/Atlas   ( 3148): Validating map...
,W/chromium( 3148): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3148): Initialized EGL, version 1.4
D/OpenGLRenderer( 3148): Enabling debug mode 0
,W/IInputConnectionWrapper( 3148): showStatusIcon on inactive InputConnection
,I/ActivityManager(  761): Displayed com.test.thalitest/.MainActivity: +429ms (total +46s280ms)
,W/BindingManager( 3148): Cannot call determinedVisibility() - never saw a connection for the pid: 3148
,D/JsMessageQueue( 3148): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3148): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257332480
,I/chromium( 3148): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/ActivityManager(  761): Killing 2497:com.google.android.youtube/u0a80 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10080/pid_2497/cgroup.procs: No such file or directory
,W/jxcore-log( 3148): Initializing JXcore engine
W/jxcore-log( 3148): JXcore engine is ready
,W/Thread-296( 3207): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[7913]" dev="sockfs" ino=7913 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-296( 3207): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-296( 3207): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6649]" dev="sockfs" ino=6649 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-296( 3207): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[19073]" dev="sockfs" ino=19073 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3148): Starting JXcore engine
,W/jxcore-log( 3148): Platform android
W/jxcore-log( 3148): 
W/jxcore-log( 3148): Process ARCH arm
W/jxcore-log( 3148): 
,I/jxcore-log( 3148): JXcore Cordova bridge is ready!
I/jxcore-log( 3148): 
,W/jxcore-log( 3148): JXcore engine is started
,I/jxcore-log( 3148): Toggling radios to true
I/jxcore-log( 3148): 
,D/BluetoothAdapter( 3148): enable(): BT is already enabled..!
,D/WifiService(  761): New client listening to asynchronous messages
,D/WifiService(  761): setWifiEnabled: true pid=3148, uid=10270
E/WifiService(  761): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3148): Radios toggled
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): My device name is: LGE-Nexus 5
I/jxcore-log( 3148): 
,I/wpa_supplicant(  986): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  761): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  761): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
E/native  (  761): do suspend true
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1605): Read error: ssl=0xb3c74e00: I/O error during system call, Connection timed out
V/NativeCrypto( 1605): SSL shutdown failed: ssl=0xb3c74e00: I/O error during system call, Broken pipe
,D/ConnectivityService(  761): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): ValidatedState{ when=-1ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiConfigStore(  761): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  761): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,D/ConnectivityService(  761): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): DefaultState{ when=-1ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Checking http://clients3.google.com/generate_204 on <unknown ssid>
,E/WifiStateMachine(  761): Start Disconnecting Watchdog 1
,I/wpa_supplicant(  986): wlan0: CTRL-EVENT-SCAN-STARTED 
,E/native  (  761): do suspend true
,D/CommandListener(  179): Clearing all IP addresses on wlan0
D/ConnectivityService(  761): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/Nat464Xlat(  761): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/CSLegacyTypeTracker(  761): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityManager.CallbackHandler(  897): CM callback handler got msg 524292
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Disconnected - quitting
D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1652): CM callback handler got msg 524292
,D/ConnectivityService(  761): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1264): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WifiNetworkAgent(  761): NetworkAgent: NetworkAgent channel lost
,I/wpa_supplicant(  986): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant(  986): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant(  986): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant(  986): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  761): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  761): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  761): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiConfigStore(  761): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  179): Setting iface cfg
,E/WifiStateMachine(  761): Start Dhcp Watchdog 2
,E/native  (  761): do suspend false
,E/WifiStateMachine(  761): scanCount==0 - aborting
,I/dhcpcd  ( 3234): version 5.5.6 starting
E/dhcpcd  ( 3234): get_duid: Read-only file system
,I/ActivityManager(  761): Killing 2080:com.google.android.deskclock/u0a38 (adj 15): empty #17
,I/dhcpcd  ( 3234): wlan0: rebinding lease of 192.168.1.114
,W/libprocessgroup(  761): failed to open /acct/uid_10038/pid_2080/cgroup.procs: No such file or directory
,I/dhcpcd  ( 3234): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3234): wlan0: leased 192.168.1.114 for 86400 seconds
,D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  761): MasterInitialState.processMessage what=3
,D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  761): MasterInitialState.processMessage what=3
,V/MusicLeanback( 2796): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1652): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
D/SystemUpdateService( 1652): onCreate
D/SystemUpdateService( 1652): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.Environment( 1652): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
I/iu.UploadsManager( 1652): num queued entries: 0
I/iu.UploadsManager( 1652): num updated entries: 0
I/iu.SyncManager( 1652): NEXT; no task
,I/SystemUpdateService( 1652): active receiver: enabled
,I/SystemUpdateService( 1652): showing system update notification
,I/Babel   ( 1936): connection state changed from CONNECTED to DISCONNECTED
,I/ActivityManager(  761): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3273 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/GpsLocationProvider(  761): No APN found to select.
,E/native  (  761): do suspend true
,D/ConnectivityService(  761): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  761): Adding iface wlan0 to network 101
,E/WifiStateMachine(  761): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  761): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  761): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  761): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  761): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  761): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  761): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  761): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  761): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  761): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  761):    accepting network in place of null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/CSLegacyTypeTracker(  761): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  761): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.114/24,fe80::5255:27ff:fef0:fd0b/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  761): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  897): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1652): CM callback handler got msg 524290
,E/GpsLocationProvider(  761): No APN found to select.
,I/ValidateNoPeople(  761): skipping global notification
,V/SystemUpdateService( 1652): retry (wakeup: false) in 3599860 ms
,D/SystemUpdateService( 1652): onDestroy
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 02 Feb 2016 11:24:35 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454412275949], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454412275934]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Validated
,D/ConnectivityService(  761): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  761): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  761): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  761): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,I/GAv4    ( 3273): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3273):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3273):   adb logcat -s GAv4
D/ConnectivityManager.CallbackHandler(  897): CM callback handler got msg 524290
,D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1652): CM callback handler got msg 524290
,D/TelephonyNetworkFactory( 1264): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,W/GAv4    ( 3273): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3273): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3273): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 3273): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3273): Time to load native libraries: 1 ms (timestamps 3776-3777)
I/LibraryLoader( 3273): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3273): Binding Chromium to main looper Looper (main, tid 1) {25add5cc}
,I/LibraryLoader( 3273): Expected native library version number "",actual native library version number ""
I/chromium( 3273): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3273): Initializing chromium process, singleProcess=true
W/art     ( 3273): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3273): ApplicationContext is null in ApplicationStatus
,W/chromium( 3273): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3273): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3273): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3273): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/AudioManagerAndroid( 3273): Requires BLUETOOTH permission
,I/NSApplication( 3273): Starting up...
,I/ActivityManager(  761): Killing 2656:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10069/pid_2656/cgroup.procs: No such file or directory
,V/MusicLeanback( 2796): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1652): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,I/jxcore-log( 3148): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3148): 
D/SystemUpdateService( 1652): onCreate
D/SystemUpdateService( 1652): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.Environment( 1652): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/iu.UploadsManager( 1652): num queued entries: 0
I/iu.UploadsManager( 1652): num updated entries: 0
I/iu.SyncManager( 1652): NEXT; no task
,I/SystemUpdateService( 1652): active receiver: enabled
,I/SystemUpdateService( 1652): showing system update notification
,I/ValidateNoPeople(  761): skipping global notification
,V/SystemUpdateService( 1652): retry (wakeup: false) in 3599976 ms
,D/SystemUpdateService( 1652): onDestroy
,I/Babel   ( 1936): connection state changed from DISCONNECTED to CONNECTED
,D/ConnectivityService(  761): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/jxcore-log( 3148): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
I/jxcore-log( 3148): 
,I/jxcore-log( 3148): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3148): 
,D/Finsky  ( 2688): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/GLSActivity( 1605): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  761): Explicit concurrent mark sweep GC freed 49311(2MB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 27MB/41MB, paused 929us total 60.395ms
,D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  761): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2796): type=WIFI subType= reason=null isConnected=true
V/GLSActivity( 1605): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1605): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/MusicLeanback( 2796): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,E/GpsLocationProvider(  761): No APN found to select.
,I/SystemUpdateService( 1652): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1652): onCreate
,D/SystemUpdateService( 1652): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1652): active receiver: enabled
,I/SystemUpdateService( 1652): showing system update notification
,I/ValidateNoPeople(  761): skipping global notification
,V/SystemUpdateService( 1652): retry (wakeup: false) in 3599986 ms
,D/SystemUpdateService( 1652): onDestroy
,V/GLSActivity( 1605): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 2688): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 2688): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 2688): untagSocket(37) failed with errno -22
D/Finsky  ( 2688): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,V/GLSActivity( 1605): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  761): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=3395 uid=10008 gids={50008, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/ResourcesManager( 3395): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 3395): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 3395): VM with version 2.1.0 has multidex support
,I/MultiDex( 3395): install
I/MultiDex( 3395): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 3395): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/qtaguid ( 2688): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 2688): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 2688): untagSocket(37) failed with errno -22
,W/ActivityThread( 3395): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 3395): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2c0dcd9c: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 3395): Installed default security provider GmsCore_OpenSSL
,D/ChimeraCfgMgr( 3395): Reading stored module config
,D/WearableService( 1605): callingUid 10008, callindPid: 1605
,E/MDM     ( 1605): [235] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/ChimeraCfgMgr( 3395): Loading module com.google.android.gms.car from APK com.google.android.gms
,D/AuthorizationBluetoothService( 1605): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1605): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/LocationInitializer( 1652): Restart initialization of location
,W/GCoreFlp( 1605): No location to return for getLastLocation()
W/FusedLocationProvider( 1605): location=null
,D/CAR.SERVICE( 3395): Connecting to CarCallService...
,D/NativeLibraryUtils( 3395): Install completed successfully. count=14 extracted=0
,I/art     ( 3395): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 3395): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/CAR.SERVICE( 3395): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service( 3395): Creating a new CarCallService.
D/CAR.TEL.PhoneAdapter( 3395): Creating a new PhoneAdapter instance
,W/ActivityManager(  761): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 3395): setListener: com.google.android.gms.car.dn@188a211b
,W/ActivityManager(  761): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 3395): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 3395): Starting CarCallService with initial phone null
,D/CAR.SERVICE( 3395): Package validated; name: com.android.vending
,V/Finsky  ( 2688): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,V/GLSActivity( 1605): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 2688): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 2688): Untagging socket 37 failed errno=-22
,W/NetworkManagementSocketTagger( 2688): untagSocket(37) failed with errno -22
,W/ResourcesManager( 2688): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 2688): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 2688): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/Finsky  ( 2688): [1] DailyHygiene.access$600: Logging device features
,D/DeviceConnectionService( 1605): client connected with version: 8296000
,D/Finsky  ( 2688): [271] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,V/GLSActivity( 1605): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2688): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/Finsky  ( 2688): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,I/ActivityManager(  761): Killing 2606:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10045/pid_2606/cgroup.procs: No such file or directory
,I/jxcore-log( 3148): Test app app.js loaded
I/jxcore-log( 3148): 
,I/chromium( 3148): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3148): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3148): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3148): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3148): 	Bluetooth MAC address: null, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3148): 	Discovery mode: BLE, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3148): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3148): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3148): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3148): 	Scan mode: 1
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3148): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e5da10d added. We now have 1 listener(s)
,I/jxcore-log( 3148): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 3148): 
,D/CAR.SERVICE( 3395): mConnectedToCar = false, abort
,E/ActivityThread( 3395): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@87f40a3 that was originally bound here
E/ActivityThread( 3395): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@87f40a3 that was originally bound here
E/ActivityThread( 3395): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3395): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3395): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3395): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3395): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3395): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3395): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3395): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3395): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3395): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 3395): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 3395): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 3395): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 3395): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2731)
E/ActivityThread( 3395): 	at android.app.ActivityThread.access$1800(ActivityThread.java:144)
E/ActivityThread( 3395): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1361)
E/ActivityThread( 3395): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3395): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3395): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3395): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3395): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3395): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3395): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
,E/ActivityThread( 3395): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@3ddd7f2a that was originally bound here
E/ActivityThread( 3395): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@3ddd7f2a that was originally bound here
E/ActivityThread( 3395): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3395): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3395): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3395): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3395): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3395): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3395): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3395): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 3395): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 3395): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 3395): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 3395): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 3395): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2758)
E/ActivityThread( 3395): 	at android.app.ActivityThread.access$1900(ActivityThread.java:144)
E/ActivityThread( 3395): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
E/ActivityThread( 3395): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3395): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3395): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3395): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3395): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3395): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3395): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
,W/ActivityManager(  761): Unbind failed: could not find connection for android.os.BinderProxy@18d22800
,D/Finsky  ( 2688): [260] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2688): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/GLSActivity( 1605): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1605): Vacuum at: now=1454412310336 tag=VacuumService
,I/PhenotypeConfigurator( 1605): Scheduling Phenotype for one-off execution 12256 seconds from now (1454412310653)
,D/GetConfigurationSnapshotOperation( 1605): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1605): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1605): Using platform SSLCertificateSocketFactory
,I/art     ( 1605): Explicit concurrent mark sweep GC freed 49078(2MB) AllocSpace objects, 12(192KB) LOS objects, 39% free, 21MB/36MB, paused 1.058ms total 54.366ms
,V/GLSActivity( 1605): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1605): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ClearcutLoggerApiImpl( 1605): disconnect managed GoogleApiClient
,I/ActivityManager(  761): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=3537 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,I/GAv4    ( 3537): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3537):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3537):   adb logcat -s GAv4
,W/GAv4    ( 3537): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3537): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3537): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  761): Killing 2766:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10003/pid_2766/cgroup.procs: No such file or directory
,I/ActivityManager(  761): Killing 2748:com.android.settings/1000 (adj 15): empty #17
,D/WifiService(  761): Client connection lost with reason: 4
,W/libprocessgroup(  761): failed to open /acct/uid_1000/pid_2748/cgroup.procs: No such file or directory
,W/bt-smp  ( 2104): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2104): Plain text(LSB ~ MSB) = f9 10 60 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2104): Encrypted text(LSB ~ MSB) = 1e 8b d6 48 0f 90 d3 ed 4b ca f8 97 b8 a3 32 92 
,W/bt-btm  ( 2104): Stopping oneshot timer
,I/UsageStatsService(  761): User[0] Flushing usage stats to disk
,TIME-OUT KILL (timeout was 1200000ms)
```
