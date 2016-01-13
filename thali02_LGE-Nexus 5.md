#### Test 558973767bac5c9_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
I/GAv4    ( 3319): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3319):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3319):   adb logcat -s GAv4
,W/GAv4    ( 3319): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
D/ChimeraCfgMgr( 1593): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1593): Module APK com.google.android.play.games already loaded
W/GAv4    ( 3319): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3319): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 3319): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
D/Finsky  ( 2734): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
W/ResourcesManager( 3319): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3319): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  762): Killing 2646:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
D/AndroidRuntime( 3373): 
D/AndroidRuntime( 3373): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
V/JNIHelp ( 3319): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/AndroidRuntime( 3373): CheckJNI is OFF
W/System  ( 3319): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3319): Installed default security provider GmsCore_OpenSSL
D/AndroidRuntime( 3373): Calling main entry com.android.commands.am.Am
W/libprocessgroup(  762): failed to open /acct/uid_10045/pid_2646/cgroup.procs: No such file or directory
V/GLSActivity( 1570): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  762): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  762): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3399 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3373): Shutting down VM
I/Icing   ( 1593): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
,V/ActivityManager(  762): Display changed displayId=0
I/WebViewFactory( 3399): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3399): Time to load native libraries: 1 ms (timestamps 9041-9042)
I/LibraryLoader( 3399): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3399): Binding Chromium to main looper Looper (main, tid 1) {290b1b16}
I/LibraryLoader( 3399): Expected native library version number "",actual native library version number ""
I/chromium( 3399): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/Icing   ( 1593): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1593): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/BrowserStartupController( 3399): Initializing chromium process, singleProcess=true
W/art     ( 3399): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3399): ApplicationContext is null in ApplicationStatus
W/chromium( 3399): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3399): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3399): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3399): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
I/Icing   ( 1593): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
D/BluetoothManagerService(  762): Message: 20
D/BluetoothManagerService(  762): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ed5bb5c:true
W/art     ( 3399): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 3399): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 3399): CordovaWebView is running on device made by: LGE
W/art     ( 3399): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3399): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 3399): Render dirty regions requested: true
D/Atlas   ( 3399): Validating map...
W/chromium( 3399): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/OpenGLRenderer( 3399): Initialized EGL, version 1.4
D/OpenGLRenderer( 3399): Enabling debug mode 0
I/Keyboard.Facilitator( 1083): onFinishInput()
W/BindingManager( 3399): Cannot call determinedVisibility() - never saw a connection for the pid: 3399
W/IInputConnectionWrapper( 3399): showStatusIcon on inactive InputConnection
I/ActivityManager(  762): Displayed com.test.thalitest/.MainActivity: +436ms (total +57s339ms)
D/JsMessageQueue( 3399): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 3399): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1405519232
I/chromium( 3399): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
I/ActivityManager(  762): Killing 2810:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
W/libprocessgroup(  762): failed to open /acct/uid_10003/pid_2810/cgroup.procs: No such file or directory
,W/jxcore-log( 3399): Initializing JXcore engine
W/jxcore-log( 3399): JXcore engine is ready
,W/Thread-326( 3481): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[10290]" dev="sockfs" ino=10290 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-326( 3481): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-326( 3481): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[10352]" dev="sockfs" ino=10352 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-326( 3481): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[17297]" dev="sockfs" ino=17297 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3399): Starting JXcore engine
,W/jxcore-log( 3399): Platform android
W/jxcore-log( 3399): 
,W/jxcore-log( 3399): Process ARCH arm
W/jxcore-log( 3399): 
,I/jxcore-log( 3399): JXcore Cordova bridge is ready!
I/jxcore-log( 3399): 
,W/jxcore-log( 3399): JXcore engine is started
,I/jxcore-log( 3399): Toggling radios to true
I/jxcore-log( 3399): 
,D/BluetoothAdapter( 3399): enable(): BT is already enabled..!
,D/WifiService(  762): New client listening to asynchronous messages
,D/WifiService(  762): setWifiEnabled: true pid=3399, uid=10270
E/WifiService(  762): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3399): Radios toggled
I/jxcore-log( 3399): 
,I/jxcore-log( 3399): My device name is: LGE-Nexus 5
I/jxcore-log( 3399): 
,I/wpa_supplicant(  982): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  762): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  762): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/native  (  762): do suspend true
,D/CommandListener(  180): Clearing all IP addresses on wlan0
V/NativeCrypto( 1570): Read error: ssl=0xb3d30e00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1570): SSL shutdown failed: ssl=0xb3d30e00: I/O error during system call, Broken pipe
,D/ConnectivityService(  762): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): ValidatedState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): DefaultState{ when=-1ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/ConnectivityService(  762): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  762): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,E/WifiConfigStore(  762): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiStateMachine(  762): Start Disconnecting Watchdog 1
,I/wpa_supplicant(  982): wlan0: CTRL-EVENT-SCAN-STARTED 
E/native  (  762): do suspend true
,D/CommandListener(  180): Clearing all IP addresses on wlan0
,D/ConnectivityService(  762): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityManager.CallbackHandler(  901): CM callback handler got msg 524292
D/ConnectivityManager.CallbackHandler( 1593): CM callback handler got msg 524292
,D/Nat464Xlat(  762): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/CSLegacyTypeTracker(  762): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): Disconnected - quitting
D/ConnectivityService(  762): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  762): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  762): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1227): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/ConnectivityService(  762): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,D/WifiNetworkAgent(  762): NetworkAgent: NetworkAgent channel lost
,I/wpa_supplicant(  982): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant(  982): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant(  982): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant(  982): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  762): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  762): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  762): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  762): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  180): Setting iface cfg
E/WifiStateMachine(  762): Start Dhcp Watchdog 2
,E/native  (  762): do suspend false
,E/WifiStateMachine(  762): scanCount==0 - aborting
,I/dhcpcd  ( 3531): version 5.5.6 starting
E/dhcpcd  ( 3531): get_duid: Read-only file system
,I/dhcpcd  ( 3531): wlan0: rebinding lease of 192.168.1.114
,I/dhcpcd  ( 3531): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3531): wlan0: leased 192.168.1.114 for 86400 seconds
,D/ConnectivityService(  762): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  762): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  762): MasterInitialState.processMessage what=3
D/Tethering(  762): MasterInitialState.processMessage what=3
,V/MusicLeanback( 2830): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1593): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1593): onCreate
,D/SystemUpdateService( 1593): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1593): active receiver: enabled
,I/SystemUpdateService( 1593): showing system update notification
,I/iu.Environment( 1593): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
I/iu.UploadsManager( 1593): num queued entries: 0
I/iu.UploadsManager( 1593): num updated entries: 0
I/iu.SyncManager( 1593): NEXT; no task
,E/GpsLocationProvider(  762): No APN found to select.
,I/ValidateNoPeople(  762): skipping global notification
,V/SystemUpdateService( 1593): retry (wakeup: false) in 3599972 ms
,I/ActivityManager(  762): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3565 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/GpsLocationProvider(  762): No APN found to select.
,I/Babel   ( 2601): connection state changed from UNKNOWN to DISCONNECTED
,D/SystemUpdateService( 1593): onDestroy
,I/GAv4    ( 3565): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3565):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3565):   adb logcat -s GAv4
,W/GAv4    ( 3565): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3565): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3565): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,E/native  (  762): do suspend true
,E/WifiStateMachine(  762): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/ConnectivityService(  762): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  762): Adding iface wlan0 to network 101
,E/ConnectivityService(  762): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  762): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  762): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  762): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  762): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  762): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  762): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  762): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  762): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  762):    accepting network in place of null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): Connected
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): Checking http://clients3.google.com/generate_204 on "NG7005g"
D/CSLegacyTypeTracker(  762): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,D/ConnectivityService(  762): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  762): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.114/24,fe80::5255:27ff:fef0:fd0b/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService(  762): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  901): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1593): CM callback handler got msg 524290
,I/WebViewFactory( 3565): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 13 Jan 2016 13:52:26 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452693146833], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452693146809]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): Validated
D/ConnectivityService(  762): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  762): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  762): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
,D/ConnectivityService(  762): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler(  901): CM callback handler got msg 524290
,D/ConnectivityService(  762): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/TelephonyNetworkFactory( 1227): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1593): CM callback handler got msg 524290
,I/LibraryLoader( 3565): Time to load native libraries: 2 ms (timestamps 5046-5048)
I/LibraryLoader( 3565): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3565): Binding Chromium to main looper Looper (main, tid 1) {38310b0a}
,I/LibraryLoader( 3565): Expected native library version number "",actual native library version number ""
,I/chromium( 3565): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3565): Initializing chromium process, singleProcess=true
W/art     ( 3565): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3565): ApplicationContext is null in ApplicationStatus
,W/chromium( 3565): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3565): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3565): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3565): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/AudioManagerAndroid( 3565): Requires BLUETOOTH permission
,I/NSApplication( 3565): Starting up...
,I/ActivityManager(  762): Killing 2791:com.android.settings/1000 (adj 15): empty #17
,D/WifiService(  762): Client connection lost with reason: 4
,W/libprocessgroup(  762): failed to open /acct/uid_1000/pid_2791/cgroup.procs: No such file or directory
,V/MusicLeanback( 2830): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1593): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1593): onCreate
,D/SystemUpdateService( 1593): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1593): active receiver: enabled
,I/SystemUpdateService( 1593): showing system update notification
,I/iu.Environment( 1593): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1593): num queued entries: 0
I/iu.UploadsManager( 1593): num updated entries: 0
,I/iu.SyncManager( 1593): NEXT; no task
,I/ValidateNoPeople(  762): skipping global notification
,V/SystemUpdateService( 1593): retry (wakeup: false) in 3599951 ms
,D/SystemUpdateService( 1593): onDestroy
,I/Babel   ( 2601): connection state changed from DISCONNECTED to CONNECTED
,D/ConnectivityService(  762): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,D/ConnectivityService(  762): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  762): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2830): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2830): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1593): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1593): onCreate
,D/SystemUpdateService( 1593): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1593): active receiver: enabled
,I/SystemUpdateService( 1593): showing system update notification
,I/art     (  762): Explicit concurrent mark sweep GC freed 44975(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 27MB/41MB, paused 1.433ms total 61.069ms
,I/ValidateNoPeople(  762): skipping global notification
,E/GpsLocationProvider(  762): No APN found to select.
,V/SystemUpdateService( 1593): retry (wakeup: false) in 3599981 ms
,D/SystemUpdateService( 1593): onDestroy
,I/jxcore-log( 3399): Test app app.js loaded
I/jxcore-log( 3399): 
,I/chromium( 3399): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/Finsky  ( 2734): [270] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2734): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/GLSActivity( 1570): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1570): Vacuum at: now=1452693159986 tag=VacuumService
,I/PhenotypeConfigurator( 1570): Scheduling Phenotype for one-off execution 11886 seconds from now (1452693160328)
,D/GetConfigurationSnapshotOperation( 1570): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1570): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1570): Using platform SSLCertificateSocketFactory
,V/GLSActivity( 1570): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1570): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Keyboard.Facilitator.LanguageModelFlusher( 1083): run()
I/Keyboard.Facilitator( 1083): flushDynamicLanguageModels()
,I/ConfigService( 1570): onCreate
,I/ConfigService( 1570): onDestroy
,I/ClearcutLoggerApiImpl( 1570): disconnect managed GoogleApiClient
,I/jxcore-log( 3399): --= Surplus to requirements =--
I/jxcore-log( 3399): 
I/jxcore-log( 3399): ****TEST TOOK:  ms ****
I/jxcore-log( 3399): 
I/jxcore-log( 3399): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3399): 
,D/AndroidRuntime( 3755): 
D/AndroidRuntime( 3755): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 3755): CheckJNI is OFF
,D/AndroidRuntime( 3755): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  762): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  762): Killing 3399:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
,I/WindowState(  762): WIN DEATH: Window{3c2cb38c u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  762): Client connection lost with reason: 4
,W/PackageSettings(  762): Skipping PackageSetting{1e5d204a com.example.hello/10278} due to missing metadata
,I/ActivityManager(  762):   Force finishing activity ActivityRecord{1e303471 u0 com.test.thalitest/.MainActivity t216}
,W/ActivityManager(  762): Spurious death for ProcessRecord{cf5ae5f 3399:com.test.thalitest/u0a270}, curProc for 3399: null
,I/ActivityManager(  762): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
,I/art     ( 1284): Explicit concurrent mark sweep GC freed 3994(295KB) AllocSpace objects, 1(126KB) LOS objects, 38% free, 25MB/41MB, paused 578us total 16.663ms
,I/InputReader(  762): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 1570): Ignoring removeGeofence because network location is disabled.
,I/art     ( 1593): Explicit concurrent mark sweep GC freed 25381(1567KB) AllocSpace objects, 5(80KB) LOS objects, 24% free, 22MB/30MB, paused 457us total 53.092ms
,I/Keyboard.Facilitator( 1083): resetDictionaries() : en_US
,I/art     (  762): Explicit concurrent mark sweep GC freed 23843(1312KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 1.035ms total 84.352ms
I/art     (  762): WaitForGcToComplete blocked for 28.552ms for cause Explicit
,D/VoicemailCleanupService( 2999): Cleaning up data for package: com.test.thalitest
,I/Keyboard.Facilitator.DecoderInitializer( 1083): run()
,I/Decoder ( 1083): createOrResetDecoder
,I/Adreno-EGL(  950): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/OpenGLRenderer(  950): Initialized EGL, version 1.4
,I/art     ( 1366): Explicit concurrent mark sweep GC freed 11935(898KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 19MB/25MB, paused 2.943ms total 122.202ms
,D/OpenGLRenderer(  950): Enabling debug mode 0
,I/ConfigService( 1570): onCreate
,W/Launcher( 1284): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@24ff6c97 new=com.google.android.velvet.VelvetApplication@24ff6c97
I/UpdateIcingCorporaServi( 1366): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/ActivityManager(  762): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3797 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,D/BackupManagerService(  762): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  762): Receieved: android.intent.action.PACKAGE_REMOVED
,D/TaskPersister(  762): removeObsoleteFile: deleting file=216_task.xml
,W/InputMethodManagerService(  762): Got RemoteException sending setActive(false) notification to pid 3399 uid 10270
,I/Keyboard.Facilitator( 1083): onFinishInput()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1083): run()
,W/ContextImpl( 3797): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
,I/art     (  762): Explicit concurrent mark sweep GC freed 6259(338KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 2.578ms total 158.417ms
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1083): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1083): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1083): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1083): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1083): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1083): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1083): run() : Loading LM = user
,D/PackageBroadcastService( 1593): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1593): Clearing selected account for com.test.thalitest
,I/UpdateIcingCorporaServi( 1366): UpdateCorporaTask done [took 129 ms] updated apps [took 129 ms] 
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1083): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1083): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1083): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1083): run()
I/StatsUtilsManager( 1083): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1083): shouldRecordStats() = Too Soon
,D/ChimeraCfgMgr( 1593): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1593): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1593): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1593): Module APK com.google.android.play.games already loaded
,E/NetworkScheduler.SchedulerReceiver( 1570): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1570): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/Keyboard.Facilitator( 1083): onFinishInput()
,W/IInputConnectionWrapper( 1284): showStatusIcon on inactive InputConnection
,I/LocationSettingsChecker( 1593): Removing dialog suppression flag for package com.test.thalitest
,D/gH_CompatibleDatabase( 1593): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1593): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1593): 0 metrics were deleted when clearing package com.test.thalitest.
,D/gH_CompatibleDatabase( 1593): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/gH_CompatibleDatabase( 1593): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1593): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1593): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/gH_CompatibleDatabase( 1593): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1593): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 1593): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,D/gH_CompatibleDatabase( 1593): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1593): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
,D/gH_CompatibleDatabase( 1593): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/ActivityManager(  762): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3827 uid=10039 gids={50039, 9997} abi=armeabi-v7a
,I/Launcher( 1284): Deferring update until onResume
,W/BaseAppContext( 1593): Using Auth Proxy for data requests.
,W/BaseAppContext( 1593): Using Auth Proxy for data requests.
,I/ActivityManager(  762): Killing 2218:com.google.android.apps.genie.geniewidget/u0a73 (adj 15): empty #17
,W/ResourcesManager( 1284): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/AndroidRuntime( 3755): Shutting down VM
,W/ResourcesManager( 1284): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Launcher( 1284): Deferring update until onResume
,W/libprocessgroup(  762): failed to open /acct/uid_10073/pid_2218/cgroup.procs: No such file or directory
,I/GMPM-SVC( 1593): App measurement is starting up, version: 8489
I/GMPM-SVC( 1593): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,I/Icing   ( 1593): doRemovePackageData com.test.thalitest
,I/ActivityManager(  762): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3852 uid=10007 gids={50007, 9997, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  762): Killing 2665:com.google.android.gm/u0a70 (adj 15): empty #17
,W/libprocessgroup(  762): failed to open /acct/uid_10070/pid_2665/cgroup.procs: No such file or directory
,I/ActivityManager(  762): Killing 2003:com.google.android.calendar/u0a31 (adj 15): empty #17
,D/ExternalStorage( 3852): After updating volumes, found 1 active roots
,W/libprocessgroup(  762): failed to open /acct/uid_10031/pid_2003/cgroup.procs: No such file or directory
,W/ResourcesManager( 3319): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3319): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.

```
