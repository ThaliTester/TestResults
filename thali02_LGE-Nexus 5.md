#### Test 50650278ee43ca0_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
I/GAv4    ( 3229): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3229):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3229):   adb logcat -s GAv4
W/GAv4    ( 3229): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3229): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3229): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/AnalyticsTrackerProxyImpl( 3229): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
D/Finsky  ( 2595): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
W/ResourcesManager( 3229): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3229): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  735): Killing 2565:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
D/AndroidRuntime( 3272): 
D/AndroidRuntime( 3272): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3272): CheckJNI is OFF
V/JNIHelp ( 3229): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/System  ( 3229): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3229): Installed default security provider GmsCore_OpenSSL
W/libprocessgroup(  735): failed to open /acct/uid_10069/pid_2565/cgroup.procs: No such file or directory
V/GLSActivity( 1576): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/AndroidRuntime( 3272): Calling main entry com.android.commands.am.Am
I/ActivityManager(  735): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  735): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3311 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3272): Shutting down VM
V/ActivityManager(  735): Display changed displayId=0
I/Icing   ( 1633): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/Icing   ( 1633): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1633): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/WebViewFactory( 3311): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3311): Time to load native libraries: 1 ms (timestamps 8026-8027)
I/LibraryLoader( 3311): Expected native library version number "",actual native library version number ""
I/Icing   ( 1633): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
V/WebViewChromiumFactoryProvider( 3311): Binding Chromium to main looper Looper (main, tid 1) {149357bf}
I/LibraryLoader( 3311): Expected native library version number "",actual native library version number ""
I/chromium( 3311): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3311): Initializing chromium process, singleProcess=true
W/art     ( 3311): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3311): ApplicationContext is null in ApplicationStatus
W/chromium( 3311): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3311): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3311): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3311): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
D/BluetoothManagerService(  735): Message: 20
D/BluetoothManagerService(  735): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@39b4291e:true
W/art     ( 3311): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 3311): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 3311): CordovaWebView is running on device made by: LGE
W/art     ( 3311): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3311): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 3311): Render dirty regions requested: true
D/Atlas   ( 3311): Validating map...
W/chromium( 3311): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/OpenGLRenderer( 3311): Initialized EGL, version 1.4
D/OpenGLRenderer( 3311): Enabling debug mode 0
W/BindingManager( 3311): Cannot call determinedVisibility() - never saw a connection for the pid: 3311
W/IInputConnectionWrapper( 3311): showStatusIcon on inactive InputConnection
I/ActivityManager(  735): Displayed com.test.thalitest/.MainActivity: +443ms (total +56s7ms)
D/JsMessageQueue( 3311): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 3311): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257332480
D/JX-Cordova( 3311): jxcore cordova android initializing
,I/ActivityManager(  735): Killing 2494:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,W/libprocessgroup(  735): failed to open /acct/uid_10045/pid_2494/cgroup.procs: No such file or directory
,W/jxcore-log( 3311): Initializing JXcore engine
W/jxcore-log( 3311): JXcore engine is ready
,W/jxcore-log( 3311): Starting JXcore engine
,W/.test.thalitest( 3311): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[8378]" dev="sockfs" ino=8378 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3311): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 3311): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6487]" dev="sockfs" ino=6487 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3311): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[19762]" dev="sockfs" ino=19762 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3311): Platform android
W/jxcore-log( 3311): 
W/jxcore-log( 3311): Process ARCH arm
W/jxcore-log( 3311): 
,I/jxcore-log( 3311): JXcore Cordova bridge is ready!
I/jxcore-log( 3311): 
,W/jxcore-log( 3311): JXcore engine is started
,I/chromium( 3311): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3311): Toggling radios to true
I/jxcore-log( 3311): 
,D/BluetoothAdapter( 3311): enable(): BT is already enabled..!
,D/WifiService(  735): New client listening to asynchronous messages
,D/WifiService(  735): setWifiEnabled: true pid=3311, uid=10270
E/WifiService(  735): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3311): Radios toggled
I/jxcore-log( 3311): 
,D/BluetoothManagerService(  735): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 3311): Got Device Bluetooth address: 34:FC:EF:11:AE:67
I/jxcore-log( 3311): 
I/jxcore-log( 3311): Perf Test app loaded loaded
I/jxcore-log( 3311): 
I/jxcore-log( 3311): check test folder
I/jxcore-log( 3311): 
I/jxcore-log( 3311): found test : ./testFindPeers.js
I/jxcore-log( 3311): 
,I/wpa_supplicant( 1026): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  735): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  735): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
E/native  (  735): do suspend true
,D/CommandListener(  178): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1576): Read error: ssl=0xaf278e00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1576): SSL shutdown failed: ssl=0xaf278e00: I/O error during system call, Broken pipe
D/ConnectivityService(  735): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): ValidatedState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): DefaultState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,E/WifiConfigStore(  735): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  735): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  735): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,I/jxcore-log( 3311): found test : ./testSendData.js
I/jxcore-log( 3311): 
,E/WifiStateMachine(  735): Start Disconnecting Watchdog 1
,I/wpa_supplicant( 1026): wlan0: CTRL-EVENT-SCAN-STARTED 
,E/native  (  735): do suspend true
,D/CommandListener(  178): Clearing all IP addresses on wlan0
,D/ConnectivityService(  735): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/Nat464Xlat(  735): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/ConnectivityManager.CallbackHandler(  902): CM callback handler got msg 524292
D/CSLegacyTypeTracker(  735): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityManager.CallbackHandler( 1633): CM callback handler got msg 524292
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Disconnected - quitting
D/ConnectivityService(  735): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  735): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  735): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1256): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WifiNetworkAgent(  735): NetworkAgent: NetworkAgent channel lost
,I/chromium( 3311): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/ActivityManager(  735): Killing 2689:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/libprocessgroup(  735): failed to open /acct/uid_10003/pid_2689/cgroup.procs: No such file or directory
,I/wpa_supplicant( 1026): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,V/GLSActivity( 1576): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1576): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/wpa_supplicant( 1026): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1026): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1026): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,W/NetworkUtils( 1362): OkHttp exception
W/EventLoggerService( 1362): Unable to send logs Error code: 262146
,D/ConnectivityService(  735): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  735): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  735): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiConfigStore(  735): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/CommandListener(  178): Setting iface cfg
E/WifiStateMachine(  735): Start Dhcp Watchdog 2
,E/native  (  735): do suspend false
,E/WifiStateMachine(  735): scanCount==0 - aborting
,I/dhcpcd  ( 3414): version 5.5.6 starting
E/dhcpcd  ( 3414): get_duid: Read-only file system
,I/dhcpcd  ( 3414): wlan0: rebinding lease of 192.168.1.114
,I/dhcpcd  ( 3414): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3414): wlan0: leased 192.168.1.114 for 86400 seconds
,E/native  (  735): do suspend true
,D/ConnectivityService(  735): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  735): Adding iface wlan0 to network 101
,E/ConnectivityService(  735): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  735): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  735): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/ConnectivityService(  735): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  735): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  735): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  735): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  735): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/ConnectivityService(  735): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  735):    accepting network in place of null
,D/CSLegacyTypeTracker(  735): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  735): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  735): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  735): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  902): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1633): CM callback handler got msg 524290
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 15 Dec 2015 04:02:31 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450152151755], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450152151740]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Validated
,D/ConnectivityService(  735): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  735): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  735): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  735): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler(  902): CM callback handler got msg 524290
D/ConnectivityService(  735): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/TelephonyNetworkFactory( 1256): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 1633): CM callback handler got msg 524290
,D/ConnectivityService(  735): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  735): MasterInitialState.processMessage what=3
,D/AlarmManagerService(  735): Setting time of day to sec=1450152151
,W/AlarmManagerService(  735): Unable to set rtc to 1450152151: Invalid argument
,D/ConnectivityService(  735): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Nat464Xlat(  735): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  735): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/Tethering(  735): MasterInitialState.processMessage what=3
,D/ConnectivityManager.CallbackHandler(  902): CM callback handler got msg 524295
,I/NetworkMonitor( 2709): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2709): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/ConnectivityManager.CallbackHandler( 1633): CM callback handler got msg 524295
,I/NetworkMonitor( 2709): type=WIFI subType= reason=null isConnected=true
,E/GpsLocationProvider(  735): No APN found to select.
,E/GpsLocationProvider(  735): No APN found to select.
,I/SystemUpdateService( 1633): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1633): onCreate
,D/SystemUpdateService( 1633): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1633): active receiver: enabled
,I/SystemUpdateService( 1633): showing system update notification
,I/ValidateNoPeople(  735): skipping global notification
,V/SystemUpdateService( 1633): retry (wakeup: false) in 3599988 ms
,I/ActivityManager(  735): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3504 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/SystemUpdateService( 1633): onDestroy
,I/GAv4    ( 3504): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3504):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3504):   adb logcat -s GAv4
,W/GAv4    ( 3504): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3504): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3504): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/ConnectivityService(  735): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/WebViewFactory( 3504): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3504): Time to load native libraries: 1 ms (timestamps 5141-5142)
I/LibraryLoader( 3504): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3504): Binding Chromium to main looper Looper (main, tid 1) {1b2a12d9}
,I/LibraryLoader( 3504): Expected native library version number "",actual native library version number ""
I/chromium( 3504): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3504): Initializing chromium process, singleProcess=true
,W/art     ( 3504): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3504): ApplicationContext is null in ApplicationStatus
,W/chromium( 3504): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3504): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3504): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3504): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/AudioManagerAndroid( 3504): Requires BLUETOOTH permission
,I/NSApplication( 3504): Starting up...
,V/MusicLeanback( 2709): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1633): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1633): onCreate
,D/SystemUpdateService( 1633): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1633): active receiver: enabled
,I/SystemUpdateService( 1633): showing system update notification
,I/ValidateNoPeople(  735): skipping global notification
,V/SystemUpdateService( 1633): retry (wakeup: false) in 3599986 ms
,D/SystemUpdateService( 1633): onDestroy
,I/ActivityManager(  735): Start proc com.google.android.keep for broadcast com.google.android.keep/.notification.AlertReceiver: pid=3574 uid=10071 gids={50071, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  735): Killing 2671:com.android.settings/1000 (adj 15): empty #17
,D/WifiService(  735): Client connection lost with reason: 4
,W/libprocessgroup(  735): failed to open /acct/uid_1000/pid_2671/cgroup.procs: No such file or directory
,I/art     (  735): Explicit concurrent mark sweep GC freed 43534(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 27MB/41MB, paused 1.083ms total 85.563ms
,I/ActivityManager(  735): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=3600 uid=10076 gids={50076, 9997} abi=armeabi-v7a
,D/TimeService( 3600): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1450152152718
,D/        ( 3600): TimeServiceNative: User Time to be set is 1450152152718
D/QC-time-services( 3600): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 3600): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 3600): Lib:time_genoff_operation: pargs->ts_val = 1450152152718
D/QC-time-services( 3600): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  199): Daemon: Connection accepted:time_genoff
D/QC-time-services(  199): Daemon:Received base = 2, unit = 1, operation = 0,value = 1450152152718
D/QC-time-services(  199): Daemon:genoff_opr: Base = 2, val = 1450152152718, operation = 0
D/QC-time-services(  199): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS3/18/70 9:53:14
D/QC-time-services(  199): Daemon:Value read from RTC seconds = 9280394000
D/QC-time-services(  199): Daemon:new time 1450152152718 
D/QC-time-services(  199): Daemon: delta 1440871758718 genoff 1440871758718 
D/QC-time-services(  199): Daemon:genoff_persistent_update: Writing genoff = 1440871758718 to memory
D/QC-time-services(  199): Daemon:Opening File: /data/system/time/ats_2
D/QC-time-services(  199): Daemon:time_persistent_memory_opr:Genoff write operation 
I/ActivityManager(  735): Killing 2537:com.google.android.gm/u0a70 (adj 15): empty #17
,D/QC-time-services(  199): Updating the TOD offset
D/QC-time-services(  199): Daemon:genoff_persistent_update: Writing genoff = 1440871758718 to memory
D/QC-time-services(  199): Daemon:Opening File: /data/system/time/ats_1
D/QC-time-services(  199): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  199): Daemon:Update to modem bit set
D/QC-time-services(  199): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  199): Daemon: Base = 2, Value being sent to MODEM = 1134187352718
,E/QC-time-services( 3600): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,D/QC-time-services(  199): Daemon: Time-services: Waiting to acceptconnection
,D/QC-time-services(  199): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,W/libprocessgroup(  735): failed to open /acct/uid_10070/pid_2537/cgroup.procs: No such file or directory
,I/CheckinService( 1633): Checkin interval check for package: unspecified last checkin: 1450144805532 min interval config: 0 actual interval: 7347214
,I/ActivityManager(  735): Killing 2781:com.android.providers.calendar/u0a2 (adj 15): empty #17
,W/libprocessgroup(  735): failed to open /acct/uid_10002/pid_2781/cgroup.procs: No such file or directory
,I/ActivityManager(  735): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver: pid=3620 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,I/GAv4    ( 3620): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3620):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3620):   adb logcat -s GAv4
,W/GAv4    ( 3620): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3620): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3620): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  735): Killing 3047:com.google.android.gms:car/u0a8 (adj 15): empty #17
,I/ActivityManager(  735): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=3642 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/libprocessgroup(  735): failed to open /acct/uid_10008/pid_3047/cgroup.procs: No such file or directory
,I/ActivityManager(  735): Killing 2873:android.process.acore/u0a4 (adj 15): empty #17
,W/libprocessgroup(  735): failed to open /acct/uid_10004/pid_2873/cgroup.procs: No such file or directory,
,W/ResourcesManager( 3642): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/CalendarProvider2( 3642): Created com.android.providers.calendar.CalendarAlarmManager@172c99de(com.android.providers.calendar.CalendarProvider2@149357bf)
,I/jxcore-log( 3311): BLE advertisement not supported: MultipleAdvertisement not supported
I/jxcore-log( 3311): 
,D/ConnectivityService(  735): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  735): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2709): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2709): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,E/GpsLocationProvider(  735): No APN found to select.
,I/SystemUpdateService( 1633): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1633): onCreate
,D/SystemUpdateService( 1633): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1633): active receiver: enabled
,I/SystemUpdateService( 1633): showing system update notification
,I/ValidateNoPeople(  735): skipping global notification
,V/SystemUpdateService( 1633): retry (wakeup: false) in 3599982 ms
,D/SystemUpdateService( 1633): onDestroy
,I/CalendarProvider2( 3642): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 3642): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,E/SQLiteLog( 3642): (284) automatic index on view_events(_id)
,D/Finsky  ( 2595): [251] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2595): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/GLSActivity( 1576): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1576): Vacuum at: now=1450152165039 tag=VacuumService
,I/PhenotypeConfigurator( 1576): Scheduling Phenotype for one-off execution 9597 seconds from now (1450152165378)
,D/GetConfigurationSnapshotOperation( 1576): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1576): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1576): Using platform SSLCertificateSocketFactory
,V/GLSActivity( 1576): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1576): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ClearcutLoggerApiImpl( 1576): disconnect managed GoogleApiClient
,I/jxcore-log( 3311): Connected to the server!
I/jxcore-log( 3311): 
,I/chromium( 3311): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3311): --- start :testFindPeers.js---
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): testFindPeers created [object Object]
I/jxcore-log( 3311): 
I/jxcore-log( 3311): serverPort is 8876
I/jxcore-log( 3311): 
,D/BluetoothManagerService(  735): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): stop: Stopping Bluetooth and peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): initialize: 34:FC:EF:11:AE:67 LGE-Nexus 5_PT5145
,D/BluetoothManagerService(  735): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3311): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): initialize: Bluetooth and Wi-Fi OK
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): setState: INITIALIZED
,D/BluetoothManagerService(  735): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5145","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3311): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  735): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3311): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5145","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3311): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5145","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onIsDiscoveryStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): startWifiPeerDiscovery: Started
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3311): start: OK
I/jxcore-log( 3311): StartBroadcasting started ok
I/jxcore-log( 3311): 
I/chromium( 3311): [INFO:CONSOLE(63)] "logCallback --- start :testFindPeers.js---", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi peer discovery...
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): startWifiPeerDiscovery: Already started
,I/io.jxcore.node.ConnectionHelper( 3311): onConnectionManagerStateChanged: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3311): Local service added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Peer discovery started successfully
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
I/io.jxcore.node.ConnectionHelper( 3311): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3311): Waiting for incoming connections...
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1026): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 3311): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service request added successfully
D/WifiP2pManager( 3311): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service request added successfully
D/WifiP2pManager( 3311): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service request added successfully
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 3: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 3311): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service request added successfully
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: Got empty list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1026): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1026): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): stopServiceDiscovery
,I/wpa_supplicant( 1026): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:ff:f0
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Peer discovery stopped successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): start: Starting peer discovery...
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1026): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 3: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 3: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 3: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 3: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3311): Ignored { when=-4ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service request added successfully
D/WifiP2pManager( 3311): Ignored { when=-3ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service request added successfully
D/WifiP2pManager( 3311): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service request added successfully
D/WifiP2pManager( 3311): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service request added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 5 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 3: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 4: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3311): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service request added successfully
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1026): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 8 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 3: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 4: Thali Test's G2 36:fc:ef:de:0a:e2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 6: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 8: S5mini-1 02:f4:6f:30:e0:6d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 8 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 3: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 4: Thali Test's G2 36:fc:ef:de:0a:e2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 6: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 8: S5mini-1 02:f4:6f:30:e0:6d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 8 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 3: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 4: Thali Test's G2 36:fc:ef:de:0a:e2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 6: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 8: S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 3311): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service request added successfully
D/WifiP2pManager( 3311): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service request added successfully
D/WifiP2pManager( 3311): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service request added successfully
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1026): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1026): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1026): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1026): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1026): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT349"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Resolved peer properties: [34:FC:EF:9D:93:0B LGE-LG-D802_PT349 34:FC:EF:9D:93:0B]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerDiscovered,
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
I/io.jxcore.node.ConnectionHelper( 3311): onPeerDiscovered: Bluetooth address: 34:FC:EF:9D:93:0B, peer name: LGE-LG-D802_PT349, peer ID: 34:FC:EF:9D:93:0B, Wi-Fi Direct device name: Thali Test's G2, Wi-Fi Direct address: 36:fc:ef:de:0a:e2
I/io.jxcore.node.ConnectionHelper( 3311): addNewPeerToListAndNotify: Adding peer with ID 34:FC:EF:9D:93:0B
I/jxcore-log( 3311): peerAvailabilityChanged [{"peerIdentifier":"34:FC:EF:9D:93:0B","peerName":"LGE-LG-D802_PT349","peerAvailable":true}]
I/jxcore-log( 3311): 
I/jxcore-log( 3311): Found peer : 34:FC:EF:9D:93:0B, peerAvailable: true
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): weAreDoneNow
I/jxcore-log( 3311): 
I/jxcore-log( 3311): done, now sending data to server
I/jxcore-log( 3311): 
,W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT349"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT349"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT349"}", service type: "Cordovap2p._tcp.local."
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT349"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT349"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT349"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT349"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5051","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT5051 7C:F9:0E:34:8A:A0]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: 2 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
I/io.jxcore.node.ConnectionHelper( 3311): onPeerDiscovered: Bluetooth address: 7C:F9:0E:34:8A:A0, peer name: samsung-SM-G900F_PT5051, peer ID: 7C:F9:0E:34:8A:A0, Wi-Fi Direct device name: S5-1, Wi-Fi Direct address: ee:1f:72:63:11:86
I/io.jxcore.node.ConnectionHelper( 3311): addNewPeerToListAndNotify: Adding peer with ID 7C:F9:0E:34:8A:A0
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list containing 2 peer(s), but doing nothing with that list
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5051","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5051","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5051","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5051","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5051","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5051","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5051","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT6503","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT6503 F8:95:C7:87:85:54]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: 3 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT6503","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT6503","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT6503","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT6503","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3311): onPeerDiscovered: Bluetooth address: F8:95:C7:87:85:54, peer name: LGE-LG-D722_PT6503, peer ID: F8:95:C7:87:85:54, Wi-Fi Direct device name: G3s-1, Wi-Fi Direct address: a2:39:f7:70:12:80
I/io.jxcore.node.ConnectionHelper( 3311): addNewPeerToListAndNotify: Adding peer with ID F8:95:C7:87:85:54
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list containing 3 peer(s), but doing nothing with that list
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT6503","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT6503","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT6503","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1026): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: Got empty list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT1299"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Resolved peer properties: [34:FC:EF:11:B1:66 LGE-Nexus 5_PT1299 34:FC:EF:11:B1:66]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
I/io.jxcore.node.ConnectionHelper( 3311): onPeerDiscovered: Bluetooth address: 34:FC:EF:11:B1:66, peer name: LGE-Nexus 5_PT1299, peer ID: 34:FC:EF:11:B1:66, Wi-Fi Direct device name: Android_2dc2, Wi-Fi Direct address: 52:55:27:f0:ff:f0
I/io.jxcore.node.ConnectionHelper( 3311): addNewPeerToListAndNotify: Adding peer with ID 34:FC:EF:11:B1:66
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT1299"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT1299"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT1299"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT1299"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT1299"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT1299"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT1299"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1026): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 1026): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT349"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Resolved peer properties: [34:FC:EF:9D:93:0B LGE-LG-D802_PT349 34:FC:EF:9D:93:0B]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: 2 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT349"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT349"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT349"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT349"}", service type: "Cordovap2p._tcp.local."
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT349"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT349"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT349"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3311): onPeerDiscovered: Bluetooth address: 34:FC:EF:9D:93:0B, peer name: LGE-LG-D802_PT349, peer ID: 34:FC:EF:9D:93:0B, Wi-Fi Direct device name: Thali Test's G2, Wi-Fi Direct address: 36:fc:ef:de:0a:e2
,I/io.jxcore.node.ConnectionHelper( 3311): addNewPeerToListAndNotify: Peer with ID 34:FC:EF:9D:93:0B already in the list
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list containing 2 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT9986"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Resolved peer properties: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT9986 00:F4:6F:30:E0:6C]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: 3 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT9986"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT9986"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT9986"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT9986"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT9986"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT9986"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT9986"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3311): onPeerDiscovered: Bluetooth address: 00:F4:6F:30:E0:6C, peer name: samsung-SM-G800F_PT9986, peer ID: 00:F4:6F:30:E0:6C, Wi-Fi Direct device name: S5mini-1, Wi-Fi Direct address: 02:f4:6f:30:e0:6d
I/io.jxcore.node.ConnectionHelper( 3311): addNewPeerToListAndNotify: Adding peer with ID 00:F4:6F:30:E0:6C
,W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list containing 3 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2765"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Resolved peer properties: [B4:CE:F6:AB:A4:6A HTC-HTC Desire 820_PT2765 B4:CE:F6:AB:A4:6A]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: 4 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2765"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2765"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2765"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2765"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2765"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2765"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2765"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/io.jxcore.node.ConnectionHelper( 3311): onPeerDiscovered: Bluetooth address: B4:CE:F6:AB:A4:6A, peer name: HTC-HTC Desire 820_PT2765, peer ID: B4:CE:F6:AB:A4:6A, Wi-Fi Direct device name: Android_1950, Wi-Fi Direct address: b6:ce:f6:ad:a4:6b
I/io.jxcore.node.ConnectionHelper( 3311): addNewPeerToListAndNotify: Adding peer with ID B4:CE:F6:AB:A4:6A,
,W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list containing 4 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT4197","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4197 F8:95:C7:87:3C:51]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: 5 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT4197","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT4197","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT4197","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT4197","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT4197","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT4197","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT4197","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/io.jxcore.node.ConnectionHelper( 3311): onPeerDiscovered: Bluetooth address: F8:95:C7:87:3C:51, peer name: LGE-LG-H815_PT4197, peer ID: F8:95:C7:87:3C:51, Wi-Fi Direct device name: G4-1, Wi-Fi Direct address: a2:39:f7:6f:c9:5d
I/io.jxcore.node.ConnectionHelper( 3311): addNewPeerToListAndNotify: Adding peer with ID F8:95:C7:87:3C:51
,W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list containing 5 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6932","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6932 08:EC:A9:50:76:27]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: 6 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6932","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6932","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6932","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6932","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6932","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6932","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6932","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3311): onPeerDiscovered: Bluetooth address: 08:EC:A9:50:76:27, peer name: samsung-SM-A300FU_PT6932, peer ID: 08:EC:A9:50:76:27, Wi-Fi Direct device name: Thali Test (Galaxy A3), Wi-Fi Direct address: 0a:ec:a9:50:76:28
I/io.jxcore.node.ConnectionHelper( 3311): addNewPeerToListAndNotify: Adding peer with ID 08:EC:A9:50:76:27
,W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list containing 6 peer(s), but doing nothing with that list
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2p_dev_addr=3a:94:96:b5:06:dd pri_dev_type=10-0050F204-5 name='Galaxy S5-2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT1658"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Resolved peer properties: [38:94:96:B5:06:DC samsung-SM-G800H_PT1658 38:94:96:B5:06:DC]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceDiscovered
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerDiscovered,
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: 7 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT1658"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT1658"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT1658"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT1658"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT1658"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT1658"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT1658"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3311): onPeerDiscovered: Bluetooth address: 38:94:96:B5:06:DC, peer name: samsung-SM-G800H_PT1658, peer ID: 38:94:96:B5:06:DC, Wi-Fi Direct device name: Galaxy S5-2, Wi-Fi Direct address: 3a:94:96:b5:06:dd
I/io.jxcore.node.ConnectionHelper( 3311): addNewPeerToListAndNotify: Adding peer with ID 38:94:96:B5:06:DC
,W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list containing 7 peer(s), but doing nothing with that list
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT1658","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Resolved peer properties: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT1658 F8:CF:C5:D9:E5:61]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: 8 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT1658","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT1658","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT1658","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT1658","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT1658","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT1658","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT1658","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3311): onPeerDiscovered: Bluetooth address: F8:CF:C5:D9:E5:61, peer name: motorola-Nexus 6_PT1658, peer ID: F8:CF:C5:D9:E5:61, Wi-Fi Direct device name: , Wi-Fi Direct address: fa:cf:c5:d9:e5:62
I/io.jxcore.node.ConnectionHelper( 3311): addNewPeerToListAndNotify: Adding peer with ID F8:CF:C5:D9:E5:61
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list containing 8 peer(s), but doing nothing with that list
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT5619","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5619 08:EC:A9:50:75:41]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerDiscovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: 9 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT5619","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT5619","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT5619","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT5619","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT5619","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT5619","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT5619","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3311): onPeerDiscovered: Bluetooth address: 08:EC:A9:50:75:41, peer name: samsung-SM-A300FU_PT5619, peer ID: 08:EC:A9:50:75:41, Wi-Fi Direct device name: A3-1, Wi-Fi Direct address: 0a:ec:a9:50:75:42
I/io.jxcore.node.ConnectionHelper( 3311): addNewPeerToListAndNotify: Adding peer with ID 08:EC:A9:50:75:41
,W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list containing 9 peer(s), but doing nothing with that list
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT3010","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT3010 58:3F:54:73:64:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: 10 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT3010","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT3010","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT3010","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT3010","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT3010","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT3010","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT3010","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3311): onPeerDiscovered: Bluetooth address: 58:3F:54:73:64:C0, peer name: LGE-LG-D855_PT3010, peer ID: 58:3F:54:73:64:C0, Wi-Fi Direct device name: , Wi-Fi Direct address: 02:9a:02:7b:60:ac
I/io.jxcore.node.ConnectionHelper( 3311): addNewPeerToListAndNotify: Adding peer with ID 58:3F:54:73:64:C0
,W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list containing 10 peer(s), but doing nothing with that list
,I/jxcore-log( 3311): --- start :testFindPeers.js---
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): testFindPeers created [object Object]
I/jxcore-log( 3311): 
I/jxcore-log( 3311): serverPort is 8876
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): weAreDoneNow
I/jxcore-log( 3311): 
I/jxcore-log( 3311): done, now sending data to server
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): done, now sending data to server
I/jxcore-log( 3311): 
,I/chromium( 3311): [INFO:CONSOLE(63)] "logCallback --- start :testFindPeers.js---", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3311): teardown
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): testFindPeers stopped
I/jxcore-log( 3311): 
I/io.jxcore.node.ConnectionHelper( 3311): stop
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3311): Shutting down...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3311): shutdown
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3311): Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3311): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3311): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3311): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:489)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3311): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:399)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3311): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3311): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3311): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread.run(BluetoothServerThread.java:89)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3311): onIncomingConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3311): Socket is null
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3311): onIncomingConnectionFailed: Socket is null
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3311): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3311): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): stopServiceDiscovery
,I/wpa_supplicant( 1026): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=3a:94:96:b5:06:dd
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:ff:f0
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): setState: NOT_INITIALIZED
I/jxcore-log( 3311): StopBroadcasting went ok
I/jxcore-log( 3311): 
,I/chromium( 3311): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onConnectionFailed: Socket is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3311): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Peer discovery stopped successfully
I/io.jxcore.node.ConnectionHelper( 3311): onConnectionManagerStateChanged: INITIALIZED
I/io.jxcore.node.ConnectionHelper( 3311): onConnectionManagerStateChanged: NOT_INITIALIZED
,I/jxcore-log( 3311): --- start :testSendData.js---
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): testSendData created {"serverTimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":22}bt-address length : 0
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): daya100000
I/jxcore-log( 3311): 
I/jxcore-log( 3311): check server
I/jxcore-log( 3311): 
I/jxcore-log( 3311): serverPort is 38884
I/jxcore-log( 3311): 
,D/BluetoothManagerService(  735): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): stop: Stopping Bluetooth and peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): initialize: 34:FC:EF:11:AE:67 LGE-Nexus 5_PT5145
,D/BluetoothManagerService(  735): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3311): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): initialize: Bluetooth and Wi-Fi OK
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): setState: INITIALIZED
,D/BluetoothManagerService(  735): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5145","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3311): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  735): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3311): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5145","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3311): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5145","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onIsDiscoveryStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): startWifiPeerDiscovery: Started
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): setState: RUNNING
I/jxcore-log( 3311): peerAvailabilityChanged [{"peerIdentifier":"34:FC:EF:9D:93:0B","peerName":"LGE-LG-D802_PT349","peerAvailable":true},{"peerIdentifier":"7C:F9:0E:34:8A:A0","peerName":"samsung-SM-G900F_PT5051","peerAvailable":true},{"peerIdentifier":"F8:95:C7:87:85:54","peerName":"LGE-LG-D722_PT6503","peerAvailable":true},{"peerIdentifier":"34:FC:EF:11:B1:66","peerName":"LGE-Nexus 5_PT1299","peerAvailable":true},{"peerIdentifier":"00:F4:6F:30:E0:6C","peerName":"samsung-SM-G800F_PT9986","peerAvailable":true},{"peerIdentifier":"B4:CE:F6:AB:A4:6A","peerName":"HTC-HTC Desire 820_PT2765","peerAvailable":true},{"peerIdentifier":"F8:95:C7:87:3C:51","peerName":"LGE-LG-H815_PT4197","peerAvailable":true},{"peerIdentifier":"08:EC:A9:50:76:27","peerName":"samsung-SM-A300FU_PT6932","peerAvailable":true},{"peerIdentifier":"38:94:96:B5:06:DC","peerName":"samsung-SM-G800H_PT1658","peerAvailable":true},{"peerIdentifier":"F8:CF:C5:D9:E5:61","peerName":"motorola-Nexus 6_PT1658","peerAvailable":true},{"peerIdentifier":"08:EC:A9:50:75:41","peerNam
I/jxcore-log( 3311): Found peer : LGE-LG-D802_PT349, Available: true
I/jxcore-log( 3311): 
I/jxcore-log( 3311): Found peer : samsung-SM-G900F_PT5051, Available: true
I/jxcore-log( 3311): 
I/jxcore-log( 3311): Found peer : LGE-LG-D722_PT6503, Available: true
I/jxcore-log( 3311): 
I/jxcore-log( 3311): Found peer : LGE-Nexus 5_PT1299, Available: true
I/jxcore-log( 3311): 
I/jxcore-log( 3311): Found peer : samsung-SM-G800F_PT9986, Available: true
I/jxcore-log( 3311): 
I/jxcore-log( 3311): Found peer : HTC-HTC Desire 820_PT2765, Available: true
I/jxcore-log( 3311): 
I/jxcore-log( 3311): Found peer : LGE-LG-H815_PT4197, Available: true
I/jxcore-log( 3311): 
I/jxcore-log( 3311): Found peer : samsung-SM-A300FU_PT6932, Available: true
I/jxcore-log( 3311): 
I/jxcore-log( 3311): Found peer : samsung-SM-G800H_PT1658, Available: true
I/jxcore-log( 3311): 
I/jxcore-log( 3311): Found peer : motorola-Nexus 6_PT1658, Available: true
I/jxcore-log( 3311): 
I/jxcore-log( 3311): Found peer : samsung-SM-A300FU_PT5619, Available: true
I/jxcore-log( 3311): 
I/jxcore-log( 3311): Found peer : LGE-LG-D855_PT3010, Available: true
I/jxcore-log( 3311): 
I/jxcore-log( 3311): startWithNextDevice
I/jxcore-log( 3311): 
I/jxcore-log( 3311): device[1]: 34:FC:EF:9D:93:0B
I/jxcore-log( 3311): 
I/jxcore-log( 3311): 2015-12-15T04:07:51.653Z SendDataConnector.js: Start called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:07:51.653Z SendDataConnector.js: doConnect called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3311): 
I/jxcore-log( 3311): 2015-12-15T04:07:51.655Z SendDataConnector.js: do connect now
I/jxcore-log( 3311): 
,I/io.jxcore.node.ConnectionHelper( 3311): connect: Trying to connect to peer with ID 34:FC:EF:9D:93:0B
D/io.jxcore.node.ConnectionHelper( 3311): hasConnection: No connection with peer with ID 34:FC:EF:9D:93:0B
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): connect: Thali Test's G2
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3311): connect: Trying to start connecting to null in address 34:FC:EF:9D:93:0B
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onConnecting: null 34:FC:EF:9D:93:0B
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3311): connect: Started connecting to null in address 34:FC:EF:9D:93:0B
I/io.jxcore.node.ConnectionHelper( 3311): connect: Connection process successfully started (peer ID: 34:FC:EF:9D:93:0B)
I/io.jxcore.node.ConnectionHelper( 3311): start: OK
I/jxcore-log( 3311): StartBroadcasting started ok
I/jxcore-log( 3311): 
I/jxcore-log( 3311): null
I/jxcore-log( 3311): 
I/jxcore-log( 3311): 2015-12-15T04:07:51.660Z SendDataTCPServer.js: TCP/IP server is bound to port: 38884
I/jxcore-log( 3311): 
I/chromium( 3311): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3311): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3311): Trying to connect to peer with address 34:FC:EF:9D:93:0B (thread ID: 304)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3311): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3311): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onWifiStateChanged: State changed to 2
,D/BTIF_SOCK( 1975): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi peer discovery...
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): startWifiPeerDiscovery: Already started
I/io.jxcore.node.ConnectionHelper( 3311): onConnectionManagerStateChanged: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3311): Local service added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): restart: Restarting...
,I/wpa_supplicant( 1026): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
I/io.jxcore.node.ConnectionHelper( 3311): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Peer discovery stopped successfully
,W/bt-btif ( 1975): info:x10
,D/        ( 1975): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
,E/BluetoothRemoteDevices( 1975): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 1975): bondStateChangeCallback: Status: 0 Address: E0:DB:10:1F:C9:5E newState: 1
E/bt-btif ( 1975): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 1975): Bond State Change Intent:E0:DB:10:1F:C9:5E OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 1975): Entering PendingCommandState State
,I/ActivityManager(  735): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.BluetoothPairingRequest: pid=3782 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/BluetoothBondStateMachine( 1975): bondStateChangeCallback: Status: 0 Address: E0:DB:10:1F:C9:5E newState: 0
,D/BluetoothAdapterProperties( 1975): Failed to remove device: E0:DB:10:1F:C9:5E
,I/BluetoothBondStateMachine( 1975): Bond State Change Intent:E0:DB:10:1F:C9:5E OldState: 11 NewState: 10
,D/BluetoothManagerService(  735): Message: 20
D/BluetoothManagerService(  735): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@38945626:true
,I/ActivityManager(  735): Killing 1507:com.google.android.partnersetup/u0a13 (adj 15): empty #17
,W/libprocessgroup(  735): failed to open /acct/uid_10013/pid_1507/cgroup.procs: No such file or directory
,I/BluetoothBondStateMachine( 1975): StableState(): Entering Off State
,W/bt-btif ( 1975): info:x10
D/        ( 1975): remote version info [34:fc:ef:9d:93:0b]: 6, f, 4106
,E/BluetoothRemoteDevices( 1975): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 1975): new conn_srvc id:26, app_id:255
,W/bt-btif ( 1975): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 1975): bta_dm_pm_ssr:2, lat:1200
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3311): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3311): Incoming connection initialized (thread ID: 305)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3311): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3311): Entering thread (ID: 305)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3311): onBytesRead: Read 82 bytes successfully (thread ID: 305)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3311): Got valid identity from [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT3106 E0:DB:10:1F:C9:5E]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3311): onBytesWritten: 77 bytes successfully written (thread ID: 305)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3311): removeThreadFromList: Removing thread with ID 305
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3311): Handshake thread disposed (thread ID: 305)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3311): onIncomingConnectionConnected: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT3106 E0:DB:10:1F:C9:5E]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3311): Exiting thread (ID: 305)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onConnected: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT3106 E0:DB:10:1F:C9:5E]
,I/io.jxcore.node.ConnectionHelper( 3311): onConnected: Incoming connection, peer ID: E0:DB:10:1F:C9:5E, name: samsung-SM-N9005_PT3106, Bluetooth address: E0:DB:10:1F:C9:5E
D/io.jxcore.node.ConnectionHelper( 3311): hasConnection: No connection with peer with ID E0:DB:10:1F:C9:5E
I/io.jxcore.node.ConnectionHelper( 3311): addNewPeerToListAndNotify: Adding peer with ID E0:DB:10:1F:C9:5E
I/jxcore-log( 3311): peerAvailabilityChanged [{"peerIdentifier":"E0:DB:10:1F:C9:5E","peerName":"samsung-SM-N9005_PT3106","peerAvailable":true}]
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): Found peer : samsung-SM-N9005_PT3106, Available: true
I/jxcore-log( 3311): 
I/io.jxcore.node.ConnectionHelper( 3311): onConnected: Incoming socket thread, for peer with ID E0:DB:10:1F:C9:5E, created successfully
,D/io.jxcore.node.ConnectionHelper( 3311): onConnected: The total number of connections is now 1
D/io.jxcore.node.IncomingSocketThread( 3311): Entering thread (ID: 306)
,I/io.jxcore.node.IncomingSocketThread( 3311): Local host address: localhost/127.0.0.1, port: 38884
,D/io.jxcore.node.IncomingSocketThread( 3311): Setting local streams and starting stream copying threads...
,I/jxcore-log( 3311): 2015-12-15T04:07:52.778Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3311): 
,I/io.jxcore.node.StreamCopyingThread( 3311): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3311): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.IncomingSocketThread( 3311): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3311): Exiting thread (ID: 306)
,I/io.jxcore.node.StreamCopyingThread( 3311): Entering thread (ID: 307, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 3311): Entering thread (ID: 308, name: Receiver)
,I/jxcore-log( 3311): 2015-12-15T04:07:53.731Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:07:53.738Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:07:53.777Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3311): 
I/jxcore-log( 3311): 2015-12-15T04:07:53.779Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:07:53.795Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:07:53.803Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:07:53.831Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:07:53.866Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:07:53.884Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:07:53.915Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:07:53.946Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:07:53.960Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:07:53.982Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:07:54.016Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:07:54.030Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:07:54.067Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:07:54.080Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:07:54.091Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:07:54.108Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:07:54.119Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:07:54.157Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:07:54.168Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:07:54.178Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:07:54.198Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:07:54.237Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:07:54.247Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:07:54.283Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:07:54.315Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:07:54.332Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3311): 
,W/bt-btif ( 1975): invalid rfc slot id: 5
,W/io.jxcore.node.StreamCopyingThread( 3311): Either failed to read from the output stream or write to the input stream (thread ID: 308, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 3311): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3311): onDisconnected: Incoming connection, peer with ID E0:DB:10:1F:C9:5E disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3311): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 306
I/io.jxcore.node.IncomingSocketThread( 3311): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3311): doStop: Thread ID: 308
I/io.jxcore.node.IncomingSocketThread( 3311): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3311): doStop: Thread ID: 307
I/io.jxcore.node.IncomingSocketThread( 3311): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.IncomingSocketThread( 3311): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3311): Either failed to read from the output stream or write to the input stream (thread ID: 307, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3311): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3311): onDisconnected: Incoming connection, peer with ID E0:DB:10:1F:C9:5E disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.IncomingSocketThread( 3311): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.IncomingSocketThread( 3311): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3311): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3311): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.ConnectionHelper( 3311): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3311): Exiting thread (ID: 307, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 3311): Exiting thread (ID: 308, name: Receiver)
,I/jxcore-log( 3311): 2015-12-15T04:07:54.429Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3311): 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): start: Starting peer discovery...
,I/wpa_supplicant( 1026): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,D/btif_config_util( 1975): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: XT1039_8c05 f4:f1:e1:5c:43:c8
,D/WifiP2pManager( 3311): Ignored { when=-6ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service request added successfully
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3311): teardown
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): testSendData stopped
I/jxcore-log( 3311): 
,I/io.jxcore.node.ConnectionHelper( 3311): stop
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3311): Shutting down...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3311): shutdown
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3311): Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3311): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3311): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3311): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:489)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3311): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:399)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3311): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3311): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3311): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread.run(BluetoothServerThread.java:89)
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3311): onIncomingConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3311): Socket is null
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3311): onIncomingConnectionFailed: Socket is null
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3311): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3311): onServerStopped
,E/bt-btm  ( 1975): tBTM_SEC_DEV:0xa3f50ebc rs_disc_pending=1
,E/bt-btif ( 1975): DISCOVERY_COMP_EVT slot id:6, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 1975): invalid rfc slot id: 6
,E/bt-btm  ( 1975): btm_sec_disconnected - Clearing Pending flag
,W/bt-btif ( 1975): bta_dm_check_av:0
,W/bt-btif ( 1975): btif_dm_cback : unhandled event (14)
,E/BluetoothRemoteDevices( 1975): aclStateChangeCallback: Device is NULL
,W/BluetoothAdapter( 3311): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 1975): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 1975): tBTM_SEC_DEV:0xa3f51084 rs_disc_pending=0
,W/bt-btif ( 1975): bta_dm_check_av:0
,W/bt-btif ( 1975): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 1975): rfc_find_lcid_mcb LCID reused LCID:0x42 current:0x0
,W/bt-rfcomm( 1975): RFCOMM_DisconnectInd LCID:0x42
,E/bt-btm  ( 1975): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 1975): onReceive
,D/BluetoothManagerService(  735): Message: 20
D/BluetoothManagerService(  735): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@14924814:true
,I/BTConnectionReceiver( 1362): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1362): Bluetooth Device Name: Note3-1
,W/bt-btif ( 1975): info:x10
,D/        ( 1975): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BTConnectionReceiver( 1362): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1362): Bluetooth Device Name: Note3-1
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/btif_config_util( 1975): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 1975): SDP - Rcvd conn cnf with error: 0x4  CID 0x43
E/bt-btif ( 1975): DISCOVERY_COMP_EVT slot id:8, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 1975): invalid rfc slot id: 8
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3311): shutdown
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3311): Exiting thread (thread ID: 304)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): stopServiceDiscovery
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): setState: NOT_INITIALIZED
I/jxcore-log( 3311): StopBroadcasting went ok
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:08:17.928Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3311): 
D/io.jxcore.node.ConnectionHelper( 3311): disconnectOutgoingConnection: Trying to close connection to peer with ID 34:FC:EF:9D:93:0B
E/io.jxcore.node.ConnectionHelper( 3311): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 34:FC:EF:9D:93:0B
D/io.jxcore.node.ConnectionHelper( 3311): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,W/io.jxcore.node.ConnectionHelper( 3311): disconnectOutgoingConnection: Failed to disconnect (peer ID: 34:FC:EF:9D:93:0B), either no such connection or failed to close the connection
,I/wpa_supplicant( 1026): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
,I/jxcore-log( 3311): 2015-12-15T04:08:17.933Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3311): 
I/jxcore-log( 3311): 2015-12-15T04:08:17.946Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
I/jxcore-log( 3311): 
I/chromium( 3311): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onConnectionFailed: Socket is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT3623"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Resolved peer properties: [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT3623 F4:F1:E1:5C:3B:E2]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT6503","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT6503 F8:95:C7:87:85:54]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: 2 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
I/io.jxcore.node.ConnectionHelper( 3311): onConnectionManagerStateChanged: INITIALIZED
I/io.jxcore.node.ConnectionHelper( 3311): onConnectionManagerStateChanged: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3311): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Peer discovery stopped successfully
,I/io.jxcore.node.ConnectionHelper( 3311): onPeerDiscovered: Bluetooth address: F4:F1:E1:5C:3B:E2, peer name: motorola-XT1039_PT3623, peer ID: F4:F1:E1:5C:3B:E2, Wi-Fi Direct device name: XT1039_8c05, Wi-Fi Direct address: f4:f1:e1:5c:43:c8
I/io.jxcore.node.ConnectionHelper( 3311): addNewPeerToListAndNotify: Adding peer with ID F4:F1:E1:5C:3B:E2
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list containing 2 peer(s), but doing nothing with that list
I/io.jxcore.node.ConnectionHelper( 3311): onPeerDiscovered: Bluetooth address: F8:95:C7:87:85:54, peer name: LGE-LG-D722_PT6503, peer ID: F8:95:C7:87:85:54, Wi-Fi Direct device name: , Wi-Fi Direct address: a2:39:f7:70:12:80
I/io.jxcore.node.ConnectionHelper( 3311): addNewPeerToListAndNotify: Peer with ID F8:95:C7:87:85:54 already in the list
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list containing 2 peer(s), but doing nothing with that list
,I/jxcore-log( 3311): --- start :testSendData.js---
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): testSendData created {"serverTimeout":1200000,"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":23}bt-address length : 0
I/jxcore-log( 3311): 
I/jxcore-log( 3311): daya100000
I/jxcore-log( 3311): 
I/jxcore-log( 3311): check server
I/jxcore-log( 3311): 
I/jxcore-log( 3311): serverPort is 40224
I/jxcore-log( 3311): 
,D/BluetoothManagerService(  735): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): stop: Stopping Bluetooth and peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): initialize: 34:FC:EF:11:AE:67 LGE-Nexus 5_PT5145
D/BluetoothManagerService(  735): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3311): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): initialize: Bluetooth and Wi-Fi OK
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): setState: INITIALIZED
,D/BluetoothManagerService(  735): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5145","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3311): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  735): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 3311): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5145","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3311): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5145","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): start: Starting peer discovery...
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onIsDiscoveryStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): startWifiPeerDiscovery: Started
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): setState: RUNNING
,I/jxcore-log( 3311): peerAvailabilityChanged [{"peerIdentifier":"34:FC:EF:9D:93:0B","peerName":"LGE-LG-D802_PT349","peerAvailable":true},{"peerIdentifier":"7C:F9:0E:34:8A:A0","peerName":"samsung-SM-G900F_PT5051","peerAvailable":true},{"peerIdentifier":"F8:95:C7:87:85:54","peerName":"LGE-LG-D722_PT6503","peerAvailable":true},{"peerIdentifier":"34:FC:EF:11:B1:66","peerName":"LGE-Nexus 5_PT1299","peerAvailable":true},{"peerIdentifier":"00:F4:6F:30:E0:6C","peerName":"samsung-SM-G800F_PT9986","peerAvailable":true},{"peerIdentifier":"B4:CE:F6:AB:A4:6A","peerName":"HTC-HTC Desire 820_PT2765","peerAvailable":true},{"peerIdentifier":"F8:95:C7:87:3C:51","peerName":"LGE-LG-H815_PT4197","peerAvailable":true},{"peerIdentifier":"08:EC:A9:50:76:27","peerName":"samsung-SM-A300FU_PT6932","peerAvailable":true},{"peerIdentifier":"38:94:96:B5:06:DC","peerName":"samsung-SM-G800H_PT1658","peerAvailable":true},{"peerIdentifier":"F8:CF:C5:D9:E5:61","peerName":"motorola-Nexus 6_PT1658","peerAvailable":true},{"peerIdentifier":"08:EC:A9:50:75:41","peerNam
I/jxcore-log( 3311): Found peer : LGE-LG-D802_PT349, Available: true
I/jxcore-log( 3311): 
I/jxcore-log( 3311): Found peer : samsung-SM-G900F_PT5051, Available: true
I/jxcore-log( 3311): 
I/jxcore-log( 3311): Found peer : LGE-LG-D722_PT6503, Available: true
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): Found peer : LGE-Nexus 5_PT1299, Available: true
I/jxcore-log( 3311): 
I/jxcore-log( 3311): Found peer : samsung-SM-G800F_PT9986, Available: true
I/jxcore-log( 3311): 
I/jxcore-log( 3311): Found peer : HTC-HTC Desire 820_PT2765, Available: true
I/jxcore-log( 3311): 
I/jxcore-log( 3311): Found peer : LGE-LG-H815_PT4197, Available: true
I/jxcore-log( 3311): 
I/jxcore-log( 3311): Found peer : samsung-SM-A300FU_PT6932, Available: true
I/jxcore-log( 3311): 
I/jxcore-log( 3311): Found peer : samsung-SM-G800H_PT1658, Available: true
I/jxcore-log( 3311): 
I/jxcore-log( 3311): Found peer : motorola-Nexus 6_PT1658, Available: true
I/jxcore-log( 3311): 
I/jxcore-log( 3311): Found peer : samsung-SM-A300FU_PT5619, Available: true
I/jxcore-log( 3311): 
I/jxcore-log( 3311): Found peer : LGE-LG-D855_PT3010, Available: true
I/jxcore-log( 3311): 
I/jxcore-log( 3311): Found peer : samsung-SM-N9005_PT3106, Available: true
I/jxcore-log( 3311): 
I/jxcore-log( 3311): Found peer : motorola-XT1039_PT3623, Available: true
I/jxcore-log( 3311): 
I/jxcore-log( 3311): startWithNextDevice
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): device[1]: 34:FC:EF:9D:93:0B
I/jxcore-log( 3311): 
I/jxcore-log( 3311): 2015-12-15T04:08:17.990Z SendDataConnector.js: Start called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3311): 
I/jxcore-log( 3311): 2015-12-15T04:08:17.990Z SendDataConnector.js: doConnect called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3311): 
I/jxcore-log( 3311): 2015-12-15T04:08:17.990Z SendDataConnector.js: do connect now
I/jxcore-log( 3311): 
,I/io.jxcore.node.ConnectionHelper( 3311): connect: Trying to connect to peer with ID 34:FC:EF:9D:93:0B
D/io.jxcore.node.ConnectionHelper( 3311): hasConnection: No connection with peer with ID 34:FC:EF:9D:93:0B
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): connect: Thali Test's G2
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3311): connect: Trying to start connecting to null in address 34:FC:EF:9D:93:0B
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onConnecting: null 34:FC:EF:9D:93:0B
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3311): connect: Started connecting to null in address 34:FC:EF:9D:93:0B
I/io.jxcore.node.ConnectionHelper( 3311): connect: Connection process successfully started (peer ID: 34:FC:EF:9D:93:0B)
I/io.jxcore.node.ConnectionHelper( 3311): start: OK
,I/jxcore-log( 3311): StartBroadcasting started ok
I/jxcore-log( 3311): 
I/jxcore-log( 3311): null
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:08:17.995Z SendDataTCPServer.js: TCP/IP server is bound to port: 40224
I/jxcore-log( 3311): 
I/chromium( 3311): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3311): Trying to connect to peer with address 34:FC:EF:9D:93:0B (thread ID: 310)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3311): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3311): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3311): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onWifiStateChanged: State changed to 2
,D/BTIF_SOCK( 1975): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi peer discovery...
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): startWifiPeerDiscovery: Already started
I/io.jxcore.node.ConnectionHelper( 3311): onConnectionManagerStateChanged: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3311): Local service added successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): restart: Restarting...
,I/wpa_supplicant( 1026): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
I/io.jxcore.node.ConnectionHelper( 3311): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Peer discovery stopped successfully
,W/ProcessCpuTracker(  735): Skipping unknown process pid 3840
W/ProcessCpuTracker(  735): Skipping unknown process pid 3843
,W/bt-btif ( 1975): new conn_srvc id:26, app_id:255
W/bt-btif ( 1975): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 1975): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3311): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3311): Incoming connection initialized (thread ID: 311)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3311): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3311): Entering thread (ID: 311)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3311): onBytesRead: Read 82 bytes successfully (thread ID: 311)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3311): Got valid identity from [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT3106 E0:DB:10:1F:C9:5E]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3311): onBytesWritten: 77 bytes successfully written (thread ID: 311)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3311): removeThreadFromList: Removing thread with ID 311
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3311): Handshake thread disposed (thread ID: 311)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3311): onIncomingConnectionConnected: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT3106 E0:DB:10:1F:C9:5E]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3311): Exiting thread (ID: 311)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onConnected: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT3106 E0:DB:10:1F:C9:5E]
I/io.jxcore.node.ConnectionHelper( 3311): onConnected: Incoming connection, peer ID: E0:DB:10:1F:C9:5E, name: samsung-SM-N9005_PT3106, Bluetooth address: E0:DB:10:1F:C9:5E
D/io.jxcore.node.ConnectionHelper( 3311): hasConnection: No connection with peer with ID E0:DB:10:1F:C9:5E
I/io.jxcore.node.ConnectionHelper( 3311): addNewPeerToListAndNotify: Peer with ID E0:DB:10:1F:C9:5E already in the list
,I/io.jxcore.node.ConnectionHelper( 3311): onConnected: Incoming socket thread, for peer with ID E0:DB:10:1F:C9:5E, created successfully
D/io.jxcore.node.ConnectionHelper( 3311): onConnected: The total number of connections is now 1
,D/io.jxcore.node.IncomingSocketThread( 3311): Entering thread (ID: 312)
,I/jxcore-log( 3311): 2015-12-15T04:08:18.521Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3311): 
,I/io.jxcore.node.IncomingSocketThread( 3311): Local host address: localhost/127.0.0.1, port: 40224
D/io.jxcore.node.IncomingSocketThread( 3311): Setting local streams and starting stream copying threads...
,I/io.jxcore.node.StreamCopyingThread( 3311): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 3311): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.IncomingSocketThread( 3311): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3311): Exiting thread (ID: 312)
,I/io.jxcore.node.StreamCopyingThread( 3311): Entering thread (ID: 314, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 3311): Entering thread (ID: 313, name: Sender)
,I/jxcore-log( 3311): 2015-12-15T04:08:19.490Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:08:19.526Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:08:19.541Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:08:19.548Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:08:19.578Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:08:19.721Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:08:19.763Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:08:19.803Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:08:19.837Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:08:19.878Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3311): 
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3311): 2015-12-15T04:08:19.944Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3311): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: S5mini-1 02:f4:6f:30:e0:6d
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): startServiceDiscovery: Invalid state, try calling restart()
,I/jxcore-log( 3311): 2015-12-15T04:08:19.971Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:08:20.007Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:08:20.015Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:08:20.027Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:08:20.060Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:08:20.095Z SendDataTCPServer.js: TCP/IP server has received 44648 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:08:20.109Z SendDataTCPServer.js: TCP/IP server has received 50588 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:08:20.112Z SendDataTCPServer.js: TCP/IP server has received 52568 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:08:20.143Z SendDataTCPServer.js: TCP/IP server has received 56528 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:08:20.147Z SendDataTCPServer.js: TCP/IP server has received 58508 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:08:20.155Z SendDataTCPServer.js: TCP/IP server has received 60488 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:08:20.158Z SendDataTCPServer.js: TCP/IP server has received 62468 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:08:20.194Z SendDataTCPServer.js: TCP/IP server has received 64448 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:08:20.197Z SendDataTCPServer.js: TCP/IP server has received 66428 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:08:20.201Z SendDataTCPServer.js: TCP/IP server has received 68408 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:08:20.205Z SendDataTCPServer.js: TCP/IP server has received 70388 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:08:20.234Z SendDataTCPServer.js: TCP/IP server has received 72368 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:08:20.273Z SendDataTCPServer.js: TCP/IP server has received 82268 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:08:20.276Z SendDataTCPServer.js: TCP/IP server has received 84248 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:08:20.315Z SendDataTCPServer.js: TCP/IP server has received 92168 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:08:20.321Z SendDataTCPServer.js: TCP/IP server has received 94148 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:08:20.356Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3311): 
,W/bt-btif ( 1975): invalid rfc slot id: 9
,W/io.jxcore.node.StreamCopyingThread( 3311): Either failed to read from the output stream or write to the input stream (thread ID: 314, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 3311): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3311): onDisconnected: Incoming connection, peer with ID E0:DB:10:1F:C9:5E disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3311): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 312
I/io.jxcore.node.IncomingSocketThread( 3311): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3311): doStop: Thread ID: 314
I/io.jxcore.node.IncomingSocketThread( 3311): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3311): doStop: Thread ID: 313
I/io.jxcore.node.IncomingSocketThread( 3311): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.IncomingSocketThread( 3311): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3311): Either failed to read from the output stream or write to the input stream (thread ID: 313, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3311): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3311): onDisconnected: Incoming connection, peer with ID E0:DB:10:1F:C9:5E disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.IncomingSocketThread( 3311): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.IncomingSocketThread( 3311): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3311): closeBluetoothSocketAndStreams
,D/io.jxcore.node.ConnectionHelper( 3311): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,I/io.jxcore.node.StreamCopyingThread( 3311): Exiting thread (ID: 314, name: Receiver)
,D/io.jxcore.node.ConnectionHelper( 3311): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,I/io.jxcore.node.StreamCopyingThread( 3311): Exiting thread (ID: 313, name: Sender)
,I/jxcore-log( 3311): 2015-12-15T04:08:20.463Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3311): 
,E/bt-btm  ( 1975): tBTM_SEC_DEV:0xa3f51084 rs_disc_pending=0
W/bt-btif ( 1975): bta_dm_check_av:0
,W/bt-btif ( 1975): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 1975): rfc_find_lcid_mcb LCID reused LCID:0x4d current:0x0
W/bt-rfcomm( 1975): RFCOMM_DisconnectInd LCID:0x4d
,W/bt-btif ( 1975): info:x10
,D/        ( 1975): remote version info [34:fc:ef:9d:93:0b]: 6, f, 4106
,E/BluetoothRemoteDevices( 1975): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1975): tBTM_SEC_DEV:0xa3f51084 rs_disc_pending=1
W/bt-btif ( 1975): bta_dm_check_av:0
,W/bt-btif ( 1975): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Peer discovery started successfully
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,E/bt-btm  ( 1975): tBTM_SEC_DEV:0xa3f50ebc rs_disc_pending=1
W/bt-btif ( 1975): bta_dm_check_av:0
,W/bt-btif ( 1975): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 1975): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 1975): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 1
E/bt-btif ( 1975): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 1975): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 1975): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 1975): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 0
,D/BluetoothAdapterProperties( 1975): Failed to remove device: 34:FC:EF:9D:93:0B
,E/bt-btm  ( 1975): btm_sec_disconnected - Clearing Pending flag
,I/BluetoothBondStateMachine( 1975): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 11 NewState: 10
,D/BluetoothMapService( 1975): onReceive
,I/BluetoothBondStateMachine( 1975): StableState(): Entering Off State
,I/BTConnectionReceiver( 1362): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1362): Bluetooth Device Name: Note3-1
,W/bt-btif ( 1975): new conn_srvc id:26, app_id:1
W/bt-btif ( 1975): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 1975): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3311): onSocketConnected: Authenticating next: [34:FC:EF:9D:93:0B LGE-LG-D802_PT349 34:FC:EF:9D:93:0B]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3311): Socket connection succeeded using port (1), total number of attempts: 1 (thread ID: 310)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3311): onBytesWritten: 77 bytes successfully written (thread ID: 315)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3311): Outgoing connection initialized (*handshake* thread ID: 315)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3311): Exiting thread (thread ID: 310)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3311): Entering thread (ID: 315)
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3311): onBytesRead: Read 76 bytes successfully (thread ID: 315)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3311): Handshake succeeded with [34:FC:EF:9D:93:0B LGE-LG-D802_PT349 34:FC:EF:9D:93:0B]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3311): onAuthenticated: Fully connected: [34:FC:EF:9D:93:0B LGE-LG-D802_PT349 34:FC:EF:9D:93:0B]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3311): Exiting thread (ID: 315)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onConnected: [34:FC:EF:9D:93:0B LGE-LG-D802_PT349 34:FC:EF:9D:93:0B]
,I/io.jxcore.node.ConnectionHelper( 3311): onConnected: Outgoing connection, peer ID: 34:FC:EF:9D:93:0B, name: LGE-LG-D802_PT349, Bluetooth address: 34:FC:EF:9D:93:0B
,D/io.jxcore.node.ConnectionHelper( 3311): hasConnection: No connection with peer with ID 34:FC:EF:9D:93:0B
I/io.jxcore.node.ConnectionHelper( 3311): addNewPeerToListAndNotify: Peer with ID 34:FC:EF:9D:93:0B already in the list
,I/io.jxcore.node.ConnectionHelper( 3311): onConnected: Outgoing socket thread, for peer with ID 34:FC:EF:9D:93:0B, created successfully
D/io.jxcore.node.ConnectionHelper( 3311): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 3311): Entering thread (ID: 316)
,D/io.jxcore.node.OutgoingSocketThread( 3311): Server socket local port: 35574
I/io.jxcore.node.OutgoingSocketThread( 3311): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3311): onListeningForIncomingConnections: Outgoing connection is using port 35574 (peer ID: 34:FC:EF:9D:93:0B)
I/jxcore-log( 3311): 2015-12-15T04:08:25.652Z SendDataConnector.js: CLIENT connected to 35574, error: null
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:08:25.653Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3311): 
,I/io.jxcore.node.OutgoingSocketThread( 3311): Incoming data from address: /127.0.0.1, port: 35574
D/io.jxcore.node.OutgoingSocketThread( 3311): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3311): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3311): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3311): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3311): Exiting thread (ID: 316)
,I/io.jxcore.node.StreamCopyingThread( 3311): Entering thread (ID: 318, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 3311): Entering thread (ID: 317, name: Sender)
,I/jxcore-log( 3311): 2015-12-15T04:08:25.732Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3311): 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1026): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1026): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 2: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 3: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 2: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 3: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 2: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 3: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3311): Ignored { when=-8ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service request added successfully
,D/WifiP2pManager( 3311): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service request added successfully
,D/WifiP2pManager( 3311): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service request added successfully
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 5 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 2: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 3: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 4: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3311): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service request added successfully
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3311): 2015-12-15T04:08:27.405Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3311): 
,D/btif_config_util( 1975): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 1026): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1026): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1026): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3311): 2015-12-15T04:08:28.285Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:08:28.616Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:08:28.939Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3311): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: Got empty list
,I/jxcore-log( 3311): 2015-12-15T04:08:29.252Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3311): 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3311): 2015-12-15T04:08:29.896Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:08:30.336Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:08:31.617Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:08:32.260Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:08:32.606Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3311): 
I/jxcore-log( 3311): 2015-12-15T04:08:32.607Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3311): 
I/jxcore-log( 3311): oneRoundDownNow
I/jxcore-log( 3311): 
I/jxcore-log( 3311): 2015-12-15T04:08:32.610Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3311): 
I/jxcore-log( 3311): 2015-12-15T04:08:32.610Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3311): 
D/io.jxcore.node.ConnectionHelper( 3311): disconnectOutgoingConnection: Trying to close connection to peer with ID 34:FC:EF:9D:93:0B
,I/io.jxcore.node.ConnectionHelper( 3311): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 34:FC:EF:9D:93:0B
I/io.jxcore.node.OutgoingSocketThread( 3311): close
I/io.jxcore.node.OutgoingSocketThread( 3311): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3311): doStop: Thread ID: 318
I/io.jxcore.node.OutgoingSocketThread( 3311): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3311): doStop: Thread ID: 317
I/io.jxcore.node.OutgoingSocketThread( 3311): closeLocalSocketAndStreams: Closing...
,I/io.jxcore.node.OutgoingSocketThread( 3311): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3311): Either failed to read from the output stream or write to the input stream (thread ID: 317, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3311): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3311): onDisconnected: Outgoing connection, peer with ID 34:FC:EF:9D:93:0B disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.OutgoingSocketThread( 3311): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.OutgoingSocketThread( 3311): closeLocalSocketAndStreams: Closing the localhost socket...
,I/io.jxcore.node.OutgoingSocketThread( 3311): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3311): Either failed to read from the output stream or write to the input stream (thread ID: 318, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.OutgoingSocketThread( 3311): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3311): onDisconnected: Outgoing connection, peer with ID 34:FC:EF:9D:93:0B disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3311): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3311): disconnectOutgoingConnection: Successfully disconnected (peer ID: 34:FC:EF:9D:93:0B
,E/io.jxcore.node.ConnectionHelper( 3311): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 34:FC:EF:9D:93:0B
D/io.jxcore.node.ConnectionHelper( 3311): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3311): Exiting thread (ID: 317, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 3311): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 34:FC:EF:9D:93:0B
D/io.jxcore.node.ConnectionHelper( 3311): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3311): Exiting thread (ID: 318, name: Receiver)
,I/jxcore-log( 3311): 2015-12-15T04:08:32.672Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): ---- round done--------
I/jxcore-log( 3311): 
I/jxcore-log( 3311): startWithNextDevice
I/jxcore-log( 3311): 
I/jxcore-log( 3311): device[2]: 7C:F9:0E:34:8A:A0
I/jxcore-log( 3311): 
I/jxcore-log( 3311): 2015-12-15T04:08:32.680Z SendDataConnector.js: Start called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3311): 
I/jxcore-log( 3311): 2015-12-15T04:08:32.680Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:08:32.680Z SendDataConnector.js: do connect now
I/jxcore-log( 3311): 
I/io.jxcore.node.ConnectionHelper( 3311): connect: Trying to connect to peer with ID 7C:F9:0E:34:8A:A0
D/io.jxcore.node.ConnectionHelper( 3311): hasConnection: No connection with peer with ID 7C:F9:0E:34:8A:A0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): connect: S5-1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3311): connect: Trying to start connecting to null in address 7C:F9:0E:34:8A:A0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onConnecting: null 7C:F9:0E:34:8A:A0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3311): connect: Started connecting to null in address 7C:F9:0E:34:8A:A0
I/io.jxcore.node.ConnectionHelper( 3311): connect: Connection process successfully started (peer ID: 7C:F9:0E:34:8A:A0)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3311): Trying to connect to peer with address 7C:F9:0E:34:8A:A0 (thread ID: 319)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3311): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
,W/BluetoothAdapter( 3311): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 1975): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 1975): bta_jv_rfc_port_to_cb(port_handle:0xc):jv handle:0x0 not FOUND
,W/bt-btif ( 1975): info:x10
,D/        ( 1975): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,E/BluetoothRemoteDevices( 1975): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 1975): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 1975): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 1
E/bt-btif ( 1975): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 1975): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 1975): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 1975): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 0
,D/BluetoothAdapterProperties( 1975): Failed to remove device: 7C:F9:0E:34:8A:A0
,I/BluetoothBondStateMachine( 1975): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 1975): StableState(): Entering Off State
,W/bt-btif ( 1975): new conn_srvc id:26, app_id:1
W/bt-btif ( 1975): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 1975): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3311): onSocketConnected: Authenticating next: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT5051 7C:F9:0E:34:8A:A0]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3311): Socket connection succeeded using port (1), total number of attempts: 1 (thread ID: 319)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3311): onBytesWritten: 77 bytes successfully written (thread ID: 320)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3311): Outgoing connection initialized (*handshake* thread ID: 320)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3311): Exiting thread (thread ID: 319)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3311): Entering thread (ID: 320)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3311): onBytesRead: Read 82 bytes successfully (thread ID: 320)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3311): Handshake succeeded with [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT5051 7C:F9:0E:34:8A:A0]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3311): onAuthenticated: Fully connected: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT5051 7C:F9:0E:34:8A:A0]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3311): Exiting thread (ID: 320)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onConnected: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT5051 7C:F9:0E:34:8A:A0]
I/io.jxcore.node.ConnectionHelper( 3311): onConnected: Outgoing connection, peer ID: 7C:F9:0E:34:8A:A0, name: samsung-SM-G900F_PT5051, Bluetooth address: 7C:F9:0E:34:8A:A0
D/io.jxcore.node.ConnectionHelper( 3311): hasConnection: No connection with peer with ID 7C:F9:0E:34:8A:A0
,I/io.jxcore.node.ConnectionHelper( 3311): addNewPeerToListAndNotify: Peer with ID 7C:F9:0E:34:8A:A0 already in the list
,I/io.jxcore.node.ConnectionHelper( 3311): onConnected: Outgoing socket thread, for peer with ID 7C:F9:0E:34:8A:A0, created successfully
D/io.jxcore.node.ConnectionHelper( 3311): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 3311): Entering thread (ID: 321)
,D/io.jxcore.node.OutgoingSocketThread( 3311): Server socket local port: 56091
I/io.jxcore.node.OutgoingSocketThread( 3311): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3311): onListeningForIncomingConnections: Outgoing connection is using port 56091 (peer ID: 7C:F9:0E:34:8A:A0)
I/jxcore-log( 3311): 2015-12-15T04:08:34.674Z SendDataConnector.js: CLIENT connected to 56091, error: null
I/jxcore-log( 3311): 
I/jxcore-log( 3311): 2015-12-15T04:08:34.675Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3311): 
,I/io.jxcore.node.OutgoingSocketThread( 3311): Incoming data from address: /127.0.0.1, port: 56091
D/io.jxcore.node.OutgoingSocketThread( 3311): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3311): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3311): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3311): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3311): Exiting thread (ID: 321)
,I/jxcore-log( 3311): 2015-12-15T04:08:34.697Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3311): 
,I/io.jxcore.node.StreamCopyingThread( 3311): Entering thread (ID: 322, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 3311): Entering thread (ID: 323, name: Receiver)
,I/jxcore-log( 3311): 2015-12-15T04:08:35.253Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:08:35.344Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:08:35.414Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:08:35.481Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:08:35.499Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:08:35.555Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:08:35.626Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:08:35.665Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:08:35.724Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:08:35.794Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3311): 
I/jxcore-log( 3311): 2015-12-15T04:08:35.795Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3311): 
I/jxcore-log( 3311): oneRoundDownNow
I/jxcore-log( 3311): 
I/jxcore-log( 3311): 2015-12-15T04:08:35.797Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3311): 
I/jxcore-log( 3311): 2015-12-15T04:08:35.797Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3311): 
D/io.jxcore.node.ConnectionHelper( 3311): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:34:8A:A0
I/io.jxcore.node.ConnectionHelper( 3311): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 7C:F9:0E:34:8A:A0
I/io.jxcore.node.OutgoingSocketThread( 3311): close
I/io.jxcore.node.OutgoingSocketThread( 3311): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3311): doStop: Thread ID: 323
I/io.jxcore.node.OutgoingSocketThread( 3311): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3311): doStop: Thread ID: 322
I/io.jxcore.node.OutgoingSocketThread( 3311): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.OutgoingSocketThread( 3311): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3311): Either failed to read from the output stream or write to the input stream (thread ID: 322, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3311): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3311): onDisconnected: Outgoing connection, peer with ID 7C:F9:0E:34:8A:A0 disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.OutgoingSocketThread( 3311): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.OutgoingSocketThread( 3311): closeLocalSocketAndStreams: Closing the localhost socket...
,I/io.jxcore.node.OutgoingSocketThread( 3311): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3311): Either failed to read from the output stream or write to the input stream (thread ID: 323, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.OutgoingSocketThread( 3311): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3311): onDisconnected: Outgoing connection, peer with ID 7C:F9:0E:34:8A:A0 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3311): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3311): disconnectOutgoingConnection: Successfully disconnected (peer ID: 7C:F9:0E:34:8A:A0
,E/io.jxcore.node.ConnectionHelper( 3311): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:34:8A:A0
D/io.jxcore.node.ConnectionHelper( 3311): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,I/io.jxcore.node.StreamCopyingThread( 3311): Exiting thread (ID: 322, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 3311): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:34:8A:A0
,D/io.jxcore.node.ConnectionHelper( 3311): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3311): Exiting thread (ID: 323, name: Receiver)
,I/jxcore-log( 3311): 2015-12-15T04:08:35.846Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3311): 
I/jxcore-log( 3311): ---- round done--------
I/jxcore-log( 3311): 
I/jxcore-log( 3311): startWithNextDevice
I/jxcore-log( 3311): 
I/jxcore-log( 3311): device[3]: F8:95:C7:87:85:54
I/jxcore-log( 3311): 
I/jxcore-log( 3311): 2015-12-15T04:08:35.852Z SendDataConnector.js: Start called with peer F8:95:C7:87:85:54
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:08:35.853Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:08:35.857Z SendDataConnector.js: do connect now
I/jxcore-log( 3311): 
,I/io.jxcore.node.ConnectionHelper( 3311): connect: Trying to connect to peer with ID F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 3311): hasConnection: No connection with peer with ID F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): connect: G3s-1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3311): connect: Trying to start connecting to null in address F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onConnecting: null F8:95:C7:87:85:54
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3311): connect: Started connecting to null in address F8:95:C7:87:85:54
I/io.jxcore.node.ConnectionHelper( 3311): connect: Connection process successfully started (peer ID: F8:95:C7:87:85:54)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3311): Trying to connect to peer with address F8:95:C7:87:85:54 (thread ID: 324)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3311): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3311): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 1975): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 1975): bta_jv_rfc_port_to_cb(port_handle:0xd):jv handle:0x0 not FOUND
,E/bt-btm  ( 1975): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 1975): onReceive
,I/BTConnectionReceiver( 1362): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:9D:93:0B, alias=null, name=Thali Test's G2, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1362): Bluetooth Device Name: Thali Test's G2
,E/bt-btm  ( 1975): tBTM_SEC_DEV:0xa3f5124c rs_disc_pending=0
W/bt-btif ( 1975): bta_dm_check_av:0
,W/bt-btif ( 1975): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 1975): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 1975): info:x10
,D/        ( 1975): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,E/BluetoothRemoteDevices( 1975): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 1975): process_service_search_attr_rsp
,E/bt-btm  ( 1975): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 1975): onReceive
,I/BTConnectionReceiver( 1362): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1362): Bluetooth Device Name: S5-1
,E/bt-btm  ( 1975): tBTM_SEC_DEV:0xa3f51414 rs_disc_pending=1
W/bt-btif ( 1975): bta_dm_check_av:0
,W/bt-btif ( 1975): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 1975): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1
E/bt-btif ( 1975): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 1975): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 1975): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 1975): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
,D/BluetoothAdapterProperties( 1975): Failed to remove device: F8:95:C7:87:85:54
,I/BluetoothBondStateMachine( 1975): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 1975): StableState(): Entering Off State
,W/bt-btif ( 1975): new conn_srvc id:26, app_id:1
W/bt-btif ( 1975): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 1975): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3311): onSocketConnected: Authenticating next: [F8:95:C7:87:85:54 LGE-LG-D722_PT6503 F8:95:C7:87:85:54]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3311): Socket connection succeeded using port (1), total number of attempts: 1 (thread ID: 324)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3311): onBytesWritten: 77 bytes successfully written (thread ID: 325)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3311): Outgoing connection initialized (*handshake* thread ID: 325)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3311): Exiting thread (thread ID: 324)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3311): Entering thread (ID: 325)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3311): onBytesRead: Read 77 bytes successfully (thread ID: 325)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3311): Handshake succeeded with [F8:95:C7:87:85:54 LGE-LG-D722_PT6503 F8:95:C7:87:85:54]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3311): onAuthenticated: Fully connected: [F8:95:C7:87:85:54 LGE-LG-D722_PT6503 F8:95:C7:87:85:54]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3311): Exiting thread (ID: 325)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onConnected: [F8:95:C7:87:85:54 LGE-LG-D722_PT6503 F8:95:C7:87:85:54]
I/io.jxcore.node.ConnectionHelper( 3311): onConnected: Outgoing connection, peer ID: F8:95:C7:87:85:54, name: LGE-LG-D722_PT6503, Bluetooth address: F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 3311): hasConnection: No connection with peer with ID F8:95:C7:87:85:54
I/io.jxcore.node.ConnectionHelper( 3311): addNewPeerToListAndNotify: Peer with ID F8:95:C7:87:85:54 already in the list
I/io.jxcore.node.ConnectionHelper( 3311): onConnected: Outgoing socket thread, for peer with ID F8:95:C7:87:85:54, created successfully
D/io.jxcore.node.ConnectionHelper( 3311): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 3311): Entering thread (ID: 326)
D/io.jxcore.node.OutgoingSocketThread( 3311): Server socket local port: 50199
I/io.jxcore.node.OutgoingSocketThread( 3311): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3311): onListeningForIncomingConnections: Outgoing connection is using port 50199 (peer ID: F8:95:C7:87:85:54)
,I/jxcore-log( 3311): 2015-12-15T04:08:41.760Z SendDataConnector.js: CLIENT connected to 50199, error: null
I/jxcore-log( 3311): 
I/jxcore-log( 3311): 2015-12-15T04:08:41.761Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:08:41.773Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3311): 
,I/io.jxcore.node.OutgoingSocketThread( 3311): Incoming data from address: /127.0.0.1, port: 50199
D/io.jxcore.node.OutgoingSocketThread( 3311): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3311): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3311): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3311): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3311): Exiting thread (ID: 326)
,I/io.jxcore.node.StreamCopyingThread( 3311): Entering thread (ID: 328, name: Receiver),
,I/io.jxcore.node.StreamCopyingThread( 3311): Entering thread (ID: 327, name: Sender)
,D/btif_config_util( 1975): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 1975): dm_pm_timer expires
W/bt-btif ( 1975): dm_pm_timer expires 0
W/bt-btif ( 1975): proc dm_pm_timer expires
,E/bt-btm  ( 1975): tBTM_SEC_DEV:0xa3f51414 rs_disc_pending=0
W/bt-btif ( 1975): bta_dm_check_av:0
,W/bt-btif ( 1975): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3311): 2015-12-15T04:08:52.240Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3311): 
I/jxcore-log( 3311): 2015-12-15T04:08:52.240Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:08:52.243Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:08:52.246Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:08:52.252Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3311): 
,E/io.jxcore.node.StreamCopyingThread( 3311): Input stream got -1 on read (thread ID: 327, thread name: Sender)
,E/io.jxcore.node.OutgoingSocketThread( 3311): The sending thread failed with error: Input stream got -1 on read
W/io.jxcore.node.ConnectionHelper( 3311): onDisconnected: Outgoing connection, peer with ID F8:95:C7:87:85:54 disconnected: Input stream got -1 on read
,I/io.jxcore.node.ConnectionHelper( 3311): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: F8:95:C7:87:85:54
I/io.jxcore.node.OutgoingSocketThread( 3311): close
I/io.jxcore.node.OutgoingSocketThread( 3311): close: Stopping receiving thread...
,I/io.jxcore.node.StreamCopyingThread( 3311): doStop: Thread ID: 328
I/io.jxcore.node.OutgoingSocketThread( 3311): close: Stopping sending thread...
,I/io.jxcore.node.StreamCopyingThread( 3311): doStop: Thread ID: 327
I/io.jxcore.node.OutgoingSocketThread( 3311): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.OutgoingSocketThread( 3311): closeLocalSocketAndStreams: Closing the local input stream...
,I/io.jxcore.node.OutgoingSocketThread( 3311): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.OutgoingSocketThread( 3311): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3311): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3311): Either failed to read from the output stream or write to the input stream (thread ID: 328, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.OutgoingSocketThread( 3311): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3311): onDisconnected: Outgoing connection, peer with ID F8:95:C7:87:85:54 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3311): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,E/io.jxcore.node.ConnectionHelper( 3311): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 3311): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,I/io.jxcore.node.StreamCopyingThread( 3311): Exiting thread (ID: 328, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 3311): Exiting thread (ID: 327, name: Sender)
,W/bt-btif ( 1975): bta_jv_rfc_port_to_cb(port_handle:0xe):jv handle:0x0 not FOUND
,E/bt-btm  ( 1975): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 1975): onReceive
,I/BTConnectionReceiver( 1362): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1362): Bluetooth Device Name: G3s-1
,I/art     (  735): Explicit concurrent mark sweep GC freed 61099(2MB) AllocSpace objects, 0(0B) LOS objects, 33% free, 27MB/41MB, paused 961us total 136.910ms
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): stopServiceDiscovery
,I/wpa_supplicant( 1026): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Peer discovery stopped successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
,I/jxcore-log( 3311): 2015-12-15T04:08:57.250Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 3311): 
I/jxcore-log( 3311): 2015-12-15T04:08:57.251Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 3311): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): start: Starting peer discovery...
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,D/io.jxcore.node.ConnectionHelper( 3311): disconnectOutgoingConnection: Trying to close connection to peer with ID F8:95:C7:87:85:54
E/io.jxcore.node.ConnectionHelper( 3311): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 3311): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3311): disconnectOutgoingConnection: Failed to disconnect (peer ID: F8:95:C7:87:85:54), either no such connection or failed to close the connection
I/jxcore-log( 3311): 2015-12-15T04:09:02.256Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3311): 
I/jxcore-log( 3311): 2015-12-15T04:09:02.256Z SendDataConnector.js: Connect (retry count 1) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 3311): 
I/jxcore-log( 3311): 2015-12-15T04:09:02.257Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3311): 
I/jxcore-log( 3311): 2015-12-15T04:09:02.258Z SendDataConnector.js: do connect now
I/jxcore-log( 3311): 
I/io.jxcore.node.ConnectionHelper( 3311): connect: Trying to connect to peer with ID F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 3311): hasConnection: No connection with peer with ID F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): connect: G3s-1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3311): connect: Trying to start connecting to G3s-1 in address F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onConnecting: G3s-1 F8:95:C7:87:85:54
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3311): connect: Started connecting to G3s-1 in address F8:95:C7:87:85:54
I/io.jxcore.node.ConnectionHelper( 3311): connect: Connection process successfully started (peer ID: F8:95:C7:87:85:54)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3311): Trying to connect to peer with address F8:95:C7:87:85:54 (thread ID: 329)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3311): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3311): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 1975): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 1975): info:x10
,D/        ( 1975): remote version info [f8:95:c7:87:85:54]: 7, f, 610c
,W/bt-sdp  ( 1975): process_service_search_attr_rsp
,I/BTConnectionReceiver( 1362): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1362): Bluetooth Device Name: G3s-1
,I/BluetoothBondStateMachine( 1975): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1
E/bt-btif ( 1975): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 1975): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 1975): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 1975): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
,D/BluetoothAdapterProperties( 1975): Failed to remove device: F8:95:C7:87:85:54
,I/BluetoothBondStateMachine( 1975): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 1975): StableState(): Entering Off State
,E/bt-btm  ( 1975): tBTM_SEC_DEV:0xa3f51414 rs_disc_pending=0
W/bt-btif ( 1975): bta_dm_check_av:0
,W/bt-btif ( 1975): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: Android_1950 b6:ce:f6:ad:a4:6b
,D/WifiP2pManager( 3311): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service request added successfully
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 1975): new conn_srvc id:26, app_id:1
W/bt-btif ( 1975): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 1975): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3311): onSocketConnected: Authenticating next: [F8:95:C7:87:85:54 LGE-LG-D722_PT6503 F8:95:C7:87:85:54]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3311): Socket connection succeeded using port (1), total number of attempts: 1 (thread ID: 329)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3311): onBytesWritten: 77 bytes successfully written (thread ID: 330)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3311): Outgoing connection initialized (*handshake* thread ID: 330)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3311): Exiting thread (thread ID: 329)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3311): Entering thread (ID: 330)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3311): onBytesRead: Read 77 bytes successfully (thread ID: 330)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3311): Handshake succeeded with [F8:95:C7:87:85:54 LGE-LG-D722_PT6503 F8:95:C7:87:85:54]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3311): onAuthenticated: Fully connected: [F8:95:C7:87:85:54 LGE-LG-D722_PT6503 F8:95:C7:87:85:54]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3311): Exiting thread (ID: 330)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onConnected: [F8:95:C7:87:85:54 LGE-LG-D722_PT6503 F8:95:C7:87:85:54]
I/io.jxcore.node.ConnectionHelper( 3311): onConnected: Outgoing connection, peer ID: F8:95:C7:87:85:54, name: LGE-LG-D722_PT6503, Bluetooth address: F8:95:C7:87:85:54
,D/io.jxcore.node.ConnectionHelper( 3311): hasConnection: No connection with peer with ID F8:95:C7:87:85:54
I/io.jxcore.node.ConnectionHelper( 3311): addNewPeerToListAndNotify: Peer with ID F8:95:C7:87:85:54 already in the list
,I/io.jxcore.node.ConnectionHelper( 3311): onConnected: Outgoing socket thread, for peer with ID F8:95:C7:87:85:54, created successfully
D/io.jxcore.node.ConnectionHelper( 3311): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 3311): Entering thread (ID: 331)
D/io.jxcore.node.OutgoingSocketThread( 3311): Server socket local port: 39669
,I/io.jxcore.node.OutgoingSocketThread( 3311): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3311): onListeningForIncomingConnections: Outgoing connection is using port 39669 (peer ID: F8:95:C7:87:85:54)
I/jxcore-log( 3311): 2015-12-15T04:09:05.962Z SendDataConnector.js: CLIENT connected to 39669, error: null
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:09:05.963Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3311): 
,I/io.jxcore.node.OutgoingSocketThread( 3311): Incoming data from address: /127.0.0.1, port: 39669
D/io.jxcore.node.OutgoingSocketThread( 3311): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3311): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3311): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3311): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3311): Exiting thread (ID: 331)
,I/jxcore-log( 3311): 2015-12-15T04:09:05.987Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3311): 
,I/io.jxcore.node.StreamCopyingThread( 3311): Entering thread (ID: 332, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 3311): Entering thread (ID: 333, name: Receiver)
,I/jxcore-log( 3311): 2015-12-15T04:09:06.527Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:09:06.556Z SendDataConnector.js: CLIENT is data received : 20000,
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:09:06.614Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:09:06.670Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:09:06.725Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:09:06.806Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:09:06.829Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:09:06.958Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:09:07.013Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:09:07.055Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3311): 
I/jxcore-log( 3311): 2015-12-15T04:09:07.056Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3311): 
I/jxcore-log( 3311): oneRoundDownNow
I/jxcore-log( 3311): 
I/jxcore-log( 3311): 2015-12-15T04:09:07.058Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3311): 
I/jxcore-log( 3311): 2015-12-15T04:09:07.058Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3311): 
D/io.jxcore.node.ConnectionHelper( 3311): disconnectOutgoingConnection: Trying to close connection to peer with ID F8:95:C7:87:85:54
I/io.jxcore.node.ConnectionHelper( 3311): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: F8:95:C7:87:85:54
I/io.jxcore.node.OutgoingSocketThread( 3311): close
I/io.jxcore.node.OutgoingSocketThread( 3311): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3311): doStop: Thread ID: 333
I/io.jxcore.node.OutgoingSocketThread( 3311): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3311): doStop: Thread ID: 332
I/io.jxcore.node.OutgoingSocketThread( 3311): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.OutgoingSocketThread( 3311): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3311): Either failed to read from the output stream or write to the input stream (thread ID: 332, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3311): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3311): onDisconnected: Outgoing connection, peer with ID F8:95:C7:87:85:54 disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.OutgoingSocketThread( 3311): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.OutgoingSocketThread( 3311): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3311): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3311): Either failed to read from the output stream or write to the input stream (thread ID: 333, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 3311): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3311): onDisconnected: Outgoing connection, peer with ID F8:95:C7:87:85:54 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3311): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3311): disconnectOutgoingConnection: Successfully disconnected (peer ID: F8:95:C7:87:85:54
,E/io.jxcore.node.ConnectionHelper( 3311): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 3311): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3311): Exiting thread (ID: 332, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 3311): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:95:C7:87:85:54
,D/io.jxcore.node.ConnectionHelper( 3311): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3311): Exiting thread (ID: 333, name: Receiver)
,I/jxcore-log( 3311): 2015-12-15T04:09:07.099Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3311): 
I/jxcore-log( 3311): ---- round done--------
I/jxcore-log( 3311): 
I/jxcore-log( 3311): startWithNextDevice
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): device[4]: 34:FC:EF:11:B1:66
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:09:07.103Z SendDataConnector.js: Start called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3311): 
I/jxcore-log( 3311): 2015-12-15T04:09:07.110Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3311): 
I/jxcore-log( 3311): 2015-12-15T04:09:07.110Z SendDataConnector.js: do connect now
I/jxcore-log( 3311): 
,I/io.jxcore.node.ConnectionHelper( 3311): connect: Trying to connect to peer with ID 34:FC:EF:11:B1:66
D/io.jxcore.node.ConnectionHelper( 3311): hasConnection: No connection with peer with ID 34:FC:EF:11:B1:66
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): connect: Android_2dc2
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3311): connect: Trying to start connecting to null in address 34:FC:EF:11:B1:66
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onConnecting: null 34:FC:EF:11:B1:66
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3311): connect: Started connecting to null in address 34:FC:EF:11:B1:66
I/io.jxcore.node.ConnectionHelper( 3311): connect: Connection process successfully started (peer ID: 34:FC:EF:11:B1:66)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3311): Trying to connect to peer with address 34:FC:EF:11:B1:66 (thread ID: 334)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3311): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3311): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 1975): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 1975): bta_jv_rfc_port_to_cb(port_handle:0xf):jv handle:0x0 not FOUND
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/btif_config_util( 1975): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1975): tBTM_SEC_DEV:0xa3f51414 rs_disc_pending=1
W/bt-btif ( 1975): bta_dm_check_av:0
,W/bt-btif ( 1975): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 1975): info:x10
,D/        ( 1975): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
,E/BluetoothRemoteDevices( 1975): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 1975): tBTM_SEC_DEV:0xa3f515dc rs_disc_pending=1
W/bt-btif ( 1975): bta_dm_check_av:0
,W/bt-btif ( 1975): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 1975): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 1975): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:B1:66 newState: 1
E/bt-btif ( 1975): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 1975): Bond State Change Intent:34:FC:EF:11:B1:66 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 1975): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 1975): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:B1:66 newState: 0
,D/BluetoothAdapterProperties( 1975): Failed to remove device: 34:FC:EF:11:B1:66
,I/BluetoothBondStateMachine( 1975): Bond State Change Intent:34:FC:EF:11:B1:66 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 1975): StableState(): Entering Off State
,W/bt-btif ( 1975): new conn_srvc id:26, app_id:1
W/bt-btif ( 1975): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 1975): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3311): onSocketConnected: Authenticating next: [34:FC:EF:11:B1:66 LGE-Nexus 5_PT1299 34:FC:EF:11:B1:66]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3311): Socket connection succeeded using port (1), total number of attempts: 1 (thread ID: 334)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3311): onBytesWritten: 77 bytes successfully written (thread ID: 335)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3311): Outgoing connection initialized (*handshake* thread ID: 335)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3311): Exiting thread (thread ID: 334)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3311): Entering thread (ID: 335)
,E/bt-btm  ( 1975): tBTM_SEC_DEV:0xa3f515dc rs_disc_pending=0
W/bt-btif ( 1975): bta_dm_check_av:0
,W/bt-btif ( 1975): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 1975): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 1975): onReceive
,I/BTConnectionReceiver( 1362): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1362): Bluetooth Device Name: G3s-1
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1026): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/btif_config_util( 1975): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 1975): dm_pm_timer expires
W/bt-btif ( 1975): dm_pm_timer expires 0
,W/bt-btif ( 1975): proc dm_pm_timer expires
,W/bt-btif ( 1975): invalid rfc slot id: 15
,E/bt-btm  ( 1975): btm_sec_disconnected - Clearing Pending flag
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3311): Disconnected: bt socket closed, read return: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3311): onDisconnected: [  ] (thread ID: 335)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3311): onConnectionFailed: Socket disconnected
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3311): shutdown
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3311): Exiting thread (ID: 335)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onConnectionFailed: Socket disconnected [  ]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3311): shutdown
,D/BluetoothMapService( 1975): onReceive,
,I/BTConnectionReceiver( 1362): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:B1:66, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1362): Bluetooth Device Name: Nexus 5
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT6734","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6734 E0:DB:10:14:E2:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
I/io.jxcore.node.ConnectionHelper( 3311): onPeerDiscovered: Bluetooth address: E0:DB:10:14:E2:C0, peer name: samsung-SM-N910C_PT6734, peer ID: E0:DB:10:14:E2:C0, Wi-Fi Direct device name: Note4-1, Wi-Fi Direct address: 92:b6:86:43:73:1c
I/io.jxcore.node.ConnectionHelper( 3311): addNewPeerToListAndNotify: Adding peer with ID E0:DB:10:14:E2:C0
I/jxcore-log( 3311): peerAvailabilityChanged [{"peerIdentifier":"E0:DB:10:14:E2:C0","peerName":"samsung-SM-N910C_PT6734","peerAvailable":true}]
I/jxcore-log( 3311): 
I/jxcore-log( 3311): Found peer : samsung-SM-N910C_PT6734, Available: true
I/jxcore-log( 3311): 
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT9222","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Resolved peer properties: [44:80:EB:7B:5A:05 motorola-XT1072_PT9222 44:80:EB:7B:5A:05]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: 2 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
I/io.jxcore.node.ConnectionHelper( 3311): onPeerDiscovered: Bluetooth address: 44:80:EB:7B:5A:05, peer name: motorola-XT1072_PT9222, peer ID: 44:80:EB:7B:5A:05, Wi-Fi Direct device name: , Wi-Fi Direct address: 44:80:eb:7b:5a:07
I/io.jxcore.node.ConnectionHelper( 3311): addNewPeerToListAndNotify: Adding peer with ID 44:80:EB:7B:5A:05
I/jxcore-log( 3311): peerAvailabilityChanged [{"peerIdentifier":"44:80:EB:7B:5A:05","peerName":"motorola-XT1072_PT9222","peerAvailable":true}]
I/jxcore-log( 3311): 
I/jxcore-log( 3311): Found peer : motorola-XT1072_PT9222, Available: true
I/jxcore-log( 3311): 
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list containing 2 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT4039","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4039 7C:F9:0E:51:18:22]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: 3 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
I/io.jxcore.node.ConnectionHelper( 3311): onPeerDiscovered: Bluetooth address: 7C:F9:0E:51:18:22, peer name: samsung-SM-A500FU_PT4039, peer ID: 7C:F9:0E:51:18:22, Wi-Fi Direct device name: , Wi-Fi Direct address: 7e:f9:0e:51:18:23
I/io.jxcore.node.ConnectionHelper( 3311): addNewPeerToListAndNotify: Adding peer with ID 7C:F9:0E:51:18:22
I/jxcore-log( 3311): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:51:18:22","peerName":"samsung-SM-A500FU_PT4039","peerAvailable":true}]
I/jxcore-log( 3311): 
I/jxcore-log( 3311): Found peer : samsung-SM-A500FU_PT4039, Available: true
I/jxcore-log( 3311): 
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list containing 3 peer(s), but doing nothing with that list
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 1026): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT1757"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Resolved peer properties: [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT1757 80:01:84:8A:B3:68]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: 4 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
I/io.jxcore.node.ConnectionHelper( 3311): onPeerDiscovered: Bluetooth address: 80:01:84:8A:B3:68, peer name: HTC-HTC Desire 820_PT1757, peer ID: 80:01:84:8A:B3:68, Wi-Fi Direct device name: Android_63cc, Wi-Fi Direct address: 82:01:84:6b:e8:5d
I/io.jxcore.node.ConnectionHelper( 3311): addNewPeerToListAndNotify: Adding peer with ID 80:01:84:8A:B3:68
I/jxcore-log( 3311): peerAvailabilityChanged [{"peerIdentifier":"80:01:84:8A:B3:68","peerName":"HTC-HTC Desire 820_PT1757","peerAvailable":true}]
I/jxcore-log( 3311): 
I/jxcore-log( 3311): Found peer : HTC-HTC Desire 820_PT1757, Available: true
I/jxcore-log( 3311): 
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list containing 4 peer(s), but doing nothing with that list
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT3010","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT3010 58:3F:54:73:64:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: 5 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
,I/io.jxcore.node.ConnectionHelper( 3311): onPeerDiscovered: Bluetooth address: 58:3F:54:73:64:C0, peer name: LGE-LG-D855_PT3010, peer ID: 58:3F:54:73:64:C0, Wi-Fi Direct device name: , Wi-Fi Direct address: 02:9a:02:7b:60:ac
I/io.jxcore.node.ConnectionHelper( 3311): addNewPeerToListAndNotify: Peer with ID 58:3F:54:73:64:C0 already in the list
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list containing 5 peer(s), but doing nothing with that list
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2p_dev_addr=3a:94:96:b5:06:dd pri_dev_type=10-0050F204-5 name='Galaxy S5-2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1026): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT3106","ra":"E0:DB:10:1F:C9:5E"}", service type: "Cordovap2p._tcp.local."
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT3106 E0:DB:10:1F:C9:5E]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: 6 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
,I/io.jxcore.node.ConnectionHelper( 3311): onPeerDiscovered: Bluetooth address: E0:DB:10:1F:C9:5E, peer name: samsung-SM-N9005_PT3106, peer ID: E0:DB:10:1F:C9:5E, Wi-Fi Direct device name: , Wi-Fi Direct address: ea:50:8b:de:28:a3
I/io.jxcore.node.ConnectionHelper( 3311): addNewPeerToListAndNotify: Peer with ID E0:DB:10:1F:C9:5E already in the list
,W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list containing 6 peer(s), but doing nothing with that list
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): stopServiceDiscovery
,I/wpa_supplicant( 1026): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:ff:f0
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=3a:94:96:b5:06:dd
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5145","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3311): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5145","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3311): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3311): Local service added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service requests cleared successfully
,I/wpa_supplicant( 1026): P2P-FIND-STOPPED 
I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Peer discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 6 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: Galaxy S5-2 3a:94:96:b5:06:dd
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 2: XT1039_8c05 f4:f1:e1:5c:43:c8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 3: Android_50a5 fa:cf:c5:d9:e5:62
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 4: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 5: Thali Test's G2 36:fc:ef:de:0a:e2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): startServiceDiscovery: Invalid state, try calling restart()
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 6 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: Galaxy S5-2 3a:94:96:b5:06:dd
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 2: XT1039_8c05 f4:f1:e1:5c:43:c8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 3: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 4: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 5: Thali Test's G2 36:fc:ef:de:0a:e2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 6 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: Galaxy S5-2 3a:94:96:b5:06:dd
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 2: XT1039_8c05 f4:f1:e1:5c:43:c8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 3: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 4: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 5: Thali Test's G2 36:fc:ef:de:0a:e2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 6 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: Galaxy S5-2 3a:94:96:b5:06:dd
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 2: XT1039_8c05 f4:f1:e1:5c:43:c8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 3: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 4: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 5: Thali Test's G2 36:fc:ef:de:0a:e2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): startServiceDiscovery: Invalid state, try calling restart()
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): restart: Restarting...
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service requests cleared successfully
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Peer discovery stopped successfully
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): start: Starting peer discovery...
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1026): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3311): Ignored { when=-9ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service request added successfully
D/WifiP2pManager( 3311): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service request added successfully
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 2: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3311): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service request added successfully
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 1026): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: Got empty list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1026): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): stopServiceDiscovery
,I/wpa_supplicant( 1026): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Peer discovery stopped successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): start: Starting peer discovery...
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: Android_63cc 82:01:84:6b:e8:5d
,D/WifiP2pManager( 3311): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service request added successfully
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 3: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 3: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 3: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 3311): Ignored { when=-3ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service request added successfully
D/WifiP2pManager( 3311): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service request added successfully
D/WifiP2pManager( 3311): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service request added successfully
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1026): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1026): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT6503","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT6503 F8:95:C7:87:85:54]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT6503","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT6503","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT6503","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3311): onPeerDiscovered: Bluetooth address: F8:95:C7:87:85:54, peer name: LGE-LG-D722_PT6503, peer ID: F8:95:C7:87:85:54, Wi-Fi Direct device name: G3s-1, Wi-Fi Direct address: a2:39:f7:70:12:80
I/io.jxcore.node.ConnectionHelper( 3311): addNewPeerToListAndNotify: Peer with ID F8:95:C7:87:85:54 already in the list
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT9986"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Resolved peer properties: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT9986 00:F4:6F:30:E0:6C]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: 2 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT9986"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT9986"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT9986"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3311): onPeerDiscovered: Bluetooth address: 00:F4:6F:30:E0:6C, peer name: samsung-SM-G800F_PT9986, peer ID: 00:F4:6F:30:E0:6C, Wi-Fi Direct device name: S5mini-1, Wi-Fi Direct address: 02:f4:6f:30:e0:6d
I/io.jxcore.node.ConnectionHelper( 3311): addNewPeerToListAndNotify: Peer with ID 00:F4:6F:30:E0:6C already in the list
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list containing 2 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT5619","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5619 08:EC:A9:50:75:41]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: 3 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT5619","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT5619","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT5619","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/io.jxcore.node.ConnectionHelper( 3311): onPeerDiscovered: Bluetooth address: 08:EC:A9:50:75:41, peer name: samsung-SM-A300FU_PT5619, peer ID: 08:EC:A9:50:75:41, Wi-Fi Direct device name: A3-1, Wi-Fi Direct address: 0a:ec:a9:50:75:42
I/io.jxcore.node.ConnectionHelper( 3311): addNewPeerToListAndNotify: Peer with ID 08:EC:A9:50:75:41 already in the list
,W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list containing 3 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): stopServiceDiscovery
,I/wpa_supplicant( 1026): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5145","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3311): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5145","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3311): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Peer discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3311): Local service added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service requests cleared successfully
,I/wpa_supplicant( 1026): P2P-FIND-STOPPED 
I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Peer discovery stopped successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): restart: Restarting...
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Peer discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Peer discovery started successfully
I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
,D/WifiP2pManager( 3311): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service request added successfully
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
,D/WifiP2pManager( 3311): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service request added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): stopServiceDiscovery
,I/wpa_supplicant( 1026): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Peer discovery stopped successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): start: Starting peer discovery...
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
,D/WifiP2pManager( 3311): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service request added successfully
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 2: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 2: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
,D/WifiP2pManager( 3311): Ignored { when=-9ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service request added successfully
D/WifiP2pManager( 3311): Ignored { when=-3ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service request added successfully
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 2: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 3: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
,D/WifiP2pManager( 3311): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service request added successfully
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 1975): info:x10
,D/        ( 1975): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,I/wpa_supplicant( 1026): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: Got empty list
,I/BTConnectionReceiver( 1362): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1362): Bluetooth Device Name: G3s-1
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1026): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/BluetoothBondStateMachine( 1975): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1
E/bt-btif ( 1975): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 1975): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 1975): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 1975): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
,D/BluetoothAdapterProperties( 1975): Failed to remove device: F8:95:C7:87:85:54
,I/BluetoothBondStateMachine( 1975): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 1975): StableState(): Entering Off State
,W/bt-btif ( 1975): new conn_srvc id:26, app_id:255
W/bt-btif ( 1975): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 1975): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3311): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3311): Incoming connection initialized (thread ID: 336)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3311): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3311): Entering thread (ID: 336)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3311): onBytesRead: Read 77 bytes successfully (thread ID: 336)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3311): Got valid identity from [F8:95:C7:87:85:54 LGE-LG-D722_PT6503 F8:95:C7:87:85:54]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3311): onBytesWritten: 77 bytes successfully written (thread ID: 336)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3311): removeThreadFromList: Removing thread with ID 336
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3311): Handshake thread disposed (thread ID: 336)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3311): onIncomingConnectionConnected: [F8:95:C7:87:85:54 LGE-LG-D722_PT6503 F8:95:C7:87:85:54]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onConnected: [F8:95:C7:87:85:54 LGE-LG-D722_PT6503 F8:95:C7:87:85:54]
I/io.jxcore.node.ConnectionHelper( 3311): onConnected: Incoming connection, peer ID: F8:95:C7:87:85:54, name: LGE-LG-D722_PT6503, Bluetooth address: F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 3311): hasConnection: No connection with peer with ID F8:95:C7:87:85:54
I/io.jxcore.node.ConnectionHelper( 3311): addNewPeerToListAndNotify: Peer with ID F8:95:C7:87:85:54 already in the list
I/io.jxcore.node.ConnectionHelper( 3311): onConnected: Incoming socket thread, for peer with ID F8:95:C7:87:85:54, created successfully
D/io.jxcore.node.ConnectionHelper( 3311): onConnected: The total number of connections is now 1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3311): Exiting thread (ID: 336)
,D/io.jxcore.node.IncomingSocketThread( 3311): Entering thread (ID: 337)
,I/jxcore-log( 3311): 2015-12-15T04:12:37.406Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3311): 
,I/io.jxcore.node.IncomingSocketThread( 3311): Local host address: localhost/127.0.0.1, port: 40224
D/io.jxcore.node.IncomingSocketThread( 3311): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3311): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3311): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3311): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3311): Exiting thread (ID: 337)
,I/io.jxcore.node.StreamCopyingThread( 3311): Entering thread (ID: 338, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 3311): Entering thread (ID: 339, name: Receiver)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT1658","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Resolved peer properties: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT1658 F8:CF:C5:D9:E5:61]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
I/io.jxcore.node.ConnectionHelper( 3311): onPeerDiscovered: Bluetooth address: F8:CF:C5:D9:E5:61, peer name: motorola-Nexus 6_PT1658, peer ID: F8:CF:C5:D9:E5:61, Wi-Fi Direct device name: Android_50a5, Wi-Fi Direct address: fa:cf:c5:d9:e5:62
I/io.jxcore.node.ConnectionHelper( 3311): addNewPeerToListAndNotify: Peer with ID F8:CF:C5:D9:E5:61 already in the list
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT1658","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT1658","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT1658","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/wpa_supplicant( 1026): p2p0: P2P: Reject scan trigger since one is already pending
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: Got empty list
I/wpa_supplicant( 1026): p2p0: P2P: Reject scan trigger since one is already pending
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: Got empty list
,I/jxcore-log( 3311): 2015-12-15T04:12:38.561Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:12:38.572Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:12:38.611Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:12:38.613Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:12:38.643Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:12:38.684Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:12:38.687Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:12:38.691Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:12:38.699Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:12:38.702Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:12:38.734Z SendDataTCPServer.js: TCP/IP server has received 35640 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:12:38.738Z SendDataTCPServer.js: TCP/IP server has received 37620 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:12:38.742Z SendDataTCPServer.js: TCP/IP server has received 39600 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:12:38.746Z SendDataTCPServer.js: TCP/IP server has received 41580 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:12:38.750Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:12:38.784Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:12:38.792Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:12:38.825Z SendDataTCPServer.js: TCP/IP server has received 55440 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:12:38.832Z SendDataTCPServer.js: TCP/IP server has received 57420 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:12:38.836Z SendDataTCPServer.js: TCP/IP server has received 59400 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:12:38.868Z SendDataTCPServer.js: TCP/IP server has received 61380 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:12:38.874Z SendDataTCPServer.js: TCP/IP server has received 63360 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:12:38.907Z SendDataTCPServer.js: TCP/IP server has received 65340 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:12:38.913Z SendDataTCPServer.js: TCP/IP server has received 67320 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:12:38.919Z SendDataTCPServer.js: TCP/IP server has received 69300 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:12:38.923Z SendDataTCPServer.js: TCP/IP server has received 71280 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:12:38.931Z SendDataTCPServer.js: TCP/IP server has received 73260 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:12:38.967Z SendDataTCPServer.js: TCP/IP server has received 87120 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:12:38.996Z SendDataTCPServer.js: TCP/IP server has received 89100 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:12:39.006Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:12:39.039Z SendDataTCPServer.js: TCP/IP server has received 95040 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:12:39.047Z SendDataTCPServer.js: TCP/IP server has received 97020 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:12:39.055Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3311): 
,W/bt-btif ( 1975): invalid rfc slot id: 11
,W/io.jxcore.node.StreamCopyingThread( 3311): Either failed to read from the output stream or write to the input stream (thread ID: 339, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 3311): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3311): onDisconnected: Incoming connection, peer with ID F8:95:C7:87:85:54 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3311): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 337
I/io.jxcore.node.IncomingSocketThread( 3311): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3311): doStop: Thread ID: 339
I/io.jxcore.node.IncomingSocketThread( 3311): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3311): doStop: Thread ID: 338
I/io.jxcore.node.IncomingSocketThread( 3311): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.IncomingSocketThread( 3311): closeLocalSocketAndStreams: Closing the local input stream...
I/io.jxcore.node.IncomingSocketThread( 3311): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.IncomingSocketThread( 3311): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3311): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3311): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3311): Exiting thread (ID: 339, name: Receiver)
,W/io.jxcore.node.StreamCopyingThread( 3311): Either failed to read from the output stream or write to the input stream (thread ID: 338, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3311): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3311): onDisconnected: Incoming connection, peer with ID F8:95:C7:87:85:54 disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.ConnectionHelper( 3311): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3311): Exiting thread (ID: 338, name: Sender)
I/jxcore-log( 3311): 2015-12-15T04:12:39.142Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3311): 
W/bt-rfcomm( 1975): rfc_find_lcid_mcb LCID reused LCID:0x4a current:0x0
W/bt-rfcomm( 1975): RFCOMM_DisconnectInd LCID:0x4a
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT1658","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Resolved peer properties: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT1658 F8:CF:C5:D9:E5:61]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT1658","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT1658","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT1658","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp.local."
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/io.jxcore.node.ConnectionHelper( 3311): onPeerDiscovered: Bluetooth address: F8:CF:C5:D9:E5:61, peer name: motorola-Nexus 6_PT1658, peer ID: F8:CF:C5:D9:E5:61, Wi-Fi Direct device name: Android_50a5, Wi-Fi Direct address: fa:cf:c5:d9:e5:62
,I/io.jxcore.node.ConnectionHelper( 3311): addNewPeerToListAndNotify: Peer with ID F8:CF:C5:D9:E5:61 already in the list
,W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT9986"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Resolved peer properties: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT9986 00:F4:6F:30:E0:6C]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: 2 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT9986"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT9986"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT9986"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3311): onPeerDiscovered: Bluetooth address: 00:F4:6F:30:E0:6C, peer name: samsung-SM-G800F_PT9986, peer ID: 00:F4:6F:30:E0:6C, Wi-Fi Direct device name: S5mini-1, Wi-Fi Direct address: 02:f4:6f:30:e0:6d
I/io.jxcore.node.ConnectionHelper( 3311): addNewPeerToListAndNotify: Peer with ID 00:F4:6F:30:E0:6C already in the list
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list containing 2 peer(s), but doing nothing with that list
,E/bt-btm  ( 1975): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 1975): onReceive
,I/BTConnectionReceiver( 1362): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1362): Bluetooth Device Name: G3s-1
,D/btif_config_util( 1975): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 1975): info:x10
,D/        ( 1975): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 1975): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/BluetoothBondStateMachine( 1975): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:76:27 newState: 1
E/bt-btif ( 1975): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 1975): Bond State Change Intent:08:EC:A9:50:76:27 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 1975): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 1975): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:76:27 newState: 0
,D/BluetoothAdapterProperties( 1975): Failed to remove device: 08:EC:A9:50:76:27
,I/BluetoothBondStateMachine( 1975): Bond State Change Intent:08:EC:A9:50:76:27 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 1975): StableState(): Entering Off State
,W/bt-btif ( 1975): new conn_srvc id:26, app_id:255
W/bt-btif ( 1975): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 1975): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3311): Incoming connection accepted
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3311): Incoming connection initialized (thread ID: 340)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3311): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3311): Entering thread (ID: 340)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3311): onBytesRead: Read 83 bytes successfully (thread ID: 340)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3311): Got valid identity from [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6932 08:EC:A9:50:76:27]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3311): onBytesWritten: 77 bytes successfully written (thread ID: 340)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3311): removeThreadFromList: Removing thread with ID 340
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3311): Handshake thread disposed (thread ID: 340)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3311): onIncomingConnectionConnected: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6932 08:EC:A9:50:76:27]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3311): Exiting thread (ID: 340)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onConnected: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6932 08:EC:A9:50:76:27]
I/io.jxcore.node.ConnectionHelper( 3311): onConnected: Incoming connection, peer ID: 08:EC:A9:50:76:27, name: samsung-SM-A300FU_PT6932, Bluetooth address: 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 3311): hasConnection: No connection with peer with ID 08:EC:A9:50:76:27
I/io.jxcore.node.ConnectionHelper( 3311): addNewPeerToListAndNotify: Peer with ID 08:EC:A9:50:76:27 already in the list
I/io.jxcore.node.ConnectionHelper( 3311): onConnected: Incoming socket thread, for peer with ID 08:EC:A9:50:76:27, created successfully
D/io.jxcore.node.ConnectionHelper( 3311): onConnected: The total number of connections is now 1
,D/io.jxcore.node.IncomingSocketThread( 3311): Entering thread (ID: 341)
,I/jxcore-log( 3311): 2015-12-15T04:12:49.441Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3311): 
,I/io.jxcore.node.IncomingSocketThread( 3311): Local host address: localhost/127.0.0.1, port: 40224
D/io.jxcore.node.IncomingSocketThread( 3311): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3311): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3311): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3311): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3311): Exiting thread (ID: 341)
,I/io.jxcore.node.StreamCopyingThread( 3311): Entering thread (ID: 342, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 3311): Entering thread (ID: 343, name: Receiver)
,I/jxcore-log( 3311): 2015-12-15T04:12:50.385Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:12:50.393Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:12:50.401Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:12:50.415Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:12:50.422Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:12:50.433Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:12:50.513Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:12:50.541Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:12:50.562Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:12:50.571Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:12:50.955Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:12:51.005Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:12:51.082Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:12:51.096Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:12:51.107Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:12:51.122Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:12:51.176Z SendDataTCPServer.js: TCP/IP server has received 35640 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:12:51.236Z SendDataTCPServer.js: TCP/IP server has received 37620 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:12:51.247Z SendDataTCPServer.js: TCP/IP server has received 39600 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:12:51.291Z SendDataTCPServer.js: TCP/IP server has received 41580 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:12:51.345Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:12:51.401Z SendDataTCPServer.js: TCP/IP server has received 45540 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:12:51.431Z SendDataTCPServer.js: TCP/IP server has received 47520 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:12:51.466Z SendDataTCPServer.js: TCP/IP server has received 49500 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:12:51.603Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:12:51.620Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:12:51.682Z SendDataTCPServer.js: TCP/IP server has received 55440 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:12:51.696Z SendDataTCPServer.js: TCP/IP server has received 57420 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:12:51.759Z SendDataTCPServer.js: TCP/IP server has received 59400 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:12:51.791Z SendDataTCPServer.js: TCP/IP server has received 61380 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:12:51.852Z SendDataTCPServer.js: TCP/IP server has received 63360 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:12:51.885Z SendDataTCPServer.js: TCP/IP server has received 71280 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:12:51.900Z SendDataTCPServer.js: TCP/IP server has received 73260 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:12:51.935Z SendDataTCPServer.js: TCP/IP server has received 77220 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:12:52.237Z SendDataTCPServer.js: TCP/IP server has received 79200 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:12:52.254Z SendDataTCPServer.js: TCP/IP server has received 81180 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:12:52.264Z SendDataTCPServer.js: TCP/IP server has received 83160 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:12:52.297Z SendDataTCPServer.js: TCP/IP server has received 85140 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:12:52.324Z SendDataTCPServer.js: TCP/IP server has received 87120 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:12:52.347Z SendDataTCPServer.js: TCP/IP server has received 89100 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:12:52.354Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:12:52.368Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:12:52.405Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3311): 
,W/bt-btif ( 1975): invalid rfc slot id: 16
,W/io.jxcore.node.StreamCopyingThread( 3311): Either failed to read from the output stream or write to the input stream (thread ID: 343, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 3311): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3311): onDisconnected: Incoming connection, peer with ID 08:EC:A9:50:76:27 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3311): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 341
I/io.jxcore.node.IncomingSocketThread( 3311): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3311): doStop: Thread ID: 343
I/io.jxcore.node.IncomingSocketThread( 3311): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3311): doStop: Thread ID: 342
I/io.jxcore.node.IncomingSocketThread( 3311): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.IncomingSocketThread( 3311): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3311): Either failed to read from the output stream or write to the input stream (thread ID: 342, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3311): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3311): onDisconnected: Incoming connection, peer with ID 08:EC:A9:50:76:27 disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,W/bt-rfcomm( 1975): rfc_find_lcid_mcb LCID reused LCID:0x4d current:0x0
W/bt-rfcomm( 1975): RFCOMM_DisconnectInd LCID:0x4d
,I/io.jxcore.node.IncomingSocketThread( 3311): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.IncomingSocketThread( 3311): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3311): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3311): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3311): Exiting thread (ID: 343, name: Receiver)
,D/io.jxcore.node.ConnectionHelper( 3311): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3311): Exiting thread (ID: 342, name: Sender)
,I/jxcore-log( 3311): 2015-12-15T04:12:52.498Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3311): 
,D/btif_config_util( 1975): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 1975): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 1975): onReceive
,I/BTConnectionReceiver( 1362): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1362): Bluetooth Device Name: Thali Test (Galaxy A3)
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): stopServiceDiscovery
,I/wpa_supplicant( 1026): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5145","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3311): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5145","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): initialize: Success
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3311): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3311): Local service added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service requests cleared successfully
,I/wpa_supplicant( 1026): P2P-FIND-STOPPED 
I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Peer discovery stopped successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
,W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Peer discovery stopped successfully
,W/bt-btif ( 1975): info:x10
,D/        ( 1975): remote version info [f8:cf:c5:d9:e5:61]: 7, f, 230f
,E/BluetoothRemoteDevices( 1975): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 1975): bondStateChangeCallback: Status: 0 Address: F8:CF:C5:D9:E5:61 newState: 1
E/bt-btif ( 1975): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 1975): Bond State Change Intent:F8:CF:C5:D9:E5:61 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 1975): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 1975): bondStateChangeCallback: Status: 0 Address: F8:CF:C5:D9:E5:61 newState: 0
,D/BluetoothAdapterProperties( 1975): Failed to remove device: F8:CF:C5:D9:E5:61
,I/BluetoothBondStateMachine( 1975): Bond State Change Intent:F8:CF:C5:D9:E5:61 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 1975): StableState(): Entering Off State
,W/bt-btif ( 1975): new conn_srvc id:26, app_id:255
W/bt-btif ( 1975): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 1975): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3311): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3311): Incoming connection initialized (thread ID: 344)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3311): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3311): Entering thread (ID: 344)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3311): onBytesRead: Read 82 bytes successfully (thread ID: 344)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3311): Got valid identity from [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT1658 F8:CF:C5:D9:E5:61]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3311): onBytesWritten: 77 bytes successfully written (thread ID: 344)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3311): removeThreadFromList: Removing thread with ID 344
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3311): Handshake thread disposed (thread ID: 344)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3311): onIncomingConnectionConnected: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT1658 F8:CF:C5:D9:E5:61]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3311): Exiting thread (ID: 344)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onConnected: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT1658 F8:CF:C5:D9:E5:61]
I/io.jxcore.node.ConnectionHelper( 3311): onConnected: Incoming connection, peer ID: F8:CF:C5:D9:E5:61, name: motorola-Nexus 6_PT1658, Bluetooth address: F8:CF:C5:D9:E5:61
D/io.jxcore.node.ConnectionHelper( 3311): hasConnection: No connection with peer with ID F8:CF:C5:D9:E5:61
I/io.jxcore.node.ConnectionHelper( 3311): addNewPeerToListAndNotify: Peer with ID F8:CF:C5:D9:E5:61 already in the list
I/io.jxcore.node.ConnectionHelper( 3311): onConnected: Incoming socket thread, for peer with ID F8:CF:C5:D9:E5:61, created successfully
D/io.jxcore.node.ConnectionHelper( 3311): onConnected: The total number of connections is now 1
,D/io.jxcore.node.IncomingSocketThread( 3311): Entering thread (ID: 345)
,I/io.jxcore.node.IncomingSocketThread( 3311): Local host address: localhost/127.0.0.1, port: 40224
D/io.jxcore.node.IncomingSocketThread( 3311): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3311): setBufferSize: Setting buffer size to 8192 bytes
,I/jxcore-log( 3311): 2015-12-15T04:13:38.182Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3311): 
,I/io.jxcore.node.StreamCopyingThread( 3311): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3311): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3311): Exiting thread (ID: 345)
,I/io.jxcore.node.StreamCopyingThread( 3311): Entering thread (ID: 347, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 3311): Entering thread (ID: 346, name: Sender)
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: S5mini-1 02:f4:6f:30:e0:6d
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): startServiceDiscovery: Invalid state, try calling restart()
,I/jxcore-log( 3311): 2015-12-15T04:13:39.038Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:13:39.045Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:13:39.059Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:13:39.071Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:13:39.085Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:13:39.098Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:13:39.137Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:13:39.149Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:13:39.190Z SendDataTCPServer.js: TCP/IP server has received 38708 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:13:39.204Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:13:39.212Z SendDataTCPServer.js: TCP/IP server has received 42668 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:13:39.245Z SendDataTCPServer.js: TCP/IP server has received 56528 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:13:39.258Z SendDataTCPServer.js: TCP/IP server has received 60488 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:13:39.297Z SendDataTCPServer.js: TCP/IP server has received 64448 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:13:39.316Z SendDataTCPServer.js: TCP/IP server has received 66428 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:13:39.324Z SendDataTCPServer.js: TCP/IP server has received 68408 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:13:39.332Z SendDataTCPServer.js: TCP/IP server has received 70388 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:13:39.342Z SendDataTCPServer.js: TCP/IP server has received 72368 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:13:39.351Z SendDataTCPServer.js: TCP/IP server has received 74348 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:13:39.388Z SendDataTCPServer.js: TCP/IP server has received 82268 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:13:39.400Z SendDataTCPServer.js: TCP/IP server has received 88208 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:13:39.407Z SendDataTCPServer.js: TCP/IP server has received 90188 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:13:39.441Z SendDataTCPServer.js: TCP/IP server has received 92168 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:13:39.475Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3311): 
,W/bt-btif ( 1975): invalid rfc slot id: 17
,W/io.jxcore.node.StreamCopyingThread( 3311): Either failed to read from the output stream or write to the input stream (thread ID: 347, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 3311): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3311): onDisconnected: Incoming connection, peer with ID F8:CF:C5:D9:E5:61 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3311): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 345
I/io.jxcore.node.IncomingSocketThread( 3311): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3311): doStop: Thread ID: 347
I/io.jxcore.node.IncomingSocketThread( 3311): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3311): doStop: Thread ID: 346
I/io.jxcore.node.IncomingSocketThread( 3311): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.IncomingSocketThread( 3311): closeLocalSocketAndStreams: Closing the local input stream...
,I/io.jxcore.node.IncomingSocketThread( 3311): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.IncomingSocketThread( 3311): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3311): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3311): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3311): Exiting thread (ID: 347, name: Receiver)
,W/bt-rfcomm( 1975): rfc_find_lcid_mcb LCID reused LCID:0x4e current:0x0
W/bt-rfcomm( 1975): RFCOMM_DisconnectInd LCID:0x4e
,W/io.jxcore.node.StreamCopyingThread( 3311): Either failed to read from the output stream or write to the input stream (thread ID: 346, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3311): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3311): onDisconnected: Incoming connection, peer with ID F8:CF:C5:D9:E5:61 disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.ConnectionHelper( 3311): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3311): Exiting thread (ID: 346, name: Sender)
,I/jxcore-log( 3311): 2015-12-15T04:13:39.560Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3311): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): start: Starting peer discovery...
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,E/bt-btm  ( 1975): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 1975): onReceive
,I/BTConnectionReceiver( 1362): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1362): Bluetooth Device Name: Nexus 6
,D/btif_config_util( 1975): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 2: Android_1950 b6:ce:f6:ad:a4:6b
,D/WifiP2pManager( 3311): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service request added successfully
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 2: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 3: Android_63cc 82:01:84:6b:e8:5d
,D/WifiP2pManager( 3311): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service request added successfully
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: Got empty list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT6734","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6734 E0:DB:10:14:E2:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT6734","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3311): onPeerDiscovered: Bluetooth address: E0:DB:10:14:E2:C0, peer name: samsung-SM-N910C_PT6734, peer ID: E0:DB:10:14:E2:C0, Wi-Fi Direct device name: , Wi-Fi Direct address: 92:b6:86:43:73:1c
,I/io.jxcore.node.ConnectionHelper( 3311): addNewPeerToListAndNotify: Peer with ID E0:DB:10:14:E2:C0 already in the list
,W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT1757"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Resolved peer properties: [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT1757 80:01:84:8A:B3:68]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerDiscovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: 2 services discovered
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT1757"}", service type: "Cordovap2p._tcp.local."
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/io.jxcore.node.ConnectionHelper( 3311): onPeerDiscovered: Bluetooth address: 80:01:84:8A:B3:68, peer name: HTC-HTC Desire 820_PT1757, peer ID: 80:01:84:8A:B3:68, Wi-Fi Direct device name: Android_63cc, Wi-Fi Direct address: 82:01:84:6b:e8:5d
I/io.jxcore.node.ConnectionHelper( 3311): addNewPeerToListAndNotify: Peer with ID 80:01:84:8A:B3:68 already in the list
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list containing 2 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2765"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Resolved peer properties: [B4:CE:F6:AB:A4:6A HTC-HTC Desire 820_PT2765 B4:CE:F6:AB:A4:6A]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: 3 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2765"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/io.jxcore.node.ConnectionHelper( 3311): onPeerDiscovered: Bluetooth address: B4:CE:F6:AB:A4:6A, peer name: HTC-HTC Desire 820_PT2765, peer ID: B4:CE:F6:AB:A4:6A, Wi-Fi Direct device name: Android_1950, Wi-Fi Direct address: b6:ce:f6:ad:a4:6b
,I/io.jxcore.node.ConnectionHelper( 3311): addNewPeerToListAndNotify: Peer with ID B4:CE:F6:AB:A4:6A already in the list
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list containing 3 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT9986"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Resolved peer properties: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT9986 00:F4:6F:30:E0:6C]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: 4 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT9986"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3311): onPeerDiscovered: Bluetooth address: 00:F4:6F:30:E0:6C, peer name: samsung-SM-G800F_PT9986, peer ID: 00:F4:6F:30:E0:6C, Wi-Fi Direct device name: S5mini-1, Wi-Fi Direct address: 02:f4:6f:30:e0:6d
I/io.jxcore.node.ConnectionHelper( 3311): addNewPeerToListAndNotify: Peer with ID 00:F4:6F:30:E0:6C already in the list
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list containing 4 peer(s), but doing nothing with that list
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT6503","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT6503 F8:95:C7:87:85:54]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: 5 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT6503","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3311): onPeerDiscovered: Bluetooth address: F8:95:C7:87:85:54, peer name: LGE-LG-D722_PT6503, peer ID: F8:95:C7:87:85:54, Wi-Fi Direct device name: G3s-1, Wi-Fi Direct address: a2:39:f7:70:12:80
I/io.jxcore.node.ConnectionHelper( 3311): addNewPeerToListAndNotify: Peer with ID F8:95:C7:87:85:54 already in the list
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list containing 5 peer(s), but doing nothing with that list
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1026): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT4197","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4197 F8:95:C7:87:3C:51]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerDiscovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: 6 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT4197","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3311): onPeerDiscovered: Bluetooth address: F8:95:C7:87:3C:51, peer name: LGE-LG-H815_PT4197, peer ID: F8:95:C7:87:3C:51, Wi-Fi Direct device name: G4-1, Wi-Fi Direct address: a2:39:f7:6f:c9:5d
I/io.jxcore.node.ConnectionHelper( 3311): addNewPeerToListAndNotify: Peer with ID F8:95:C7:87:3C:51 already in the list
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list containing 6 peer(s), but doing nothing with that list
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT4039","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4039 7C:F9:0E:51:18:22]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: 7 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT4039","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3311): onPeerDiscovered: Bluetooth address: 7C:F9:0E:51:18:22, peer name: samsung-SM-A500FU_PT4039, peer ID: 7C:F9:0E:51:18:22, Wi-Fi Direct device name: , Wi-Fi Direct address: 7e:f9:0e:51:18:23
I/io.jxcore.node.ConnectionHelper( 3311): addNewPeerToListAndNotify: Peer with ID 7C:F9:0E:51:18:22 already in the list
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list containing 7 peer(s), but doing nothing with that list
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT3932","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3932 7C:F9:0E:37:96:AB]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: 8 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT3932","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3311): onPeerDiscovered: Bluetooth address: 7C:F9:0E:37:96:AB, peer name: samsung-SM-A500FU_PT3932, peer ID: 7C:F9:0E:37:96:AB, Wi-Fi Direct device name: , Wi-Fi Direct address: 7e:f9:0e:37:96:ac
I/io.jxcore.node.ConnectionHelper( 3311): addNewPeerToListAndNotify: Adding peer with ID 7C:F9:0E:37:96:AB
I/jxcore-log( 3311): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:37:96:AB","peerName":"samsung-SM-A500FU_PT3932","peerAvailable":true}]
I/jxcore-log( 3311): 
I/jxcore-log( 3311): Found peer : samsung-SM-A500FU_PT3932, Available: true
I/jxcore-log( 3311): 
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list containing 8 peer(s), but doing nothing with that list
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT9222","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Resolved peer properties: [44:80:EB:7B:5A:05 motorola-XT1072_PT9222 44:80:EB:7B:5A:05]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: 9 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT9222","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3311): onPeerDiscovered: Bluetooth address: 44:80:EB:7B:5A:05, peer name: motorola-XT1072_PT9222, peer ID: 44:80:EB:7B:5A:05, Wi-Fi Direct device name: , Wi-Fi Direct address: 44:80:eb:7b:5a:07
I/io.jxcore.node.ConnectionHelper( 3311): addNewPeerToListAndNotify: Peer with ID 44:80:EB:7B:5A:05 already in the list
,W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list containing 9 peer(s), but doing nothing with that list
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): stopServiceDiscovery
,I/wpa_supplicant( 1026): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5145","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3311): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5145","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3311): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3311): Local service added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service requests cleared successfully
,I/wpa_supplicant( 1026): P2P-FIND-STOPPED 
I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Peer discovery stopped successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Got empty list
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
,W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Peer discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): start: Starting peer discovery...
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: Note3-1 ea:50:8b:de:28:a3
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: Note3-1 ea:50:8b:de:28:a3
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
,D/WifiP2pManager( 3311): Ignored { when=-19ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service request added successfully
D/WifiP2pManager( 3311): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service request added successfully
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1026): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: Note3-1 ea:50:8b:de:28:a3
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 3: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 4: Android_1950 b6:ce:f6:ad:a4:6b
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: Note3-1 ea:50:8b:de:28:a3
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 3: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 4: Android_1950 b6:ce:f6:ad:a4:6b
,D/WifiP2pManager( 3311): Ignored { when=-10ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service request added successfully
D/WifiP2pManager( 3311): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service request added successfully
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 6 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: Note3-1 ea:50:8b:de:28:a3
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 3: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 4: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 5: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 6 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: Note3-1 ea:50:8b:de:28:a3
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 3: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 4: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 5: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 3311): Ignored { when=-9ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service request added successfully
D/WifiP2pManager( 3311): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service request added successfully
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 1026): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: Got empty list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1026): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1026): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT1757"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Resolved peer properties: [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT1757 80:01:84:8A:B3:68]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT1757"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT1757"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT1757"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT1757"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT1757"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3311): onPeerDiscovered: Bluetooth address: 80:01:84:8A:B3:68, peer name: HTC-HTC Desire 820_PT1757, peer ID: 80:01:84:8A:B3:68, Wi-Fi Direct device name: , Wi-Fi Direct address: 82:01:84:6b:e8:5d
I/io.jxcore.node.ConnectionHelper( 3311): addNewPeerToListAndNotify: Peer with ID 80:01:84:8A:B3:68 already in the list
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT1658","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Resolved peer properties: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT1658 F8:CF:C5:D9:E5:61]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: 2 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT1658","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT1658","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT1658","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT1658","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT1658","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3311): onPeerDiscovered: Bluetooth address: F8:CF:C5:D9:E5:61, peer name: motorola-Nexus 6_PT1658, peer ID: F8:CF:C5:D9:E5:61, Wi-Fi Direct device name: Android_50a5, Wi-Fi Direct address: fa:cf:c5:d9:e5:62
I/io.jxcore.node.ConnectionHelper( 3311): addNewPeerToListAndNotify: Peer with ID F8:CF:C5:D9:E5:61 already in the list
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list containing 2 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): stopServiceDiscovery
,I/wpa_supplicant( 1026): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5145","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3311): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5145","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3311): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Peer discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3311): Local service added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service requests cleared successfully
,I/wpa_supplicant( 1026): P2P-FIND-STOPPED 
I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Peer discovery stopped successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): restart: Restarting...
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Peer discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): start: Starting peer discovery...
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3311): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service request added successfully
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3311): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service request added successfully
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 2: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3311): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service request added successfully
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 1026): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2765"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Resolved peer properties: [B4:CE:F6:AB:A4:6A HTC-HTC Desire 820_PT2765 B4:CE:F6:AB:A4:6A]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2765"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2765"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3311): onPeerDiscovered: Bluetooth address: B4:CE:F6:AB:A4:6A, peer name: HTC-HTC Desire 820_PT2765, peer ID: B4:CE:F6:AB:A4:6A, Wi-Fi Direct device name: , Wi-Fi Direct address: b6:ce:f6:ad:a4:6b
I/io.jxcore.node.ConnectionHelper( 3311): addNewPeerToListAndNotify: Peer with ID B4:CE:F6:AB:A4:6A already in the list
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT3932","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3932 7C:F9:0E:37:96:AB]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT3932","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT3932","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3311): onPeerDiscovered: Bluetooth address: 7C:F9:0E:37:96:AB, peer name: samsung-SM-A500FU_PT3932, peer ID: 7C:F9:0E:37:96:AB, Wi-Fi Direct device name: , Wi-Fi Direct address: 7e:f9:0e:37:96:ac
I/io.jxcore.node.ConnectionHelper( 3311): addNewPeerToListAndNotify: Peer with ID 7C:F9:0E:37:96:AB already in the list
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT3623"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Resolved peer properties: [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT3623 F4:F1:E1:5C:3B:E2]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: 2 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT3623"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT3623"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3311): onPeerDiscovered: Bluetooth address: F4:F1:E1:5C:3B:E2, peer name: motorola-XT1039_PT3623, peer ID: F4:F1:E1:5C:3B:E2, Wi-Fi Direct device name: , Wi-Fi Direct address: f4:f1:e1:5c:43:c8
I/io.jxcore.node.ConnectionHelper( 3311): addNewPeerToListAndNotify: Peer with ID F4:F1:E1:5C:3B:E2 already in the list
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list containing 2 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT349"}", service type: "Cordovap2p._tcp.local."
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Resolved peer properties: [34:FC:EF:9D:93:0B LGE-LG-D802_PT349 34:FC:EF:9D:93:0B]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: 3 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT349"}", service type: "Cordovap2p._tcp.local."
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT349"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/io.jxcore.node.ConnectionHelper( 3311): onPeerDiscovered: Bluetooth address: 34:FC:EF:9D:93:0B, peer name: LGE-LG-D802_PT349, peer ID: 34:FC:EF:9D:93:0B, Wi-Fi Direct device name: , Wi-Fi Direct address: 36:fc:ef:de:0a:e2
I/io.jxcore.node.ConnectionHelper( 3311): addNewPeerToListAndNotify: Peer with ID 34:FC:EF:9D:93:0B already in the list
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list containing 3 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): stopServiceDiscovery
,I/wpa_supplicant( 1026): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5145","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3311): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5145","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3311): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3311): Local service added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started,
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service requests cleared successfully
,I/wpa_supplicant( 1026): P2P-FIND-STOPPED 
I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Peer discovery stopped successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): restart: Restarting...
,W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Peer discovery stopped successfully
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): startServiceDiscovery: Invalid state, try calling restart()
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): start: Starting peer discovery...
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 2: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 3311): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service request added successfully
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/EventLogService( 1633): Aggregate from 1450151195915 (log), 1450151195915 (data)
,I/GoogleURLConnFactory( 1576): Using platform SSLCertificateSocketFactory
,I/PhenotypeConfigurator( 1576): Scheduling Phenotype every 14400 seconds, with flex of 1800 seconds
,W/PhenotypeConfigurator( 1576): Server returned 404
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): stopServiceDiscovery
,I/wpa_supplicant( 1026): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Peer discovery stopped successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): start: Starting peer discovery...
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
,D/WifiP2pManager( 3311): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service request added successfully
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
,D/WifiP2pManager( 3311): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service request added successfully
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 2: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
,D/WifiP2pManager( 3311): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service request added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1026): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: Got empty list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT4197","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4197 F8:95:C7:87:3C:51]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT4197","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT4197","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3311): onPeerDiscovered: Bluetooth address: F8:95:C7:87:3C:51, peer name: LGE-LG-H815_PT4197, peer ID: F8:95:C7:87:3C:51, Wi-Fi Direct device name: , Wi-Fi Direct address: a2:39:f7:6f:c9:5d
I/io.jxcore.node.ConnectionHelper( 3311): addNewPeerToListAndNotify: Peer with ID F8:95:C7:87:3C:51 already in the list
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT9986"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Resolved peer properties: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT9986 00:F4:6F:30:E0:6C]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: 2 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT9986"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT9986"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3311): onPeerDiscovered: Bluetooth address: 00:F4:6F:30:E0:6C, peer name: samsung-SM-G800F_PT9986, peer ID: 00:F4:6F:30:E0:6C, Wi-Fi Direct device name: S5mini-1, Wi-Fi Direct address: 02:f4:6f:30:e0:6d
I/io.jxcore.node.ConnectionHelper( 3311): addNewPeerToListAndNotify: Peer with ID 00:F4:6F:30:E0:6C already in the list
,W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list containing 2 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT1757"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Resolved peer properties: [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT1757 80:01:84:8A:B3:68]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: 3 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT1757"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT1757"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3311): onPeerDiscovered: Bluetooth address: 80:01:84:8A:B3:68, peer name: HTC-HTC Desire 820_PT1757, peer ID: 80:01:84:8A:B3:68, Wi-Fi Direct device name: Android_63cc, Wi-Fi Direct address: 82:01:84:6b:e8:5d
I/io.jxcore.node.ConnectionHelper( 3311): addNewPeerToListAndNotify: Peer with ID 80:01:84:8A:B3:68 already in the list
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list containing 3 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6932","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6932 08:EC:A9:50:76:27]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: 4 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6932","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6932","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3311): onPeerDiscovered: Bluetooth address: 08:EC:A9:50:76:27, peer name: samsung-SM-A300FU_PT6932, peer ID: 08:EC:A9:50:76:27, Wi-Fi Direct device name: , Wi-Fi Direct address: 0a:ec:a9:50:76:28
I/io.jxcore.node.ConnectionHelper( 3311): addNewPeerToListAndNotify: Peer with ID 08:EC:A9:50:76:27 already in the list
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list containing 4 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT349"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Resolved peer properties: [34:FC:EF:9D:93:0B LGE-LG-D802_PT349 34:FC:EF:9D:93:0B]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: 5 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT349"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT349"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3311): onPeerDiscovered: Bluetooth address: 34:FC:EF:9D:93:0B, peer name: LGE-LG-D802_PT349, peer ID: 34:FC:EF:9D:93:0B, Wi-Fi Direct device name: , Wi-Fi Direct address: 36:fc:ef:de:0a:e2
I/io.jxcore.node.ConnectionHelper( 3311): addNewPeerToListAndNotify: Peer with ID 34:FC:EF:9D:93:0B already in the list
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list containing 5 peer(s), but doing nothing with that list
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT3932","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3932 7C:F9:0E:37:96:AB]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: 6 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT3932","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT3932","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/io.jxcore.node.ConnectionHelper( 3311): onPeerDiscovered: Bluetooth address: 7C:F9:0E:37:96:AB, peer name: samsung-SM-A500FU_PT3932, peer ID: 7C:F9:0E:37:96:AB, Wi-Fi Direct device name: , Wi-Fi Direct address: 7e:f9:0e:37:96:ac
I/io.jxcore.node.ConnectionHelper( 3311): addNewPeerToListAndNotify: Peer with ID 7C:F9:0E:37:96:AB already in the list
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list containing 6 peer(s), but doing nothing with that list
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT1658","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Resolved peer properties: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT1658 F8:CF:C5:D9:E5:61]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: 7 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT1658","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT1658","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/io.jxcore.node.ConnectionHelper( 3311): onPeerDiscovered: Bluetooth address: F8:CF:C5:D9:E5:61, peer name: motorola-Nexus 6_PT1658, peer ID: F8:CF:C5:D9:E5:61, Wi-Fi Direct device name: , Wi-Fi Direct address: fa:cf:c5:d9:e5:62
I/io.jxcore.node.ConnectionHelper( 3311): addNewPeerToListAndNotify: Peer with ID F8:CF:C5:D9:E5:61 already in the list
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list containing 7 peer(s), but doing nothing with that list
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1026): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): stopServiceDiscovery
,I/wpa_supplicant( 1026): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5145","ra":"34:FC:EF:11:AE:67"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3311): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5145","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3311): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3311): Local service added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service requests cleared successfully
,I/wpa_supplicant( 1026): P2P-FIND-STOPPED 
I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Peer discovery stopped successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): restart: Restarting...
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Peer discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): start: Starting peer discovery...
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1,
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
,D/WifiP2pManager( 3311): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service request added successfully
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 3311): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service request added successfully
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1026): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT4039","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4039 7C:F9:0E:51:18:22]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT4039","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3311): onPeerDiscovered: Bluetooth address: 7C:F9:0E:51:18:22, peer name: samsung-SM-A500FU_PT4039, peer ID: 7C:F9:0E:51:18:22, Wi-Fi Direct device name: Thali Test (Galaxy A5), Wi-Fi Direct address: 7e:f9:0e:51:18:23
I/io.jxcore.node.ConnectionHelper( 3311): addNewPeerToListAndNotify: Peer with ID 7C:F9:0E:51:18:22 already in the list
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT6734","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6734 E0:DB:10:14:E2:C0]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerDiscovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: 2 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT6734","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3311): onPeerDiscovered: Bluetooth address: E0:DB:10:14:E2:C0, peer name: samsung-SM-N910C_PT6734, peer ID: E0:DB:10:14:E2:C0, Wi-Fi Direct device name: , Wi-Fi Direct address: 92:b6:86:43:73:1c
I/io.jxcore.node.ConnectionHelper( 3311): addNewPeerToListAndNotify: Peer with ID E0:DB:10:14:E2:C0 already in the list
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list containing 2 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT4197","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4197 F8:95:C7:87:3C:51]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: 3 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT4197","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3311): onPeerDiscovered: Bluetooth address: F8:95:C7:87:3C:51, peer name: LGE-LG-H815_PT4197, peer ID: F8:95:C7:87:3C:51, Wi-Fi Direct device name: , Wi-Fi Direct address: a2:39:f7:6f:c9:5d
I/io.jxcore.node.ConnectionHelper( 3311): addNewPeerToListAndNotify: Peer with ID F8:95:C7:87:3C:51 already in the list
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list containing 3 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT5619","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5619 08:EC:A9:50:75:41]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: 4 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT5619","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3311): onPeerDiscovered: Bluetooth address: 08:EC:A9:50:75:41, peer name: samsung-SM-A300FU_PT5619, peer ID: 08:EC:A9:50:75:41, Wi-Fi Direct device name: A3-1, Wi-Fi Direct address: 0a:ec:a9:50:75:42
I/io.jxcore.node.ConnectionHelper( 3311): addNewPeerToListAndNotify: Peer with ID 08:EC:A9:50:75:41 already in the list
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list containing 4 peer(s), but doing nothing with that list
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 1975): info:x10
,D/        ( 1975): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 230f
,I/BTConnectionReceiver( 1362): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1362): Bluetooth Device Name: S5-1
,W/bt-btif ( 1975): new conn_srvc id:26, app_id:255
W/bt-btif ( 1975): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 1975): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3311): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3311): Incoming connection initialized (thread ID: 348)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3311): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3311): Entering thread (ID: 348)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3311): onBytesRead: Read 82 bytes successfully (thread ID: 348)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3311): Got valid identity from [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT5051 7C:F9:0E:34:8A:A0]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3311): onBytesWritten: 77 bytes successfully written (thread ID: 348)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3311): removeThreadFromList: Removing thread with ID 348
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3311): Handshake thread disposed (thread ID: 348)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3311): onIncomingConnectionConnected: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT5051 7C:F9:0E:34:8A:A0]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3311): Exiting thread (ID: 348)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onConnected: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT5051 7C:F9:0E:34:8A:A0]
I/io.jxcore.node.ConnectionHelper( 3311): onConnected: Incoming connection, peer ID: 7C:F9:0E:34:8A:A0, name: samsung-SM-G900F_PT5051, Bluetooth address: 7C:F9:0E:34:8A:A0
D/io.jxcore.node.ConnectionHelper( 3311): hasConnection: No connection with peer with ID 7C:F9:0E:34:8A:A0
I/io.jxcore.node.ConnectionHelper( 3311): addNewPeerToListAndNotify: Peer with ID 7C:F9:0E:34:8A:A0 already in the list
I/io.jxcore.node.ConnectionHelper( 3311): onConnected: Incoming socket thread, for peer with ID 7C:F9:0E:34:8A:A0, created successfully
D/io.jxcore.node.ConnectionHelper( 3311): onConnected: The total number of connections is now 1
,D/io.jxcore.node.IncomingSocketThread( 3311): Entering thread (ID: 349)
,I/io.jxcore.node.IncomingSocketThread( 3311): Local host address: localhost/127.0.0.1, port: 40224
D/io.jxcore.node.IncomingSocketThread( 3311): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3311): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3311): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.IncomingSocketThread( 3311): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3311): Exiting thread (ID: 349)
,I/jxcore-log( 3311): 2015-12-15T04:19:27.222Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3311): 
,I/io.jxcore.node.StreamCopyingThread( 3311): Entering thread (ID: 350, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 3311): Entering thread (ID: 351, name: Receiver)
,I/jxcore-log( 3311): 2015-12-15T04:19:28.252Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:19:28.261Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:19:28.340Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:19:28.423Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:19:28.495Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:19:28.511Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:19:28.545Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:19:28.573Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:19:28.604Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:19:28.669Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:19:28.706Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:19:28.735Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3311): 
I/jxcore-log( 3311): 2015-12-15T04:19:28.738Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:19:28.784Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:19:28.826Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:19:28.856Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:19:28.866Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:19:28.905Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:19:28.913Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:19:28.945Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:19:28.952Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:19:28.971Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:19:28.981Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:19:28.991Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:19:29.027Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:19:29.034Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:19:29.050Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:19:29.087Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:19:29.096Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:19:29.161Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:19:29.196Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:19:29.236Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:19:29.242Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:19:29.365Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:19:29.472Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:19:29.536Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:19:29.542Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:19:29.635Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3311): 
,W/bt-btif ( 1975): invalid rfc slot id: 18
,W/io.jxcore.node.StreamCopyingThread( 3311): Either failed to read from the output stream or write to the input stream (thread ID: 351, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 3311): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3311): onDisconnected: Incoming connection, peer with ID 7C:F9:0E:34:8A:A0 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3311): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 349
I/io.jxcore.node.IncomingSocketThread( 3311): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3311): doStop: Thread ID: 351
I/io.jxcore.node.IncomingSocketThread( 3311): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3311): doStop: Thread ID: 350
I/io.jxcore.node.IncomingSocketThread( 3311): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.IncomingSocketThread( 3311): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3311): Either failed to read from the output stream or write to the input stream (thread ID: 350, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3311): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3311): onDisconnected: Incoming connection, peer with ID 7C:F9:0E:34:8A:A0 disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.IncomingSocketThread( 3311): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.IncomingSocketThread( 3311): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3311): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3311): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3311): Exiting thread (ID: 351, name: Receiver)
,D/io.jxcore.node.ConnectionHelper( 3311): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,I/io.jxcore.node.StreamCopyingThread( 3311): Exiting thread (ID: 350, name: Sender)
,I/jxcore-log( 3311): 2015-12-15T04:19:29.831Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3311): 
,D/btif_config_util( 1975): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-rfcomm( 1975): rfc_find_lcid_mcb LCID reused LCID:0x41 current:0x0
W/bt-rfcomm( 1975): RFCOMM_DisconnectInd LCID:0x41
,E/bt-btm  ( 1975): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 1975): onReceive
,I/BTConnectionReceiver( 1362): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1362): Bluetooth Device Name: S5-1
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): stopServiceDiscovery
,I/wpa_supplicant( 1026): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5145","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3311): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5145","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3311): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3311): Local service added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service requests cleared successfully
,I/wpa_supplicant( 1026): P2P-FIND-STOPPED 
I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Peer discovery stopped successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Peer discovery stopped successfully
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: Android_63cc 82:01:84:6b:e8:5d
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): start: Starting peer discovery...
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 2: Android_63cc 82:01:84:6b:e8:5d
,D/WifiP2pManager( 3311): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service request added successfully
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1026): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 2: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 4: XT1039_8c05 f4:f1:e1:5c:43:c8
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 2: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 4: XT1039_8c05 f4:f1:e1:5c:43:c8
,D/WifiP2pManager( 3311): Ignored { when=-13ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service request added successfully
D/WifiP2pManager( 3311): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service request added successfully
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 1026): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: Got empty list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT349"}", service type: "Cordovap2p._tcp.local."
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Resolved peer properties: [34:FC:EF:9D:93:0B LGE-LG-D802_PT349 34:FC:EF:9D:93:0B]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT349"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT349"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/io.jxcore.node.ConnectionHelper( 3311): onPeerDiscovered: Bluetooth address: 34:FC:EF:9D:93:0B, peer name: LGE-LG-D802_PT349, peer ID: 34:FC:EF:9D:93:0B, Wi-Fi Direct device name: , Wi-Fi Direct address: 36:fc:ef:de:0a:e2
I/io.jxcore.node.ConnectionHelper( 3311): addNewPeerToListAndNotify: Peer with ID 34:FC:EF:9D:93:0B already in the list
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT4197","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4197 F8:95:C7:87:3C:51]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: 2 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT4197","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT4197","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3311): onPeerDiscovered: Bluetooth address: F8:95:C7:87:3C:51, peer name: LGE-LG-H815_PT4197, peer ID: F8:95:C7:87:3C:51, Wi-Fi Direct device name: G4-1, Wi-Fi Direct address: a2:39:f7:6f:c9:5d
I/io.jxcore.node.ConnectionHelper( 3311): addNewPeerToListAndNotify: Peer with ID F8:95:C7:87:3C:51 already in the list
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list containing 2 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT3623"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Resolved peer properties: [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT3623 F4:F1:E1:5C:3B:E2]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: 3 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT3623"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT3623"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3311): onPeerDiscovered: Bluetooth address: F4:F1:E1:5C:3B:E2, peer name: motorola-XT1039_PT3623, peer ID: F4:F1:E1:5C:3B:E2, Wi-Fi Direct device name: XT1039_8c05, Wi-Fi Direct address: f4:f1:e1:5c:43:c8
I/io.jxcore.node.ConnectionHelper( 3311): addNewPeerToListAndNotify: Peer with ID F4:F1:E1:5C:3B:E2 already in the list
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list containing 3 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT4039","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4039 7C:F9:0E:51:18:22]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: 4 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT4039","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT4039","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3311): onPeerDiscovered: Bluetooth address: 7C:F9:0E:51:18:22, peer name: samsung-SM-A500FU_PT4039, peer ID: 7C:F9:0E:51:18:22, Wi-Fi Direct device name: , Wi-Fi Direct address: 7e:f9:0e:51:18:23
I/io.jxcore.node.ConnectionHelper( 3311): addNewPeerToListAndNotify: Peer with ID 7C:F9:0E:51:18:22 already in the list
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list containing 4 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6932","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6932 08:EC:A9:50:76:27]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: 5 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6932","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6932","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3311): onPeerDiscovered: Bluetooth address: 08:EC:A9:50:76:27, peer name: samsung-SM-A300FU_PT6932, peer ID: 08:EC:A9:50:76:27, Wi-Fi Direct device name: Thali Test (Galaxy A3), Wi-Fi Direct address: 0a:ec:a9:50:76:28
I/io.jxcore.node.ConnectionHelper( 3311): addNewPeerToListAndNotify: Peer with ID 08:EC:A9:50:76:27 already in the list
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list containing 5 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): stopServiceDiscovery
,I/wpa_supplicant( 1026): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5145","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3311): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5145","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3311): Local services cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Peer discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3311): Local service added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service requests cleared successfully
,I/wpa_supplicant( 1026): P2P-FIND-STOPPED 
I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Peer discovery stopped successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Peer discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Peer discovery started successfully
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 3311): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service request added successfully
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT6734","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6734 E0:DB:10:14:E2:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerDiscovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: 1 services discovered
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
,I/io.jxcore.node.ConnectionHelper( 3311): onPeerDiscovered: Bluetooth address: E0:DB:10:14:E2:C0, peer name: samsung-SM-N910C_PT6734, peer ID: E0:DB:10:14:E2:C0, Wi-Fi Direct device name: , Wi-Fi Direct address: 92:b6:86:43:73:1c,
,I/io.jxcore.node.ConnectionHelper( 3311): addNewPeerToListAndNotify: Peer with ID E0:DB:10:14:E2:C0 already in the list
,W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT3932","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3932 7C:F9:0E:37:96:AB]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: 2 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
I/io.jxcore.node.ConnectionHelper( 3311): onPeerDiscovered: Bluetooth address: 7C:F9:0E:37:96:AB, peer name: samsung-SM-A500FU_PT3932, peer ID: 7C:F9:0E:37:96:AB, Wi-Fi Direct device name: , Wi-Fi Direct address: 7e:f9:0e:37:96:ac
I/io.jxcore.node.ConnectionHelper( 3311): addNewPeerToListAndNotify: Peer with ID 7C:F9:0E:37:96:AB already in the list
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list containing 2 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT3623"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Resolved peer properties: [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT3623 F4:F1:E1:5C:3B:E2]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: 3 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
I/io.jxcore.node.ConnectionHelper( 3311): onPeerDiscovered: Bluetooth address: F4:F1:E1:5C:3B:E2, peer name: motorola-XT1039_PT3623, peer ID: F4:F1:E1:5C:3B:E2, Wi-Fi Direct device name: , Wi-Fi Direct address: f4:f1:e1:5c:43:c8
I/io.jxcore.node.ConnectionHelper( 3311): addNewPeerToListAndNotify: Peer with ID F4:F1:E1:5C:3B:E2 already in the list
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list containing 3 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT9986"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Resolved peer properties: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT9986 00:F4:6F:30:E0:6C]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: 4 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
I/io.jxcore.node.ConnectionHelper( 3311): onPeerDiscovered: Bluetooth address: 00:F4:6F:30:E0:6C, peer name: samsung-SM-G800F_PT9986, peer ID: 00:F4:6F:30:E0:6C, Wi-Fi Direct device name: S5mini-1, Wi-Fi Direct address: 02:f4:6f:30:e0:6d
I/io.jxcore.node.ConnectionHelper( 3311): addNewPeerToListAndNotify: Peer with ID 00:F4:6F:30:E0:6C already in the list
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list containing 4 peer(s), but doing nothing with that list
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT4039","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4039 7C:F9:0E:51:18:22]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: 5 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
I/io.jxcore.node.ConnectionHelper( 3311): onPeerDiscovered: Bluetooth address: 7C:F9:0E:51:18:22, peer name: samsung-SM-A500FU_PT4039, peer ID: 7C:F9:0E:51:18:22, Wi-Fi Direct device name: , Wi-Fi Direct address: 7e:f9:0e:51:18:23
I/io.jxcore.node.ConnectionHelper( 3311): addNewPeerToListAndNotify: Peer with ID 7C:F9:0E:51:18:22 already in the list
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list containing 5 peer(s), but doing nothing with that list
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT5619","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5619 08:EC:A9:50:75:41]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: 6 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
I/io.jxcore.node.ConnectionHelper( 3311): onPeerDiscovered: Bluetooth address: 08:EC:A9:50:75:41, peer name: samsung-SM-A300FU_PT5619, peer ID: 08:EC:A9:50:75:41, Wi-Fi Direct device name: , Wi-Fi Direct address: 0a:ec:a9:50:75:42
I/io.jxcore.node.ConnectionHelper( 3311): addNewPeerToListAndNotify: Peer with ID 08:EC:A9:50:75:41 already in the list
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list containing 6 peer(s), but doing nothing with that list
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1026): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2765"}", service type: "Cordovap2p._tcp.local."
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Resolved peer properties: [B4:CE:F6:AB:A4:6A HTC-HTC Desire 820_PT2765 B4:CE:F6:AB:A4:6A]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: 7 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
,I/io.jxcore.node.ConnectionHelper( 3311): onPeerDiscovered: Bluetooth address: B4:CE:F6:AB:A4:6A, peer name: HTC-HTC Desire 820_PT2765, peer ID: B4:CE:F6:AB:A4:6A, Wi-Fi Direct device name: Android_1950, Wi-Fi Direct address: b6:ce:f6:ad:a4:6b
I/io.jxcore.node.ConnectionHelper( 3311): addNewPeerToListAndNotify: Peer with ID B4:CE:F6:AB:A4:6A already in the list
,W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list containing 7 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6932","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6932 08:EC:A9:50:76:27]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: 8 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
I/io.jxcore.node.ConnectionHelper( 3311): onPeerDiscovered: Bluetooth address: 08:EC:A9:50:76:27, peer name: samsung-SM-A300FU_PT6932, peer ID: 08:EC:A9:50:76:27, Wi-Fi Direct device name: Thali Test (Galaxy A3), Wi-Fi Direct address: 0a:ec:a9:50:76:28
I/io.jxcore.node.ConnectionHelper( 3311): addNewPeerToListAndNotify: Peer with ID 08:EC:A9:50:76:27 already in the list
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list containing 8 peer(s), but doing nothing with that list
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/UsageStatsService(  735): User[0] Flushing usage stats to disk
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT7800","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT7800 B0:C5:59:3F:75:69]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: 9 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
I/io.jxcore.node.ConnectionHelper( 3311): onPeerDiscovered: Bluetooth address: B0:C5:59:3F:75:69, peer name: samsung-SM-G900F_PT7800, peer ID: B0:C5:59:3F:75:69, Wi-Fi Direct device name: Thali Test (Galaxy S5), Wi-Fi Direct address: ee:1f:72:18:8b:78
I/io.jxcore.node.ConnectionHelper( 3311): addNewPeerToListAndNotify: Adding peer with ID B0:C5:59:3F:75:69
I/jxcore-log( 3311): peerAvailabilityChanged [{"peerIdentifier":"B0:C5:59:3F:75:69","peerName":"samsung-SM-G900F_PT7800","peerAvailable":true}]
I/jxcore-log( 3311): 
I/jxcore-log( 3311): Found peer : samsung-SM-G900F_PT7800, Available: true
I/jxcore-log( 3311): 
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list containing 9 peer(s), but doing nothing with that list
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT4197","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4197 F8:95:C7:87:3C:51]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: 10 services discovered
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
I/io.jxcore.node.ConnectionHelper( 3311): onPeerDiscovered: Bluetooth address: F8:95:C7:87:3C:51, peer name: LGE-LG-H815_PT4197, peer ID: F8:95:C7:87:3C:51, Wi-Fi Direct device name: , Wi-Fi Direct address: a2:39:f7:6f:c9:5d
I/io.jxcore.node.ConnectionHelper( 3311): addNewPeerToListAndNotify: Peer with ID F8:95:C7:87:3C:51 already in the list
,W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list containing 10 peer(s), but doing nothing with that list
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5051","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT5051 7C:F9:0E:34:8A:A0]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: 11 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
I/io.jxcore.node.ConnectionHelper( 3311): onPeerDiscovered: Bluetooth address: 7C:F9:0E:34:8A:A0, peer name: samsung-SM-G900F_PT5051, peer ID: 7C:F9:0E:34:8A:A0, Wi-Fi Direct device name: S5-1, Wi-Fi Direct address: ee:1f:72:63:11:86
I/io.jxcore.node.ConnectionHelper( 3311): addNewPeerToListAndNotify: Peer with ID 7C:F9:0E:34:8A:A0 already in the list
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list containing 11 peer(s), but doing nothing with that list
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT1658"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Resolved peer properties: [38:94:96:B5:06:DC samsung-SM-G800H_PT1658 38:94:96:B5:06:DC]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: 12 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
I/io.jxcore.node.ConnectionHelper( 3311): onPeerDiscovered: Bluetooth address: 38:94:96:B5:06:DC, peer name: samsung-SM-G800H_PT1658, peer ID: 38:94:96:B5:06:DC, Wi-Fi Direct device name: , Wi-Fi Direct address: 3a:94:96:b5:06:dd
I/io.jxcore.node.ConnectionHelper( 3311): addNewPeerToListAndNotify: Peer with ID 38:94:96:B5:06:DC already in the list
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list containing 12 peer(s), but doing nothing with that list
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): stopServiceDiscovery
,I/wpa_supplicant( 1026): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
,I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
,I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5145","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3311): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5145","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3311): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Peer discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3311): Local service added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service requests cleared successfully
,I/wpa_supplicant( 1026): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Peer discovery stopped successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Peer discovery stopped successfully
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 3: S5mini-1 02:f4:6f:30:e0:6d
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): startServiceDiscovery: Invalid state, try calling restart()
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 3: S5mini-1 02:f4:6f:30:e0:6d
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 3: S5mini-1 02:f4:6f:30:e0:6d
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Peer discovery started successfully
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 3: S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 3311): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service request added successfully
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 3: S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 3311): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service request added successfully
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: Got empty list
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Got a list of peers, but since we are currently discovering services (not peers), the new list is ignored
,I/wpa_supplicant( 1026): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: Got empty list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT5619","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT5619 08:EC:A9:50:75:41]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT5619","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/io.jxcore.node.ConnectionHelper( 3311): onPeerDiscovered: Bluetooth address: 08:EC:A9:50:75:41, peer name: samsung-SM-A300FU_PT5619, peer ID: 08:EC:A9:50:75:41, Wi-Fi Direct device name: A3-1, Wi-Fi Direct address: 0a:ec:a9:50:75:42
I/io.jxcore.node.ConnectionHelper( 3311): addNewPeerToListAndNotify: Peer with ID 08:EC:A9:50:75:41 already in the list
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT4197","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4197 F8:95:C7:87:3C:51]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: 2 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT4197","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3311): onPeerDiscovered: Bluetooth address: F8:95:C7:87:3C:51, peer name: LGE-LG-H815_PT4197, peer ID: F8:95:C7:87:3C:51, Wi-Fi Direct device name: , Wi-Fi Direct address: a2:39:f7:6f:c9:5d
I/io.jxcore.node.ConnectionHelper( 3311): addNewPeerToListAndNotify: Peer with ID F8:95:C7:87:3C:51 already in the list
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list containing 2 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT1658","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Resolved peer properties: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT1658 F8:CF:C5:D9:E5:61]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: 3 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT1658","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3311): onPeerDiscovered: Bluetooth address: F8:CF:C5:D9:E5:61, peer name: motorola-Nexus 6_PT1658, peer ID: F8:CF:C5:D9:E5:61, Wi-Fi Direct device name: , Wi-Fi Direct address: fa:cf:c5:d9:e5:62
,I/io.jxcore.node.ConnectionHelper( 3311): addNewPeerToListAndNotify: Peer with ID F8:CF:C5:D9:E5:61 already in the list
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list containing 3 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT3932","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3932 7C:F9:0E:37:96:AB]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: 4 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT3932","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/io.jxcore.node.ConnectionHelper( 3311): onPeerDiscovered: Bluetooth address: 7C:F9:0E:37:96:AB, peer name: samsung-SM-A500FU_PT3932, peer ID: 7C:F9:0E:37:96:AB, Wi-Fi Direct device name: , Wi-Fi Direct address: 7e:f9:0e:37:96:ac
,I/io.jxcore.node.ConnectionHelper( 3311): addNewPeerToListAndNotify: Peer with ID 7C:F9:0E:37:96:AB already in the list
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list containing 4 peer(s), but doing nothing with that list
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5051","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT5051 7C:F9:0E:34:8A:A0]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: 5 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5051","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3311): onPeerDiscovered: Bluetooth address: 7C:F9:0E:34:8A:A0, peer name: samsung-SM-G900F_PT5051, peer ID: 7C:F9:0E:34:8A:A0, Wi-Fi Direct device name: S5-1, Wi-Fi Direct address: ee:1f:72:63:11:86
I/io.jxcore.node.ConnectionHelper( 3311): addNewPeerToListAndNotify: Peer with ID 7C:F9:0E:34:8A:A0 already in the list
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list containing 5 peer(s), but doing nothing with that list
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT3106","ra":"E0:DB:10:1F:C9:5E"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT3106 E0:DB:10:1F:C9:5E]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: 6 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT3106","ra":"E0:DB:10:1F:C9:5E"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3311): onPeerDiscovered: Bluetooth address: E0:DB:10:1F:C9:5E, peer name: samsung-SM-N9005_PT3106, peer ID: E0:DB:10:1F:C9:5E, Wi-Fi Direct device name: Note3-1, Wi-Fi Direct address: ea:50:8b:de:28:a3
I/io.jxcore.node.ConnectionHelper( 3311): addNewPeerToListAndNotify: Peer with ID E0:DB:10:1F:C9:5E already in the list
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list containing 6 peer(s), but doing nothing with that list
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT6734","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT6734 E0:DB:10:14:E2:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: 7 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT6734","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3311): onPeerDiscovered: Bluetooth address: E0:DB:10:14:E2:C0, peer name: samsung-SM-N910C_PT6734, peer ID: E0:DB:10:14:E2:C0, Wi-Fi Direct device name: Note4-1, Wi-Fi Direct address: 92:b6:86:43:73:1c
I/io.jxcore.node.ConnectionHelper( 3311): addNewPeerToListAndNotify: Peer with ID E0:DB:10:14:E2:C0 already in the list
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list containing 7 peer(s), but doing nothing with that list
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT349"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Resolved peer properties: [34:FC:EF:9D:93:0B LGE-LG-D802_PT349 34:FC:EF:9D:93:0B]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: 8 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT349"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3311): onPeerDiscovered: Bluetooth address: 34:FC:EF:9D:93:0B, peer name: LGE-LG-D802_PT349, peer ID: 34:FC:EF:9D:93:0B, Wi-Fi Direct device name: , Wi-Fi Direct address: 36:fc:ef:de:0a:e2
I/io.jxcore.node.ConnectionHelper( 3311): addNewPeerToListAndNotify: Peer with ID 34:FC:EF:9D:93:0B already in the list
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list containing 8 peer(s), but doing nothing with that list
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT7800","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT7800 B0:C5:59:3F:75:69]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceDiscovered
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerDiscovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: 9 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT7800","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3311): onPeerDiscovered: Bluetooth address: B0:C5:59:3F:75:69, peer name: samsung-SM-G900F_PT7800, peer ID: B0:C5:59:3F:75:69, Wi-Fi Direct device name: Thali Test (Galaxy S5), Wi-Fi Direct address: ee:1f:72:18:8b:78
I/io.jxcore.node.ConnectionHelper( 3311): addNewPeerToListAndNotify: Peer with ID B0:C5:59:3F:75:69 already in the list
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list containing 9 peer(s), but doing nothing with that list
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): stopServiceDiscovery
,I/wpa_supplicant( 1026): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5145","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3311): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5145","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3311): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3311): Local service added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 1026): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Peer discovery stopped successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Peer discovery stopped successfully
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): start: Starting peer discovery...
,I/wpa_supplicant( 1026): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
,D/WifiP2pManager( 3311): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service request added successfully
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
,D/WifiP2pManager( 3311): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service request added successfully
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 3311): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service request added successfully
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1026): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1026): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1026): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT4197","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4197 F8:95:C7:87:3C:51]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT4197","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT4197","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3311): onPeerDiscovered: Bluetooth address: F8:95:C7:87:3C:51, peer name: LGE-LG-H815_PT4197, peer ID: F8:95:C7:87:3C:51, Wi-Fi Direct device name: G4-1, Wi-Fi Direct address: a2:39:f7:6f:c9:5d
I/io.jxcore.node.ConnectionHelper( 3311): addNewPeerToListAndNotify: Peer with ID F8:95:C7:87:3C:51 already in the list
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): stopServiceDiscovery
,I/wpa_supplicant( 1026): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5145","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3311): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5145","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3311): Local services cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3311): Local service added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service requests cleared successfully
,I/wpa_supplicant( 1026): P2P-FIND-STOPPED 
I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Peer discovery stopped successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Peer discovery stopped successfully
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Peer discovery started successfully
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 2: S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 3311): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service request added successfully
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: Got empty list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2765"}", service type: "Cordovap2p._tcp.local."
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Resolved peer properties: [B4:CE:F6:AB:A4:6A HTC-HTC Desire 820_PT2765 B4:CE:F6:AB:A4:6A]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerDiscovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
I/io.jxcore.node.ConnectionHelper( 3311): onPeerDiscovered: Bluetooth address: B4:CE:F6:AB:A4:6A, peer name: HTC-HTC Desire 820_PT2765, peer ID: B4:CE:F6:AB:A4:6A, Wi-Fi Direct device name: , Wi-Fi Direct address: b6:ce:f6:ad:a4:6b
I/io.jxcore.node.ConnectionHelper( 3311): addNewPeerToListAndNotify: Peer with ID B4:CE:F6:AB:A4:6A already in the list
,W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/jxcore-log( 3311): timeout now
I/jxcore-log( 3311): 
I/jxcore-log( 3311): weAreDoneNow, resultArray.length: 3
I/jxcore-log( 3311): 
I/jxcore-log( 3311): sendReportNow
I/jxcore-log( 3311): 
I/jxcore-log( 3311): done, now sending data to server
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:24:58.028Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3311): 
D/io.jxcore.node.ConnectionHelper( 3311): disconnectOutgoingConnection: Trying to close connection to peer with ID 34:FC:EF:11:B1:66
E/io.jxcore.node.ConnectionHelper( 3311): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 34:FC:EF:11:B1:66
D/io.jxcore.node.ConnectionHelper( 3311): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3311): disconnectOutgoingConnection: Failed to disconnect (peer ID: 34:FC:EF:11:B1:66), either no such connection or failed to close the connection
I/jxcore-log( 3311): 2015-12-15T04:24:58.031Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3311): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): stopServiceDiscovery
,I/wpa_supplicant( 1026): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5145","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3311): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5145","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3311): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3311): Local service added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Peer discovery started successfully
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 1026): P2P-FIND-STOPPED 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Peer discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Peer discovery stopped successfully
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: G4-1 a2:39:f7:6f:c9:5d
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): start: Starting peer discovery...
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3311): Ignored { when=-3ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service request added successfully
,D/WifiP2pManager( 3311): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service request added successfully
D/WifiP2pManager( 3311): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service request added successfully
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 2: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3311): Ignored { when=-3ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service request added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1026): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1026): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 1026): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT1757"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Resolved peer properties: [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT1757 80:01:84:8A:B3:68]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT1757"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT1757"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT1757"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3311): onPeerDiscovered: Bluetooth address: 80:01:84:8A:B3:68, peer name: HTC-HTC Desire 820_PT1757, peer ID: 80:01:84:8A:B3:68, Wi-Fi Direct device name: Android_63cc, Wi-Fi Direct address: 82:01:84:6b:e8:5d
I/io.jxcore.node.ConnectionHelper( 3311): addNewPeerToListAndNotify: Peer with ID 80:01:84:8A:B3:68 already in the list
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2765"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Resolved peer properties: [B4:CE:F6:AB:A4:6A HTC-HTC Desire 820_PT2765 B4:CE:F6:AB:A4:6A]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: 2 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2765"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2765"}", service type: "Cordovap2p._tcp.local."
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2765"}", service type: "Cordovap2p._tcp.local."
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3311): onPeerDiscovered: Bluetooth address: B4:CE:F6:AB:A4:6A, peer name: HTC-HTC Desire 820_PT2765, peer ID: B4:CE:F6:AB:A4:6A, Wi-Fi Direct device name: Android_1950, Wi-Fi Direct address: b6:ce:f6:ad:a4:6b
,I/io.jxcore.node.ConnectionHelper( 3311): addNewPeerToListAndNotify: Peer with ID B4:CE:F6:AB:A4:6A already in the list
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list containing 2 peer(s), but doing nothing with that list
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1026): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT3106","ra":"E0:DB:10:1F:C9:5E"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT3106 E0:DB:10:1F:C9:5E]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: 3 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT3106","ra":"E0:DB:10:1F:C9:5E"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT3106","ra":"E0:DB:10:1F:C9:5E"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT3106","ra":"E0:DB:10:1F:C9:5E"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/io.jxcore.node.ConnectionHelper( 3311): onPeerDiscovered: Bluetooth address: E0:DB:10:1F:C9:5E, peer name: samsung-SM-N9005_PT3106, peer ID: E0:DB:10:1F:C9:5E, Wi-Fi Direct device name: Note3-1, Wi-Fi Direct address: ea:50:8b:de:28:a3
I/io.jxcore.node.ConnectionHelper( 3311): addNewPeerToListAndNotify: Peer with ID E0:DB:10:1F:C9:5E already in the list
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list containing 3 peer(s), but doing nothing with that list
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT6503","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT6503 F8:95:C7:87:85:54]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: 4 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT6503","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3311): onPeerDiscovered: Bluetooth address: F8:95:C7:87:85:54, peer name: LGE-LG-D722_PT6503, peer ID: F8:95:C7:87:85:54, Wi-Fi Direct device name: G3s-1, Wi-Fi Direct address: a2:39:f7:70:12:80
I/io.jxcore.node.ConnectionHelper( 3311): addNewPeerToListAndNotify: Peer with ID F8:95:C7:87:85:54 already in the list
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list containing 4 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT6503","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT6503","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1026): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT1658"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Resolved peer properties: [38:94:96:B5:06:DC samsung-SM-G800H_PT1658 38:94:96:B5:06:DC]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: 5 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT1658"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT1658"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT1658"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3311): onPeerDiscovered: Bluetooth address: 38:94:96:B5:06:DC, peer name: samsung-SM-G800H_PT1658, peer ID: 38:94:96:B5:06:DC, Wi-Fi Direct device name: , Wi-Fi Direct address: 3a:94:96:b5:06:dd
,I/io.jxcore.node.ConnectionHelper( 3311): addNewPeerToListAndNotify: Peer with ID 38:94:96:B5:06:DC already in the list
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list containing 5 peer(s), but doing nothing with that list
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): stopServiceDiscovery
,I/wpa_supplicant( 1026): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5145","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3311): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5145","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3311): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3311): Local service added successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service requests cleared successfully
,I/wpa_supplicant( 1026): P2P-FIND-STOPPED 
I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Peer discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): startServiceDiscovery: Invalid state, try calling restart()
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): startServiceDiscovery: Invalid state, try calling restart()
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): startServiceDiscovery: Invalid state, try calling restart()
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): startServiceDiscovery: Invalid state, try calling restart()
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): startServiceDiscovery: Invalid state, try calling restart()
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): startServiceDiscovery: Invalid state, try calling restart()
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): startServiceDiscovery: Invalid state, try calling restart()
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): startServiceDiscovery: Invalid state, try calling restart()
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): startServiceDiscovery: Invalid state, try calling restart()
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): restart: Restarting...
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Peer discovery stopped successfully
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): start: Starting peer discovery...
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1026): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 4 P2P devices discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 2: Android_63cc 82:01:84:6b:e8:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 2: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 2: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 2: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3311): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service request added successfully
D/WifiP2pManager( 3311): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service request added successfully
D/WifiP2pManager( 3311): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service request added successfully
,D/WifiP2pManager( 3311): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service request added successfully
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 6 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 2: Note3-1 ea:50:8b:de:28:a3
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 4: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 5: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 6 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 2: Note3-1 ea:50:8b:de:28:a3
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 4: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 5: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3311): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service request added successfully
D/WifiP2pManager( 3311): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service request added successfully
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 1026): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1026): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service discovery started successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1026): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1026): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1026): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: Got empty list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): stopServiceDiscovery
,I/wpa_supplicant( 1026): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Peer discovery stopped successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Peer discovery started successfully
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
,D/WifiP2pManager( 3311): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service request added successfully
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1026): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 3311): Ignored { when=-14ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service request added successfully
,D/WifiP2pManager( 3311): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service request added successfully
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: 4 P2P devices discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
,I/wpa_supplicant( 1026): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onP2pDeviceListChanged: Peer 4: XT1039_8c05 f4:f1:e1:5c:43:c8
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: Got empty list
D/WifiP2pManager( 3311): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service request added successfully
,I/wpa_supplicant( 1026): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1026): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1026): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1026): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1026): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT349"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Resolved peer properties: [34:FC:EF:9D:93:0B LGE-LG-D802_PT349 34:FC:EF:9D:93:0B]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT349"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT349"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT349"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3311): onPeerDiscovered: Bluetooth address: 34:FC:EF:9D:93:0B, peer name: LGE-LG-D802_PT349, peer ID: 34:FC:EF:9D:93:0B, Wi-Fi Direct device name: Thali Test's G2, Wi-Fi Direct address: 36:fc:ef:de:0a:e2
I/io.jxcore.node.ConnectionHelper( 3311): addNewPeerToListAndNotify: Peer with ID 34:FC:EF:9D:93:0B already in the list
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT9986"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Resolved peer properties: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT9986 00:F4:6F:30:E0:6C]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: 2 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT9986"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT9986"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT9986"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3311): onPeerDiscovered: Bluetooth address: 00:F4:6F:30:E0:6C, peer name: samsung-SM-G800F_PT9986, peer ID: 00:F4:6F:30:E0:6C, Wi-Fi Direct device name: S5mini-1, Wi-Fi Direct address: 02:f4:6f:30:e0:6d
I/io.jxcore.node.ConnectionHelper( 3311): addNewPeerToListAndNotify: Peer with ID 00:F4:6F:30:E0:6C already in the list
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list containing 2 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT3010","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT3010 58:3F:54:73:64:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): onServiceListChanged: 3 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT3010","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT3010","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT3010","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3311): onPeerDiscovered: Bluetooth address: 58:3F:54:73:64:C0, peer name: LGE-LG-D855_PT3010, peer ID: 58:3F:54:73:64:C0, Wi-Fi Direct device name: G3-1, Wi-Fi Direct address: 02:9a:02:7b:60:ac
I/io.jxcore.node.ConnectionHelper( 3311): addNewPeerToListAndNotify: Peer with ID 58:3F:54:73:64:C0 already in the list
W/io.jxcore.node.ConnectionHelper( 3311): onPeerListChanged: Got a list containing 3 peer(s), but doing nothing with that list
,I/jxcore-log( 3311): server initiated timeout
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): testSendData stopped
I/jxcore-log( 3311): 
I/io.jxcore.node.ConnectionHelper( 3311): stop
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3311): Shutting down...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3311): shutdown
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3311): Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3311): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3311): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3311): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:489)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3311): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:399)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3311): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3311): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3311): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread.run(BluetoothServerThread.java:89)
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3311): onIncomingConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3311): Socket is null
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3311): onIncomingConnectionFailed: Socket is null
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3311): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3311): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3311): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): stopServiceDiscovery
,I/wpa_supplicant( 1026): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 1026): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): setState: NOT_INITIALIZED
I/jxcore-log( 3311): StopBroadcasting went ok
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): sendReportNow
I/jxcore-log( 3311): 
I/jxcore-log( 3311): done, now sending data to server
I/jxcore-log( 3311): 
,I/jxcore-log( 3311): 2015-12-15T04:27:51.207Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
I/jxcore-log( 3311): 
I/chromium( 3311): [INFO:CONSOLE(63)] "logCallback server initiated timeout", source: file:///android_asset/www/js/thali_main.js (63)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3311): onConnectionFailed: Socket is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3311): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3311): Peer discovery stopped successfully
I/io.jxcore.node.ConnectionHelper( 3311): onConnectionManagerStateChanged: INITIALIZED
I/io.jxcore.node.ConnectionHelper( 3311): onConnectionManagerStateChanged: NOT_INITIALIZED
,I/ActivityManager(  735): Killing 3504:com.google.android.apps.magazines/u0a61 (adj 13): empty for 1801s
,I/ActivityManager(  735): Killing 2709:com.google.android.music:main/u0a60 (adj 13): empty for 1801s
,I/ActivityManager(  735): Killing 3600:com.qualcomm.timeservice/u0a76 (adj 13): empty for 1802s
,I/ActivityManager(  735): Killing 3574:com.google.android.keep/u0a71 (adj 13): empty for 1802s
,I/ActivityManager(  735): Killing 3120:com.android.defcontainer/u0a5 (adj 15): empty for 1808s
,I/ActivityManager(  735): Killing 3229:com.google.android.apps.docs/u0a40 (adj 15): empty for 1811s
,I/ActivityManager(  735): Killing 3197:com.android.musicfx/u0a15 (adj 15): empty for 1811s
,I/ProcessStatsService(  735): Prepared write state in 3ms
,W/libprocessgroup(  735): failed to open /acct/uid_10060/pid_2709/cgroup.procs: No such file or directory
,W/libprocessgroup(  735): failed to open /acct/uid_10040/pid_3229/cgroup.procs: No such file or directory
,W/libprocessgroup(  735): failed to open /acct/uid_10015/pid_3197/cgroup.procs: No such file or directory
,W/libprocessgroup(  735): failed to open /acct/uid_10061/pid_3504/cgroup.procs: No such file or directory
,W/libprocessgroup(  735): failed to open /acct/uid_10076/pid_3600/cgroup.procs: No such file or directory
,W/libprocessgroup(  735): failed to open /acct/uid_10071/pid_3574/cgroup.procs: No such file or directory
,W/libprocessgroup(  735): failed to open /acct/uid_10005/pid_3120/cgroup.procs: No such file or directory
,V/GLSActivity( 1576): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1576): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ProcessStatsService(  735): Pruning old procstats: /data/system/procstats/state-2015-12-14-16-17-24.bin
,TIME-OUT KILL (timeout was 1800000ms)
```
