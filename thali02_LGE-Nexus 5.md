#### Test 54970261aa56788_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
I/GAv4    ( 3151): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3151):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3151):   adb logcat -s GAv4
W/GAv4    ( 3151): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
D/ChimeraCfgMgr( 1605): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1605): Module APK com.google.android.play.games already loaded
W/GAv4    ( 3151): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3151): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 3151): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
D/Finsky  ( 2604): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
I/ActivityManager(  761): Killing 2574:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
W/ResourcesManager( 3151): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3151): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/AndroidRuntime( 3192): 
D/AndroidRuntime( 3192): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3192): CheckJNI is OFF
W/libprocessgroup(  761): failed to open /acct/uid_10069/pid_2574/cgroup.procs: No such file or directory
V/JNIHelp ( 3151): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/AndroidRuntime( 3192): Calling main entry com.android.commands.am.Am
I/ActivityManager(  761): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
W/System  ( 3151): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3151): Installed default security provider GmsCore_OpenSSL
I/ActivityManager(  761): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3222 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3192): Shutting down VM
V/GLSActivity( 1559): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/ActivityManager(  761): Display changed displayId=0
I/Icing   ( 1605): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/WebViewFactory( 3222): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3222): Time to load native libraries: 2 ms (timestamps 8016-8018)
I/LibraryLoader( 3222): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3222): Binding Chromium to main looper Looper (main, tid 1) {1dfdb6f2}
I/LibraryLoader( 3222): Expected native library version number "",actual native library version number ""
I/chromium( 3222): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/Icing   ( 1605): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/BrowserStartupController( 3222): Initializing chromium process, singleProcess=true
W/art     ( 3222): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3222): ApplicationContext is null in ApplicationStatus
W/chromium( 3222): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3222): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3222): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3222): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
D/BluetoothManagerService(  761): Message: 20
D/BluetoothManagerService(  761): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@35cff564:true
I/Icing   ( 1605): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1605): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
W/art     ( 3222): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 3222): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 3222): CordovaWebView is running on device made by: LGE
W/art     ( 3222): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3222): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 3222): Render dirty regions requested: true
D/Atlas   ( 3222): Validating map...
W/chromium( 3222): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/OpenGLRenderer( 3222): Initialized EGL, version 1.4
D/OpenGLRenderer( 3222): Enabling debug mode 0
I/Keyboard.Facilitator( 1088): onFinishInput()
W/IInputConnectionWrapper( 3222): showStatusIcon on inactive InputConnection
I/ActivityManager(  761): Displayed com.test.thalitest/.MainActivity: +449ms (total +56s181ms)
W/BindingManager( 3222): Cannot call determinedVisibility() - never saw a connection for the pid: 3222
D/JsMessageQueue( 3222): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 3222): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257342720
D/JX-Cordova( 3222): jxcore cordova android initializing
,I/ActivityManager(  761): Killing 2523:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10045/pid_2523/cgroup.procs: No such file or directory
,W/jxcore-log( 3222): Initializing JXcore engine
W/jxcore-log( 3222): JXcore engine is ready
,W/jxcore-log( 3222): Starting JXcore engine
,W/.test.thalitest( 3222): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[6496]" dev="sockfs" ino=6496 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3222): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
,W/.test.thalitest( 3222): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8455]" dev="sockfs" ino=8455 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3222): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[19146]" dev="sockfs" ino=19146 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3222): Platform android
W/jxcore-log( 3222): 
W/jxcore-log( 3222): Process ARCH arm
W/jxcore-log( 3222): 
,I/jxcore-log( 3222): JXcore Cordova bridge is ready!
I/jxcore-log( 3222): 
W/jxcore-log( 3222): JXcore engine is started
I/Choreographer( 3222): Skipped 116 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3222): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3222): Toggling radios to true
I/jxcore-log( 3222): 
,D/BluetoothAdapter( 3222): enable(): BT is already enabled..!
,D/WifiService(  761): New client listening to asynchronous messages
,D/WifiService(  761): setWifiEnabled: true pid=3222, uid=10270
E/WifiService(  761): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3222): Radios toggled
I/jxcore-log( 3222): 
,I/wpa_supplicant( 1012): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  761): WifiStateMachine: Leaving Connected state
,E/WifiConfigStore(  761): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/native  (  761): do suspend true
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1559): Read error: ssl=0xa4374e00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1559): SSL shutdown failed: ssl=0xa4374e00: I/O error during system call, Broken pipe
D/ConnectivityService(  761): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): ValidatedState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): DefaultState{ when=-1ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/ConnectivityService(  761): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  761): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
E/WifiConfigStore(  761): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
E/WifiStateMachine(  761): Start Disconnecting Watchdog 1
I/wpa_supplicant( 1012): wlan0: CTRL-EVENT-SCAN-STARTED 
E/native  (  761): do suspend true
,D/CommandListener(  179): Clearing all IP addresses on wlan0
D/ConnectivityService(  761): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityManager.CallbackHandler(  893): CM callback handler got msg 524292
D/Nat464Xlat(  761): requiresClat: netType=1, connected=false, hasIPv4Address=true
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Disconnected - quitting
D/ConnectivityManager.CallbackHandler( 1605): CM callback handler got msg 524292
,D/CSLegacyTypeTracker(  761): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  761): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory( 1212): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WifiNetworkAgent(  761): NetworkAgent: NetworkAgent channel lost
E/ConnectivityService(  761): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,I/wpa_supplicant( 1012): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant( 1012): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1012): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1012): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  761): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  761): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  761): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  761): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  179): Setting iface cfg
,E/WifiStateMachine(  761): Start Dhcp Watchdog 2
,E/native  (  761): do suspend false
,E/WifiStateMachine(  761): scanCount==0 - aborting
,I/dhcpcd  ( 3321): version 5.5.6 starting
,E/dhcpcd  ( 3321): get_duid: Read-only file system
,I/dhcpcd  ( 3321): wlan0: rebinding lease of 192.168.1.114
,V/GLSActivity( 1559): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1559): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/NetworkUtils( 1299): OkHttp exception
,W/EventLoggerService( 1299): Unable to send logs Error code: 262146
,D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  761): MasterInitialState.processMessage what=3
D/Tethering(  761): MasterInitialState.processMessage what=3
,V/MusicLeanback( 2740): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/dhcpcd  ( 3321): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/SystemUpdateService( 1605): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1605): onCreate
,D/SystemUpdateService( 1605): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.Environment( 1605): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1605): num queued entries: 0
I/iu.UploadsManager( 1605): num updated entries: 0
I/iu.SyncManager( 1605): NEXT; no task
,I/Babel   ( 1889): connection state changed from CONNECTED to DISCONNECTED
I/SystemUpdateService( 1605): active receiver: enabled
,I/dhcpcd  ( 3321): wlan0: leased 192.168.1.114 for 86400 seconds
,I/SystemUpdateService( 1605): showing system update notification
,I/ActivityManager(  761): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3364 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/GpsLocationProvider(  761): No APN found to select.
,I/ValidateNoPeople(  761): skipping global notification
,E/GpsLocationProvider(  761): No APN found to select.
,V/SystemUpdateService( 1605): retry (wakeup: false) in 3599939 ms
,D/SystemUpdateService( 1605): onDestroy
,I/GAv4    ( 3364): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3364):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3364):   adb logcat -s GAv4
,W/GAv4    ( 3364): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3364): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3364): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,E/native  (  761): do suspend true
,D/ConnectivityService(  761): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  761): Adding iface wlan0 to network 101
,E/WifiStateMachine(  761): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  761): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  761): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  761): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/ConnectivityService(  761): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/ConnectivityService(  761): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  761): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  761): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  761): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  761): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  761):    accepting network in place of null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/CSLegacyTypeTracker(  761): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  761): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.114/24,fe80::5255:27ff:fef0:fd0b/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  761): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  893): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1605): CM callback handler got msg 524290
,I/WebViewFactory( 3364): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 05 Jan 2016 18:40:38 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452019238626], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452019238596]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Don't send network conditions - lacking user consent.
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Validated
D/ConnectivityService(  761): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  761): rematching NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  761): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  761): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler(  893): CM callback handler got msg 524290
D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/TelephonyNetworkFactory( 1212): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 1605): CM callback handler got msg 524290
,I/LibraryLoader( 3364): Time to load native libraries: 1 ms (timestamps 4183-4184)
I/LibraryLoader( 3364): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3364): Binding Chromium to main looper Looper (main, tid 1) {173fdd26}
,I/LibraryLoader( 3364): Expected native library version number "",actual native library version number ""
I/chromium( 3364): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3364): Initializing chromium process, singleProcess=true
W/art     ( 3364): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3364): ApplicationContext is null in ApplicationStatus
,W/chromium( 3364): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3364): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3364): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3364): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/AudioManagerAndroid( 3364): Requires BLUETOOTH permission
,I/NSApplication( 3364): Starting up...
,I/ActivityManager(  761): Killing 2714:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10003/pid_2714/cgroup.procs: No such file or directory
,V/MusicLeanback( 2740): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1605): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1605): onCreate
,D/SystemUpdateService( 1605): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1605): active receiver: enabled
,I/SystemUpdateService( 1605): showing system update notification
,I/iu.Environment( 1605): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1605): num queued entries: 0
,I/iu.UploadsManager( 1605): num updated entries: 0
I/iu.SyncManager( 1605): NEXT; no task
,I/ValidateNoPeople(  761): skipping global notification
,V/SystemUpdateService( 1605): retry (wakeup: false) in 3599954 ms
,D/SystemUpdateService( 1605): onDestroy
,I/Babel   ( 1889): connection state changed from DISCONNECTED to CONNECTED
,I/art     (  761): Explicit concurrent mark sweep GC freed 42055(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 27MB/41MB, paused 1.238ms total 83.319ms
,D/ConnectivityService(  761): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/jxcore-log( 3222): Test app app.js loaded
I/jxcore-log( 3222): 
,I/chromium( 3222): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
I/Choreographer( 3222): Skipped 366 frames!  The application may be doing too much work on its main thread.
,D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  761): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2740): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2740): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,E/GpsLocationProvider(  761): No APN found to select.
,I/SystemUpdateService( 1605): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1605): onCreate
,D/SystemUpdateService( 1605): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1605): active receiver: enabled
,I/SystemUpdateService( 1605): showing system update notification
,I/ValidateNoPeople(  761): skipping global notification
,V/SystemUpdateService( 1605): retry (wakeup: false) in 3599983 ms
,D/SystemUpdateService( 1605): onDestroy
,D/Finsky  ( 2604): [255] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2604): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/GLSActivity( 1559): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1559): Vacuum at: now=1452019252414 tag=VacuumService
,I/PhenotypeConfigurator( 1559): Scheduling Phenotype for one-off execution 7680 seconds from now (1452019252773)
,D/GetConfigurationSnapshotOperation( 1559): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1559): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1559): Using platform SSLCertificateSocketFactory
,V/GLSActivity( 1559): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1559): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Keyboard.Facilitator.LanguageModelFlusher( 1088): run()
I/Keyboard.Facilitator( 1088): flushDynamicLanguageModels()
,I/ConfigService( 1559): onCreate
,I/ConfigService( 1559): onDestroy
,I/ClearcutLoggerApiImpl( 1559): disconnect managed GoogleApiClient
,I/ActivityManager(  761): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=3583 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,I/GAv4    ( 3583): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3583):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3583):   adb logcat -s GAv4
,W/GAv4    ( 3583): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3583): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3583): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  761): Killing 2692:com.android.settings/1000 (adj 15): empty #17
,D/WifiService(  761): Client connection lost with reason: 4
,W/libprocessgroup(  761): failed to open /acct/uid_1000/pid_2692/cgroup.procs: No such file or directory
,I/jxcore-log( 3222): TAP version 13
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): # setup
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): # multiplex can send data
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): # teardown
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): ok 1 String should be length:200
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): # setup
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): # basic
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): # teardown
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): ok 2 sane
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): # setup
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): # another
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): # teardown
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): ok 3 sane
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): # setup
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): # successfully create a new pkcs12 file and return hash value
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): # teardown
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): ok 4 should be equal
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): ok 5 null
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): ok 6 (unnamed assert)
I/jxcore-log( 3222): 
I/jxcore-log( 3222): ok 7 should be equal
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): ok 8 should not throw
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): # setup
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): # successfully read a previous pkcs12 file and return hash value
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): # teardown
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): ok 9 (unnamed assert)
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): ok 10 (unnamed assert)
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): ok 11 should not throw
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): ok 12 should be equal
I/jxcore-log( 3222): 
I/jxcore-log( 3222): ok 13 should be equal
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): # setup
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): # failed to extract public key because of corrupt pkcs12 file
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): # teardown
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): ok 14 should be equal
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): # setup
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): # failed to get mobile documents path
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): # teardown
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): ok 15 should be equal
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): # setup
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): # #init should register the peerAvailabilityChanged event
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): # teardown
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): ok 16 should be equal
I/jxcore-log( 3222): 
I/jxcore-log( 3222): ok 17 should be equal
I/jxcore-log( 3222): 
I/jxcore-log( 3222): ok 18 should be equal
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): # setup
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): # #init should register the networkChanged event
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): # teardown
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): ok 19 should be equal
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): # setup
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): # #startBroadcasting should throw on null device name
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): # teardown
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): ok 20 should throw
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): # setup
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): # #startBroadcasting should throw on empty string device name
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): # teardown
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): ok 21 should throw
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): # setup
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): # #startBroadcasting should throw on non-number port
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): # teardown
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): ok 22 should throw
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): # setup
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): # #startBroadcasting should throw on NaN port
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): # teardown
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): ok 23 should throw
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): # setup
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): # #startBroadcasting should throw on negative port
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): # teardown
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): ok 24 should throw
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): # setup
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): # #startBroadcasting should throw on too large port
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): # teardown
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): ok 25 should throw
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): # setup
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): # #startBroadcasting should call Mobile("StartBroadcasting") without an error
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): # teardown
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): ok 26 should be equal
I/jxcore-log( 3222): 
I/jxcore-log( 3222): ok 27 should be equal
I/jxcore-log( 3222): 
I/jxcore-log( 3222): ok 28 should be equal
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): # setup
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): # #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): # teardown
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): ok 29 should be equal
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): ok 30 should be equal
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): ok 31 should be equal
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): # setup
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): # #stopBroadcasting should call Mobile("StopBroadcasting") without an error
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): # teardown
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): ok 32 should be equal
I/jxcore-log( 3222): 
I/jxcore-log( 3222): ok 33 should be equal
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): # setup
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): # #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): # teardown
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): ok 34 should be equal
I/jxcore-log( 3222): 
I/jxcore-log( 3222): ok 35 should be equal
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): # setup
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): # #connect should call Mobile("Connect") with a port and without an error
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): # teardown
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): ok 36 should be equal
I/jxcore-log( 3222): 
I/jxcore-log( 3222): ok 37 should be equal
I/jxcore-log( 3222): 
I/jxcore-log( 3222): ok 38 should be equal
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): # setup
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): # #connect should call Mobile("Connect") and handle an error
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): # teardown
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): ok 39 should be equal
I/jxcore-log( 3222): 
I/jxcore-log( 3222): ok 40 should be equal
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): # setup
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): # should call Mobile("Disconnect") without an error
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): # teardown
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): ok 41 should be equal
I/jxcore-log( 3222): 
I/jxcore-log( 3222): ok 42 should be equal
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): # setup
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): # should call Mobile("Disconnect") and handle an error
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): # teardown
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): ok 43 should be equal
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): ok 44 should be equal
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): # setup
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): # ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
I/jxcore-log( 3222): 
,I/jxcore-log( 3222): # teardown
I/jxcore-log( 3222): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): setDiscoveryMode: Mode set to WIFI
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3222): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452019698783.3222
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3222): bind: Binding a new listener
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3222): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3222): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1452019698783.3222","ra":"34:FC:EF:11:AE:67"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3222): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3222): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3222): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3222): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3222): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3222): start: OK
I/io.jxcore.node.ConnectionHelper( 3222): start: Using peer discovery mode: WIFI
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452019698783.3222
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3222): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1452019698783.3222","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3222): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3222): start: {"pi":"34:FC:EF:11:AE:67","pn":"1452019698783.3222","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3222): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1452019698783.3222","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3222): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3222): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3222): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3222): start: OK
I/jxcore-log( 3222): ok 45 Should be able to call startBroadcasting without error
I/jxcore-log( 3222): 
I/io.jxcore.node.ConnectionHelper( 3222): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3222): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3222): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3222): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3222): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3222): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3222): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3222): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3222): setState: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3222): stop: Stopping services
,I/wpa_supplicant( 1012): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3222): stop: Stopping P2P device discovery...
,I/wpa_supplicant( 1012): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3222): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3222): release: No more listeners, de-initializing...
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3222): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3222): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): setState: NOT_STARTED
,I/jxcore-log( 3222): ok 46 Should be able to call stopBroadcasting without error
I/jxcore-log( 3222): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3222): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452019698867.3222
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3222): bind: Binding a new listener
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3222): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3222): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1452019698867.3222","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3222): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3222): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3222): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 3222): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3222): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3222): start: OK
I/io.jxcore.node.ConnectionHelper( 3222): start: Using peer discovery mode: WIFI
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452019698867.3222
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3222): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1452019698867.3222","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3222): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3222): start: {"pi":"34:FC:EF:11:AE:67","pn":"1452019698867.3222","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3222): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1452019698867.3222","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3222): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3222): start: Starting P2P device discovery...
,I/wpa_supplicant( 1012): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3222): start: OK
I/jxcore-log( 3222): ok 47 Should be able to call startBroadcasting without error
I/jxcore-log( 3222): 
,I/io.jxcore.node.ConnectionHelper( 3222): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3222): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3222): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3222): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3222): shutdown
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3222): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3222): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3222): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3222): stop: Stopping P2P device discovery...
,I/wpa_supplicant( 1012): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3222): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3222): release: No more listeners, de-initializing...
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3222): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3222): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): setState: NOT_STARTED
I/jxcore-log( 3222): ok 48 Should be able to call stopBroadcasting without error
I/jxcore-log( 3222): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): setDiscoveryMode: Mode set to WIFI
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3222): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452019698893.3222
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3222): bind: Binding a new listener
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3222): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3222): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1452019698893.3222","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3222): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3222): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3222): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3222): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3222): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3222): start: OK
I/io.jxcore.node.ConnectionHelper( 3222): start: Using peer discovery mode: WIFI
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3222): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3222): onServerStopped
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452019698893.3222
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3222): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1452019698893.3222","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3222): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3222): start: {"pi":"34:FC:EF:11:AE:67","pn":"1452019698893.3222","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3222): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1452019698893.3222","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3222): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3222): start: Starting P2P device discovery...
,I/wpa_supplicant( 1012): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3222): start: OK
,I/jxcore-log( 3222): ok 49 Should be able to call startBroadcasting without error
I/jxcore-log( 3222): 
I/io.jxcore.node.ConnectionHelper( 3222): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3222): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3222): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3222): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3222): shutdown
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3222): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3222): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3222): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3222): stop: Stopping P2P device discovery...
,I/wpa_supplicant( 1012): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3222): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3222): release: No more listeners, de-initializing...
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3222): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3222): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): setState: NOT_STARTED
,I/jxcore-log( 3222): ok 50 Should be able to call stopBroadcasting without error
I/jxcore-log( 3222): 
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3222): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452019698925.3222
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3222): bind: Binding a new listener
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3222): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3222): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1452019698925.3222","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3222): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3222): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3222): startListeningForIncomingConnections: Starting...
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3222): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3222): onServerStopped
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3222): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3222): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3222): start: OK
I/io.jxcore.node.ConnectionHelper( 3222): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452019698925.3222
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3222): Waiting for incoming connections...
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3222): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1452019698925.3222","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3222): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3222): start: {"pi":"34:FC:EF:11:AE:67","pn":"1452019698925.3222","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3222): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1452019698925.3222","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3222): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3222): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3222): start: OK
I/jxcore-log( 3222): ok 51 Should be able to call startBroadcasting without error
I/jxcore-log( 3222): 
I/wpa_supplicant( 1012): p2p0: P2P: Reject scan trigger since one is already pending
I/io.jxcore.node.ConnectionHelper( 3222): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3222): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3222): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3222): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3222): shutdown
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3222): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3222): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3222): onServerStopped
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3222): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3222): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3222): stop: Stopping P2P device discovery...
,I/wpa_supplicant( 1012): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3222): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3222): release: No more listeners, de-initializing...
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3222): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3222): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): setState: NOT_STARTED
,I/jxcore-log( 3222): ok 52 Should be able to call stopBroadcasting without error
I/jxcore-log( 3222): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): setDiscoveryMode: Mode set to WIFI
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3222): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452019698955.3222
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3222): bind: Binding a new listener
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3222): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3222): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1452019698955.3222","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3222): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3222): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3222): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 3222): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3222): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3222): start: OK
I/io.jxcore.node.ConnectionHelper( 3222): start: Using peer discovery mode: WIFI
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452019698955.3222
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3222): Waiting for incoming connections...
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3222): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1452019698955.3222","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3222): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3222): start: {"pi":"34:FC:EF:11:AE:67","pn":"1452019698955.3222","ra":"34:FC:EF:11:AE:67"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3222): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1452019698955.3222","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3222): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3222): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): start: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3222): start: OK
I/jxcore-log( 3222): ok 53 Should be able to call startBroadcasting without error
I/jxcore-log( 3222): 
I/wpa_supplicant( 1012): p2p0: P2P: Reject scan trigger since one is already pending
I/io.jxcore.node.ConnectionHelper( 3222): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3222): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3222): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3222): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3222): shutdown
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3222): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3222): Exiting thread
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3222): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3222): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3222): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3222): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3222): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): onIsWifiPeerDiscoveryStartedChanged: false
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3222): release: No more listeners, de-initializing...
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3222): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3222): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): setState: NOT_STARTED
I/wpa_supplicant( 1012): P2P-FIND-STOPPED 
,I/jxcore-log( 3222): ok 54 Should be able to call stopBroadcasting without error
I/jxcore-log( 3222): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): setDiscoveryMode: Mode set to WIFI
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3222): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452019698973.3222
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3222): bind: Binding a new listener
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3222): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3222): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1452019698973.3222","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3222): setConnectionTimeout: 15000
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3222): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3222): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 3222): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3222): setState: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3222): start: OK
I/io.jxcore.node.ConnectionHelper( 3222): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452019698973.3222
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3222): Waiting for incoming connections...
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3222): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1452019698973.3222","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3222): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3222): start: {"pi":"34:FC:EF:11:AE:67","pn":"1452019698973.3222","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3222): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1452019698973.3222","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3222): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3222): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): onIsWifiPeerDiscoveryStartedChanged: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): start: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3222): start: OK
,I/jxcore-log( 3222): ok 55 Should be able to call startBroadcasting without error
I/jxcore-log( 3222): 
I/io.jxcore.node.ConnectionHelper( 3222): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3222): stop: Stopping Bluetooth...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3222): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3222): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3222): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3222): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3222): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3222): release: No more listeners, de-initializing...
I/wpa_supplicant( 1012): p2p0: P2P: Reject scan trigger since one is already pending
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3222): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): stop: Stopping peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3222): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3222): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3222): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3222): release: No more listeners, de-initializing...
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3222): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3222): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): setState: NOT_STARTED
I/wpa_supplicant( 1012): P2P-FIND-STOPPED 
I/jxcore-log( 3222): ok 56 Should be able to call stopBroadcasting without error
I/jxcore-log( 3222): 
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3222): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452019698993.3222
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3222): bind: Binding a new listener
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3222): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3222): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1452019698993.3222","ra":"34:FC:EF:11:AE:67"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3222): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3222): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3222): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3222): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3222): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3222): start: OK
I/io.jxcore.node.ConnectionHelper( 3222): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3222): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452019698993.3222
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3222): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1452019698993.3222","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3222): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3222): start: {"pi":"34:FC:EF:11:AE:67","pn":"1452019698993.3222","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3222): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1452019698993.3222","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3222): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3222): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3222): start: OK
I/jxcore-log( 3222): ok 57 Should be able to call startBroadcasting without error
I/jxcore-log( 3222): 
I/io.jxcore.node.ConnectionHelper( 3222): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3222): stop: Stopping Bluetooth...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3222): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3222): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3222): shutdown
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3222): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3222): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3222): onServerStopped
I/wpa_supplicant( 1012): p2p0: P2P: Reject scan trigger since one is already pending
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3222): setState: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3222): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3222): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3222): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3222): release: No more listeners, de-initializing...
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3222): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3222): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): setState: NOT_STARTED
,I/jxcore-log( 3222): ok 58 Should be able to call stopBroadcasting without error
I/jxcore-log( 3222): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): setDiscoveryMode: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/wpa_supplicant( 1012): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3222): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452019699013.3222
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3222): bind: Binding a new listener
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3222): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3222): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1452019699013.3222","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3222): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3222): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3222): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 3222): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3222): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3222): start: OK
I/io.jxcore.node.ConnectionHelper( 3222): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452019699013.3222
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3222): Waiting for incoming connections...
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3222): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1452019699013.3222","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3222): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3222): start: {"pi":"34:FC:EF:11:AE:67","pn":"1452019699013.3222","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3222): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1452019699013.3222","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3222): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3222): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3222): start: OK
,I/wpa_supplicant( 1012): p2p0: P2P: Reject scan trigger since one is already pending
,I/jxcore-log( 3222): ok 59 Should be able to call startBroadcasting without error
I/jxcore-log( 3222): 
,I/io.jxcore.node.ConnectionHelper( 3222): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3222): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3222): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3222): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3222): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3222): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3222): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3222): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3222): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3222): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3222): stop: Stopping P2P device discovery...
,I/wpa_supplicant( 1012): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3222): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3222): release: No more listeners, de-initializing...
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3222): release: The given listener does not exist in the list,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3222): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): setState: NOT_STARTED
I/jxcore-log( 3222): ok 60 Should be able to call stopBroadcasting without error
I/jxcore-log( 3222): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3222): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452019699053.3222
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3222): bind: Binding a new listener
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3222): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3222): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1452019699053.3222","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3222): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3222): startListeningForIncomingConnections
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3222): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 3222): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3222): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3222): start: OK
I/io.jxcore.node.ConnectionHelper( 3222): start: Using peer discovery mode: WIFI
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452019699053.3222
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3222): Waiting for incoming connections...
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3222): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1452019699053.3222","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3222): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3222): start: {"pi":"34:FC:EF:11:AE:67","pn":"1452019699053.3222","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3222): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1452019699053.3222","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3222): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3222): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3222): start: OK
I/wpa_supplicant( 1012): p2p0: P2P: Reject scan trigger since one is already pending
I/jxcore-log( 3222): ok 61 Should be able to call startBroadcasting without error
I/jxcore-log( 3222): 
I/io.jxcore.node.ConnectionHelper( 3222): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3222): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3222): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3222): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3222): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3222): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3222): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3222): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3222): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3222): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3222): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3222): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3222): release: No more listeners, de-initializing...
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3222): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3222): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): setState: NOT_STARTED
I/jxcore-log( 3222): ok 62 Should be able to call stopBroadcasting without error
I/jxcore-log( 3222): 
I/wpa_supplicant( 1012): P2P-FIND-STOPPED 
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): setDiscoveryMode: Mode set to WIFI
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3222): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452019699069.3222
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3222): bind: Binding a new listener
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3222): initialize: My bluetooth address is 34:FC:EF:11:AE:67
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3222): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1452019699069.3222","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3222): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3222): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3222): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 3222): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3222): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3222): start: OK
I/io.jxcore.node.ConnectionHelper( 3222): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1452019699069.3222
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3222): Waiting for incoming connections...
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3222): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1452019699069.3222","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3222): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3222): start: {"pi":"34:FC:EF:11:AE:67","pn":"1452019699069.3222","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3222): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1452019699069.3222","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3222): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3222): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3222): start: OK
I/wpa_supplicant( 1012): p2p0: P2P: Reject scan trigger since one is already pending
I/jxcore-log( 3222): ok 63 Should be able to call startBroadcasting without error
I/jxcore-log( 3222): 
I/io.jxcore.node.ConnectionHelper( 3222): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3222): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3222): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3222): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3222): shutdown
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3222): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3222): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3222): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3222): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3222): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3222): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3222): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3222): release: No more listeners, de-initializing...
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3222): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3222): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3222): setState: NOT_STARTED
I/wpa_supplicant( 1012): P2P-FIND-STOPPED 
I/jxcore-log( 3222): ok 64 Should be able to call stopBroadcasting without error
I/jxcore-log( 3222): 
I/jxcore-log( 3222): # setup
I/jxcore-log( 3222): 
I/io.jxcore.node.ConnectionHelper( 3222): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3222): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3222): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3222): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 3222): onDiscoveryManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 3222): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3222): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3222): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3222): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 3222): onDiscoveryManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3222): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3222): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3222): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3222): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 3222): onDiscoveryManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 3222): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3222): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3222): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3222): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 3222): onDiscoveryManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3222): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3222): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3222): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3222): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 3222): onDiscoveryManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 3222): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3222): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3222): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3222): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 3222): onDiscoveryManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3222): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 3222): onDiscoveryManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3222): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3222): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3222): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 3222): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3222): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3222): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3222): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 3222): onDiscoveryManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3222): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 3222): onDiscoveryManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3222): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3222): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3222): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 3222): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3222): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3222): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3222): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3222): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 3222): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 3222): onDiscoveryManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3222): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 3222): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3222): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3222): setState: STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3222): Local services cleared successfully
I/io.jxcore.node.ConnectionHelper( 3222): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3222): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3222): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 3222): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 3222): onDiscoveryManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3222): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 3222): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3222): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3222): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 3222): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3222): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3222): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3222): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 3222): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 3222): onDiscoveryManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3222): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3222): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3222): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 3222): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3222): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3222): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3222): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 3222): onDiscoveryManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3222): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3222): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 3222): onDiscoveryManagerStateChanged: RUNNING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3222): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3222): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 3222): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3222): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3222): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3222): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3222): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 3222): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3222): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 3222): onDiscoveryManagerStateChanged: RUNNING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3222): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3222): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 3222): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3222): Local services cleared successfully
I/io.jxcore.node.ConnectionHelper( 3222): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3222): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3222): Service requests cleared successfully
,I/ActivityManager(  761): Killing 2548:com.google.android.gm/u0a70 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10070/pid_2548/cgroup.procs: No such file or directory
,W/bt-smp  ( 2060): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2060): Plain text(LSB ~ MSB) = 24 69 4c 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2060): Encrypted text(LSB ~ MSB) = f1 d9 50 0c 58 6f fa b3 8d df 1f 02 30 21 d3 f3 
W/bt-btm  ( 2060): Stopping oneshot timer
,I/EventLogService( 1605): Aggregate from 1452017899023 (log), 1452017899023 (data)
,I/UsageStatsService(  761): User[0] Flushing usage stats to disk
,I/ProcessStatsService(  761): Prepared write state in 48ms
,W/bt-smp  ( 2060): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2060): Plain text(LSB ~ MSB) = ee 7f 76 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2060): Encrypted text(LSB ~ MSB) = 5f de 2c dd e1 80 41 c6 fa 68 1f 14 7f 46 29 24 
W/bt-btm  ( 2060): Stopping oneshot timer
,I/ProcessStatsService(  761): Pruning old procstats: /data/system/procstats/state-2016-01-05-02-51-01.bin
,I/ActivityManager(  761): Killing 3120:com.android.musicfx/u0a15 (adj 13): empty for 1808s
,I/ActivityManager(  761): Killing 1463:com.google.android.partnersetup/u0a13 (adj 13): empty for 1808s
,I/ActivityManager(  761): Killing 2874:android.process.acore/u0a4 (adj 13): empty for 1808s
,I/ActivityManager(  761): Killing 2806:com.android.providers.calendar/u0a2 (adj 13): empty for 1816s
,I/ActivityManager(  761): Killing 2991:com.google.android.gms:car/u0a8 (adj 15): empty for 1816s
,I/ActivityManager(  761): Killing 1951:com.google.android.calendar/u0a31 (adj 15): empty for 1845s
,W/libprocessgroup(  761): failed to open /acct/uid_10015/pid_3120/cgroup.procs: No such file or directory
,W/libprocessgroup(  761): failed to open /acct/uid_10004/pid_2874/cgroup.procs: No such file or directory
,W/libprocessgroup(  761): failed to open /acct/uid_10002/pid_2806/cgroup.procs: No such file or directory
W/libprocessgroup(  761): failed to open /acct/uid_10008/pid_2991/cgroup.procs: No such file or directory
W/libprocessgroup(  761): failed to open /acct/uid_10031/pid_1951/cgroup.procs: No such file or directory
,W/libprocessgroup(  761): failed to open /acct/uid_10013/pid_1463/cgroup.procs: No such file or directory
,V/GLSActivity( 1559): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1559): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  761): Killing 3151:com.google.android.apps.docs/u0a40 (adj 15): empty for 1808s
,W/libprocessgroup(  761): failed to open /acct/uid_10040/pid_3151/cgroup.procs: No such file or directory
,TIME-OUT KILL (timeout was 1800000ms)
```
