#### Test 50650278d0426ce_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
D/Finsky  ( 2629): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
I/ActivityManager(  759): Killing 2601:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
W/ResourcesManager( 3203): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3203): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/libprocessgroup(  759): failed to open /acct/uid_10069/pid_2601/cgroup.procs: No such file or directory
V/JNIHelp ( 3203): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/System  ( 3203): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3203): Installed default security provider GmsCore_OpenSSL
V/GLSActivity( 1622): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 1695): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/Icing   ( 1695): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/Icing   ( 1695): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1695): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
,D/AndroidRuntime( 3264): 
D/AndroidRuntime( 3264): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3264): CheckJNI is OFF
D/AndroidRuntime( 3264): Calling main entry com.android.commands.am.Am
I/ActivityManager(  759): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  759): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3278 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3264): Shutting down VM
V/ActivityManager(  759): Display changed displayId=0
I/WebViewFactory( 3278): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3278): Time to load native libraries: 2 ms (timestamps 9134-9136)
I/LibraryLoader( 3278): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3278): Binding Chromium to main looper Looper (main, tid 1) {3c8cc6de}
I/LibraryLoader( 3278): Expected native library version number "",actual native library version number ""
I/chromium( 3278): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3278): Initializing chromium process, singleProcess=true
W/art     ( 3278): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3278): ApplicationContext is null in ApplicationStatus
W/chromium( 3278): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3278): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3278): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3278): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  759): Message: 20
,D/BluetoothManagerService(  759): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1c4e63e7:true
,W/art     ( 3278): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3278): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3278): CordovaWebView is running on device made by: LGE
,W/art     ( 3278): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3278): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3278): Render dirty regions requested: true
,D/Atlas   ( 3278): Validating map...
,W/chromium( 3278): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/ActivityManager(  759): Killing 2557:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,W/libprocessgroup(  759): failed to open /acct/uid_10045/pid_2557/cgroup.procs: No such file or directory
,I/OpenGLRenderer( 3278): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3278): Enabling debug mode 0
,W/IInputConnectionWrapper( 3278): showStatusIcon on inactive InputConnection
,I/ActivityManager(  759): Displayed com.test.thalitest/.MainActivity: +424ms (total +57s681ms)
,W/BindingManager( 3278): Cannot call determinedVisibility() - never saw a connection for the pid: 3278
,D/JsMessageQueue( 3278): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3278): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257342720
,D/JX-Cordova( 3278): jxcore cordova android initializing
,W/jxcore-log( 3278): Initializing JXcore engine
W/jxcore-log( 3278): JXcore engine is ready
,W/jxcore-log( 3278): Starting JXcore engine
,W/.test.thalitest( 3278): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[7976]" dev="sockfs" ino=7976 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/.test.thalitest( 3278): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 3278): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8033]" dev="sockfs" ino=8033 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3278): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[19318]" dev="sockfs" ino=19318 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3278): Platform android
W/jxcore-log( 3278): 
,W/jxcore-log( 3278): Process ARCH arm
W/jxcore-log( 3278): 
,I/jxcore-log( 3278): JXcore Cordova bridge is ready!
I/jxcore-log( 3278): 
,W/jxcore-log( 3278): JXcore engine is started
I/chromium( 3278): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3278): Toggling radios to true
I/jxcore-log( 3278): 
,D/BluetoothAdapter( 3278): enable(): BT is already enabled..!
,D/WifiService(  759): New client listening to asynchronous messages
,D/WifiService(  759): setWifiEnabled: true pid=3278, uid=10270
E/WifiService(  759): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3278): Radios toggled
I/jxcore-log( 3278): 
,I/wpa_supplicant( 1025): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  759): WifiStateMachine: Leaving Connected state
,E/WifiConfigStore(  759): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/native  (  759): do suspend true
,D/CommandListener(  178): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1622): Read error: ssl=0xb425de00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1622): SSL shutdown failed: ssl=0xb425de00: I/O error during system call, Broken pipe
,D/ConnectivityService(  759): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): ValidatedState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): DefaultState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,E/WifiConfigStore(  759): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiStateMachine(  759): Start Disconnecting Watchdog 1
D/ConnectivityService(  759): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  759): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,E/native  (  759): do suspend true
,I/wpa_supplicant( 1025): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/CommandListener(  178): Clearing all IP addresses on wlan0
,D/ConnectivityService(  759): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/Nat464Xlat(  759): requiresClat: netType=1, connected=false, hasIPv4Address=true
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/CSLegacyTypeTracker(  759): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Disconnected - quitting
D/ConnectivityManager.CallbackHandler( 1695): CM callback handler got msg 524292
D/ConnectivityManager.CallbackHandler(  897): CM callback handler got msg 524292
D/ConnectivityService(  759): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  759): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  759): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1259): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WifiNetworkAgent(  759): NetworkAgent: NetworkAgent channel lost
,V/GLSActivity( 1622): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1622): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/NetworkUtils( 1379): OkHttp exception
W/EventLoggerService( 1379): Unable to send logs Error code: 262146
,I/wpa_supplicant( 1025): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant( 1025): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1025): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1025): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  759): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  759): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  759): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  759): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  178): Setting iface cfg
,E/WifiStateMachine(  759): Start Dhcp Watchdog 2
,E/native  (  759): do suspend false
,E/WifiStateMachine(  759): scanCount==0 - aborting
,I/dhcpcd  ( 3357): version 5.5.6 starting
,E/dhcpcd  ( 3357): get_duid: Read-only file system
,I/dhcpcd  ( 3357): wlan0: rebinding lease of 192.168.1.114
,I/dhcpcd  ( 3357): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3357): wlan0: leased 192.168.1.114 for 86400 seconds
,D/ConnectivityService(  759): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  759): MasterInitialState.processMessage what=3
,D/ConnectivityService(  759): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  759): MasterInitialState.processMessage what=3
,V/MusicLeanback( 2756): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1695): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1695): onCreate
,D/SystemUpdateService( 1695): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.Environment( 1695): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/SystemUpdateService( 1695): active receiver: enabled
,I/Babel   ( 1939): connection state changed from CONNECTED to DISCONNECTED
,I/SystemUpdateService( 1695): showing system update notification
,I/iu.UploadsManager( 1695): num queued entries: 0
I/iu.UploadsManager( 1695): num updated entries: 0
I/iu.SyncManager( 1695): NEXT; no task
,I/ActivityManager(  759): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3390 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/native  (  759): do suspend true
,D/ConnectivityService(  759): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService(  759): Adding iface wlan0 to network 101
,E/WifiStateMachine(  759): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/GpsLocationProvider(  759): No APN found to select.
,E/ConnectivityService(  759): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  759): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  759): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  759): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  759): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  759): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  759): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  759): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  759): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  759):    accepting network in place of null
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/CSLegacyTypeTracker(  759): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  759): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  759): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.114/24,fe80::5255:27ff:fef0:fd0b/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  759): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,I/ValidateNoPeople(  759): skipping global notification
,D/ConnectivityManager.CallbackHandler(  897): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1695): CM callback handler got msg 524290
,E/GpsLocationProvider(  759): No APN found to select.
,V/SystemUpdateService( 1695): retry (wakeup: false) in 3599912 ms
,D/SystemUpdateService( 1695): onDestroy
,I/GAv4    ( 3390): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3390):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3390):   adb logcat -s GAv4
,W/GAv4    ( 3390): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 09 Dec 2015 17:12:34 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1449681154788], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1449681154758]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Validated
D/ConnectivityService(  759): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  759): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  759): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  759): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  897): CM callback handler got msg 524290
,D/ConnectivityService(  759): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1695): CM callback handler got msg 524290
D/TelephonyNetworkFactory( 1259): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,W/GAv4    ( 3390): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3390): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 3390): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3390): Time to load native libraries: 2 ms (timestamps 5093-5095)
I/LibraryLoader( 3390): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3390): Binding Chromium to main looper Looper (main, tid 1) {33136e20}
,I/LibraryLoader( 3390): Expected native library version number "",actual native library version number ""
,I/chromium( 3390): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3390): Initializing chromium process, singleProcess=true
,W/art     ( 3390): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3390): ApplicationContext is null in ApplicationStatus
,W/chromium( 3390): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3390): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3390): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3390): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/AudioManagerAndroid( 3390): Requires BLUETOOTH permission
,I/NSApplication( 3390): Starting up...
,I/ActivityManager(  759): Killing 2736:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/libprocessgroup(  759): failed to open /acct/uid_10003/pid_2736/cgroup.procs: No such file or directory
,V/MusicLeanback( 2756): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1695): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1695): onCreate
,D/SystemUpdateService( 1695): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1695): active receiver: enabled
,I/SystemUpdateService( 1695): showing system update notification
,I/iu.Environment( 1695): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1695): num queued entries: 0
,I/iu.UploadsManager( 1695): num updated entries: 0
,I/iu.SyncManager( 1695): NEXT; no task
,I/ValidateNoPeople(  759): skipping global notification
,V/SystemUpdateService( 1695): retry (wakeup: false) in 3599957 ms
,D/SystemUpdateService( 1695): onDestroy
,I/Babel   ( 1939): connection state changed from DISCONNECTED to CONNECTED
,D/ConnectivityService(  759): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/jxcore-log( 3278): Test app app.js loaded
I/jxcore-log( 3278): 
,D/ConnectivityService(  759): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/chromium( 3278): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/Tethering(  759): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2756): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2756): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1695): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1695): onCreate
,D/SystemUpdateService( 1695): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1695): active receiver: enabled
,I/SystemUpdateService( 1695): showing system update notification
,I/ValidateNoPeople(  759): skipping global notification
,V/SystemUpdateService( 1695): retry (wakeup: false) in 3599978 ms
,E/GpsLocationProvider(  759): No APN found to select.
,D/SystemUpdateService( 1695): onDestroy
,D/Finsky  ( 2629): [260] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2629): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/art     (  759): Explicit concurrent mark sweep GC freed 44635(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 27MB/41MB, paused 1.210ms total 118.105ms
,V/GLSActivity( 1622): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1622): Vacuum at: now=1449681167341 tag=VacuumService
,I/ClearcutLoggerApiImpl( 1622): disconnect managed GoogleApiClient
,I/ActivityManager(  759): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=3503 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,I/GAv4    ( 3503): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3503):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3503):   adb logcat -s GAv4
,W/GAv4    ( 3503): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3503): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3503): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  759): Killing 2703:com.android.settings/1000 (adj 15): empty #17
,D/WifiService(  759): Client connection lost with reason: 4
,W/libprocessgroup(  759): failed to open /acct/uid_1000/pid_2703/cgroup.procs: No such file or directory
,V/GLSActivity( 1622): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1622): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1622): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 3278): Toggling radios to false
I/jxcore-log( 3278): 
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  759): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@d3d43aa mBinding = false
,D/BluetoothManagerService(  759): Message: 2
D/BluetoothManagerService(  759): Sending off request.
,D/BluetoothAdapterState( 2104): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 2104): Setting state to 13
I/BluetoothAdapterState( 2104): Bluetooth adapter state changed: 12-> 13
,D/BluetoothAdapterProperties( 2104): onBluetoothDisable()
I/BluetoothAdapterState( 2104): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,D/BluetoothAdapterProperties( 2104): Scan Mode:20
,D/BluetoothAdapterState( 2104): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,V/BluetoothMapMasInstance( 2104): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 2104): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 2104): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
V/BluetoothMapMasInstance( 2104): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:489)
V/BluetoothMapMasInstance( 2104): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:399)
V/BluetoothMapMasInstance( 2104): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 2104): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 2104): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,D/btif_config_util( 2104): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/BtOppRfcommListener( 2104): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,W/bt-btif ( 2104): bta_dm_disable BTA_DISABLE_DELAY set to 100 ms
,W/bt-l2cap( 2104): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2104): L2CAP - PSM: 0x0017 not found for deregistration
,D/BluetoothManagerService(  759): Message: 60
D/BluetoothManagerService(  759): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService(  759): Bluetooth State Change Intent: 12 -> 13
,D/BluetoothMapService( 2104): onReceive
D/BluetoothMapService( 2104): STATE_TURNING_OFF
V/BluetoothMapService( 2104): Handler(): got msg=4
D/BluetoothMapService( 2104): MAP Service closeService in
D/BluetoothMapMasInstance( 2104): MAP Service shutdown
V/BluetoothMapService( 2104): MAP Service closeService out
,I/BtOppRfcommListener( 2104): stopping Accept Thread
,I/BtOppRfcommListener( 2104): BluetoothSocket listen thread finished
,D/WifiService(  759): setWifiEnabled: false pid=3278, uid=10270
E/WifiService(  759): Invoking mWifiStateMachine.setWifiEnabled
,I/ActivityManager(  759): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=3565 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,E/WifiStateMachine(  759): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  759): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,I/jxcore-log( 3278): Radios toggled
I/jxcore-log( 3278): 
,E/native  (  759): do suspend true
,D/CommandListener(  178): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1622): Read error: ssl=0x9dae8200: I/O error during system call, Connection timed out
,V/NativeCrypto( 1622): SSL shutdown failed: ssl=0x9dae8200: I/O error during system call, Broken pipe
,D/bt_userial( 2104): RX termination
W/bt_userial( 2104): select_read return size <=0:-1, exiting userial_read_thread
D/bt_userial( 2104): Leaving userial_read_thread()
W/bt-btif ( 2104): ag scb idx 1 not allocated
E/bt-btif ( 2104): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 2104): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2104): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2104): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2104): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2104): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2104): L2CAP - PSM: 0x0017 not found for deregistration
D/bt_userial( 2104): userial_close_reader Joined userial reader thread: 0
D/bt_hwcfg( 2104): hw_epilog_process
I/bt_userial_vendor( 2104): device fd = 53 close
,D/ConnectivityService(  759): reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10008
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): ValidatedState{ when=-1ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): DefaultState{ when=-1ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Checking http://clients3.google.com/generate_204 on "NG7005g"
I/GKI_LINUX( 2104): gki_task task_id=0 [BTU] terminating
,I/GKI_LINUX( 2104): GKI_exit_task 0 done
I/GKI_LINUX( 2104): GKI_shutdown(): task [BTU] terminated
D/BluetoothAdapterState( 2104): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/ConnectivityService(  759): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  759): NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,D/HeadsetService( 2104): Received stop request...Stopping profile...
,D/BluetoothAdapterService( 2104): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a3c80bf
,D/HeadsetStateMachine( 2104): Exit Disconnected: -1
,D/BluetoothHeadset(  759): Proxy object disconnected
E/WifiConfigStore(  759): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/BluetoothHeadset( 1221): Proxy object disconnected
,D/BluetoothHeadset( 1221): Proxy object disconnected
,D/BluetoothHeadset( 1259): Proxy object disconnected
D/BluetoothAdapterState( 2104): Stopping profile services that were post enabled
,E/WifiStateMachine(  759): scanCount==0 - aborting
D/A2dpService( 2104): Received stop request...Stopping profile...
D/A2dpStateMachine( 2104): Exit Disconnected: -1
,D/BluetoothAdapterService( 2104): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a3c80bf
,D/HidService( 2104): Received stop request...Stopping profile...
,D/BluetoothAdapterService( 2104): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a3c80bf
D/BluetoothA2dp(  759): Proxy object disconnected
D/WifiScanningService(  759): SCAN_AVAILABLE : 1
D/RttService(  759): SCAN_AVAILABLE : 1
D/WifiNetworkAgent(  759): NetworkAgent: NetworkAgent channel lost
,D/RttService(  759): EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
E/native  (  759): do suspend true
D/HealthService( 2104): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2104): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a3c80bf
,D/WifiScanningService(  759): StartedState got{ when=-3ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiScanningService(  759): DefaultState
,D/HeadsetStateMachine( 2104): Unbinding service...
,W/BluetoothHeadsetServiceJni( 2104): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 2104): Cleaning up Bluetooth Handsfree callback object
,D/ConnectivityService(  759): notifyType LOST for NetworkAgentInfo [WIFI () - 101]
D/PanService( 2104): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2104): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a3c80bf
D/ConnectivityManager.CallbackHandler(  897): CM callback handler got msg 524292
,D/Nat464Xlat(  759): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/BtGatt.DebugUtils( 2104): handleDebugAction() action=null
D/CSLegacyTypeTracker(  759): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  759): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/BtGatt.GattService( 2104): Received stop request...Stopping profile...
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Disconnected - quitting
D/BtGatt.GattService( 2104): stop()
D/ConnectivityService(  759): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/BtGatt.AdvertiseManager( 2104): advertise clients cleared
D/ConnectivityService(  759): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1259): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/ConnectivityService(  759): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/ConnectivityManager.CallbackHandler( 1695): CM callback handler got msg 524292
,D/CommandListener(  178): Clearing all IP addresses on wlan0
,D/BluetoothAdapterService( 2104): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a3c80bf
,D/BluetoothMapService( 2104): Received stop request...Stopping profile...
D/BluetoothMapService( 2104): stop()
,D/BluetoothMapEmailAppObserver( 2104): deinitObservers()
D/BluetoothMapEmailAppObserver( 2104): removeReceiver()
,D/BluetoothAdapterService( 2104): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a3c80bf
,I/GKI_LINUX( 2104): gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 2104): GKI_exit_task 2 done
I/GKI_LINUX( 2104): GKI_shutdown(): task [A2DP-MEDIA] terminated
W/BluetoothHidServiceJni( 2104): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 2104): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 2104): Cleaning up Bluetooth GID callback object
W/BluetoothHealthServiceJni( 2104): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 2104): Cleaning up Bluetooth Health object
W/BluetoothPanServiceJni( 2104): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 2104): Cleaning up Bluetooth PAN callback object
,V/BluetoothMapService( 2104): Handler(): got msg=4
D/BluetoothMapService( 2104): MAP Service closeService in
V/BluetoothMapService( 2104): MAP Service closeService out
D/BluetoothMapService( 2104): cleanup()
D/BluetoothMapService( 2104): MAP Service closeService in
V/BluetoothMapService( 2104): MAP Service closeService out
D/BluetoothAdapterState( 2104): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 2104): Setting state to 10
I/BluetoothAdapterState( 2104): Bluetooth adapter state changed: 13-> 10
D/BluetoothManagerService(  759): Message: 60
,I/BluetoothAdapterState( 2104): Entering OffState
D/BluetoothManagerService(  759): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService(  759): Broadcasting onBluetoothStateChange(false) to 5 receivers.
D/BluetoothA2dp(  759): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1221): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1259): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1221): onBluetoothStateChange: up=false
,D/BluetoothHeadset(  759): onBluetoothStateChange: up=false
,D/BluetoothManagerService(  759): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService(  759): Broadcasting onBluetoothServiceDown() to 8 receivers.
,D/BluetoothManagerService(  759): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@d3d43aa mBinding = false
,D/BluetoothManagerService(  759): Sending unbind request.
,D/BluetoothManagerService(  759): Bluetooth State Change Intent: 13 -> 10
,D/BluetoothAdapter(  897): 895254320: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter(  897): 895254320: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter(  897): 895254320: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 1622): 440126643: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 1622): 440126643: getState() :  mService = null. Returning STATE_OFF
,W/ContextImpl( 3565): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
I/GKI_LINUX( 2104): gki_task task_id=1 [BTIF] terminating
,I/GKI_LINUX( 2104): GKI_exit_task 1 done
I/GKI_LINUX( 2104): GKI_shutdown(): task [BTIF] terminated
,I/BluetoothServiceJni( 2104): cleanupNative: return from cleanup
,I/art     ( 2104): System.exit called, status: 0
I/AndroidRuntime( 2104): VM exiting with result code 0, cleanup skipped.
,D/BluetoothManagerService(  759): Message: 20
D/BluetoothManagerService(  759): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c358677:true
,I/wpa_supplicant( 1025): p2p0: CTRL-EVENT-TERMINATING 
,I/wpa_supplicant( 1025): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,I/ActivityManager(  759): Process com.android.bluetooth (pid 2104) has died
,W/ActivityManager(  759): Scheduling restart of crashed service com.android.bluetooth/.pbap.BluetoothPbapService in 1000ms
,D/BluetoothAdapter( 3565): 1015858910: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothManagerService(  759): Message: 30
,D/BluetoothManagerService(  759): Message: 30
,D/LocalBluetoothProfileManager( 3565): Adding local MAP profile
D/BluetoothMap( 3565): Create BluetoothMap proxy object
,D/BluetoothManagerService(  759): Message: 30
,D/BluetoothManagerService(  759): Message: 30
,D/LocalBluetoothProfileManager( 3565): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 3565): finishStartingService: stopping service
,I/ActivityManager(  759): Killing 2577:com.google.android.gm/u0a70 (adj 15): empty #17
,W/libprocessgroup(  759): failed to open /acct/uid_10070/pid_2577/cgroup.procs: No such file or directory
,I/PhenotypeConfigurator( 1622): Scheduling Phenotype for one-off execution 4567 seconds from now (1449681519298)
,D/GetConfigurationSnapshotOperation( 1622): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,D/WifiService(  759): New client listening to asynchronous messages
,D/Tethering(  759): InitialState.processMessage what=4
I/wpa_supplicant( 1025): wlan0: CTRL-EVENT-TERMINATING 
D/Tethering(  759): sendTetherStateChangedBroadcast 0, 0, 0
,I/ActivityManager(  759): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=3621 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,I/PhenotypeFlagCommitter( 1622): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1622): Using platform SSLCertificateSocketFactory
,W/ResourcesManager( 3621): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,W/Settings( 1939): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings( 1622): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/AdapterServiceConfig( 3621): Adding HeadsetService
D/AdapterServiceConfig( 3621): Adding A2dpService
,D/AdapterServiceConfig( 3621): Adding HidService
D/AdapterServiceConfig( 3621): Adding HealthService
D/AdapterServiceConfig( 3621): Adding PanService
D/AdapterServiceConfig( 3621): Adding GattService
D/AdapterServiceConfig( 3621): Adding BluetoothMapService
,I/ActivityManager(  759): Killing 2001:com.google.android.calendar/u0a31 (adj 15): empty #17
,D/AuthorizationBluetoothService( 1622): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,W/libprocessgroup(  759): failed to open /acct/uid_10031/pid_2001/cgroup.procs: No such file or directory
,D/Uploader( 1622): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,I/ActivityManager(  759): Start proc com.google.android.keep for broadcast com.google.android.keep/.notification.AlertReceiver: pid=3643 uid=10071 gids={50071, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Uploader( 1622): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,W/ContextImpl( 3565): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/DockEventReceiver( 3565): finishStartingService: stopping service
,D/BluetoothAdapter( 3565): 1015858910: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 3565): 1015858910: getState() :  mService = null. Returning STATE_OFF
,I/ActivityManager(  759): Killing 2821:com.android.providers.calendar/u0a2 (adj 15): empty #17
,W/libprocessgroup(  759): failed to open /acct/uid_10002/pid_2821/cgroup.procs: No such file or directory
,D/AuthorizationBluetoothService( 1622): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothAdapter( 3565): 1015858910: getState() :  mService = null. Returning STATE_OFF
,D/Uploader( 1622): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/Uploader( 1622): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/Uploader( 1622): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/Uploader( 1622): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/Uploader( 1622): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,V/GLSActivity( 1622): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1622): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Uploader( 1622): Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/ConnectivityService(  759): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  759): MasterInitialState.processMessage what=3
,D/ConnectivityService(  759): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  759): MasterInitialState.processMessage what=3
,V/MusicLeanback( 2756): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1695): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1695): onCreate
,D/SystemUpdateService( 1695): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.Environment( 1695): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,V/MusicLeanback( 2756): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/iu.UploadsManager( 1695): num queued entries: 0
I/iu.UploadsManager( 1695): num updated entries: 0
,I/Babel   ( 1939): connection state changed from CONNECTED to DISCONNECTED
I/iu.SyncManager( 1695): NEXT; no task
,I/SystemUpdateService( 1695): active receiver: enabled
,E/GpsLocationProvider(  759): No APN found to select.
I/SystemUpdateService( 1695): showing system update notification
,I/SystemUpdateService( 1695): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1695): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/ValidateNoPeople(  759): skipping global notification
,E/GpsLocationProvider(  759): No APN found to select.
,V/SystemUpdateService( 1695): retry (wakeup: false) in 3599982 ms
,I/SystemUpdateService( 1695): active receiver: enabled
,I/SystemUpdateService( 1695): showing system update notification
,I/ValidateNoPeople(  759): skipping global notification
,V/SystemUpdateService( 1695): retry (wakeup: false) in 3599982 ms
,D/SystemUpdateService( 1695): onDestroy
,D/ConnectivityService(  759): Failed to find a new network - expiring NetTransition Wakelock
,I/ActivityManager(  759): Killing 3072:com.google.android.gms:car/u0a8 (adj 15): empty #17
,W/libprocessgroup(  759): failed to open /acct/uid_10008/pid_3072/cgroup.procs: No such file or directory
,I/EventLogService( 1695): Aggregate from 1449680400486 (log), 1449680400486 (data)
,I/UsageStatsService(  759): User[0] Flushing usage stats to disk
,TIME-OUT KILL (timeout was 1800000ms)
```
