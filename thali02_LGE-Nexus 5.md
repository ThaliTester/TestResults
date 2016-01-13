#### Test 5590220275263c8_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
D/ChimeraCfgMgr( 1604): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1604): Module APK com.google.android.play.games already loaded
I/GAv4    ( 3326): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3326):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3326):   adb logcat -s GAv4
W/GAv4    ( 3326): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3326): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3326): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 3326): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
D/Finsky  ( 2599): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
W/ResourcesManager( 3326): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3326): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  762): Killing 2834:com.google.android.apps.magazines/u0a61 (adj 15): empty #17
V/JNIHelp ( 3326): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/System  ( 3326): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3326): Installed default security provider GmsCore_OpenSSL
W/libprocessgroup(  762): failed to open /acct/uid_10061/pid_2834/cgroup.procs: No such file or directory
V/GLSActivity( 1558): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 1604): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/Icing   ( 1604): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/Icing   ( 1604): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1604): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
,I/ActivityManager(  762): Killing 2964:com.google.android.apps.cloudprint/u0a35 (adj 15): empty #17
D/AndroidRuntime( 3382): 
D/AndroidRuntime( 3382): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3382): CheckJNI is OFF
W/libprocessgroup(  762): failed to open /acct/uid_10035/pid_2964/cgroup.procs: No such file or directory
D/AndroidRuntime( 3382): Calling main entry com.android.commands.am.Am
I/ActivityManager(  762): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  762): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3417 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3382): Shutting down VM
V/ActivityManager(  762): Display changed displayId=0
I/WebViewFactory( 3417): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3417): Time to load native libraries: 1 ms (timestamps 8155-8156)
I/LibraryLoader( 3417): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3417): Binding Chromium to main looper Looper (main, tid 1) {f2d6445}
I/LibraryLoader( 3417): Expected native library version number "",actual native library version number ""
I/chromium( 3417): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3417): Initializing chromium process, singleProcess=true
W/art     ( 3417): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3417): ApplicationContext is null in ApplicationStatus
,W/chromium( 3417): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3417): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3417): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3417): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  762): Message: 20
D/BluetoothManagerService(  762): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@177ec0f:true
,W/art     ( 3417): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3417): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3417): CordovaWebView is running on device made by: LGE
,W/art     ( 3417): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3417): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3417): Render dirty regions requested: true
,D/Atlas   ( 3417): Validating map...
,W/chromium( 3417): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3417): Initialized EGL, version 1.4
D/OpenGLRenderer( 3417): Enabling debug mode 0
,I/Keyboard.Facilitator( 1110): onFinishInput()
,W/IInputConnectionWrapper( 3417): showStatusIcon on inactive InputConnection
,I/ActivityManager(  762): Displayed com.test.thalitest/.MainActivity: +445ms (total +55s686ms)
,W/BindingManager( 3417): Cannot call determinedVisibility() - never saw a connection for the pid: 3417
,D/JsMessageQueue( 3417): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3417): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1356460288
D/JX-Cordova( 3417): jxcore cordova android initializing
,W/jxcore-log( 3417): Initializing JXcore engine
W/jxcore-log( 3417): JXcore engine is ready
,W/jxcore-log( 3417): Starting JXcore engine
,W/.test.thalitest( 3417): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[7944]" dev="sockfs" ino=7944 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/.test.thalitest( 3417): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 3417): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8467]" dev="sockfs" ino=8467 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3417): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[22584]" dev="sockfs" ino=22584 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3417): Platform android
W/jxcore-log( 3417): 
,W/jxcore-log( 3417): Process ARCH arm
W/jxcore-log( 3417): 
,I/jxcore-log( 3417): JXcore Cordova bridge is ready!
I/jxcore-log( 3417): 
W/jxcore-log( 3417): JXcore engine is started
,I/Choreographer( 3417): Skipped 118 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3417): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3417): Toggling radios to true
I/jxcore-log( 3417): 
,D/BluetoothAdapter( 3417): enable(): BT is already enabled..!
,D/WifiService(  762): New client listening to asynchronous messages
,D/WifiService(  762): setWifiEnabled: true pid=3417, uid=10270
E/WifiService(  762): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3417): Radios toggled
I/jxcore-log( 3417): 
I/jxcore-log( 3417): My device name is: LGE-Nexus 5
I/jxcore-log( 3417): 
,I/wpa_supplicant(  994): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
E/WifiStateMachine(  762): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  762): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
E/native  (  762): do suspend true
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1558): Read error: ssl=0xaf6ace00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1558): SSL shutdown failed: ssl=0xaf6ace00: I/O error during system call, Broken pipe
,D/ConnectivityService(  762): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): ValidatedState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): DefaultState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): Checking http://clients3.google.com/generate_204 on "NG7005g"
,E/WifiConfigStore(  762): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  762): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  762): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,E/WifiStateMachine(  762): Start Disconnecting Watchdog 1
I/wpa_supplicant(  994): wlan0: CTRL-EVENT-SCAN-STARTED 
E/native  (  762): do suspend true
,D/CommandListener(  179): Clearing all IP addresses on wlan0
D/ConnectivityService(  762): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityManager.CallbackHandler(  902): CM callback handler got msg 524292
D/ConnectivityManager.CallbackHandler( 1604): CM callback handler got msg 524292
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): Disconnected - quitting
,D/Nat464Xlat(  762): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  762): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  762): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  762): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  762): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1224): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WifiNetworkAgent(  762): NetworkAgent: NetworkAgent channel lost
,I/wpa_supplicant(  994): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant(  994): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant(  994): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant(  994): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  762): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  762): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  762): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiConfigStore(  762): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/CommandListener(  179): Setting iface cfg
E/WifiStateMachine(  762): Start Dhcp Watchdog 2
,E/native  (  762): do suspend false
,E/WifiStateMachine(  762): scanCount==0 - aborting
,I/dhcpcd  ( 3509): version 5.5.6 starting
E/dhcpcd  ( 3509): get_duid: Read-only file system
,I/dhcpcd  ( 3509): wlan0: rebinding lease of 192.168.1.114
,V/GLSActivity( 1558): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1558): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/NetworkUtils( 1366): OkHttp exception
W/EventLoggerService( 1366): Unable to send logs Error code: 262146
,I/dhcpcd  ( 3509): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3509): wlan0: leased 192.168.1.114 for 86400 seconds
,D/ConnectivityService(  762): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  762): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  762): MasterInitialState.processMessage what=3
,D/Tethering(  762): MasterInitialState.processMessage what=3
,V/MusicLeanback( 2702): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1604): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1604): onCreate
,D/SystemUpdateService( 1604): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.Environment( 1604): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1604): num queued entries: 0
,I/SystemUpdateService( 1604): active receiver: enabled
,I/iu.UploadsManager( 1604): num updated entries: 0
I/iu.SyncManager( 1604): NEXT; no task
,E/GpsLocationProvider(  762): No APN found to select.
,I/SystemUpdateService( 1604): showing system update notification
,I/Babel   ( 1894): connection state changed from CONNECTED to DISCONNECTED
,I/ActivityManager(  762): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3554 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/GpsLocationProvider(  762): No APN found to select.
,I/ValidateNoPeople(  762): skipping global notification
,V/SystemUpdateService( 1604): retry (wakeup: false) in 3599904 ms
,D/SystemUpdateService( 1604): onDestroy
,I/GAv4    ( 3554): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3554):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3554):   adb logcat -s GAv4
,W/GAv4    ( 3554): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3554): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3554): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,E/native  (  762): do suspend true
,E/WifiStateMachine(  762): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/ConnectivityService(  762): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  762): Adding iface wlan0 to network 101
,E/ConnectivityService(  762): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  762): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  762): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  762): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/ConnectivityService(  762): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  762): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  762): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  762): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  762): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  762):    accepting network in place of null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): Checking http://clients3.google.com/generate_204 on "NG7005g"
D/CSLegacyTypeTracker(  762): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  762): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  762): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::5255:27ff:fef0:fd0b/64,192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService(  762): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler(  902): CM callback handler got msg 524290
D/ConnectivityManager.CallbackHandler( 1604): CM callback handler got msg 524290
,I/WebViewFactory( 3554): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 13 Jan 2016 14:32:53 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452695574040], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452695574024]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): Validated
,D/ConnectivityService(  762): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  762): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  762): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  762): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  762): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/TelephonyNetworkFactory( 1224): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1604): CM callback handler got msg 524290
D/ConnectivityManager.CallbackHandler(  902): CM callback handler got msg 524290
,I/LibraryLoader( 3554): Time to load native libraries: 2 ms (timestamps 4345-4347)
,I/LibraryLoader( 3554): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3554): Binding Chromium to main looper Looper (main, tid 1) {17efa649}
,I/LibraryLoader( 3554): Expected native library version number "",actual native library version number ""
I/chromium( 3554): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3554): Initializing chromium process, singleProcess=true
W/art     ( 3554): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3554): ApplicationContext is null in ApplicationStatus
,W/chromium( 3554): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3554): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3554): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3554): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/AudioManagerAndroid( 3554): Requires BLUETOOTH permission
,I/NSApplication( 3554): Starting up...
,I/ActivityManager(  762): Killing 2933:com.google.android.apps.cloudprint:sync/u0a35 (adj 15): empty #17
,W/libprocessgroup(  762): failed to open /acct/uid_10035/pid_2933/cgroup.procs: No such file or directory
,V/MusicLeanback( 2702): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1604): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1604): onCreate
D/SystemUpdateService( 1604): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.Environment( 1604): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1604): num queued entries: 0
I/iu.UploadsManager( 1604): num updated entries: 0
,I/SystemUpdateService( 1604): active receiver: enabled
I/iu.SyncManager( 1604): NEXT; no task
I/SystemUpdateService( 1604): showing system update notification
,I/ValidateNoPeople(  762): skipping global notification
,V/SystemUpdateService( 1604): retry (wakeup: false) in 3599988 ms
,I/art     (  762): Explicit concurrent mark sweep GC freed 41281(2MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 27MB/41MB, paused 1.373ms total 74.558ms
,D/SystemUpdateService( 1604): onDestroy
,I/Babel   ( 1894): connection state changed from DISCONNECTED to CONNECTED
,D/ConnectivityService(  762): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/jxcore-log( 3417): Test app app.js loaded
I/jxcore-log( 3417): 
,I/chromium( 3417): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/ConnectivityService(  762): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  762): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2702): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2702): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1604): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1604): onCreate
,D/SystemUpdateService( 1604): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1604): active receiver: enabled
,E/GpsLocationProvider(  762): No APN found to select.
,I/SystemUpdateService( 1604): showing system update notification
,I/ValidateNoPeople(  762): skipping global notification
,V/SystemUpdateService( 1604): retry (wakeup: false) in 3599970 ms
,D/SystemUpdateService( 1604): onDestroy
,D/Finsky  ( 2599): [250] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2599): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/art     ( 1558): Explicit concurrent mark sweep GC freed 46229(2MB) AllocSpace objects, 7(112KB) LOS objects, 40% free, 21MB/36MB, paused 767us total 42.211ms
,V/GLSActivity( 1558): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1558): Vacuum at: now=1452695589625 tag=VacuumService
,I/PhenotypeConfigurator( 1558): Scheduling Phenotype for one-off execution 408 seconds from now (1452695589959)
,D/GetConfigurationSnapshotOperation( 1558): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1558): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1558): Using platform SSLCertificateSocketFactory
,I/Keyboard.Facilitator.LanguageModelFlusher( 1110): run()
I/Keyboard.Facilitator( 1110): flushDynamicLanguageModels()
,I/ConfigService( 1558): onCreate
,I/ConfigService( 1558): onDestroy
,I/ClearcutLoggerApiImpl( 1558): disconnect managed GoogleApiClient
,D/AlarmManagerService(  762): Setting time of day to sec=1452695687
,W/AlarmManagerService(  762): Unable to set rtc to 1452695687: Invalid argument
,I/ActivityManager(  762): Start proc com.google.android.keep for broadcast com.google.android.keep/.notification.AlertReceiver: pid=3755 uid=10071 gids={50071, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  762): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=3780 uid=10076 gids={50076, 9997} abi=armeabi-v7a
,I/ActivityManager(  762): Killing 2524:com.google.android.gm/u0a70 (adj 15): empty #17
,W/libprocessgroup(  762): failed to open /acct/uid_10070/pid_2524/cgroup.procs: No such file or directory
,D/TimeService( 3780): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1452695688554
D/        ( 3780): TimeServiceNative: User Time to be set is 1452695688554
D/QC-time-services( 3780): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 3780): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 3780): Lib:time_genoff_operation: pargs->ts_val = 1452695688554
D/QC-time-services( 3780): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  197): Daemon: Connection accepted:time_genoff
,D/QC-time-services(  197): Daemon:Received base = 2, unit = 1, operation = 0,value = 1452695688554
D/QC-time-services(  197): Daemon:genoff_opr: Base = 2, val = 1452695688554, operation = 0
D/QC-time-services(  197): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS4/17/70 20:25:17
D/QC-time-services(  197): Daemon:Value read from RTC seconds = 11823917000
D/QC-time-services(  197): Daemon:new time 1452695688554 
D/QC-time-services(  197): Daemon: delta 1440871771554 genoff 1440871771554 
D/QC-time-services(  197): Daemon:genoff_persistent_update: Writing genoff = 1440871771554 to memory
D/QC-time-services(  197): Daemon:Opening File: /data/system/time/ats_2
D/QC-time-services(  197): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  197): Updating the TOD offset
D/QC-time-services(  197): Daemon:genoff_persistent_update: Writing genoff = 1440871771554 to memory
D/QC-time-services(  197): Daemon:Opening File: /data/system/time/ats_1
D/QC-time-services(  197): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  197): Daemon:Update to modem bit set
E/QC-time-services( 3780): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,I/ActivityManager(  762): Killing 2882:com.google.android.videos/u0a77 (adj 15): empty #17
,D/QC-time-services(  197): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  197): Daemon: Base = 2, Value being sent to MODEM = 1136730888554
,D/QC-time-services(  197): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,D/QC-time-services(  197): Daemon: Time-services: Waiting to acceptconnection
,W/libprocessgroup(  762): failed to open /acct/uid_10077/pid_2882/cgroup.procs: No such file or directory
,I/CheckinService( 1604): Checkin interval check for package: unspecified last checkin: 1452672242183 min interval config: 0 actual interval: 23446455
,I/ActivityManager(  762): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver: pid=3801 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,I/GAv4    ( 3801): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3801):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3801):   adb logcat -s GAv4
,W/GAv4    ( 3801): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3801): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3801): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  762): Killing 3160:com.google.android.gms:car/u0a8 (adj 15): empty #17
,W/libprocessgroup(  762): failed to open /acct/uid_10008/pid_3160/cgroup.procs: No such file or directory
,I/jxcore-log( 3417): --= Surplus to requirements =--
I/jxcore-log( 3417): 
I/jxcore-log( 3417): ****TEST TOOK:  ms ****
I/jxcore-log( 3417): 
I/jxcore-log( 3417): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3417): 
,D/AndroidRuntime( 3836): 
D/AndroidRuntime( 3836): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 3836): CheckJNI is OFF
,D/AndroidRuntime( 3836): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  762): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  762): Killing 3417:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
,I/WindowState(  762): WIN DEATH: Window{3231f6ff u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  762): Client connection lost with reason: 4
,W/PackageSettings(  762): Skipping PackageSetting{37191489 com.example.hello/10278} due to missing metadata
,I/ActivityManager(  762):   Force finishing activity ActivityRecord{3518cc3b u0 com.test.thalitest/.MainActivity t216}
,W/ActivityManager(  762): Spurious death for ProcessRecord{501a431 3417:com.test.thalitest/u0a270}, curProc for 3417: null
,I/ActivityManager(  762): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
,I/art     ( 1604): Explicit concurrent mark sweep GC freed 11380(556KB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 23MB/30MB, paused 508us total 30.309ms
,I/art     ( 1366): Explicit concurrent mark sweep GC freed 8760(595KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 18MB/25MB, paused 301us total 30.123ms
,I/InputReader(  762): Reconfiguring input devices.  changes=0x00000010
I/Keyboard.Facilitator( 1110): resetDictionaries() : en_US
,W/GeofencerStateMachine( 1558): Ignoring removeGeofence because network location is disabled.
,I/art     ( 1272): Explicit concurrent mark sweep GC freed 7275(546KB) AllocSpace objects, 2(253KB) LOS objects, 38% free, 25MB/41MB, paused 824us total 31.776ms
,D/VoicemailCleanupService( 1380): Cleaning up data for package: com.test.thalitest
,I/Keyboard.Facilitator.DecoderInitializer( 1110): run()
,I/Decoder ( 1110): createOrResetDecoder
,I/art     (  762): Explicit concurrent mark sweep GC freed 29506(1579KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 899us total 87.160ms
,I/UpdateIcingCorporaServi( 1366): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,W/Launcher( 1272): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@1d3ee79a new=com.google.android.velvet.VelvetApplication@1d3ee79a
,I/Adreno-EGL(  948): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
I/OpenGLRenderer(  948): Initialized EGL, version 1.4
,D/OpenGLRenderer(  948): Enabling debug mode 0
,I/ActivityManager(  762): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3876 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/ConfigService( 1558): onCreate
,D/BackupManagerService(  762): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService(  762): Receieved: android.intent.action.PACKAGE_REMOVED
,W/InputMethodManagerService(  762): Got RemoteException sending setActive(false) notification to pid 3417 uid 10270
,I/Keyboard.Facilitator( 1110): onFinishInput()
,D/TaskPersister(  762): removeObsoleteFile: deleting file=216_task.xml
,I/art     (  762): Explicit concurrent mark sweep GC freed 5217(286KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 1.767ms total 125.994ms
,W/ContextImpl( 3876): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1110): run()
,I/ActivityManager(  762): Killing 3249:com.google.android.partnersetup/u0a13 (adj 15): empty #17
D/PackageBroadcastService( 1604): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1604): Clearing selected account for com.test.thalitest
,I/Keyboard.Facilitator( 1110): onFinishInput()
,I/UpdateIcingCorporaServi( 1366): UpdateCorporaTask done [took 161 ms] updated apps [took 161 ms] 
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1110): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1110): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1110): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1110): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1110): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1110): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1110): run() : Loading LM = user
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1110): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1110): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1110): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1110): run()
I/StatsUtilsManager( 1110): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1110): shouldRecordStats() = Too Soon
,W/IInputConnectionWrapper( 1272): showStatusIcon on inactive InputConnection
,D/AndroidRuntime( 3836): Shutting down VM
,D/ChimeraCfgMgr( 1604): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1604): Module APK com.google.android.play.games already loaded
,W/libprocessgroup(  762): failed to open /acct/uid_10013/pid_3249/cgroup.procs: No such file or directory
,D/ChimeraCfgMgr( 1604): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1604): Module APK com.google.android.play.games already loaded
,E/NetworkScheduler.SchedulerReceiver( 1558): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1558): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/LocationSettingsChecker( 1604): Removing dialog suppression flag for package com.test.thalitest
,I/ActivityManager(  762): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3916 uid=10039 gids={50039, 9997} abi=armeabi-v7a
,I/art     (  194): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 178us total 8.830ms
,D/gH_CompatibleDatabase( 1604): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1604): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
I/art     (  194): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 449us total 7.972ms
,D/gH_MetricsDatabase( 1604): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1604): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,W/FileUtils( 1604): Failed to chmod(/data/data/com.google.android.gms/databases/help_responses.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
D/gH_CompatibleDatabase( 1604): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1604): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,E/SQLiteLog( 1604): (3850) statement aborts at 21: [DELETE FROM help_responses WHERE app_package_name="com.test.thalitest"] disk I/O error
I/art     (  194): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 166us total 7.529ms
,D/gH_CompatibleDatabase( 1604): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,--------- beginning of crash
E/AndroidRuntime( 1604): FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
E/AndroidRuntime( 1604): Process: com.google.android.gms, PID: 1604
E/AndroidRuntime( 1604): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1604): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1604): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 1604): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1604): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1604): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 1604): 	at com.google.android.gms.googlehelp.b.b.d(SourceFile:535)
E/AndroidRuntime( 1604): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:52)
E/AndroidRuntime( 1604): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 1604): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1604): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 1604): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/Process ( 1604): Sending signal. PID: 1604 SIG: 9
,E/DropBoxManagerService(  762): Can't write: system_app_crash
E/DropBoxManagerService(  762): java.io.FileNotFoundException: /data/system/dropbox/drop94.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  762): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  762): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  762): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  762): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  762): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  762): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12006)
E/DropBoxManagerService(  762): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  762): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  762): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  762): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  762): 	... 5 more
,D/ConnectivityService(  762): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@37922b99)
,D/ConnectivityService(  762): releasing NetworkRequest NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  762): RemoteException caught trying to send a callback msg for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]

```
