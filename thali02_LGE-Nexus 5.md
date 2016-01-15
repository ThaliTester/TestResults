#### Test 56151093f3290d6_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
I/GAv4    ( 3130): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3130):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3130):   adb logcat -s GAv4
W/GAv4    ( 3130): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3130): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3130): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 3130): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
D/Finsky  ( 2598): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
W/ResourcesManager( 3130): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3130): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  736): Killing 2566:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
V/JNIHelp ( 3130): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/System  ( 3130): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3130): Installed default security provider GmsCore_OpenSSL
W/libprocessgroup(  736): failed to open /acct/uid_10069/pid_2566/cgroup.procs: No such file or directory
V/GLSActivity( 1571): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 1630): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/Icing   ( 1630): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/Icing   ( 1630): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1630): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
,I/ActivityManager(  736): Killing 2517:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
W/libprocessgroup(  736): failed to open /acct/uid_10045/pid_2517/cgroup.procs: No such file or directory
D/AndroidRuntime( 3204): 
D/AndroidRuntime( 3204): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3204): CheckJNI is OFF
D/AndroidRuntime( 3204): Calling main entry com.android.commands.am.Am
I/ActivityManager(  736): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  736): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3228 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3204): Shutting down VM
V/ActivityManager(  736): Display changed displayId=0
I/WebViewFactory( 3228): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3228): Time to load native libraries: 2 ms (timestamps 9549-9551)
I/LibraryLoader( 3228): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3228): Binding Chromium to main looper Looper (main, tid 1) {3b20baa2}
I/LibraryLoader( 3228): Expected native library version number "",actual native library version number ""
I/chromium( 3228): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3228): Initializing chromium process, singleProcess=true
W/art     ( 3228): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3228): ApplicationContext is null in ApplicationStatus
,W/chromium( 3228): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3228): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 3228): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3228): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  736): Message: 20
D/BluetoothManagerService(  736): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@727c5cd:true
,W/art     ( 3228): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3228): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3228): CordovaWebView is running on device made by: LGE
,W/art     ( 3228): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3228): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3228): Render dirty regions requested: true
,D/Atlas   ( 3228): Validating map...
,W/chromium( 3228): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3228): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3228): Enabling debug mode 0
,W/IInputConnectionWrapper( 3228): showStatusIcon on inactive InputConnection
,I/ActivityManager(  736): Displayed com.test.thalitest/.MainActivity: +444ms (total +58s101ms)
,W/BindingManager( 3228): Cannot call determinedVisibility() - never saw a connection for the pid: 3228
,D/JsMessageQueue( 3228): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3228): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257340160
D/JX-Cordova( 3228): jxcore cordova android initializing
,W/jxcore-log( 3228): Initializing JXcore engine
W/jxcore-log( 3228): JXcore engine is ready
,W/jxcore-log( 3228): Starting JXcore engine
,W/.test.thalitest( 3228): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[8369]" dev="sockfs" ino=8369 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3228): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
,W/.test.thalitest( 3228): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8412]" dev="sockfs" ino=8412 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3228): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[20580]" dev="sockfs" ino=20580 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3228): Platform android
W/jxcore-log( 3228): 
W/jxcore-log( 3228): Process ARCH arm
W/jxcore-log( 3228): 
,I/jxcore-log( 3228): JXcore Cordova bridge is ready!
I/jxcore-log( 3228): 
W/jxcore-log( 3228): JXcore engine is started
I/Choreographer( 3228): Skipped 120 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3228): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3228): Toggling radios to true
I/jxcore-log( 3228): 
,D/BluetoothAdapter( 3228): enable(): BT is already enabled..!
,D/WifiService(  736): New client listening to asynchronous messages
,D/WifiService(  736): setWifiEnabled: true pid=3228, uid=10270
E/WifiService(  736): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3228): Radios toggled
I/jxcore-log( 3228): 
I/jxcore-log( 3228): My device name is: LGE-Nexus 5
I/jxcore-log( 3228): 
,I/wpa_supplicant( 1031): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  736): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  736): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
E/native  (  736): do suspend true
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,I/ActivityManager(  736): Killing 2680:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,V/NativeCrypto( 1571): Read error: ssl=0xb3f39e00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1571): SSL shutdown failed: ssl=0xb3f39e00: I/O error during system call, Broken pipe
,D/ConnectivityService(  736): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  736): ValidatedState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  736): DefaultState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  736): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  736): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  736): Checking http://clients3.google.com/generate_204 on "NG7005g"
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  736): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,W/libprocessgroup(  736): failed to open /acct/uid_10003/pid_2680/cgroup.procs: No such file or directory
,D/ConnectivityService(  736): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  736): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
E/WifiConfigStore(  736): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiStateMachine(  736): Start Disconnecting Watchdog 1
,E/native  (  736): do suspend true
,I/wpa_supplicant( 1031): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,D/ConnectivityService(  736): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/Nat464Xlat(  736): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  736): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  736): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  736): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  736): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1630): CM callback handler got msg 524292
D/ConnectivityManager.CallbackHandler(  901): CM callback handler got msg 524292
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  736): Disconnected - quitting
,D/ConnectivityService(  736): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  736): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory( 1238): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  736): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,D/WifiNetworkAgent(  736): NetworkAgent: NetworkAgent channel lost
,I/wpa_supplicant( 1031): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant( 1031): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1031): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1031): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  736): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  736): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  736): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  736): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  179): Setting iface cfg
,E/WifiStateMachine(  736): Start Dhcp Watchdog 2
,E/native  (  736): do suspend false
,E/WifiStateMachine(  736): scanCount==0 - aborting
,I/dhcpcd  ( 3305): version 5.5.6 starting
,E/dhcpcd  ( 3305): get_duid: Read-only file system
,I/dhcpcd  ( 3305): wlan0: rebinding lease of 192.168.1.114
,I/chromium( 3228): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/dhcpcd  ( 3305): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3305): wlan0: leased 192.168.1.114 for 86400 seconds
,D/ConnectivityService(  736): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  736): MasterInitialState.processMessage what=3
,D/ConnectivityService(  736): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  736): MasterInitialState.processMessage what=3
,V/MusicLeanback( 2701): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,E/GpsLocationProvider(  736): No APN found to select.
I/SystemUpdateService( 1630): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1630): onCreate
,D/SystemUpdateService( 1630): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,E/GpsLocationProvider(  736): No APN found to select.
,I/SystemUpdateService( 1630): active receiver: enabled
,I/SystemUpdateService( 1630): showing system update notification
,I/iu.Environment( 1630): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1630): num queued entries: 0
,I/iu.UploadsManager( 1630): num updated entries: 0
I/iu.SyncManager( 1630): NEXT; no task
,I/Babel   ( 1890): connection state changed from CONNECTED to DISCONNECTED
,I/ValidateNoPeople(  736): skipping global notification
,V/SystemUpdateService( 1630): retry (wakeup: false) in 3599983 ms
,I/ActivityManager(  736): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3352 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/SystemUpdateService( 1630): onDestroy
,E/native  (  736): do suspend true
,D/ConnectivityService(  736): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  736): Adding iface wlan0 to network 101
,E/WifiStateMachine(  736): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  736): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  736): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/ConnectivityService(  736): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  736): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  736): Setting Dns servers for network 101 to [/192.168.1.1]
D/Nat464Xlat(  736): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  736): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  736): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  736): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  736):    accepting network in place of null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  736): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  736): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  736): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  736): Checking http://clients3.google.com/generate_204 on "NG7005g"
D/CSLegacyTypeTracker(  736): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  736): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  736): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  736): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1630): CM callback handler got msg 524290
D/ConnectivityManager.CallbackHandler(  901): CM callback handler got msg 524290
,I/GAv4    ( 3352): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3352):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3352):   adb logcat -s GAv4
,W/GAv4    ( 3352): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3352): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3352): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  736): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 15 Jan 2016 13:01:12 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452862872277], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452862872259]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  736): Don't send network conditions - lacking user consent.
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  736): Validated
D/ConnectivityService(  736): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  736): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  736): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
,D/ConnectivityService(  736): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler(  901): CM callback handler got msg 524290
D/ConnectivityManager.CallbackHandler( 1630): CM callback handler got msg 524290
D/ConnectivityService(  736): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/TelephonyNetworkFactory( 1238): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/Nat464Xlat(  736): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  736): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1630): CM callback handler got msg 524295
D/ConnectivityManager.CallbackHandler(  901): CM callback handler got msg 524295
,I/WebViewFactory( 3352): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3352): Time to load native libraries: 2 ms (timestamps 5875-5877)
,I/LibraryLoader( 3352): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3352): Binding Chromium to main looper Looper (main, tid 1) {e59e744}
I/LibraryLoader( 3352): Expected native library version number "",actual native library version number ""
,I/chromium( 3352): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3352): Initializing chromium process, singleProcess=true
,W/art     ( 3352): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3352): ApplicationContext is null in ApplicationStatus
,W/chromium( 3352): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3352): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3352): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3352): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/NSApplication( 3352): Starting up...
,W/AudioManagerAndroid( 3352): Requires BLUETOOTH permission
,I/ActivityManager(  736): Killing 2650:com.android.settings/1000 (adj 15): empty #17
,D/WifiService(  736): Client connection lost with reason: 4
,W/libprocessgroup(  736): failed to open /acct/uid_1000/pid_2650/cgroup.procs: No such file or directory
,V/MusicLeanback( 2701): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1630): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1630): onCreate
,D/SystemUpdateService( 1630): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1630): active receiver: enabled
,I/SystemUpdateService( 1630): showing system update notification
,I/iu.Environment( 1630): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1630): num queued entries: 0
,I/iu.UploadsManager( 1630): num updated entries: 0
I/iu.SyncManager( 1630): NEXT; no task
,W/art     ( 2846): Suspending all threads took: 11.579ms
,V/SystemUpdateService( 1630): retry (wakeup: false) in 3599929 ms
I/ValidateNoPeople(  736): skipping global notification
,D/SystemUpdateService( 1630): onDestroy
,I/Babel   ( 1890): connection state changed from DISCONNECTED to CONNECTED
,D/ConnectivityService(  736): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,D/ConnectivityService(  736): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  736): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2701): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2701): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1630): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1630): onCreate
,D/SystemUpdateService( 1630): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1630): active receiver: enabled
,I/SystemUpdateService( 1630): showing system update notification
,I/ValidateNoPeople(  736): skipping global notification
,E/GpsLocationProvider(  736): No APN found to select.
,V/SystemUpdateService( 1630): retry (wakeup: false) in 3599971 ms
,D/SystemUpdateService( 1630): onDestroy
,I/art     (  736): Explicit concurrent mark sweep GC freed 46618(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 27MB/41MB, paused 1.231ms total 58.371ms
,D/Finsky  ( 2598): [260] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2598): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/GLSActivity( 1571): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1571): Vacuum at: now=1452862884173 tag=VacuumService
,D/HeadsetStateMachine( 2061): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 2061): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
D/HeadsetStateMachine( 2061): Disconnected process message: 11, size: 0
,I/ClearcutLoggerApiImpl( 1571): disconnect managed GoogleApiClient
,D/HeadsetStateMachine( 2061): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 2061): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 2061): Disconnected process message: 11, size: 0
,I/ActivityManager(  736): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=3497 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,W/bt-smp  ( 2061): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2061): Plain text(LSB ~ MSB) = 18 36 53 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2061): Encrypted text(LSB ~ MSB) = 63 82 0f c1 1b 2d 11 68 a5 b9 15 54 2f 38 5c 3b 
W/bt-btm  ( 2061): Stopping oneshot timer
,I/EventLogService( 1630): Aggregate from 1452861262564 (log), 1452861262564 (data)
,I/GAv4    ( 3497): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3497):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3497):   adb logcat -s GAv4
,W/GAv4    ( 3497): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3497): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3497): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  736): Killing 2540:com.google.android.gm/u0a70 (adj 15): empty #17
,W/libprocessgroup(  736): failed to open /acct/uid_10070/pid_2540/cgroup.procs: No such file or directory
,D/ChimeraCfgMgr( 1630): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1630): Module APK com.google.android.play.games already loaded
,I/GamesSyncServiceMain( 1630): Found unexpected GCM tag when scheduling; aborting
W/GamesSyncServiceMain( 1630): Failed to execute periodic sync, missing client context - aborting
,I/PhenotypeConfigurator( 1571): Scheduling Phenotype for one-off execution 10543 seconds from now (1452863773371)
,D/GetConfigurationSnapshotOperation( 1571): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1571): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1571): Using platform SSLCertificateSocketFactory
,D/ConnectivityService(  736): reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10008
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  736): ValidatedState{ when=-3ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  736): DefaultState{ when=-3ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  736): Forcing reevaluation
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  736): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  736): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  736): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 15 Jan 2016 13:19:16 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452863956310], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452863956293]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  736): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  736): Validated
,D/ConnectivityService(  736): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  736): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  736): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  736): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  901): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1630): CM callback handler got msg 524290
,I/UsageStatsService(  736): User[0] Flushing usage stats to disk
,I/ProcessStatsService(  736): Prepared write state in 11ms
,I/ProcessStatsService(  736): Pruning old procstats: /data/system/procstats/state-2016-01-14-19-48-09.bin
,W/bt-smp  ( 2061): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2061): Plain text(LSB ~ MSB) = fa 79 51 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2061): Encrypted text(LSB ~ MSB) = 0d 0c cc f1 67 c8 3b 81 84 1c cd 2f e3 21 60 af 
,W/bt-btm  ( 2061): Stopping oneshot timer
,TIME-OUT KILL (timeout was 1800000ms)
```
