#### Test 50650278923ff9f_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
D/ChimeraCfgMgr( 1602): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1602): Module APK com.google.android.play.games already loaded
I/GAv4    ( 3230): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3230):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3230):   adb logcat -s GAv4
W/GAv4    ( 3230): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3230): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3230): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 3230): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
D/Finsky  ( 2614): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
W/ResourcesManager( 3230): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3230): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  759): Killing 2535:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
V/JNIHelp ( 3230): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/libprocessgroup(  759): failed to open /acct/uid_10045/pid_2535/cgroup.procs: No such file or directory
W/System  ( 3230): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3230): Installed default security provider GmsCore_OpenSSL
V/GLSActivity( 1567): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 1602): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/Icing   ( 1602): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/Icing   ( 1602): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1602): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
,D/AndroidRuntime( 3289): 
D/AndroidRuntime( 3289): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3289): CheckJNI is OFF
D/AndroidRuntime( 3289): Calling main entry com.android.commands.am.Am
I/ActivityManager(  759): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  759): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3309 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3289): Shutting down VM
V/ActivityManager(  759): Display changed displayId=0
I/WebViewFactory( 3309): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3309): Time to load native libraries: 2 ms (timestamps 8918-8920)
I/LibraryLoader( 3309): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3309): Binding Chromium to main looper Looper (main, tid 1) {672f617}
I/LibraryLoader( 3309): Expected native library version number "",actual native library version number ""
I/chromium( 3309): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3309): Initializing chromium process, singleProcess=true
W/art     ( 3309): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3309): ApplicationContext is null in ApplicationStatus
W/chromium( 3309): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3309): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3309): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3309): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  759): Message: 20
,D/BluetoothManagerService(  759): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3d5bb326:true
,W/art     ( 3309): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3309): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3309): CordovaWebView is running on device made by: LGE
,W/art     ( 3309): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3309): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3309): Render dirty regions requested: true
,D/Atlas   ( 3309): Validating map...
,W/chromium( 3309): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3309): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3309): Enabling debug mode 0
,I/Keyboard.Facilitator( 1086): onFinishInput()
,W/IInputConnectionWrapper( 3309): showStatusIcon on inactive InputConnection
,I/ActivityManager(  759): Displayed com.test.thalitest/.MainActivity: +424ms (total +57s392ms)
,I/ActivityManager(  759): Killing 2703:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/BindingManager( 3309): Cannot call determinedVisibility() - never saw a connection for the pid: 3309
,W/libprocessgroup(  759): failed to open /acct/uid_10003/pid_2703/cgroup.procs: No such file or directory
,D/JsMessageQueue( 3309): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3309): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257342720
D/JX-Cordova( 3309): jxcore cordova android initializing
,W/jxcore-log( 3309): Initializing JXcore engine
W/jxcore-log( 3309): JXcore engine is ready
,W/jxcore-log( 3309): Starting JXcore engine
,W/.test.thalitest( 3309): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[8346]" dev="sockfs" ino=8346 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3309): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 3309): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6596]" dev="sockfs" ino=6596 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3309): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[19828]" dev="sockfs" ino=19828 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3309): Platform android
W/jxcore-log( 3309): 
W/jxcore-log( 3309): Process ARCH arm
W/jxcore-log( 3309): 
,I/jxcore-log( 3309): JXcore Cordova bridge is ready!
I/jxcore-log( 3309): 
,W/jxcore-log( 3309): JXcore engine is started
I/Choreographer( 3309): Skipped 107 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3309): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3309): Toggling radios to true
I/jxcore-log( 3309): 
D/BluetoothAdapter( 3309): enable(): BT is already enabled..!
,D/WifiService(  759): New client listening to asynchronous messages
D/WifiService(  759): setWifiEnabled: true pid=3309, uid=10270
E/WifiService(  759): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3309): Radios toggled
I/jxcore-log( 3309): 
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 3309): Got Device Bluetooth address: 34:FC:EF:11:AE:67
I/jxcore-log( 3309): 
I/wpa_supplicant( 1023): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,I/jxcore-log( 3309): Perf Test app loaded loaded
I/jxcore-log( 3309): 
E/WifiStateMachine(  759): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  759): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/native  (  759): do suspend true
,D/CommandListener(  180): Clearing all IP addresses on wlan0
,I/jxcore-log( 3309): check test folder
I/jxcore-log( 3309): 
I/jxcore-log( 3309): found test : ./testFindPeers.js
I/jxcore-log( 3309): 
,I/jxcore-log( 3309): found test : ./testSendData.js
I/jxcore-log( 3309): 
V/NativeCrypto( 1567): Read error: ssl=0x9b401e00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1567): SSL shutdown failed: ssl=0x9b401e00: I/O error during system call, Broken pipe
,D/ConnectivityService(  759): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  759): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,E/WifiConfigStore(  759): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiStateMachine(  759): Start Disconnecting Watchdog 1
,D/ConnectivityService(  759): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
I/wpa_supplicant( 1023): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): ValidatedState{ when=-1ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): DefaultState{ when=-1ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Checking http://clients3.google.com/generate_204 on <unknown ssid>
E/native  (  759): do suspend true
,D/ConnectivityService(  759): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/Nat464Xlat(  759): requiresClat: netType=1, connected=false, hasIPv4Address=true
,D/CSLegacyTypeTracker(  759): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  759): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler(  895): CM callback handler got msg 524292
,D/ConnectivityManager.CallbackHandler( 1602): CM callback handler got msg 524292
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): EvaluatingState{ when=-7ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): DefaultState{ when=-7ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Disconnected - quitting
,D/CommandListener(  180): Clearing all IP addresses on wlan0
,D/ConnectivityService(  759): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  759): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/ConnectivityService(  759): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,D/TelephonyNetworkFactory( 1226): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WifiNetworkAgent(  759): NetworkAgent: NetworkAgent channel lost
,I/Choreographer( 3309): Skipped 68 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3309): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/wpa_supplicant( 1023): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant( 1023): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1023): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1023): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  759): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService(  759): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiConfigStore(  759): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  759): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  180): Setting iface cfg
E/WifiStateMachine(  759): Start Dhcp Watchdog 2
,E/native  (  759): do suspend false
,E/WifiStateMachine(  759): scanCount==0 - aborting
,I/dhcpcd  ( 3400): version 5.5.6 starting
,E/dhcpcd  ( 3400): get_duid: Read-only file system
,I/dhcpcd  ( 3400): wlan0: rebinding lease of 192.168.1.114
,D/ConnectivityService(  759): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  759): MasterInitialState.processMessage what=3
,D/ConnectivityService(  759): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  759): MasterInitialState.processMessage what=3
,V/MusicLeanback( 2735): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1602): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1602): onCreate
,D/SystemUpdateService( 1602): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.Environment( 1602): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1602): num queued entries: 0
,I/iu.UploadsManager( 1602): num updated entries: 0
I/iu.SyncManager( 1602): NEXT; no task
,I/SystemUpdateService( 1602): active receiver: enabled
I/Babel   ( 1897): connection state changed from CONNECTED to DISCONNECTED
,I/SystemUpdateService( 1602): showing system update notification
,I/ActivityManager(  759): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3428 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/GpsLocationProvider(  759): No APN found to select.
,I/ValidateNoPeople(  759): skipping global notification
,E/GpsLocationProvider(  759): No APN found to select.
,V/SystemUpdateService( 1602): retry (wakeup: false) in 3599957 ms
,D/SystemUpdateService( 1602): onDestroy
,I/dhcpcd  ( 3400): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3400): wlan0: leased 192.168.1.114 for 86400 seconds
,I/GAv4    ( 3428): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3428):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3428):   adb logcat -s GAv4
,W/GAv4    ( 3428): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3428): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3428): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,E/native  (  759): do suspend true
,I/WebViewFactory( 3428): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,E/WifiStateMachine(  759): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/ConnectivityService(  759): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService(  759): Adding iface wlan0 to network 101
,E/ConnectivityService(  759): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  759): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  759): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/ConnectivityService(  759): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  759): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  759): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  759): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  759): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  759): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  759):    accepting network in place of null
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/CSLegacyTypeTracker(  759): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  759): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  759): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::5255:27ff:fef0:fd0b/64,192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  759): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  895): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1602): CM callback handler got msg 524290
,I/LibraryLoader( 3428): Time to load native libraries: 2 ms (timestamps 5881-5883)
,I/LibraryLoader( 3428): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3428): Binding Chromium to main looper Looper (main, tid 1) {134e60fb}
,I/LibraryLoader( 3428): Expected native library version number "",actual native library version number ""
I/chromium( 3428): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3428): Initializing chromium process, singleProcess=true
,W/art     ( 3428): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3428): ApplicationContext is null in ApplicationStatus
,W/chromium( 3428): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3428): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3428): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3428): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 16 Dec 2015 15:45:21 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450280721785], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450280721763]}
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Validated
D/ConnectivityService(  759): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  759): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  759): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  759): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler(  895): CM callback handler got msg 524290
D/ConnectivityManager.CallbackHandler( 1602): CM callback handler got msg 524290
D/ConnectivityService(  759): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/TelephonyNetworkFactory( 1226): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,W/AudioManagerAndroid( 3428): Requires BLUETOOTH permission
I/NSApplication( 3428): Starting up...
,I/ActivityManager(  759): Killing 2672:com.android.settings/1000 (adj 15): empty #17
,D/WifiService(  759): Client connection lost with reason: 4
,W/libprocessgroup(  759): failed to open /acct/uid_1000/pid_2672/cgroup.procs: No such file or directory
,V/MusicLeanback( 2735): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1602): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1602): onCreate
,D/SystemUpdateService( 1602): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1602): active receiver: enabled
,I/SystemUpdateService( 1602): showing system update notification
,I/iu.Environment( 1602): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1602): num queued entries: 0
I/iu.UploadsManager( 1602): num updated entries: 0
,I/iu.SyncManager( 1602): NEXT; no task
,I/ValidateNoPeople(  759): skipping global notification
,V/SystemUpdateService( 1602): retry (wakeup: false) in 3599984 ms
,D/SystemUpdateService( 1602): onDestroy
,I/Babel   ( 1897): connection state changed from DISCONNECTED to CONNECTED
,D/ConnectivityService(  759): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/jxcore-log( 3309): BLE advertisement not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 3309): 
,W/NetworkUtils( 1317): OkHttp exception
,W/EventLoggerService( 1317): Unable to send logs Error code: 262146
,D/ConnectivityService(  759): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  759): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2735): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2735): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1602): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,I/art     (  759): Explicit concurrent mark sweep GC freed 44092(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 27MB/41MB, paused 1.010ms total 70.948ms
,D/SystemUpdateService( 1602): onCreate
D/SystemUpdateService( 1602): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
I/SystemUpdateService( 1602): active receiver: enabled
,I/SystemUpdateService( 1602): showing system update notification
,I/ValidateNoPeople(  759): skipping global notification
,V/SystemUpdateService( 1602): retry (wakeup: false) in 3599980 ms
,D/SystemUpdateService( 1602): onDestroy
,E/GpsLocationProvider(  759): No APN found to select.
,D/Finsky  ( 2614): [255] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2614): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/GLSActivity( 1567): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1567): Vacuum at: now=1450280733254 tag=VacuumService
,I/PhenotypeConfigurator( 1567): Scheduling Phenotype for one-off execution 7770 seconds from now (1450280733478)
,D/GetConfigurationSnapshotOperation( 1567): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1567): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1567): Using platform SSLCertificateSocketFactory
,V/GLSActivity( 1567): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1567): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Keyboard.Facilitator.LanguageModelFlusher( 1086): run()
I/Keyboard.Facilitator( 1086): flushDynamicLanguageModels()
,I/ConfigService( 1567): onCreate
,I/ConfigService( 1567): onDestroy
,I/ClearcutLoggerApiImpl( 1567): disconnect managed GoogleApiClient
,I/jxcore-log( 3309): Connected to the server!
I/jxcore-log( 3309): 
,I/chromium( 3309): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,I/ActivityManager(  759): Killing 2553:com.google.android.gm/u0a70 (adj 15): empty #17
,W/libprocessgroup(  759): failed to open /acct/uid_10070/pid_2553/cgroup.procs: No such file or directory
,W/bt-smp  ( 2086): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2086): Plain text(LSB ~ MSB) = 5e 1c 7e 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2086): Encrypted text(LSB ~ MSB) = 16 92 fa 29 8f 65 a3 32 87 94 5d ed f8 c3 9b 79 
W/bt-btm  ( 2086): Stopping oneshot timer
,I/EventLogService( 1602): Aggregate from 1450279201510 (log), 1450279201510 (data)
,I/ActivityManager(  759): Start proc com.google.android.youtube for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator: pid=3664 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 3664): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3664): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 3664): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 3664): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 3664): Installed default security provider GmsCore_OpenSSL
,E/YouTube MDX( 3664): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,I/dex2oat ( 3710): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads-1324881926.jar --oat-fd=30 --oat-location=/data/data/com.google.android.youtube/cache/ads-1324881926.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 3710): dex2oat took 41.767ms (threads: 4)
,W/InstanceID/Rpc( 3664): Found 10008
,I/ActivityManager(  759): Killing 1959:com.google.android.calendar/u0a31 (adj 15): empty #17
,W/libprocessgroup(  759): failed to open /acct/uid_10031/pid_1959/cgroup.procs: No such file or directory
,I/UsageStatsService(  759): User[0] Flushing usage stats to disk
,I/ProcessStatsService(  759): Prepared write state in 24ms
,I/ProcessStatsService(  759): Prepared write state in 4ms
,V/GLSActivity( 1567): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1567): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ProcessStatsService(  759): Pruning old procstats: /data/system/procstats/state-2015-12-16-02-32-25.bin
,I/ActivityManager(  759): Killing 1994:com.android.providers.calendar/u0a2 (adj 15): empty for 1802s
,I/ActivityManager(  759): Killing 3069:com.google.android.gms:car/u0a8 (adj 15): empty for 1802s
,W/libprocessgroup(  759): failed to open /acct/uid_10002/pid_1994/cgroup.procs: No such file or directory
,W/libprocessgroup(  759): failed to open /acct/uid_10008/pid_3069/cgroup.procs: No such file or directory
,I/ActivityManager(  759): Killing 3128:com.android.defcontainer/u0a5 (adj 13): empty for 1807s
,W/bt-smp  ( 2086): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2086): Plain text(LSB ~ MSB) = ec c9 75 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2086): Encrypted text(LSB ~ MSB) = 1f 57 9d 75 77 8b d4 f1 38 d6 46 9a 1d 1c 2f 48 
W/bt-btm  ( 2086): Stopping oneshot timer
,I/ActivityManager(  759): Killing 3230:com.google.android.apps.docs/u0a40 (adj 15): empty for 1810s
,I/ActivityManager(  759): Killing 3197:com.android.musicfx/u0a15 (adj 15): empty for 1810s
,I/ActivityManager(  759): Killing 1441:com.google.android.partnersetup/u0a13 (adj 15): empty for 1810s
,I/ActivityManager(  759): Killing 2869:android.process.acore/u0a4 (adj 15): empty for 1810s
,W/libprocessgroup(  759): failed to open /acct/uid_10040/pid_3230/cgroup.procs: No such file or directory
,W/libprocessgroup(  759): failed to open /acct/uid_10015/pid_3197/cgroup.procs: No such file or directory
,W/libprocessgroup(  759): failed to open /acct/uid_10013/pid_1441/cgroup.procs: No such file or directory
,W/libprocessgroup(  759): failed to open /acct/uid_10004/pid_2869/cgroup.procs: No such file or directory
,W/libprocessgroup(  759): failed to open /acct/uid_10005/pid_3128/cgroup.procs: No such file or directory
,TIME-OUT KILL (timeout was 1800000ms)
```
