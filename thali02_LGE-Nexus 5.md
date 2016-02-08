#### Test 586024278176cca_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
D/ChimeraCfgMgr( 1657): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1657): Module APK com.google.android.play.games already loaded
I/GAv4    ( 3222): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3222):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3222):   adb logcat -s GAv4
W/GAv4    ( 3222): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3222): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3222): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 3222): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
E/SQLiteLog( 3222): (283) recovered 24 frames from WAL file /data/data/com.google.android.apps.docs/databases/DocList.db-wal
D/Finsky  ( 2797): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
W/ResourcesManager( 3222): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3222): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  759): Killing 2574:com.google.android.youtube/u0a80 (adj 15): empty #17
E/Sensors (  189): sns_acm_mr.c(432):Transport error -45
I/DisplayManagerService(  759): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 442.451 x 443.345 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/SurfaceFlinger(  171): Set power mode=0, type=0 flinger=0xb6962000
D/qdhwcomposer(  171): hwc_blank: Blanking display: 0
V/ActivityManager(  759): Display changed displayId=0
V/JNIHelp ( 3222): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/libprocessgroup(  759): failed to open /acct/uid_10080/pid_2574/cgroup.procs: No such file or directory
W/System  ( 3222): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3222): Installed default security provider GmsCore_OpenSSL
V/GLSActivity( 1619): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 1657): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
D/qdhwcomposer(  171): hwc_blank: Done blanking display: 0
D/SurfaceControl(  759): Excessive delay in setPowerMode(): 283ms
I/Icing   ( 1657): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1657): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/Icing   ( 1657): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
,D/AndroidRuntime( 3299): 
D/AndroidRuntime( 3299): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3299): CheckJNI is OFF
D/AndroidRuntime( 3299): Calling main entry com.android.commands.am.Am
I/ActivityManager(  759): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  759): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3320 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3299): Shutting down VM
V/ActivityManager(  759): Display changed displayId=0
I/WebViewFactory( 3320): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3320): Time to load native libraries: 1 ms (timestamps 3939-3940)
I/LibraryLoader( 3320): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3320): Binding Chromium to main looper Looper (main, tid 1) {2688391b}
I/LibraryLoader( 3320): Expected native library version number "",actual native library version number ""
I/chromium( 3320): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3320): Initializing chromium process, singleProcess=true
W/art     ( 3320): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3320): ApplicationContext is null in ApplicationStatus
,W/chromium( 3320): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3320): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3320): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3320): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  759): Message: 20
D/BluetoothManagerService(  759): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3c65e728:true
,W/art     ( 3320): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3320): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3320): CordovaWebView is running on device made by: LGE
,W/art     ( 3320): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3320): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3320): Render dirty regions requested: true
,D/Atlas   ( 3320): Validating map...
,W/chromium( 3320): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3320): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3320): Enabling debug mode 0
,I/Keyboard.Facilitator( 1067): onFinishInput()
,W/IInputConnectionWrapper( 3320): showStatusIcon on inactive InputConnection
,I/ActivityManager(  759): Displayed com.test.thalitest/.MainActivity: +431ms (total +42s484ms)
,W/BindingManager( 3320): Cannot call determinedVisibility() - never saw a connection for the pid: 3320
,D/JsMessageQueue( 3320): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3320): JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1258388736
,I/chromium( 3320): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/ActivityManager(  759): Killing 2122:com.google.android.deskclock/u0a38 (adj 15): empty #17
,W/libprocessgroup(  759): failed to open /acct/uid_10038/pid_2122/cgroup.procs: No such file or directory
,I/ActivityManager(  759): Killing 2762:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
,W/libprocessgroup(  759): failed to open /acct/uid_10069/pid_2762/cgroup.procs: No such file or directory
,W/jxcore-log( 3320): Initializing JXcore engine
W/jxcore-log( 3320): JXcore engine is ready
,W/Thread-316( 3369): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[7962]" dev="sockfs" ino=7962 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-316( 3369): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-316( 3369): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8409]" dev="sockfs" ino=8409 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-316( 3369): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[21546]" dev="sockfs" ino=21546 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3320): Starting JXcore engine
,W/jxcore-log( 3320): Platform android
W/jxcore-log( 3320): 
W/jxcore-log( 3320): Process ARCH arm
W/jxcore-log( 3320): 
,I/jxcore-log( 3320): JXcore Cordova bridge is ready!
I/jxcore-log( 3320): 
,W/jxcore-log( 3320): JXcore engine is started
,I/jxcore-log( 3320): Toggling radios to true
I/jxcore-log( 3320): 
,D/BluetoothAdapter( 3320): enable(): BT is already enabled..!
,D/WifiService(  759): New client listening to asynchronous messages
,D/WifiService(  759): setWifiEnabled: true pid=3320, uid=10270
E/WifiService(  759): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3320): Radios toggled
I/jxcore-log( 3320): 
I/jxcore-log( 3320): My device name is: LGE-Nexus 5
I/jxcore-log( 3320): 
,I/wpa_supplicant( 1030): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  759): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  759): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/native  (  759): do suspend true
,D/CommandListener(  178): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1619): Read error: ssl=0xb3b42e00: I/O error during system call, Connection timed out
V/NativeCrypto( 1619): SSL shutdown failed: ssl=0xb3b42e00: I/O error during system call, Broken pipe
,D/ConnectivityService(  759): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): ValidatedState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): DefaultState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,E/WifiConfigStore(  759): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  759): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  759): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
E/WifiStateMachine(  759): Start Disconnecting Watchdog 1
,I/wpa_supplicant( 1030): wlan0: CTRL-EVENT-SCAN-STARTED 
,E/native  (  759): do suspend true
,D/ConnectivityService(  759): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): EvaluatingState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  178): Clearing all IP addresses on wlan0
,D/ConnectivityService(  759): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/Nat464Xlat(  759): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/CSLegacyTypeTracker(  759): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Disconnected - quitting
D/ConnectivityManager.CallbackHandler(  897): CM callback handler got msg 524292
,D/ConnectivityManager.CallbackHandler( 1657): CM callback handler got msg 524292
D/ConnectivityService(  759): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  759): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  759): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1224): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WifiNetworkAgent(  759): NetworkAgent: NetworkAgent channel lost
,I/wpa_supplicant( 1030): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant( 1030): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1030): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1030): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  759): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  759): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  759): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiConfigStore(  759): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  178): Setting iface cfg
,E/WifiStateMachine(  759): Start Dhcp Watchdog 2
,E/native  (  759): do suspend false
,E/WifiStateMachine(  759): scanCount==0 - aborting
,I/dhcpcd  ( 3400): version 5.5.6 starting
E/dhcpcd  ( 3400): get_duid: Read-only file system
,I/dhcpcd  ( 3400): wlan0: rebinding lease of 192.168.1.114
,I/dhcpcd  ( 3400): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3400): wlan0: leased 192.168.1.114 for 86400 seconds
,E/native  (  759): do suspend true
,D/ConnectivityService(  759): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  759): Adding iface wlan0 to network 101
,E/WifiStateMachine(  759): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  759): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  759): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  759): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/ConnectivityService(  759): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  759): Setting Dns servers for network 101 to [/192.168.1.1]
D/Nat464Xlat(  759): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  759): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  759): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  759): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  759):    accepting network in place of null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): DefaultState{ when=-2ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/CSLegacyTypeTracker(  759): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  759): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  759): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService(  759): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  897): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1657): CM callback handler got msg 524290
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 08 Feb 2016 12:36:36 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454934996186], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454934996167]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Validated
,D/ConnectivityService(  759): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  759): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  759): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  759): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  897): CM callback handler got msg 524290
D/ConnectivityService(  759): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/TelephonyNetworkFactory( 1224): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1657): CM callback handler got msg 524290
,D/Finsky  ( 2797): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/GLSActivity( 1619): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1619): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1619): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  759): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  759): MasterInitialState.processMessage what=3
,D/ConnectivityService(  759): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  759): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2912): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2912): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,E/GpsLocationProvider(  759): No APN found to select.
I/NetworkMonitor( 2912): type=WIFI subType= reason=null isConnected=true
,I/SystemUpdateService( 1657): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1657): onCreate
,E/GpsLocationProvider(  759): No APN found to select.
,D/SystemUpdateService( 1657): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1657): active receiver: enabled
,V/GLSActivity( 1619): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/SystemUpdateService( 1657): showing system update notification
,I/ValidateNoPeople(  759): skipping global notification
,V/SystemUpdateService( 1657): retry (wakeup: false) in 3599980 ms
,D/Nat464Xlat(  759): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  759): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,I/ActivityManager(  759): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3450 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ConnectivityManager.CallbackHandler(  897): CM callback handler got msg 524295
,D/SystemUpdateService( 1657): onDestroy
,D/ConnectivityManager.CallbackHandler( 1657): CM callback handler got msg 524295
,I/qtaguid ( 2797): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 2797): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 2797): untagSocket(37) failed with errno -22
,D/Finsky  ( 2797): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,D/ConnectivityService(  759): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,V/GLSActivity( 1619): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  759): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=3470 uid=10008 gids={50008, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/ResourcesManager( 3470): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3470): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/art     (  759): Explicit concurrent mark sweep GC freed 51530(2MB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 27MB/41MB, paused 1.104ms total 79.067ms
,I/MultiDex( 3470): VM with version 2.1.0 has multidex support
I/MultiDex( 3470): install
I/MultiDex( 3470): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 3470): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/GAv4    ( 3450): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3450):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3450):   adb logcat -s GAv4
,W/GAv4    ( 3450): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3450): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3450): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/ActivityThread( 3470): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 3470): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@18cef565: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3470): Installed default security provider GmsCore_OpenSSL
,D/ChimeraCfgMgr( 3470): Reading stored module config
,D/ChimeraCfgMgr( 3470): Loading module com.google.android.gms.car from APK com.google.android.gms
,D/NativeLibraryUtils( 3470): Install completed successfully. count=14 extracted=0
,D/CAR.SERVICE( 3470): Connecting to CarCallService...
,I/art     ( 3470): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 3470): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/qtaguid ( 2797): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 2797): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 2797): untagSocket(37) failed with errno -22
,I/WebViewFactory( 3450): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3450): Time to load native libraries: 1 ms (timestamps 9825-9826)
I/LibraryLoader( 3450): Expected native library version number "",actual native library version number ""
D/CAR.SERVICE( 3470): com.google.android.projection.gearhead isn't installed.
,V/WebViewChromiumFactoryProvider( 3450): Binding Chromium to main looper Looper (main, tid 1) {370101d5}
I/LibraryLoader( 3450): Expected native library version number "",actual native library version number ""
I/chromium( 3450): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,D/CAR.TEL.Service( 3470): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 3470): Creating a new PhoneAdapter instance
,W/ActivityManager(  759): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 3470): setListener: com.google.android.gms.car.dn@2d13df78
,W/ActivityManager(  759): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 3470): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 3470): Starting CarCallService with initial phone null
,I/BrowserStartupController( 3450): Initializing chromium process, singleProcess=true
W/art     ( 3450): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3450): ApplicationContext is null in ApplicationStatus
,W/chromium( 3450): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3450): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3450): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3450): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/CAR.SERVICE( 3470): Package validated; name: com.android.vending
,V/Finsky  ( 2797): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,W/AudioManagerAndroid( 3450): Requires BLUETOOTH permission
,I/NSApplication( 3450): Starting up...
,V/MusicLeanback( 2912): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1657): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1657): onCreate
,D/SystemUpdateService( 1657): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1657): active receiver: enabled
,I/SystemUpdateService( 1657): showing system update notification
,I/ValidateNoPeople(  759): skipping global notification
,V/SystemUpdateService( 1657): retry (wakeup: false) in 3599984 ms
,D/SystemUpdateService( 1657): onDestroy
,D/LocationInitializer( 1657): Restart initialization of location
,D/WearableService( 1619): callingUid 10008, callindPid: 1619
D/AuthorizationBluetoothService( 1619): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1619): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/MDM     ( 1619): [240] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,W/GCoreFlp( 1619): No location to return for getLastLocation()
W/FusedLocationProvider( 1619): location=null
,I/jxcore-log( 3320): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3320): 
,V/GLSActivity( 1619): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 2797): Failed write_ctrl(u 37) res=-1 errno=22
I/qtaguid ( 2797): Untagging socket 37 failed errno=-22
W/NetworkManagementSocketTagger( 2797): untagSocket(37) failed with errno -22
,I/jxcore-log( 3320): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 3320): 
,W/ResourcesManager( 2797): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2797): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/jxcore-log( 3320): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 3320): 
,I/jxcore-log( 3320): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 3320): 
,I/jxcore-log( 3320): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 3320): 
,I/jxcore-log( 3320): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
I/jxcore-log( 3320): 
,W/ResourcesManager( 2797): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/Finsky  ( 2797): [1] DailyHygiene.access$600: Logging device features
,D/DeviceConnectionService( 1619): client connected with version: 8296000
,D/Finsky  ( 2797): [282] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 2797): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 2797): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,V/GLSActivity( 1619): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  759): Killing 2892:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,I/ActivityManager(  759): Killing 2708:com.google.android.apps.fitness/u0a45 (adj 15): empty #18
,W/libprocessgroup(  759): failed to open /acct/uid_10003/pid_2892/cgroup.procs: No such file or directory
,W/libprocessgroup(  759): failed to open /acct/uid_10045/pid_2708/cgroup.procs: No such file or directory
,D/ConnectivityService(  759): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  759): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2912): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2912): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1657): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1657): onCreate
,D/SystemUpdateService( 1657): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1657): active receiver: enabled
,E/GpsLocationProvider(  759): No APN found to select.
,I/SystemUpdateService( 1657): showing system update notification
,I/ValidateNoPeople(  759): skipping global notification
,V/SystemUpdateService( 1657): retry (wakeup: false) in 3599965 ms
,D/SystemUpdateService( 1657): onDestroy
,D/CAR.SERVICE( 3470): mConnectedToCar = false, abort
,E/ActivityThread( 3470): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@1de9e460 that was originally bound here
E/ActivityThread( 3470): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@1de9e460 that was originally bound here
E/ActivityThread( 3470): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3470): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3470): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3470): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3470): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3470): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3470): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3470): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3470): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3470): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 3470): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 3470): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 3470): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 3470): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2731)
E/ActivityThread( 3470): 	at android.app.ActivityThread.access$1800(ActivityThread.java:144)
E/ActivityThread( 3470): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1361)
E/ActivityThread( 3470): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3470): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3470): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3470): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3470): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3470): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3470): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
,E/ActivityThread( 3470): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@1129f8db that was originally bound here
E/ActivityThread( 3470): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@1129f8db that was originally bound here
E/ActivityThread( 3470): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3470): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3470): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3470): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3470): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3470): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3470): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3470): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 3470): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 3470): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 3470): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 3470): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 3470): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2758)
E/ActivityThread( 3470): 	at android.app.ActivityThread.access$1900(ActivityThread.java:144)
E/ActivityThread( 3470): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
E/ActivityThread( 3470): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3470): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3470): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3470): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3470): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3470): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3470): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
,W/ActivityManager(  759): Unbind failed: could not find connection for android.os.BinderProxy@17a3ca23
,I/jxcore-log( 3320): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 3320): 
I/jxcore-log( 3320): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 3320): 
I/jxcore-log( 3320): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3320): 
,I/jxcore-log( 3320): Test app app.js loaded
I/jxcore-log( 3320): 
,I/chromium( 3320): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3320): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3320): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3320): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3320): 	Bluetooth MAC address: 34:FC:EF:11:AE:67, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3320): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3320): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3320): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3320): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3320): 	Scan mode: 1
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3320): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@380a053a added. We now have 1 listener(s)
,I/jxcore-log( 3320): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 3320): 
,D/Finsky  ( 2797): [271] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 2797): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/GLSActivity( 1619): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1619): Vacuum at: now=1454935027805 tag=VacuumService
,I/Keyboard.Facilitator.LanguageModelFlusher( 1067): run()
I/Keyboard.Facilitator( 1067): flushDynamicLanguageModels()
,I/ConfigService( 1619): onCreate
,I/ConfigService( 1619): onDestroy
,I/ClearcutLoggerApiImpl( 1619): disconnect managed GoogleApiClient
,I/jxcore-log( 3320): --= Surplus to requirements =--
I/jxcore-log( 3320): 
I/jxcore-log( 3320): ****TEST TOOK:  ms ****
I/jxcore-log( 3320): 
I/jxcore-log( 3320): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3320): 
,D/AndroidRuntime( 3648): 
D/AndroidRuntime( 3648): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 3648): CheckJNI is OFF
,D/AndroidRuntime( 3648): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  759): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  759): Killing 3320:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
,I/WindowState(  759): WIN DEATH: Window{10756a58 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  759): Client connection lost with reason: 4
,W/PackageSettings(  759): Skipping PackageSetting{394707ff com.example.hello/10278} due to missing metadata
,I/ActivityManager(  759):   Force finishing activity ActivityRecord{7fcb3a4 u0 com.test.thalitest/.MainActivity t216}
,W/ActivityManager(  759): Spurious death for ProcessRecord{6cbea4d 3320:com.test.thalitest/u0a270}, curProc for 3320: null
I/ActivityManager(  759): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
,I/art     ( 1255): Explicit concurrent mark sweep GC freed 10099(773KB) AllocSpace objects, 2(253KB) LOS objects, 38% free, 25MB/41MB, paused 548us total 16.764ms
,W/GeofencerStateMachine( 1619): Ignoring removeGeofence because network location is disabled.
,I/InputReader(  759): Reconfiguring input devices.  changes=0x00000010
,I/Keyboard.Facilitator( 1067): resetDictionaries() : en_US
,I/Keyboard.Facilitator.DecoderInitializer( 1067): run()
,D/NetworkChangeNotifierAutoDetect(  946): Network connectivity changed, type is: 2
,I/Decoder ( 1067): createOrResetDecoder
,D/VoicemailCleanupService( 3010): Cleaning up data for package: com.test.thalitest
,I/art     ( 1399): Explicit concurrent mark sweep GC freed 6438(491KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 19MB/25MB, paused 385us total 110.520ms
I/ConfigService( 1619): onCreate
,I/art     ( 1657): Explicit concurrent mark sweep GC freed 4199(218KB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 22MB/30MB, paused 506us total 125.367ms
I/art     (  759): Explicit concurrent mark sweep GC freed 33462(1745KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 27MB/41MB, paused 1.219ms total 113.976ms
I/LibraryLoader( 1366): Loading chrome directly from within /data/app/com.android.chrome-1/base.apk
,I/UpdateIcingCorporaServi( 1399): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,W/Launcher( 1255): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@2f48bab8 new=com.google.android.velvet.VelvetApplication@2f48bab8
,I/OpenGLRenderer(  946): Initialized EGL, version 1.4
,D/OpenGLRenderer(  946): Enabling debug mode 0
,I/ActivityManager(  759): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3688 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
I/LibraryLoader( 1366): Time to load native libraries: 81 ms (timestamps 4292-4373)
I/LibraryLoader( 1366): Expected native library version number "44.0.2403.133",actual native library version number "44.0.2403.133"
I/chromium( 1366): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
W/art     ( 1366): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 1366): Attempt to remove local handle scope entry from IRT, ignoring
,D/BackupManagerService(  759): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  759): Receieved: android.intent.action.PACKAGE_REMOVED
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1067): run()
,D/TaskPersister(  759): removeObsoleteFile: deleting file=216_task.xml
,W/art     (  946): Attempt to remove local handle scope entry from IRT, ignoring
,W/InputMethodManagerService(  759): Got RemoteException sending setActive(false) notification to pid 3320 uid 10270
,I/Keyboard.Facilitator( 1067): onFinishInput()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1067): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1067): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1067): run() : Loading LM = contacts
,I/UpdateIcingCorporaServi( 1399): UpdateCorporaTask done [took 142 ms] updated apps [took 142 ms] 
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1067): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1067): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1067): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1067): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1067): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1067): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1067): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1067): run()
I/StatsUtilsManager( 1067): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1067): shouldRecordStats() = Too Soon
,W/ContextImpl( 3688): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
,D/PackageBroadcastService( 1657): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1657): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1657): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1657): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1657): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1657): Module APK com.google.android.play.games already loaded
,I/LocationSettingsChecker( 1657): Removing dialog suppression flag for package com.test.thalitest
,E/NetworkScheduler.SchedulerReceiver( 1619): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1619): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/Keyboard.Facilitator( 1067): onFinishInput()
,I/Launcher( 1255): Deferring update until onResume
,D/gH_CompatibleDatabase( 1657): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1657): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1657): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1657): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/gH_CompatibleDatabase( 1657): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1657): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1657): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 1657): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1657): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1657): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
W/ResourcesManager( 1255): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/gH_CompatibleDatabase( 1657): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1657): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1657): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,E/DataBuffer( 1619): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@297d4f1)
E/DataBuffer( 1619): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@ed48d6)
E/DataBuffer( 1619): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1cbd6757)
E/DataBuffer( 1619): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@366bb244)
E/DataBuffer( 1619): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@20c3cf2d)
E/DataBuffer( 1619): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@64d1c62)
E/DataBuffer( 1619): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@34721f3)
E/DataBuffer( 1619): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@693aeb0)
E/DataBuffer( 1619): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@183b3129)
E/DataBuffer( 1619): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@8e49cae)
E/DataBuffer( 1619): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@da7ea4f)
,I/art     ( 1619): Explicit concurrent mark sweep GC freed 48012(2MB) AllocSpace objects, 8(128KB) LOS objects, 39% free, 21MB/36MB, paused 1.308ms total 37.694ms
I/ActivityManager(  759): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3727 uid=10039 gids={50039, 9997} abi=armeabi-v7a
W/ResourcesManager( 1255): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/Launcher( 1255): Deferring update until onResume
,I/art     (  759): Explicit concurrent mark sweep GC freed 9582(461KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 1.364ms total 341.123ms
,W/BaseAppContext( 1657): Using Auth Proxy for data requests.
,W/BaseAppContext( 1657): Using Auth Proxy for data requests.
,I/ActivityManager(  759): Killing 2868:com.android.settings/1000 (adj 15): empty #17
,W/IInputConnectionWrapper(  946): showStatusIcon on inactive InputConnection
,D/WifiService(  759): Client connection lost with reason: 4
,W/libprocessgroup(  759): failed to open /acct/uid_1000/pid_2868/cgroup.procs: No such file or directory
,I/GMPM-SVC( 1657): App measurement is starting up, version: 8489
I/GMPM-SVC( 1657): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,I/ActivityManager(  759): Killing 2736:com.google.android.gm/u0a70 (adj 15): empty #17
,D/AndroidRuntime( 3648): Shutting down VM
,W/libprocessgroup(  759): failed to open /acct/uid_10070/pid_2736/cgroup.procs: No such file or directory
,I/Icing   ( 1657): doRemovePackageData com.test.thalitest
,I/ActivityManager(  759): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3752 uid=10007 gids={50007, 9997, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  759): Killing 2024:com.google.android.calendar/u0a31 (adj 15): empty #17
,W/libprocessgroup(  759): failed to open /acct/uid_10031/pid_2024/cgroup.procs: No such file or directory
,D/ExternalStorage( 3752): After updating volumes, found 1 active roots
,W/ResourcesManager( 3222): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3222): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/Documents( 3727): Update found 7 roots in 257ms
,D/Documents( 3727): Update found 7 roots in 107ms

```
