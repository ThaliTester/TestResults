#### Test 534296758dfd01f_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
D/ChimeraCfgMgr( 1597): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1597): Module APK com.google.android.play.games already loaded
I/GAv4    ( 3154): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3154):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3154):   adb logcat -s GAv4
W/GAv4    ( 3154): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3154): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3154): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 3154): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
D/Finsky  ( 2644): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
W/ResourcesManager( 3154): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3154): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  757): Killing 2608:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
V/JNIHelp ( 3154): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/libprocessgroup(  757): failed to open /acct/uid_10069/pid_2608/cgroup.procs: No such file or directory
W/System  ( 3154): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3154): Installed default security provider GmsCore_OpenSSL
V/GLSActivity( 1571): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 1597): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/Icing   ( 1597): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1597): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/Icing   ( 1597): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
,D/AndroidRuntime( 3204): 
D/AndroidRuntime( 3204): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3204): CheckJNI is OFF
D/AndroidRuntime( 3204): Calling main entry com.android.commands.am.Am
I/ActivityManager(  757): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  757): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3228 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3204): Shutting down VM
I/art     (  195): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 837us total 10.239ms
I/art     (  195): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 169us total 7.397ms
I/art     (  195): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 167us total 7.425ms
V/ActivityManager(  757): Display changed displayId=0
I/WebViewFactory( 3228): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3228): Time to load native libraries: 1 ms (timestamps 1408-1409)
I/LibraryLoader( 3228): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3228): Binding Chromium to main looper Looper (main, tid 1) {3d9c9005}
I/LibraryLoader( 3228): Expected native library version number "",actual native library version number ""
I/chromium( 3228): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3228): Initializing chromium process, singleProcess=true
W/art     ( 3228): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3228): ApplicationContext is null in ApplicationStatus
W/chromium( 3228): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3228): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3228): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3228): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  757): Message: 20
D/BluetoothManagerService(  757): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f63eb19:true
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
,W/BindingManager( 3228): Cannot call determinedVisibility() - never saw a connection for the pid: 3228
I/Keyboard.Facilitator( 1065): onFinishInput()
,I/ActivityManager(  757): Displayed com.test.thalitest/.MainActivity: +439ms (total +58s983ms)
,W/IInputConnectionWrapper( 3228): showStatusIcon on inactive InputConnection
,D/JsMessageQueue( 3228): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3228): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257332480
D/JX-Cordova( 3228): jxcore cordova android initializing
,V/GLSActivity( 1571): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1571): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/jxcore-log( 3228): Initializing JXcore engine
W/jxcore-log( 3228): JXcore engine is ready
,W/jxcore-log( 3228): Starting JXcore engine
,W/.test.thalitest( 3228): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[8324]" dev="sockfs" ino=8324 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/.test.thalitest( 3228): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 3228): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8450]" dev="sockfs" ino=8450 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/.test.thalitest( 3228): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[19700]" dev="sockfs" ino=19700 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3228): Platform android
W/jxcore-log( 3228): 
W/jxcore-log( 3228): Process ARCH arm
W/jxcore-log( 3228): 
,I/jxcore-log( 3228): JXcore Cordova bridge is ready!
I/jxcore-log( 3228): 
,W/jxcore-log( 3228): JXcore engine is started
I/Choreographer( 3228): Skipped 114 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3228): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3228): Toggling radios to true
I/jxcore-log( 3228): 
,D/BluetoothAdapter( 3228): enable(): BT is already enabled..!
,D/WifiService(  757): setWifiEnabled: true pid=3228, uid=10270
E/WifiService(  757): Invoking mWifiStateMachine.setWifiEnabled
,D/WifiService(  757): New client listening to asynchronous messages
,I/jxcore-log( 3228): Radios toggled
I/jxcore-log( 3228): 
,I/wpa_supplicant( 1047): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  757): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  757): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
E/native  (  757): do suspend true
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1571): Read error: ssl=0xb3d28e00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1571): SSL shutdown failed: ssl=0xb3d28e00: I/O error during system call, Broken pipe
,D/ConnectivityService(  757): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): ValidatedState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): DefaultState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,E/WifiConfigStore(  757): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  757): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  757): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,E/WifiStateMachine(  757): Start Disconnecting Watchdog 1
,I/wpa_supplicant( 1047): wlan0: CTRL-EVENT-SCAN-STARTED 
,E/native  (  757): do suspend true
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,D/ConnectivityService(  757): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler(  899): CM callback handler got msg 524292
,D/Nat464Xlat(  757): requiresClat: netType=1, connected=false, hasIPv4Address=true
,D/CSLegacyTypeTracker(  757): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  757): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): Disconnected - quitting
D/ConnectivityManager.CallbackHandler( 1597): CM callback handler got msg 524292
,D/ConnectivityService(  757): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  757): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1201): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WifiNetworkAgent(  757): NetworkAgent: NetworkAgent channel lost
,I/wpa_supplicant( 1047): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant( 1047): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1047): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1047): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  757): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  757): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  757): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiConfigStore(  757): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  179): Setting iface cfg
,E/WifiStateMachine(  757): Start Dhcp Watchdog 2
,D/BluetoothManagerService(  757): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 3228): Got Device Bluetooth address: 34:FC:EF:11:AE:67
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): my name is : LGE-Nexus 5_PT6995
I/jxcore-log( 3228): 
,E/native  (  757): do suspend false
,E/WifiStateMachine(  757): scanCount==0 - aborting
,I/jxcore-log( 3228): attempting to connect to test coordinator
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): check test folder
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): found test : ./testFindPeers.js
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): found test : ./testReConnect.js
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): found test : ./testSendData.js
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): Test app app.js loaded
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3228): 
,I/Choreographer( 3228): Skipped 111 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3228): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/dhcpcd  ( 3342): version 5.5.6 starting
,E/dhcpcd  ( 3342): get_duid: Read-only file system
,I/dhcpcd  ( 3342): wlan0: rebinding lease of 192.168.1.114
,I/dhcpcd  ( 3342): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3342): wlan0: leased 192.168.1.114 for 86400 seconds
,E/native  (  757): do suspend true
,D/ConnectivityService(  757): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService(  757): Adding iface wlan0 to network 101
,E/WifiStateMachine(  757): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  757): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  757): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  757): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  757): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  757): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  757): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  757): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  757): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  757): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  757):    accepting network in place of null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/CSLegacyTypeTracker(  757): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  757): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  757): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  757): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  899): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1597): CM callback handler got msg 524290
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 11 Dec 2015 19:07:04 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1449860824235], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1449860824219]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): Validated
,D/ConnectivityService(  757): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  757): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  757): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  757): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  757): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler(  899): CM callback handler got msg 524290
,D/TelephonyNetworkFactory( 1201): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 1597): CM callback handler got msg 524290
,D/ConnectivityService(  757): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  757): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  757): MasterInitialState.processMessage what=3
,D/Tethering(  757): MasterInitialState.processMessage what=3
,D/Nat464Xlat(  757): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  757): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  899): CM callback handler got msg 524295
,I/NetworkMonitor( 2772): type=WIFI subType= reason=null isConnected=true
,D/ConnectivityManager.CallbackHandler( 1597): CM callback handler got msg 524295
,I/NetworkMonitor( 2772): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2772): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,E/GpsLocationProvider(  757): No APN found to select.
,E/GpsLocationProvider(  757): No APN found to select.
,I/SystemUpdateService( 1597): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1597): onCreate
,D/SystemUpdateService( 1597): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1597): active receiver: enabled
,I/SystemUpdateService( 1597): showing system update notification
,I/ValidateNoPeople(  757): skipping global notification
,I/jxcore-log( 3228): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3228): 
,V/SystemUpdateService( 1597): retry (wakeup: false) in 3599984 ms
,I/ActivityManager(  757): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3408 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ConnectivityService(  757): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,D/SystemUpdateService( 1597): onDestroy
,I/GAv4    ( 3408): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3408):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3408):   adb logcat -s GAv4
,W/GAv4    ( 3408): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3408): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3408): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 3408): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3408): Time to load native libraries: 1 ms (timestamps 7918-7919)
I/LibraryLoader( 3408): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3408): Binding Chromium to main looper Looper (main, tid 1) {3abfca2f}
,I/LibraryLoader( 3408): Expected native library version number "",actual native library version number ""
,I/chromium( 3408): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3408): Initializing chromium process, singleProcess=true
,W/art     ( 3408): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3408): ApplicationContext is null in ApplicationStatus
,W/chromium( 3408): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3408): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3408): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3408): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/NSApplication( 3408): Starting up...
,I/ActivityManager(  757): Killing 2563:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,W/AudioManagerAndroid( 3408): Requires BLUETOOTH permission
,W/libprocessgroup(  757): failed to open /acct/uid_10045/pid_2563/cgroup.procs: No such file or directory
,V/MusicLeanback( 2772): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1597): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1597): onCreate
,D/SystemUpdateService( 1597): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1597): active receiver: enabled
,I/SystemUpdateService( 1597): showing system update notification
,I/ValidateNoPeople(  757): skipping global notification
,V/SystemUpdateService( 1597): retry (wakeup: false) in 3599968 ms
,D/SystemUpdateService( 1597): onDestroy
,I/art     (  757): Explicit concurrent mark sweep GC freed 41035(1989KB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 27MB/41MB, paused 1.176ms total 82.914ms
,D/ConnectivityService(  757): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  757): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2772): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2772): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1597): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1597): onCreate
,D/SystemUpdateService( 1597): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1597): active receiver: enabled
,I/SystemUpdateService( 1597): showing system update notification
,E/GpsLocationProvider(  757): No APN found to select.
,I/ValidateNoPeople(  757): skipping global notification
,V/SystemUpdateService( 1597): retry (wakeup: false) in 3599973 ms
,D/SystemUpdateService( 1597): onDestroy
,I/jxcore-log( 3228): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): BLE advertisement not supported: MultipleAdvertisement not supported
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3228): 
,D/Finsky  ( 2644): [255] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2644): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/jxcore-log( 3228): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3228): 
,V/GLSActivity( 1571): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1571): Vacuum at: now=1449860836774 tag=VacuumService
,I/PhenotypeConfigurator( 1571): Scheduling Phenotype for one-off execution 6109 seconds from now (1449860837033)
,D/GetConfigurationSnapshotOperation( 1571): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1571): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1571): Using platform SSLCertificateSocketFactory
,V/GLSActivity( 1571): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1571): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 3228): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3228): 
,I/Keyboard.Facilitator.LanguageModelFlusher( 1065): run()
I/Keyboard.Facilitator( 1065): flushDynamicLanguageModels()
,I/ConfigService( 1571): onCreate
,I/jxcore-log( 3228): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3228): 
,I/ConfigService( 1571): onDestroy
,I/jxcore-log( 3228): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3228): 
,I/ClearcutLoggerApiImpl( 1571): disconnect managed GoogleApiClient
,I/jxcore-log( 3228): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): DBG, CoordinatorConnector connect called
I/jxcore-log( 3228): 
I/jxcore-log( 3228): Coordinator is now connected to the server!
I/jxcore-log( 3228): 
,I/chromium( 3228): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3228): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): DBG, CoordinatorConnector command called
I/jxcore-log( 3228): 
I/jxcore-log( 3228): command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":10000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":22,"addressList":[{"address":"F8:95:C7:87:85:54","tryCount":0},{"address":"F8:CF:C5:D9:E5:61","tryCount":0},{"address":"34:FC:EF:11:B1:66","tryCount":0},{"address":"44:80:EB:7B:5A:05","tryCount":0},{"address":"B0:C5:59:3F:75:69","tryCount":0},{"address":"7C:F9:0E:34:8A:A0","tryCount":0},{"address":"80:01:84:8A:B3:68","tryCount":0},{"address":"E0:DB:10:1F:C9:5E","tryCount":0},{"address":"58:2A:F7:ED:96:BE","tryCount":0},{"address":"F8:95:C7:87:3C:51","tryCount":0},{"address":"7C:F9:0E:37:96:AB","tryCount":0},{"address":"B4:CE:F6:AB:A4:6A","tryCount":0},{"address":"08:EC:A9:50:75:41","tryCount":0},{"address":"08:EC:A9:50:76:27","tryCount":0},{"address":"38:94:96:B5:06:DC","tryCount":0},{"address":"7C:F9:0E:51:18:22","tryCount":0},{"address":"E0:DB:10:14:E2:C0","tryCount":0},{"address":"58:3F:54:73:64
,I/jxcore-log( 3228): Start now : testSendData.js
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 22
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): check server
I/jxcore-log( 3228): 
I/jxcore-log( 3228): serverPort is 45763
I/jxcore-log( 3228): 
,D/BluetoothManagerService(  757): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): stop: Stopping Bluetooth and peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): initialize: 34:FC:EF:11:AE:67 LGE-Nexus 5_PT6995
,D/BluetoothManagerService(  757): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3228): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): initialize: Bluetooth and Wi-Fi OK
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): setState: INITIALIZED
,D/BluetoothManagerService(  757): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT6995","ra":"34:FC:EF:11:AE:67"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3228): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  757): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3228): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT6995","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3228): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT6995","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onIsDiscoveryStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): startWifiPeerDiscovery: Started
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3228): start: OK
I/jxcore-log( 3228): StartBroadcasting started ok
I/jxcore-log( 3228): 
I/jxcore-log( 3228): do fake peer & start
I/jxcore-log( 3228): 
I/jxcore-log( 3228): Connect to fake peer: E0:DB:10:1F:C9:5E
I/jxcore-log( 3228): 
I/jxcore-log( 3228): 2015-12-11T19:12:37.723Z SendDataConnector.js: Start called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3228): 
I/jxcore-log( 3228): 2015-12-11T19:12:37.723Z SendDataConnector.js: doConnect called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3228): 
I/jxcore-log( 3228): 2015-12-11T19:12:37.723Z SendDataConnector.js: do connect now
I/jxcore-log( 3228): 
I/io.jxcore.node.ConnectionHelper( 3228): connect: Trying to connect to peer with ID E0:DB:10:1F:C9:5E
D/io.jxcore.node.ConnectionHelper( 3228): hasConnection: No connection with peer with ID E0:DB:10:1F:C9:5E
W/io.jxcore.node.ConnectionHelper( 3228): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3228): connect: Trying to start connecting to null in address E0:DB:10:1F:C9:5E
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onConnecting: null E0:DB:10:1F:C9:5E
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3228): connect: Started connecting to null in address E0:DB:10:1F:C9:5E
I/io.jxcore.node.ConnectionHelper( 3228): connect: Connection process successfully started (peer ID: E0:DB:10:1F:C9:5E)
,I/jxcore-log( 3228): 2015-12-11T19:12:37.734Z SendDataTCPServer.js: TCP/IP server is bound to port: 45763
I/jxcore-log( 3228): 
I/chromium( 3228): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi peer discovery...
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): startWifiPeerDiscovery: Already started
I/io.jxcore.node.ConnectionHelper( 3228): onConnectionManagerStateChanged: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3228): Local service added successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
I/io.jxcore.node.ConnectionHelper( 3228): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): Trying to connect to peer with address E0:DB:10:1F:C9:5E (thread ID: 298)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3228): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3228): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2106): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2106): info:x10
,D/        ( 2106): remote version info [b4:ce:f6:ab:a4:6a]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2106): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 2106): bondStateChangeCallback: Status: 0 Address: B4:CE:F6:AB:A4:6A newState: 1
E/bt-btif ( 2106): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2106): Bond State Change Intent:B4:CE:F6:AB:A4:6A OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2106): Entering PendingCommandState State
,W/BluetoothEventManager( 2727): CachedBluetoothDevice for device B4:CE:F6:AB:A4:6A not found, calling readPairedDevices().
,E/BluetoothEventManager( 2727): Got bonding state changed for B4:CE:F6:AB:A4:6A, but we have no record of that device.
,I/BluetoothBondStateMachine( 2106): bondStateChangeCallback: Status: 0 Address: B4:CE:F6:AB:A4:6A newState: 0
D/BluetoothAdapterProperties( 2106): Failed to remove device: B4:CE:F6:AB:A4:6A
,I/BluetoothBondStateMachine( 2106): Bond State Change Intent:B4:CE:F6:AB:A4:6A OldState: 11 NewState: 10
,W/BluetoothEventManager( 2727): CachedBluetoothDevice for device B4:CE:F6:AB:A4:6A not found, calling readPairedDevices().
,E/BluetoothEventManager( 2727): Got bonding state changed for B4:CE:F6:AB:A4:6A, but we have no record of that device.
,I/BluetoothBondStateMachine( 2106): StableState(): Entering Off State
,W/bt-btif ( 2106): info:x10
,D/        ( 2106): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
,E/BluetoothRemoteDevices( 2106): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 2106): new conn_srvc id:26, app_id:255
W/bt-btif ( 2106): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2106): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): Incoming connection accepted
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): Incoming connection initialized (thread ID: 299)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3228): Entering thread (ID: 299)
,E/bt-btm  ( 2106): tBTM_SEC_DEV:0xa41bdebc rs_disc_pending=1
,W/bt-btif ( 2106): bta_dm_check_av:0
,W/bt-btif ( 2106): btif_dm_cback : unhandled event (14)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): onBytesRead: Read 84 bytes successfully (thread ID: 299)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): Got valid identity from [B4:CE:F6:AB:A4:6A HTC-HTC Desire 820_PT8021 B4:CE:F6:AB:A4:6A]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): onBytesWritten: 77 bytes successfully written (thread ID: 299)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): removeThreadFromList: Removing thread with ID 299
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): Handshake thread disposed (thread ID: 299)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3228): onIncomingConnectionConnected: [B4:CE:F6:AB:A4:6A HTC-HTC Desire 820_PT8021 B4:CE:F6:AB:A4:6A]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3228): Exiting thread (ID: 299)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onConnected: [B4:CE:F6:AB:A4:6A HTC-HTC Desire 820_PT8021 B4:CE:F6:AB:A4:6A]
I/io.jxcore.node.ConnectionHelper( 3228): onConnected: Incoming connection, peer ID: B4:CE:F6:AB:A4:6A, name: HTC-HTC Desire 820_PT8021, Bluetooth address: B4:CE:F6:AB:A4:6A
D/io.jxcore.node.ConnectionHelper( 3228): hasConnection: No connection with peer with ID B4:CE:F6:AB:A4:6A
I/io.jxcore.node.ConnectionHelper( 3228): addNewPeerToListAndNotify: Adding peer with ID B4:CE:F6:AB:A4:6A
,I/io.jxcore.node.ConnectionHelper( 3228): onConnected: Incoming socket thread, for peer with ID B4:CE:F6:AB:A4:6A, created successfully
D/io.jxcore.node.ConnectionHelper( 3228): onConnected: The total number of connections is now 1
,D/io.jxcore.node.IncomingSocketThread( 3228): Entering thread (ID: 300)
,I/io.jxcore.node.IncomingSocketThread( 3228): Local host address: localhost/127.0.0.1, port: 45763
D/io.jxcore.node.IncomingSocketThread( 3228): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3228): setBufferSize: Setting buffer size to 8192 bytes
,I/jxcore-log( 3228): 2015-12-11T19:12:39.658Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3228): 
,I/io.jxcore.node.StreamCopyingThread( 3228): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3228): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3228): Exiting thread (ID: 300)
,I/io.jxcore.node.StreamCopyingThread( 3228): Entering thread (ID: 302, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 3228): Entering thread (ID: 301, name: Sender)
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/WifiP2pManager( 3228): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service request added successfully
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 2106): tBTM_SEC_DEV:0xa41bdebc rs_disc_pending=0
W/bt-btif ( 2106): bta_dm_check_av:0
,W/bt-btif ( 2106): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3228): 2015-12-11T19:12:40.701Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:12:40.811Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:12:40.846Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:12:40.860Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3228): 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceListChanged: Got empty list
,I/jxcore-log( 3228): 2015-12-11T19:12:41.173Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3228): 
,W/bt-sdp  ( 2106): process_service_search_attr_rsp
,I/jxcore-log( 3228): 2015-12-11T19:12:41.329Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:12:41.545Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:12:41.614Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:12:41.654Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:12:41.665Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:12:41.717Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:12:41.815Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:12:41.851Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:12:41.858Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:12:41.868Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:12:41.986Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:12:42.003Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:12:42.042Z SendDataTCPServer.js: TCP/IP server has received 35640 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:12:42.147Z SendDataTCPServer.js: TCP/IP server has received 37620 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:12:42.157Z SendDataTCPServer.js: TCP/IP server has received 39600 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:12:42.187Z SendDataTCPServer.js: TCP/IP server has received 41580 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:12:42.255Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:12:42.301Z SendDataTCPServer.js: TCP/IP server has received 45540 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:12:42.354Z SendDataTCPServer.js: TCP/IP server has received 47520 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:12:42.398Z SendDataTCPServer.js: TCP/IP server has received 49500 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:12:42.437Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:12:42.453Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:12:42.492Z SendDataTCPServer.js: TCP/IP server has received 55440 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:12:42.497Z SendDataTCPServer.js: TCP/IP server has received 57420 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:12:42.659Z SendDataTCPServer.js: TCP/IP server has received 59400 bytes of data
I/jxcore-log( 3228): 
,I/BluetoothBondStateMachine( 2106): bondStateChangeCallback: Status: 0 Address: E0:DB:10:1F:C9:5E newState: 1
E/bt-btif ( 2106): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2106): Bond State Change Intent:E0:DB:10:1F:C9:5E OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2106): Entering PendingCommandState State
,I/jxcore-log( 3228): 2015-12-11T19:12:42.772Z SendDataTCPServer.js: TCP/IP server has received 61380 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:12:42.786Z SendDataTCPServer.js: TCP/IP server has received 65340 bytes of data
I/jxcore-log( 3228): 
,W/BluetoothEventManager( 2727): CachedBluetoothDevice for device E0:DB:10:1F:C9:5E not found, calling readPairedDevices().
,E/BluetoothEventManager( 2727): Got bonding state changed for E0:DB:10:1F:C9:5E, but we have no record of that device.
,I/jxcore-log( 3228): 2015-12-11T19:12:42.835Z SendDataTCPServer.js: TCP/IP server has received 67320 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:12:42.883Z SendDataTCPServer.js: TCP/IP server has received 69300 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:12:42.889Z SendDataTCPServer.js: TCP/IP server has received 71280 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:12:42.898Z SendDataTCPServer.js: TCP/IP server has received 73260 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:12:42.929Z SendDataTCPServer.js: TCP/IP server has received 75240 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:12:42.939Z SendDataTCPServer.js: TCP/IP server has received 77220 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:12:42.945Z SendDataTCPServer.js: TCP/IP server has received 79200 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:12:43.074Z SendDataTCPServer.js: TCP/IP server has received 81180 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:12:43.087Z SendDataTCPServer.js: TCP/IP server has received 83160 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:12:43.121Z SendDataTCPServer.js: TCP/IP server has received 87120 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:12:43.204Z SendDataTCPServer.js: TCP/IP server has received 89100 bytes of data
I/jxcore-log( 3228): 
,I/BluetoothBondStateMachine( 2106): bondStateChangeCallback: Status: 0 Address: E0:DB:10:1F:C9:5E newState: 0
,D/BluetoothAdapterProperties( 2106): Failed to remove device: E0:DB:10:1F:C9:5E
,W/BluetoothEventManager( 2727): CachedBluetoothDevice for device E0:DB:10:1F:C9:5E not found, calling readPairedDevices().
,I/jxcore-log( 3228): 2015-12-11T19:12:43.244Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:12:43.256Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 3228): 
,I/BluetoothBondStateMachine( 2106): Bond State Change Intent:E0:DB:10:1F:C9:5E OldState: 11 NewState: 10
,I/jxcore-log( 3228): 2015-12-11T19:12:43.274Z SendDataTCPServer.js: TCP/IP server has received 95040 bytes of data
I/jxcore-log( 3228): 
,I/BluetoothBondStateMachine( 2106): StableState(): Entering Off State
,E/BluetoothEventManager( 2727): Got bonding state changed for E0:DB:10:1F:C9:5E, but we have no record of that device.
,I/jxcore-log( 3228): 2015-12-11T19:12:43.309Z SendDataTCPServer.js: TCP/IP server has received 99000 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:12:43.353Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3228): 
,E/bt-btm  ( 2106): tBTM_SEC_DEV:0xa41be084 rs_disc_pending=0
W/bt-btif ( 2106): bta_dm_check_av:0
,W/bt-btif ( 2106): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2106): new conn_srvc id:26, app_id:1
W/bt-btif ( 2106): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2106): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3228): onSocketConnected: Authenticating next: [E0:DB:10:1F:C9:5E E0:DB:10:1F:C9:5E E0:DB:10:1F:C9:5E]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): Socket connection succeeded using port (1), total number of attempts: 1 (thread ID: 298)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): onBytesWritten: 77 bytes successfully written (thread ID: 303)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): Outgoing connection initialized (*handshake* thread ID: 303)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): Exiting thread (thread ID: 298)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3228): Entering thread (ID: 303)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): onBytesRead: Read 82 bytes successfully (thread ID: 303)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): Handshake succeeded with [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT7716 E0:DB:10:1F:C9:5E]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3228): onAuthenticated: Fully connected: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT7716 E0:DB:10:1F:C9:5E]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3228): Exiting thread (ID: 303)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onConnected: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT7716 E0:DB:10:1F:C9:5E]
I/io.jxcore.node.ConnectionHelper( 3228): onConnected: Outgoing connection, peer ID: E0:DB:10:1F:C9:5E, name: samsung-SM-N9005_PT7716, Bluetooth address: E0:DB:10:1F:C9:5E
D/io.jxcore.node.ConnectionHelper( 3228): hasConnection: No connection with peer with ID E0:DB:10:1F:C9:5E
I/io.jxcore.node.ConnectionHelper( 3228): addNewPeerToListAndNotify: Adding peer with ID E0:DB:10:1F:C9:5E
,I/io.jxcore.node.ConnectionHelper( 3228): onConnected: Outgoing socket thread, for peer with ID E0:DB:10:1F:C9:5E, created successfully
D/io.jxcore.node.ConnectionHelper( 3228): onConnected: The total number of connections is now 2
,D/io.jxcore.node.OutgoingSocketThread( 3228): Entering thread (ID: 304)
,D/io.jxcore.node.OutgoingSocketThread( 3228): Server socket local port: 57035
,I/io.jxcore.node.OutgoingSocketThread( 3228): Now accepting connections...
,W/bt-btif ( 2106): invalid rfc slot id: 4
,W/io.jxcore.node.StreamCopyingThread( 3228): Either failed to read from the output stream or write to the input stream (thread ID: 302, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 3228): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3228): onDisconnected: Incoming connection, peer with ID B4:CE:F6:AB:A4:6A disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3228): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 300
I/io.jxcore.node.OutgoingSocketThread( 3228): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3228): doStop: Thread ID: 302
I/io.jxcore.node.OutgoingSocketThread( 3228): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3228): doStop: Thread ID: 301
I/io.jxcore.node.OutgoingSocketThread( 3228): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.OutgoingSocketThread( 3228): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3228): Either failed to read from the output stream or write to the input stream (thread ID: 301, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3228): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3228): onDisconnected: Incoming connection, peer with ID B4:CE:F6:AB:A4:6A disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.OutgoingSocketThread( 3228): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.OutgoingSocketThread( 3228): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3228): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3228): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.ConnectionHelper( 3228): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,I/io.jxcore.node.StreamCopyingThread( 3228): Exiting thread (ID: 301, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 3228): Exiting thread (ID: 302, name: Receiver)
,I/jxcore-log( 3228): 2015-12-11T19:12:45.184Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3228): 
,I/io.jxcore.node.ConnectionHelper( 3228): onListeningForIncomingConnections: Outgoing connection is using port 57035 (peer ID: E0:DB:10:1F:C9:5E)
I/jxcore-log( 3228): 2015-12-11T19:12:45.263Z SendDataConnector.js: CLIENT connected to 57035, error: null
I/jxcore-log( 3228): 
I/jxcore-log( 3228): 2015-12-11T19:12:45.263Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3228): 
,I/io.jxcore.node.OutgoingSocketThread( 3228): Incoming data from address: /127.0.0.1, port: 57035
D/io.jxcore.node.OutgoingSocketThread( 3228): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3228): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3228): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3228): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3228): Exiting thread (ID: 304)
,I/io.jxcore.node.StreamCopyingThread( 3228): Entering thread (ID: 306, name: Receiver)
,I/jxcore-log( 3228): 2015-12-11T19:12:45.269Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3228): 
,I/io.jxcore.node.StreamCopyingThread( 3228): Entering thread (ID: 305, name: Sender)
,E/bt-btm  ( 2106): tBTM_SEC_DEV:0xa41be084 rs_disc_pending=1
W/bt-btif ( 2106): bta_dm_check_av:0
,W/bt-btif ( 2106): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 2106): rfc_find_lcid_mcb LCID reused LCID:0x43 current:0x0
W/bt-rfcomm( 2106): RFCOMM_DisconnectInd LCID:0x43
,E/bt-btm  ( 2106): tBTM_SEC_DEV:0xa41bdebc rs_disc_pending=1
W/bt-btif ( 2106): bta_dm_check_av:0
,W/bt-btif ( 2106): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3228): 2015-12-11T19:12:47.293Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3228): 
,D/btif_config_util( 2106): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3228): 2015-12-11T19:12:47.874Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:12:48.366Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:12:48.845Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:12:49.409Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3228): 
,E/bt-btm  ( 2106): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2106): onReceive
,D/BluetoothManagerService(  757): Message: 20
D/BluetoothManagerService(  757): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@138d33e0:true
,I/BTConnectionReceiver( 1380): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B4:CE:F6:AB:A4:6A, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1380): Bluetooth Device Name: HTC Desire 820
,I/jxcore-log( 3228): 2015-12-11T19:12:49.852Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:12:50.310Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:12:50.475Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:12:50.595Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:12:50.676Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:12:50.683Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:12:50.704Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3228): 
I/jxcore-log( 3228): 2015-12-11T19:12:50.705Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3228): 
,D/io.jxcore.node.ConnectionHelper( 3228): disconnectOutgoingConnection: Trying to close connection to peer with ID E0:DB:10:1F:C9:5E
I/io.jxcore.node.ConnectionHelper( 3228): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: E0:DB:10:1F:C9:5E
I/io.jxcore.node.OutgoingSocketThread( 3228): close
I/io.jxcore.node.OutgoingSocketThread( 3228): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3228): doStop: Thread ID: 306
I/io.jxcore.node.OutgoingSocketThread( 3228): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3228): doStop: Thread ID: 305
I/io.jxcore.node.OutgoingSocketThread( 3228): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.OutgoingSocketThread( 3228): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3228): Either failed to read from the output stream or write to the input stream (thread ID: 305, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3228): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3228): onDisconnected: Outgoing connection, peer with ID E0:DB:10:1F:C9:5E disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.OutgoingSocketThread( 3228): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.OutgoingSocketThread( 3228): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3228): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3228): Either failed to read from the output stream or write to the input stream (thread ID: 306, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 3228): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3228): onDisconnected: Outgoing connection, peer with ID E0:DB:10:1F:C9:5E disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3228): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3228): disconnectOutgoingConnection: Successfully disconnected (peer ID: E0:DB:10:1F:C9:5E
,E/io.jxcore.node.ConnectionHelper( 3228): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID E0:DB:10:1F:C9:5E
D/io.jxcore.node.ConnectionHelper( 3228): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3228): Exiting thread (ID: 305, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 3228): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID E0:DB:10:1F:C9:5E
D/io.jxcore.node.ConnectionHelper( 3228): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,I/io.jxcore.node.StreamCopyingThread( 3228): Exiting thread (ID: 306, name: Receiver)
,I/jxcore-log( 3228): 2015-12-11T19:12:50.755Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): ---- round done--------
I/jxcore-log( 3228): 
I/jxcore-log( 3228): do fake peer & start
I/jxcore-log( 3228): 
I/jxcore-log( 3228): Connect to fake peer: F8:CF:C5:D9:E5:61
I/jxcore-log( 3228): 
I/jxcore-log( 3228): 2015-12-11T19:12:50.756Z SendDataConnector.js: Start called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 3228): 
I/jxcore-log( 3228): 2015-12-11T19:12:50.756Z SendDataConnector.js: doConnect called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 3228): 
I/jxcore-log( 3228): 2015-12-11T19:12:50.756Z SendDataConnector.js: do connect now
I/jxcore-log( 3228): 
I/io.jxcore.node.ConnectionHelper( 3228): connect: Trying to connect to peer with ID F8:CF:C5:D9:E5:61
D/io.jxcore.node.ConnectionHelper( 3228): hasConnection: No connection with peer with ID F8:CF:C5:D9:E5:61
W/io.jxcore.node.ConnectionHelper( 3228): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3228): connect: Trying to start connecting to null in address F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onConnecting: null F8:CF:C5:D9:E5:61
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3228): connect: Started connecting to null in address F8:CF:C5:D9:E5:61
I/io.jxcore.node.ConnectionHelper( 3228): connect: Connection process successfully started (peer ID: F8:CF:C5:D9:E5:61)
I/chromium( 3228): [INFO:CONSOLE(63)] "logCallback Round of send data to peer E0:DB:10:1F:C9:5E done with result: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): Trying to connect to peer with address F8:CF:C5:D9:E5:61 (thread ID: 307)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3228): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3228): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2106): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2106): tBTM_SEC_DEV:0xa41bdebc rs_disc_pending=0
W/bt-btif ( 2106): bta_dm_check_av:0
,W/bt-btif ( 2106): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2106): bta_jv_rfc_port_to_cb(port_handle:0x9):jv handle:0x0 not FOUND
,E/bt-btm  ( 2106): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2106): onReceive
,I/BTConnectionReceiver( 1380): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1380): Bluetooth Device Name: Note3-1
,W/bt-btif ( 2106): info:x10
,D/        ( 2106): remote version info [f8:cf:c5:d9:e5:61]: 7, f, 230f
,E/BluetoothRemoteDevices( 2106): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2106): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2106): bondStateChangeCallback: Status: 0 Address: F8:CF:C5:D9:E5:61 newState: 1
E/bt-btif ( 2106): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2106): Bond State Change Intent:F8:CF:C5:D9:E5:61 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2106): Entering PendingCommandState State
,W/BluetoothEventManager( 2727): CachedBluetoothDevice for device F8:CF:C5:D9:E5:61 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2727): Got bonding state changed for F8:CF:C5:D9:E5:61, but we have no record of that device.
,I/BluetoothBondStateMachine( 2106): bondStateChangeCallback: Status: 0 Address: F8:CF:C5:D9:E5:61 newState: 0
,D/BluetoothAdapterProperties( 2106): Failed to remove device: F8:CF:C5:D9:E5:61
,I/BluetoothBondStateMachine( 2106): Bond State Change Intent:F8:CF:C5:D9:E5:61 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2106): StableState(): Entering Off State
,W/BluetoothEventManager( 2727): CachedBluetoothDevice for device F8:CF:C5:D9:E5:61 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2727): Got bonding state changed for F8:CF:C5:D9:E5:61, but we have no record of that device.
,W/bt-btif ( 2106): new conn_srvc id:26, app_id:1
W/bt-btif ( 2106): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2106): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3228): onSocketConnected: Authenticating next: [F8:CF:C5:D9:E5:61 F8:CF:C5:D9:E5:61 F8:CF:C5:D9:E5:61]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): Socket connection succeeded using port (1), total number of attempts: 1 (thread ID: 307)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): onBytesWritten: 77 bytes successfully written (thread ID: 308)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): Outgoing connection initialized (*handshake* thread ID: 308)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): Exiting thread (thread ID: 307)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3228): Entering thread (ID: 308)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): onBytesRead: Read 82 bytes successfully (thread ID: 308)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): Handshake succeeded with [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT3473 F8:CF:C5:D9:E5:61]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3228): onAuthenticated: Fully connected: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT3473 F8:CF:C5:D9:E5:61]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3228): Exiting thread (ID: 308)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onConnected: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT3473 F8:CF:C5:D9:E5:61]
I/io.jxcore.node.ConnectionHelper( 3228): onConnected: Outgoing connection, peer ID: F8:CF:C5:D9:E5:61, name: motorola-Nexus 6_PT3473, Bluetooth address: F8:CF:C5:D9:E5:61
D/io.jxcore.node.ConnectionHelper( 3228): hasConnection: No connection with peer with ID F8:CF:C5:D9:E5:61
I/io.jxcore.node.ConnectionHelper( 3228): addNewPeerToListAndNotify: Adding peer with ID F8:CF:C5:D9:E5:61
I/io.jxcore.node.ConnectionHelper( 3228): onConnected: Outgoing socket thread, for peer with ID F8:CF:C5:D9:E5:61, created successfully
D/io.jxcore.node.ConnectionHelper( 3228): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 3228): Entering thread (ID: 309)
,D/io.jxcore.node.OutgoingSocketThread( 3228): Server socket local port: 47616
I/io.jxcore.node.OutgoingSocketThread( 3228): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3228): onListeningForIncomingConnections: Outgoing connection is using port 47616 (peer ID: F8:CF:C5:D9:E5:61)
I/jxcore-log( 3228): 2015-12-11T19:13:00.085Z SendDataConnector.js: CLIENT connected to 47616, error: null
I/jxcore-log( 3228): 
I/jxcore-log( 3228): 2015-12-11T19:13:00.085Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3228): 
,I/io.jxcore.node.OutgoingSocketThread( 3228): Incoming data from address: /127.0.0.1, port: 47616
D/io.jxcore.node.OutgoingSocketThread( 3228): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3228): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3228): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3228): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3228): Exiting thread (ID: 309)
,I/jxcore-log( 3228): 2015-12-11T19:13:00.094Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3228): 
,I/io.jxcore.node.StreamCopyingThread( 3228): Entering thread (ID: 311, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 3228): Entering thread (ID: 310, name: Sender)
,D/        ( 2106): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23716
,I/jxcore-log( 3228): 2015-12-11T19:13:01.016Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:13:01.090Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3228): 
,D/        ( 2106): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:12826
,I/jxcore-log( 3228): 2015-12-11T19:13:01.138Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:13:01.193Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3228): 
,D/        ( 2106): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:3916
,I/jxcore-log( 3228): 2015-12-11T19:13:01.236Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:13:01.268Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:13:01.339Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:13:01.504Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:13:01.574Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:13:01.620Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3228): 
I/jxcore-log( 3228): 2015-12-11T19:13:01.621Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:13:01.637Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3228): 
I/jxcore-log( 3228): 2015-12-11T19:13:01.637Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3228): 
,D/io.jxcore.node.ConnectionHelper( 3228): disconnectOutgoingConnection: Trying to close connection to peer with ID F8:CF:C5:D9:E5:61
I/io.jxcore.node.ConnectionHelper( 3228): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: F8:CF:C5:D9:E5:61
I/io.jxcore.node.OutgoingSocketThread( 3228): close
I/io.jxcore.node.OutgoingSocketThread( 3228): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3228): doStop: Thread ID: 311
I/io.jxcore.node.OutgoingSocketThread( 3228): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3228): doStop: Thread ID: 310
I/io.jxcore.node.OutgoingSocketThread( 3228): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.OutgoingSocketThread( 3228): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3228): Either failed to read from the output stream or write to the input stream (thread ID: 310, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3228): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3228): onDisconnected: Outgoing connection, peer with ID F8:CF:C5:D9:E5:61 disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.OutgoingSocketThread( 3228): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.OutgoingSocketThread( 3228): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3228): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3228): Either failed to read from the output stream or write to the input stream (thread ID: 311, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 3228): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3228): onDisconnected: Outgoing connection, peer with ID F8:CF:C5:D9:E5:61 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3228): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3228): disconnectOutgoingConnection: Successfully disconnected (peer ID: F8:CF:C5:D9:E5:61
,E/io.jxcore.node.ConnectionHelper( 3228): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:CF:C5:D9:E5:61,
D/io.jxcore.node.ConnectionHelper( 3228): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3228): Exiting thread (ID: 310, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 3228): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:CF:C5:D9:E5:61
,D/io.jxcore.node.ConnectionHelper( 3228): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3228): Exiting thread (ID: 311, name: Receiver)
,I/jxcore-log( 3228): 2015-12-11T19:13:01.675Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): ---- round done--------
I/jxcore-log( 3228): 
I/jxcore-log( 3228): do fake peer & start
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): Connect to fake peer: 34:FC:EF:11:B1:66
I/jxcore-log( 3228): 
I/jxcore-log( 3228): 2015-12-11T19:13:01.676Z SendDataConnector.js: Start called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3228): 
I/jxcore-log( 3228): 2015-12-11T19:13:01.676Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3228): 
I/jxcore-log( 3228): 2015-12-11T19:13:01.676Z SendDataConnector.js: do connect now
I/jxcore-log( 3228): 
,I/io.jxcore.node.ConnectionHelper( 3228): connect: Trying to connect to peer with ID 34:FC:EF:11:B1:66
D/io.jxcore.node.ConnectionHelper( 3228): hasConnection: No connection with peer with ID 34:FC:EF:11:B1:66
,W/io.jxcore.node.ConnectionHelper( 3228): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3228): connect: Trying to start connecting to null in address 34:FC:EF:11:B1:66
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onConnecting: null 34:FC:EF:11:B1:66
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3228): connect: Started connecting to null in address 34:FC:EF:11:B1:66
I/io.jxcore.node.ConnectionHelper( 3228): connect: Connection process successfully started (peer ID: 34:FC:EF:11:B1:66)
I/chromium( 3228): [INFO:CONSOLE(63)] "logCallback Round of send data to peer F8:CF:C5:D9:E5:61 done with result: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): Trying to connect to peer with address 34:FC:EF:11:B1:66 (thread ID: 312)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3228): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3228): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2106): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2106): tBTM_SEC_DEV:0xa41be24c rs_disc_pending=1
W/bt-btif ( 2106): bta_dm_check_av:0
,W/bt-btif ( 2106): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2106): tBTM_SEC_DEV:0xa41be24c rs_disc_pending=0
W/bt-btif ( 2106): bta_dm_check_av:0
,W/bt-btif ( 2106): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2106): bta_jv_rfc_port_to_cb(port_handle:0xa):jv handle:0x0 not FOUND
,W/bt-btif ( 2106): info:x10
,D/        ( 2106): remote version info [58:3f:54:73:64:c0]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 2106): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 2106): info:x10
,D/        ( 2106): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
,E/BluetoothRemoteDevices( 2106): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2106): tBTM_SEC_DEV:0xa41be414 rs_disc_pending=0
W/bt-btif ( 2106): bta_dm_check_av:0
,W/bt-btif ( 2106): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2106): tBTM_SEC_DEV:0xa41be24c rs_disc_pending=1
W/bt-btif ( 2106): bta_dm_check_av:0
,W/bt-btif ( 2106): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2106): tBTM_SEC_DEV:0xa41be5dc rs_disc_pending=0
W/bt-btif ( 2106): bta_dm_check_av:0
,W/bt-btif ( 2106): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 2106): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2106): bondStateChangeCallback: Status: 0 Address: 58:3F:54:73:64:C0 newState: 1
E/bt-btif ( 2106): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2106): Bond State Change Intent:58:3F:54:73:64:C0 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2106): Entering PendingCommandState State
,W/BluetoothEventManager( 2727): CachedBluetoothDevice for device 58:3F:54:73:64:C0 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2727): Got bonding state changed for 58:3F:54:73:64:C0, but we have no record of that device.
,E/bt-btm  ( 2106): tBTM_SEC_DEV:0xa41be24c rs_disc_pending=0
W/bt-btif ( 2106): bta_dm_check_av:0
,W/bt-btif ( 2106): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 2106): bondStateChangeCallback: Status: 0 Address: 58:3F:54:73:64:C0 newState: 0
,D/BluetoothAdapterProperties( 2106): Failed to remove device: 58:3F:54:73:64:C0
,I/BluetoothBondStateMachine( 2106): Bond State Change Intent:58:3F:54:73:64:C0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2106): StableState(): Entering Off State
,W/BluetoothEventManager( 2727): CachedBluetoothDevice for device 58:3F:54:73:64:C0 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2727): Got bonding state changed for 58:3F:54:73:64:C0, but we have no record of that device.
,W/bt-btif ( 2106): new conn_srvc id:26, app_id:255
W/bt-btif ( 2106): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2106): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): Incoming connection accepted
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): Incoming connection initialized (thread ID: 313)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3228): Entering thread (ID: 313)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): onBytesRead: Read 77 bytes successfully (thread ID: 313)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): Got valid identity from [58:3F:54:73:64:C0 LGE-LG-D855_PT2944 58:3F:54:73:64:C0]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): onBytesWritten: 77 bytes successfully written (thread ID: 313)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): removeThreadFromList: Removing thread with ID 313
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): Handshake thread disposed (thread ID: 313)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3228): onIncomingConnectionConnected: [58:3F:54:73:64:C0 LGE-LG-D855_PT2944 58:3F:54:73:64:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3228): Exiting thread (ID: 313)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onConnected: [58:3F:54:73:64:C0 LGE-LG-D855_PT2944 58:3F:54:73:64:C0]
I/io.jxcore.node.ConnectionHelper( 3228): onConnected: Incoming connection, peer ID: 58:3F:54:73:64:C0, name: LGE-LG-D855_PT2944, Bluetooth address: 58:3F:54:73:64:C0
,D/io.jxcore.node.ConnectionHelper( 3228): hasConnection: No connection with peer with ID 58:3F:54:73:64:C0
I/io.jxcore.node.ConnectionHelper( 3228): addNewPeerToListAndNotify: Adding peer with ID 58:3F:54:73:64:C0
,I/io.jxcore.node.ConnectionHelper( 3228): onConnected: Incoming socket thread, for peer with ID 58:3F:54:73:64:C0, created successfully
D/io.jxcore.node.ConnectionHelper( 3228): onConnected: The total number of connections is now 1
,D/io.jxcore.node.IncomingSocketThread( 3228): Entering thread (ID: 314)
,I/jxcore-log( 3228): 2015-12-11T19:13:05.446Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3228): 
,I/io.jxcore.node.IncomingSocketThread( 3228): Local host address: localhost/127.0.0.1, port: 45763
D/io.jxcore.node.IncomingSocketThread( 3228): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3228): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3228): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3228): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3228): Exiting thread (ID: 314)
,I/io.jxcore.node.StreamCopyingThread( 3228): Entering thread (ID: 315, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 3228): Entering thread (ID: 316, name: Receiver)
,E/bt-btm  ( 2106): tBTM_SEC_DEV:0xa41be24c rs_disc_pending=1
W/bt-btif ( 2106): bta_dm_check_av:0
,W/bt-btif ( 2106): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 2106): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:B1:66 newState: 1
E/bt-btif ( 2106): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2106): Bond State Change Intent:34:FC:EF:11:B1:66 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2106): Entering PendingCommandState State
,W/BluetoothEventManager( 2727): CachedBluetoothDevice for device 34:FC:EF:11:B1:66 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2727): Got bonding state changed for 34:FC:EF:11:B1:66, but we have no record of that device.
,E/bt-btm  ( 2106): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2106): onReceive
,I/BTConnectionReceiver( 1380): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1380): Bluetooth Device Name: Nexus 6
,I/BluetoothBondStateMachine( 2106): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:B1:66 newState: 0
,D/BluetoothAdapterProperties( 2106): Failed to remove device: 34:FC:EF:11:B1:66
,I/BluetoothBondStateMachine( 2106): Bond State Change Intent:34:FC:EF:11:B1:66 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2106): StableState(): Entering Off State
,W/BluetoothEventManager( 2727): CachedBluetoothDevice for device 34:FC:EF:11:B1:66 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2727): Got bonding state changed for 34:FC:EF:11:B1:66, but we have no record of that device.
,E/bt-btm  ( 2106): tBTM_SEC_DEV:0xa41be5dc rs_disc_pending=1
W/bt-btif ( 2106): bta_dm_check_av:0
,W/bt-btif ( 2106): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3228): 2015-12-11T19:13:06.710Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:13:06.859Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:13:06.941Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:13:07.333Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:13:07.408Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:13:07.512Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:13:07.530Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:13:07.614Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:13:07.622Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:13:08.059Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:13:08.143Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:13:08.736Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:13:08.778Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:13:08.895Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:13:09.229Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:13:09.313Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:13:09.436Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:13:09.471Z SendDataTCPServer.js: TCP/IP server has received 32768 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:13:09.497Z SendDataTCPServer.js: TCP/IP server has received 34748 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:13:09.525Z SendDataTCPServer.js: TCP/IP server has received 36728 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:13:09.873Z SendDataTCPServer.js: TCP/IP server has received 38708 bytes of data
I/jxcore-log( 3228): 
,D/btif_config_util( 2106): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): stopServiceDiscovery
,I/wpa_supplicant( 1047): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Peer discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Peer discovery stopped successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3228): onPeerListChanged: Got a list of peers, which is null
,I/jxcore-log( 3228): 2015-12-11T19:13:10.592Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:13:10.670Z SendDataTCPServer.js: TCP/IP server has received 42668 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:13:10.702Z SendDataTCPServer.js: TCP/IP server has received 44648 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:13:11.144Z SendDataTCPServer.js: TCP/IP server has received 46628 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:13:11.158Z SendDataTCPServer.js: TCP/IP server has received 48608 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:13:11.188Z SendDataTCPServer.js: TCP/IP server has received 50588 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:13:11.263Z SendDataTCPServer.js: TCP/IP server has received 52568 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:13:11.301Z SendDataTCPServer.js: TCP/IP server has received 56528 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:13:11.762Z SendDataTCPServer.js: TCP/IP server has received 58508 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:13:11.801Z SendDataTCPServer.js: TCP/IP server has received 60488 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:13:11.885Z SendDataTCPServer.js: TCP/IP server has received 62468 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:13:11.921Z SendDataTCPServer.js: TCP/IP server has received 64448 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:13:12.000Z SendDataTCPServer.js: TCP/IP server has received 66428 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:13:12.455Z SendDataTCPServer.js: TCP/IP server has received 68408 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:13:12.484Z SendDataTCPServer.js: TCP/IP server has received 70388 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:13:12.493Z SendDataTCPServer.js: TCP/IP server has received 72368 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:13:12.633Z SendDataTCPServer.js: TCP/IP server has received 74348 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:13:12.639Z SendDataTCPServer.js: TCP/IP server has received 76328 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:13:12.694Z SendDataTCPServer.js: TCP/IP server has received 78308 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:13:12.748Z SendDataTCPServer.js: TCP/IP server has received 80288 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:13:12.788Z SendDataTCPServer.js: TCP/IP server has received 82268 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:13:12.822Z SendDataTCPServer.js: TCP/IP server has received 84248 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:13:12.831Z SendDataTCPServer.js: TCP/IP server has received 86228 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:13:12.838Z SendDataTCPServer.js: TCP/IP server has received 88208 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:13:12.917Z SendDataTCPServer.js: TCP/IP server has received 90188 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:13:12.929Z SendDataTCPServer.js: TCP/IP server has received 92168 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:13:12.950Z SendDataTCPServer.js: TCP/IP server has received 94148 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:13:13.048Z SendDataTCPServer.js: TCP/IP server has received 96128 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:13:13.079Z SendDataTCPServer.js: TCP/IP server has received 98108 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:13:13.085Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3228): 
,W/bt-btif ( 2106): invalid rfc slot id: 6
,W/io.jxcore.node.StreamCopyingThread( 3228): Either failed to read from the output stream or write to the input stream (thread ID: 316, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.IncomingSocketThread( 3228): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
,E/bt-btm  ( 2106): tBTM_SEC_DEV:0xa41be5dc rs_disc_pending=1
W/bt-btif ( 2106): bta_dm_check_av:0
,W/bt-btif ( 2106): btif_dm_cback : unhandled event (14)
,W/io.jxcore.node.ConnectionHelper( 3228): onDisconnected: Incoming connection, peer with ID 58:3F:54:73:64:C0 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3228): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 314
I/io.jxcore.node.IncomingSocketThread( 3228): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3228): doStop: Thread ID: 316
I/io.jxcore.node.IncomingSocketThread( 3228): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3228): doStop: Thread ID: 315
I/io.jxcore.node.IncomingSocketThread( 3228): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.IncomingSocketThread( 3228): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3228): Either failed to read from the output stream or write to the input stream (thread ID: 315, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3228): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3228): onDisconnected: Incoming connection, peer with ID 58:3F:54:73:64:C0 disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.IncomingSocketThread( 3228): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.IncomingSocketThread( 3228): closeLocalSocketAndStreams: Closing the localhost socket...
,I/io.jxcore.node.IncomingSocketThread( 3228): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3228): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.ConnectionHelper( 3228): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3228): Exiting thread (ID: 315, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 3228): Exiting thread (ID: 316, name: Receiver)
,I/jxcore-log( 3228): 2015-12-11T19:13:13.444Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3228): 
,W/bt-rfcomm( 2106): rfc_find_lcid_mcb LCID reused LCID:0x4b current:0x0
W/bt-rfcomm( 2106): RFCOMM_DisconnectInd LCID:0x4b
,E/bt-btm  ( 2106): tBTM_SEC_DEV:0xa41be414 rs_disc_pending=1
W/bt-btif ( 2106): bta_dm_check_av:0
,W/bt-btif ( 2106): btif_dm_cback : unhandled event (14)
E/bt-btm  ( 2106): btm_sec_disconnected - Clearing Pending flag
W/bt-l2cap( 2106): L2CAP got sec_comp for unknown BD_ADDR
W/bt-btif ( 2106): invalid rfc slot id: 8
,W/BluetoothAdapter( 3228): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothMapService( 2106): onReceive
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): start: Starting peer discovery...
,D/BTIF_SOCK( 2106): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/BTConnectionReceiver( 1380): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:B1:66, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1380): Bluetooth Device Name: Nexus 5
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 2106): tBTM_SEC_DEV:0xa41be5dc rs_disc_pending=0
W/bt-btif ( 2106): bta_dm_check_av:0
,W/bt-btif ( 2106): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3228): Connection timeout
,I/wpa_supplicant( 1047): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,E/bt-btm  ( 2106): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2106): onReceive
,I/BTConnectionReceiver( 1380): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1380): Bluetooth Device Name: G3-1
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1047): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 1047): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2106): SDP - Rcvd conn cnf with error: 0x22  CID 0x4e
E/bt-btif ( 2106): DISCOVERY_COMP_EVT slot id:10, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2106): invalid rfc slot id: 10
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 312)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): Trying to connect again in 300 ms... (thread ID: 312)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): shutdown
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3228): onConnectionFailed: Cancelled: Connection timeout
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): stopServiceDiscovery
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onIsDiscoveryStartedChanged: false,
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT6995","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3228): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT6995","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onIsDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onConnectionFailed: Cancelled: Connection timeout [34:FC:EF:11:B1:66 34:FC:EF:11:B1:66 34:FC:EF:11:B1:66]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: 9 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 1: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 2: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 3: Thali Test's G2 36:fc:ef:de:0a:e2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 6: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 7: XT1039_8c05 f4:f1:e1:5c:43:c8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 8: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 9: S5mini-1 02:f4:6f:30:e0:6d
,I/wpa_supplicant( 1047): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: 9 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 1: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 2: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 3: Thali Test's G2 36:fc:ef:de:0a:e2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 6: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 7: XT1039_8c05 f4:f1:e1:5c:43:c8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 8: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 9: S5mini-1 02:f4:6f:30:e0:6d
I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:ff:f0
I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,W/io.jxcore.node.ConnectionHelper( 3228): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: 9 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 1: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 2: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 3: Thali Test's G2 36:fc:ef:de:0a:e2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 6: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 7: XT1039_8c05 f4:f1:e1:5c:43:c8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 8: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 9: S5mini-1 02:f4:6f:30:e0:6d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: 9 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 1: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 2: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 3: Thali Test's G2 36:fc:ef:de:0a:e2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 6: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 7: XT1039_8c05 f4:f1:e1:5c:43:c8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 8: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 9: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
I/jxcore-log( 3228): 2015-12-11T19:13:47.236Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:13:47.237Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:13:47.239Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3228): 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3228): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Peer discovery stopped successfully
,I/wpa_supplicant( 1047): p2p0: P2P: Reject scan trigger since one is already pending
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3228): Local service added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): stopServiceDiscovery
,D/WifiP2pManager( 3228): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service request added successfully
D/WifiP2pManager( 3228): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service request added successfully
D/WifiP2pManager( 3228): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service request added successfully
D/WifiP2pManager( 3228): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/wpa_supplicant( 1047): P2P-FIND-STOPPED 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service request added successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Peer discovery stopped successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerListChanged
,W/io.jxcore.node.ConnectionHelper( 3228): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3228): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3228): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3228): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3228): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3228): onPeerListChanged: Got a list of peers, which is null
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3228): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3228): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3228): onPeerListChanged: Got a list of peers, which is null
,I/wpa_supplicant( 1047): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 1: S5mini-1 02:f4:6f:30:e0:6d
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): Exiting thread (thread ID: 312)
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Failed to start the service discovery, got error code: 3
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Failed to start the service discovery, got error code: 3
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Failed to start the service discovery, got error code: 3
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Failed to start the service discovery, got error code: 3
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service requests cleared successfully
,I/jxcore-log( 3228): 2015-12-11T19:13:52.241Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 3228): 
I/jxcore-log( 3228): 2015-12-11T19:13:52.242Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3228): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): start: Starting peer discovery...
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 1: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 2: Android_63cc 82:01:84:6b:e8:5d
,D/WifiP2pManager( 3228): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service request added successfully
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/io.jxcore.node.ConnectionHelper( 3228): disconnectOutgoingConnection: Trying to close connection to peer with ID 34:FC:EF:11:B1:66
E/io.jxcore.node.ConnectionHelper( 3228): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 34:FC:EF:11:B1:66
D/io.jxcore.node.ConnectionHelper( 3228): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3228): disconnectOutgoingConnection: Failed to disconnect (peer ID: 34:FC:EF:11:B1:66), either no such connection or failed to close the connection
I/jxcore-log( 3228): 2015-12-11T19:13:57.248Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:13:57.252Z SendDataConnector.js: Connect (retry count 1) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 3228): 
I/jxcore-log( 3228): 2015-12-11T19:13:57.254Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3228): 
I/jxcore-log( 3228): 2015-12-11T19:13:57.254Z SendDataConnector.js: do connect now
I/jxcore-log( 3228): 
I/io.jxcore.node.ConnectionHelper( 3228): connect: Trying to connect to peer with ID 34:FC:EF:11:B1:66
D/io.jxcore.node.ConnectionHelper( 3228): hasConnection: No connection with peer with ID 34:FC:EF:11:B1:66
W/io.jxcore.node.ConnectionHelper( 3228): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3228): connect: Trying to start connecting to Nexus 5 in address 34:FC:EF:11:B1:66
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onConnecting: Nexus 5 34:FC:EF:11:B1:66
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3228): connect: Started connecting to Nexus 5 in address 34:FC:EF:11:B1:66
I/io.jxcore.node.ConnectionHelper( 3228): connect: Connection process successfully started (peer ID: 34:FC:EF:11:B1:66)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): Trying to connect to peer with address 34:FC:EF:11:B1:66 (thread ID: 317)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3228): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3228): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2106): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2106): No ag scb for peer addr
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3228): Connection timeout
,W/bt-btif ( 2106): info:x10
,D/        ( 2106): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608
,E/BluetoothRemoteDevices( 2106): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 2106): bondStateChangeCallback: Status: 0 Address: 58:2A:F7:ED:96:BE newState: 1
E/bt-btif ( 2106): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2106): Bond State Change Intent:58:2A:F7:ED:96:BE OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2106): Entering PendingCommandState State
,W/BluetoothEventManager( 2727): CachedBluetoothDevice for device 58:2A:F7:ED:96:BE not found, calling readPairedDevices().
,E/BluetoothEventManager( 2727): Got bonding state changed for 58:2A:F7:ED:96:BE, but we have no record of that device.
,I/BluetoothBondStateMachine( 2106): bondStateChangeCallback: Status: 0 Address: 58:2A:F7:ED:96:BE newState: 0
,D/BluetoothAdapterProperties( 2106): Failed to remove device: 58:2A:F7:ED:96:BE
,I/BluetoothBondStateMachine( 2106): Bond State Change Intent:58:2A:F7:ED:96:BE OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2106): StableState(): Entering Off State
,W/BluetoothEventManager( 2727): CachedBluetoothDevice for device 58:2A:F7:ED:96:BE not found, calling readPairedDevices().
,E/BluetoothEventManager( 2727): Got bonding state changed for 58:2A:F7:ED:96:BE, but we have no record of that device.
,W/bt-btif ( 2106): new conn_srvc id:26, app_id:255
W/bt-btif ( 2106): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2106): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): Incoming connection initialized (thread ID: 318)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3228): Entering thread (ID: 318)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): onBytesRead: Read 80 bytes successfully (thread ID: 318)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): Got valid identity from [58:2A:F7:ED:96:BE HUAWEI-ALE-L21_PT4001 58:2A:F7:ED:96:BE]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): onBytesWritten: 77 bytes successfully written (thread ID: 318)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): removeThreadFromList: Removing thread with ID 318
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): Handshake thread disposed (thread ID: 318)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3228): onIncomingConnectionConnected: [58:2A:F7:ED:96:BE HUAWEI-ALE-L21_PT4001 58:2A:F7:ED:96:BE]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3228): Exiting thread (ID: 318)
,D/btif_config_util( 2106): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 2106): invalid rfc slot id: 9
,W/bt-rfcomm( 2106): rfc_find_lcid_mcb LCID reused LCID:0x42 current:0x0
,W/bt-rfcomm( 2106): RFCOMM_DisconnectInd LCID:0x42
,E/bt-btm  ( 2106): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2106): onReceive
,I/BTConnectionReceiver( 1380): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1380): Bluetooth Device Name: ALE-L21
,W/bt-btif ( 2106): info:x10
,D/        ( 2106): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608
,I/BTConnectionReceiver( 1380): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1380): Bluetooth Device Name: ALE-L21
,E/bt-btif ( 2106): DISCOVERY_COMP_EVT slot id:11, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2106): invalid rfc slot id: 11
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3228): onConnectionFailed: Cancelled: Connection timeout
,W/BluetoothAdapter( 3228): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2106): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): stopServiceDiscovery
,I/wpa_supplicant( 1047): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT6995","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3228): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT6995","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onIsDiscoveryStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Got discovery timeout, restarting...
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): restart: Cannot restart, because not initialized
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onConnected: [58:2A:F7:ED:96:BE HUAWEI-ALE-L21_PT4001 58:2A:F7:ED:96:BE]
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onConnectionFailed: Cancelled: Connection timeout [34:FC:EF:11:B1:66 34:FC:EF:11:B1:66 34:FC:EF:11:B1:66]
,W/io.jxcore.node.ConnectionHelper( 3228): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3228): Local services cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3228): Local service added successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
I/io.jxcore.node.ConnectionHelper( 3228): onConnected: Incoming connection, peer ID: 58:2A:F7:ED:96:BE, name: HUAWEI-ALE-L21_PT4001, Bluetooth address: 58:2A:F7:ED:96:BE
D/io.jxcore.node.ConnectionHelper( 3228): hasConnection: No connection with peer with ID 58:2A:F7:ED:96:BE
,I/io.jxcore.node.ConnectionHelper( 3228): addNewPeerToListAndNotify: Adding peer with ID 58:2A:F7:ED:96:BE
I/wpa_supplicant( 1047): P2P-FIND-STOPPED 
I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/io.jxcore.node.ConnectionHelper( 3228): onConnected: Incoming socket thread, for peer with ID 58:2A:F7:ED:96:BE, created successfully
D/io.jxcore.node.ConnectionHelper( 3228): onConnected: The total number of connections is now 1
I/jxcore-log( 3228): 2015-12-11T19:14:58.294Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3228): 
I/jxcore-log( 3228): 2015-12-11T19:14:58.294Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3228): 
I/jxcore-log( 3228): 2015-12-11T19:14:58.295Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3228): 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Peer discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Peer discovery stopped successfully
,D/io.jxcore.node.IncomingSocketThread( 3228): Entering thread (ID: 319)
,I/io.jxcore.node.IncomingSocketThread( 3228): Local host address: localhost/127.0.0.1, port: 45763
D/io.jxcore.node.IncomingSocketThread( 3228): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3228): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3228): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3228): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3228): Exiting thread (ID: 319)
,I/jxcore-log( 3228): 2015-12-11T19:14:58.303Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3228): 
,I/io.jxcore.node.StreamCopyingThread( 3228): Entering thread (ID: 321, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 3228): Entering thread (ID: 320, name: Sender)
,W/io.jxcore.node.StreamCopyingThread( 3228): Either failed to read from the output stream or write to the input stream (thread ID: 321, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 3228): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3228): onDisconnected: Incoming connection, peer with ID 58:2A:F7:ED:96:BE disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3228): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 319
I/io.jxcore.node.IncomingSocketThread( 3228): close: Stopping receiving thread...
,I/jxcore-log( 3228): 2015-12-11T19:14:58.308Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3228): 
,W/io.jxcore.node.StreamCopyingThread( 3228): Either failed to read from the output stream or write to the input stream (thread ID: 320, thread name: Sender): Broken pipe
E/io.jxcore.node.IncomingSocketThread( 3228): The sending thread failed with error: Either failed to read from the output stream or write to the input stream: Broken pipe
W/io.jxcore.node.ConnectionHelper( 3228): onDisconnected: Incoming connection, peer with ID 58:2A:F7:ED:96:BE disconnected: Either failed to read from the output stream or write to the input stream: Broken pipe
,I/io.jxcore.node.StreamCopyingThread( 3228): doStop: Thread ID: 321
I/io.jxcore.node.IncomingSocketThread( 3228): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3228): doStop: Thread ID: 320
I/io.jxcore.node.IncomingSocketThread( 3228): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.IncomingSocketThread( 3228): closeLocalSocketAndStreams: Closing the local input stream...
,I/io.jxcore.node.IncomingSocketThread( 3228): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.IncomingSocketThread( 3228): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3228): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3228): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3228): Exiting thread (ID: 321, name: Receiver)
,I/jxcore-log( 3228): 2015-12-11T19:14:58.313Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3228): 
,D/io.jxcore.node.ConnectionHelper( 3228): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3228): Exiting thread (ID: 320, name: Sender)
,W/bt-btif ( 2106): new conn_srvc id:26, app_id:255
W/bt-btif ( 2106): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2106): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): Incoming connection accepted
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): Incoming connection initialized (thread ID: 322)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3228): Entering thread (ID: 322)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): onBytesRead: Read 80 bytes successfully (thread ID: 322)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): Got valid identity from [58:2A:F7:ED:96:BE HUAWEI-ALE-L21_PT4001 58:2A:F7:ED:96:BE]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): onBytesWritten: 77 bytes successfully written (thread ID: 322)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): removeThreadFromList: Removing thread with ID 322
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): Handshake thread disposed (thread ID: 322)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3228): onIncomingConnectionConnected: [58:2A:F7:ED:96:BE HUAWEI-ALE-L21_PT4001 58:2A:F7:ED:96:BE]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3228): Exiting thread (ID: 322)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onConnected: [58:2A:F7:ED:96:BE HUAWEI-ALE-L21_PT4001 58:2A:F7:ED:96:BE]
,I/io.jxcore.node.ConnectionHelper( 3228): onConnected: Incoming connection, peer ID: 58:2A:F7:ED:96:BE, name: HUAWEI-ALE-L21_PT4001, Bluetooth address: 58:2A:F7:ED:96:BE
D/io.jxcore.node.ConnectionHelper( 3228): hasConnection: No connection with peer with ID 58:2A:F7:ED:96:BE
,I/io.jxcore.node.ConnectionHelper( 3228): addNewPeerToListAndNotify: Peer with ID 58:2A:F7:ED:96:BE already in the list
,I/io.jxcore.node.ConnectionHelper( 3228): onConnected: Incoming socket thread, for peer with ID 58:2A:F7:ED:96:BE, created successfully
D/io.jxcore.node.ConnectionHelper( 3228): onConnected: The total number of connections is now 1
,D/io.jxcore.node.IncomingSocketThread( 3228): Entering thread (ID: 323)
,I/io.jxcore.node.IncomingSocketThread( 3228): Local host address: localhost/127.0.0.1, port: 45763
D/io.jxcore.node.IncomingSocketThread( 3228): Setting local streams and starting stream copying threads...
,I/jxcore-log( 3228): 2015-12-11T19:15:00.533Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3228): 
,I/io.jxcore.node.StreamCopyingThread( 3228): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3228): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3228): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3228): Exiting thread (ID: 323)
,I/io.jxcore.node.StreamCopyingThread( 3228): Entering thread (ID: 324, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 3228): Entering thread (ID: 325, name: Receiver)
,D/btif_config_util( 2106): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3228): 2015-12-11T19:15:01.208Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:15:01.220Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:15:01.242Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:15:01.251Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:15:01.261Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:15:01.304Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:15:01.327Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:15:01.362Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:15:01.368Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:15:01.381Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:15:01.387Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:15:01.414Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:15:01.452Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:15:01.488Z SendDataTCPServer.js: TCP/IP server has received 35640 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:15:01.522Z SendDataTCPServer.js: TCP/IP server has received 39600 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:15:01.545Z SendDataTCPServer.js: TCP/IP server has received 41580 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:15:01.556Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:15:01.591Z SendDataTCPServer.js: TCP/IP server has received 45540 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:15:01.621Z SendDataTCPServer.js: TCP/IP server has received 47520 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:15:01.633Z SendDataTCPServer.js: TCP/IP server has received 49500 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:15:01.667Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:15:01.680Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:15:01.708Z SendDataTCPServer.js: TCP/IP server has received 55440 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:15:01.742Z SendDataTCPServer.js: TCP/IP server has received 57420 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:15:01.764Z SendDataTCPServer.js: TCP/IP server has received 59400 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:15:01.773Z SendDataTCPServer.js: TCP/IP server has received 63360 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:15:01.830Z SendDataTCPServer.js: TCP/IP server has received 65340 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:15:01.863Z SendDataTCPServer.js: TCP/IP server has received 67320 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:15:01.881Z SendDataTCPServer.js: TCP/IP server has received 69300 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:15:01.917Z SendDataTCPServer.js: TCP/IP server has received 71280 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:15:01.928Z SendDataTCPServer.js: TCP/IP server has received 73260 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:15:01.950Z SendDataTCPServer.js: TCP/IP server has received 75240 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:15:01.998Z SendDataTCPServer.js: TCP/IP server has received 77220 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:15:02.005Z SendDataTCPServer.js: TCP/IP server has received 79200 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:15:02.027Z SendDataTCPServer.js: TCP/IP server has received 81180 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:15:02.073Z SendDataTCPServer.js: TCP/IP server has received 83160 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:15:02.113Z SendDataTCPServer.js: TCP/IP server has received 85140 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:15:02.124Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:15:02.146Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:15:02.184Z SendDataTCPServer.js: TCP/IP server has received 97020 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:15:02.206Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3228): 
,W/bt-btif ( 2106): invalid rfc slot id: 12
,W/io.jxcore.node.StreamCopyingThread( 3228): Either failed to read from the output stream or write to the input stream (thread ID: 325, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 3228): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3228): onDisconnected: Incoming connection, peer with ID 58:2A:F7:ED:96:BE disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3228): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 323
I/io.jxcore.node.IncomingSocketThread( 3228): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3228): doStop: Thread ID: 325
I/io.jxcore.node.IncomingSocketThread( 3228): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3228): doStop: Thread ID: 324
I/io.jxcore.node.IncomingSocketThread( 3228): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.IncomingSocketThread( 3228): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3228): Either failed to read from the output stream or write to the input stream (thread ID: 324, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3228): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3228): onDisconnected: Incoming connection, peer with ID 58:2A:F7:ED:96:BE disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.IncomingSocketThread( 3228): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.IncomingSocketThread( 3228): closeLocalSocketAndStreams: Closing the localhost socket...
,I/io.jxcore.node.IncomingSocketThread( 3228): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3228): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.ConnectionHelper( 3228): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3228): Exiting thread (ID: 324, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 3228): Exiting thread (ID: 325, name: Receiver)
,I/jxcore-log( 3228): 2015-12-11T19:15:02.317Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3228): 
,E/bt-btm  ( 2106): tBTM_SEC_DEV:0xa41be7a4 rs_disc_pending=0
W/bt-btif ( 2106): bta_dm_check_av:0
,W/bt-btif ( 2106): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 2106): rfc_find_lcid_mcb LCID reused LCID:0x43 current:0x0
W/bt-rfcomm( 2106): RFCOMM_DisconnectInd LCID:0x43
,I/jxcore-log( 3228): 2015-12-11T19:15:03.295Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 3228): 
I/jxcore-log( 3228): 2015-12-11T19:15:03.296Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3228): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): start: Starting peer discovery...
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 2106): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2106): onReceive
,I/BTConnectionReceiver( 1380): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1380): Bluetooth Device Name: ALE-L21
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: 1 P2P devices discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 1: XT1039_8c05 f4:f1:e1:5c:43:c8
,D/WifiP2pManager( 3228): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service request added successfully
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/io.jxcore.node.ConnectionHelper( 3228): disconnectOutgoingConnection: Trying to close connection to peer with ID 34:FC:EF:11:B1:66
E/io.jxcore.node.ConnectionHelper( 3228): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 34:FC:EF:11:B1:66
D/io.jxcore.node.ConnectionHelper( 3228): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3228): disconnectOutgoingConnection: Failed to disconnect (peer ID: 34:FC:EF:11:B1:66), either no such connection or failed to close the connection
,I/jxcore-log( 3228): 2015-12-11T19:15:08.310Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3228): 
I/jxcore-log( 3228): 2015-12-11T19:15:08.310Z SendDataConnector.js: Connect (retry count 2) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 3228): 
I/jxcore-log( 3228): 2015-12-11T19:15:08.311Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3228): 
I/jxcore-log( 3228): 2015-12-11T19:15:08.312Z SendDataConnector.js: do connect now
I/jxcore-log( 3228): 
I/io.jxcore.node.ConnectionHelper( 3228): connect: Trying to connect to peer with ID 34:FC:EF:11:B1:66
D/io.jxcore.node.ConnectionHelper( 3228): hasConnection: No connection with peer with ID 34:FC:EF:11:B1:66
W/io.jxcore.node.ConnectionHelper( 3228): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): connect: 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3228): connect: Trying to start connecting to Nexus 5 in address 34:FC:EF:11:B1:66
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onConnecting: Nexus 5 34:FC:EF:11:B1:66
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3228): connect: Started connecting to Nexus 5 in address 34:FC:EF:11:B1:66
I/io.jxcore.node.ConnectionHelper( 3228): connect: Connection process successfully started (peer ID: 34:FC:EF:11:B1:66)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): Trying to connect to peer with address 34:FC:EF:11:B1:66 (thread ID: 326)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3228): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3228): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2106): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1047): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceListChanged: Got empty list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT5056"}", service type: "Cordovap2p._tcp.local."
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Resolved peer properties: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT5056 00:F4:6F:30:E0:6C]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Identity: "{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT8021"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Resolved peer properties: [B4:CE:F6:AB:A4:6A HTC-HTC Desire 820_PT8021 B4:CE:F6:AB:A4:6A]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceListChanged: 2 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerListChanged
I/io.jxcore.node.ConnectionHelper( 3228): onPeerDiscovered: Bluetooth address: 00:F4:6F:30:E0:6C, peer name: samsung-SM-G800F_PT5056, peer ID: 00:F4:6F:30:E0:6C, Wi-Fi Direct device name: , Wi-Fi Direct address: 02:f4:6f:30:e0:6d
I/io.jxcore.node.ConnectionHelper( 3228): addNewPeerToListAndNotify: Adding peer with ID 00:F4:6F:30:E0:6C
,W/io.jxcore.node.ConnectionHelper( 3228): onPeerListChanged: Got a list containing 2 peer(s), but doing nothing with that list
I/io.jxcore.node.ConnectionHelper( 3228): onPeerDiscovered: Bluetooth address: B4:CE:F6:AB:A4:6A, peer name: HTC-HTC Desire 820_PT8021, peer ID: B4:CE:F6:AB:A4:6A, Wi-Fi Direct device name: , Wi-Fi Direct address: b6:ce:f6:ad:a4:6b
I/io.jxcore.node.ConnectionHelper( 3228): addNewPeerToListAndNotify: Peer with ID B4:CE:F6:AB:A4:6A already in the list
,W/io.jxcore.node.ConnectionHelper( 3228): onPeerListChanged: Got a list containing 2 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3228): Connection timeout
,W/bt-sdp  ( 2106): SDP - Rcvd conn cnf with error: 0x22  CID 0x44
E/bt-btif ( 2106): DISCOVERY_COMP_EVT slot id:13, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2106): invalid rfc slot id: 13
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): Exiting thread (thread ID: 317)
,W/bt-btif ( 2106): No ag scb for peer addr
,W/bt-btif ( 2106): info:x10
,D/        ( 2106): remote version info [b0:c5:59:3f:75:69]: 7, f, 610c
E/BluetoothRemoteDevices( 2106): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2106): tBTM_SEC_DEV:0xa41be96c rs_disc_pending=0
,W/bt-btif ( 2106): bta_dm_check_av:0
,W/bt-btif ( 2106): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 2106): bondStateChangeCallback: Status: 0 Address: B0:C5:59:3F:75:69 newState: 1
E/bt-btif ( 2106): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2106): Bond State Change Intent:B0:C5:59:3F:75:69 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2106): Entering PendingCommandState State
,W/BluetoothEventManager( 2727): CachedBluetoothDevice for device B0:C5:59:3F:75:69 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2727): Got bonding state changed for B0:C5:59:3F:75:69, but we have no record of that device.
,I/BluetoothBondStateMachine( 2106): bondStateChangeCallback: Status: 0 Address: B0:C5:59:3F:75:69 newState: 0
,D/BluetoothAdapterProperties( 2106): Failed to remove device: B0:C5:59:3F:75:69
,I/BluetoothBondStateMachine( 2106): Bond State Change Intent:B0:C5:59:3F:75:69 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2106): StableState(): Entering Off State
,W/BluetoothEventManager( 2727): CachedBluetoothDevice for device B0:C5:59:3F:75:69 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2727): Got bonding state changed for B0:C5:59:3F:75:69, but we have no record of that device.
,W/bt-btif ( 2106): new conn_srvc id:26, app_id:255
W/bt-btif ( 2106): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2106): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): Incoming connection initialized (thread ID: 327)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3228): Entering thread (ID: 327)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): onBytesRead: Read 82 bytes successfully (thread ID: 327)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): Got valid identity from [B0:C5:59:3F:75:69 samsung-SM-G900F_PT5536 B0:C5:59:3F:75:69]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): onBytesWritten: 77 bytes successfully written (thread ID: 327)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): removeThreadFromList: Removing thread with ID 327
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): Handshake thread disposed (thread ID: 327)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3228): onIncomingConnectionConnected: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT5536 B0:C5:59:3F:75:69]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3228): Exiting thread (ID: 327)
,D/btif_config_util( 2106): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/ActivityManager(  757): Killing 2748:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/libprocessgroup(  757): failed to open /acct/uid_10003/pid_2748/cgroup.procs: No such file or directory
,W/bt-btif ( 2106): invalid rfc slot id: 14
,W/bt-rfcomm( 2106): rfc_find_lcid_mcb LCID reused LCID:0x47 current:0x0
W/bt-rfcomm( 2106): RFCOMM_DisconnectInd LCID:0x47
,E/bt-btm  ( 2106): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2106): onReceive
,I/BTConnectionReceiver( 1380): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1380): Bluetooth Device Name: Thali Test (Galaxy S5)
,E/bt-btif ( 2106): DISCOVERY_COMP_EVT slot id:15, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2106): invalid rfc slot id: 15
,W/BluetoothAdapter( 3228): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2106): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2106): info:x10
,D/        ( 2106): remote version info [b0:c5:59:3f:75:69]: 7, f, 610c
,I/BTConnectionReceiver( 1380): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1380): Bluetooth Device Name: Thali Test (Galaxy S5)
,W/bt-btif ( 2106): new conn_srvc id:26, app_id:255
W/bt-btif ( 2106): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2106): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): Incoming connection initialized (thread ID: 328)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3228): Entering thread (ID: 328)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): onBytesRead: Read 82 bytes successfully (thread ID: 328)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): Got valid identity from [B0:C5:59:3F:75:69 samsung-SM-G900F_PT5536 B0:C5:59:3F:75:69]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): onBytesWritten: 77 bytes successfully written (thread ID: 328)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): removeThreadFromList: Removing thread with ID 328
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): Handshake thread disposed (thread ID: 328)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3228): onIncomingConnectionConnected: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT5536 B0:C5:59:3F:75:69]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3228): Exiting thread (ID: 328)
,D/btif_config_util( 2106): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
,W/bt-btif ( 2106): invalid rfc slot id: 16
,W/bt-rfcomm( 2106): rfc_find_lcid_mcb LCID reused LCID:0x4c current:0x0
W/bt-rfcomm( 2106): RFCOMM_DisconnectInd LCID:0x4c
,E/bt-btm  ( 2106): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2106): onReceive
,I/BTConnectionReceiver( 1380): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1380): Bluetooth Device Name: Thali Test (Galaxy S5)
,W/bt-btif ( 2106): info:x10
,D/        ( 2106): remote version info [b0:c5:59:3f:75:69]: 7, f, 610c
,I/BTConnectionReceiver( 1380): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1380): Bluetooth Device Name: Thali Test (Galaxy S5)
,W/bt-btif ( 2106): new conn_srvc id:26, app_id:255
W/bt-btif ( 2106): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2106): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): Incoming connection accepted
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): Incoming connection initialized (thread ID: 329)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3228): Entering thread (ID: 329)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): onBytesRead: Read 82 bytes successfully (thread ID: 329)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): Got valid identity from [B0:C5:59:3F:75:69 samsung-SM-G900F_PT5536 B0:C5:59:3F:75:69]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): onBytesWritten: 77 bytes successfully written (thread ID: 329)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): removeThreadFromList: Removing thread with ID 329
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): Handshake thread disposed (thread ID: 329)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3228): onIncomingConnectionConnected: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT5536 B0:C5:59:3F:75:69]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3228): Exiting thread (ID: 329)
,D/btif_config_util( 2106): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-sdp  ( 2106): SDP - Rcvd conn cnf with error: 0x22  CID 0x49
E/bt-btif ( 2106): DISCOVERY_COMP_EVT slot id:17, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2106): invalid rfc slot id: 17
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3228): onConnectionFailed: Cancelled: Connection timeout
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 326)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): Trying to connect again in 300 ms... (thread ID: 326)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): stopServiceDiscovery
,I/wpa_supplicant( 1047): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT6995","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3228): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT6995","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onIsDiscoveryStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onConnected: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT5536 B0:C5:59:3F:75:69]
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onConnected: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT5536 B0:C5:59:3F:75:69]
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onConnected: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT5536 B0:C5:59:3F:75:69]
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onConnectionFailed: Cancelled: Connection timeout [34:FC:EF:11:B1:66 34:FC:EF:11:B1:66 34:FC:EF:11:B1:66]
W/io.jxcore.node.ConnectionHelper( 3228): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3228): Local services cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3228): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 3228): onConnected: Incoming connection, peer ID: B0:C5:59:3F:75:69, name: samsung-SM-G900F_PT5536, Bluetooth address: B0:C5:59:3F:75:69
D/io.jxcore.node.ConnectionHelper( 3228): hasConnection: No connection with peer with ID B0:C5:59:3F:75:69
I/io.jxcore.node.ConnectionHelper( 3228): addNewPeerToListAndNotify: Adding peer with ID B0:C5:59:3F:75:69
,I/io.jxcore.node.ConnectionHelper( 3228): onConnected: Incoming socket thread, for peer with ID B0:C5:59:3F:75:69, created successfully
D/io.jxcore.node.ConnectionHelper( 3228): onConnected: The total number of connections is now 1
I/io.jxcore.node.ConnectionHelper( 3228): onConnected: Incoming connection, peer ID: B0:C5:59:3F:75:69, name: samsung-SM-G900F_PT5536, Bluetooth address: B0:C5:59:3F:75:69
D/io.jxcore.node.ConnectionHelper( 3228): hasConnection: We have an incoming connection with peer with ID B0:C5:59:3F:75:69
,W/io.jxcore.node.ConnectionHelper( 3228): onConnected: Already connected with peer (ID: B0:C5:59:3F:75:69), continuing anyway...
I/io.jxcore.node.ConnectionHelper( 3228): addNewPeerToListAndNotify: Peer with ID B0:C5:59:3F:75:69 already in the list
,I/io.jxcore.node.ConnectionHelper( 3228): onConnected: Incoming socket thread, for peer with ID B0:C5:59:3F:75:69, created successfully
D/io.jxcore.node.ConnectionHelper( 3228): onConnected: The total number of connections is now 2
,I/io.jxcore.node.ConnectionHelper( 3228): onConnected: Incoming connection, peer ID: B0:C5:59:3F:75:69, name: samsung-SM-G900F_PT5536, Bluetooth address: B0:C5:59:3F:75:69
D/io.jxcore.node.ConnectionHelper( 3228): hasConnection: We have an incoming connection with peer with ID B0:C5:59:3F:75:69
W/io.jxcore.node.ConnectionHelper( 3228): onConnected: Already connected with peer (ID: B0:C5:59:3F:75:69), continuing anyway...
I/io.jxcore.node.ConnectionHelper( 3228): addNewPeerToListAndNotify: Peer with ID B0:C5:59:3F:75:69 already in the list
I/io.jxcore.node.ConnectionHelper( 3228): onConnected: Incoming socket thread, for peer with ID B0:C5:59:3F:75:69, created successfully
D/io.jxcore.node.ConnectionHelper( 3228): onConnected: The total number of connections is now 3
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3228): 2015-12-11T19:17:00.185Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:17:00.185Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3228): 
I/jxcore-log( 3228): 2015-12-11T19:17:00.187Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3228): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): stopServiceDiscovery
,I/wpa_supplicant( 1047): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Peer discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Peer discovery stopped successfully
,D/io.jxcore.node.IncomingSocketThread( 3228): Entering thread (ID: 332)
,D/io.jxcore.node.IncomingSocketThread( 3228): Entering thread (ID: 331)
,D/io.jxcore.node.IncomingSocketThread( 3228): Entering thread (ID: 330)
,I/jxcore-log( 3228): 2015-12-11T19:17:00.206Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3228): 
,I/io.jxcore.node.IncomingSocketThread( 3228): Local host address: localhost/127.0.0.1, port: 45763
D/io.jxcore.node.IncomingSocketThread( 3228): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3228): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3228): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.IncomingSocketThread( 3228): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3228): Exiting thread (ID: 332)
,I/io.jxcore.node.IncomingSocketThread( 3228): Local host address: localhost/127.0.0.1, port: 45763
D/io.jxcore.node.IncomingSocketThread( 3228): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3228): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3228): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3228): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3228): Exiting thread (ID: 331)
,I/jxcore-log( 3228): 2015-12-11T19:17:00.212Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:17:00.214Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3228): 
,I/io.jxcore.node.IncomingSocketThread( 3228): Local host address: localhost/127.0.0.1, port: 45763
D/io.jxcore.node.IncomingSocketThread( 3228): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3228): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3228): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3228): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3228): Exiting thread (ID: 330)
,I/io.jxcore.node.StreamCopyingThread( 3228): Entering thread (ID: 334, name: Receiver)
,I/jxcore-log( 3228): 2015-12-11T19:17:00.218Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:17:00.221Z SendDataTCPServer.js: TCP/IP server has received 81920 bytes of data
I/jxcore-log( 3228): 
,I/io.jxcore.node.StreamCopyingThread( 3228): Entering thread (ID: 336, name: Receiver)
,I/jxcore-log( 3228): 2015-12-11T19:17:00.223Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:17:00.224Z SendDataTCPServer.js: TCP/IP server has received 65536 bytes of data
I/jxcore-log( 3228): 
,I/io.jxcore.node.StreamCopyingThread( 3228): Entering thread (ID: 338, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 3228): Entering thread (ID: 333, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 3228): Entering thread (ID: 335, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 3228): Entering thread (ID: 337, name: Sender)
,I/jxcore-log( 3228): 2015-12-11T19:17:00.233Z SendDataTCPServer.js: TCP/IP server has received 98304 bytes of data
I/jxcore-log( 3228): 
I/jxcore-log( 3228): 2015-12-11T19:17:00.234Z SendDataTCPServer.js: TCP/IP server has received 98304 bytes of data
I/jxcore-log( 3228): 
,W/io.jxcore.node.StreamCopyingThread( 3228): Either failed to read from the output stream or write to the input stream (thread ID: 336, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 3228): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3228): onDisconnected: Incoming connection, peer with ID B0:C5:59:3F:75:69 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3228): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 331
I/io.jxcore.node.IncomingSocketThread( 3228): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3228): doStop: Thread ID: 336
I/io.jxcore.node.IncomingSocketThread( 3228): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3228): doStop: Thread ID: 335
I/io.jxcore.node.IncomingSocketThread( 3228): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.IncomingSocketThread( 3228): closeLocalSocketAndStreams: Closing the local input stream...
I/io.jxcore.node.IncomingSocketThread( 3228): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.IncomingSocketThread( 3228): closeLocalSocketAndStreams: Closing the localhost socket...
,I/jxcore-log( 3228): 2015-12-11T19:17:00.237Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3228): 
,W/io.jxcore.node.StreamCopyingThread( 3228): Either failed to read from the output stream or write to the input stream (thread ID: 335, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3228): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3228): onDisconnected: Incoming connection, peer with ID B0:C5:59:3F:75:69 disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.StreamCopyingThread( 3228): Either failed to read from the output stream or write to the input stream (thread ID: 338, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 3228): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3228): onDisconnected: Incoming connection, peer with ID B0:C5:59:3F:75:69 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,W/io.jxcore.node.StreamCopyingThread( 3228): Either failed to read from the output stream or write to the input stream (thread ID: 337, thread name: Sender): Broken pipe
E/io.jxcore.node.IncomingSocketThread( 3228): The sending thread failed with error: Either failed to read from the output stream or write to the input stream: Broken pipe
W/io.jxcore.node.ConnectionHelper( 3228): onDisconnected: Incoming connection, peer with ID B0:C5:59:3F:75:69 disconnected: Either failed to read from the output stream or write to the input stream: Broken pipe
,I/jxcore-log( 3228): 2015-12-11T19:17:00.241Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3228): 
I/jxcore-log( 3228): 2015-12-11T19:17:00.241Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3228): 
,I/io.jxcore.node.IncomingSocketThread( 3228): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3228): closeAndRemoveIncomingConnectionThread: 2 incoming connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3228): Exiting thread (ID: 336, name: Receiver)
,D/io.jxcore.node.ConnectionHelper( 3228): closeAndRemoveIncomingConnectionThread: 2 incoming connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3228): Exiting thread (ID: 335, name: Sender)
,I/io.jxcore.node.ConnectionHelper( 3228): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 330
I/io.jxcore.node.IncomingSocketThread( 3228): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3228): doStop: Thread ID: 338
I/io.jxcore.node.IncomingSocketThread( 3228): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3228): doStop: Thread ID: 337
I/io.jxcore.node.IncomingSocketThread( 3228): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.IncomingSocketThread( 3228): closeLocalSocketAndStreams: Closing the local input stream...
I/io.jxcore.node.IncomingSocketThread( 3228): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.IncomingSocketThread( 3228): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3228): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3228): closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3228): Exiting thread (ID: 338, name: Receiver)
D/io.jxcore.node.ConnectionHelper( 3228): closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3228): Exiting thread (ID: 337, name: Sender)
,I/jxcore-log( 3228): 2015-12-11T19:17:00.246Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3228): 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): Exiting thread (thread ID: 326)
,W/bt-btif ( 2106): invalid rfc slot id: 18
,W/io.jxcore.node.StreamCopyingThread( 3228): Either failed to read from the output stream or write to the input stream (thread ID: 334, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 3228): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3228): onDisconnected: Incoming connection, peer with ID B0:C5:59:3F:75:69 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,I/io.jxcore.node.ConnectionHelper( 3228): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 332
I/io.jxcore.node.IncomingSocketThread( 3228): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3228): doStop: Thread ID: 334
I/io.jxcore.node.IncomingSocketThread( 3228): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3228): doStop: Thread ID: 333
I/io.jxcore.node.IncomingSocketThread( 3228): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.IncomingSocketThread( 3228): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3228): Either failed to read from the output stream or write to the input stream (thread ID: 333, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3228): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3228): onDisconnected: Incoming connection, peer with ID B0:C5:59:3F:75:69 disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/jxcore-log( 3228): 2015-12-11T19:17:00.873Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3228): 
,I/io.jxcore.node.IncomingSocketThread( 3228): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.IncomingSocketThread( 3228): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3228): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3228): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.ConnectionHelper( 3228): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3228): Exiting thread (ID: 333, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 3228): Exiting thread (ID: 334, name: Receiver)
,E/bt-btm  ( 2106): tBTM_SEC_DEV:0xa41be96c rs_disc_pending=0
W/bt-btif ( 2106): bta_dm_check_av:0
,W/bt-btif ( 2106): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 2106): rfc_find_lcid_mcb LCID reused LCID:0x4b current:0x0
,W/bt-rfcomm( 2106): RFCOMM_DisconnectInd LCID:0x4b
,E/bt-btm  ( 2106): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2106): onReceive
,I/BTConnectionReceiver( 1380): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1380): Bluetooth Device Name: Thali Test (Galaxy S5)
,I/jxcore-log( 3228): 2015-12-11T19:17:05.188Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 3228): 
I/jxcore-log( 3228): 2015-12-11T19:17:05.189Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3228): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): start: Starting peer discovery...
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 1047): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,D/WifiP2pManager( 3228): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service request added successfully
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1047): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80,
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3228): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service request added successfully
D/WifiP2pManager( 3228): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service request added successfully
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3228): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service request added successfully
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1047): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 1047): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceListChanged: Got empty list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1047): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1047): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 1047): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/io.jxcore.node.ConnectionHelper( 3228): disconnectOutgoingConnection: Trying to close connection to peer with ID 34:FC:EF:11:B1:66
E/io.jxcore.node.ConnectionHelper( 3228): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 34:FC:EF:11:B1:66
D/io.jxcore.node.ConnectionHelper( 3228): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3228): disconnectOutgoingConnection: Failed to disconnect (peer ID: 34:FC:EF:11:B1:66), either no such connection or failed to close the connection
I/jxcore-log( 3228): 2015-12-11T19:17:10.195Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3228): 
I/jxcore-log( 3228): 2015-12-11T19:17:10.196Z SendDataConnector.js: Connect (retry count 3) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 3228): 
I/jxcore-log( 3228): 2015-12-11T19:17:10.196Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3228): 
I/jxcore-log( 3228): 2015-12-11T19:17:10.197Z SendDataConnector.js: do connect now
I/jxcore-log( 3228): 
I/io.jxcore.node.ConnectionHelper( 3228): connect: Trying to connect to peer with ID 34:FC:EF:11:B1:66
D/io.jxcore.node.ConnectionHelper( 3228): hasConnection: No connection with peer with ID 34:FC:EF:11:B1:66
W/io.jxcore.node.ConnectionHelper( 3228): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3228): connect: Trying to start connecting to Nexus 5 in address 34:FC:EF:11:B1:66
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onConnecting: Nexus 5 34:FC:EF:11:B1:66
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3228): connect: Started connecting to Nexus 5 in address 34:FC:EF:11:B1:66
I/io.jxcore.node.ConnectionHelper( 3228): connect: Connection process successfully started (peer ID: 34:FC:EF:11:B1:66)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): Trying to connect to peer with address 34:FC:EF:11:B1:66 (thread ID: 339)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3228): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
,W/BluetoothAdapter( 3228): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2106): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2106): No ag scb for peer addr
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3228): Connection timeout
,W/bt-btif ( 2106): info:x10
,D/        ( 2106): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
E/BluetoothRemoteDevices( 2106): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 2106): bondStateChangeCallback: Status: 0 Address: F4:F1:E1:5C:3B:E2 newState: 1
E/bt-btif ( 2106): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2106): Bond State Change Intent:F4:F1:E1:5C:3B:E2 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2106): Entering PendingCommandState State
,W/BluetoothEventManager( 2727): CachedBluetoothDevice for device F4:F1:E1:5C:3B:E2 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2727): Got bonding state changed for F4:F1:E1:5C:3B:E2, but we have no record of that device.
,I/BluetoothBondStateMachine( 2106): bondStateChangeCallback: Status: 0 Address: F4:F1:E1:5C:3B:E2 newState: 0
,D/BluetoothAdapterProperties( 2106): Failed to remove device: F4:F1:E1:5C:3B:E2
,I/BluetoothBondStateMachine( 2106): Bond State Change Intent:F4:F1:E1:5C:3B:E2 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2106): StableState(): Entering Off State
,W/BluetoothEventManager( 2727): CachedBluetoothDevice for device F4:F1:E1:5C:3B:E2 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2727): Got bonding state changed for F4:F1:E1:5C:3B:E2, but we have no record of that device.
,W/bt-btif ( 2106): new conn_srvc id:26, app_id:255
W/bt-btif ( 2106): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2106): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): Incoming connection initialized (thread ID: 340)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3228): Entering thread (ID: 340)
,E/bt-btm  ( 2106): tBTM_SEC_DEV:0xa41beb34 rs_disc_pending=0
W/bt-btif ( 2106): bta_dm_check_av:0
,W/bt-btif ( 2106): btif_dm_cback : unhandled event (14)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): onBytesRead: Read 80 bytes successfully (thread ID: 340)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): Got valid identity from [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT376 F4:F1:E1:5C:3B:E2]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): onBytesWritten: 77 bytes successfully written (thread ID: 340)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): removeThreadFromList: Removing thread with ID 340
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): Handshake thread disposed (thread ID: 340)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3228): onIncomingConnectionConnected: [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT376 F4:F1:E1:5C:3B:E2]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3228): Exiting thread (ID: 340)
,D/btif_config_util( 2106): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 2106): invalid rfc slot id: 19
,W/bt-rfcomm( 2106): rfc_find_lcid_mcb LCID reused LCID:0x42 current:0x0
,W/bt-rfcomm( 2106): RFCOMM_DisconnectInd LCID:0x42
,E/bt-btm  ( 2106): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2106): onReceive
,I/BTConnectionReceiver( 1380): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1380): Bluetooth Device Name: XT1039
,W/bt-btif ( 2106): info:x10
,D/        ( 2106): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1380): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1380): Bluetooth Device Name: XT1039
,D/btif_config_util( 2106): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
,E/bt-btif ( 2106): DISCOVERY_COMP_EVT slot id:20, failed to find channle,                                       status:1, scn:0
,W/BluetoothAdapter( 3228): getBluetoothService() called with no BluetoothManagerCallback
,W/bt-btif ( 2106): invalid rfc slot id: 20
,E/bt-btm  ( 2106): btm_sec_disconnected - Clearing Pending flag
,D/BTIF_SOCK( 2106): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-l2cap( 2106): L2CAP got conn_comp in bad state: 5  status: 0x15
,D/BluetoothMapService( 2106): onReceive
,I/BTConnectionReceiver( 1380): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1380): Bluetooth Device Name: XT1039
,W/bt-sdp  ( 2106): SDP - Rcvd conn cnf with error: 0x9  CID 0x43
E/bt-btif ( 2106): DISCOVERY_COMP_EVT slot id:22, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2106): invalid rfc slot id: 22
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 339)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): Trying to connect again in 300 ms... (thread ID: 339)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3228): onConnectionFailed: Cancelled: Connection timeout
,I/jxcore-log( 3228): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): The Coordinator has disconnected!
I/jxcore-log( 3228): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): stopServiceDiscovery
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT6995","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3228): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT6995","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/wpa_supplicant( 1047): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): start: Starting peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onIsDiscoveryStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onConnected: [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT376 F4:F1:E1:5C:3B:E2]
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onConnectionFailed: Cancelled: Connection timeout [34:FC:EF:11:B1:66 34:FC:EF:11:B1:66 34:FC:EF:11:B1:66]
W/io.jxcore.node.ConnectionHelper( 3228): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3228): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Peer discovery stopped successfully
,I/io.jxcore.node.ConnectionHelper( 3228): onConnected: Incoming connection, peer ID: F4:F1:E1:5C:3B:E2, name: motorola-XT1039_PT376, Bluetooth address: F4:F1:E1:5C:3B:E2
D/io.jxcore.node.ConnectionHelper( 3228): hasConnection: No connection with peer with ID F4:F1:E1:5C:3B:E2
I/io.jxcore.node.ConnectionHelper( 3228): addNewPeerToListAndNotify: Adding peer with ID F4:F1:E1:5C:3B:E2
I/io.jxcore.node.ConnectionHelper( 3228): onConnected: Incoming socket thread, for peer with ID F4:F1:E1:5C:3B:E2, created successfully
D/io.jxcore.node.ConnectionHelper( 3228): onConnected: The total number of connections is now 1
I/jxcore-log( 3228): 2015-12-11T19:18:56.680Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3228): 
I/jxcore-log( 3228): 2015-12-11T19:18:56.680Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3228): 
I/jxcore-log( 3228): 2015-12-11T19:18:56.681Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3228): 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3228): Local service added successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 1047): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Peer discovery stopped successfully
,D/io.jxcore.node.IncomingSocketThread( 3228): Entering thread (ID: 341)
,I/io.jxcore.node.IncomingSocketThread( 3228): Local host address: localhost/127.0.0.1, port: 45763
D/io.jxcore.node.IncomingSocketThread( 3228): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3228): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3228): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3228): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3228): Exiting thread (ID: 341)
,I/jxcore-log( 3228): 2015-12-11T19:18:56.701Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3228): 
,I/io.jxcore.node.StreamCopyingThread( 3228): Entering thread (ID: 342, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 3228): Entering thread (ID: 343, name: Receiver)
,I/jxcore-log( 3228): 2015-12-11T19:18:56.706Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3228): 
,W/io.jxcore.node.StreamCopyingThread( 3228): Either failed to read from the output stream or write to the input stream (thread ID: 343, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 3228): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3228): onDisconnected: Incoming connection, peer with ID F4:F1:E1:5C:3B:E2 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3228): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 341
I/io.jxcore.node.IncomingSocketThread( 3228): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3228): doStop: Thread ID: 343
I/io.jxcore.node.IncomingSocketThread( 3228): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3228): doStop: Thread ID: 342
I/io.jxcore.node.IncomingSocketThread( 3228): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.IncomingSocketThread( 3228): closeLocalSocketAndStreams: Closing the local input stream...
I/io.jxcore.node.IncomingSocketThread( 3228): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.IncomingSocketThread( 3228): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3228): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3228): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3228): Exiting thread (ID: 343, name: Receiver)
,W/io.jxcore.node.StreamCopyingThread( 3228): Either failed to read from the output stream or write to the input stream (thread ID: 342, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3228): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3228): onDisconnected: Incoming connection, peer with ID F4:F1:E1:5C:3B:E2 disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.ConnectionHelper( 3228): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3228): Exiting thread (ID: 342, name: Sender)
,I/jxcore-log( 3228): 2015-12-11T19:18:56.711Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3228): 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): Exiting thread (thread ID: 339)
,I/jxcore-log( 3228): DBG, CoordinatorConnector connect called
I/jxcore-log( 3228): 
I/jxcore-log( 3228): Coordinator is now connected to the server!
I/jxcore-log( 3228): 
,I/chromium( 3228): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3228): 2015-12-11T19:19:01.681Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 3228): 
I/jxcore-log( 3228): 2015-12-11T19:19:01.681Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3228): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1047): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 1: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 1: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 3228): Ignored { when=-11ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service request added successfully
D/WifiP2pManager( 3228): Ignored { when=-6ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service request added successfully
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 1047): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1047): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT7207"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Resolved peer properties: [34:FC:EF:9D:93:0B LGE-LG-D802_PT7207 34:FC:EF:9D:93:0B]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT7207"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3228): onPeerDiscovered: Bluetooth address: 34:FC:EF:9D:93:0B, peer name: LGE-LG-D802_PT7207, peer ID: 34:FC:EF:9D:93:0B, Wi-Fi Direct device name: Thali Test's G2, Wi-Fi Direct address: 36:fc:ef:de:0a:e2
I/io.jxcore.node.ConnectionHelper( 3228): addNewPeerToListAndNotify: Adding peer with ID 34:FC:EF:9D:93:0B
W/io.jxcore.node.ConnectionHelper( 3228): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT7716","ra":"E0:DB:10:1F:C9:5E"}", service type: "Cordovap2p._tcp.local."
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT7716 E0:DB:10:1F:C9:5E]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceDiscovered
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerDiscovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceListChanged: 2 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerListChanged
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT7716","ra":"E0:DB:10:1F:C9:5E"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3228): onPeerDiscovered: Bluetooth address: E0:DB:10:1F:C9:5E, peer name: samsung-SM-N9005_PT7716, peer ID: E0:DB:10:1F:C9:5E, Wi-Fi Direct device name: , Wi-Fi Direct address: ea:50:8b:de:28:a3
I/io.jxcore.node.ConnectionHelper( 3228): addNewPeerToListAndNotify: Peer with ID E0:DB:10:1F:C9:5E already in the list
W/io.jxcore.node.ConnectionHelper( 3228): onPeerListChanged: Got a list containing 2 peer(s), but doing nothing with that list
,D/io.jxcore.node.ConnectionHelper( 3228): disconnectOutgoingConnection: Trying to close connection to peer with ID 34:FC:EF:11:B1:66
E/io.jxcore.node.ConnectionHelper( 3228): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 34:FC:EF:11:B1:66
D/io.jxcore.node.ConnectionHelper( 3228): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3228): disconnectOutgoingConnection: Failed to disconnect (peer ID: 34:FC:EF:11:B1:66), either no such connection or failed to close the connection
I/jxcore-log( 3228): 2015-12-11T19:19:06.687Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3228): 
I/jxcore-log( 3228): 2015-12-11T19:19:06.688Z SendDataConnector.js: Connect (retry count 4) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:19:06.689Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3228): 
I/jxcore-log( 3228): 2015-12-11T19:19:06.695Z SendDataConnector.js: do connect now
I/jxcore-log( 3228): 
I/io.jxcore.node.ConnectionHelper( 3228): connect: Trying to connect to peer with ID 34:FC:EF:11:B1:66
D/io.jxcore.node.ConnectionHelper( 3228): hasConnection: No connection with peer with ID 34:FC:EF:11:B1:66
W/io.jxcore.node.ConnectionHelper( 3228): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3228): connect: Trying to start connecting to Nexus 5 in address 34:FC:EF:11:B1:66
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onConnecting: Nexus 5 34:FC:EF:11:B1:66
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3228): connect: Started connecting to Nexus 5 in address 34:FC:EF:11:B1:66
I/io.jxcore.node.ConnectionHelper( 3228): connect: Connection process successfully started (peer ID: 34:FC:EF:11:B1:66)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): Trying to connect to peer with address 34:FC:EF:11:B1:66 (thread ID: 344)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3228): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3228): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2106): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT5056"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Resolved peer properties: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT5056 00:F4:6F:30:E0:6C]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceListChanged: 3 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerListChanged
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT5056"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3228): onPeerDiscovered: Bluetooth address: 00:F4:6F:30:E0:6C, peer name: samsung-SM-G800F_PT5056, peer ID: 00:F4:6F:30:E0:6C, Wi-Fi Direct device name: , Wi-Fi Direct address: 02:f4:6f:30:e0:6d
I/io.jxcore.node.ConnectionHelper( 3228): addNewPeerToListAndNotify: Peer with ID 00:F4:6F:30:E0:6C already in the list
W/io.jxcore.node.ConnectionHelper( 3228): onPeerListChanged: Got a list containing 3 peer(s), but doing nothing with that list
,W/bt-btif ( 2106): info:x10
,D/        ( 2106): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1380): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1380): Bluetooth Device Name: XT1039
,W/bt-btif ( 2106): new conn_srvc id:26, app_id:255
W/bt-btif ( 2106): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2106): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): Incoming connection initialized (thread ID: 345)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3228): Entering thread (ID: 345)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): onBytesRead: Read 80 bytes successfully (thread ID: 345)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): Got valid identity from [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT376 F4:F1:E1:5C:3B:E2]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): onBytesWritten: 77 bytes successfully written (thread ID: 345)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): removeThreadFromList: Removing thread with ID 345
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): Handshake thread disposed (thread ID: 345)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3228): onIncomingConnectionConnected: [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT376 F4:F1:E1:5C:3B:E2]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3228): Exiting thread (ID: 345)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onConnected: [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT376 F4:F1:E1:5C:3B:E2]
I/io.jxcore.node.ConnectionHelper( 3228): onConnected: Incoming connection, peer ID: F4:F1:E1:5C:3B:E2, name: motorola-XT1039_PT376, Bluetooth address: F4:F1:E1:5C:3B:E2
D/io.jxcore.node.ConnectionHelper( 3228): hasConnection: No connection with peer with ID F4:F1:E1:5C:3B:E2
I/io.jxcore.node.ConnectionHelper( 3228): addNewPeerToListAndNotify: Peer with ID F4:F1:E1:5C:3B:E2 already in the list
I/io.jxcore.node.ConnectionHelper( 3228): onConnected: Incoming socket thread, for peer with ID F4:F1:E1:5C:3B:E2, created successfully
D/io.jxcore.node.ConnectionHelper( 3228): onConnected: The total number of connections is now 1
,D/io.jxcore.node.IncomingSocketThread( 3228): Entering thread (ID: 346)
,I/jxcore-log( 3228): 2015-12-11T19:19:08.040Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3228): 
,I/io.jxcore.node.IncomingSocketThread( 3228): Local host address: localhost/127.0.0.1, port: 45763
D/io.jxcore.node.IncomingSocketThread( 3228): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3228): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 3228): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3228): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3228): Exiting thread (ID: 346)
,I/io.jxcore.node.StreamCopyingThread( 3228): Entering thread (ID: 348, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 3228): Entering thread (ID: 347, name: Sender)
,I/jxcore-log( 3228): 2015-12-11T19:19:09.010Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:19:09.342Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:19:09.349Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:19:09.394Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:19:09.415Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:19:09.443Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:19:09.481Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:19:09.487Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:19:09.494Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:19:09.527Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:19:09.562Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3228): 
,W/bt-sdp  ( 2106): SDP - Rcvd conn cnf with error: 0x9  CID 0x44
E/bt-btif ( 2106): DISCOVERY_COMP_EVT slot id:23, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2106): invalid rfc slot id: 23
,W/BluetoothAdapter( 3228): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2106): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/jxcore-log( 3228): 2015-12-11T19:19:10.227Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:19:10.257Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:19:10.288Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:19:10.303Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:19:10.331Z SendDataTCPServer.js: TCP/IP server has received 36728 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:19:10.370Z SendDataTCPServer.js: TCP/IP server has received 38708 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:19:10.379Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:19:10.418Z SendDataTCPServer.js: TCP/IP server has received 42668 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:19:10.457Z SendDataTCPServer.js: TCP/IP server has received 44648 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:19:10.463Z SendDataTCPServer.js: TCP/IP server has received 46628 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:19:10.470Z SendDataTCPServer.js: TCP/IP server has received 48608 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:19:10.476Z SendDataTCPServer.js: TCP/IP server has received 50588 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:19:10.515Z SendDataTCPServer.js: TCP/IP server has received 52568 bytes of data
I/jxcore-log( 3228): 
,W/bt-sdp  ( 2106): SDP - Rcvd conn cnf with error: 0x9  CID 0x45
E/bt-btif ( 2106): DISCOVERY_COMP_EVT slot id:25, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2106): invalid rfc slot id: 25
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 344)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): Trying to connect again in 300 ms... (thread ID: 344)
,I/jxcore-log( 3228): 2015-12-11T19:19:10.564Z SendDataTCPServer.js: TCP/IP server has received 56528 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:19:10.569Z SendDataTCPServer.js: TCP/IP server has received 58508 bytes of data
I/jxcore-log( 3228): 
,D/btif_config_util( 2106): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3228): 2015-12-11T19:19:10.607Z SendDataTCPServer.js: TCP/IP server has received 60488 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:19:10.688Z SendDataTCPServer.js: TCP/IP server has received 62468 bytes of data
I/jxcore-log( 3228): 
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3228): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3228): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2106): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/jxcore-log( 3228): 2015-12-11T19:19:10.881Z SendDataTCPServer.js: TCP/IP server has received 64448 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:19:11.082Z SendDataTCPServer.js: TCP/IP server has received 66428 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:19:11.152Z SendDataTCPServer.js: TCP/IP server has received 68408 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:19:11.366Z SendDataTCPServer.js: TCP/IP server has received 70388 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:19:11.475Z SendDataTCPServer.js: TCP/IP server has received 72368 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:19:11.517Z SendDataTCPServer.js: TCP/IP server has received 76328 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:19:11.556Z SendDataTCPServer.js: TCP/IP server has received 78308 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:19:11.568Z SendDataTCPServer.js: TCP/IP server has received 80288 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:19:11.577Z SendDataTCPServer.js: TCP/IP server has received 82268 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:19:11.607Z SendDataTCPServer.js: TCP/IP server has received 84248 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:19:11.641Z SendDataTCPServer.js: TCP/IP server has received 86228 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:19:11.652Z SendDataTCPServer.js: TCP/IP server has received 88208 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:19:11.658Z SendDataTCPServer.js: TCP/IP server has received 90188 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:19:11.670Z SendDataTCPServer.js: TCP/IP server has received 92168 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:19:11.785Z SendDataTCPServer.js: TCP/IP server has received 94148 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:19:11.819Z SendDataTCPServer.js: TCP/IP server has received 96128 bytes of data
I/jxcore-log( 3228): 
,W/bt-sdp  ( 2106): SDP - Rcvd conn cnf with error: 0x9  CID 0x48
E/bt-btif ( 2106): DISCOVERY_COMP_EVT slot id:26, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2106): invalid rfc slot id: 26
,W/BluetoothAdapter( 3228): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2106): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/jxcore-log( 3228): 2015-12-11T19:19:11.917Z SendDataTCPServer.js: TCP/IP server has received 98108 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:19:11.924Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3228): 
,W/bt-sdp  ( 2106): SDP - Rcvd conn cnf with error: 0x9  CID 0x4c
E/bt-btif ( 2106): DISCOVERY_COMP_EVT slot id:27, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2106): invalid rfc slot id: 27
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): Failed to connect (tried 2 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 344)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): Trying to connect again in 300 ms... (thread ID: 344)
,E/bt-btm  ( 2106): tBTM_SEC_DEV:0xa41beb34 rs_disc_pending=0
W/bt-btif ( 2106): bta_dm_check_av:0
,W/bt-btif ( 2106): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2106): invalid rfc slot id: 21
,W/io.jxcore.node.StreamCopyingThread( 3228): Either failed to read from the output stream or write to the input stream (thread ID: 348, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 3228): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3228): onDisconnected: Incoming connection, peer with ID F4:F1:E1:5C:3B:E2 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3228): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 346
I/io.jxcore.node.IncomingSocketThread( 3228): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3228): doStop: Thread ID: 348
I/io.jxcore.node.IncomingSocketThread( 3228): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3228): doStop: Thread ID: 347
I/io.jxcore.node.IncomingSocketThread( 3228): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.IncomingSocketThread( 3228): closeLocalSocketAndStreams: Closing the local input stream...
,I/io.jxcore.node.IncomingSocketThread( 3228): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.IncomingSocketThread( 3228): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3228): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3228): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3228): Exiting thread (ID: 348, name: Receiver)
,W/io.jxcore.node.StreamCopyingThread( 3228): Either failed to read from the output stream or write to the input stream (thread ID: 347, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3228): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3228): onDisconnected: Incoming connection, peer with ID F4:F1:E1:5C:3B:E2 disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.ConnectionHelper( 3228): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3228): Exiting thread (ID: 347, name: Sender)
,I/jxcore-log( 3228): 2015-12-11T19:19:12.346Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3228): 
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3228): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3228): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2106): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-rfcomm( 2106): rfc_find_lcid_mcb LCID reused LCID:0x47 current:0x0
W/bt-rfcomm( 2106): RFCOMM_DisconnectInd LCID:0x47
,E/bt-btm  ( 2106): tBTM_SEC_DEV:0xa41beb34 rs_disc_pending=1
W/bt-btif ( 2106): bta_dm_check_av:0
,W/bt-btif ( 2106): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2106): tBTM_SEC_DEV:0xa41beb34 rs_disc_pending=0
W/bt-btif ( 2106): bta_dm_check_av:0
,W/bt-btif ( 2106): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2106): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2106): onReceive
,I/BTConnectionReceiver( 1380): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1380): Bluetooth Device Name: XT1039
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2106): SDP - Rcvd conn cnf with error: 0x9  CID 0x4d
E/bt-btif ( 2106): DISCOVERY_COMP_EVT slot id:28, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2106): invalid rfc slot id: 28
,W/BluetoothAdapter( 3228): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2106): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2106): SDP - Rcvd conn cnf with error: 0x9  CID 0x49
E/bt-btif ( 2106): DISCOVERY_COMP_EVT slot id:29, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2106): invalid rfc slot id: 29
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): Failed to connect (tried 3 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 344)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): Trying to connect again in 300 ms... (thread ID: 344)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3228): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3228): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2106): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3228): Connection timeout
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1047): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1047): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2106): SDP - Rcvd conn cnf with error: 0x22  CID 0x4b
E/bt-btif ( 2106): DISCOVERY_COMP_EVT slot id:30, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2106): invalid rfc slot id: 30
,W/BluetoothAdapter( 3228): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2106): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2106): SDP - Rcvd conn cnf with error: 0x9  CID 0x4e
E/bt-btif ( 2106): DISCOVERY_COMP_EVT slot id:31, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2106): invalid rfc slot id: 31
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3228): onConnectionFailed: Cancelled: Connection timeout
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): Failed to connect (tried 4 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 344)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): Trying to connect again in 300 ms... (thread ID: 344)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT2316","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2316 E0:DB:10:14:E2:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceListChanged: 4 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT2316","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT7692","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7692 7C:F9:0E:51:18:22]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceListChanged: 5 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT7692","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Identity: "{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT8021"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Resolved peer properties: [B4:CE:F6:AB:A4:6A HTC-HTC Desire 820_PT8021 B4:CE:F6:AB:A4:6A]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceListChanged: 6 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Identity: "{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT8021"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5167","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT5167 F8:95:C7:87:3C:51]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerDiscovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceListChanged: 7 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5167","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Identity: "{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT3473","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp.local."
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Resolved peer properties: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT3473 F8:CF:C5:D9:E5:61]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceListChanged: 8 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerListChanged
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Identity: "{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT3473","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Peer already exists in the list of peers
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onConnectionFailed: Cancelled: Connection timeout [34:FC:EF:11:B1:66 34:FC:EF:11:B1:66 34:FC:EF:11:B1:66]
,I/io.jxcore.node.ConnectionHelper( 3228): onPeerDiscovered: Bluetooth address: E0:DB:10:14:E2:C0, peer name: samsung-SM-N910C_PT2316, peer ID: E0:DB:10:14:E2:C0, Wi-Fi Direct device name: , Wi-Fi Direct address: 92:b6:86:43:73:1c
I/io.jxcore.node.ConnectionHelper( 3228): addNewPeerToListAndNotify: Adding peer with ID E0:DB:10:14:E2:C0
W/io.jxcore.node.ConnectionHelper( 3228): onPeerListChanged: Got a list containing 8 peer(s), but doing nothing with that list
I/io.jxcore.node.ConnectionHelper( 3228): onPeerDiscovered: Bluetooth address: 7C:F9:0E:51:18:22, peer name: samsung-SM-A500FU_PT7692, peer ID: 7C:F9:0E:51:18:22, Wi-Fi Direct device name: , Wi-Fi Direct address: 7e:f9:0e:51:18:23
I/io.jxcore.node.ConnectionHelper( 3228): addNewPeerToListAndNotify: Adding peer with ID 7C:F9:0E:51:18:22
W/io.jxcore.node.ConnectionHelper( 3228): onPeerListChanged: Got a list containing 8 peer(s), but doing nothing with that list
I/io.jxcore.node.ConnectionHelper( 3228): onPeerDiscovered: Bluetooth address: B4:CE:F6:AB:A4:6A, peer name: HTC-HTC Desire 820_PT8021, peer ID: B4:CE:F6:AB:A4:6A, Wi-Fi Direct device name: , Wi-Fi Direct address: b6:ce:f6:ad:a4:6b
I/io.jxcore.node.ConnectionHelper( 3228): addNewPeerToListAndNotify: Peer with ID B4:CE:F6:AB:A4:6A already in the list
W/io.jxcore.node.ConnectionHelper( 3228): onPeerListChanged: Got a list containing 8 peer(s), but doing nothing with that list
,I/io.jxcore.node.ConnectionHelper( 3228): onPeerDiscovered: Bluetooth address: F8:95:C7:87:3C:51, peer name: LGE-LG-H815_PT5167, peer ID: F8:95:C7:87:3C:51, Wi-Fi Direct device name: G4-1, Wi-Fi Direct address: a2:39:f7:6f:c9:5d
I/io.jxcore.node.ConnectionHelper( 3228): addNewPeerToListAndNotify: Adding peer with ID F8:95:C7:87:3C:51
W/io.jxcore.node.ConnectionHelper( 3228): onPeerListChanged: Got a list containing 8 peer(s), but doing nothing with that list
I/io.jxcore.node.ConnectionHelper( 3228): onPeerDiscovered: Bluetooth address: F8:CF:C5:D9:E5:61, peer name: motorola-Nexus 6_PT3473, peer ID: F8:CF:C5:D9:E5:61, Wi-Fi Direct device name: , Wi-Fi Direct address: fa:cf:c5:d9:e5:62
I/io.jxcore.node.ConnectionHelper( 3228): addNewPeerToListAndNotify: Peer with ID F8:CF:C5:D9:E5:61 already in the list
W/io.jxcore.node.ConnectionHelper( 3228): onPeerListChanged: Got a list containing 8 peer(s), but doing nothing with that list
I/jxcore-log( 3228): 2015-12-11T19:19:53.815Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3228): 
I/jxcore-log( 3228): 2015-12-11T19:19:53.815Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:19:53.818Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3228): 
,D/io.jxcore.node.ConnectionHelper( 3228): disconnectOutgoingConnection: Trying to close connection to peer with ID 34:FC:EF:11:B1:66
E/io.jxcore.node.ConnectionHelper( 3228): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 34:FC:EF:11:B1:66
D/io.jxcore.node.ConnectionHelper( 3228): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3228): disconnectOutgoingConnection: Failed to disconnect (peer ID: 34:FC:EF:11:B1:66), either no such connection or failed to close the connection
I/jxcore-log( 3228): 2015-12-11T19:19:53.820Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): ---- round done--------
I/jxcore-log( 3228): 
I/jxcore-log( 3228): ---- gotta redo : 34:FC:EF:11:B1:66, try count now: 1
I/jxcore-log( 3228): 
I/jxcore-log( 3228): do fake peer & start
I/jxcore-log( 3228): 
I/jxcore-log( 3228): Connect to fake peer: 7C:F9:0E:51:18:22
I/jxcore-log( 3228): 
I/jxcore-log( 3228): 2015-12-11T19:19:53.821Z SendDataConnector.js: Start called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3228): 
I/jxcore-log( 3228): 2015-12-11T19:19:53.821Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3228): 
I/jxcore-log( 3228): 2015-12-11T19:19:53.821Z SendDataConnector.js: do connect now
I/jxcore-log( 3228): 
I/io.jxcore.node.ConnectionHelper( 3228): connect: Trying to connect to peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 3228): hasConnection: No connection with peer with ID 7C:F9:0E:51:18:22
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3228): connect: Trying to start connecting to null in address 7C:F9:0E:51:18:22
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onConnecting: null 7C:F9:0E:51:18:22
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3228): connect: Started connecting to null in address 7C:F9:0E:51:18:22
I/io.jxcore.node.ConnectionHelper( 3228): connect: Connection process successfully started (peer ID: 7C:F9:0E:51:18:22)
,I/chromium( 3228): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 34:FC:EF:11:B1:66 done with result: Connection to peer with ID 34:FC:EF:11:B1:66 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): Trying to connect to peer with address 7C:F9:0E:51:18:22 (thread ID: 349)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3228): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3228): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2106): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): Exiting thread (thread ID: 344)
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2106): SDP - Rcvd conn cnf with error: 0x4  CID 0x41
E/bt-btif ( 2106): DISCOVERY_COMP_EVT slot id:32, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2106): invalid rfc slot id: 32
,W/BluetoothAdapter( 3228): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2106): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): stopServiceDiscovery
,I/wpa_supplicant( 1047): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:ff:f0
I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT6995","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3228): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT6995","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 3228): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3228): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3228): Local service added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service requests cleared successfully
,I/wpa_supplicant( 1047): P2P-FIND-STOPPED 
I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Peer discovery stopped successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3228): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3228): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerListChanged
,W/io.jxcore.node.ConnectionHelper( 3228): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Got empty list
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3228): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3228): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3228): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Got empty list
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3228): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3228): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3228): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3228): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): restart: Restarting...
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service requests cleared successfully
W/io.jxcore.node.ConnectionHelper( 3228): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Peer discovery stopped successfully
,W/bt-sdp  ( 2106): SDP - Rcvd conn cnf with error: 0x4  CID 0x4f
E/bt-btif ( 2106): DISCOVERY_COMP_EVT slot id:33, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2106): invalid rfc slot id: 33
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 349)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): Trying to connect again in 300 ms... (thread ID: 349)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3228): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3228): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2106): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): start: Starting peer discovery...
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3228): Connection timeout
,I/wpa_supplicant( 1047): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 1047): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 1047): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1047): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1047): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2106): info:x10
,D/        ( 2106): remote version info [7c:f9:0e:51:18:22]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2106): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2106): process_service_search_attr_rsp
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BluetoothBondStateMachine( 2106): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:51:18:22 newState: 1
E/bt-btif ( 2106): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2106): Bond State Change Intent:7C:F9:0E:51:18:22 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2106): Entering PendingCommandState State
,W/BluetoothEventManager( 2727): CachedBluetoothDevice for device 7C:F9:0E:51:18:22 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2727): Got bonding state changed for 7C:F9:0E:51:18:22, but we have no record of that device.
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BluetoothBondStateMachine( 2106): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:51:18:22 newState: 0
,D/BluetoothAdapterProperties( 2106): Failed to remove device: 7C:F9:0E:51:18:22
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BluetoothBondStateMachine( 2106): Bond State Change Intent:7C:F9:0E:51:18:22 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2106): StableState(): Entering Off State
,W/BluetoothEventManager( 2727): CachedBluetoothDevice for device 7C:F9:0E:51:18:22 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2727): Got bonding state changed for 7C:F9:0E:51:18:22, but we have no record of that device.
,D/btif_config_util( 2106): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2106): new conn_srvc id:26, app_id:1
W/bt-btif ( 2106): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2106): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): shutdown
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3228): onConnectionFailed: Cancelled: Connection timeout
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3228): onSocketConnected: Authenticating next: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7692 7C:F9:0E:51:18:22]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): Socket connection succeeded using port (1), total number of attempts: 2 (thread ID: 349)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): Exiting thread (thread ID: 349)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onConnectionFailed: Cancelled: Connection timeout [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7692 7C:F9:0E:51:18:22]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: 13 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 6: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 8: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 9: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 10: G4-1 a2:39:f7:6f:c9:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 11: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 12: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 13: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: 13 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 6: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 8: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 9: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 10: G4-1 a2:39:f7:6f:c9:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 11: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 12: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 13: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/jxcore-log( 3228): 2015-12-11T19:20:35.575Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 7C:F9:0E:51:18:22 failed
I/jxcore-log( 3228): 
I/jxcore-log( 3228): 2015-12-11T19:20:35.575Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 7C:F9:0E:51:18:22 failed
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:20:35.575Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3228): 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: 13 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 6: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 8: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 9: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 10: G4-1 a2:39:f7:6f:c9:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 11: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 12: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 13: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: 13 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 6: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 8: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 9: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 10: G4-1 a2:39:f7:6f:c9:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 11: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 12: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 13: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: 13 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 6: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 8: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 9: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 10: G4-1 a2:39:f7:6f:c9:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 11: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 12: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 13: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: 13 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 6: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 8: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 9: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 10: G4-1 a2:39:f7:6f:c9:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 11: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 12: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 13: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: 13 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 6: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 8: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 9: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 10: G4-1 a2:39:f7:6f:c9:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 11: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 12: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 13: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: 13 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 6: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 8: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 9: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 10: G4-1 a2:39:f7:6f:c9:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 11: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 12: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 13: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: 13 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 6: Android_1950 b6:ce:f6:ad:a4:6b
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 8: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 9: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 10: G4-1 a2:39:f7:6f:c9:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 11: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 12: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 13: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: 13 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 6: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 8: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 9: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 10: G4-1 a2:39:f7:6f:c9:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 11: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 12: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 13: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: 13 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 6: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 8: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 9: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 10: G4-1 a2:39:f7:6f:c9:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 11: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 12: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 13: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: 13 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 6: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 8: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 9: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 10: G4-1 a2:39:f7:6f:c9:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 11: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 12: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 13: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: 13 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 6: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 8: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 9: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 10: G4-1 a2:39:f7:6f:c9:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 11: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 12: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 13: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiP2pManager( 3228): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service request added successfully
D/WifiP2pManager( 3228): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service request added successfully
D/WifiP2pManager( 3228): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service request added successfully
D/WifiP2pManager( 3228): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service request added successfully
D/WifiP2pManager( 3228): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service request added successfully
D/WifiP2pManager( 3228): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service request added successfully
D/WifiP2pManager( 3228): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service request added successfully
D/WifiP2pManager( 3228): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service request added successfully
D/WifiP2pManager( 3228): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service request added successfully
D/WifiP2pManager( 3228): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service request added successfully
D/WifiP2pManager( 3228): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service request added successfully
D/WifiP2pManager( 3228): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service request added successfully
D/WifiP2pManager( 3228): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service request added successfully
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2106): bta_jv_rfc_port_to_cb(port_handle:0x14):jv handle:0x0 not FOUND
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1047): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1047): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1047): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1047): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1047): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1047): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1047): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1047): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1047): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1047): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1047): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1047): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1047): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3228): 2015-12-11T19:20:40.575Z SendDataConnector.js: re-try now : 7C:F9:0E:51:18:22
I/jxcore-log( 3228): 
I/jxcore-log( 3228): 2015-12-11T19:20:40.576Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3228): 
,E/bt-btm  ( 2106): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2106): onReceive
,I/BTConnectionReceiver( 1380): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:51:18:22, alias=null, name=Thali Test (Galaxy A5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1380): Bluetooth Device Name: Thali Test (Galaxy A5)
,D/io.jxcore.node.ConnectionHelper( 3228): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:51:18:22
E/io.jxcore.node.ConnectionHelper( 3228): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 3228): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3228): disconnectOutgoingConnection: Failed to disconnect (peer ID: 7C:F9:0E:51:18:22), either no such connection or failed to close the connection
I/jxcore-log( 3228): 2015-12-11T19:20:45.583Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3228): 
I/jxcore-log( 3228): 2015-12-11T19:20:45.584Z SendDataConnector.js: Connect (retry count 1) to peer 7C:F9:0E:51:18:22 with availability status: true
I/jxcore-log( 3228): 
I/jxcore-log( 3228): 2015-12-11T19:20:45.584Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3228): 
I/jxcore-log( 3228): 2015-12-11T19:20:45.585Z SendDataConnector.js: do connect now
I/jxcore-log( 3228): 
I/io.jxcore.node.ConnectionHelper( 3228): connect: Trying to connect to peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 3228): hasConnection: No connection with peer with ID 7C:F9:0E:51:18:22
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3228): connect: Trying to start connecting to Thali Test (Galaxy A5) in address 7C:F9:0E:51:18:22
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onConnecting: Thali Test (Galaxy A5) 7C:F9:0E:51:18:22
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3228): connect: Started connecting to Thali Test (Galaxy A5) in address 7C:F9:0E:51:18:22
I/io.jxcore.node.ConnectionHelper( 3228): connect: Connection process successfully started (peer ID: 7C:F9:0E:51:18:22)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): Trying to connect to peer with address 7C:F9:0E:51:18:22 (thread ID: 350)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3228): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3228): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2106): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-btif ( 2106): info:x10
,D/        ( 2106): remote version info [7c:f9:0e:51:18:22]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1380): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:51:18:22, alias=null, name=Thali Test (Galaxy A5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1380): Bluetooth Device Name: Thali Test (Galaxy A5)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3228): Connection timeout
,W/bt-sdp  ( 2106): process_service_search_attr_rsp
,D/btif_config_util( 2106): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 2106): new conn_srvc id:26, app_id:1
W/bt-btif ( 2106): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2106): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): shutdown
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3228): onConnectionFailed: Cancelled: Connection timeout
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onConnectionFailed: Cancelled: Connection timeout [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7692 7C:F9:0E:51:18:22]
I/jxcore-log( 3228): 2015-12-11T19:21:00.917Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 7C:F9:0E:51:18:22 failed
I/jxcore-log( 3228): 
I/jxcore-log( 3228): 2015-12-11T19:21:00.918Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 7C:F9:0E:51:18:22 failed
I/jxcore-log( 3228): 
I/jxcore-log( 3228): 2015-12-11T19:21:00.918Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3228): 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3228): onSocketConnected: Authenticating next: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7692 7C:F9:0E:51:18:22]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): Socket connection succeeded using port (1), total number of attempts: 1 (thread ID: 350)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): Exiting thread (thread ID: 350)
,W/bt-btif ( 2106): bta_jv_rfc_port_to_cb(port_handle:0x15):jv handle:0x0 not FOUND
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1047): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 2106): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2106): onReceive
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BTConnectionReceiver( 1380): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:51:18:22, alias=null, name=Thali Test (Galaxy A5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1380): Bluetooth Device Name: Thali Test (Galaxy A5)
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): stopServiceDiscovery
,I/wpa_supplicant( 1047): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:ff:f0
I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Peer discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): startServiceDiscovery: Invalid state, try calling restart()
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): startServiceDiscovery: Invalid state, try calling restart()
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): startServiceDiscovery: Invalid state, try calling restart()
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3228): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3228): onPeerListChanged: Got a list of peers, which is null
,I/jxcore-log( 3228): 2015-12-11T19:21:05.928Z SendDataConnector.js: re-try now : 7C:F9:0E:51:18:22
I/jxcore-log( 3228): 
I/jxcore-log( 3228): 2015-12-11T19:21:05.928Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3228): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): start: Starting peer discovery...
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,D/io.jxcore.node.ConnectionHelper( 3228): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:51:18:22
E/io.jxcore.node.ConnectionHelper( 3228): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 3228): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3228): disconnectOutgoingConnection: Failed to disconnect (peer ID: 7C:F9:0E:51:18:22), either no such connection or failed to close the connection
I/jxcore-log( 3228): 2015-12-11T19:21:10.931Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3228): 
I/jxcore-log( 3228): 2015-12-11T19:21:10.932Z SendDataConnector.js: Connect (retry count 2) to peer 7C:F9:0E:51:18:22 with availability status: true
I/jxcore-log( 3228): 
I/jxcore-log( 3228): 2015-12-11T19:21:10.933Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3228): 
I/jxcore-log( 3228): 2015-12-11T19:21:10.933Z SendDataConnector.js: do connect now
I/jxcore-log( 3228): 
I/io.jxcore.node.ConnectionHelper( 3228): connect: Trying to connect to peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 3228): hasConnection: No connection with peer with ID 7C:F9:0E:51:18:22
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3228): connect: Trying to start connecting to Thali Test (Galaxy A5) in address 7C:F9:0E:51:18:22
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onConnecting: Thali Test (Galaxy A5) 7C:F9:0E:51:18:22
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3228): connect: Started connecting to Thali Test (Galaxy A5) in address 7C:F9:0E:51:18:22
I/io.jxcore.node.ConnectionHelper( 3228): connect: Connection process successfully started (peer ID: 7C:F9:0E:51:18:22)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): Trying to connect to peer with address 7C:F9:0E:51:18:22 (thread ID: 351)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3228): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3228): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2106): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1047): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 1: Android_50a5 fa:cf:c5:d9:e5:62
,D/WifiP2pManager( 3228): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service request added successfully
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2106): info:x10
,D/        ( 2106): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2106): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 1047): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceListChanged: Got empty list
,I/BluetoothBondStateMachine( 2106): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:76:27 newState: 1
E/bt-btif ( 2106): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2106): Bond State Change Intent:08:EC:A9:50:76:27 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2106): Entering PendingCommandState State
,W/BluetoothEventManager( 2727): CachedBluetoothDevice for device 08:EC:A9:50:76:27 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2727): Got bonding state changed for 08:EC:A9:50:76:27, but we have no record of that device.
,I/BluetoothBondStateMachine( 2106): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:76:27 newState: 0
,D/BluetoothAdapterProperties( 2106): Failed to remove device: 08:EC:A9:50:76:27
,I/BluetoothBondStateMachine( 2106): Bond State Change Intent:08:EC:A9:50:76:27 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2106): StableState(): Entering Off State
,W/BluetoothEventManager( 2727): CachedBluetoothDevice for device 08:EC:A9:50:76:27 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2727): Got bonding state changed for 08:EC:A9:50:76:27, but we have no record of that device.
,W/bt-btif ( 2106): new conn_srvc id:26, app_id:255
W/bt-btif ( 2106): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2106): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): Incoming connection accepted
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): Incoming connection initialized (thread ID: 352)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3228): Entering thread (ID: 352)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): onBytesRead: Read 83 bytes successfully (thread ID: 352)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): Got valid identity from [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6611 08:EC:A9:50:76:27]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): onBytesWritten: 77 bytes successfully written (thread ID: 352)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): removeThreadFromList: Removing thread with ID 352
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): Handshake thread disposed (thread ID: 352)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3228): onIncomingConnectionConnected: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6611 08:EC:A9:50:76:27]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3228): Exiting thread (ID: 352)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onConnected: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6611 08:EC:A9:50:76:27]
I/io.jxcore.node.ConnectionHelper( 3228): onConnected: Incoming connection, peer ID: 08:EC:A9:50:76:27, name: samsung-SM-A300FU_PT6611, Bluetooth address: 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 3228): hasConnection: No connection with peer with ID 08:EC:A9:50:76:27
I/io.jxcore.node.ConnectionHelper( 3228): addNewPeerToListAndNotify: Adding peer with ID 08:EC:A9:50:76:27
,I/io.jxcore.node.ConnectionHelper( 3228): onConnected: Incoming socket thread, for peer with ID 08:EC:A9:50:76:27, created successfully
D/io.jxcore.node.ConnectionHelper( 3228): onConnected: The total number of connections is now 1
,D/io.jxcore.node.IncomingSocketThread( 3228): Entering thread (ID: 353)
,I/io.jxcore.node.IncomingSocketThread( 3228): Local host address: localhost/127.0.0.1, port: 45763
D/io.jxcore.node.IncomingSocketThread( 3228): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3228): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3228): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3228): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3228): Exiting thread (ID: 353)
,I/jxcore-log( 3228): 2015-12-11T19:21:15.646Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3228): 
,I/io.jxcore.node.StreamCopyingThread( 3228): Entering thread (ID: 354, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 3228): Entering thread (ID: 355, name: Receiver)
,W/bt-sdp  ( 2106): SDP - Rcvd conn cnf with error: 0x4  CID 0x46
E/bt-btif ( 2106): DISCOVERY_COMP_EVT slot id:36, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2106): invalid rfc slot id: 36
W/BluetoothAdapter( 3228): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2106): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/jxcore-log( 3228): 2015-12-11T19:21:17.493Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:21:17.502Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:21:17.516Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:21:17.525Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:21:17.530Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:21:17.543Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:21:17.575Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:21:17.617Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:21:17.627Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:21:17.637Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:21:17.981Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 3228): 
,D/btif_config_util( 2106): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-sdp  ( 2106): SDP - Rcvd conn cnf with error: 0x4  CID 0x48
E/bt-btif ( 2106): DISCOVERY_COMP_EVT slot id:38, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2106): invalid rfc slot id: 38
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 351)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): Trying to connect again in 300 ms... (thread ID: 351)
,I/jxcore-log( 3228): 2015-12-11T19:21:21.499Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 3228): 
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3228): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3228): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2106): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/jxcore-log( 3228): 2015-12-11T19:21:21.561Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:21:21.568Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:21:21.580Z SendDataTCPServer.js: TCP/IP server has received 35640 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:21:21.612Z SendDataTCPServer.js: TCP/IP server has received 41580 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:21:21.691Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:21:22.202Z SendDataTCPServer.js: TCP/IP server has received 45540 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:21:22.337Z SendDataTCPServer.js: TCP/IP server has received 47520 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:21:22.540Z SendDataTCPServer.js: TCP/IP server has received 49500 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:21:22.613Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:21:22.747Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:21:22.883Z SendDataTCPServer.js: TCP/IP server has received 55440 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:21:23.017Z SendDataTCPServer.js: TCP/IP server has received 57420 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:21:23.152Z SendDataTCPServer.js: TCP/IP server has received 59400 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:21:23.286Z SendDataTCPServer.js: TCP/IP server has received 61380 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:21:23.488Z SendDataTCPServer.js: TCP/IP server has received 63360 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:21:23.566Z SendDataTCPServer.js: TCP/IP server has received 65340 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:21:23.633Z SendDataTCPServer.js: TCP/IP server has received 67320 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:21:23.840Z SendDataTCPServer.js: TCP/IP server has received 69300 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:21:23.906Z SendDataTCPServer.js: TCP/IP server has received 71280 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:21:24.044Z SendDataTCPServer.js: TCP/IP server has received 73260 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:21:24.178Z SendDataTCPServer.js: TCP/IP server has received 75240 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:21:24.317Z SendDataTCPServer.js: TCP/IP server has received 77220 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:21:24.448Z SendDataTCPServer.js: TCP/IP server has received 79200 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:21:24.592Z SendDataTCPServer.js: TCP/IP server has received 81180 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:21:24.721Z SendDataTCPServer.js: TCP/IP server has received 83160 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:21:24.856Z SendDataTCPServer.js: TCP/IP server has received 85140 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:21:24.991Z SendDataTCPServer.js: TCP/IP server has received 87120 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:21:25.125Z SendDataTCPServer.js: TCP/IP server has received 89100 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:21:25.331Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:21:25.462Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:21:25.561Z SendDataTCPServer.js: TCP/IP server has received 95040 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:21:25.572Z SendDataTCPServer.js: TCP/IP server has received 97020 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:21:25.578Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3228): 
,W/bt-btif ( 2106): invalid rfc slot id: 24
,W/io.jxcore.node.StreamCopyingThread( 3228): Either failed to read from the output stream or write to the input stream (thread ID: 355, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.IncomingSocketThread( 3228): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3228): onDisconnected: Incoming connection, peer with ID 08:EC:A9:50:76:27 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3228): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 353
I/io.jxcore.node.IncomingSocketThread( 3228): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3228): doStop: Thread ID: 355
I/io.jxcore.node.IncomingSocketThread( 3228): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3228): doStop: Thread ID: 354
I/io.jxcore.node.IncomingSocketThread( 3228): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.IncomingSocketThread( 3228): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3228): Either failed to read from the output stream or write to the input stream (thread ID: 354, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3228): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3228): onDisconnected: Incoming connection, peer with ID 08:EC:A9:50:76:27 disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.IncomingSocketThread( 3228): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.IncomingSocketThread( 3228): closeLocalSocketAndStreams: Closing the localhost socket...
,I/io.jxcore.node.IncomingSocketThread( 3228): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3228): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.ConnectionHelper( 3228): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3228): Exiting thread (ID: 354, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 3228): Exiting thread (ID: 355, name: Receiver)
,I/jxcore-log( 3228): 2015-12-11T19:21:25.666Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3228): 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3228): Connection timeout
,E/bt-btm  ( 2106): tBTM_SEC_DEV:0xa41beec4 rs_disc_pending=0
W/bt-btif ( 2106): bta_dm_check_av:0
,W/bt-btif ( 2106): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 2106): rfc_find_lcid_mcb LCID reused LCID:0x45 current:0x0
W/bt-rfcomm( 2106): RFCOMM_DisconnectInd LCID:0x45
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2106): SDP - Rcvd conn cnf with error: 0x4  CID 0x4c
E/bt-btif ( 2106): DISCOVERY_COMP_EVT slot id:39, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2106): invalid rfc slot id: 39
,W/BluetoothAdapter( 3228): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2106): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,E/bt-btm  ( 2106): tBTM_SEC_DEV:0xa41beec4 rs_disc_pending=1
W/bt-btif ( 2106): bta_dm_check_av:0
,W/bt-btif ( 2106): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2106): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2106): onReceive
,I/BTConnectionReceiver( 1380): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1380): Bluetooth Device Name: Thali Test (Galaxy A3)
,W/bt-sdp  ( 2106): SDP - Rcvd conn cnf with error: 0x4  CID 0x47
E/bt-btif ( 2106): DISCOVERY_COMP_EVT slot id:40, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2106): invalid rfc slot id: 40
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3228): onConnectionFailed: Cancelled: Connection timeout
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): Failed to connect (tried 2 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 351)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): Trying to connect again in 300 ms... (thread ID: 351)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Identity: "{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT3473","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Resolved peer properties: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT3473 F8:CF:C5:D9:E5:61]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onConnectionFailed: Cancelled: Connection timeout [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7692 7C:F9:0E:51:18:22]
,I/io.jxcore.node.ConnectionHelper( 3228): onPeerDiscovered: Bluetooth address: F8:CF:C5:D9:E5:61, peer name: motorola-Nexus 6_PT3473, peer ID: F8:CF:C5:D9:E5:61, Wi-Fi Direct device name: Android_50a5, Wi-Fi Direct address: fa:cf:c5:d9:e5:62
I/io.jxcore.node.ConnectionHelper( 3228): addNewPeerToListAndNotify: Peer with ID F8:CF:C5:D9:E5:61 already in the list
W/io.jxcore.node.ConnectionHelper( 3228): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/jxcore-log( 3228): 2015-12-11T19:21:33.493Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 7C:F9:0E:51:18:22 failed
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:21:33.496Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 7C:F9:0E:51:18:22 failed
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:21:33.503Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3228): 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): Exiting thread (thread ID: 351)
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3228): 2015-12-11T19:21:38.502Z SendDataConnector.js: re-try now : 7C:F9:0E:51:18:22
I/jxcore-log( 3228): 
I/jxcore-log( 3228): 2015-12-11T19:21:38.503Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3228): 
,D/io.jxcore.node.ConnectionHelper( 3228): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:51:18:22
E/io.jxcore.node.ConnectionHelper( 3228): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 3228): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3228): disconnectOutgoingConnection: Failed to disconnect (peer ID: 7C:F9:0E:51:18:22), either no such connection or failed to close the connection
I/jxcore-log( 3228): 2015-12-11T19:21:43.508Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:21:43.514Z SendDataConnector.js: Connect (retry count 3) to peer 7C:F9:0E:51:18:22 with availability status: true
I/jxcore-log( 3228): 
I/jxcore-log( 3228): 2015-12-11T19:21:43.515Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:21:43.518Z SendDataConnector.js: do connect now
I/jxcore-log( 3228): 
,I/io.jxcore.node.ConnectionHelper( 3228): connect: Trying to connect to peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 3228): hasConnection: No connection with peer with ID 7C:F9:0E:51:18:22
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3228): connect: Trying to start connecting to Thali Test (Galaxy A5) in address 7C:F9:0E:51:18:22
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onConnecting: Thali Test (Galaxy A5) 7C:F9:0E:51:18:22
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3228): connect: Started connecting to Thali Test (Galaxy A5) in address 7C:F9:0E:51:18:22
I/io.jxcore.node.ConnectionHelper( 3228): connect: Connection process successfully started (peer ID: 7C:F9:0E:51:18:22)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): Trying to connect to peer with address 7C:F9:0E:51:18:22 (thread ID: 356)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3228): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3228): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2106): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2106): SDP - Rcvd conn cnf with error: 0x4  CID 0x4d
E/bt-btif ( 2106): DISCOVERY_COMP_EVT slot id:41, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2106): invalid rfc slot id: 41
,W/BluetoothAdapter( 3228): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2106): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5167","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT5167 F8:95:C7:87:3C:51]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceListChanged: 2 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerListChanged
I/io.jxcore.node.ConnectionHelper( 3228): onPeerDiscovered: Bluetooth address: F8:95:C7:87:3C:51, peer name: LGE-LG-H815_PT5167, peer ID: F8:95:C7:87:3C:51, Wi-Fi Direct device name: G4-1, Wi-Fi Direct address: a2:39:f7:6f:c9:5d
I/io.jxcore.node.ConnectionHelper( 3228): addNewPeerToListAndNotify: Peer with ID F8:95:C7:87:3C:51 already in the list
W/io.jxcore.node.ConnectionHelper( 3228): onPeerListChanged: Got a list containing 2 peer(s), but doing nothing with that list
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3228): Connection timeout
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/ActivityManager(  757): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=3718 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,I/GAv4    ( 3718): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3718):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3718):   adb logcat -s GAv4
,W/GAv4    ( 3718): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/EventLogService( 1597): Aggregate from 1449859620087 (log), 1449859620087 (data)
,W/GAv4    ( 3718): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3718): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  757): Killing 2581:com.google.android.gm/u0a70 (adj 15): empty #17
,W/libprocessgroup(  757): failed to open /acct/uid_10070/pid_2581/cgroup.procs: No such file or directory
,W/bt-sdp  ( 2106): SDP - Rcvd conn cnf with error: 0xd  CID 0x49
E/bt-btif ( 2106): DISCOVERY_COMP_EVT slot id:42, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2106): invalid rfc slot id: 42
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3228): onConnectionFailed: Cancelled: Connection timeout
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): Exiting thread (thread ID: 356)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT2316","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2316 E0:DB:10:14:E2:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceListChanged: 3 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onConnectionFailed: Cancelled: Connection timeout [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7692 7C:F9:0E:51:18:22]
,I/io.jxcore.node.ConnectionHelper( 3228): onPeerDiscovered: Bluetooth address: E0:DB:10:14:E2:C0, peer name: samsung-SM-N910C_PT2316, peer ID: E0:DB:10:14:E2:C0, Wi-Fi Direct device name: Note4-1, Wi-Fi Direct address: 92:b6:86:43:73:1c
I/io.jxcore.node.ConnectionHelper( 3228): addNewPeerToListAndNotify: Peer with ID E0:DB:10:14:E2:C0 already in the list
,W/io.jxcore.node.ConnectionHelper( 3228): onPeerListChanged: Got a list containing 3 peer(s), but doing nothing with that list
,I/jxcore-log( 3228): 2015-12-11T19:22:09.878Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 7C:F9:0E:51:18:22 failed
I/jxcore-log( 3228): 
I/jxcore-log( 3228): 2015-12-11T19:22:09.879Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 7C:F9:0E:51:18:22 failed
I/jxcore-log( 3228): 
I/jxcore-log( 3228): 2015-12-11T19:22:09.880Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3228): 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): stopServiceDiscovery
,I/wpa_supplicant( 1047): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT6995","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3228): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT6995","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 3228): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3228): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3228): Local service added successfully
,I/wpa_supplicant( 1047): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 1047): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Peer discovery stopped successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3228): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3228): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3228): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3228): onPeerListChanged: Got a list of peers, which is null
,I/wpa_supplicant( 1047): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3228): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): startServiceDiscovery: Invalid state, try calling restart()
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service requests cleared successfully
,I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Peer discovery stopped successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3228): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3228): onPeerListChanged: Got a list of peers, which is null
,I/jxcore-log( 3228): 2015-12-11T19:22:14.881Z SendDataConnector.js: re-try now : 7C:F9:0E:51:18:22
I/jxcore-log( 3228): 
I/jxcore-log( 3228): 2015-12-11T19:22:14.882Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3228): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): start: Starting peer discovery...
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 1047): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1047): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 1: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 1: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3228): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service request added successfully
D/WifiP2pManager( 3228): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service request added successfully
,D/io.jxcore.node.ConnectionHelper( 3228): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:51:18:22
E/io.jxcore.node.ConnectionHelper( 3228): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 3228): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3228): disconnectOutgoingConnection: Failed to disconnect (peer ID: 7C:F9:0E:51:18:22), either no such connection or failed to close the connection
I/jxcore-log( 3228): 2015-12-11T19:22:19.887Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3228): 
I/jxcore-log( 3228): 2015-12-11T19:22:19.888Z SendDataConnector.js: Connect (retry count 4) to peer 7C:F9:0E:51:18:22 with availability status: true
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:22:19.898Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3228): 
I/jxcore-log( 3228): 2015-12-11T19:22:19.899Z SendDataConnector.js: do connect now
I/jxcore-log( 3228): 
I/io.jxcore.node.ConnectionHelper( 3228): connect: Trying to connect to peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 3228): hasConnection: No connection with peer with ID 7C:F9:0E:51:18:22
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): connect: 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3228): connect: Trying to start connecting to Thali Test (Galaxy A5) in address 7C:F9:0E:51:18:22
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onConnecting: Thali Test (Galaxy A5) 7C:F9:0E:51:18:22
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3228): connect: Started connecting to Thali Test (Galaxy A5) in address 7C:F9:0E:51:18:22
I/io.jxcore.node.ConnectionHelper( 3228): connect: Connection process successfully started (peer ID: 7C:F9:0E:51:18:22)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): Trying to connect to peer with address 7C:F9:0E:51:18:22 (thread ID: 357)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3228): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3228): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2106): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1047): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 1: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3228): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service request added successfully
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1047): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceListChanged: Got empty list
,W/bt-btif ( 2106): info:x10
,D/        ( 2106): remote version info [f8:cf:c5:d9:e5:61]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1380): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1380): Bluetooth Device Name: Nexus 6
,E/bt-btm  ( 2106): tBTM_SEC_DEV:0xa41be24c rs_disc_pending=0
W/bt-btif ( 2106): bta_dm_check_av:0
,W/bt-btif ( 2106): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2106): info:x10
,D/        ( 2106): remote version info [7c:f9:0e:51:18:22]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1380): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:51:18:22, alias=null, name=Thali Test (Galaxy A5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1380): Bluetooth Device Name: Thali Test (Galaxy A5)
,E/bt-btm  ( 2106): tBTM_SEC_DEV:0xa41be24c rs_disc_pending=1
W/bt-btif ( 2106): bta_dm_check_av:0
,W/bt-btif ( 2106): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2106): new conn_srvc id:26, app_id:255
W/bt-btif ( 2106): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2106): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): Incoming connection initialized (thread ID: 358)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3228): Entering thread (ID: 358)
,E/bt-btm  ( 2106): tBTM_SEC_DEV:0xa41becfc rs_disc_pending=1
W/bt-btif ( 2106): bta_dm_check_av:0
,W/bt-btif ( 2106): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2106): tBTM_SEC_DEV:0xa41be24c rs_disc_pending=0
W/bt-btif ( 2106): bta_dm_check_av:0
,W/bt-btif ( 2106): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 2106): process_service_search_attr_rsp
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): onBytesRead: Read 82 bytes successfully (thread ID: 358)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): Got valid identity from [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT3473 F8:CF:C5:D9:E5:61]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): onBytesWritten: 77 bytes successfully written (thread ID: 358)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): removeThreadFromList: Removing thread with ID 358
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): Handshake thread disposed (thread ID: 358)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3228): onIncomingConnectionConnected: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT3473 F8:CF:C5:D9:E5:61]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3228): Exiting thread (ID: 358)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onConnected: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT3473 F8:CF:C5:D9:E5:61]
,I/io.jxcore.node.ConnectionHelper( 3228): onConnected: Incoming connection, peer ID: F8:CF:C5:D9:E5:61, name: motorola-Nexus 6_PT3473, Bluetooth address: F8:CF:C5:D9:E5:61
D/io.jxcore.node.ConnectionHelper( 3228): hasConnection: No connection with peer with ID F8:CF:C5:D9:E5:61
I/io.jxcore.node.ConnectionHelper( 3228): addNewPeerToListAndNotify: Peer with ID F8:CF:C5:D9:E5:61 already in the list
,I/io.jxcore.node.ConnectionHelper( 3228): onConnected: Incoming socket thread, for peer with ID F8:CF:C5:D9:E5:61, created successfully
D/io.jxcore.node.ConnectionHelper( 3228): onConnected: The total number of connections is now 1
,D/io.jxcore.node.IncomingSocketThread( 3228): Entering thread (ID: 359)
,I/jxcore-log( 3228): 2015-12-11T19:22:26.624Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3228): 
,I/io.jxcore.node.IncomingSocketThread( 3228): Local host address: localhost/127.0.0.1, port: 45763
D/io.jxcore.node.IncomingSocketThread( 3228): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3228): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3228): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.IncomingSocketThread( 3228): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3228): Exiting thread (ID: 359)
,I/io.jxcore.node.StreamCopyingThread( 3228): Entering thread (ID: 361, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 3228): Entering thread (ID: 360, name: Sender)
,W/bt-btif ( 2106): new conn_srvc id:26, app_id:1
W/bt-btif ( 2106): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2106): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3228): onSocketConnected: Authenticating next: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7692 7C:F9:0E:51:18:22]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): Socket connection succeeded using port (1), total number of attempts: 1 (thread ID: 357)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): onBytesWritten: 77 bytes successfully written (thread ID: 362)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): Outgoing connection initialized (*handshake* thread ID: 362)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): Exiting thread (thread ID: 357)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3228): Entering thread (ID: 362)
,E/bt-btm  ( 2106): tBTM_SEC_DEV:0xa41be24c rs_disc_pending=1
W/bt-btif ( 2106): bta_dm_check_av:0
,W/bt-btif ( 2106): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2106): tBTM_SEC_DEV:0xa41becfc rs_disc_pending=1
W/bt-btif ( 2106): bta_dm_check_av:0
,W/bt-btif ( 2106): btif_dm_cback : unhandled event (14)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): onBytesRead: Read 83 bytes successfully (thread ID: 362)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): Handshake succeeded with [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7692 7C:F9:0E:51:18:22]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3228): onAuthenticated: Fully connected: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7692 7C:F9:0E:51:18:22]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3228): Exiting thread (ID: 362)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onConnected: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7692 7C:F9:0E:51:18:22]
I/io.jxcore.node.ConnectionHelper( 3228): onConnected: Outgoing connection, peer ID: 7C:F9:0E:51:18:22, name: samsung-SM-A500FU_PT7692, Bluetooth address: 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 3228): hasConnection: No connection with peer with ID 7C:F9:0E:51:18:22
I/io.jxcore.node.ConnectionHelper( 3228): addNewPeerToListAndNotify: Peer with ID 7C:F9:0E:51:18:22 already in the list
I/io.jxcore.node.ConnectionHelper( 3228): onConnected: Outgoing socket thread, for peer with ID 7C:F9:0E:51:18:22, created successfully
D/io.jxcore.node.ConnectionHelper( 3228): onConnected: The total number of connections is now 2
,D/io.jxcore.node.OutgoingSocketThread( 3228): Entering thread (ID: 363)
,D/io.jxcore.node.OutgoingSocketThread( 3228): Server socket local port: 38363
I/io.jxcore.node.OutgoingSocketThread( 3228): Now accepting connections...
,I/jxcore-log( 3228): 2015-12-11T19:22:27.428Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:22:27.440Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:22:27.509Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3228): 
,I/io.jxcore.node.ConnectionHelper( 3228): onListeningForIncomingConnections: Outgoing connection is using port 38363 (peer ID: 7C:F9:0E:51:18:22)
I/jxcore-log( 3228): 2015-12-11T19:22:27.624Z SendDataConnector.js: CLIENT connected to 38363, error: null
I/jxcore-log( 3228): 
I/jxcore-log( 3228): 2015-12-11T19:22:27.625Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3228): 
,I/io.jxcore.node.OutgoingSocketThread( 3228): Incoming data from address: /127.0.0.1, port: 38363
,D/io.jxcore.node.OutgoingSocketThread( 3228): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3228): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 3228): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3228): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3228): Exiting thread (ID: 363)
,I/io.jxcore.node.StreamCopyingThread( 3228): Entering thread (ID: 365, name: Receiver)
,I/jxcore-log( 3228): 2015-12-11T19:22:27.658Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:22:27.676Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3228): 
,I/io.jxcore.node.StreamCopyingThread( 3228): Entering thread (ID: 364, name: Sender)
,I/jxcore-log( 3228): 2015-12-11T19:22:28.055Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:22:28.101Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:22:28.113Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:22:28.150Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:22:28.161Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:22:28.201Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:22:28.205Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:22:28.209Z SendDataTCPServer.js: TCP/IP server has received 32768 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:22:28.242Z SendDataTCPServer.js: TCP/IP server has received 36728 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:22:28.263Z SendDataTCPServer.js: TCP/IP server has received 38708 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:22:28.357Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:22:28.453Z SendDataTCPServer.js: TCP/IP server has received 42668 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:22:28.491Z SendDataTCPServer.js: TCP/IP server has received 46628 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:22:28.544Z SendDataTCPServer.js: TCP/IP server has received 48608 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:22:28.662Z SendDataTCPServer.js: TCP/IP server has received 50588 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:22:28.787Z SendDataTCPServer.js: TCP/IP server has received 52568 bytes of data
I/jxcore-log( 3228): 
,D/        ( 2106): PORT_WriteDataCO: tx queue is full,tx.queue_size:10172,tx.queue.count:11,available:24706
,I/jxcore-log( 3228): 2015-12-11T19:22:28.820Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:22:28.825Z SendDataTCPServer.js: TCP/IP server has received 58508 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:22:28.835Z SendDataTCPServer.js: TCP/IP server has received 62468 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:22:28.847Z SendDataTCPServer.js: TCP/IP server has received 68408 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:22:28.861Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:22:28.882Z SendDataTCPServer.js: TCP/IP server has received 70388 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:22:28.901Z SendDataTCPServer.js: TCP/IP server has received 72368 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:22:28.965Z SendDataTCPServer.js: TCP/IP server has received 74348 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:22:29.053Z SendDataTCPServer.js: TCP/IP server has received 76328 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:22:29.060Z SendDataTCPServer.js: TCP/IP server has received 78308 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:22:29.067Z SendDataTCPServer.js: TCP/IP server has received 80288 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:22:29.096Z SendDataTCPServer.js: TCP/IP server has received 82268 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:22:29.131Z SendDataTCPServer.js: TCP/IP server has received 84248 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:22:29.193Z SendDataTCPServer.js: TCP/IP server has received 86228 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:22:29.305Z SendDataTCPServer.js: TCP/IP server has received 88208 bytes of data
I/jxcore-log( 3228): 
,D/        ( 2106): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:14806
,I/jxcore-log( 3228): 2015-12-11T19:22:29.335Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:22:29.354Z SendDataTCPServer.js: TCP/IP server has received 92168 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:22:29.393Z SendDataTCPServer.js: TCP/IP server has received 94148 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:22:29.432Z SendDataTCPServer.js: TCP/IP server has received 98108 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:22:29.570Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:22:29.582Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3228): 
,D/        ( 2106): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:3916
,I/jxcore-log( 3228): 2015-12-11T19:22:29.705Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:22:30.029Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3228): 
,E/bt-btm  ( 2106): tBTM_SEC_DEV:0xa41be24c rs_disc_pending=0
W/bt-btif ( 2106): bta_dm_check_av:0
,W/bt-btif ( 2106): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3228): 2015-12-11T19:22:30.156Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3228): 
,W/bt-btif ( 2106): invalid rfc slot id: 37
,W/io.jxcore.node.StreamCopyingThread( 3228): Either failed to read from the output stream or write to the input stream (thread ID: 361, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.OutgoingSocketThread( 3228): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
,W/io.jxcore.node.ConnectionHelper( 3228): onDisconnected: Incoming connection, peer with ID F8:CF:C5:D9:E5:61 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,I/io.jxcore.node.ConnectionHelper( 3228): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 359
I/io.jxcore.node.OutgoingSocketThread( 3228): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3228): doStop: Thread ID: 361
I/io.jxcore.node.OutgoingSocketThread( 3228): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3228): doStop: Thread ID: 360
I/io.jxcore.node.OutgoingSocketThread( 3228): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.OutgoingSocketThread( 3228): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3228): Either failed to read from the output stream or write to the input stream (thread ID: 360, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3228): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3228): onDisconnected: Incoming connection, peer with ID F8:CF:C5:D9:E5:61 disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.OutgoingSocketThread( 3228): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.OutgoingSocketThread( 3228): closeLocalSocketAndStreams: Closing the localhost socket...
,I/io.jxcore.node.OutgoingSocketThread( 3228): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3228): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.ConnectionHelper( 3228): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3228): Exiting thread (ID: 360, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 3228): Exiting thread (ID: 361, name: Receiver)
,I/jxcore-log( 3228): 2015-12-11T19:22:30.245Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:22:30.367Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3228): 
,D/btif_config_util( 2106): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3228): 2015-12-11T19:22:30.466Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:22:30.622Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:22:30.627Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:22:30.642Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3228): 
I/jxcore-log( 3228): 2015-12-11T19:22:30.643Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3228): 
D/io.jxcore.node.ConnectionHelper( 3228): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:51:18:22
I/io.jxcore.node.ConnectionHelper( 3228): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 7C:F9:0E:51:18:22
I/io.jxcore.node.OutgoingSocketThread( 3228): close
I/io.jxcore.node.OutgoingSocketThread( 3228): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3228): doStop: Thread ID: 365
I/io.jxcore.node.OutgoingSocketThread( 3228): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3228): doStop: Thread ID: 364
I/io.jxcore.node.OutgoingSocketThread( 3228): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.OutgoingSocketThread( 3228): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3228): Either failed to read from the output stream or write to the input stream (thread ID: 364, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3228): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3228): onDisconnected: Outgoing connection, peer with ID 7C:F9:0E:51:18:22 disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.OutgoingSocketThread( 3228): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.OutgoingSocketThread( 3228): closeLocalSocketAndStreams: Closing the localhost socket...
,I/io.jxcore.node.OutgoingSocketThread( 3228): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3228): Either failed to read from the output stream or write to the input stream (thread ID: 365, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.OutgoingSocketThread( 3228): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3228): onDisconnected: Outgoing connection, peer with ID 7C:F9:0E:51:18:22 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3228): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3228): disconnectOutgoingConnection: Successfully disconnected (peer ID: 7C:F9:0E:51:18:22
,E/io.jxcore.node.ConnectionHelper( 3228): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 3228): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3228): Exiting thread (ID: 364, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 3228): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 3228): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3228): Exiting thread (ID: 365, name: Receiver)
,I/jxcore-log( 3228): 2015-12-11T19:22:30.676Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3228): 
I/jxcore-log( 3228): ---- round done--------
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): do fake peer & start
I/jxcore-log( 3228): 
I/jxcore-log( 3228): Connect to fake peer: 34:FC:EF:9D:93:0B
I/jxcore-log( 3228): 
I/jxcore-log( 3228): 2015-12-11T19:22:30.677Z SendDataConnector.js: Start called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3228): 
I/jxcore-log( 3228): 2015-12-11T19:22:30.677Z SendDataConnector.js: doConnect called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3228): 
I/jxcore-log( 3228): 2015-12-11T19:22:30.677Z SendDataConnector.js: do connect now
I/jxcore-log( 3228): 
I/io.jxcore.node.ConnectionHelper( 3228): connect: Trying to connect to peer with ID 34:FC:EF:9D:93:0B
D/io.jxcore.node.ConnectionHelper( 3228): hasConnection: No connection with peer with ID 34:FC:EF:9D:93:0B
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): connect: Thali Test's G2
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3228): connect: Trying to start connecting to null in address 34:FC:EF:9D:93:0B
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onConnecting: null 34:FC:EF:9D:93:0B
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3228): connect: Started connecting to null in address 34:FC:EF:9D:93:0B
I/io.jxcore.node.ConnectionHelper( 3228): connect: Connection process successfully started (peer ID: 34:FC:EF:9D:93:0B)
I/chromium( 3228): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 7C:F9:0E:51:18:22 done with result: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): Trying to connect to peer with address 34:FC:EF:9D:93:0B (thread ID: 366)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3228): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3228): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2106): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2106): tBTM_SEC_DEV:0xa41be24c rs_disc_pending=1
W/bt-btif ( 2106): bta_dm_check_av:0
,W/bt-btif ( 2106): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2106): bta_jv_rfc_port_to_cb(port_handle:0x18):jv handle:0x0 not FOUND
,W/bt-rfcomm( 2106): rfc_find_lcid_mcb LCID reused LCID:0x41 current:0x0
W/bt-rfcomm( 2106): RFCOMM_DisconnectInd LCID:0x41
,E/bt-btm  ( 2106): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2106): onReceive
,I/BTConnectionReceiver( 1380): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:51:18:22, alias=null, name=Thali Test (Galaxy A5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1380): Bluetooth Device Name: Thali Test (Galaxy A5)
,E/bt-btm  ( 2106): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2106): onReceive
,I/BTConnectionReceiver( 1380): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1380): Bluetooth Device Name: Nexus 6
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3228): Connection timeout
,W/bt-sdp  ( 2106): SDP - Rcvd conn cnf with error: 0x22  CID 0x42
E/bt-btif ( 2106): DISCOVERY_COMP_EVT slot id:45, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2106): invalid rfc slot id: 45
,W/BluetoothAdapter( 3228): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2106): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2106): No ag scb for peer addr
,I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,E/bt-btif ( 2106): DISCOVERY_COMP_EVT slot id:46, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2106): invalid rfc slot id: 46
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 366)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): Trying to connect again in 300 ms... (thread ID: 366)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3228): onConnectionFailed: Cancelled: Connection timeout
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): stopServiceDiscovery
,I/wpa_supplicant( 1047): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): stopServiceDiscovery
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onIsDiscoveryStartedChanged: false
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT6995","ra":"34:FC:EF:11:AE:67"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3228): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT6995","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onIsDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onConnectionFailed: Cancelled: Connection timeout [34:FC:EF:9D:93:0B LGE-LG-D802_PT7207 34:FC:EF:9D:93:0B]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Peer discovery stopped successfully
W/io.jxcore.node.ConnectionHelper( 3228): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3228): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): restart: Restarting...
,I/jxcore-log( 3228): 2015-12-11T19:24:00.666Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3228): 
I/jxcore-log( 3228): 2015-12-11T19:24:00.666Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3228): 
I/jxcore-log( 3228): 2015-12-11T19:24:00.666Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3228): 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Peer discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3228): Local service added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Peer discovery started successfully
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service requests cleared successfully
,I/wpa_supplicant( 1047): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Peer discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Peer discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): Exiting thread (thread ID: 366)
,I/jxcore-log( 3228): 2015-12-11T19:24:05.667Z SendDataConnector.js: re-try now : 34:FC:EF:9D:93:0B
I/jxcore-log( 3228): 
I/jxcore-log( 3228): 2015-12-11T19:24:05.668Z SendDataConnector.js: ReStart called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3228): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Start timer timeout, starting now...
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): start: Cannot start, because not initialized
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): start: Starting peer discovery...
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 1047): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1047): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 2: Android_1950 b6:ce:f6:ad:a4:6b
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 2: Android_1950 b6:ce:f6:ad:a4:6b
,D/WifiP2pManager( 3228): Ignored { when=-9ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service request added successfully
D/WifiP2pManager( 3228): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service request added successfully
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1047): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 1: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 3: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 4: Thali Test's G2 36:fc:ef:de:0a:e2
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 1: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 3: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 4: Thali Test's G2 36:fc:ef:de:0a:e2
,D/WifiP2pManager( 3228): Ignored { when=-9ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service request added successfully
D/WifiP2pManager( 3228): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service request added successfully
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: 5 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 2: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 3: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 4: Thali Test's G2 36:fc:ef:de:0a:e2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 3228): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service request added successfully
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 1047): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1047): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1047): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/io.jxcore.node.ConnectionHelper( 3228): disconnectOutgoingConnection: Trying to close connection to peer with ID 34:FC:EF:9D:93:0B
E/io.jxcore.node.ConnectionHelper( 3228): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 34:FC:EF:9D:93:0B
D/io.jxcore.node.ConnectionHelper( 3228): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3228): disconnectOutgoingConnection: Failed to disconnect (peer ID: 34:FC:EF:9D:93:0B), either no such connection or failed to close the connection
I/jxcore-log( 3228): 2015-12-11T19:24:10.672Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3228): 
I/jxcore-log( 3228): 2015-12-11T19:24:10.672Z SendDataConnector.js: Connect (retry count 1) to peer 34:FC:EF:9D:93:0B with availability status: true
I/jxcore-log( 3228): 
I/jxcore-log( 3228): 2015-12-11T19:24:10.673Z SendDataConnector.js: doConnect called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3228): 
I/jxcore-log( 3228): 2015-12-11T19:24:10.673Z SendDataConnector.js: do connect now
I/jxcore-log( 3228): 
I/io.jxcore.node.ConnectionHelper( 3228): connect: Trying to connect to peer with ID 34:FC:EF:9D:93:0B
D/io.jxcore.node.ConnectionHelper( 3228): hasConnection: No connection with peer with ID 34:FC:EF:9D:93:0B
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): connect: Thali Test's G2
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3228): connect: Trying to start connecting to null in address 34:FC:EF:9D:93:0B
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onConnecting: null 34:FC:EF:9D:93:0B
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3228): connect: Started connecting to null in address 34:FC:EF:9D:93:0B
I/io.jxcore.node.ConnectionHelper( 3228): connect: Connection process successfully started (peer ID: 34:FC:EF:9D:93:0B)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): Trying to connect to peer with address 34:FC:EF:9D:93:0B (thread ID: 367)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3228): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3228): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2106): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT8142","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT8142 7C:F9:0E:37:96:AB]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT8142","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT8142","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT8142","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT8142","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3228): onPeerDiscovered: Bluetooth address: 7C:F9:0E:37:96:AB, peer name: samsung-SM-A500FU_PT8142, peer ID: 7C:F9:0E:37:96:AB, Wi-Fi Direct device name: A5-1, Wi-Fi Direct address: 7e:f9:0e:37:96:ac
I/io.jxcore.node.ConnectionHelper( 3228): addNewPeerToListAndNotify: Adding peer with ID 7C:F9:0E:37:96:AB
W/io.jxcore.node.ConnectionHelper( 3228): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/wpa_supplicant( 1047): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1047): p2p0: P2P: Reject scan trigger since one is already pending
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceListChanged: Got empty list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT8142","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT8142 7C:F9:0E:37:96:AB]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT8142","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT8142","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT8142","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT8142","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3228): onPeerDiscovered: Bluetooth address: 7C:F9:0E:37:96:AB, peer name: samsung-SM-A500FU_PT8142, peer ID: 7C:F9:0E:37:96:AB, Wi-Fi Direct device name: A5-1, Wi-Fi Direct address: 7e:f9:0e:37:96:ac
I/io.jxcore.node.ConnectionHelper( 3228): addNewPeerToListAndNotify: Peer with ID 7C:F9:0E:37:96:AB already in the list
W/io.jxcore.node.ConnectionHelper( 3228): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT5536","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT5536 B0:C5:59:3F:75:69]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceListChanged: 2 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT5536","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT5536","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT5536","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT5536","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3228): onPeerDiscovered: Bluetooth address: B0:C5:59:3F:75:69, peer name: samsung-SM-G900F_PT5536, peer ID: B0:C5:59:3F:75:69, Wi-Fi Direct device name: Thali Test (Galaxy S5), Wi-Fi Direct address: ee:1f:72:18:8b:78
I/io.jxcore.node.ConnectionHelper( 3228): addNewPeerToListAndNotify: Peer with ID B0:C5:59:3F:75:69 already in the list
W/io.jxcore.node.ConnectionHelper( 3228): onPeerListChanged: Got a list containing 2 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3228): Connection timeout
,W/bt-sdp  ( 2106): SDP - Rcvd conn cnf with error: 0x22  CID 0x4a
E/bt-btif ( 2106): DISCOVERY_COMP_EVT slot id:47, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2106): invalid rfc slot id: 47
,W/BluetoothAdapter( 3228): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2106): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2106): No ag scb for peer addr
,W/bt-btif ( 2106): info:x10
,D/        ( 2106): remote version info [e0:db:10:1f:c9:5e]: 7, f, 230f
,I/BTConnectionReceiver( 1380): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1380): Bluetooth Device Name: Note3-1
,E/bt-btm  ( 2106): tBTM_SEC_DEV:0xa41bdebc rs_disc_pending=0
W/bt-btif ( 2106): bta_dm_check_av:0
,W/bt-btif ( 2106): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2106): new conn_srvc id:26, app_id:255
W/bt-btif ( 2106): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2106): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): Incoming connection initialized (thread ID: 368)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3228): Entering thread (ID: 368)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): onBytesRead: Read 82 bytes successfully (thread ID: 368)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): Got valid identity from [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT7716 E0:DB:10:1F:C9:5E]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): onBytesWritten: 77 bytes successfully written (thread ID: 368)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): removeThreadFromList: Removing thread with ID 368
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): Handshake thread disposed (thread ID: 368)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3228): onIncomingConnectionConnected: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT7716 E0:DB:10:1F:C9:5E]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3228): Exiting thread (ID: 368)
,D/btif_config_util( 2106): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 2106): invalid rfc slot id: 44
,W/bt-rfcomm( 2106): rfc_find_lcid_mcb LCID reused LCID:0x46 current:0x0
W/bt-rfcomm( 2106): RFCOMM_DisconnectInd LCID:0x46
,I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
,E/bt-btm  ( 2106): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2106): onReceive
,I/BTConnectionReceiver( 1380): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1380): Bluetooth Device Name: Note3-1
,E/bt-btif ( 2106): DISCOVERY_COMP_EVT slot id:48, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2106): invalid rfc slot id: 48
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3228): onConnectionFailed: Cancelled: Connection timeout
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 367)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): Trying to connect again in 300 ms... (thread ID: 367)
,I/jxcore-log( 3228): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): The Coordinator has disconnected!
I/jxcore-log( 3228): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): stopServiceDiscovery
,I/wpa_supplicant( 1047): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT6995","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3228): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT6995","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): start: Starting peer discovery...
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onIsDiscoveryStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onConnected: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT7716 E0:DB:10:1F:C9:5E]
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onConnectionFailed: Cancelled: Connection timeout [34:FC:EF:9D:93:0B LGE-LG-D802_PT7207 34:FC:EF:9D:93:0B]
W/io.jxcore.node.ConnectionHelper( 3228): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3228): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3228): Local service added successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): restart: Restarting...
,I/wpa_supplicant( 1047): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
I/io.jxcore.node.ConnectionHelper( 3228): onConnected: Incoming connection, peer ID: E0:DB:10:1F:C9:5E, name: samsung-SM-N9005_PT7716, Bluetooth address: E0:DB:10:1F:C9:5E
D/io.jxcore.node.ConnectionHelper( 3228): hasConnection: No connection with peer with ID E0:DB:10:1F:C9:5E
I/io.jxcore.node.ConnectionHelper( 3228): addNewPeerToListAndNotify: Peer with ID E0:DB:10:1F:C9:5E already in the list
I/io.jxcore.node.ConnectionHelper( 3228): onConnected: Incoming socket thread, for peer with ID E0:DB:10:1F:C9:5E, created successfully
D/io.jxcore.node.ConnectionHelper( 3228): onConnected: The total number of connections is now 1
I/jxcore-log( 3228): 2015-12-11T19:25:41.660Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3228): 
I/jxcore-log( 3228): 2015-12-11T19:25:41.660Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3228): 
I/jxcore-log( 3228): 2015-12-11T19:25:41.660Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3228): 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Peer discovery stopped successfully
,D/io.jxcore.node.IncomingSocketThread( 3228): Entering thread (ID: 369)
,I/jxcore-log( 3228): 2015-12-11T19:25:41.667Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3228): 
,I/io.jxcore.node.IncomingSocketThread( 3228): Local host address: localhost/127.0.0.1, port: 45763
D/io.jxcore.node.IncomingSocketThread( 3228): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3228): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3228): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3228): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3228): Exiting thread (ID: 369)
,I/io.jxcore.node.StreamCopyingThread( 3228): Entering thread (ID: 370, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 3228): Entering thread (ID: 371, name: Receiver)
,I/jxcore-log( 3228): 2015-12-11T19:25:41.672Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3228): 
,W/io.jxcore.node.StreamCopyingThread( 3228): Either failed to read from the output stream or write to the input stream (thread ID: 370, thread name: Sender): Broken pipe
E/io.jxcore.node.IncomingSocketThread( 3228): The sending thread failed with error: Either failed to read from the output stream or write to the input stream: Broken pipe
W/io.jxcore.node.ConnectionHelper( 3228): onDisconnected: Incoming connection, peer with ID E0:DB:10:1F:C9:5E disconnected: Either failed to read from the output stream or write to the input stream: Broken pipe
I/io.jxcore.node.ConnectionHelper( 3228): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 369
I/io.jxcore.node.IncomingSocketThread( 3228): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3228): doStop: Thread ID: 371
I/io.jxcore.node.IncomingSocketThread( 3228): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3228): doStop: Thread ID: 370
I/io.jxcore.node.IncomingSocketThread( 3228): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.IncomingSocketThread( 3228): closeLocalSocketAndStreams: Closing the local input stream...
I/io.jxcore.node.IncomingSocketThread( 3228): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.IncomingSocketThread( 3228): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3228): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3228): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3228): Exiting thread (ID: 370, name: Sender)
,I/jxcore-log( 3228): 2015-12-11T19:25:41.676Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3228): 
,W/io.jxcore.node.StreamCopyingThread( 3228): Either failed to read from the output stream or write to the input stream (thread ID: 371, thread name: Receiver): socket closed
E/io.jxcore.node.IncomingSocketThread( 3228): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: socket closed
W/io.jxcore.node.ConnectionHelper( 3228): onDisconnected: Incoming connection, peer with ID E0:DB:10:1F:C9:5E disconnected: Either failed to read from the output stream or write to the input stream: socket closed
D/io.jxcore.node.ConnectionHelper( 3228): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3228): Exiting thread (ID: 371, name: Receiver)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): Exiting thread (thread ID: 367)
,I/jxcore-log( 3228): DBG, CoordinatorConnector connect called
I/jxcore-log( 3228): 
I/jxcore-log( 3228): Coordinator is now connected to the server!
I/jxcore-log( 3228): 
,I/chromium( 3228): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63)
,W/bt-btif ( 2106): info:x10
,D/        ( 2106): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
,I/BTConnectionReceiver( 1380): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1380): Bluetooth Device Name: Note3-1
,W/bt-btif ( 2106): new conn_srvc id:26, app_id:255
W/bt-btif ( 2106): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2106): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): Incoming connection accepted
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): Incoming connection initialized (thread ID: 372)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3228): Entering thread (ID: 372)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): onBytesRead: Read 82 bytes successfully (thread ID: 372)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): Got valid identity from [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT7716 E0:DB:10:1F:C9:5E]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): onBytesWritten: 77 bytes successfully written (thread ID: 372)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): removeThreadFromList: Removing thread with ID 372
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): Handshake thread disposed (thread ID: 372)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3228): onIncomingConnectionConnected: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT7716 E0:DB:10:1F:C9:5E]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3228): Exiting thread (ID: 372)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onConnected: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT7716 E0:DB:10:1F:C9:5E]
I/io.jxcore.node.ConnectionHelper( 3228): onConnected: Incoming connection, peer ID: E0:DB:10:1F:C9:5E, name: samsung-SM-N9005_PT7716, Bluetooth address: E0:DB:10:1F:C9:5E
D/io.jxcore.node.ConnectionHelper( 3228): hasConnection: No connection with peer with ID E0:DB:10:1F:C9:5E
I/io.jxcore.node.ConnectionHelper( 3228): addNewPeerToListAndNotify: Peer with ID E0:DB:10:1F:C9:5E already in the list
I/io.jxcore.node.ConnectionHelper( 3228): onConnected: Incoming socket thread, for peer with ID E0:DB:10:1F:C9:5E, created successfully
D/io.jxcore.node.ConnectionHelper( 3228): onConnected: The total number of connections is now 1
,D/io.jxcore.node.IncomingSocketThread( 3228): Entering thread (ID: 373)
,I/jxcore-log( 3228): 2015-12-11T19:25:46.407Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3228): 
,I/io.jxcore.node.IncomingSocketThread( 3228): Local host address: localhost/127.0.0.1, port: 45763
D/io.jxcore.node.IncomingSocketThread( 3228): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3228): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 3228): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3228): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3228): Exiting thread (ID: 373)
,I/io.jxcore.node.StreamCopyingThread( 3228): Entering thread (ID: 375, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 3228): Entering thread (ID: 374, name: Sender)
,I/jxcore-log( 3228): 2015-12-11T19:25:46.662Z SendDataConnector.js: re-try now : 34:FC:EF:9D:93:0B
I/jxcore-log( 3228): 
I/jxcore-log( 3228): 2015-12-11T19:25:46.663Z SendDataConnector.js: ReStart called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3228): 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): start: Starting peer discovery...
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/jxcore-log( 3228): 2015-12-11T19:25:47.282Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:25:47.295Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:25:47.318Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:25:47.328Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:25:47.337Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:25:47.347Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:25:47.417Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:25:47.452Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:25:47.461Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:25:47.502Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:25:47.518Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:25:47.546Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:25:47.586Z SendDataTCPServer.js: TCP/IP server has received 41580 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:25:47.597Z SendDataTCPServer.js: TCP/IP server has received 45540 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:25:47.631Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:25:47.643Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:25:47.671Z SendDataTCPServer.js: TCP/IP server has received 63360 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:25:47.698Z SendDataTCPServer.js: TCP/IP server has received 65340 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:25:47.731Z SendDataTCPServer.js: TCP/IP server has received 67320 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:25:47.766Z SendDataTCPServer.js: TCP/IP server has received 69300 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:25:47.780Z SendDataTCPServer.js: TCP/IP server has received 73260 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:25:47.801Z SendDataTCPServer.js: TCP/IP server has received 75240 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:25:47.831Z SendDataTCPServer.js: TCP/IP server has received 83160 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:25:47.849Z SendDataTCPServer.js: TCP/IP server has received 85140 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:25:47.881Z SendDataTCPServer.js: TCP/IP server has received 89100 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:25:47.893Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:25:47.917Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:25:47.951Z SendDataTCPServer.js: TCP/IP server has received 97020 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:25:47.973Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3228): 
,W/bt-btif ( 2106): invalid rfc slot id: 49
,W/io.jxcore.node.StreamCopyingThread( 3228): Either failed to read from the output stream or write to the input stream (thread ID: 375, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.IncomingSocketThread( 3228): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3228): onDisconnected: Incoming connection, peer with ID E0:DB:10:1F:C9:5E disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,I/io.jxcore.node.ConnectionHelper( 3228): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 373
I/io.jxcore.node.IncomingSocketThread( 3228): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3228): doStop: Thread ID: 375
I/io.jxcore.node.IncomingSocketThread( 3228): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3228): doStop: Thread ID: 374
I/io.jxcore.node.IncomingSocketThread( 3228): closeLocalSocketAndStreams: Closing...
,I/io.jxcore.node.IncomingSocketThread( 3228): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3228): Either failed to read from the output stream or write to the input stream (thread ID: 374, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3228): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3228): onDisconnected: Incoming connection, peer with ID E0:DB:10:1F:C9:5E disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.IncomingSocketThread( 3228): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.IncomingSocketThread( 3228): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3228): closeBluetoothSocketAndStreams
,D/io.jxcore.node.ConnectionHelper( 3228): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3228): Exiting thread (ID: 375, name: Receiver)
,D/io.jxcore.node.ConnectionHelper( 3228): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3228): Exiting thread (ID: 374, name: Sender)
,I/jxcore-log( 3228): 2015-12-11T19:25:48.059Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3228): 
,W/bt-rfcomm( 2106): rfc_find_lcid_mcb LCID reused LCID:0x45 current:0x0
W/bt-rfcomm( 2106): RFCOMM_DisconnectInd LCID:0x45
,I/wpa_supplicant( 1047): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1047): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: 2 P2P devices discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3228): Ignored { when=-9ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service request added successfully
D/WifiP2pManager( 3228): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service request added successfully
,D/btif_config_util( 2106): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3228): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service request added successfully
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceListChanged: Got empty list
,D/io.jxcore.node.ConnectionHelper( 3228): disconnectOutgoingConnection: Trying to close connection to peer with ID 34:FC:EF:9D:93:0B
E/io.jxcore.node.ConnectionHelper( 3228): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 34:FC:EF:9D:93:0B
D/io.jxcore.node.ConnectionHelper( 3228): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3228): disconnectOutgoingConnection: Failed to disconnect (peer ID: 34:FC:EF:9D:93:0B), either no such connection or failed to close the connection
I/jxcore-log( 3228): 2015-12-11T19:25:51.667Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3228): 
I/jxcore-log( 3228): 2015-12-11T19:25:51.668Z SendDataConnector.js: Connect (retry count 2) to peer 34:FC:EF:9D:93:0B with availability status: true
I/jxcore-log( 3228): 
I/jxcore-log( 3228): 2015-12-11T19:25:51.668Z SendDataConnector.js: doConnect called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:25:51.669Z SendDataConnector.js: do connect now
I/jxcore-log( 3228): 
,I/io.jxcore.node.ConnectionHelper( 3228): connect: Trying to connect to peer with ID 34:FC:EF:9D:93:0B
D/io.jxcore.node.ConnectionHelper( 3228): hasConnection: No connection with peer with ID 34:FC:EF:9D:93:0B
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): connect: Thali Test's G2
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3228): connect: Trying to start connecting to null in address 34:FC:EF:9D:93:0B
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onConnecting: null 34:FC:EF:9D:93:0B
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3228): connect: Started connecting to null in address 34:FC:EF:9D:93:0B
I/io.jxcore.node.ConnectionHelper( 3228): connect: Connection process successfully started (peer ID: 34:FC:EF:9D:93:0B)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): Trying to connect to peer with address 34:FC:EF:9D:93:0B (thread ID: 376)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3228): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3228): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2106): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2106): tBTM_SEC_DEV:0xa41bdebc rs_disc_pending=1
W/bt-btif ( 2106): bta_dm_check_av:0
,W/bt-btif ( 2106): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2106): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2106): onReceive
,I/BTConnectionReceiver( 1380): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1380): Bluetooth Device Name: Note3-1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceListChanged: Got empty list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: P2P: Reject scan trigger since one is already pending
,I/UsageStatsService(  757): User[0] Flushing usage stats to disk
,I/wpa_supplicant( 1047): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1047): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT7716","ra":"E0:DB:10:1F:C9:5E"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT7716 E0:DB:10:1F:C9:5E]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT7716","ra":"E0:DB:10:1F:C9:5E"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT7716","ra":"E0:DB:10:1F:C9:5E"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3228): onPeerDiscovered: Bluetooth address: E0:DB:10:1F:C9:5E, peer name: samsung-SM-N9005_PT7716, peer ID: E0:DB:10:1F:C9:5E, Wi-Fi Direct device name: , Wi-Fi Direct address: ea:50:8b:de:28:a3
I/io.jxcore.node.ConnectionHelper( 3228): addNewPeerToListAndNotify: Peer with ID E0:DB:10:1F:C9:5E already in the list
,W/io.jxcore.node.ConnectionHelper( 3228): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3228): Connection timeout
,W/bt-sdp  ( 2106): SDP - Rcvd conn cnf with error: 0x22  CID 0x4c
E/bt-btif ( 2106): DISCOVERY_COMP_EVT slot id:51, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2106): invalid rfc slot id: 51
,W/BluetoothAdapter( 3228): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2106): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2106): SDP - Rcvd conn cnf with error: 0x9  CID 0x47
E/bt-btif ( 2106): DISCOVERY_COMP_EVT slot id:52, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2106): invalid rfc slot id: 52
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 376)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): Trying to connect again in 300 ms... (thread ID: 376)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3228): onConnectionFailed: Cancelled: Connection timeout
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onConnectionFailed: Cancelled: Connection timeout [34:FC:EF:9D:93:0B LGE-LG-D802_PT7207 34:FC:EF:9D:93:0B]
I/jxcore-log( 3228): 2015-12-11T19:26:26.334Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3228): 
I/jxcore-log( 3228): 2015-12-11T19:26:26.335Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3228): 
I/jxcore-log( 3228): 2015-12-11T19:26:26.335Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3228): 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): Exiting thread (thread ID: 376)
,I/jxcore-log( 3228): 2015-12-11T19:26:31.337Z SendDataConnector.js: re-try now : 34:FC:EF:9D:93:0B
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:26:31.343Z SendDataConnector.js: ReStart called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3228): 
,D/io.jxcore.node.ConnectionHelper( 3228): disconnectOutgoingConnection: Trying to close connection to peer with ID 34:FC:EF:9D:93:0B
E/io.jxcore.node.ConnectionHelper( 3228): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 34:FC:EF:9D:93:0B
,D/io.jxcore.node.ConnectionHelper( 3228): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3228): disconnectOutgoingConnection: Failed to disconnect (peer ID: 34:FC:EF:9D:93:0B), either no such connection or failed to close the connection
I/jxcore-log( 3228): 2015-12-11T19:26:36.351Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3228): 
I/jxcore-log( 3228): 2015-12-11T19:26:36.352Z SendDataConnector.js: Connect (retry count 3) to peer 34:FC:EF:9D:93:0B with availability status: true
I/jxcore-log( 3228): 
I/jxcore-log( 3228): 2015-12-11T19:26:36.353Z SendDataConnector.js: doConnect called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3228): 
I/jxcore-log( 3228): 2015-12-11T19:26:36.353Z SendDataConnector.js: do connect now
I/jxcore-log( 3228): 
I/io.jxcore.node.ConnectionHelper( 3228): connect: Trying to connect to peer with ID 34:FC:EF:9D:93:0B
D/io.jxcore.node.ConnectionHelper( 3228): hasConnection: No connection with peer with ID 34:FC:EF:9D:93:0B
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): connect: Thali Test's G2
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3228): connect: Trying to start connecting to null in address 34:FC:EF:9D:93:0B
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onConnecting: null 34:FC:EF:9D:93:0B
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3228): connect: Started connecting to null in address 34:FC:EF:9D:93:0B
I/io.jxcore.node.ConnectionHelper( 3228): connect: Connection process successfully started (peer ID: 34:FC:EF:9D:93:0B)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): Trying to connect to peer with address 34:FC:EF:9D:93:0B (thread ID: 377)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3228): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3228): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2106): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2106): SDP - Rcvd conn cnf with error: 0x9  CID 0x4d
E/bt-btif ( 2106): DISCOVERY_COMP_EVT slot id:53, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2106): invalid rfc slot id: 53
,W/BluetoothAdapter( 3228): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2106): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2106): No ag scb for peer addr
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): stopServiceDiscovery
,I/wpa_supplicant( 1047): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT6995","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3228): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT6995","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 3228): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3228): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3228): Local service added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service requests cleared successfully
,I/wpa_supplicant( 1047): P2P-FIND-STOPPED 
I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): restart: Restarting...
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Peer discovery stopped successfully
W/io.jxcore.node.ConnectionHelper( 3228): onPeerListChanged: Got a list of peers, which is null
,I/wpa_supplicant( 1047): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3228): Connection timeout
,E/bt-btif ( 2106): DISCOVERY_COMP_EVT slot id:54, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2106): invalid rfc slot id: 54
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 377)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): Trying to connect again in 300 ms... (thread ID: 377)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3228): onConnectionFailed: Cancelled: Connection timeout
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): start: Starting peer discovery...
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): restart: Restarting...
,I/wpa_supplicant( 1047): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onConnectionFailed: Cancelled: Connection timeout [34:FC:EF:9D:93:0B LGE-LG-D802_PT7207 34:FC:EF:9D:93:0B]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): restart: Restarting...
,I/jxcore-log( 3228): 2015-12-11T19:27:38.481Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3228): 
I/jxcore-log( 3228): 2015-12-11T19:27:38.481Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3228): 
I/jxcore-log( 3228): 2015-12-11T19:27:38.481Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3228): 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Peer discovery stopped successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3228): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): Exiting thread (thread ID: 377)
,W/bt-btif ( 2106): info:x10
,D/        ( 2106): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 2106): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 2106): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 1
E/bt-btif ( 2106): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2106): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2106): Entering PendingCommandState State
,W/BluetoothEventManager( 2727): CachedBluetoothDevice for device 44:80:EB:7B:5A:05 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2727): Got bonding state changed for 44:80:EB:7B:5A:05, but we have no record of that device.
,I/BluetoothBondStateMachine( 2106): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 0
,D/BluetoothAdapterProperties( 2106): Failed to remove device: 44:80:EB:7B:5A:05
,I/BluetoothBondStateMachine( 2106): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2106): StableState(): Entering Off State
,W/BluetoothEventManager( 2727): CachedBluetoothDevice for device 44:80:EB:7B:5A:05 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2727): Got bonding state changed for 44:80:EB:7B:5A:05, but we have no record of that device.
,W/bt-btif ( 2106): new conn_srvc id:26, app_id:255
W/bt-btif ( 2106): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2106): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): Incoming connection initialized (thread ID: 378)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3228): Entering thread (ID: 378)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): onBytesRead: Read 81 bytes successfully (thread ID: 378)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): Got valid identity from [44:80:EB:7B:5A:05 motorola-XT1072_PT3360 44:80:EB:7B:5A:05]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): onBytesWritten: 77 bytes successfully written (thread ID: 378)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): removeThreadFromList: Removing thread with ID 378
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): Handshake thread disposed (thread ID: 378)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3228): onIncomingConnectionConnected: [44:80:EB:7B:5A:05 motorola-XT1072_PT3360 44:80:EB:7B:5A:05]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3228): Exiting thread (ID: 378)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onConnected: [44:80:EB:7B:5A:05 motorola-XT1072_PT3360 44:80:EB:7B:5A:05]
I/io.jxcore.node.ConnectionHelper( 3228): onConnected: Incoming connection, peer ID: 44:80:EB:7B:5A:05, name: motorola-XT1072_PT3360, Bluetooth address: 44:80:EB:7B:5A:05
D/io.jxcore.node.ConnectionHelper( 3228): hasConnection: No connection with peer with ID 44:80:EB:7B:5A:05
I/io.jxcore.node.ConnectionHelper( 3228): addNewPeerToListAndNotify: Adding peer with ID 44:80:EB:7B:5A:05
I/io.jxcore.node.ConnectionHelper( 3228): onConnected: Incoming socket thread, for peer with ID 44:80:EB:7B:5A:05, created successfully
D/io.jxcore.node.ConnectionHelper( 3228): onConnected: The total number of connections is now 1
,D/io.jxcore.node.IncomingSocketThread( 3228): Entering thread (ID: 379)
,I/io.jxcore.node.IncomingSocketThread( 3228): Local host address: localhost/127.0.0.1, port: 45763
D/io.jxcore.node.IncomingSocketThread( 3228): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3228): setBufferSize: Setting buffer size to 8192 bytes
,I/jxcore-log( 3228): 2015-12-11T19:27:39.647Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3228): 
,I/io.jxcore.node.StreamCopyingThread( 3228): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3228): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3228): Exiting thread (ID: 379)
,I/io.jxcore.node.StreamCopyingThread( 3228): Entering thread (ID: 381, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 3228): Entering thread (ID: 380, name: Sender)
,I/jxcore-log( 3228): 2015-12-11T19:27:40.481Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:27:40.492Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:27:40.501Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:27:40.513Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:27:40.545Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:27:40.571Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:27:40.577Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:27:40.586Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:27:40.625Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:27:40.637Z SendDataTCPServer.js: TCP/IP server has received 32768 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:27:40.674Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:27:40.721Z SendDataTCPServer.js: TCP/IP server has received 42668 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:27:40.752Z SendDataTCPServer.js: TCP/IP server has received 48608 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:27:40.761Z SendDataTCPServer.js: TCP/IP server has received 50588 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:27:40.775Z SendDataTCPServer.js: TCP/IP server has received 54548 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:27:40.813Z SendDataTCPServer.js: TCP/IP server has received 64448 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:27:40.821Z SendDataTCPServer.js: TCP/IP server has received 66428 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:27:40.831Z SendDataTCPServer.js: TCP/IP server has received 68408 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:27:40.862Z SendDataTCPServer.js: TCP/IP server has received 70388 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:27:40.873Z SendDataTCPServer.js: TCP/IP server has received 72368 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:27:40.957Z SendDataTCPServer.js: TCP/IP server has received 84248 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:27:40.967Z SendDataTCPServer.js: TCP/IP server has received 88208 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:27:40.973Z SendDataTCPServer.js: TCP/IP server has received 90188 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:27:41.014Z SendDataTCPServer.js: TCP/IP server has received 92168 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:27:41.052Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3228): 
,W/bt-btif ( 2106): invalid rfc slot id: 50
,W/io.jxcore.node.StreamCopyingThread( 3228): Either failed to read from the output stream or write to the input stream (thread ID: 381, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 3228): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3228): onDisconnected: Incoming connection, peer with ID 44:80:EB:7B:5A:05 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3228): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 379
I/io.jxcore.node.IncomingSocketThread( 3228): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3228): doStop: Thread ID: 381
I/io.jxcore.node.IncomingSocketThread( 3228): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3228): doStop: Thread ID: 380
I/io.jxcore.node.IncomingSocketThread( 3228): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.IncomingSocketThread( 3228): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3228): Either failed to read from the output stream or write to the input stream (thread ID: 380, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3228): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3228): onDisconnected: Incoming connection, peer with ID 44:80:EB:7B:5A:05 disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.IncomingSocketThread( 3228): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.IncomingSocketThread( 3228): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3228): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3228): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3228): Exiting thread (ID: 381, name: Receiver)
,D/io.jxcore.node.ConnectionHelper( 3228): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3228): Exiting thread (ID: 380, name: Sender)
,I/jxcore-log( 3228): 2015-12-11T19:27:41.135Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3228): 
,W/bt-rfcomm( 2106): rfc_find_lcid_mcb LCID reused LCID:0x4b current:0x0
W/bt-rfcomm( 2106): RFCOMM_DisconnectInd LCID:0x4b
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): start: Starting peer discovery...
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3228): 2015-12-11T19:27:43.507Z SendDataConnector.js: re-try now : 34:FC:EF:9D:93:0B
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:27:43.508Z SendDataConnector.js: ReStart called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3228): 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,D/btif_config_util( 2106): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2106): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2106): onReceive
,I/BTConnectionReceiver( 1380): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1380): Bluetooth Device Name: XT1072
,I/wpa_supplicant( 1047): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 1: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3228): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service request added successfully
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1047): P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2p_dev_addr=3a:94:96:b5:06:dd pri_dev_type=10-0050F204-5 name='Galaxy S5-2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1047): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1047): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT7093","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Resolved peer properties: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT7093 90:E7:C4:F6:69:77]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerListChanged
I/io.jxcore.node.ConnectionHelper( 3228): onPeerDiscovered: Bluetooth address: 90:E7:C4:F6:69:77, peer name: HTC-HTC One M8s_PT7093, peer ID: 90:E7:C4:F6:69:77, Wi-Fi Direct device name: Android_608e, Wi-Fi Direct address: 92:e7:c4:e6:4c:f8
I/io.jxcore.node.ConnectionHelper( 3228): addNewPeerToListAndNotify: Adding peer with ID 90:E7:C4:F6:69:77
,W/io.jxcore.node.ConnectionHelper( 3228): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT5056"}", service type: "Cordovap2p._tcp.local."
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Resolved peer properties: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT5056 00:F4:6F:30:E0:6C]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceListChanged: 2 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerListChanged
I/io.jxcore.node.ConnectionHelper( 3228): onPeerDiscovered: Bluetooth address: 00:F4:6F:30:E0:6C, peer name: samsung-SM-G800F_PT5056, peer ID: 00:F4:6F:30:E0:6C, Wi-Fi Direct device name: , Wi-Fi Direct address: 02:f4:6f:30:e0:6d
I/io.jxcore.node.ConnectionHelper( 3228): addNewPeerToListAndNotify: Peer with ID 00:F4:6F:30:E0:6C already in the list
W/io.jxcore.node.ConnectionHelper( 3228): onPeerListChanged: Got a list containing 2 peer(s), but doing nothing with that list
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/io.jxcore.node.ConnectionHelper( 3228): disconnectOutgoingConnection: Trying to close connection to peer with ID 34:FC:EF:9D:93:0B
E/io.jxcore.node.ConnectionHelper( 3228): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 34:FC:EF:9D:93:0B
D/io.jxcore.node.ConnectionHelper( 3228): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3228): disconnectOutgoingConnection: Failed to disconnect (peer ID: 34:FC:EF:9D:93:0B), either no such connection or failed to close the connection
I/jxcore-log( 3228): 2015-12-11T19:27:48.518Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:27:48.518Z SendDataConnector.js: Connect (retry count 4) to peer 34:FC:EF:9D:93:0B with availability status: true
I/jxcore-log( 3228): 
I/jxcore-log( 3228): 2015-12-11T19:27:48.523Z SendDataConnector.js: doConnect called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:27:48.526Z SendDataConnector.js: do connect now
I/jxcore-log( 3228): 
,I/io.jxcore.node.ConnectionHelper( 3228): connect: Trying to connect to peer with ID 34:FC:EF:9D:93:0B
D/io.jxcore.node.ConnectionHelper( 3228): hasConnection: No connection with peer with ID 34:FC:EF:9D:93:0B
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): connect: Thali Test's G2
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3228): connect: Trying to start connecting to null in address 34:FC:EF:9D:93:0B
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onConnecting: null 34:FC:EF:9D:93:0B
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3228): connect: Started connecting to null in address 34:FC:EF:9D:93:0B
I/io.jxcore.node.ConnectionHelper( 3228): connect: Connection process successfully started (peer ID: 34:FC:EF:9D:93:0B)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): Trying to connect to peer with address 34:FC:EF:9D:93:0B (thread ID: 382)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3228): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
,W/BluetoothAdapter( 3228): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2106): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1047): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,W/bt-btif ( 2106): info:x10
,D/        ( 2106): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2106): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 2106): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 1
E/bt-btif ( 2106): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2106): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2106): Entering PendingCommandState State
,W/BluetoothEventManager( 2727): CachedBluetoothDevice for device 7C:F9:0E:37:96:AB not found, calling readPairedDevices().
,E/BluetoothEventManager( 2727): Got bonding state changed for 7C:F9:0E:37:96:AB, but we have no record of that device.
,I/BluetoothBondStateMachine( 2106): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 0
,D/BluetoothAdapterProperties( 2106): Failed to remove device: 7C:F9:0E:37:96:AB
,I/BluetoothBondStateMachine( 2106): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2106): StableState(): Entering Off State
,W/BluetoothEventManager( 2727): CachedBluetoothDevice for device 7C:F9:0E:37:96:AB not found, calling readPairedDevices().
,E/BluetoothEventManager( 2727): Got bonding state changed for 7C:F9:0E:37:96:AB, but we have no record of that device.
,W/bt-btif ( 2106): new conn_srvc id:26, app_id:255
W/bt-btif ( 2106): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2106): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): Incoming connection initialized (thread ID: 383)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3228): Entering thread (ID: 383)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): onBytesRead: Read 83 bytes successfully (thread ID: 383)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): Got valid identity from [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT8142 7C:F9:0E:37:96:AB]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): onBytesWritten: 77 bytes successfully written (thread ID: 383)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): removeThreadFromList: Removing thread with ID 383
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): Handshake thread disposed (thread ID: 383)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3228): onIncomingConnectionConnected: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT8142 7C:F9:0E:37:96:AB]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3228): Exiting thread (ID: 383)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onConnected: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT8142 7C:F9:0E:37:96:AB]
I/io.jxcore.node.ConnectionHelper( 3228): onConnected: Incoming connection, peer ID: 7C:F9:0E:37:96:AB, name: samsung-SM-A500FU_PT8142, Bluetooth address: 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 3228): hasConnection: No connection with peer with ID 7C:F9:0E:37:96:AB
I/io.jxcore.node.ConnectionHelper( 3228): addNewPeerToListAndNotify: Peer with ID 7C:F9:0E:37:96:AB already in the list
I/io.jxcore.node.ConnectionHelper( 3228): onConnected: Incoming socket thread, for peer with ID 7C:F9:0E:37:96:AB, created successfully
D/io.jxcore.node.ConnectionHelper( 3228): onConnected: The total number of connections is now 1
,D/io.jxcore.node.IncomingSocketThread( 3228): Entering thread (ID: 384)
,I/jxcore-log( 3228): 2015-12-11T19:27:52.616Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3228): 
,I/io.jxcore.node.IncomingSocketThread( 3228): Local host address: localhost/127.0.0.1, port: 45763
,D/io.jxcore.node.IncomingSocketThread( 3228): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3228): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 3228): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3228): startStreamCopyingThreads: OK
,D/io.jxcore.node.IncomingSocketThread( 3228): Exiting thread (ID: 384)
,I/io.jxcore.node.StreamCopyingThread( 3228): Entering thread (ID: 386, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 3228): Entering thread (ID: 385, name: Sender)
,I/jxcore-log( 3228): 2015-12-11T19:27:53.586Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:27:53.793Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:27:53.804Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:27:53.918Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:27:54.004Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:27:54.012Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:27:54.024Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:27:54.091Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:27:54.178Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:27:54.423Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:27:54.551Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:27:54.621Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:27:54.651Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:27:54.751Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:27:54.954Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:27:55.070Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:27:55.101Z SendDataTCPServer.js: TCP/IP server has received 35640 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:27:55.246Z SendDataTCPServer.js: TCP/IP server has received 37620 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:27:55.255Z SendDataTCPServer.js: TCP/IP server has received 39600 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:27:55.338Z SendDataTCPServer.js: TCP/IP server has received 41580 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:27:55.371Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:27:55.412Z SendDataTCPServer.js: TCP/IP server has received 45540 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:27:55.583Z SendDataTCPServer.js: TCP/IP server has received 47520 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:27:55.816Z SendDataTCPServer.js: TCP/IP server has received 49500 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:27:55.891Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:27:55.909Z SendDataTCPServer.js: TCP/IP server has received 55440 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:27:56.013Z SendDataTCPServer.js: TCP/IP server has received 57420 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:27:56.019Z SendDataTCPServer.js: TCP/IP server has received 59400 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:27:56.127Z SendDataTCPServer.js: TCP/IP server has received 61380 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:27:56.325Z SendDataTCPServer.js: TCP/IP server has received 63360 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:27:56.361Z SendDataTCPServer.js: TCP/IP server has received 65340 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:27:56.408Z SendDataTCPServer.js: TCP/IP server has received 67320 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:27:56.504Z SendDataTCPServer.js: TCP/IP server has received 69300 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:27:56.543Z SendDataTCPServer.js: TCP/IP server has received 71280 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:27:56.629Z SendDataTCPServer.js: TCP/IP server has received 73260 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:27:56.662Z SendDataTCPServer.js: TCP/IP server has received 75240 bytes of data
I/jxcore-log( 3228): 
,D/btif_config_util( 2106): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3228): 2015-12-11T19:27:56.857Z SendDataTCPServer.js: TCP/IP server has received 77220 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:27:56.950Z SendDataTCPServer.js: TCP/IP server has received 79200 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:27:57.054Z SendDataTCPServer.js: TCP/IP server has received 81180 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:27:57.072Z SendDataTCPServer.js: TCP/IP server has received 83160 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:27:57.286Z SendDataTCPServer.js: TCP/IP server has received 85140 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:27:57.394Z SendDataTCPServer.js: TCP/IP server has received 87120 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:27:57.706Z SendDataTCPServer.js: TCP/IP server has received 89100 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:27:57.720Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:27:57.796Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:27:57.923Z SendDataTCPServer.js: TCP/IP server has received 95040 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:27:57.931Z SendDataTCPServer.js: TCP/IP server has received 97020 bytes of data
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): 2015-12-11T19:27:58.235Z SendDataTCPServer.js: TCP/IP server has received 99000 bytes of data
I/jxcore-log( 3228): 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3228): 2015-12-11T19:27:58.454Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3228): 
,W/bt-btif ( 2106): invalid rfc slot id: 55
,W/io.jxcore.node.StreamCopyingThread( 3228): Either failed to read from the output stream or write to the input stream (thread ID: 386, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.IncomingSocketThread( 3228): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
,W/io.jxcore.node.ConnectionHelper( 3228): onDisconnected: Incoming connection, peer with ID 7C:F9:0E:37:96:AB disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3228): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 384
I/io.jxcore.node.IncomingSocketThread( 3228): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3228): doStop: Thread ID: 386
I/io.jxcore.node.IncomingSocketThread( 3228): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3228): doStop: Thread ID: 385
,I/io.jxcore.node.IncomingSocketThread( 3228): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.IncomingSocketThread( 3228): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3228): Either failed to read from the output stream or write to the input stream (thread ID: 385, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3228): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3228): onDisconnected: Incoming connection, peer with ID 7C:F9:0E:37:96:AB disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.IncomingSocketThread( 3228): closeLocalSocketAndStreams: Closing the local output stream...
,I/io.jxcore.node.IncomingSocketThread( 3228): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3228): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3228): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.ConnectionHelper( 3228): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3228): Exiting thread (ID: 385, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 3228): Exiting thread (ID: 386, name: Receiver)
,I/jxcore-log( 3228): 2015-12-11T19:27:58.697Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3228): 
,W/bt-rfcomm( 2106): rfc_find_lcid_mcb LCID reused LCID:0x42 current:0x0
,W/bt-rfcomm( 2106): RFCOMM_DisconnectInd LCID:0x42
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 2106): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2106): onReceive
,I/BTConnectionReceiver( 1380): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1380): Bluetooth Device Name: A5-1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3228): Connection timeout
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2106): SDP - Rcvd conn cnf with error: 0x22  CID 0x4f
E/bt-btif ( 2106): DISCOVERY_COMP_EVT slot id:56, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2106): invalid rfc slot id: 56
,W/BluetoothAdapter( 3228): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2106): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2106): No ag scb for peer addr
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-smp  ( 2106): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2106): Plain text(LSB ~ MSB) = 53 31 7f 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2106): Encrypted text(LSB ~ MSB) = ed 31 30 20 80 52 21 50 41 fb ae 87 d6 67 c0 73 
W/bt-btm  ( 2106): Stopping oneshot timer
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btif ( 2106): DISCOVERY_COMP_EVT slot id:58, failed to find channle,                                       status:1, scn:0
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 382)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): Trying to connect again in 300 ms... (thread ID: 382)
,W/bt-btif ( 2106): invalid rfc slot id: 58
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3228): onConnectionFailed: Cancelled: Connection timeout
,I/jxcore-log( 3228): timeout now
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): dun
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): weAreDoneNow , resultArray.length: 3
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): done, now sending data to server
I/jxcore-log( 3228): 
I/jxcore-log( 3228): DBG, CoordinatorConnector sendData called
I/jxcore-log( 3228): 
I/jxcore-log( 3228): -- RESULT DATA {"name:":"LGE-Nexus 5_PT6995","time":1003023,"result":"TIMEOUT","sendList":[{"name":"E0:DB:10:1F:C9:5E","time":12964,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"F8:CF:C5:D9:E5:61","time":10866,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:51:18:22","time":156809,"result":"OK","connections":5,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"connections":1,"name":"34:FC:EF:9D:93:0B","time":0,"result":"Fail"},{"connections":0,"name":"38:94:96:B5:06:DC","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:85:54","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:3C:51","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:75:41","time":0,"result":"Fail"},{"connections":0,"name":"80:01:84:8A:B3:68","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:76:27","time":0,"result":"Fail"},{"connections":
I/jxcore-log( 3228): sendList : 100% : 156809 ms, 99% : 156809 ms, 95 : 156809 ms, 90% : 156809 ms.
I/jxcore-log( 3228): 
I/jxcore-log( 3228): Result count 3, range 10866 ms to  156809 ms.
I/jxcore-log( 3228): 
I/jxcore-log( 3228): sendList failed peers count : 2 [40 %]
I/jxcore-log( 3228): 
I/jxcore-log( 3228): - Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
I/jxcore-log( 3228): 
I/jxcore-log( 3228): - Peer ID : 34:FC:EF:11:B1:66, Tried : 1
I/jxcore-log( 3228): 
I/jxcore-log( 3228): sendList never tried peers count : 17 [77.27272727272727 %]
I/jxcore-log( 3228): 
I/jxcore-log( 3228): - Peer ID : 38:94:96:B5:06:DC
I/jxcore-log( 3228): 
I/jxcore-log( 3228): - Peer ID : F8:95:C7:87:85:54
I/jxcore-log( 3228): 
I/jxcore-log( 3228): - Peer ID : F8:95:C7:87:3C:51
I/jxcore-log( 3228): 
I/jxcore-log( 3228): - Peer ID : 08:EC:A9:50:75:41
I/jxcore-log( 3228): 
I/jxcore-log( 3228): - Peer ID : 80:01:84:8A:B3:68
I/jxcore-log( 3228): 
I/jxcore-log( 3228): - Peer ID : 08:EC:A9:50:76:27
I/jxcore-log( 3228): 
I/jxcore-log( 3228): - Peer ID : 7C:F9:0E:37:96:AB
I/jxcore-log( 3228): 
I/jxcore-log( 3228): - Peer ID : 58:2A:F7:ED:96:BE
I/jxcore-log( 3228): 
I/jxcore-log( 3228): - Peer ID : 58:3F:54:73:64:C0
I/jxcore-log( 3228): 
I/jxcore-log( 3228): - Peer ID : 44:80:EB:7B:5A:05
I/jxcore-log( 3228): 
I/jxcore-log( 3228): - Peer ID : F4:F1:E1:5C:3B:E2
I/jxcore-log( 3228): 
I/jxcore-log( 3228): - Peer ID : B0:C5:59:3F:75:69
I/jxcore-log( 3228): 
I/jxcore-log( 3228): - Peer ID : B4:CE:F6:AB:A4:6A
I/jxcore-log( 3228): 
I/jxcore-log( 3228): - Peer ID : 90:E7:C4:F6:69:77
I/jxcore-log( 3228): 
I/jxcore-log( 3228): - Peer ID : E0:DB:10:14:E2:C0
I/jxcore-log( 3228): 
I/jxcore-log( 3228): - Peer ID : 00:F4:6F:30:E0:6C
I/jxcore-log( 3228): 
I/jxcore-log( 3228): - Peer ID : 7C:F9:0E:34:8A:A0
I/jxcore-log( 3228): 
I/jxcore-log( 3228): 2015-12-11T19:29:20.698Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3228): 
D/io.jxcore.node.ConnectionHelper( 3228): disconnectOutgoingConnection: Trying to close connection to peer with ID 34:FC:EF:9D:93:0B
E/io.jxcore.node.ConnectionHelper( 3228): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 34:FC:EF:9D:93:0B
D/io.jxcore.node.ConnectionHelper( 3228): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3228): disconnectOutgoingConnection: Failed to disconnect (peer ID: 34:FC:EF:9D:93:0B), either no such connection or failed to close the connection
I/jxcore-log( 3228): 2015-12-11T19:29:20.698Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3228): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT5536","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT5536 B0:C5:59:3F:75:69]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerDiscovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceListChanged: 3 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): stopServiceDiscovery
,I/wpa_supplicant( 1047): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:ff:f0
I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=3a:94:96:b5:06:dd
I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT6995","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3228): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT6995","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onIsDiscoveryStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Identity: "{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT3473","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Resolved peer properties: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT3473 F8:CF:C5:D9:E5:61]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT8201","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT8201 08:EC:A9:50:75:41]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceListChanged: 2 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT7716","ra":"E0:DB:10:1F:C9:5E"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT7716 E0:DB:10:1F:C9:5E]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceListChanged: 3 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Identity: "{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT8021"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Resolved peer properties: [B4:CE:F6:AB:A4:6A HTC-HTC Desire 820_PT8021 B4:CE:F6:AB:A4:6A]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceListChanged: 4 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT5708","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT5708 F8:95:C7:87:85:54]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceListChange,d: 5 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT2316","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2316 E0:DB:10:14:E2:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceListChanged: 6 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4634","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT4634 7C:F9:0E:34:8A:A0]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceListChanged: 7 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT2944","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT2944 58:3F:54:73:64:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceListChanged: 8 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onConnectionFailed: Cancelled: Connection timeout [34:FC:EF:9D:93:0B LGE-LG-D802_PT7207 34:FC:EF:9D:93:0B]
I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
I/chromium( 3228): [INFO:CONSOLE(63)] "logCallback *** TIMEOUT ***", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3228): [INFO:CONSOLE(63)] "logCallback ---- finished : send-data -- ", source: file:///android_asset/www/js/thali_main.js (63)
I/io.jxcore.node.ConnectionHelper( 3228): onPeerDiscovered: Bluetooth address: B0:C5:59:3F:75:69, peer name: samsung-SM-G900F_PT5536, peer ID: B0:C5:59:3F:75:69, Wi-Fi Direct device name: , Wi-Fi Direct address: ee:1f:72:18:8b:78
I/io.jxcore.node.ConnectionHelper( 3228): addNewPeerToListAndNotify: Peer with ID B0:C5:59:3F:75:69 already in the list
W/io.jxcore.node.ConnectionHelper( 3228): onPeerListChanged: Got a list containing 3 peer(s), but doing nothing with that list
W/io.jxcore.node.ConnectionHelper( 3228): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3228): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3228): Local service added successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): restart: Restarting...
I/wpa_supplicant( 1047): P2P-FIND-STOPPED 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
I/io.jxcore.node.ConnectionHelper( 3228): onPeerDiscovered: Bluetooth address: F8:CF:C5:D9:E5:61, peer name: motorola-Nexus 6_PT3473, peer ID: F8:CF:C5:D9:E5:61, Wi-Fi Direct device name: Android_50a5, Wi-Fi Direct address: fa:cf:c5:d9:e5:62
I/io.jxcore.node.ConnectionHelper( 3228): addNewPeerToListAndNotify: Peer with ID F8:CF:C5:D9:E5:61 already in the list
W/io.jxcore.node.ConnectionHelper( 3228): onPeerListChanged: Got a list containing 8 peer(s), but doing nothing with that list
I/io.jxcore.node.ConnectionHelper( 3228): onPeerDiscovered: Bluetooth address: 08:EC:A9:50:75:41, peer name: samsung-SM-A300FU_PT8201, peer ID: 08:EC:A9:50:75:41, Wi-Fi Direct device name: , Wi-Fi Direct address: 0a:ec:a9:50:75:42
I/io.jxcore.node.ConnectionHelper( 3228): addNewPeerToListAndNotify: Adding peer with ID 08:EC:A9:50:75:41
W/io.jxcore.node.ConnectionHelper( 3228): onPeerListChanged: Got a list containing 8 peer(s), but doing nothing with that list
I/io.jxcore.node.ConnectionHelper( 3228): onPeerDiscovered: Bluetooth address: E0:DB:10:1F:C9:5E, peer name: samsung-SM-N9005_PT7716, peer ID: E0:DB:10:1F:C9:5E, Wi-Fi Direct device name: , Wi-Fi Direct address: ea:50:8b:de:28:a3
I/io.jxcore.node.ConnectionHelper( 3228): addNewPeerToListAndNotify: Peer with ID E0:DB:10:1F:C9:5E already in the list
W/io.jxcore.node.ConnectionHelper( 3228): onPeerListChanged: Got a list containing 8 peer(s), but doing nothing with that list
I/io.jxcore.node.ConnectionHelper( 3228): onPeerDiscovered: Bluetooth address: B4:CE:F6:AB:A4:6A, peer name: HTC-HTC Desire 820_PT8021, peer ID: B4:CE:F6:AB:A4:6A, Wi-Fi Direct device name: , Wi-Fi Direct address: b6:ce:f6:ad:a4:6b
I/io.jxcore.node.ConnectionHelper( 3228): addNewPeerToListAndNotify: Peer with ID B4:CE:F6:AB:A4:6A already in the list
W/io.jxcore.node.ConnectionHelper( 3228): onPeerListChanged: Got a list containing 8 peer(s), but doing nothing with that list
I/io.jxcore.node.ConnectionHelper( 3228): onPeerDiscovered: Bluetooth address: F8:95:C7:87:85:54, peer name: LGE-LG-D722_PT5708, peer ID: F8:95:C7:87:85:54, Wi-Fi Direct device name: G3s-1, Wi-Fi Direct address: a2:39:f7:70:12:80
I/io.jxcore.node.ConnectionHelper( 3228): addNewPeerToListAndNotify: Adding peer with ID F8:95:C7:87:85:54
W/io.jxcore.node.ConnectionHelper( 3228): onPeerListChanged: Got a list containing 8 peer(s), but doing nothing with that list
I/io.jxcore.node.ConnectionHelper( 3228): onPeerDiscovered: Bluetooth address: E0:DB:10:14:E2:C0, peer name: samsung-SM-N910C_PT2316, peer ID: E0:DB:10:14:E2:C0, Wi-Fi Direct device name: , Wi-Fi Direct address: 92:b6:86:43:73:1c
I/io.jxcore.node.ConnectionHelper( 3228): addNewPeerToListAndNotify: Peer with ID E0:DB:10:14:E2:C0 already in the list
W/io.jxcore.node.ConnectionHelper( 3228): onPeerListChanged: Got a list containing 8 peer(s), but doing nothing with that list
I/io.jxcore.node.ConnectionHelper( 3228): onPeerDiscovered: Bluetooth address: 7C:F9:0E:34:8A:A0, peer name: samsung-SM-G900F_PT4634, peer ID: 7C:F9:0E:34:8A:A0, Wi-Fi Direct device name: S5-1, Wi-Fi Direct address: ee:1f:72:63:11:86
I/io.jxcore.node.ConnectionHelper( 3228): addNewPeerToListAndNotify: Adding peer with ID 7C:F9:0E:34:8A:A0
W/io.jxcore.node.ConnectionHelper( 3228): onPeerListChanged: Got a list containing 8 peer(s), but doing nothing with that list
I/io.jxcore.node.ConnectionHelper( 3228): onPeerDiscovered: Bluetooth address: 58:3F:54:73:64:C0, peer name: LGE-LG-D855_PT2944, peer ID: 58:3F:54:73:64:C0, Wi-Fi Direct device name: , Wi-Fi Direct address: 02:9a:02:7b:60:ac
I/io.jxcore.node.ConnectionHelper( 3228): addNewPeerToListAndNotify: Peer with ID 58:3F:54:73:64:C0 already in the list
W/io.jxcore.node.ConnectionHelper( 3228): onPeerListChanged: Got a list containing 8 peer(s), but doing nothing with that list
I/jxcore-log( 3228): 2015-12-11T19:29:20.741Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3228): 
I/jxcore-log( 3228): 2015-12-11T19:29:20.741Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3228): 
I/jxcore-log( 3228): 2015-12-11T19:29:20.741Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3228): 
D/io.jxcore.node.ConnectionHelper( 3228): disconnectOutgoingConnection: Trying to close connection to peer with ID 34:FC:EF:9D:93:0B
E/io.jxcore.node.ConnectionHelper( 3228): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 34:FC:EF:9D:93:0B
D/io.jxcore.node.ConnectionHelper( 3228): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3228): disconnectOutgoingConnection: Failed to disconnect (peer ID: 34:FC:EF:9D:93:0B), either no such connection or failed to close the connection
I/jxcore-log( 3228): 2015-12-11T19:29:20.742Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3228): 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Peer discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3228): Exiting thread (thread ID: 382)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): start: Starting peer discovery...
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 1047): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 1: Thali Test's G2 36:fc:ef:de:0a:e2
,D/WifiP2pManager( 3228): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service request added successfully
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1047): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 1: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 2: Thali Test's G2 36:fc:ef:de:0a:e2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 1: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 2: Thali Test's G2 36:fc:ef:de:0a:e2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
,D/WifiP2pManager( 3228): Ignored { when=-9ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service request added successfully
D/WifiP2pManager( 3228): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service request added successfully
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 1: S5mini-1 02:f4:6f:30:e0:6d
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 3: Thali Test's G2 36:fc:ef:de:0a:e2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 4: Android_608e 92:e7:c4:e6:4c:f8
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceListChanged: Got empty list
D/WifiP2pManager( 3228): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service request added successfully
,I/wpa_supplicant( 1047): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1047): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1047): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1047): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1047): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): stopServiceDiscovery
,I/wpa_supplicant( 1047): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Peer discovery stopped successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3228): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3228): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3228): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3228): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3228): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3228): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): start: Starting peer discovery...
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
,D/WifiP2pManager( 3228): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service request added successfully
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1047): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1047): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1047): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 3: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 4: G3-1 02:9a:02:7b:60:ac
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: 5 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 4: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: 5 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 4: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 3228): Ignored { when=-3ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service request added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: 5 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 4: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 3228): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service request added successfully
,D/WifiP2pManager( 3228): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service request added successfully
D/WifiP2pManager( 3228): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service request added successfully
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: 6 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 4: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 5: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 3228): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service request added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service discovery started successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1047): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1047): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1047): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1047): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceListChanged: Got empty list
,I/jxcore-log( 3228): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): The Coordinator has disconnected!
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): DBG, CoordinatorConnector connect called
I/jxcore-log( 3228): 
I/jxcore-log( 3228): Coordinator is now connected to the server!
I/jxcore-log( 3228): 
,I/chromium( 3228): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): stopServiceDiscovery
,I/wpa_supplicant( 1047): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:ff:f0
I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Peer discovery stopped successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3228): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3228): onPeerListChanged: Got a list of peers, which is null
,W/io.jxcore.node.ConnectionHelper( 3228): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3228): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3228): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3228): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Peer discovery started successfully
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 1047): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 1: S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 3228): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service request added successfully
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 1: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 2: Android_2dc2 52:55:27:f0:ff:f0
,D/WifiP2pManager( 3228): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service request added successfully
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1047): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1047): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service discovery started successfully
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceListChanged: Got empty list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT2944","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT2944 58:3F:54:73:64:C0]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerDiscovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT2944","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3228): onPeerDiscovered: Bluetooth address: 58:3F:54:73:64:C0, peer name: LGE-LG-D855_PT2944, peer ID: 58:3F:54:73:64:C0, Wi-Fi Direct device name: G3-1, Wi-Fi Direct address: 02:9a:02:7b:60:ac
I/io.jxcore.node.ConnectionHelper( 3228): addNewPeerToListAndNotify: Peer with ID 58:3F:54:73:64:C0 already in the list
W/io.jxcore.node.ConnectionHelper( 3228): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/wpa_supplicant( 1047): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6611","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6611 08:EC:A9:50:76:27]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceListChanged: 2 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6611","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3228): onPeerDiscovered: Bluetooth address: 08:EC:A9:50:76:27, peer name: samsung-SM-A300FU_PT6611, peer ID: 08:EC:A9:50:76:27, Wi-Fi Direct device name: Thali Test (Galaxy A3), Wi-Fi Direct address: 0a:ec:a9:50:76:28
I/io.jxcore.node.ConnectionHelper( 3228): addNewPeerToListAndNotify: Peer with ID 08:EC:A9:50:76:27 already in the list
W/io.jxcore.node.ConnectionHelper( 3228): onPeerListChanged: Got a list containing 2 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT2944","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT2944","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT8201","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT8201 08:EC:A9:50:75:41]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceListChanged: 3 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT8201","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3228): onPeerDiscovered: Bluetooth address: 08:EC:A9:50:75:41, peer name: samsung-SM-A300FU_PT8201, peer ID: 08:EC:A9:50:75:41, Wi-Fi Direct device name: , Wi-Fi Direct address: 0a:ec:a9:50:75:42
I/io.jxcore.node.ConnectionHelper( 3228): addNewPeerToListAndNotify: Peer with ID 08:EC:A9:50:75:41 already in the list
W/io.jxcore.node.ConnectionHelper( 3228): onPeerListChanged: Got a list containing 3 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): stopServiceDiscovery
,I/wpa_supplicant( 1047): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:ff:f0
I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT6995","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3228): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT6995","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/art     (  757): Explicit concurrent mark sweep GC freed 111729(5MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 28MB/43MB, paused 1.205ms total 79.188ms
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): start: Starting peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 3228): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3228): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3228): Local service added successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Peer discovery started successfully,
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service requests cleared successfully
,I/wpa_supplicant( 1047): P2P-FIND-STOPPED 
I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Peer discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Peer discovery stopped successfully
,I/wpa_supplicant( 1047): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1047): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1047): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1047): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1047): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: 5 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 4: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: 5 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 4: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: 5 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 4: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): startServiceDiscovery: Invalid state, try calling restart()
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: 5 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 4: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: 5 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 4: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): start: Starting peer discovery...
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1047): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1047): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: 5 P2P devices discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 4: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: 5 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 4: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: 5 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 4: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3228): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service request added successfully
D/WifiP2pManager( 3228): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service request added successfully
D/WifiP2pManager( 3228): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service request added successfully
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 1047): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: 6 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 5: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: 6 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 5: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3228): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service request added successfully
,D/WifiP2pManager( 3228): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service request added successfully
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: 7 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 4: XT1039_8c05 f4:f1:e1:5c:43:c8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 6: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3228): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service request added successfully
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1047): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1047): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1047): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1047): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1047): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1047): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): stopServiceDiscovery
,I/wpa_supplicant( 1047): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Peer discovery stopped successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3228): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3228): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3228): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3228): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3228): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3228): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3228): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3228): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Start timer timeout, starting now...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): start: Starting peer discovery...
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 1047): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1047): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1047): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/WifiP2pManager( 3228): Ignored { when=-9ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service request added successfully
,D/WifiP2pManager( 3228): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service request added successfully
,D/WifiP2pManager( 3228): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service request added successfully
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1047): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: 5 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 3: Note3-1 ea:50:8b:de:28:a3
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: 5 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 3: Note3-1 ea:50:8b:de:28:a3
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/WifiP2pManager( 3228): Ignored { when=-10ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service request added successfully
D/WifiP2pManager( 3228): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service request added successfully
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 1047): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1047): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1047): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: 9 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 6: XT1039_8c05 f4:f1:e1:5c:43:c8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 7: Note3-1 ea:50:8b:de:28:a3
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 8: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: 9 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 6: XT1039_8c05 f4:f1:e1:5c:43:c8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 7: Note3-1 ea:50:8b:de:28:a3
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 8: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: 9 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 6: XT1039_8c05 f4:f1:e1:5c:43:c8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 7: Note3-1 ea:50:8b:de:28:a3
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 8: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: 9 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 6: XT1039_8c05 f4:f1:e1:5c:43:c8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 7: Note3-1 ea:50:8b:de:28:a3
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 8: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 3228): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service request added successfully
,D/WifiP2pManager( 3228): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service request added successfully
D/WifiP2pManager( 3228): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service request added successfully
D/WifiP2pManager( 3228): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service request added successfully
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1047): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1047): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1047): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT5056"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Resolved peer properties: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT5056 00:F4:6F:30:E0:6C]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerDiscovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceListChanged: 1 services discovered
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerListChanged
,I/io.jxcore.node.ConnectionHelper( 3228): onPeerDiscovered: Bluetooth address: 00:F4:6F:30:E0:6C, peer name: samsung-SM-G800F_PT5056, peer ID: 00:F4:6F:30:E0:6C, Wi-Fi Direct device name: S5mini-1, Wi-Fi Direct address: 02:f4:6f:30:e0:6d
,I/io.jxcore.node.ConnectionHelper( 3228): addNewPeerToListAndNotify: Peer with ID 00:F4:6F:30:E0:6C already in the list
,W/io.jxcore.node.ConnectionHelper( 3228): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT5056"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT5056"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT5056"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT5056"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT5056"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT5056"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT5056"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT5056"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1047): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceListChanged: Got empty list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1047): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1047): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1047): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1047): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceListChanged: Got empty list
,I/wpa_supplicant( 1047): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1047): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1047): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT5056"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Resolved peer properties: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT5056 00:F4:6F:30:E0:6C]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerListChanged
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT5056"}", service type: "Cordovap2p._tcp.local."
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT5056"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT5056"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT5056"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT5056"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT5056"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT5056"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT5056"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3228): onPeerDiscovered: Bluetooth address: 00:F4:6F:30:E0:6C, peer name: samsung-SM-G800F_PT5056, peer ID: 00:F4:6F:30:E0:6C, Wi-Fi Direct device name: S5mini-1, Wi-Fi Direct address: 02:f4:6f:30:e0:6d
,I/io.jxcore.node.ConnectionHelper( 3228): addNewPeerToListAndNotify: Peer with ID 00:F4:6F:30:E0:6C already in the list
W/io.jxcore.node.ConnectionHelper( 3228): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Identity: "{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT376"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Resolved peer properties: [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT376 F4:F1:E1:5C:3B:E2]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): onServiceListChanged: 2 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Identity: "{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT376"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Identity: "{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT376"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Identity: "{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT376"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Identity: "{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT376"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Identity: "{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT376"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Identity: "{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT376"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Identity: "{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT376"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Identity: "{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT376"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3228): onPeerDiscovered: Bluetooth address: F4:F1:E1:5C:3B:E2, peer name: motorola-XT1039_PT376, peer ID: F4:F1:E1:5C:3B:E2, Wi-Fi Direct device name: XT1039_8c05, Wi-Fi D,irect address: f4:f1:e1:5c:43:c8
I/io.jxcore.node.ConnectionHelper( 3228): addNewPeerToListAndNotify: Peer with ID F4:F1:E1:5C:3B:E2 already in the list
W/io.jxcore.node.ConnectionHelper( 3228): onPeerListChanged: Got a list containing 2 peer(s), but doing nothing with that list
,I/jxcore-log( 3228): DBG, CoordinatorConnector command called
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): command received : {"command":"timeout","testName":"","testData":"","devices":"","addressList":[]}
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): stop tests now !
I/jxcore-log( 3228): 
I/jxcore-log( 3228): stop current!
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): testSendData stopped
I/jxcore-log( 3228): 
I/io.jxcore.node.ConnectionHelper( 3228): stop
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3228): Shutting down...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): shutdown
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:489)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:399)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread.run(BluetoothServerThread.java:89)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3228): onIncomingConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): Socket is null
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3228): onIncomingConnectionFailed: Socket is null
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3228): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3228): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3228): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): stopServiceDiscovery
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): setState: NOT_INITIALIZED
I/jxcore-log( 3228): StopBroadcasting went ok
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): done, now sending data to server
I/jxcore-log( 3228): 
I/jxcore-log( 3228): DBG, CoordinatorConnector sendData called
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): -- RESULT DATA {"name:":"LGE-Nexus 5_PT6995","time":1199740,"result":"TIMEOUT","sendList":[{"name":"E0:DB:10:1F:C9:5E","time":12964,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"F8:CF:C5:D9:E5:61","time":10866,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:51:18:22","time":156809,"result":"OK","connections":5,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"connections":1,"name":"34:FC:EF:9D:93:0B","time":0,"result":"Fail"},{"connections":0,"name":"38:94:96:B5:06:DC","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:85:54","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:3C:51","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:75:41","time":0,"result":"Fail"},{"connections":0,"name":"80:01:84:8A:B3:68","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:76:27","time":0,"result":"Fail"},{"connections":
I/jxcore-log( 3228): sendList : 100% : 156809 ms, 99% : 156809 ms, 95 : 156809 ms, 90% : 156809 ms.
I/jxcore-log( 3228): 
I/jxcore-log( 3228): Result count 3, range 10866 ms to  156809 ms.
I/jxcore-log( 3228): 
I/jxcore-log( 3228): sendList failed peers count : 3 [50 %]
I/jxcore-log( 3228): 
I/jxcore-log( 3228): - Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
I/jxcore-log( 3228): 
I/jxcore-log( 3228): - Peer ID : 34:FC:EF:11:B1:66, Tried : 1
I/jxcore-log( 3228): 
I/jxcore-log( 3228): - Peer ID : 34:FC:EF:11:B1:66, Tried : 1
I/jxcore-log( 3228): 
I/jxcore-log( 3228): sendList never tried peers count : 34 [85 %]
I/jxcore-log( 3228): 
I/jxcore-log( 3228): - Peer ID : 38:94:96:B5:06:DC
I/jxcore-log( 3228): 
I/jxcore-log( 3228): - Peer ID : F8:95:C7:87:85:54
I/jxcore-log( 3228): 
I/jxcore-log( 3228): - Peer ID : F8:95:C7:87:3C:51
I/jxcore-log( 3228): 
I/jxcore-log( 3228): - Peer ID : 08:EC:A9:50:75:41
I/jxcore-log( 3228): 
I/jxcore-log( 3228): - Peer ID : 80:01:84:8A:B3:68
I/jxcore-log( 3228): 
I/jxcore-log( 3228): - Peer ID : 08:EC:A9:50:76:27
I/jxcore-log( 3228): 
I/jxcore-log( 3228): - Peer ID : 7C:F9:0E:37:96:AB
I/jxcore-log( 3228): 
I/jxcore-log( 3228): - Peer ID : 58:2A:F7:ED:96:BE
I/jxcore-log( 3228): 
I/jxcore-log( 3228): - Peer ID : 58:3F:54:73:64:C0
I/jxcore-log( 3228): 
I/jxcore-log( 3228): - Peer ID : 44:80:EB:7B:5A:05
I/jxcore-log( 3228): 
I/jxcore-log( 3228): - Peer ID : F4:F1:E1:5C:3B:E2
I/jxcore-log( 3228): 
I/jxcore-log( 3228): - Peer ID : B0:C5:59:3F:75:69
I/jxcore-log( 3228): 
I/jxcore-log( 3228): - Peer ID : B4:CE:F6:AB:A4:6A
I/jxcore-log( 3228): 
I/jxcore-log( 3228): - Peer ID : 90:E7:C4:F6:69:77
I/jxcore-log( 3228): 
I/jxcore-log( 3228): - Peer ID : E0:DB:10:14:E2:C0
I/jxcore-log( 3228): 
I/jxcore-log( 3228): - Peer ID : 00:F4:6F:30:E0:6C
I/jxcore-log( 3228): 
I/jxcore-log( 3228): - Peer ID : 7C:F9:0E:34:8A:A0
I/jxcore-log( 3228): 
I/jxcore-log( 3228): - Peer ID : 38:94:96:B5:06:DC
I/jxcore-log( 3228): 
I/jxcore-log( 3228): - Peer ID : F8:95:C7:87:85:54
I/jxcore-log( 3228): 
I/jxcore-log( 3228): - Peer ID : F8:95:C7:87:3C:51
I/jxcore-log( 3228): 
I/jxcore-log( 3228): - Peer ID : 08:EC:A9:50:75:41
I/jxcore-log( 3228): 
I/jxcore-log( 3228): - Peer ID : 80:01:84:8A:B3:68
I/jxcore-log( 3228): 
I/jxcore-log( 3228): - Peer ID : 08:EC:A9:50:76:27
I/jxcore-log( 3228): 
I/jxcore-log( 3228): - Peer ID : 7C:F9:0E:37:96:AB
I/jxcore-log( 3228): 
I/jxcore-log( 3228): - Peer ID : 58:2A:F7:ED:96:BE
I/jxcore-log( 3228): 
I/jxcore-log( 3228): - Peer ID : 58:3F:54:73:64:C0
I/jxcore-log( 3228): 
I/jxcore-log( 3228): - Peer ID : 44:80:EB:7B:5A:05
I/jxcore-log( 3228): 
I/jxcore-log( 3228): - Peer ID : F4:F1:E1:5C:3B:E2
I/jxcore-log( 3228): 
I/jxcore-log( 3228): - Peer ID : B0:C5:59:3F:75:69
I/jxcore-log( 3228): 
I/jxcore-log( 3228): - Peer ID : B4:CE:F6:AB:A4:6A
I/jxcore-log( 3228): 
I/jxcore-log( 3228): - Peer ID : 90:E7:C4:F6:69:77
I/jxcore-log( 3228): 
I/jxcore-log( 3228): - Peer ID : E0:DB:10:14:E2:C0
I/jxcore-log( 3228): 
I/j,xcore-log( 3228): - Peer ID : 00:F4:6F:30:E0:6C
I/jxcore-log( 3228): 
I/jxcore-log( 3228): - Peer ID : 7C:F9:0E:34:8A:A0
I/jxcore-log( 3228): 
I/jxcore-log( 3228): 2015-12-11T19:32:37.413Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
I/jxcore-log( 3228): 
I/chromium( 3228): [INFO:CONSOLE(63)] "logCallback stop-by-timeout", source: file:///android_asset/www/js/thali_main.js (63)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3228): onConnectionFailed: Socket is null
I/io.jxcore.node.ConnectionHelper( 3228): onConnectionManagerStateChanged: INITIALIZED
I/io.jxcore.node.ConnectionHelper( 3228): onConnectionManagerStateChanged: NOT_INITIALIZED
,I/chromium( 3228): [INFO:CONSOLE(63)] "logCallback ---- sendReportNow", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3228): [INFO:CONSOLE(63)] "logCallback ---- finished : send-data -- ", source: file:///android_asset/www/js/thali_main.js (63)
,I/wpa_supplicant( 1047): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 1047): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3228): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3228): Peer discovery stopped successfully
,I/jxcore-log( 3228): DBG, CoordinatorConnector command called
I/jxcore-log( 3228): 
I/jxcore-log( 3228): command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): stop tests now !
I/jxcore-log( 3228): 
,I/chromium( 3228): [INFO:CONSOLE(63)] "logCallback stop", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3228): DBG, CoordinatorConnector command called
I/jxcore-log( 3228): 
I/jxcore-log( 3228): command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"F8:CF:C5:D9:E5:61\",\"time\":10866,\"result\":\"OK\",\"connections\":1,\"tryCount\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},{\"name\":\"E0:DB:10:1F:C9:5E\",\"time\":12964,\"result\":\"OK\",\"connections\":1,\"tryCount\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},{\"name\":\"7C:F9:0E:51:18:22\",\"time\":156809,\"result\":\"OK\",\"connections\":5,\"tryCount\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000}],\"sendError\":{\"failedPeer\":[{\"connections\":1,\"name\":\"34:FC:EF:9D:93:0B\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"34:FC:EF:11:B1:66\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"34:FC:EF:11:B1:66\",\"time\":0,\"result\":\"Fail\"}],\"notTriedList\":[{\"connections\":0,\"name\":\"38:94:96:B5:06:DC\",\"time\":0,\"result\":\"Fail\"},{\"connections\":0,\"name\":\"F8:95:C7:87:85:54\",\"time\":0,
I/jxcore-log( 3228): ****TEST TOOK:  ms ****
I/jxcore-log( 3228): 
I/jxcore-log( 3228): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3228): 
I/jxcore-log( 3228): stop tests now !
I/jxcore-log( 3228): 
I/jxcore-log( 3228): end, event received
I/jxcore-log( 3228): 
,I/jxcore-log( 3228): CoordinatorConnector close called
I/jxcore-log( 3228): 
I/jxcore-log( 3228): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 3228): 
I/jxcore-log( 3228): The Coordinator has disconnected!
I/jxcore-log( 3228): 
I/jxcore-log( 3228): The Coordinator has closed!
I/jxcore-log( 3228): 
I/jxcore-log( 3228): stop tests now !
I/jxcore-log( 3228): 
I/jxcore-log( 3228): turning Radios off
I/jxcore-log( 3228): 
I/jxcore-log( 3228): Toggling radios to false
I/jxcore-log( 3228): 
D/BluetoothManagerService(  757): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  757): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@30842cca mBinding = false
,D/BluetoothManagerService(  757): Message: 2
,D/BluetoothManagerService(  757): Sending off request.
,D/BluetoothAdapterState( 2106): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 2106): Setting state to 13
I/BluetoothAdapterState( 2106): Bluetooth adapter state changed: 12-> 13
,D/BluetoothAdapterProperties( 2106): onBluetoothDisable()
I/BluetoothAdapterState( 2106): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,D/BluetoothAdapterProperties( 2106): Scan Mode:20
,D/BluetoothAdapterState( 2106): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,V/BluetoothMapMasInstance( 2106): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 2106): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 2106): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
V/BluetoothMapMasInstance( 2106): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:489)
V/BluetoothMapMasInstance( 2106): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:399)
V/BluetoothMapMasInstance( 2106): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 2106): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 2106): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,E/BtOppRfcommListener( 2106): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,D/btif_config_util( 2106): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 2106): bta_dm_disable BTA_DISABLE_DELAY set to 100 ms
,W/bt-l2cap( 2106): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2106): L2CAP - PSM: 0x0017 not found for deregistration
,D/BluetoothManagerService(  757): Message: 60
D/BluetoothManagerService(  757): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService(  757): Bluetooth State Change Intent: 12 -> 13
,D/BluetoothMapService( 2106): onReceive
D/BluetoothMapService( 2106): STATE_TURNING_OFF
V/BluetoothMapService( 2106): Handler(): got msg=4
D/BluetoothMapService( 2106): MAP Service closeService in
D/BluetoothMapMasInstance( 2106): MAP Service shutdown
,V/BluetoothMapService( 2106): MAP Service closeService out
,I/BtOppRfcommListener( 2106): stopping Accept Thread
,I/BtOppRfcommListener( 2106): BluetoothSocket listen thread finished
,D/WifiService(  757): setWifiEnabled: false pid=3228, uid=10270
E/WifiService(  757): Invoking mWifiStateMachine.setWifiEnabled
,W/ContextImpl( 2727): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/DockEventReceiver( 2727): finishStartingService: stopping service
,D/AuthorizationBluetoothService( 1571): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothPbap( 2727): Proxy object disconnected
D/PbapServerProfile( 2727): Bluetooth service disconnected
,E/WifiStateMachine(  757): WifiStateMachine: Leaving Connected state
,E/WifiConfigStore(  757): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
I/jxcore-log( 3228): Radios toggled
I/jxcore-log( 3228): 
,I/chromium( 3228): [INFO:CONSOLE(63)] "logCallback fully-closed", source: file:///android_asset/www/js/thali_main.js (63)
E/native  (  757): do suspend true
,D/bt_userial( 2106): RX termination
,W/bt-btif ( 2106): ag scb idx 1 not allocated
E/bt-btif ( 2106): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 2106): L2CAP - PSM: 0x0019 not found for deregistration
,W/bt-l2cap( 2106): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2106): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2106): L2CAP - PSM: 0x0017 not found for deregistration
,W/bt-l2cap( 2106): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2106): L2CAP - PSM: 0x0017 not found for deregistration
W/bt_userial( 2106): select_read return size <=0:-1, exiting userial_read_thread
D/bt_userial( 2106): Leaving userial_read_thread()
D/bt_userial( 2106): userial_close_reader Joined userial reader thread: 0
,D/bt_hwcfg( 2106): hw_epilog_process
I/bt_userial_vendor( 2106): device fd = 53 close
,I/GKI_LINUX( 2106): gki_task task_id=0 [BTU] terminating
,I/GKI_LINUX( 2106): GKI_exit_task 0 done
I/GKI_LINUX( 2106): GKI_shutdown(): task [BTU] terminated
,D/BluetoothAdapterState( 2106): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,D/HeadsetService( 2106): Received stop request...Stopping profile...
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,D/BluetoothAdapterService( 2106): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1869085a
,D/HeadsetStateMachine( 2106): Exit Disconnected: -1
,D/BluetoothHeadset( 2727): Proxy object disconnected
,D/HeadsetProfile( 2727): Bluetooth service disconnected
D/BluetoothHeadset( 1157): Proxy object disconnected
D/BluetoothHeadset( 1157): Proxy object disconnected
,D/BluetoothHeadset(  757): Proxy object disconnected
D/BluetoothHeadset( 1201): Proxy object disconnected
,D/A2dpService( 2106): Received stop request...Stopping profile...
,D/BluetoothAdapterState( 2106): Stopping profile services that were post enabled
,D/A2dpStateMachine( 2106): Exit Disconnected: -1
D/BluetoothAdapterService( 2106): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1869085a
,D/BluetoothA2dp( 2727): Proxy object disconnected
D/A2dpProfile( 2727): Bluetooth service disconnected
,D/BluetoothA2dp(  757): Proxy object disconnected
,D/HidService( 2106): Received stop request...Stopping profile...
,D/BluetoothAdapterService( 2106): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1869085a
,D/HealthService( 2106): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2106): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1869085a
D/BluetoothInputDevice( 2727): Proxy object disconnected
D/HidProfile( 2727): Bluetooth service disconnected
,D/PanService( 2106): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2106): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1869085a
,D/BtGatt.DebugUtils( 2106): handleDebugAction() action=null
,D/BtGatt.GattService( 2106): Received stop request...Stopping profile...
D/BtGatt.GattService( 2106): stop()
D/BtGatt.AdvertiseManager( 2106): advertise clients cleared
,D/BluetoothPan( 2727): BluetoothPAN Proxy object disconnected
D/PanProfile( 2727): Bluetooth service disconnected
,D/BluetoothAdapterService( 2106): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1869085a
,D/HeadsetStateMachine( 2106): Unbinding service...
,W/BluetoothHeadsetServiceJni( 2106): Cleaning up Bluetooth Handsfree Interface...
,W/BluetoothHeadsetServiceJni( 2106): Cleaning up Bluetooth Handsfree callback object
,D/BluetoothMapService( 2106): Received stop request...Stopping profile...
D/BluetoothMapService( 2106): stop()
,D/BluetoothMapEmailAppObserver( 2106): deinitObservers()
D/BluetoothMapEmailAppObserver( 2106): removeReceiver()
,D/BluetoothAdapterService( 2106): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1869085a
,D/BluetoothMap( 2727): Proxy object disconnected
D/MapProfile( 2727): Bluetooth service disconnected
I/GKI_LINUX( 2106): gki_task task_id=2 [A2DP-MEDIA] terminating
,I/GKI_LINUX( 2106): GKI_exit_task 2 done
I/GKI_LINUX( 2106): GKI_shutdown(): task [A2DP-MEDIA] terminated
,W/BluetoothHidServiceJni( 2106): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 2106): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 2106): Cleaning up Bluetooth GID callback object
W/BluetoothHealthServiceJni( 2106): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 2106): Cleaning up Bluetooth Health object
,W/BluetoothPanServiceJni( 2106): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 2106): Cleaning up Bluetooth PAN callback object
,V/BluetoothMapService( 2106): Handler(): got msg=4
D/BluetoothMapService( 2106): MAP Service closeService in
,V/BluetoothMapService( 2106): MAP Service closeService out
D/BluetoothAdapterState( 2106): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 2106): Setting state to 10
I/BluetoothAdapterState( 2106): Bluetooth adapter state changed: 13-> 10
,D/BluetoothManagerService(  757): Message: 60
D/BluetoothManagerService(  757): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService(  757): Broadcasting onBluetoothStateChange(false) to 11 receivers.
,I/BluetoothAdapterState( 2106): Entering OffState
D/BluetoothMapService( 2106): cleanup()
D/BluetoothMapService( 2106): MAP Service closeService in
V/BluetoothMapService( 2106): MAP Service closeService out
V/NativeCrypto( 1571): Read error: ssl=0xb3d28e00: I/O error during system call, Connection timed out
,D/BluetoothInputDevice( 2727): onBluetoothStateChange: up=false
,V/NativeCrypto( 1571): SSL shutdown failed: ssl=0xb3d28e00: I/O error during system call, Broken pipe
,D/ConnectivityService(  757): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  757): NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
E/WifiConfigStore(  757): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiStateMachine(  757): scanCount==0 - aborting
D/ConnectivityService(  757): reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10008
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): ValidatedState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): DefaultState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): Checking http://clients3.google.com/generate_204 on <unknown ssid>
D/WifiNetworkAgent(  757): NetworkAgent: NetworkAgent channel lost
D/WifiScanningService(  757): SCAN_AVAILABLE : 1
D/RttService(  757): SCAN_AVAILABLE : 1
D/WifiScanningService(  757): StartedState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  757): DefaultState
D/RttService(  757): EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,E/native  (  757): do suspend true
,D/BluetoothHeadset( 1157): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1201): onBluetoothStateChange: up=false
,D/BluetoothA2dp( 2727): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1157): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 2727): onBluetoothStateChange: up=false
,D/BluetoothMap( 2727): onBluetoothStateChange: up=false
,D/BluetoothA2dp(  757): onBluetoothStateChange: up=false
D/BluetoothHeadset(  757): onBluetoothStateChange: up=false
D/BluetoothPbap( 2727): onBluetoothStateChange: up=false
,D/BluetoothManagerService(  757): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService(  757): Broadcasting onBluetoothServiceDown() to 10 receivers.
,D/BluetoothManagerService(  757): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@30842cca mBinding = false
,D/BluetoothManagerService(  757): Sending unbind request.
D/CommandListener(  179): Clearing all IP addresses on wlan0
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/ConnectivityService(  757): notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,D/BluetoothManagerService(  757): Bluetooth State Change Intent: 13 -> 10
D/Nat464Xlat(  757): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  757): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  757): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler(  899): CM callback handler got msg 524292
,D/ConnectivityService(  757): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): Disconnected - quitting
D/ConnectivityService(  757): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1201): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/AndroidRuntime( 3866): 
D/AndroidRuntime( 3866): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,E/ConnectivityService(  757): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,D/BluetoothAdapter(  899): 1067605631: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter(  899): 1067605631: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter(  899): 1067605631: getState() :  mService = null. Returning STATE_OFF
,D/AndroidRuntime( 3866): CheckJNI is OFF
,D/ConnectivityManager.CallbackHandler( 1597): CM callback handler got msg 524292
,I/GKI_LINUX( 2106): gki_task task_id=1 [BTIF] terminating
,I/GKI_LINUX( 2106): GKI_exit_task 1 done
I/GKI_LINUX( 2106): GKI_shutdown(): task [BTIF] terminated
I/BluetoothServiceJni( 2106): cleanupNative: return from cleanup
W/ContextImpl( 2727): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/BluetoothAdapter( 1571): 217027818: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1571): 217027818: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1571): 217027818: getState() :  mService = null. Returning STATE_OFF
E/BluetoothDevice( 1571): BT not enabled. Cannot get Bluetooth Class
E/BluetoothDevice( 1571): BT not enabled. Cannot get Remote Device name
E/BluetoothDevice( 1571): BT not enabled. Cannot get Remote Device Alias
E/BluetoothDevice( 1571): BT not enabled. Cannot get Bluetooth Class
E/BluetoothDevice( 1571): BT not enabled. Cannot get Bluetooth Class
E/BluetoothDevice( 1571): BT not enabled. Cannot get Remote Device name
E/BluetoothDevice( 1571): BT not enabled. Cannot get Remote Device Alias
,D/DockEventReceiver( 2727): finishStartingService: stopping service
,I/art     ( 2106): System.exit called, status: 0
I/AndroidRuntime( 2106): VM exiting with result code 0, cleanup skipped.
,I/ActivityManager(  757): Process com.android.bluetooth (pid 2106) has died
,D/AndroidRuntime( 3866): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  757): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  757): Killing 3228:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
,I/wpa_supplicant( 1047): p2p0: CTRL-EVENT-TERMINATING 
,I/wpa_supplicant( 1047): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,W/PackageSettings(  757): Skipping PackageSetting{3e50449 com.example.hello/10277} due to missing metadata
,I/WindowState(  757): WIN DEATH: Window{1928cc89 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  757): Client connection lost with reason: 4
,D/Tethering(  757): InitialState.processMessage what=4
,I/wpa_supplicant( 1047): wlan0: CTRL-EVENT-TERMINATING 
,I/ActivityManager(  757):   Force finishing activity ActivityRecord{3abab83a u0 com.test.thalitest/.MainActivity t214}
,W/ActivityManager(  757): Spurious death for ProcessRecord{197f5304 3228:com.test.thalitest/u0a270}, curProc for 3228: null
,I/ActivityManager(  757): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
,I/ActivityManager(  757):   Force finishing activity ActivityRecord{3abab83a u0 com.test.thalitest/.MainActivity t214 f}
W/ActivityManager(  757): Duplicate finish request for ActivityRecord{3abab83a u0 com.test.thalitest/.MainActivity t214 f}
,D/Tethering(  757): sendTetherStateChangedBroadcast 0, 0, 0
,I/art     ( 1252): Explicit concurrent mark sweep GC freed 3942(293KB) AllocSpace objects, 1(126KB) LOS objects, 38% free, 25MB/41MB, paused 236us total 19.520ms
,I/InputReader(  757): Reconfiguring input devices.  changes=0x00000010
,I/Keyboard.Facilitator( 1065): resetDictionaries() : en_US
,W/GeofencerStateMachine( 1571): Ignoring removeGeofence because network location is disabled.
,I/Adreno-EGL(  946): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothAdapter( 2727): 296898476: getState() :  mService = null. Returning STATE_OFF
I/OpenGLRenderer(  946): Initialized EGL, version 1.4
,D/OpenGLRenderer(  946): Enabling debug mode 0
,I/ActivityManager(  757): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=3920 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
W/Settings( 1891): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings( 1571): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Keyboard.Facilitator.DecoderInitializer( 1065): run()
,I/art     (  757): Explicit concurrent mark sweep GC freed 55168(2MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 28MB/42MB, paused 2.196ms total 107.040ms
I/art     (  757): WaitForGcToComplete blocked for 105.300ms for cause Explicit
,I/art     ( 1380): Explicit concurrent mark sweep GC freed 71967(3MB) AllocSpace objects, 14(224KB) LOS objects, 24% free, 19MB/25MB, paused 323us total 132.483ms
,I/Decoder ( 1065): createOrResetDecoder
,W/InputMethodManagerService(  757): Got RemoteException sending setActive(false) notification to pid 3228 uid 10270
,I/Keyboard.Facilitator( 1065): onFinishInput()
,I/ConfigService( 1571): onCreate
,I/art     ( 1597): Explicit concurrent mark sweep GC freed 35676(2MB) AllocSpace objects, 9(144KB) LOS objects, 25% free, 22MB/30MB, paused 587us total 129.306ms
,W/ResourcesManager( 3920): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,D/BackupManagerService(  757): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService(  757): Receieved: android.intent.action.PACKAGE_REMOVED
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1065): run()
,D/TaskPersister(  757): removeObsoleteFile: deleting file=214_task.xml
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1065): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1065): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1065): run() : Loading LM = contacts
,I/Keyboard.Facilitator( 1065): onFinishInput()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1065): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1065): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1065): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1065): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1065): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1065): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1065): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1065): run()
I/StatsUtilsManager( 1065): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1065): shouldRecordStats() = Too Soon
,D/AdapterServiceConfig( 3920): Adding HeadsetService
,D/AdapterServiceConfig( 3920): Adding A2dpService
D/AdapterServiceConfig( 3920): Adding HidService
,D/AdapterServiceConfig( 3920): Adding HealthService
D/AdapterServiceConfig( 3920): Adding PanService
D/AdapterServiceConfig( 3920): Adding GattService
D/AdapterServiceConfig( 3920): Adding BluetoothMapService
W/IInputConnectionWrapper( 1252): showStatusIcon on inactive InputConnection
I/Launcher( 1252): Deferring update until onResume
,I/ActivityManager(  757): Killing 2009:com.google.android.calendar/u0a31 (adj 15): empty #17
,I/art     (  757): Explicit concurrent mark sweep GC freed 7025(374KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 28MB/42MB, paused 1.447ms total 142.302ms
,W/ResourcesManager( 1252): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 1252): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Launcher( 1252): Deferring update until onResume
,D/AndroidRuntime( 3866): Shutting down VM
,D/AuthorizationBluetoothService( 1571): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,W/libprocessgroup(  757): failed to open /acct/uid_10031/pid_2009/cgroup.procs: No such file or directory
,D/BluetoothAdapter( 2727): 296898476: getState() :  mService = null. Returning STATE_OFF
,I/ActivityManager(  757): Start proc com.google.android.keep for broadcast com.google.android.keep/.notification.AlertReceiver: pid=3950 uid=10071 gids={50071, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SQLiteLog( 1344): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,--------- beginning of crash
E/AndroidRuntime( 1344): FATAL EXCEPTION: ContactsProviderWorker
E/AndroidRuntime( 1344): Process: android.process.acore, PID: 1344
E/AndroidRuntime( 1344): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1344): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 1344): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AndroidRuntime( 1344): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 1344): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 1344): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AndroidRuntime( 1344): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/AndroidRuntime( 1344): 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:381)
E/AndroidRuntime( 1344): 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:350)
E/AndroidRuntime( 1344): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1706)
E/AndroidRuntime( 1344): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1492)
E/AndroidRuntime( 1344): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1344): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 1344): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/VoicemailCleanupService( 1344): Cleaning up data for package: com.test.thalitest
,I/ActivityManager(  757): Killing 3007:com.google.android.gms:car/u0a8 (adj 15): empty #17
,E/DropBoxManagerService(  757): Can't write: system_app_crash
E/DropBoxManagerService(  757): java.io.FileNotFoundException: /data/system/dropbox/drop99.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  757): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  757): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  757): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  757): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  757): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  757): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12006)
E/DropBoxManagerService(  757): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  757): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  757): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  757): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  757): 	... 5 more
,I/Process ( 1344): Sending signal. PID: 1344 SIG: 9
,I/UpdateIcingCorporaServi( 1380): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,E/SQLiteLog( 1380): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/AndroidRuntime( 1380): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 1380): Process: com.google.android.googlequicksearchbox:search, PID: 1380
E/AndroidRuntime( 1380): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1380): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 1380): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AndroidRuntime( 1380): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 1380): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 1380): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AndroidRuntime( 1380): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/AndroidRuntime( 1380): 	at csx.d(PG:186)
E/AndroidRuntime( 1380): 	at cun.g(PG:594)
E/AndroidRuntime( 1380): 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 1380): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:325)
E/AndroidRuntime( 1380): 	at android.content.ContentResolver.update(ContentResolver.java:1333)
E/AndroidRuntime( 1380): 	at cuw.Tg(PG:368)
E/AndroidRuntime( 1380): 	at cuy.ub(PG:301)
E/AndroidRuntime( 1380): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(PG:268)
E/AndroidRuntime( 1380): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(PG:186)
E/AndroidRuntime( 1380): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 1380): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1380): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 1380): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/libprocessgroup(  757): failed to open /acct/uid_10008/pid_3007/cgroup.procs: No such file or directory
W/Launcher( 1252): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@1869085a new=com.google.android.velvet.VelvetApplication@1869085a
E/DropBoxManagerService(  757): Can't write: system_app_crash
E/DropBoxManagerService(  757): java.io.FileNotFoundException: /data/system/dropbox/drop100.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  757): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  757): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  757): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  757): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  757): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  757): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12006)
E/DropBoxManagerService(  757): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  757): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  757): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  757): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  757): 	... 5 more
E/SQLiteLog( 1252): (3850) statement aborts at 24: [DELETE FROM shortcut_and_widget_previews WHERE name LIKE ? OR name LIKE ?] disk I/O error
I/ActivityManager(  757): Process android.process.acore (pid 1344) has died
W/ActivityManager(  757): Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
I/ActivityManager(  757): Killing 1065:com.google.android.inputmethod.latin/u0a56 (adj 2): depends on provider com.android.providers.userdictionary/.UserDictionaryProvider in dying proc android.process.acore
,W/InputMethodManagerService(  757): Session failed to close due to remote exception
W/InputMethodManagerService(  757): android.os.DeadObjectException
W/InputMethodManagerService(  757): 	at android.os.BinderProxy.transactNative(Native Method)
W/InputMethodManagerService(  757): 	at android.os.BinderProxy.transact(Binder.java:496)
W/InputMethodManagerService(  757): 	at com.android.internal.view.IInputMethodSession$Stub$Proxy.finishSession(IInputMethodSession.java:305)
W/InputMethodManagerService(  757): 	at com.android.server.InputMethodManagerService.finishSessionLocked(InputMethodManagerService.java:1415)
W/InputMethodManagerService(  757): 	at com.android.server.InputMethodManagerService.clearClientSessionLocked(InputMethodManagerService.java:1406)
W/InputMethodManagerService(  757): 	at com.android.server.InputMethodManagerService.clearCurMethodLocked(InputMethodManagerService.java:1432)
W/InputMethodManagerService(  757): 	at com.android.server.InputMethodManagerService.onServiceDisconnected(InputMethodManagerService.java:1451)
W/InputMethodManagerService(  757): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1208)
W/InputMethodManagerService(  757): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1222)
W/InputMethodManagerService(  757): 	at android.os.Handler.handleCallback(Handler.java:739)
W/InputMethodManagerService(  757): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/InputMethodManagerService(  757): 	at android.os.Looper.loop(Looper.java:135)
W/InputMethodManagerService(  757): 	at com.android.server.SystemServer.run(SystemServer.java:269)
W/InputMethodManagerService(  757): 	at com.android.server.SystemServer.main(SystemServer.java:170)
W/InputMethodManagerService(  757): 	at java.lang.reflect.Method.invoke(Native Method)
W/InputMethodManagerService(  757): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/InputMethodManagerService(  757): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
W/InputMethodManagerService(  757): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
W/InputMethodManagerService(  757): Session failed to close due to remote exception
W/InputMethodManagerService(  757): android.os.DeadObjectException
W/InputMethodManagerService(  757): 	at android.os.BinderProxy.transactNative(Native Method)
W/InputMethodManagerService(  757): 	at android.os.BinderProxy.transact(Binder.java:496)
W/InputMethodManagerService(  757): 	at com.android.internal.view.IInputMethodSession$Stub$Proxy.finishSession(IInputMethodSession.java:305)
W/InputMethodManagerService(  757): 	at com.android.server.InputMethodManagerService.finishSessionLocked(InputMethodManagerService.java:1415)
W/InputMethodManagerService(  757): 	at com.android.server.InputMethodManagerService.clearClientSessionLocked(InputMethodManagerService.java:1406)
W/InputMethodManagerService(  757): 	at com.android.server.InputMethodManagerService.clearCurMethodLocked(InputMethodManagerService.java:1432)
W/InputMethodManagerService(  757): 	at com.android.server.InputMethodManagerService.onServiceDisconnected(InputMethodManagerService.java:1451)
W/InputMethodManagerService(  757): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1208)
W/InputMethodManagerService(  757): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1222)
W/InputMethodManagerService(  757): 	at android.os.Handler.handleCallback(Handler.java:739)
W/InputMethodManagerService(  757): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/InputMethodManagerService(  757): 	at android.os.Looper.loop(Looper.java:135)
W/InputMethodManagerService(  757): 	at com.android.server.SystemServer.run(SystemServer.java:269)
W/InputMethodManagerService(  757): 	at com.android.server.SystemServer.main(SystemServer.java:170)
W/InputMethodManagerService(  757): 	at java.lang.reflect.Method.invoke(Native Method)
W/InputMethodManagerService(  757): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/I,nputMethodManagerService(  757): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
W/InputMethodManagerService(  757): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)

```
