#### Test 565307121a686b7_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
I/GAv4    ( 3133): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3133):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3133):   adb logcat -s GAv4
W/GAv4    ( 3133): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3133): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3133): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 3133): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
D/Finsky  ( 2640): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
I/ActivityManager(  733): Killing 2088:com.google.android.deskclock/u0a38 (adj 15): empty #17
W/ResourcesManager( 3133): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3133): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/libprocessgroup(  733): failed to open /acct/uid_10038/pid_2088/cgroup.procs: No such file or directory
V/JNIHelp ( 3133): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/System  ( 3133): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3133): Installed default security provider GmsCore_OpenSSL
V/GLSActivity( 1609): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 1629): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/Icing   ( 1629): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1629): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/Icing   ( 1629): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
,I/ActivityManager(  733): Killing 2608:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
W/libprocessgroup(  733): failed to open /acct/uid_10069/pid_2608/cgroup.procs: No such file or directory
D/AndroidRuntime( 3203): 
D/AndroidRuntime( 3203): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3203): CheckJNI is OFF
D/AndroidRuntime( 3203): Calling main entry com.android.commands.am.Am
I/ActivityManager(  733): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  733): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3236 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3203): Shutting down VM
V/ActivityManager(  733): Display changed displayId=0
I/WebViewFactory( 3236): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3236): Time to load native libraries: 2 ms (timestamps 965-967)
I/LibraryLoader( 3236): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3236): Binding Chromium to main looper Looper (main, tid 1) {e0f2abc}
I/LibraryLoader( 3236): Expected native library version number "",actual native library version number ""
I/chromium( 3236): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3236): Initializing chromium process, singleProcess=true
,W/art     ( 3236): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3236): ApplicationContext is null in ApplicationStatus
,W/chromium( 3236): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3236): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 3236): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3236): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  733): Message: 20
D/BluetoothManagerService(  733): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@33f89159:true
,W/art     ( 3236): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3236): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3236): CordovaWebView is running on device made by: LGE
,W/art     ( 3236): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3236): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3236): Render dirty regions requested: true
,D/Atlas   ( 3236): Validating map...
,W/chromium( 3236): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3236): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3236): Enabling debug mode 0
,I/Keyboard.Facilitator( 1083): onFinishInput()
,W/BindingManager( 3236): Cannot call determinedVisibility() - never saw a connection for the pid: 3236
,W/IInputConnectionWrapper( 3236): showStatusIcon on inactive InputConnection
I/ActivityManager(  733): Displayed com.test.thalitest/.MainActivity: +434ms (total +59s901ms)
,D/JsMessageQueue( 3236): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3236): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257343360
,I/chromium( 3236): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 3236): Initializing JXcore engine
W/jxcore-log( 3236): JXcore engine is ready
,W/Thread-301( 3291): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[8093]" dev="sockfs" ino=8093 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-301( 3291): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-301( 3291): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8143]" dev="sockfs" ino=8143 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-301( 3291): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[18931]" dev="sockfs" ino=18931 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3236): Starting JXcore engine
,W/jxcore-log( 3236): Platform android
W/jxcore-log( 3236): 
W/jxcore-log( 3236): Process ARCH arm
W/jxcore-log( 3236): 
,I/jxcore-log( 3236): JXcore Cordova bridge is ready!
I/jxcore-log( 3236): 
W/jxcore-log( 3236): JXcore engine is started
,I/jxcore-log( 3236): Toggling radios to true
I/jxcore-log( 3236): 
,D/BluetoothAdapter( 3236): enable(): BT is already enabled..!
,D/WifiService(  733): New client listening to asynchronous messages
D/WifiService(  733): setWifiEnabled: true pid=3236, uid=10270
E/WifiService(  733): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3236): Radios toggled
I/jxcore-log( 3236): 
I/jxcore-log( 3236): My device name is: LGE-Nexus 5
I/jxcore-log( 3236): 
,I/wpa_supplicant(  987): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  733): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  733): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/native  (  733): do suspend true
,D/CommandListener(  180): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1609): Read error: ssl=0xafdf7e00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1609): SSL shutdown failed: ssl=0xafdf7e00: I/O error during system call, Broken pipe
,D/ConnectivityService(  733): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): ValidatedState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): DefaultState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/ConnectivityService(  733): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  733): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,E/WifiConfigStore(  733): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiStateMachine(  733): Start Disconnecting Watchdog 1
I/wpa_supplicant(  987): wlan0: CTRL-EVENT-SCAN-STARTED 
E/native  (  733): do suspend true
,W/ProcessCpuTracker(  733): Skipping unknown process pid 3303
,D/CommandListener(  180): Clearing all IP addresses on wlan0
,D/ConnectivityService(  733): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityManager.CallbackHandler(  897): CM callback handler got msg 524292
D/Nat464Xlat(  733): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  733): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,D/ConnectivityService(  733): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityManager.CallbackHandler( 1629): CM callback handler got msg 524292
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): Disconnected - quitting
D/ConnectivityService(  733): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  733): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1227): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/ConnectivityService(  733): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,D/WifiNetworkAgent(  733): NetworkAgent: NetworkAgent channel lost
,I/wpa_supplicant(  987): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant(  987): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant(  987): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant(  987): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  733): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  733): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  733): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiConfigStore(  733): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  180): Setting iface cfg
E/WifiStateMachine(  733): Start Dhcp Watchdog 2
,E/native  (  733): do suspend false
,E/WifiStateMachine(  733): scanCount==0 - aborting
,I/dhcpcd  ( 3320): version 5.5.6 starting
,E/dhcpcd  ( 3320): get_duid: Read-only file system
,I/dhcpcd  ( 3320): wlan0: rebinding lease of 192.168.1.114
,D/ConnectivityService(  733): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  733): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  733): MasterInitialState.processMessage what=3
,D/Tethering(  733): MasterInitialState.processMessage what=3
,V/MusicLeanback( 2761): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1629): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1629): onCreate
,D/SystemUpdateService( 1629): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.Environment( 1629): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/SystemUpdateService( 1629): active receiver: enabled
,I/iu.UploadsManager( 1629): num queued entries: 0
,E/GpsLocationProvider(  733): No APN found to select.
,I/iu.UploadsManager( 1629): num updated entries: 0
I/iu.SyncManager( 1629): NEXT; no task
,I/SystemUpdateService( 1629): showing system update notification
,E/GpsLocationProvider(  733): No APN found to select.
,I/ValidateNoPeople(  733): skipping global notification
,V/SystemUpdateService( 1629): retry (wakeup: false) in 3599984 ms
,D/SystemUpdateService( 1629): onDestroy
,I/Babel   ( 1944): connection state changed from CONNECTED to DISCONNECTED
,I/ActivityManager(  733): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3337 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GAv4    ( 3337): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3337):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3337):   adb logcat -s GAv4
,W/GAv4    ( 3337): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3337): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3337): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 3337): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3337): Time to load native libraries: 1 ms (timestamps 7097-7098)
,I/LibraryLoader( 3337): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3337): Binding Chromium to main looper Looper (main, tid 1) {2e510250}
,I/LibraryLoader( 3337): Expected native library version number "",actual native library version number ""
I/chromium( 3337): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3337): Initializing chromium process, singleProcess=true
,W/art     ( 3337): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3337): ApplicationContext is null in ApplicationStatus
,W/chromium( 3337): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3337): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3337): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3337): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/jxcore-log( 3236): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3236): 
,W/AudioManagerAndroid( 3337): Requires BLUETOOTH permission
,I/NSApplication( 3337): Starting up...
,I/ActivityManager(  733): Killing 2556:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,W/libprocessgroup(  733): failed to open /acct/uid_10045/pid_2556/cgroup.procs: No such file or directory
,V/MusicLeanback( 2761): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1629): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
D/SystemUpdateService( 1629): onCreate
,D/SystemUpdateService( 1629): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1629): active receiver: enabled
,I/SystemUpdateService( 1629): showing system update notification
,I/ValidateNoPeople(  733): skipping global notification
,V/SystemUpdateService( 1629): retry (wakeup: false) in 3599978 ms
,D/SystemUpdateService( 1629): onDestroy
,I/jxcore-log( 3236): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 3236): 
,I/dhcpcd  ( 3320): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3320): wlan0: leased 192.168.1.114 for 86400 seconds
,I/jxcore-log( 3236): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3236): 
,E/native  (  733): do suspend true
,D/ConnectivityService(  733): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  733): Adding iface wlan0 to network 101
,E/ConnectivityService(  733): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  733): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/ConnectivityService(  733): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  733): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  733): Setting Dns servers for network 101 to [/192.168.1.1]
D/Nat464Xlat(  733): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  733): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  733): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): DefaultState{ when=-6ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): Connected
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/ConnectivityService(  733): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  733):    accepting network in place of null
D/CSLegacyTypeTracker(  733): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  733): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  733): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::5255:27ff:fef0:fd0b/64,192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  733): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1629): CM callback handler got msg 524290
D/ConnectivityManager.CallbackHandler(  897): CM callback handler got msg 524290
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 19 Jan 2016 22:06:52 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1453241212863], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1453241212833]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): Validated
D/ConnectivityService(  733): Validated NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  733): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  733): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  733): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  897): CM callback handler got msg 524290
D/ConnectivityService(  733): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/TelephonyNetworkFactory( 1227): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 1629): CM callback handler got msg 524290
,I/jxcore-log( 3236): Test app app.js loaded
I/jxcore-log( 3236): 
,I/chromium( 3236): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 3236): BLE advertisement is supported
I/jxcore-log( 3236): 
,D/ConnectivityService(  733): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,D/ConnectivityService(  733): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  733): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2761): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2761): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1629): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1629): onCreate
,D/SystemUpdateService( 1629): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.Environment( 1629): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1629): num queued entries: 0
,I/iu.UploadsManager( 1629): num updated entries: 0
,I/iu.SyncManager( 1629): NEXT; no task
,I/SystemUpdateService( 1629): active receiver: enabled
,I/SystemUpdateService( 1629): showing system update notification
,I/ValidateNoPeople(  733): skipping global notification
,V/SystemUpdateService( 1629): retry (wakeup: false) in 3599985 ms
,D/SystemUpdateService( 1629): onDestroy
,I/Babel   ( 1944): connection state changed from DISCONNECTED to CONNECTED
,I/art     (  733): Explicit concurrent mark sweep GC freed 44938(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 27MB/41MB, paused 930us total 54.712ms
,E/GpsLocationProvider(  733): No APN found to select.
,D/Finsky  ( 2640): [256] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2640): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/GLSActivity( 1609): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1609): Vacuum at: now=1453241226355 tag=VacuumService
,I/PhenotypeConfigurator( 1609): Scheduling Phenotype for one-off execution 11484 seconds from now (1453241226756)
,D/GetConfigurationSnapshotOperation( 1609): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1609): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1609): Using platform SSLCertificateSocketFactory
,V/GLSActivity( 1609): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1609): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Keyboard.Facilitator.LanguageModelFlusher( 1083): run()
I/Keyboard.Facilitator( 1083): flushDynamicLanguageModels()
,I/ClearcutLoggerApiImpl( 1609): disconnect managed GoogleApiClient
,I/EventLogService( 1629): Aggregate from 1453239483106 (log), 1453239483106 (data)
,I/jxcore-log( 3236): TAP version 13
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): # setup
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): # multiplex can send data
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): # teardown
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): ok 1 String should be length:200
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): # setup
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): # basic
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): # teardown
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): ok 2 sane
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): # setup
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): # another
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): # teardown
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): ok 3 sane
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): # setup
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): # successfully create a new pkcs12 file and return hash value
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): # teardown
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): ok 4 should be equal
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): ok 5 null
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): ok 6 (unnamed assert)
I/jxcore-log( 3236): 
I/jxcore-log( 3236): ok 7 should be equal
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): ok 8 should not throw
I/jxcore-log( 3236): 
I/jxcore-log( 3236): # setup
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): # successfully read a previous pkcs12 file and return hash value
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): # teardown
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): ok 9 (unnamed assert)
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): ok 10 (unnamed assert)
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): ok 11 should not throw
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): ok 12 should be equal
I/jxcore-log( 3236): 
I/jxcore-log( 3236): ok 13 should be equal
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): # setup
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): # failed to extract public key because of corrupt pkcs12 file
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): # teardown
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): ok 14 should be equal
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): # setup
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): # failed to get mobile documents path
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): # teardown
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): ok 15 should be equal
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): # setup
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): # #init should register the peerAvailabilityChanged event
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): # teardown
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): ok 16 should be equal
I/jxcore-log( 3236): 
I/jxcore-log( 3236): ok 17 should be equal
I/jxcore-log( 3236): 
I/jxcore-log( 3236): ok 18 should be equal
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): # setup
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): # #init should register the networkChanged event
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): # teardown
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): ok 19 should be equal
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): # setup
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): # #startBroadcasting should throw on null device name
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): # teardown
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): ok 20 should throw
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): # setup
I/jxcore-log( 3236): 
I/jxcore-log( 3236): # #startBroadcasting should throw on empty string device name
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): # teardown
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): ok 21 should throw
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): # setup
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): # #startBroadcasting should throw on non-number port
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): # teardown
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): ok 22 should throw
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): # setup
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): # #startBroadcasting should throw on NaN port
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): # teardown
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): ok 23 should throw
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): # setup
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): # #startBroadcasting should throw on negative port
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): # teardown
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): ok 24 should throw
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): # setup
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): # #startBroadcasting should throw on too large port
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): # teardown
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): ok 25 should throw
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): # setup
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): # #startBroadcasting should call Mobile("StartBroadcasting") without an error
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): # teardown
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): ok 26 should be equal
I/jxcore-log( 3236): 
I/jxcore-log( 3236): ok 27 should be equal
I/jxcore-log( 3236): 
I/jxcore-log( 3236): ok 28 should be equal
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): # setup
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): # #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): # teardown
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): ok 29 should be equal
I/jxcore-log( 3236): 
I/jxcore-log( 3236): ok 30 should be equal
I/jxcore-log( 3236): 
I/jxcore-log( 3236): ok 31 should be equal
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): # setup
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): # #stopBroadcasting should call Mobile("StopBroadcasting") without an error
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): # teardown
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): ok 32 should be equal
I/jxcore-log( 3236): 
I/jxcore-log( 3236): ok 33 should be equal
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): # setup
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): # #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): # teardown
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): ok 34 should be equal
I/jxcore-log( 3236): 
I/jxcore-log( 3236): ok 35 should be equal
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): # setup
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): # #connect should call Mobile("Connect") with a port and without an error
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): # teardown
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): ok 36 should be equal
I/jxcore-log( 3236): 
I/jxcore-log( 3236): ok 37 should be equal
I/jxcore-log( 3236): 
I/jxcore-log( 3236): ok 38 should be equal
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): # setup
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): # #connect should call Mobile("Connect") and handle an error
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): # teardown
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): ok 39 should be equal
I/jxcore-log( 3236): 
I/jxcore-log( 3236): ok 40 should be equal
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): # setup
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): # should call Mobile("Disconnect") without an error
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): # teardown
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): ok 41 should be equal
I/jxcore-log( 3236): 
I/jxcore-log( 3236): ok 42 should be equal
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): # setup
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): # should call Mobile("Disconnect") and handle an error
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): # teardown
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): ok 43 should be equal
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): ok 44 should be equal
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): # setup
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): # ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): # teardown
I/jxcore-log( 3236): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): setDiscoveryMode: Mode set to BLE_AND_WIFI
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3236): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453241443806.3236
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3236): bind: Binding a new listener
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3236): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3236): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453241443806.3236","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3236): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3236): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3236): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3236): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3236): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 3236): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3236): start: OK
I/io.jxcore.node.ConnectionHelper( 3236): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453241443806.3236
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3236): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3236): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3236): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3236): createAdvertiseData: From: 1453241443806.3236 b6a44ad1-d319-4b3a-815d-8b805a47fb51 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3236): 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3236): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 52, -4, -17, 17, -82, 103]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3236): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3236): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453241443806.3236","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3236): start: {"pi":"34:FC:EF:11:AE:67","pn":"1453241443806.3236","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3236): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1453241443806.3236","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3236): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): setState: RUNNING_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453241443806.3236
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): startBlePeerDiscovery: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3236): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3236): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 3236): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
,I/io.jxcore.node.ConnectionHelper( 3236): start: OK
,I/jxcore-log( 3236): ok 45 Should be able to call startBroadcasting without error
I/jxcore-log( 3236): 
,I/io.jxcore.node.ConnectionHelper( 3236): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3236): stop: Stopping Bluetooth...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3236): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3236): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3236): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3236): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3236): onServerStopped
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3236): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3236): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 3236): onConnectionManagerStateChanged: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): stop: Stopping peer discovery...
,D/BluetoothLeScanner( 3236): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3236): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3236): Local services cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): stop: Stopping P2P device discovery...
,I/wpa_supplicant(  987): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): P2P device discovery stopped successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): setState: NOT_INITIALIZED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3236): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3236): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3236): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3236): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 3236): ok 46 Should be able to call stopBroadcasting without error
I/jxcore-log( 3236): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): setDiscoveryMode: Mode set to BLE_AND_WIFI
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3236): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453241443893.3236
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3236): bind: Binding a new listener
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3236): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3236): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453241443893.3236","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3236): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3236): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3236): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3236): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3236): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 3236): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3236): start: OK
I/io.jxcore.node.ConnectionHelper( 3236): start: Using peer discovery mode: BLE_AND_WIFI
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453241443893.3236
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3236): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3236): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3236): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3236): createAdvertiseData: From: 1453241443893.3236 b6a44ad1-d319-4b3a-815d-8b805a47fb51 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3236): 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3236): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 52, -4, -17, 17, -82, 103]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3236): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3236): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453241443893.3236","ra":"34:FC:EF:11:AE:67"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3236): start: {"pi":"34:FC:EF:11:AE:67","pn":"1453241443893.3236","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3236): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1453241443893.3236","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): start: Starting P2P device discovery...
,I/wpa_supplicant(  987): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): setState: RUNNING_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453241443893.3236
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): startBlePeerDiscovery: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3236): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): setState: RESTARTING
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3236): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 3236): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
,I/wpa_supplicant(  987): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): P2P device discovery stopped successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): setState: RESTARTING
,I/io.jxcore.node.ConnectionHelper( 3236): start: OK
I/jxcore-log( 3236): ok 47 Should be able to call startBroadcasting without error
I/jxcore-log( 3236): 
I/io.jxcore.node.ConnectionHelper( 3236): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3236): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3236): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3236): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3236): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3236): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3236): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 3236): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): stop: Stopping peer discovery...
,D/BluetoothLeScanner( 3236): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3236): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3236): Local services cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): setState: NOT_INITIALIZED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3236): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3236): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3236): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3236): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 3236): ok 48 Should be able to call stopBroadcasting without error
I/jxcore-log( 3236): 
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3236): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3236): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): setDiscoveryMode: Mode set to BLE_AND_WIFI
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3236): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453241443934.3236
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3236): bind: Binding a new listener
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3236): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3236): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453241443934.3236","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3236): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3236): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3236): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3236): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3236): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3236): start: OK
I/io.jxcore.node.ConnectionHelper( 3236): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 3236): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453241443934.3236
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3236): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3236): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3236): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3236): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3236): createAdvertiseData: From: 1453241443934.3236 b6a44ad1-d319-4b3a-815d-8b805a47fb51 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3236): 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3236): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 52, -4, -17, 17, -82, 103]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3236): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3236): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453241443934.3236","ra":"34:FC:EF:11:AE:67"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3236): start: {"pi":"34:FC:EF:11:AE:67","pn":"1453241443934.3236","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3236): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1453241443934.3236","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): start: Starting P2P device discovery...
I/wpa_supplicant(  987): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): setState: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 3236): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453241443934.3236
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3236): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 3236): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 3236): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  987): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): P2P device discovery stopped successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): setState: RESTARTING
,I/jxcore-log( 3236): ok 49 Should be able to call startBroadcasting without error
I/jxcore-log( 3236): 
,I/io.jxcore.node.ConnectionHelper( 3236): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3236): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3236): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3236): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3236): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3236): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3236): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3236): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3236): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 3236): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): stop: Stopping peer discovery...
,D/BluetoothLeScanner( 3236): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): stopBlePeerDiscovery: Stopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3236): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3236): Local services cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): setState: NOT_INITIALIZED,
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3236): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3236): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3236): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3236): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 3236): ok 50 Should be able to call stopBroadcasting without error
I/jxcore-log( 3236): 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3236): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453241443973.3236
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3236): bind: Binding a new listener
D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3236): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3236): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453241443973.3236","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3236): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3236): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3236): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 3236): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3236): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 3236): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3236): start: OK
I/io.jxcore.node.ConnectionHelper( 3236): start: Using peer discovery mode: BLE_AND_WIFI
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3236): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453241443973.3236
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3236): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3236): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3236): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3236): createAdvertiseData: From: 1453241443973.3236 b6a44ad1-d319-4b3a-815d-8b805a47fb51 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3236): 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3236): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 52, -4, -17, 17, -82, 103]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3236): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3236): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453241443973.3236","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3236): start: {"pi":"34:FC:EF:11:AE:67","pn":"1453241443973.3236","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3236): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1453241443973.3236","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): start: Starting P2P device discovery...
,I/wpa_supplicant(  987): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453241443973.3236
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): startBlePeerDiscovery: Already running
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): startBlePeerDiscovery: OK
,I/io.jxcore.node.ConnectionHelper( 3236): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): start: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3236): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): setState: RESTARTING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 3236): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3236): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/wpa_supplicant(  987): P2P-FIND-STOPPED 
I/jxcore-log( 3236): ok 51 Should be able to call startBroadcasting without error
I/jxcore-log( 3236): 
I/io.jxcore.node.ConnectionHelper( 3236): stop
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3236): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3236): Shutting down...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3236): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3236): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): setState: RESTARTING
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3236): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3236): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): stop: Stopping peer discovery...
I/io.jxcore.node.ConnectionHelper( 3236): onConnectionManagerStateChanged: NOT_STARTED
D/BluetoothLeScanner( 3236): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3236): stop: Stopping services
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3236): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3236): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3236): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3236): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3236): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): P2P device discovery stopped successfully
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): setState: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3236): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 3236): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 3236): ok 52 Should be able to call stopBroadcasting without error
I/jxcore-log( 3236): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3236): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453241443999.3236
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3236): bind: Binding a new listener
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3236): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3236): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453241443999.3236","ra":"34:FC:EF:11:AE:67"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3236): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3236): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3236): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 3236): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3236): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 3236): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3236): start: OK
I/io.jxcore.node.ConnectionHelper( 3236): start: Using peer discovery mode: BLE_AND_WIFI
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453241443999.3236
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3236): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3236): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3236): Waiting for incoming connections...
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3236): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3236): createAdvertiseData: From: 1453241443999.3236 b6a44ad1-d319-4b3a-815d-8b805a47fb51 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3236): 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3236): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 52, -4, -17, 17, -82, 103]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3236): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3236): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453241443999.3236","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3236): start: {"pi":"34:FC:EF:11:AE:67","pn":"1453241443999.3236","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3236): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1453241443999.3236","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453241443999.3236
I/wpa_supplicant(  987): p2p0: P2P: Reject scan trigger since one is already pending
,I/io.jxcore.node.ConnectionHelper( 3236): start: OK
,I/jxcore-log( 3236): ok 53 Should be able to call startBroadcasting without error
I/jxcore-log( 3236): 
I/io.jxcore.node.ConnectionHelper( 3236): stop
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3236): stop: Stopping Bluetooth...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): startBlePeerDiscovery: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3236): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3236): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3236): shutdown
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): setState: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3236): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3236): setState: NOT_STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3236): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 3236): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3236): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3236): onConnectionManagerStateChanged: NOT_STARTED
I/wpa_supplicant(  987): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): setState: RESTARTING
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3236): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3236): onServerStopped
,D/BluetoothLeScanner( 3236): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3236): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): stop: Stopping P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3236): Local services cleared successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3236): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): P2P device discovery stopped successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3236): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3236): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 3236): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 3236): ok 54 Should be able to call stopBroadcasting without error
I/jxcore-log( 3236): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): setDiscoveryMode: Mode set to BLE_AND_WIFI
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3236): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453241444028.3236
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3236): bind: Binding a new listener
D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3236): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3236): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453241444028.3236","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3236): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3236): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3236): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3236): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3236): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 3236): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3236): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3236): start: OK
I/io.jxcore.node.ConnectionHelper( 3236): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453241444028.3236
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3236): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3236): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3236): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3236): createAdvertiseData: From: 1453241444028.3236 b6a44ad1-d319-4b3a-815d-8b805a47fb51 34:FC:EF:11:AE:67
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3236): 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3236): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 52, -4, -17, 17, -82, 103]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3236): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3236): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453241444028.3236","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3236): start: {"pi":"34:FC:EF:11:AE:67","pn":"1453241444028.3236","ra":"34:FC:EF:11:AE:67"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3236): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1453241444028.3236","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): start: Starting P2P device discovery...
I/wpa_supplicant(  987): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453241444028.3236
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): startWifiPeerDiscovery: Wi-Fi Direct OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): setState: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3236): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3236): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 3236): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/wpa_supplicant(  987): P2P-FIND-STOPPED 
I/io.jxcore.node.ConnectionHelper( 3236): start: OK
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): P2P device discovery stopped successfully
I/jxcore-log( 3236): ok 55 Should be able to call startBroadcasting without error
I/jxcore-log( 3236): 
I/io.jxcore.node.ConnectionHelper( 3236): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3236): stop: Stopping Bluetooth...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3236): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3236): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): setState: RESTARTING
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3236): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3236): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3236): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3236): Exiting thread
I/io.jxcore.node.ConnectionHelper( 3236): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3236): onServerStopped
,D/BluetoothLeScanner( 3236): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3236): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3236): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3236): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3236): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3236): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3236): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 3236): ok 56 Should be able to call stopBroadcasting without error
I/jxcore-log( 3236): 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3236): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453241444054.3236
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3236): bind: Binding a new listener
D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3236): initialize: My bluetooth address is 34:FC:EF:11:AE:67
D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3236): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453241444054.3236","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3236): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3236): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3236): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 3236): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3236): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3236): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3236): start: OK
I/io.jxcore.node.ConnectionHelper( 3236): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453241444054.3236
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3236): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3236): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3236): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3236): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3236): createAdvertiseData: From: 1453241444054.3236 b6a44ad1-d319-4b3a-815d-8b805a47fb51 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3236): 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3236): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 52, -4, -17, 17, -82, 103]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3236): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3236): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453241444054.3236","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3236): start: {"pi":"34:FC:EF:11:AE:67","pn":"1453241444054.3236","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3236): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1453241444054.3236","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): setState: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 3236): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453241444054.3236
I/wpa_supplicant(  987): p2p0: P2P: Reject scan trigger since one is already pending
I/jxcore-log( 3236): ok 57 Should be able to call startBroadcasting without error
I/jxcore-log( 3236): 
I/io.jxcore.node.ConnectionHelper( 3236): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3236): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3236): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3236): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3236): shutdown
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3236): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3236): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): setState: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): setState: RESTARTING
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3236): release: 1 listener(s) left
I/io.jxcore.node.ConnectionHelper( 3236): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3236): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3236): Local service added successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3236): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3236): onConnectionManagerStateChanged: NOT_STARTED
I/wpa_supplicant(  987): P2P-FIND-STOPPED 
D/BluetoothLeScanner( 3236): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3236): stop: Stopping services
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3236): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): setState: NOT_INITIALIZED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3236): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3236): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3236): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3236): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 3236): ok 58 Should be able to call stopBroadcasting without error
I/jxcore-log( 3236): 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3236): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453241444084.3236
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3236): bind: Binding a new listener
D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3236): initialize: My bluetooth address is 34:FC:EF:11:AE:67
D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3236): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453241444084.3236","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3236): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3236): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3236): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 3236): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3236): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3236): start: OK
I/io.jxcore.node.ConnectionHelper( 3236): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 3236): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3236): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453241444084.3236
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3236): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3236): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3236): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3236): createAdvertiseData: From: 1453241444084.3236 b6a44ad1-d319-4b3a-815d-8b805a47fb51 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3236): 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3236): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 52, -4, -17, 17, -82, 103]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3236): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3236): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453241444084.3236","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3236): start: {"pi":"34:FC:EF:11:AE:67","pn":"1453241444084.3236","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3236): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1453241444084.3236","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): start: OK
I/wpa_supplicant(  987): p2p0: P2P: Reject scan trigger since one is already pending
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453241444084.3236
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): startBlePeerDiscovery: OK
I/io.jxcore.node.ConnectionHelper( 3236): start: OK
I/jxcore-log( 3236): ok 59 Should be able to call startBroadcasting without error
I/jxcore-log( 3236): 
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): setState: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3236): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3236): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3236): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3236): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3236): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): setState: RESTARTING
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3236): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3236): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3236): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 3236): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/wpa_supplicant(  987): P2P-FIND-STOPPED 
I/io.jxcore.node.ConnectionHelper( 3236): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3236): onConnectionManagerStateChanged: NOT_STARTED
D/BluetoothLeScanner( 3236): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3236): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3236): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3236): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3236): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3236): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3236): Exiting thread
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3236): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3236): onServerStopped
I/jxcore-log( 3236): ok 60 Should be able to call stopBroadcasting without error
I/jxcore-log( 3236): 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3236): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453241444110.3236
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3236): bind: Binding a new listener
D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3236): initialize: My bluetooth address is 34:FC:EF:11:AE:67
D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3236): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453241444110.3236","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3236): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3236): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3236): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 3236): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3236): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3236): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3236): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3236): start: OK
I/io.jxcore.node.ConnectionHelper( 3236): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453241444110.3236
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3236): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3236): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3236): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3236): createAdvertiseData: From: 1453241444110.3236 b6a44ad1-d319-4b3a-815d-8b805a47fb51 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3236): 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3236): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 52, -4, -17, 17, -82, 103]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3236): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3236): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453241444110.3236","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3236): start: {"pi":"34:FC:EF:11:AE:67","pn":"1453241444110.3236","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3236): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1453241444110.3236","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): setState: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 3236): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453241444110.3236
I/wpa_supplicant(  987): p2p0: P2P: Reject scan trigger since one is already pending
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): startBlePeerDiscovery: OK
I/jxcore-log( 3236): ok 61 Should be able to call startBroadcasting without error
I/jxcore-log( 3236): 
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): setState: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3236): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 3236): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 3236): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3236): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3236): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3236): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3236): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3236): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3236): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3236): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): stop: Stopping peer discovery...
I/io.jxcore.node.ConnectionHelper( 3236): onConnectionManagerStateChanged: NOT_STARTED
I/wpa_supplicant(  987): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/BluetoothLeScanner( 3236): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3236): stop: Stopping services
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3236): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3236): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3236): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3236): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3236): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3236): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3236): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 3236): ok 62 Should be able to call stopBroadcasting without error
I/jxcore-log( 3236): 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3236): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453241444146.3236
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3236): bind: Binding a new listener
D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3236): initialize: My bluetooth address is 34:FC:EF:11:AE:67
D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3236): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453241444146.3236","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3236): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3236): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3236): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 3236): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3236): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3236): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3236): start: OK
I/io.jxcore.node.ConnectionHelper( 3236): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3236): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453241444146.3236
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3236): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3236): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3236): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3236): createAdvertiseData: From: 1453241444146.3236 b6a44ad1-d319-4b3a-815d-8b805a47fb51 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3236): 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3236): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 52, -4, -17, 17, -82, 103]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3236): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3236): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453241444146.3236","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3236): start: {"pi":"34:FC:EF:11:AE:67","pn":"1453241444146.3236","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3236): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1453241444146.3236","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): setState: RUNNING_WIFI
I/wpa_supplicant(  987): p2p0: P2P: Reject scan trigger since one is already pending
I/io.jxcore.node.ConnectionHelper( 3236): start: OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453241444146.3236
I/jxcore-log( 3236): ok 63 Should be able to call startBroadcasting without error
I/jxcore-log( 3236): 
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): startBlePeerDiscovery: OK
I/io.jxcore.node.ConnectionHelper( 3236): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3236): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3236): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3236): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3236): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3236): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3236): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3236): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3236): setState: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3236): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 3236): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3236): onConnectionManagerStateChanged: NOT_STARTED
I/wpa_supplicant(  987): P2P-FIND-STOPPED 
I/io.jxcore.node.ConnectionHelper( 3236): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): P2P device discovery stopped successfully
D/BluetoothLeScanner( 3236): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3236): stop: Stopping services
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3236): Local services cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3236): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3236): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): P2P device discovery stopped successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3236): Service requests cleared successfully
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3236): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 3236): ok 64 Should be able to call stopBroadcasting without error
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): # setup
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): # ThaliEmitter calls startBroadcasting twice with error
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): # teardown
I/jxcore-log( 3236): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): setDiscoveryMode: Mode set to BLE_AND_WIFI
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3236): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453241444952.3236
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3236): bind: Binding a new listener
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3236): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3236): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453241444952.3236","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3236): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3236): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3236): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3236): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3236): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 3236): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3236): start: OK
I/io.jxcore.node.ConnectionHelper( 3236): start: Using peer discovery mode: BLE_AND_WIFI
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453241444952.3236
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3236): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3236): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3236): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3236): createAdvertiseData: From: 1453241444952.3236 b6a44ad1-d319-4b3a-815d-8b805a47fb51 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3236): 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3236): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 52, -4, -17, 17, -82, 103]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3236): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3236): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453241444952.3236","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3236): start: {"pi":"34:FC:EF:11:AE:67","pn":"1453241444952.3236","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3236): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1453241444952.3236","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): start: Starting P2P device discovery...
,I/wpa_supplicant(  987): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): setState: RUNNING_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453241444952.3236
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): startBlePeerDiscovery: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3236): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): setState: RESTARTING
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3236): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 3236): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
,I/wpa_supplicant(  987): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): setState: RESTARTING
,I/io.jxcore.node.ConnectionHelper( 3236): start: OK
I/jxcore-log( 3236): ok 65 Should be able to call startBroadcasting without error
I/jxcore-log( 3236): 
I/jxcore-log( 3236): ok 66 Cannot call startBroadcasting twice
I/jxcore-log( 3236): 
I/io.jxcore.node.ConnectionHelper( 3236): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3236): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3236): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3236): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3236): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3236): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3236): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 3236): onConnectionManagerStateChanged: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): stop: Stopping peer discovery...
,D/BluetoothLeScanner( 3236): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3236): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3236): Local services cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): setState: NOT_INITIALIZED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3236): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3236): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3236): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 3236): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 3236): ok 67 Should be able to call stopBroadcasting without error
I/jxcore-log( 3236): 
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3236): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3236): onServerStopped
,I/jxcore-log( 3236): # setup
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): # ThaliEmitter throws on connection to bad peer
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): # teardown
I/jxcore-log( 3236): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): setDiscoveryMode: Mode set to BLE_AND_WIFI
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3236): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453241445533.3236
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3236): bind: Binding a new listener
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3236): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3236): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453241445533.3236","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3236): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3236): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3236): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3236): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3236): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 3236): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3236): start: OK
I/io.jxcore.node.ConnectionHelper( 3236): start: Using peer discovery mode: BLE_AND_WIFI
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453241445533.3236
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3236): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3236): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3236): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3236): createAdvertiseData: From: 1453241445533.3236 b6a44ad1-d319-4b3a-815d-8b805a47fb51 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3236): 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3236): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 52, -4, -17, 17, -82, 103]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3236): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3236): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453241445533.3236","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3236): start: {"pi":"34:FC:EF:11:AE:67","pn":"1453241445533.3236","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3236): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1453241445533.3236","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): start: Starting P2P device discovery...
I/wpa_supplicant(  987): p2p0: P2P: Reject scan trigger since one is already pending
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453241445533.3236
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3236): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): setState: RESTARTING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 3236): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 3236): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/wpa_supplicant(  987): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 3236): start: OK
I/jxcore-log( 3236): ok 68 Should be able to call startBroadcasting without error
I/jxcore-log( 3236): 
I/io.jxcore.node.ConnectionHelper( 3236): connect: Trying to connect to peer with ID foobar
W/io.jxcore.node.ConnectionHelper( 3236): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
E/io.jxcore.node.ConnectionHelper( 3236): connect: Invalid Bluetooth address: foobar
I/jxcore-log( 3236): ok 69 Should not connect to a bad peer
I/jxcore-log( 3236): 
I/io.jxcore.node.ConnectionHelper( 3236): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3236): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3236): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3236): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3236): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3236): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3236): onServerStopped
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3236): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3236): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 3236): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): stop: Stopping peer discovery...
,D/BluetoothLeScanner( 3236): could not find callback wrapper
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3236): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3236): Local services cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): setState: NOT_INITIALIZED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3236): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3236): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3236): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 3236): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 3236): ok 70 Should be able to call stopBroadcasting without error
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): # setup
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): # ThaliEmitter throws on disconnect to bad peer
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): # teardown
I/jxcore-log( 3236): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): setDiscoveryMode: Mode set to BLE_AND_WIFI
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3236): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453241445824.3236
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3236): bind: Binding a new listener
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3236): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3236): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453241445824.3236","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3236): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3236): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3236): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3236): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3236): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 3236): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3236): start: OK
I/io.jxcore.node.ConnectionHelper( 3236): start: Using peer discovery mode: BLE_AND_WIFI
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453241445824.3236
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3236): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3236): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3236): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3236): createAdvertiseData: From: 1453241445824.3236 b6a44ad1-d319-4b3a-815d-8b805a47fb51 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3236): 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3236): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 52, -4, -17, 17, -82, 103]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3236): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3236): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453241445824.3236","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3236): start: {"pi":"34:FC:EF:11:AE:67","pn":"1453241445824.3236","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3236): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1453241445824.3236","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): start: OK
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): setState: RUNNING_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453241445824.3236
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): startBlePeerDiscovery: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3236): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): setState: RESTARTING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3236): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 3236): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
,I/wpa_supplicant(  987): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): setState: RESTARTING
,I/io.jxcore.node.ConnectionHelper( 3236): start: OK
I/jxcore-log( 3236): ok 71 Should be able to call startBroadcasting without error
I/jxcore-log( 3236): 
D/io.jxcore.node.ConnectionHelper( 3236): disconnectOutgoingConnection: Trying to close connection to peer with ID foobar
E/io.jxcore.node.ConnectionHelper( 3236): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID foobar
D/io.jxcore.node.ConnectionHelper( 3236): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3236): disconnectOutgoingConnection: Failed to disconnect (peer ID: foobar), either no such connection or failed to close the connection
,I/jxcore-log( 3236): ok 72 Disconnect should fail to a non-existant peer 
I/jxcore-log( 3236): 
I/io.jxcore.node.ConnectionHelper( 3236): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3236): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3236): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3236): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3236): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3236): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3236): onServerStopped
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3236): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3236): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 3236): onConnectionManagerStateChanged: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): stop: Stopping peer discovery...
,D/BluetoothLeScanner( 3236): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3236): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3236): Local services cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3236): setState: NOT_INITIALIZED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3236): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3236): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3236): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3236): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 3236): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 3236): ok 73 Should be able to call stopBroadcasting without error
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): # setup
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): # #startListeningForAdvertisements should emit wifiPeerAvailabilityChanged after test peer becomes available
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): # teardown
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): ok 74 should be equal
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): # setup
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): # #startUpdateAdvertisingAndListenForIncomingConnections should use different USN after every invocation
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): # teardown
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): ok 75 should not be equal
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): # setup
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): # verify that Thali-specific messages are filtered correctly
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): # teardown
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): ok 76 irrelevant messages should be ignored
I/jxcore-log( 3236): 
I/jxcore-log( 3236): ok 77 relevant messages should not be ignored
I/jxcore-log( 3236): 
I/jxcore-log( 3236): ok 78 messages from this device should be ignored
I/jxcore-log( 3236): 
,I/jxcore-log( 3236): Tests Complete
I/jxcore-log( 3236): 
,I/chromium( 3236): [INFO:CONSOLE(63)] "logCallback ------ Final results ---- ", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3236): Total: 0	Passed: 0	Failed: 0
I/jxcore-log( 3236): 
I/jxcore-log( 3236): Toggling radios to false
I/jxcore-log( 3236): 
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  733): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@2f1d420f mBinding = false
,I/chromium( 3236): [INFO:CONSOLE(63)] "logCallback Total: 0, Passed: 0, Failed: 0", source: file:///android_asset/www/js/thali_main.js (63)
,D/BluetoothManagerService(  733): Message: 2
,D/BluetoothManagerService(  733): Sending off request.
,D/BluetoothAdapterState( 2110): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 2110): Setting state to 13
I/BluetoothAdapterState( 2110): Bluetooth adapter state changed: 12-> 13
,D/BluetoothAdapterProperties( 2110): onBluetoothDisable()
I/BluetoothAdapterState( 2110): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,D/BluetoothAdapterProperties( 2110): Scan Mode:20
,D/BluetoothAdapterState( 2110): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,V/BluetoothMapMasInstance( 2110): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 2110): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 2110): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
V/BluetoothMapMasInstance( 2110): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:489)
V/BluetoothMapMasInstance( 2110): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:399)
V/BluetoothMapMasInstance( 2110): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 2110): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 2110): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,E/BtOppRfcommListener( 2110): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,D/btif_config_util( 2110): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 2110): bta_dm_disable BTA_DISABLE_DELAY set to 100 ms
,W/bt-l2cap( 2110): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2110): L2CAP - PSM: 0x0017 not found for deregistration
,D/BluetoothManagerService(  733): Message: 60
D/BluetoothManagerService(  733): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService(  733): Bluetooth State Change Intent: 12 -> 13
,D/BluetoothMapService( 2110): onReceive
D/BluetoothMapService( 2110): STATE_TURNING_OFF
V/BluetoothMapService( 2110): Handler(): got msg=4
D/BluetoothMapService( 2110): MAP Service closeService in
D/BluetoothMapMasInstance( 2110): MAP Service shutdown
V/BluetoothMapService( 2110): MAP Service closeService out
,I/BtOppRfcommListener( 2110): stopping Accept Thread
,I/BtOppRfcommListener( 2110): BluetoothSocket listen thread finished
,W/ContextImpl( 2704): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/WifiService(  733): setWifiEnabled: false pid=3236, uid=10270
E/WifiService(  733): Invoking mWifiStateMachine.setWifiEnabled
,D/DockEventReceiver( 2704): finishStartingService: stopping service
,D/BluetoothPbap( 2704): Proxy object disconnected
D/PbapServerProfile( 2704): Bluetooth service disconnected
,D/AuthorizationBluetoothService( 1609): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/jxcore-log( 3236): Radios toggled
I/jxcore-log( 3236): 
I/jxcore-log( 3236): ****TEST TOOK:  ms ****
I/jxcore-log( 3236): 
,E/WifiStateMachine(  733): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  733): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,I/jxcore-log( 3236): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3236): 
E/native  (  733): do suspend true
,D/CommandListener(  180): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1609): Read error: ssl=0x9bfb8200: I/O error during system call, Connection timed out
,V/NativeCrypto( 1609): SSL shutdown failed: ssl=0x9bfb8200: I/O error during system call, Broken pipe
,D/ConnectivityService(  733): reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10008
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): ValidatedState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): DefaultState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/ConnectivityService(  733): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  733): NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
E/WifiConfigStore(  733): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/bt_userial( 2110): RX termination
W/bt_userial( 2110): select_read return size <=0:-1, exiting userial_read_thread
D/bt_userial( 2110): Leaving userial_read_thread()
W/bt-btif ( 2110): ag scb idx 1 not allocated
E/bt-btif ( 2110): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 2110): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2110): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2110): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2110): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2110): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2110): L2CAP - PSM: 0x0017 not found for deregistration
D/bt_userial( 2110): userial_close_reader Joined userial reader thread: 0
D/bt_hwcfg( 2110): hw_epilog_process
I/bt_userial_vendor( 2110): device fd = 53 close
,I/GKI_LINUX( 2110): gki_task task_id=0 [BTU] terminating
I/GKI_LINUX( 2110): GKI_exit_task 0 done
I/GKI_LINUX( 2110): GKI_shutdown(): task [BTU] terminated
D/BluetoothAdapterState( 2110): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,D/HeadsetService( 2110): Received stop request...Stopping profile...
,D/BluetoothAdapterService( 2110): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24e2aa45
,D/HeadsetStateMachine( 2110): Exit Disconnected: -1
,D/BluetoothHeadset( 1180): Proxy object disconnected
,D/BluetoothHeadset( 1180): Proxy object disconnected
,D/A2dpService( 2110): Received stop request...Stopping profile...
D/A2dpStateMachine( 2110): Exit Disconnected: -1
D/BluetoothHeadset(  733): Proxy object disconnected
D/BluetoothHeadset( 1227): Proxy object disconnected
,D/BluetoothAdapterService( 2110): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24e2aa45
,D/BluetoothAdapterState( 2110): Stopping profile services that were post enabled
,D/BluetoothA2dp(  733): Proxy object disconnected
,D/HidService( 2110): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2110): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24e2aa45
,D/BluetoothHeadset( 2704): Proxy object disconnected
D/HeadsetProfile( 2704): Bluetooth service disconnected
D/BluetoothA2dp( 2704): Proxy object disconnected
D/A2dpProfile( 2704): Bluetooth service disconnected
,D/HealthService( 2110): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2110): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24e2aa45
,D/BluetoothInputDevice( 2704): Proxy object disconnected
D/HidProfile( 2704): Bluetooth service disconnected
,E/WifiStateMachine(  733): scanCount==0 - aborting
,I/jxcore-log( 3236): Toggling radios to false
I/jxcore-log( 3236): 
,D/PanService( 2110): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2110): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24e2aa45
,D/WifiScanningService(  733): SCAN_AVAILABLE : 1
D/BtGatt.DebugUtils( 2110): handleDebugAction() action=null
D/BtGatt.GattService( 2110): Received stop request...Stopping profile...
D/BtGatt.GattService( 2110): stop()
D/BtGatt.AdvertiseManager( 2110): advertise clients cleared
,D/RttService(  733): SCAN_AVAILABLE : 1
D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  733): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@2f1d420f mBinding = false
D/WifiScanningService(  733): StartedState got{ when=-2ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  733): DefaultState
D/BluetoothAdapterService( 2110): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24e2aa45
D/BluetoothManagerService(  733): Message: 2
,D/BluetoothManagerService(  733): Sending off request.
,D/RttService(  733): EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
D/BluetoothAdapterState( 2110): CURRENT_STATE=PENDING, MESSAGE = USER_TURN_ON, isTurningOn=false, isTurningOff=true
I/BluetoothAdapterState( 2110): CURRENT_STATE=PENDING: Alreadying turning off bluetooth... Ignoring USER_TURN_OFF...
,D/HeadsetStateMachine( 2110): Unbinding service...
W/BluetoothHeadsetServiceJni( 2110): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 2110): Cleaning up Bluetooth Handsfree callback object
D/WifiNetworkAgent(  733): NetworkAgent: NetworkAgent channel lost
,E/native  (  733): do suspend true
,D/BluetoothMapService( 2110): Received stop request...Stopping profile...
D/BluetoothMapService( 2110): stop()
D/BluetoothPan( 2704): BluetoothPAN Proxy object disconnected
D/PanProfile( 2704): Bluetooth service disconnected
,D/BluetoothMapEmailAppObserver( 2110): deinitObservers()
D/BluetoothMapEmailAppObserver( 2110): removeReceiver()
,D/BluetoothAdapterService( 2110): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@24e2aa45
,I/GKI_LINUX( 2110): gki_task task_id=2 [A2DP-MEDIA] terminating
,I/GKI_LINUX( 2110): GKI_exit_task 2 done
I/GKI_LINUX( 2110): GKI_shutdown(): task [A2DP-MEDIA] terminated
W/BluetoothHidServiceJni( 2110): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 2110): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 2110): Cleaning up Bluetooth GID callback object
W/BluetoothHealthServiceJni( 2110): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 2110): Cleaning up Bluetooth Health object
W/BluetoothPanServiceJni( 2110): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 2110): Cleaning up Bluetooth PAN callback object
,V/BluetoothMapService( 2110): Handler(): got msg=4
,D/BluetoothMapService( 2110): MAP Service closeService in
V/BluetoothMapService( 2110): MAP Service closeService out
D/BluetoothMapService( 2110): cleanup()
D/BluetoothMapService( 2110): MAP Service closeService in
V/BluetoothMapService( 2110): MAP Service closeService out
D/BluetoothAdapterState( 2110): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 2110): Setting state to 10
I/BluetoothAdapterState( 2110): Bluetooth adapter state changed: 13-> 10
,D/BluetoothManagerService(  733): Message: 60
D/BluetoothManagerService(  733): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService(  733): Broadcasting onBluetoothStateChange(false) to 11 receivers.
I/BluetoothAdapterState( 2110): Entering OffState
D/BluetoothPbap( 2704): onBluetoothStateChange: up=false
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/ConnectivityService(  733): notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,D/BluetoothHeadset( 1180): onBluetoothStateChange: up=false
,D/BluetoothMap( 2704): Proxy object disconnected
D/MapProfile( 2704): Bluetooth service disconnected
D/CommandListener(  180): Clearing all IP addresses on wlan0
D/BluetoothA2dp( 2704): onBluetoothStateChange: up=false
D/BluetoothMap( 2704): onBluetoothStateChange: up=false
,D/WifiService(  733): setWifiEnabled: false pid=3236, uid=10270
E/WifiService(  733): Invoking mWifiStateMachine.setWifiEnabled
D/BluetoothA2dp(  733): onBluetoothStateChange: up=false
D/BluetoothHeadset(  733): onBluetoothStateChange: up=false
,I/jxcore-log( 3236): Radios toggled
I/jxcore-log( 3236): 
,D/Nat464Xlat(  733): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  733): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,D/ConnectivityService(  733): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  733): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler(  897): CM callback handler got msg 524292
D/ConnectivityService(  733): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1629): CM callback handler got msg 524292
,E/ConnectivityService(  733): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/BluetoothHeadset( 1227): onBluetoothStateChange: up=false
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): EvaluatingState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/TelephonyNetworkFactory( 1227): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): Disconnected - quitting
,D/BluetoothHeadset( 2704): onBluetoothStateChange: up=false
,D/BluetoothInputDevice( 2704): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1180): onBluetoothStateChange: up=false
,D/BluetoothManagerService(  733): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService(  733): Broadcasting onBluetoothServiceDown() to 9 receivers.
,D/BluetoothManagerService(  733): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@2f1d420f mBinding = false
,D/BluetoothManagerService(  733): Sending unbind request.
,D/BluetoothManagerService(  733): Bluetooth State Change Intent: 13 -> 10
,D/BluetoothAdapter(  897): 670108894: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter(  897): 670108894: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter(  897): 670108894: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 1609): 292568782: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1609): 292568782: getState() :  mService = null. Returning STATE_OFF
,I/GKI_LINUX( 2110): gki_task task_id=1 [BTIF] terminating
,I/GKI_LINUX( 2110): GKI_exit_task 1 done
I/GKI_LINUX( 2110): GKI_shutdown(): task [BTIF] terminated
I/BluetoothServiceJni( 2110): cleanupNative: return from cleanup
,I/art     ( 2110): System.exit called, status: 0
,I/AndroidRuntime( 2110): VM exiting with result code 0, cleanup skipped.
I/GoogleURLConnFactory( 1609): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  733): Start proc com.google.android.keep for broadcast com.google.android.keep/.notification.AlertReceiver: pid=3636 uid=10071 gids={50071, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/AndroidRuntime( 3620): 
D/AndroidRuntime( 3620): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 3620): CheckJNI is OFF
,I/wpa_supplicant(  987): p2p0: CTRL-EVENT-TERMINATING 
,I/wpa_supplicant(  987): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,I/ActivityManager(  733): Process com.android.bluetooth (pid 2110) has died
,I/PhenotypeConfigurator( 1609): Scheduling Phenotype every 14400 seconds, with flex of 1800 seconds
,D/AndroidRuntime( 3620): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  733): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  733): Killing 3236:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
,W/PackageSettings(  733): Skipping PackageSetting{12904190 com.example.hello/10278} due to missing metadata
,I/WindowState(  733): WIN DEATH: Window{345382c9 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  733): Client connection lost with reason: 4
,D/Tethering(  733): InitialState.processMessage what=4
,I/wpa_supplicant(  987): wlan0: CTRL-EVENT-TERMINATING 
,I/ActivityManager(  733):   Force finishing activity ActivityRecord{bff4da5 u0 com.test.thalitest/.MainActivity t216}
,W/ActivityManager(  733): Spurious death for ProcessRecord{1a759c1e 3236:com.test.thalitest/u0a270}, curProc for 3236: null
,I/ActivityManager(  733): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
,I/ActivityManager(  733):   Force finishing activity ActivityRecord{bff4da5 u0 com.test.thalitest/.MainActivity t216 f}
,W/ActivityManager(  733): Duplicate finish request for ActivityRecord{bff4da5 u0 com.test.thalitest/.MainActivity t216 f}
,I/art     ( 1273): Explicit concurrent mark sweep GC freed 4024(297KB) AllocSpace objects, 1(126KB) LOS objects, 23% free, 25MB/33MB, paused 485us total 32.822ms
D/Tethering(  733): sendTetherStateChangedBroadcast 0, 0, 0
,W/GeofencerStateMachine( 1609): Ignoring removeGeofence because network location is disabled.
,I/InputReader(  733): Reconfiguring input devices.  changes=0x00000010
,I/Keyboard.Facilitator( 1083): resetDictionaries() : en_US
,I/Keyboard.Facilitator.DecoderInitializer( 1083): run()
,W/Settings( 1944): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/art     ( 1350): Explicit concurrent mark sweep GC freed 12025(926KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 19MB/25MB, paused 431us total 64.953ms
,W/Settings( 1609): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/art     ( 1629): Explicit concurrent mark sweep GC freed 12678(672KB) AllocSpace objects, 3(48KB) LOS objects, 39% free, 22MB/37MB, paused 2.299ms total 75.211ms
I/Decoder ( 1083): createOrResetDecoder
,I/art     (  733): Explicit concurrent mark sweep GC freed 50220(2MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 996us total 96.326ms
,I/art     (  733): WaitForGcToComplete blocked for 45.833ms for cause Explicit
,I/Adreno-EGL(  944): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/OpenGLRenderer(  944): Initialized EGL, version 1.4
,D/OpenGLRenderer(  944): Enabling debug mode 0
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1083): run()
,W/InputMethodManagerService(  733): Focus gain on non-focused client com.android.internal.view.IInputMethodClient$Stub$Proxy@26664256 (uid=10034 pid=944)
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1083): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1083): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1083): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1083): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1083): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1083): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1083): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1083): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1083): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1083): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1083): run()
I/StatsUtilsManager( 1083): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1083): shouldRecordStats() = Too Soon
D/BackupManagerService(  733): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  733): Receieved: android.intent.action.PACKAGE_REMOVED
,D/TaskPersister(  733): removeObsoleteFile: deleting file=216_task.xml
,W/InputMethodManagerService(  733): Got RemoteException sending setActive(false) notification to pid 3236 uid 10270
I/Keyboard.Facilitator( 1083): onFinishInput()
,I/art     (  733): Explicit concurrent mark sweep GC freed 8059(467KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 1.884ms total 160.331ms
I/art     ( 1609): Explicit concurrent mark sweep GC freed 115572(6MB) AllocSpace objects, 29(464KB) LOS objects, 40% free, 23MB/39MB, paused 2.608ms total 173.682ms
I/Launcher( 1273): Deferring update until onResume
,E/DataBuffer( 1609): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@75cd5a3)
,E/DataBuffer( 1609): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@ab0d0a0)
E/DataBuffer( 1609): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2899c459)
E/DataBuffer( 1609): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1921e81e)
E/DataBuffer( 1609): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2d5d28ff)
E/DataBuffer( 1609): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@276256cc)
,W/ContextImpl( 2704): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,W/ResourcesManager( 1273): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 1273): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  733): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=3679 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,I/Launcher( 1273): Deferring update until onResume
,E/DataBuffer( 1609): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@29194d15)
E/DataBuffer( 1609): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2880682a)
,E/DataBuffer( 1609): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@18e5561b)
E/DataBuffer( 1609): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2dc413b8)
,E/DataBuffer( 1609): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@32cea591)
,D/DockEventReceiver( 2704): finishStartingService: stopping service
,I/ActivityManager(  733): Killing 2740:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,D/AndroidRuntime( 3620): Shutting down VM
,W/libprocessgroup(  733): failed to open /acct/uid_10003/pid_2740/cgroup.procs: No such file or directory
,W/PhenotypeConfigurator( 1609): IOException while sending for: 
,W/ResourcesManager( 3679): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,D/AdapterServiceConfig( 3679): Adding HeadsetService
,D/AdapterServiceConfig( 3679): Adding A2dpService
,D/AdapterServiceConfig( 3679): Adding HidService
,D/AdapterServiceConfig( 3679): Adding HealthService
D/AdapterServiceConfig( 3679): Adding PanService
D/AdapterServiceConfig( 3679): Adding GattService
D/AdapterServiceConfig( 3679): Adding BluetoothMapService
,D/BluetoothAdapter( 2704): 947611454: getState() :  mService = null. Returning STATE_OFF
,I/ActivityManager(  733): Killing 2582:com.google.android.gm/u0a70 (adj 15): empty #17
,W/libprocessgroup(  733): failed to open /acct/uid_10070/pid_2582/cgroup.procs: No such file or directory
,D/AuthorizationBluetoothService( 1609): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/VoicemailCleanupService( 1329): Cleaning up data for package: com.test.thalitest
,I/UpdateIcingCorporaServi( 1350): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,W/Launcher( 1273): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@24e2aa45 new=com.google.android.velvet.VelvetApplication@24e2aa45
,I/ActivityManager(  733): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3713 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,E/SQLiteLog( 1350): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,W/ContextImpl( 3713): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
,E/IcingCorporaProvider( 1350): Exception thrown from notifyTableChanged
E/IcingCorporaProvider( 1350): java.lang.RuntimeException: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/IcingCorporaProvider( 1350): 	at beg.a(PG:301)
E/IcingCorporaProvider( 1350): 	at beg.c(PG:222)
E/IcingCorporaProvider( 1350): 	at cun.b(PG:660)
E/IcingCorporaProvider( 1350): 	at cun.a(PG:651)
E/IcingCorporaProvider( 1350): 	at cun.g(PG:597)
E/IcingCorporaProvider( 1350): 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(PG:301)
E/IcingCorporaProvider( 1350): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:325)
E/IcingCorporaProvider( 1350): 	at android.content.ContentResolver.update(ContentResolver.java:1333)
E/IcingCorporaProvider( 1350): 	at cuw.Tg(PG:368)
E/IcingCorporaProvider( 1350): 	at cuy.ub(PG:301)
E/IcingCorporaProvider( 1350): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(PG:268)
E/IcingCorporaProvider( 1350): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(PG:186)
E/IcingCorporaProvider( 1350): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/IcingCorporaProvider( 1350): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/IcingCorporaProvider( 1350): 	at android.os.Looper.loop(Looper.java:135)
E/IcingCorporaProvider( 1350): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/IcingCorporaProvider( 1350): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/IcingCorporaProvider( 1350): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/IcingCorporaProvider( 1350): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/IcingCorporaProvider( 1350): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/IcingCorporaProvider( 1350): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/IcingCorporaProvider( 1350): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/IcingCorporaProvider( 1350): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/IcingCorporaProvider( 1350): 	at bea.a(PG:382)
E/IcingCorporaProvider( 1350): 	at beg.i(PG:325)
E/IcingCorporaProvider( 1350): 	at beh.call(PG:215)
E/IcingCorporaProvider( 1350): 	at beg.a(PG:299)
E/IcingCorporaProvider( 1350): 	... 15 more
W/IcingCorporaProvider( 1350): notifyTableChanged failed.
W/IcingCorporaProvider( 1350): Table change notification failed for TableStorageSpec[applications]
I/UpdateIcingCorporaServi( 1350): UpdateCorporaTask done [took 119 ms] updated apps [took 119 ms] 
,D/PackageBroadcastService( 1629): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1629): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 1629): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1629): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1629): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1629): Module APK com.google.android.play.games already loaded
,E/SQLiteDatabase( 3713): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 3713): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3713): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3713): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 3713): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 3713): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3713): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3713): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3713): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 3713): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 3713): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 3713): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/SQLiteDatabase( 3713): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 3713): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 3713): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 3713): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
E/SQLiteDatabase( 3713): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
E/SQLiteDatabase( 3713): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 3713): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 3713): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 3713): 	at android.os.HandlerThread.run(HandlerThread.java:61)
--------- beginning of crash
E/AndroidRuntime( 3713): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 3713): Process: com.android.keychain, PID: 3713
E/AndroidRuntime( 3713): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 3713): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 3713): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 3713): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 3713): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 3713): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 3713): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 3713): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AndroidRuntime( 3713): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AndroidRuntime( 3713): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 3713): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/AndroidRuntime( 3713): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 3713): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 3713): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 3713): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
E/AndroidRuntime( 3713): 	at com.android.keychain.KeyChainService.onHandleI,ntent(KeyChainService.java:396)
E/AndroidRuntime( 3713): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 3713): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 3713): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 3713): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteLog( 1629): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteLog( 1609): (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,D/AndroidRuntime( 1609): Shutting down VM
I/LocationSettingsChecker( 1629): Removing dialog suppression flag for package com.test.thalitest
,E/AndroidRuntime( 1629): FATAL EXCEPTION: PlayGamesAsyncThread1
E/AndroidRuntime( 1629): Process: com.google.android.gms, PID: 1629
E/AndroidRuntime( 1629): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1629): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 1629): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AndroidRuntime( 1629): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 1629): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 1629): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AndroidRuntime( 1629): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
E/AndroidRuntime( 1629): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 1629): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 1629): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 1629): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:309)
E/AndroidRuntime( 1629): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
E/AndroidRuntime( 1629): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3146)
E/AndroidRuntime( 1629): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 1629): 	at com.google.android.gms.games.service.operations.GamesOperationAdapter.execute(GamesOperationAdapter.java:23)
E/AndroidRuntime( 1629): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 1629): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 1629): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 1629): 	at java.lang.Thread.run(Thread.java:818)
I/Process ( 3713): Sending signal. PID: 3713 SIG: 9
,I/Process ( 1629): Sending signal. PID: 1629 SIG: 9
E/AndroidRuntime( 1609): FATAL EXCEPTION: main
E/AndroidRuntime( 1609): Process: com.google.android.gms.persistent, PID: 1609
E/AndroidRuntime( 1609): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1609): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2586)
E/AndroidRuntime( 1609): 	at android.app.ActivityThread.access$1700(ActivityThread.java:144)
E/AndroidRuntime( 1609): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1355)
E/AndroidRuntime( 1609): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1609): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 1609): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/AndroidRuntime( 1609): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 1609): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 1609): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/AndroidRuntime( 1609): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
E/AndroidRuntime( 1609): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1609): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1609): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 1609): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1609): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1609): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 1609): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 1609): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 1609): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 1609): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2579)
E/AndroidRuntime( 1609): 	... 9 more
,E/DropBoxManagerService(  733): Can't write: system_app_crash
E/DropBoxManagerService(  733): java.io.FileNotFoundException: /data/system/dropbox/drop98.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  733): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  733): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  733): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  733): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  733): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  733): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12006)
E/DropBoxManagerService(  733): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  733): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  733): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  733): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  733): 	... 5 more
,W/ActivityManager(  733): Process com.google.android.gms has crashed too many times: killing!
,I/ActivityManager(  733): Killing 1609:com.google.android.gms.persistent/u0a8 (adj 0): crash
,E/DropBoxManagerService(  733): Can't write: system_app_crash
E/DropBoxManagerService(  733): java.io.FileNotFoundException: /data/system/dropbox/drop100.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  733): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  733): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  733): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  733): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  733): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  733): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12006)
E/DropBoxManagerService(  733): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  733): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  733): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  733): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  733): 	... 5 more
E/DropBoxManagerService(  733): Can't write: system_app_crash
E/DropBoxManagerService(  733): java.io.FileNotFoundException: /data/system/dropbox/drop99.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  733): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  733): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  733): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  733): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  733): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  733): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12006)
E/DropBoxManagerService(  733): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  733): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  733): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  733): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  733): 	... 5 more
,D/ConnectivityService(  733): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@34238ca2)
,D/ConnectivityService(  733): releasing NetworkRequest NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/ConnectivityService(  733): RemoteException caught trying to send a callback msg for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/GpsStatusListenerHelper(  733): Remote Listener died: android.location.IGpsStatusListener$Stub$Proxy@2f486d33
,V/BackupManagerService(  733): Disconnected from transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  733): Registering transport com.google.android.gms/.backup.BackupTransportService::null = null

```
