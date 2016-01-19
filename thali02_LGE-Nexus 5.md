#### Test 5644966031ce140_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
D/Finsky  ( 2620): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,--------- beginning of system
W/ResourcesManager( 3215): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3215): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/JNIHelp ( 3215): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/ActivityManager(  734): Killing 2065:com.google.android.deskclock/u0a38 (adj 15): empty #17
W/System  ( 3215): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3215): Installed default security provider GmsCore_OpenSSL
W/libprocessgroup(  734): failed to open /acct/uid_10038/pid_2065/cgroup.procs: No such file or directory
V/GLSActivity( 1598): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/AndroidRuntime( 3265): 
D/AndroidRuntime( 3265): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3265): CheckJNI is OFF
D/AndroidRuntime( 3265): Calling main entry com.android.commands.am.Am
I/ActivityManager(  734): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  734): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3289 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3265): Shutting down VM
I/Icing   ( 1581): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
V/ActivityManager(  734): Display changed displayId=0
I/Icing   ( 1581): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/Icing   ( 1581): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/WebViewFactory( 3289): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/Icing   ( 1581): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
I/LibraryLoader( 3289): Time to load native libraries: 1 ms (timestamps 7008-7009)
I/LibraryLoader( 3289): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3289): Binding Chromium to main looper Looper (main, tid 1) {2ffba203}
I/LibraryLoader( 3289): Expected native library version number "",actual native library version number ""
I/chromium( 3289): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3289): Initializing chromium process, singleProcess=true
W/art     ( 3289): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3289): ApplicationContext is null in ApplicationStatus
,W/chromium( 3289): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3289): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3289): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3289): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  734): Message: 20
D/BluetoothManagerService(  734): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3b58bc1d:true
,W/art     ( 3289): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3289): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3289): CordovaWebView is running on device made by: LGE
,W/art     ( 3289): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3289): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3289): Render dirty regions requested: true
,D/Atlas   ( 3289): Validating map...
,W/chromium( 3289): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3289): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3289): Enabling debug mode 0
,I/Keyboard.Facilitator( 1051): onFinishInput()
,W/BindingManager( 3289): Cannot call determinedVisibility() - never saw a connection for the pid: 3289
,W/IInputConnectionWrapper( 3289): showStatusIcon on inactive InputConnection
,I/ActivityManager(  734): Displayed com.test.thalitest/.MainActivity: +478ms (total +55s318ms)
,I/ActivityManager(  734): Killing 2521:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,W/libprocessgroup(  734): failed to open /acct/uid_10045/pid_2521/cgroup.procs: No such file or directory
,D/JsMessageQueue( 3289): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3289): JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1258381056
I/chromium( 3289): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 3289): Initializing JXcore engine
W/jxcore-log( 3289): JXcore engine is ready
,W/Thread-306( 3351): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[6390]" dev="sockfs" ino=6390 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-306( 3351): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
,W/Thread-306( 3351): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[9565]" dev="sockfs" ino=9565 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/Thread-306( 3351): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[20556]" dev="sockfs" ino=20556 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3289): Starting JXcore engine
,W/jxcore-log( 3289): Platform android
W/jxcore-log( 3289): 
W/jxcore-log( 3289): Process ARCH arm
W/jxcore-log( 3289): 
,I/jxcore-log( 3289): JXcore Cordova bridge is ready!
I/jxcore-log( 3289): 
W/jxcore-log( 3289): JXcore engine is started
,I/jxcore-log( 3289): Toggling radios to true
I/jxcore-log( 3289): 
,D/BluetoothAdapter( 3289): enable(): BT is already enabled..!
,D/WifiService(  734): New client listening to asynchronous messages
,D/WifiService(  734): setWifiEnabled: true pid=3289, uid=10270
E/WifiService(  734): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3289): Radios toggled
I/jxcore-log( 3289): 
I/jxcore-log( 3289): My device name is: LGE-Nexus 5
I/jxcore-log( 3289): 
,I/wpa_supplicant( 1000): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  734): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  734): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
E/native  (  734): do suspend true
D/CommandListener(  181): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1598): Read error: ssl=0xb3a2ee00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1598): SSL shutdown failed: ssl=0xb3a2ee00: I/O error during system call, Broken pipe
,D/ConnectivityService(  734): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): ValidatedState{ when=-1ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): DefaultState{ when=-1ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): Checking http://clients3.google.com/generate_204 on "NG7005g"
,E/WifiConfigStore(  734): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  734): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  734): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,E/WifiStateMachine(  734): Start Disconnecting Watchdog 1
,I/wpa_supplicant( 1000): wlan0: CTRL-EVENT-SCAN-STARTED 
,E/native  (  734): do suspend true
,D/CommandListener(  181): Clearing all IP addresses on wlan0
,D/ConnectivityService(  734): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler(  900): CM callback handler got msg 524292
,D/Nat464Xlat(  734): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/CSLegacyTypeTracker(  734): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): Disconnected - quitting
D/ConnectivityService(  734): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  734): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1581): CM callback handler got msg 524292
,D/ConnectivityService(  734): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1207): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WifiNetworkAgent(  734): NetworkAgent: NetworkAgent channel lost
,I/wpa_supplicant( 1000): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant( 1000): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1000): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1000): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  734): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService(  734): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiConfigStore(  734): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
E/WifiConfigStore(  734): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  181): Setting iface cfg
,E/WifiStateMachine(  734): Start Dhcp Watchdog 2
,E/native  (  734): do suspend false
,E/WifiStateMachine(  734): scanCount==0 - aborting
,I/dhcpcd  ( 3388): version 5.5.6 starting
E/dhcpcd  ( 3388): get_duid: Read-only file system
,I/dhcpcd  ( 3388): wlan0: rebinding lease of 192.168.1.114
,I/dhcpcd  ( 3388): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3388): wlan0: leased 192.168.1.114 for 86400 seconds
,E/native  (  734): do suspend true
,D/ConnectivityService(  734): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  734): Adding iface wlan0 to network 101
,E/WifiStateMachine(  734): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  734): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  734): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  734): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  734): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  734): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  734): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  734): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  734): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  734): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  734):    accepting network in place of null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): Checking http://clients3.google.com/generate_204 on "NG7005g"
D/CSLegacyTypeTracker(  734): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  734): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  734): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  734): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler(  900): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1581): CM callback handler got msg 524290
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 19 Jan 2016 12:02:49 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1453204969470], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1453204969452]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): Validated
,D/ConnectivityService(  734): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  734): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  734): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  734): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  734): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/TelephonyNetworkFactory( 1207): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler(  900): CM callback handler got msg 524290
D/ConnectivityManager.CallbackHandler( 1581): CM callback handler got msg 524290
,V/GLSActivity( 1598): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1598): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  734): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering(  734): MasterInitialState.processMessage what=3
D/ConnectivityService(  734): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  734): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2750): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2750): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 2750): type=WIFI subType= reason=null isConnected=true
,I/SystemUpdateService( 1581): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1581): onCreate
,D/SystemUpdateService( 1581): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1581): active receiver: enabled
,I/SystemUpdateService( 1581): showing system update notification
,I/ActivityManager(  734): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3447 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/GpsLocationProvider(  734): No APN found to select.
,E/GpsLocationProvider(  734): No APN found to select.
,I/ValidateNoPeople(  734): skipping global notification
,V/SystemUpdateService( 1581): retry (wakeup: false) in 3599939 ms
,D/SystemUpdateService( 1581): onDestroy
,D/Nat464Xlat(  734): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  734): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  900): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 1581): CM callback handler got msg 524295
,I/GAv4    ( 3447): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3447):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3447):   adb logcat -s GAv4
,W/GAv4    ( 3447): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3447): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3447): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/ConnectivityService(  734): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/WebViewFactory( 3447): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3447): Time to load native libraries: 2 ms (timestamps 3267-3269)
,I/LibraryLoader( 3447): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3447): Binding Chromium to main looper Looper (main, tid 1) {2e1cde7d}
,I/LibraryLoader( 3447): Expected native library version number "",actual native library version number ""
,I/chromium( 3447): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3447): Initializing chromium process, singleProcess=true
W/art     ( 3447): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3447): ApplicationContext is null in ApplicationStatus
,W/chromium( 3447): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3447): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3447): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3447): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/AudioManagerAndroid( 3447): Requires BLUETOOTH permission
,I/NSApplication( 3447): Starting up...
,I/ActivityManager(  734): Killing 2723:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/libprocessgroup(  734): failed to open /acct/uid_10003/pid_2723/cgroup.procs: No such file or directory
,I/jxcore-log( 3289): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3289): 
,V/MusicLeanback( 2750): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1581): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1581): onCreate
,D/SystemUpdateService( 1581): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1581): active receiver: enabled
,I/SystemUpdateService( 1581): showing system update notification
,I/ValidateNoPeople(  734): skipping global notification
,V/SystemUpdateService( 1581): retry (wakeup: false) in 3599970 ms
,D/SystemUpdateService( 1581): onDestroy
,I/jxcore-log( 3289): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 3289): 
,I/jxcore-log( 3289): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 3289): 
,I/jxcore-log( 3289): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 3289): 
,I/jxcore-log( 3289): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 3289): 
,I/jxcore-log( 3289): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 3289): 
,I/jxcore-log( 3289): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3289): 
,D/ConnectivityService(  734): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  734): MasterInitialState.processMessage what=3
I/NetworkMonitor( 2750): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2750): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/SystemUpdateService( 1581): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
D/SystemUpdateService( 1581): onCreate
D/SystemUpdateService( 1581): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1581): active receiver: enabled
,I/SystemUpdateService( 1581): showing system update notification
,I/ValidateNoPeople(  734): skipping global notification
V/SystemUpdateService( 1581): retry (wakeup: false) in 3599949 ms
,I/art     (  734): Explicit concurrent mark sweep GC freed 45163(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 27MB/41MB, paused 1.056ms total 58.275ms
,D/SystemUpdateService( 1581): onDestroy
,E/GpsLocationProvider(  734): No APN found to select.
,I/jxcore-log( 3289): Test app app.js loaded
I/jxcore-log( 3289): 
,I/chromium( 3289): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3289): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 3289): BLE advertisement is supported
I/jxcore-log( 3289): 
,D/Finsky  ( 2620): [255] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2620): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/GLSActivity( 1598): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1598): Vacuum at: now=1453204985386 tag=VacuumService
,I/PhenotypeConfigurator( 1598): Scheduling Phenotype for one-off execution 9381 seconds from now (1453204985736)
,D/GetConfigurationSnapshotOperation( 1598): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1598): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1598): Using platform SSLCertificateSocketFactory
,I/Keyboard.Facilitator.LanguageModelFlusher( 1051): run()
I/Keyboard.Facilitator( 1051): flushDynamicLanguageModels()
,I/ConfigService( 1598): onCreate
,I/ConfigService( 1598): onDestroy
,I/ClearcutLoggerApiImpl( 1598): disconnect managed GoogleApiClient
,I/jxcore-log( 3289): --= Surplus to requirements =--
I/jxcore-log( 3289): 
I/jxcore-log( 3289): ****TEST TOOK:  ms ****
I/jxcore-log( 3289): 
I/jxcore-log( 3289): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3289): 
,D/AndroidRuntime( 3608): 
D/AndroidRuntime( 3608): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 3608): CheckJNI is OFF
,D/AndroidRuntime( 3608): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  734): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  734): Killing 3289:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
,I/WindowState(  734): WIN DEATH: Window{645e68d u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  734): Client connection lost with reason: 4
,W/PackageSettings(  734): Skipping PackageSetting{d02b267 com.example.hello/10278} due to missing metadata
,I/ActivityManager(  734):   Force finishing activity ActivityRecord{108f812e u0 com.test.thalitest/.MainActivity t216}
,W/ActivityManager(  734): Spurious death for ProcessRecord{266c3662 3289:com.test.thalitest/u0a270}, curProc for 3289: null
I/ActivityManager(  734): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
I/ActivityManager(  734):   Force finishing activity ActivityRecord{108f812e u0 com.test.thalitest/.MainActivity t216 f}
W/ActivityManager(  734): Duplicate finish request for ActivityRecord{108f812e u0 com.test.thalitest/.MainActivity t216 f}
,I/InputReader(  734): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1598): Ignoring removeGeofence because network location is disabled.
,I/Keyboard.Facilitator( 1051): resetDictionaries() : en_US
,I/art     ( 1261): Explicit concurrent mark sweep GC freed 3990(295KB) AllocSpace objects, 1(126KB) LOS objects, 38% free, 25MB/41MB, paused 224us total 39.541ms
,I/Keyboard.Facilitator.DecoderInitializer( 1051): run()
,I/Decoder ( 1051): createOrResetDecoder
,I/art     ( 1326): Explicit concurrent mark sweep GC freed 15369(1075KB) AllocSpace objects, 1(39KB) LOS objects, 25% free, 19MB/25MB, paused 39.980ms total 91.451ms
,D/VoicemailCleanupService( 2891): Cleaning up data for package: com.test.thalitest
,I/art     (  734): Explicit concurrent mark sweep GC freed 21389(1192KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 1.981ms total 93.020ms
,I/art     ( 1581): Explicit concurrent mark sweep GC freed 12015(572KB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 22MB/30MB, paused 472us total 113.653ms
,I/Adreno-EGL(  954): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
I/OpenGLRenderer(  954): Initialized EGL, version 1.4
,I/ConfigService( 1598): onCreate
,I/UpdateIcingCorporaServi( 1326): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,D/OpenGLRenderer(  954): Enabling debug mode 0
,W/Launcher( 1261): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@2ad31580 new=com.google.android.velvet.VelvetApplication@2ad31580
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1051): run()
,I/ActivityManager(  734): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3650 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,D/BackupManagerService(  734): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  734): Receieved: android.intent.action.PACKAGE_REMOVED
I/art     (  734): Explicit concurrent mark sweep GC freed 3228(168KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 27MB/41MB, paused 1.548ms total 96.622ms
,D/TaskPersister(  734): removeObsoleteFile: deleting file=216_task.xml
,W/InputMethodManagerService(  734): Got RemoteException sending setActive(false) notification to pid 3289 uid 10270
,I/Keyboard.Facilitator( 1051): onFinishInput()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1051): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1051): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1051): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1051): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1051): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1051): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1051): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1051): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1051): run() : Loaded (exit)
,I/Keyboard.Facilitator.Delight2FileSweeper( 1051): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1051): run()
I/StatsUtilsManager( 1051): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1051): shouldRecordStats() = Too Soon
,W/ContextImpl( 3650): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
,I/UpdateIcingCorporaServi( 1326): UpdateCorporaTask done [took 158 ms] updated apps [took 157 ms] 
,D/PackageBroadcastService( 1581): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1581): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 1581): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1581): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1581): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1581): Module APK com.google.android.play.games already loaded
,I/Keyboard.Facilitator( 1051): onFinishInput()
,E/NetworkScheduler.SchedulerReceiver( 1598): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1598): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/LocationSettingsChecker( 1581): Removing dialog suppression flag for package com.test.thalitest
W/IInputConnectionWrapper( 1261): showStatusIcon on inactive InputConnection
,D/gH_CompatibleDatabase( 1581): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1581): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 1581): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1581): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/AndroidRuntime( 3608): Shutting down VM
,D/gH_CompatibleDatabase( 1581): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1581): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1581): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/gH_CompatibleDatabase( 1581): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1581): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 1581): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1581): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1581): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1581): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/ActivityManager(  734): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3682 uid=10039 gids={50039, 9997} abi=armeabi-v7a
,I/Launcher( 1261): Deferring update until onResume
,W/BaseAppContext( 1581): Using Auth Proxy for data requests.
,W/ResourcesManager( 1261): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/BaseAppContext( 1581): Using Auth Proxy for data requests.
,I/ActivityManager(  734): Killing 2692:com.android.settings/1000 (adj 15): empty #17
,I/GMPM-SVC( 1581): App measurement is starting up, version: 8489
I/GMPM-SVC( 1581): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,D/WifiService(  734): Client connection lost with reason: 4
,W/ResourcesManager( 1261): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Launcher( 1261): Deferring update until onResume
,W/libprocessgroup(  734): failed to open /acct/uid_1000/pid_2692/cgroup.procs: No such file or directory
,I/Icing   ( 1581): doRemovePackageData com.test.thalitest
,I/ActivityManager(  734): Killing 2553:com.google.android.gm/u0a70 (adj 15): empty #17
,W/libprocessgroup(  734): failed to open /acct/uid_10070/pid_2553/cgroup.procs: No such file or directory
,I/ActivityManager(  734): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3710 uid=10007 gids={50007, 9997, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  734): Killing 1997:com.google.android.calendar/u0a31 (adj 15): empty #17
,W/libprocessgroup(  734): failed to open /acct/uid_10031/pid_1997/cgroup.procs: No such file or directory
,D/ExternalStorage( 3710): After updating volumes, found 1 active roots
,W/ResourcesManager( 3215): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3215): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/Documents( 3682): Update found 7 roots in 275ms
,D/Documents( 3682): Update found 7 roots in 60ms

```
