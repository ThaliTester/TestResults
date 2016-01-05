#### Test 54968200254eab2_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
I/GAv4    ( 3202): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3202):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3202):   adb logcat -s GAv4
W/GAv4    ( 3202): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3202): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3202): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 3202): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
E/SQLiteLog( 3202): (283) recovered 24 frames from WAL file /data/data/com.google.android.apps.docs/databases/DocList.db-wal
D/Finsky  ( 2654): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
W/ResourcesManager( 3202): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3202): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  755): Killing 2616:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
V/JNIHelp ( 3202): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/System  ( 3202): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3202): Installed default security provider GmsCore_OpenSSL
W/libprocessgroup(  755): failed to open /acct/uid_10069/pid_2616/cgroup.procs: No such file or directory
V/GLSActivity( 1569): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 1600): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/Icing   ( 1600): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1600): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/Icing   ( 1600): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
,I/ActivityManager(  755): Killing 2567:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
D/AndroidRuntime( 3260): 
D/AndroidRuntime( 3260): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3260): CheckJNI is OFF
W/libprocessgroup(  755): failed to open /acct/uid_10045/pid_2567/cgroup.procs: No such file or directory
D/AndroidRuntime( 3260): Calling main entry com.android.commands.am.Am
I/ActivityManager(  755): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  755): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3281 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3260): Shutting down VM
V/ActivityManager(  755): Display changed displayId=0
I/WebViewFactory( 3281): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3281): Time to load native libraries: 2 ms (timestamps 8834-8836)
I/LibraryLoader( 3281): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3281): Binding Chromium to main looper Looper (main, tid 1) {170188b6}
I/LibraryLoader( 3281): Expected native library version number "",actual native library version number ""
I/chromium( 3281): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3281): Initializing chromium process, singleProcess=true
W/art     ( 3281): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3281): ApplicationContext is null in ApplicationStatus
W/chromium( 3281): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3281): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3281): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3281): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  755): Message: 20
D/BluetoothManagerService(  755): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@28a1bff6:true
,W/art     ( 3281): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3281): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3281): CordovaWebView is running on device made by: LGE
,W/art     ( 3281): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3281): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3281): Render dirty regions requested: true
,D/Atlas   ( 3281): Validating map...
,W/chromium( 3281): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3281): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3281): Enabling debug mode 0
,I/Keyboard.Facilitator( 1078): onFinishInput()
,W/BindingManager( 3281): Cannot call determinedVisibility() - never saw a connection for the pid: 3281
,W/IInputConnectionWrapper( 3281): showStatusIcon on inactive InputConnection
,I/ActivityManager(  755): Displayed com.test.thalitest/.MainActivity: +403ms (total +56s408ms)
,D/JsMessageQueue( 3281): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3281): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257342720
,D/JX-Cordova( 3281): jxcore cordova android initializing
,W/art     ( 3281): Suspending all threads took: 6.529ms
,W/jxcore-log( 3281): Initializing JXcore engine
W/jxcore-log( 3281): JXcore engine is ready
,W/jxcore-log( 3281): Starting JXcore engine
,I/art     ( 3281): Background sticky concurrent mark sweep GC freed 68826(6MB) AllocSpace objects, 2(3MB) LOS objects, 20% free, 29MB/37MB, paused 7.499ms total 70.608ms
W/.test.thalitest( 3281): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[9472]" dev="sockfs" ino=9472 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3281): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 3281): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6636]" dev="sockfs" ino=6636 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3281): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[20742]" dev="sockfs" ino=20742 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3281): Platform android
W/jxcore-log( 3281): 
,W/jxcore-log( 3281): Process ARCH arm
W/jxcore-log( 3281): 
,I/jxcore-log( 3281): JXcore Cordova bridge is ready!
I/jxcore-log( 3281): 
W/jxcore-log( 3281): JXcore engine is started
,I/chromium( 3281): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
I/Choreographer( 3281): Skipped 107 frames!  The application may be doing too much work on its main thread.
,I/jxcore-log( 3281): Toggling radios to true
I/jxcore-log( 3281): 
,D/BluetoothAdapter( 3281): enable(): BT is already enabled..!
,D/WifiService(  755): New client listening to asynchronous messages
,D/WifiService(  755): setWifiEnabled: true pid=3281, uid=10270
,E/WifiService(  755): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3281): Radios toggled
I/jxcore-log( 3281): 
,D/BluetoothManagerService(  755): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 3281): Got Device Bluetooth address: 34:FC:EF:11:AE:67
I/jxcore-log( 3281): 
I/jxcore-log( 3281): Perf Test app loaded loaded
I/jxcore-log( 3281): 
I/wpa_supplicant( 1084): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
E/WifiStateMachine(  755): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  755): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/native  (  755): do suspend true
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,I/jxcore-log( 3281): check test folder
I/jxcore-log( 3281): 
,I/jxcore-log( 3281): found test : ./testFindPeers.js
I/jxcore-log( 3281): 
,V/NativeCrypto( 1569): Read error: ssl=0xb412ae00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1569): SSL shutdown failed: ssl=0xb412ae00: I/O error during system call, Broken pipe
,E/WifiConfigStore(  755): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  755): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  755): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,D/ConnectivityService(  755): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
,E/WifiStateMachine(  755): Start Disconnecting Watchdog 1
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  755): ValidatedState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  755): DefaultState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  755): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  755): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  755): Checking http://clients3.google.com/generate_204 on <unknown ssid>
I/wpa_supplicant( 1084): wlan0: CTRL-EVENT-SCAN-STARTED 
,E/native  (  755): do suspend true
,I/jxcore-log( 3281): found test : ./testSendData.js
I/jxcore-log( 3281): 
,D/CommandListener(  179): Clearing all IP addresses on wlan0
D/ConnectivityService(  755): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  755): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/ConnectivityManager.CallbackHandler(  899): CM callback handler got msg 524292
D/Nat464Xlat(  755): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  755): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityManager.CallbackHandler( 1600): CM callback handler got msg 524292
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  755): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/CSLegacyTypeTracker(  755): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  755): Disconnected - quitting
D/ConnectivityService(  755): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  755): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  755): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory( 1201): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WifiNetworkAgent(  755): NetworkAgent: NetworkAgent channel lost
,I/chromium( 3281): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,V/GLSActivity( 1569): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1569): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/NetworkUtils( 1321): OkHttp exception
,W/EventLoggerService( 1321): Unable to send logs Error code: 262146
,I/wpa_supplicant( 1084): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant( 1084): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1084): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1084): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  755): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  755): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  755): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  755): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/CommandListener(  179): Setting iface cfg
E/WifiStateMachine(  755): Start Dhcp Watchdog 2
,E/native  (  755): do suspend false
,E/WifiStateMachine(  755): scanCount==0 - aborting
,I/dhcpcd  ( 3362): version 5.5.6 starting
,E/dhcpcd  ( 3362): get_duid: Read-only file system
,I/dhcpcd  ( 3362): wlan0: rebinding lease of 192.168.1.114
,I/dhcpcd  ( 3362): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3362): wlan0: leased 192.168.1.114 for 86400 seconds
,E/native  (  755): do suspend true
,D/ConnectivityService(  755): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  755): Adding iface wlan0 to network 101
,E/WifiStateMachine(  755): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  755): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  755): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  755): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  755): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  755): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  755): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  755): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  755): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  755): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  755): Connected
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  755): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  755): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/ConnectivityService(  755): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  755):    accepting network in place of null
,D/CSLegacyTypeTracker(  755): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  755): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  755): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService(  755): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  899): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1600): CM callback handler got msg 524290
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  755): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 05 Jan 2016 00:39:23 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1451954363207], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1451954363189]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  755): Don't send network conditions - lacking user consent.
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  755): Validated
D/ConnectivityService(  755): Validated NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  755): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  755): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  755): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  899): CM callback handler got msg 524290
D/ConnectivityService(  755): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/TelephonyNetworkFactory( 1201): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 1600): CM callback handler got msg 524290
,D/ConnectivityService(  755): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  755): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  755): MasterInitialState.processMessage what=3
,D/Tethering(  755): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2784): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 2784): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2784): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,E/GpsLocationProvider(  755): No APN found to select.
,I/SystemUpdateService( 1600): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1600): onCreate
,D/SystemUpdateService( 1600): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1600): active receiver: enabled
,I/SystemUpdateService( 1600): showing system update notification
,E/GpsLocationProvider(  755): No APN found to select.
,E/ActivityThread( 1600): Failed to find provider info for com.android.contacts.metadata
,I/ValidateNoPeople(  755): skipping global notification
,V/SystemUpdateService( 1600): retry (wakeup: false) in 3599977 ms
,I/ActivityManager(  755): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3447 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/SyncManager(  755): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 66749, reason: UserStart, SyncResult: databaseError: true stats []
D/SyncManager(  755): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 151226, reason: UserStart
,D/SystemUpdateService( 1600): onDestroy
,D/Nat464Xlat(  755): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  755): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  899): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 1600): CM callback handler got msg 524295
,D/ConnectivityService(  755): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/GAv4    ( 3447): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3447):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3447):   adb logcat -s GAv4
,W/GAv4    ( 3447): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3447): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3447): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 3447): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3447): Time to load native libraries: 2 ms (timestamps 5812-5814)
I/LibraryLoader( 3447): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3447): Binding Chromium to main looper Looper (main, tid 1) {32504e38}
I/LibraryLoader( 3447): Expected native library version number "",actual native library version number ""
I/chromium( 3447): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3447): Initializing chromium process, singleProcess=true
,W/art     ( 3447): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3447): ApplicationContext is null in ApplicationStatus
,W/chromium( 3447): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3447): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3447): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3447): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/AudioManagerAndroid( 3447): Requires BLUETOOTH permission
,I/NSApplication( 3447): Starting up...
,I/ActivityManager(  755): Killing 2760:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/libprocessgroup(  755): failed to open /acct/uid_10003/pid_2760/cgroup.procs: No such file or directory
,V/MusicLeanback( 2784): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1600): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1600): onCreate
,D/SystemUpdateService( 1600): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1600): active receiver: enabled
,I/SystemUpdateService( 1600): showing system update notification
,I/ValidateNoPeople(  755): skipping global notification
,V/SystemUpdateService( 1600): retry (wakeup: false) in 3599987 ms
,D/SystemUpdateService( 1600): onDestroy
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): setDiscoveryMode: Mode set to WIFI
,I/jxcore-log( 3281): BLE supported!!
I/jxcore-log( 3281): 
,D/ConnectivityService(  755): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  755): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2784): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2784): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1600): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,I/art     (  755): Explicit concurrent mark sweep GC freed 46769(2MB) AllocSpace objects, 8(128KB) LOS objects, 33% free, 27MB/41MB, paused 1.066ms total 69.559ms
,D/SystemUpdateService( 1600): onCreate
,D/SystemUpdateService( 1600): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,E/GpsLocationProvider(  755): No APN found to select.
I/SystemUpdateService( 1600): active receiver: enabled
,I/SystemUpdateService( 1600): showing system update notification
,I/ValidateNoPeople(  755): skipping global notification
,V/SystemUpdateService( 1600): retry (wakeup: false) in 3599986 ms
,D/SystemUpdateService( 1600): onDestroy
,D/Finsky  ( 2654): [255] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2654): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/GLSActivity( 1569): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1569): Vacuum at: now=1451954378168 tag=VacuumService
,I/Keyboard.Facilitator.LanguageModelFlusher( 1078): run()
I/Keyboard.Facilitator( 1078): flushDynamicLanguageModels()
,I/ConfigService( 1569): onCreate
,I/ConfigService( 1569): onDestroy
,I/ClearcutLoggerApiImpl( 1569): disconnect managed GoogleApiClient
,I/jxcore-log( 3281): Connected to the server!
I/jxcore-log( 3281): 
,I/chromium( 3281): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3281): --- start :testFindPeers.js---
I/jxcore-log( 3281): 
,I/jxcore-log( 3281): testFindPeers created [object Object]
I/jxcore-log( 3281): 
,I/jxcore-log( 3281): serverPort is 8876
I/jxcore-log( 3281): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): setDiscoveryMode: Mode set to WIFI
,D/BluetoothManagerService(  755): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3281): start: Peer ID: 34:FC:EF:11:AE:67, peer name: LGE-Nexus 5_PT9383
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3281): bind: Binding a new listener
,D/BluetoothManagerService(  755): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3281): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  755): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3281): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT9383","ra":"34:FC:EF:11:AE:67"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3281): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3281): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3281): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  755): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3281): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3281): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3281): start: OK
I/io.jxcore.node.ConnectionHelper( 3281): start: Using peer discovery mode: WIFI
,D/BluetoothManagerService(  755): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): start: Peer ID: 34:FC:EF:11:AE:67, peer name: LGE-Nexus 5_PT9383
,D/BluetoothManagerService(  755): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3281): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT9383","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3281): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3281): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT9383","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3281): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT9383","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3281): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3281): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3281): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3281): start: OK
I/jxcore-log( 3281): StartBroadcasting started ok
I/jxcore-log( 3281): 
I/chromium( 3281): [INFO:CONSOLE(63)] "logCallback --- start :testFindPeers.js---", source: file:///android_asset/www/js/thali_main.js (63)
I/io.jxcore.node.ConnectionHelper( 3281): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3281): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3281): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3281): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3281): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3281): onDiscoveryManagerStateChanged: RUNNING
,I/wpa_supplicant( 1084): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1084): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1084): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1084): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1084): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3281): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
,D/WifiP2pManager( 3281): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3281): Service request added successfully
,I/wpa_supplicant( 1084): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1084): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3281): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
,I/wpa_supplicant( 1084): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1084): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3281): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3281): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6753","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3281): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3281): onServiceDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753]
I/io.jxcore.node.ConnectionHelper( 3281): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
D/io.jxcore.node.ConnectionHelper( 3281): notifyPeerAvailability: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753] is available
,I/jxcore-log( 3281): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:76:27","peerName":"samsung-SM-A300FU_PT6753","peerAvailable":true}]
I/jxcore-log( 3281): 
I/jxcore-log( 3281): Found peer : 08:EC:A9:50:76:27, peerAvailable: true
I/jxcore-log( 3281): 
I/jxcore-log( 3281): weAreDoneNow
I/jxcore-log( 3281): 
I/jxcore-log( 3281): done, now sending data to server
I/jxcore-log( 3281): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3281): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT8357","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3281): onDnsSdServiceAvailable: Resolved peer properties: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8357]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3281): onServiceDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8357]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8357]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8357], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): modifyListOfDiscoveredPeers: Adding new peer: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8357]
I/io.jxcore.node.ConnectionHelper( 3281): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8357], Bluetooth address: 90:E7:C4:F6:69:77, device name: Android_608e, device address: 92:e7:c4:e6:4c:f8
D/io.jxcore.node.ConnectionHelper( 3281): notifyPeerAvailability: Peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8357] is available
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3281): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3281): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3281): setState: RESTARTING
,I/wpa_supplicant( 1084): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1084): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 1084): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3281): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3281): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3281): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3281): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3281): P2P device discovery started successfully
,I/wpa_supplicant( 1084): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3281): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3281): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1084): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3281): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): onP2pDeviceListChanged: Peer 1: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3281): restart: Restarting...
,D/WifiP2pManager( 3281): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3281): Service request added successfully
,I/wpa_supplicant( 1084): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1084): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3281): Service discovery started successfully
,I/wpa_supplicant( 1084): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1084): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1084): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3281): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3281): restart: Restarting...
,D/WifiP2pManager( 3281): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3281): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3281): Service discovery started successfully
,I/wpa_supplicant( 1084): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1084): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 1084): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3281): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8357], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8357]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3281): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): checkListForExpiredPeers: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): modifyListOfDiscoveredPeers: Removed [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753]
I/io.jxcore.node.ConnectionHelper( 3281): onPeerLost: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753]
D/io.jxcore.node.ConnectionHelper( 3281): hasConnection: No connection with peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 3281): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753] removed
D/io.jxcore.node.ConnectionHelper( 3281): notifyPeerAvailability: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753] not available
,D/WifiP2pManager( 3281): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3281): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3281): Service discovery started successfully
,I/wpa_supplicant( 1084): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1084): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 1084): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1084): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3281): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8357], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8357]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3281): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8357], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8357]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3281): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT8357","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3281): onDnsSdServiceAvailable: Resolved peer properties: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8357]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3281): onServiceDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8357]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8357]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8357], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8357]
,I/io.jxcore.node.ConnectionHelper( 3281): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8357], Bluetooth address: 90:E7:C4:F6:69:77, device name: Android_608e, device address: 92:e7:c4:e6:4c:f8
W/io.jxcore.node.ConnectionHelper( 3281): modifyListOfDiscoveredPeers: Peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8357] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3281): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6753","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3281): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3281): onServiceDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753]
,I/io.jxcore.node.ConnectionHelper( 3281): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
,D/io.jxcore.node.ConnectionHelper( 3281): notifyPeerAvailability: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753] is available
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3281): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3281): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3281): setState: RESTARTING
,I/wpa_supplicant( 1084): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1084): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 1084): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
I/wpa_supplicant( 1084): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 1084): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3281): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3281): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3281): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3281): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3281): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3281): Start timer timeout, starting now...
,I/wpa_supplicant( 1084): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3281): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3281): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3281): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1084): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3281): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3281): restart: Restarting...
,D/WifiP2pManager( 3281): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3281): Service request added successfully
,I/wpa_supplicant( 1084): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1084): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 1084): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3281): Service discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3281): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
,I/wpa_supplicant( 1084): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1084): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3281): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80,
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3281): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT2787","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3281): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3281): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787]
I/io.jxcore.node.ConnectionHelper( 3281): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT2787], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
D/io.jxcore.node.ConnectionHelper( 3281): notifyPeerAvailability: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT2787] is available
,I/wpa_supplicant( 1084): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3281): teardown
I/jxcore-log( 3281): 
,I/jxcore-log( 3281): testFindPeers stopped
I/jxcore-log( 3281): 
,I/io.jxcore.node.ConnectionHelper( 3281): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3281): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3281): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3281): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3281): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3281): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3281): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3281): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3281): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3281): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3281): stop: Stopping P2P device discovery...
,I/wpa_supplicant( 1084): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1084): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
,I/wpa_supplicant( 1084): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 1084): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3281): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3281): release: No more listeners, de-initializing...
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3281): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3281): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): setState: NOT_STARTED
,I/jxcore-log( 3281): StopBroadcasting went ok
I/jxcore-log( 3281): 
,I/chromium( 3281): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
I/io.jxcore.node.ConnectionHelper( 3281): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3281): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3281): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3281): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 3281): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 3281): --- start :testSendData.js---
I/jxcore-log( 3281): 
,I/jxcore-log( 3281): testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":14}bt-address length : 0
I/jxcore-log( 3281): 
,I/jxcore-log( 3281): daya100000
I/jxcore-log( 3281): 
I/jxcore-log( 3281): check server
I/jxcore-log( 3281): 
I/jxcore-log( 3281): serverPort is 41887
I/jxcore-log( 3281): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): setDiscoveryMode: Mode set to WIFI
,D/BluetoothManagerService(  755): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3281): start: Peer ID: 34:FC:EF:11:AE:67, peer name: LGE-Nexus 5_PT9383
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3281): bind: Binding a new listener
,D/BluetoothManagerService(  755): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3281): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  755): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3281): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT9383","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3281): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3281): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3281): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  755): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3281): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3281): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3281): start: OK
I/io.jxcore.node.ConnectionHelper( 3281): start: Using peer discovery mode: WIFI
,D/BluetoothManagerService(  755): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): start: Peer ID: 34:FC:EF:11:AE:67, peer name: LGE-Nexus 5_PT9383
,D/BluetoothManagerService(  755): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3281): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT9383","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3281): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3281): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT9383","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3281): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT9383","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3281): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3281): start: Starting P2P device discovery...
,I/wpa_supplicant( 1084): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3281): start: OK
,I/jxcore-log( 3281): StartBroadcasting started ok
I/jxcore-log( 3281): 
,I/jxcore-log( 3281): null
I/jxcore-log( 3281): 
I/jxcore-log( 3281): 2016-01-05T00:47:23.678Z SendDataTCPServer.js: TCP/IP server is bound to port: 41887
I/jxcore-log( 3281): 
,I/chromium( 3281): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
,I/io.jxcore.node.ConnectionHelper( 3281): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3281): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3281): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3281): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3281): setState: RESTARTING
,I/wpa_supplicant( 1084): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3281): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3281): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3281): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3281): onDiscoveryManagerStateChanged: RUNNING
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3281): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3281): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3281): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3281): setState: RESTARTING
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3281): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3281): Start timer timeout, starting now...
,I/wpa_supplicant( 1084): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3281): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3281): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3281): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1084): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1084): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1084): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1084): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 1084): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3281): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3281): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3281): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/WifiP2pManager( 3281): Ignored { when=-12ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3281): Service request added successfully
,I/wpa_supplicant( 1084): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1084): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3281): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): onP2pDeviceListChanged: Peer 4: G3-1 02:9a:02:7b:60:ac
,W/bt-btif ( 2110): info:x10
,D/        ( 2110): remote version info [7c:f9:0e:51:18:22]: 7, 1d, 7d3
E/BluetoothRemoteDevices( 2110): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 1084): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1084): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3281): Service discovery started successfully
,I/wpa_supplicant( 1084): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3281): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
,I/BluetoothBondStateMachine( 2110): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:51:18:22 newState: 1
E/bt-btif ( 2110): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2110): Bond State Change Intent:7C:F9:0E:51:18:22 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2110): Entering PendingCommandState State
,W/BluetoothEventManager( 2740): CachedBluetoothDevice for device 7C:F9:0E:51:18:22 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2740): Got bonding state changed for 7C:F9:0E:51:18:22, but we have no record of that device.
,I/BluetoothBondStateMachine( 2110): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:51:18:22 newState: 0
,D/BluetoothAdapterProperties( 2110): Failed to remove device: 7C:F9:0E:51:18:22
,I/BluetoothBondStateMachine( 2110): Bond State Change Intent:7C:F9:0E:51:18:22 OldState: 11 NewState: 10
,W/BluetoothEventManager( 2740): CachedBluetoothDevice for device 7C:F9:0E:51:18:22 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2740): Got bonding state changed for 7C:F9:0E:51:18:22, but we have no record of that device.
,I/BluetoothBondStateMachine( 2110): StableState(): Entering Off State
,W/bt-btif ( 2110): new conn_srvc id:26, app_id:255
W/bt-btif ( 2110): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2110): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3281): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3281): Incoming connection initialized (thread ID: 310)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3281): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3281): Entering thread (ID: 310)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3281): onBytesRead: Read 83 bytes successfully (thread ID: 310)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3281): Got valid identity from [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3281): onBytesWritten: 77 bytes successfully written (thread ID: 310)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3281): removeThreadFromList: Removing thread with ID 310
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3281): Handshake thread disposed (thread ID: 310)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3281): onIncomingConnectionConnected: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3281): onConnected: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690]
I/io.jxcore.node.ConnectionHelper( 3281): onConnected: Incoming connection to peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690]
D/io.jxcore.node.ConnectionHelper( 3281): hasConnection: No connection with peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 3281): notifyPeerAvailability: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690] is available
I/jxcore-log( 3281): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:51:18:22","peerName":"samsung-SM-A500FU_PT3690","peerAvailable":true}]
I/jxcore-log( 3281): 
I/jxcore-log( 3281): Found peer : samsung-SM-A500FU_PT3690, Available: true
I/jxcore-log( 3281): 
,I/jxcore-log( 3281): startWithNextDevice
I/jxcore-log( 3281): 
I/jxcore-log( 3281): device[1]: 7C:F9:0E:51:18:22
I/jxcore-log( 3281): 
I/jxcore-log( 3281): 2016-01-05T00:47:33.213Z SendDataConnector.js: Start called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3281): 
,I/jxcore-log( 3281): 2016-01-05T00:47:33.214Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:51:18:22,
I/jxcore-log( 3281): 
I/jxcore-log( 3281): 2016-01-05T00:47:33.215Z SendDataConnector.js: do connect now
I/jxcore-log( 3281): 
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3281): Exiting thread (ID: 310)
,I/io.jxcore.node.ConnectionHelper( 3281): connect: Trying to connect to peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 3281): hasConnection: No connection with peer with ID 7C:F9:0E:51:18:22
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3281): connect: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3281): connect: Trying to start connecting to Thali Test (Galaxy A5) in address 7C:F9:0E:51:18:22
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3281): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3281): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3281): onConnecting: Thali Test (Galaxy A5) 7C:F9:0E:51:18:22
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3281): connect: Started connecting to Thali Test (Galaxy A5) in address 7C:F9:0E:51:18:22
I/io.jxcore.node.ConnectionHelper( 3281): connect: Connection process successfully started (peer ID: 7C:F9:0E:51:18:22)
,I/io.jxcore.node.ConnectionHelper( 3281): onConnected: Incoming socket thread, for peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690], created successfully
D/io.jxcore.node.ConnectionHelper( 3281): onConnected: The total number of connections is now 1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3281): Trying to connect to peer with address 7C:F9:0E:51:18:22 (thread ID: 311)
W/BluetoothAdapter( 3281): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2110): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/io.jxcore.node.IncomingSocketThread( 3281): Entering thread (ID: 312)
,I/io.jxcore.node.IncomingSocketThread( 3281): Local host address: localhost/127.0.0.1, port: 41887
D/io.jxcore.node.IncomingSocketThread( 3281): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3281): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3281): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3281): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3281): Exiting thread (ID: 312)
,I/jxcore-log( 3281): 2016-01-05T00:47:33.239Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3281): 
,D/io.jxcore.node.StreamCopyingThread( 3281): Entering thread (ID: 314, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3281): Entering thread (ID: 313, name: Sender)
,W/bt-sdp  ( 2110): process_service_search_attr_rsp
,W/bt-btif ( 2110): new conn_srvc id:26, app_id:1
W/bt-btif ( 2110): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2110): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2110): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3281): onSocketConnected: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3281): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 311)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3281): onBytesWritten: 77 bytes successfully written (thread ID: 315)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3281): Outgoing connection initialized (*handshake* thread ID: 315)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3281): Exiting thread (thread ID: 311)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3281): Entering thread (ID: 315)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3281): onBytesRead: Read 83 bytes successfully (thread ID: 315)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3281): Handshake succeeded with [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3281): onHandshakeSucceeded: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3281): Exiting thread (ID: 315)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3281): onConnected: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690]
I/io.jxcore.node.ConnectionHelper( 3281): onConnected: Outgoing connection to peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690]
D/io.jxcore.node.ConnectionHelper( 3281): hasConnection: We have an incoming connection with peer with ID 7C:F9:0E:51:18:22
W/io.jxcore.node.ConnectionHelper( 3281): onConnected: Already connected with peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690], continuing anyway...
W/io.jxcore.node.ConnectionHelper( 3281): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 3281): onConnected: Outgoing socket thread, for peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3281): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 3281): onConnected: The total number of connections is now 2
,D/io.jxcore.node.OutgoingSocketThread( 3281): Entering thread (ID: 316)
,D/io.jxcore.node.OutgoingSocketThread( 3281): Server socket local port: 47982
I/io.jxcore.node.OutgoingSocketThread( 3281): Now accepting connections...
,I/jxcore-log( 3281): 2016-01-05T00:47:33.957Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3281): 
,I/jxcore-log( 3281): 2016-01-05T00:47:33.981Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3281): 
,I/jxcore-log( 3281): 2016-01-05T00:47:34.030Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3281): 
,I/io.jxcore.node.ConnectionHelper( 3281): onListeningForIncomingConnections: Outgoing connection is using port 47982 (peer ID: 7C:F9:0E:51:18:22)
I/jxcore-log( 3281): 2016-01-05T00:47:34.038Z SendDataConnector.js: CLIENT connected to 47982, error: null
I/jxcore-log( 3281): 
I/jxcore-log( 3281): 2016-01-05T00:47:34.039Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3281): 
,I/io.jxcore.node.OutgoingSocketThread( 3281): Incoming data from address: /127.0.0.1, port: 47982
D/io.jxcore.node.OutgoingSocketThread( 3281): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3281): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3281): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3281): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3281): Exiting thread (ID: 316)
,D/io.jxcore.node.StreamCopyingThread( 3281): Entering thread (ID: 317, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 3281): Entering thread (ID: 318, name: Receiver)
,I/jxcore-log( 3281): 2016-01-05T00:47:34.085Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3281): 
,I/jxcore-log( 3281): 2016-01-05T00:47:34.086Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3281): 
,I/jxcore-log( 3281): 2016-01-05T00:47:34.553Z SendDataTCPServer.js: TCP/IP server has received 55440 bytes of data
I/jxcore-log( 3281): 
,I/jxcore-log( 3281): 2016-01-05T00:47:34.588Z SendDataTCPServer.js: TCP/IP server has received 57420 bytes of data
I/jxcore-log( 3281): 
,I/jxcore-log( 3281): 2016-01-05T00:47:34.672Z SendDataTCPServer.js: TCP/IP server has received 59400 bytes of data
I/jxcore-log( 3281): 
,I/jxcore-log( 3281): 2016-01-05T00:47:34.796Z SendDataTCPServer.js: TCP/IP server has received 61380 bytes of data
I/jxcore-log( 3281): 
,I/jxcore-log( 3281): 2016-01-05T00:47:34.862Z SendDataTCPServer.js: TCP/IP server has received 63360 bytes of data
I/jxcore-log( 3281): 
,I/jxcore-log( 3281): 2016-01-05T00:47:34.893Z SendDataTCPServer.js: TCP/IP server has received 65340 bytes of data
I/jxcore-log( 3281): 
,I/jxcore-log( 3281): 2016-01-05T00:47:34.952Z SendDataTCPServer.js: TCP/IP server has received 67320 bytes of data
I/jxcore-log( 3281): 
,D/        ( 2110): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23716
,I/jxcore-log( 3281): 2016-01-05T00:47:35.005Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3281): 
I/jxcore-log( 3281): 2016-01-05T00:47:35.011Z SendDataTCPServer.js: TCP/IP server has received 69300 bytes of data
I/jxcore-log( 3281): 
,I/jxcore-log( 3281): 2016-01-05T00:47:35.029Z SendDataTCPServer.js: TCP/IP server has received 71280 bytes of data
I/jxcore-log( 3281): 
,I/jxcore-log( 3281): 2016-01-05T00:47:35.040Z SendDataTCPServer.js: TCP/IP server has received 73260 bytes of data
I/jxcore-log( 3281): 
,I/jxcore-log( 3281): 2016-01-05T00:47:35.077Z SendDataTCPServer.js: TCP/IP server has received 77220 bytes of data
I/jxcore-log( 3281): 
,I/jxcore-log( 3281): 2016-01-05T00:47:35.094Z SendDataTCPServer.js: TCP/IP server has received 79200 bytes of data
I/jxcore-log( 3281): 
,I/jxcore-log( 3281): 2016-01-05T00:47:35.106Z SendDataTCPServer.js: TCP/IP server has received 81180 bytes of data
I/jxcore-log( 3281): 
,I/jxcore-log( 3281): 2016-01-05T00:47:35.127Z SendDataTCPServer.js: TCP/IP server has received 83160 bytes of data
I/jxcore-log( 3281): 
,I/jxcore-log( 3281): 2016-01-05T00:47:35.133Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3281): 
,I/jxcore-log( 3281): 2016-01-05T00:47:35.147Z SendDataTCPServer.js: TCP/IP server has received 89100 bytes of data
I/jxcore-log( 3281): 
,I/jxcore-log( 3281): 2016-01-05T00:47:35.176Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log( 3281): 
,D/        ( 2110): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:13816
,I/jxcore-log( 3281): 2016-01-05T00:47:35.210Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3281): 
,I/jxcore-log( 3281): 2016-01-05T00:47:35.261Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 3281): 
,I/jxcore-log( 3281): 2016-01-05T00:47:35.297Z SendDataTCPServer.js: TCP/IP server has received 97020 bytes of data
I/jxcore-log( 3281): 
,I/jxcore-log( 3281): 2016-01-05T00:47:35.323Z SendDataTCPServer.js: TCP/IP server has received 99000 bytes of data
I/jxcore-log( 3281): 
,I/jxcore-log( 3281): 2016-01-05T00:47:35.347Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3281): 
,D/        ( 2110): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:3916
,I/jxcore-log( 3281): 2016-01-05T00:47:35.414Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3281): 
,W/bt-btif ( 2110): invalid rfc slot id: 5
,W/io.jxcore.node.StreamCopyingThread( 3281): Either failed to read from the output stream or write to the input stream (thread ID: 314, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 3281): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3281): onDisconnected: Incoming connection, peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3281): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 312
,D/io.jxcore.node.OutgoingSocketThread( 3281): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3281): doStop: Thread ID: 314
,D/io.jxcore.node.OutgoingSocketThread( 3281): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3281): doStop: Thread ID: 313
D/io.jxcore.node.OutgoingSocketThread( 3281): closeLocalSocketAndStreams: Closing...
,D/io.jxcore.node.OutgoingSocketThread( 3281): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3281): Either failed to read from the output stream or write to the input stream (thread ID: 313, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3281): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3281): onDisconnected: Incoming connection, peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 3281): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 3281): closeLocalSocketAndStreams: Closing the localhost socket...
,I/io.jxcore.node.OutgoingSocketThread( 3281): closeBluetoothSocketAndStreams
,D/io.jxcore.node.ConnectionHelper( 3281): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.ConnectionHelper( 3281): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3281): Exiting thread (ID: 313, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 3281): Exiting thread (ID: 314, name: Receiver)
,I/jxcore-log( 3281): 2016-01-05T00:47:35.523Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3281): 
,I/jxcore-log( 3281): 2016-01-05T00:47:36.312Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3281): 
,I/jxcore-log( 3281): 2016-01-05T00:47:36.527Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3281): 
,I/jxcore-log( 3281): 2016-01-05T00:47:36.592Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3281): 
,I/jxcore-log( 3281): 2016-01-05T00:47:36.660Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3281): 
,I/jxcore-log( 3281): 2016-01-05T00:47:36.751Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3281): 
I/jxcore-log( 3281): 2016-01-05T00:47:36.752Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3281): 
I/jxcore-log( 3281): oneRoundDownNow
I/jxcore-log( 3281): 
,I/jxcore-log( 3281): 2016-01-05T00:47:36.760Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3281): 
I/jxcore-log( 3281): 2016-01-05T00:47:36.761Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3281): 
D/io.jxcore.node.ConnectionHelper( 3281): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:51:18:22
I/io.jxcore.node.ConnectionHelper( 3281): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 7C:F9:0E:51:18:22
I/io.jxcore.node.OutgoingSocketThread( 3281): close
D/io.jxcore.node.OutgoingSocketThread( 3281): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3281): doStop: Thread ID: 318
D/io.jxcore.node.OutgoingSocketThread( 3281): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3281): doStop: Thread ID: 317
D/io.jxcore.node.OutgoingSocketThread( 3281): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 3281): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3281): Either failed to read from the output stream or write to the input stream (thread ID: 317, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3281): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3281): onDisconnected: Outgoing connection, peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 3281): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 3281): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3281): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3281): Either failed to read from the output stream or write to the input stream (thread ID: 318, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.OutgoingSocketThread( 3281): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3281): onDisconnected: Outgoing connection, peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3690] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3281): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3281): disconnectOutgoingConnection: Successfully disconnected (peer ID: 7C:F9:0E:51:18:22
,E/io.jxcore.node.ConnectionHelper( 3281): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:51:18:22
,D/io.jxcore.node.ConnectionHelper( 3281): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3281): Exiting thread (ID: 317, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 3281): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 3281): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3281): Exiting thread (ID: 318, name: Receiver)
,I/jxcore-log( 3281): 2016-01-05T00:47:36.802Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3281): 
I/jxcore-log( 3281): ---- round done--------
I/jxcore-log( 3281): 
I/jxcore-log( 3281): startWithNextDevice
I/jxcore-log( 3281): 
,W/bt-btif ( 2110): bta_jv_rfc_port_to_cb(port_handle:0xa):jv handle:0x0 not FOUND
,D/btif_config_util( 2110): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2110): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2110): onReceive
,D/BluetoothManagerService(  755): Message: 20
D/BluetoothManagerService(  755): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2c4b4011:true
,I/BTConnectionReceiver( 1321): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:51:18:22, alias=null, name=Thali Test (Galaxy A5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1321): Bluetooth Device Name: Thali Test (Galaxy A5)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3281): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3281): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3281): setState: RESTARTING
,I/wpa_supplicant( 1084): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1084): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 1084): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 1084): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant( 1084): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 1084): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3281): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3281): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3281): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3281): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3281): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3281): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3281): Start timer timeout, starting now...
,I/wpa_supplicant( 1084): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3281): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3281): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3281): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1084): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1084): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1084): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3281): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): onP2pDeviceListChanged: Peer 1: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3281): restart: Restarting...
,D/WifiP2pManager( 3281): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3281): Service request added successfully
,I/wpa_supplicant( 1084): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1084): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1084): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3281): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3281): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT6440","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3281): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3281): onServiceDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): modifyListOfDiscoveredPeers: Adding new peer: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
I/io.jxcore.node.ConnectionHelper( 3281): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440], Bluetooth address: B0:C5:59:3F:75:69, device name: , device address: ee:1f:72:18:8b:78
D/io.jxcore.node.ConnectionHelper( 3281): notifyPeerAvailability: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440] is available
I/jxcore-log( 3281): peerAvailabilityChanged [{"peerIdentifier":"B0:C5:59:3F:75:69","peerName":"samsung-SM-G900F_PT6440","peerAvailable":true}]
I/jxcore-log( 3281): 
I/jxcore-log( 3281): Found peer : samsung-SM-G900F_PT6440, Available: true
I/jxcore-log( 3281): 
I/jxcore-log( 3281): startWithNextDevice
I/jxcore-log( 3281): 
I/jxcore-log( 3281): device[2]: B0:C5:59:3F:75:69
I/jxcore-log( 3281): 
I/jxcore-log( 3281): 2016-01-05T00:48:15.592Z SendDataConnector.js: Start called with peer B0:C5:59:3F:75:69
I/jxcore-log( 3281): 
I/jxcore-log( 3281): 2016-01-05T00:48:15.593Z SendDataConnector.js: doConnect called with peer B0:C5:59:3F:75:69
I/jxcore-log( 3281): 
I/jxcore-log( 3281): 2016-01-05T00:48:15.593Z SendDataConnector.js: do connect now
I/jxcore-log( 3281): 
,I/io.jxcore.node.ConnectionHelper( 3281): connect: Trying to connect to peer with ID B0:C5:59:3F:75:69
,D/io.jxcore.node.ConnectionHelper( 3281): hasConnection: No connection with peer with ID B0:C5:59:3F:75:69
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3281): connect: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3281): connect: Trying to start connecting to null in address B0:C5:59:3F:75:69
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3281): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3281): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3281): onConnecting: null B0:C5:59:3F:75:69
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3281): connect: Started connecting to null in address B0:C5:59:3F:75:69
I/io.jxcore.node.ConnectionHelper( 3281): connect: Connection process successfully started (peer ID: B0:C5:59:3F:75:69)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3281): Trying to connect to peer with address B0:C5:59:3F:75:69 (thread ID: 319)
W/BluetoothAdapter( 3281): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2110): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2110): info:x10
,D/        ( 2110): remote version info [b0:c5:59:3f:75:69]: 7, f, 610c
,E/BluetoothRemoteDevices( 2110): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2110): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2110): bondStateChangeCallback: Status: 0 Address: B0:C5:59:3F:75:69 newState: 1
E/bt-btif ( 2110): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2110): Bond State Change Intent:B0:C5:59:3F:75:69 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2110): Entering PendingCommandState State
,W/BluetoothEventManager( 2740): CachedBluetoothDevice for device B0:C5:59:3F:75:69 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2740): Got bonding state changed for B0:C5:59:3F:75:69, but we have no record of that device.
,I/BluetoothBondStateMachine( 2110): bondStateChangeCallback: Status: 0 Address: B0:C5:59:3F:75:69 newState: 0
,D/BluetoothAdapterProperties( 2110): Failed to remove device: B0:C5:59:3F:75:69
,I/BluetoothBondStateMachine( 2110): Bond State Change Intent:B0:C5:59:3F:75:69 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2110): StableState(): Entering Off State
,W/BluetoothEventManager( 2740): CachedBluetoothDevice for device B0:C5:59:3F:75:69 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2740): Got bonding state changed for B0:C5:59:3F:75:69, but we have no record of that device.
,W/bt-btif ( 2110): new conn_srvc id:26, app_id:1
W/bt-btif ( 2110): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2110): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3281): onSocketConnected: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3281): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 319)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3281): onBytesWritten: 77 bytes successfully written (thread ID: 320)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3281): Outgoing connection initialized (*handshake* thread ID: 320)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3281): Exiting thread (thread ID: 319)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3281): Entering thread (ID: 320)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3281): onBytesRead: Read 82 bytes successfully (thread ID: 320)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3281): Handshake succeeded with [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3281): onHandshakeSucceeded: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3281): onConnected: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
I/io.jxcore.node.ConnectionHelper( 3281): onConnected: Outgoing connection to peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
D/io.jxcore.node.ConnectionHelper( 3281): hasConnection: No connection with peer with ID B0:C5:59:3F:75:69
W/io.jxcore.node.ConnectionHelper( 3281): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 3281): onConnected: Outgoing socket thread, for peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3281): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 3281): onConnected: The total number of connections is now 1
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3281): Exiting thread (ID: 320)
,D/io.jxcore.node.OutgoingSocketThread( 3281): Entering thread (ID: 321)
,D/io.jxcore.node.OutgoingSocketThread( 3281): Server socket local port: 35750
I/io.jxcore.node.OutgoingSocketThread( 3281): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3281): onListeningForIncomingConnections: Outgoing connection is using port 35750 (peer ID: B0:C5:59:3F:75:69)
I/jxcore-log( 3281): 2016-01-05T00:48:19.432Z SendDataConnector.js: CLIENT connected to 35750, error: null
I/jxcore-log( 3281): 
I/jxcore-log( 3281): 2016-01-05T00:48:19.433Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3281): 
,I/io.jxcore.node.OutgoingSocketThread( 3281): Incoming data from address: /127.0.0.1, port: 35750
D/io.jxcore.node.OutgoingSocketThread( 3281): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3281): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3281): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3281): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3281): Exiting thread (ID: 321)
,I/jxcore-log( 3281): 2016-01-05T00:48:19.457Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3281): 
,D/io.jxcore.node.StreamCopyingThread( 3281): Entering thread (ID: 323, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3281): Entering thread (ID: 322, name: Sender)
,I/jxcore-log( 3281): 2016-01-05T00:48:20.681Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3281): 
,I/jxcore-log( 3281): 2016-01-05T00:48:20.691Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3281): 
,I/jxcore-log( 3281): 2016-01-05T00:48:20.830Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3281): 
,I/jxcore-log( 3281): 2016-01-05T00:48:21.315Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3281): 
,I/jxcore-log( 3281): 2016-01-05T00:48:21.895Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3281): 
,I/jxcore-log( 3281): 2016-01-05T00:48:22.437Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3281): 
,I/jxcore-log( 3281): 2016-01-05T00:48:22.490Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3281): 
,I/jxcore-log( 3281): 2016-01-05T00:48:22.547Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3281): 
I/jxcore-log( 3281): 2016-01-05T00:48:22.548Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3281): 
,I/jxcore-log( 3281): oneRoundDownNow
I/jxcore-log( 3281): 
I/jxcore-log( 3281): 2016-01-05T00:48:22.550Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3281): 
I/jxcore-log( 3281): 2016-01-05T00:48:22.551Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3281): 
,D/io.jxcore.node.ConnectionHelper( 3281): disconnectOutgoingConnection: Trying to close connection to peer with ID B0:C5:59:3F:75:69
I/io.jxcore.node.ConnectionHelper( 3281): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: B0:C5:59:3F:75:69
I/io.jxcore.node.OutgoingSocketThread( 3281): close
D/io.jxcore.node.OutgoingSocketThread( 3281): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3281): doStop: Thread ID: 323
D/io.jxcore.node.OutgoingSocketThread( 3281): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3281): doStop: Thread ID: 322
D/io.jxcore.node.OutgoingSocketThread( 3281): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 3281): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3281): Either failed to read from the output stream or write to the input stream (thread ID: 322, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3281): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3281): onDisconnected: Outgoing connection, peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 3281): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 3281): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3281): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3281): Either failed to read from the output stream or write to the input stream (thread ID: 323, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 3281): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3281): onDisconnected: Outgoing connection, peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3281): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3281): disconnectOutgoingConnection: Successfully disconnected (peer ID: B0:C5:59:3F:75:69
,E/io.jxcore.node.ConnectionHelper( 3281): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID B0:C5:59:3F:75:69
D/io.jxcore.node.ConnectionHelper( 3281): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3281): Exiting thread (ID: 322, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 3281): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID B0:C5:59:3F:75:69
,D/io.jxcore.node.ConnectionHelper( 3281): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3281): Exiting thread (ID: 323, name: Receiver)
,I/jxcore-log( 3281): 2016-01-05T00:48:22.600Z SendDataConnector.js: Mobile.Disconnect() callback with peer B0:C5:59:3F:75:69
I/jxcore-log( 3281): 
I/jxcore-log( 3281): ---- round done--------
I/jxcore-log( 3281): 
I/jxcore-log( 3281): startWithNextDevice
I/jxcore-log( 3281): 
,W/bt-btif ( 2110): bta_jv_rfc_port_to_cb(port_handle:0xb):jv handle:0x0 not FOUND
,D/btif_config_util( 2110): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 2110): new conn_srvc id:26, app_id:255
W/bt-btif ( 2110): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2110): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3281): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3281): Incoming connection initialized (thread ID: 324)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3281): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3281): Entering thread (ID: 324)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3281): onBytesRead: Read 82 bytes successfully (thread ID: 324)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3281): Got valid identity from [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3281): onBytesWritten: 77 bytes successfully written (thread ID: 324)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3281): removeThreadFromList: Removing thread with ID 324
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3281): Handshake thread disposed (thread ID: 324)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3281): onIncomingConnectionConnected: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3281): Exiting thread (ID: 324)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3281): onConnected: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
,I/io.jxcore.node.ConnectionHelper( 3281): onConnected: Incoming connection to peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
D/io.jxcore.node.ConnectionHelper( 3281): hasConnection: No connection with peer with ID B0:C5:59:3F:75:69
W/io.jxcore.node.ConnectionHelper( 3281): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 3281): onConnected: Incoming socket thread, for peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440], created successfully
D/io.jxcore.node.ConnectionHelper( 3281): onConnected: The total number of connections is now 1
,D/io.jxcore.node.IncomingSocketThread( 3281): Entering thread (ID: 325)
,I/jxcore-log( 3281): 2016-01-05T00:48:25.604Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3281): 
,I/io.jxcore.node.IncomingSocketThread( 3281): Local host address: localhost/127.0.0.1, port: 41887
D/io.jxcore.node.IncomingSocketThread( 3281): Setting local streams and starting stream copying threads...
,I/io.jxcore.node.StreamCopyingThread( 3281): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 3281): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.IncomingSocketThread( 3281): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3281): Exiting thread (ID: 325)
,D/io.jxcore.node.StreamCopyingThread( 3281): Entering thread (ID: 327, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3281): Entering thread (ID: 326, name: Sender)
,I/jxcore-log( 3281): 2016-01-05T00:48:26.713Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3281): 
,I/jxcore-log( 3281): 2016-01-05T00:48:26.724Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3281): 
,I/jxcore-log( 3281): 2016-01-05T00:48:26.733Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3281): 
,I/jxcore-log( 3281): 2016-01-05T00:48:26.739Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3281): 
,I/jxcore-log( 3281): 2016-01-05T00:48:26.749Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3281): 
,I/jxcore-log( 3281): 2016-01-05T00:48:26.760Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3281): 
,I/jxcore-log( 3281): 2016-01-05T00:48:26.796Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3281): 
,I/jxcore-log( 3281): 2016-01-05T00:48:26.821Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3281): 
,I/jxcore-log( 3281): 2016-01-05T00:48:26.841Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3281): 
,I/jxcore-log( 3281): 2016-01-05T00:48:26.876Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3281): 
,I/jxcore-log( 3281): 2016-01-05T00:48:26.908Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3281): 
,I/jxcore-log( 3281): 2016-01-05T00:48:26.912Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3281): 
,I/jxcore-log( 3281): 2016-01-05T00:48:26.915Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3281): 
,I/jxcore-log( 3281): 2016-01-05T00:48:26.946Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3281): 
,I/jxcore-log( 3281): 2016-01-05T00:48:26.956Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 3281): 
,I/jxcore-log( 3281): 2016-01-05T00:48:26.998Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 3281): 
,I/jxcore-log( 3281): 2016-01-05T00:48:27.026Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3281): 
,I/jxcore-log( 3281): 2016-01-05T00:48:27.072Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3281): 
,I/jxcore-log( 3281): 2016-01-05T00:48:27.090Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3281): 
,I/jxcore-log( 3281): 2016-01-05T00:48:27.141Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3281): 
,I/jxcore-log( 3281): 2016-01-05T00:48:27.178Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 3281): 
,I/jxcore-log( 3281): 2016-01-05T00:48:27.203Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3281): 
,I/jxcore-log( 3281): 2016-01-05T00:48:27.207Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3281): 
,I/jxcore-log( 3281): 2016-01-05T00:48:27.229Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3281): 
,I/jxcore-log( 3281): 2016-01-05T00:48:27.274Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 3281): 
,I/jxcore-log( 3281): 2016-01-05T00:48:27.303Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3281): 
,I/jxcore-log( 3281): 2016-01-05T00:48:27.313Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3281): 
,I/jxcore-log( 3281): 2016-01-05T00:48:27.358Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 3281): 
,I/jxcore-log( 3281): 2016-01-05T00:48:27.500Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 3281): 
,I/jxcore-log( 3281): 2016-01-05T00:48:27.512Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3281): 
,I/jxcore-log( 3281): 2016-01-05T00:48:27.569Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 3281): 
,I/jxcore-log( 3281): 2016-01-05T00:48:27.608Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 3281): 
,I/jxcore-log( 3281): 2016-01-05T00:48:27.671Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data
I/jxcore-log( 3281): 
,I/jxcore-log( 3281): 2016-01-05T00:48:27.731Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3281): 
,W/bt-btif ( 2110): invalid rfc slot id: 6
,W/io.jxcore.node.StreamCopyingThread( 3281): Either failed to read from the output stream or write to the input stream (thread ID: 327, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 3281): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3281): onDisconnected: Incoming connection, peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3281): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 325
D/io.jxcore.node.IncomingSocketThread( 3281): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3281): doStop: Thread ID: 327
D/io.jxcore.node.IncomingSocketThread( 3281): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3281): doStop: Thread ID: 326
D/io.jxcore.node.IncomingSocketThread( 3281): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 3281): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3281): Either failed to read from the output stream or write to the input stream (thread ID: 326, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3281): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3281): onDisconnected: Incoming connection, peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.IncomingSocketThread( 3281): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 3281): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3281): closeBluetoothSocketAndStreams
,D/io.jxcore.node.ConnectionHelper( 3281): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.ConnectionHelper( 3281): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3281): Exiting thread (ID: 326, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 3281): Exiting thread (ID: 327, name: Receiver)
,I/jxcore-log( 3281): 2016-01-05T00:48:27.889Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3281): 
,W/bt-rfcomm( 2110): rfc_find_lcid_mcb LCID reused LCID:0x46 current:0x0
W/bt-rfcomm( 2110): RFCOMM_DisconnectInd LCID:0x46
,E/bt-btm  ( 2110): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2110): onReceive
,I/BTConnectionReceiver( 1321): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1321): Bluetooth Device Name: Thali Test (Galaxy S5)
,I/ActivityManager(  755): Killing 2590:com.google.android.gm/u0a70 (adj 15): empty #17
,W/libprocessgroup(  755): failed to open /acct/uid_10070/pid_2590/cgroup.procs: No such file or directory
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3281): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3281): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3281): setState: RESTARTING
,I/wpa_supplicant( 1084): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1084): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3281): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3281): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3281): Start timer timeout, starting now...
,I/wpa_supplicant( 1084): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3281): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3281): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3281): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1084): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1084): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1084): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3281): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3281): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3281): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3281): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3281): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3281): Service request added successfully
,I/wpa_supplicant( 1084): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1084): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1084): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3281): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3281): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3281): Service discovery started successfully
,I/wpa_supplicant( 1084): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1084): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3281): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3281): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6753","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3281): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3281): onServiceDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753]
I/io.jxcore.node.ConnectionHelper( 3281): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
W/io.jxcore.node.ConnectionHelper( 3281): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6753] already in the list, will not add again
,I/jxcore-log( 3281): timeout now
I/jxcore-log( 3281): 
I/jxcore-log( 3281): weAreDoneNow, resultArray.length: 2
I/jxcore-log( 3281): 
I/jxcore-log( 3281): sendReportNow
I/jxcore-log( 3281): 
I/jxcore-log( 3281): done, now sending data to server
I/jxcore-log( 3281): 
,I/jxcore-log( 3281): 2016-01-05T00:49:03.696Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3281): 
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): checkListForExpiredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): modifyListOfDiscoveredPeers: Removed [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
I/io.jxcore.node.ConnectionHelper( 3281): onPeerLost: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440]
D/io.jxcore.node.ConnectionHelper( 3281): hasConnection: No connection with peer with ID B0:C5:59:3F:75:69
D/io.jxcore.node.ConnectionHelper( 3281): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440] removed
D/io.jxcore.node.ConnectionHelper( 3281): notifyPeerAvailability: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6440] not available
I/jxcore-log( 3281): peerAvailabilityChanged [{"peerIdentifier":"B0:C5:59:3F:75:69","peerName":"samsung-SM-G900F_PT6440","peerAvailable":false}]
I/jxcore-log( 3281): 
I/jxcore-log( 3281): startWithNextDevice
I/jxcore-log( 3281): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3281): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3281): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3281): setState: RESTARTING
,I/wpa_supplicant( 1084): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1084): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 1084): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant( 1084): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 1084): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 1084): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 1084): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3281): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3281): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3281): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3281): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3281): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3281): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3281): onP2pDeviceListChanged: 0 device(s) discovered
,I/jxcore-log( 3281): teardown
I/jxcore-log( 3281): 
,I/jxcore-log( 3281): testSendData stopped
I/jxcore-log( 3281): 
I/io.jxcore.node.ConnectionHelper( 3281): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3281): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3281): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3281): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3281): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3281): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3281): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3281): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3281): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3281): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3281): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3281): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3281): release: No more listeners, de-initializing...
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3281): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3281): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3281): setState: NOT_STARTED
,I/jxcore-log( 3281): StopBroadcasting went ok
I/jxcore-log( 3281): 
,I/jxcore-log( 3281): 2016-01-05T00:49:24.060Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
I/jxcore-log( 3281): 
,I/chromium( 3281): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/io.jxcore.node.ConnectionHelper( 3281): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3281): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3281): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3281): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 3281): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 3281): ****TEST TOOK:  ms ****
I/jxcore-log( 3281): 
I/jxcore-log( 3281): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3281): 
,D/AndroidRuntime( 3628): 
D/AndroidRuntime( 3628): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 3628): CheckJNI is OFF
,D/AndroidRuntime( 3628): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  755): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
,I/ActivityManager(  755): Killing 3281:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
,I/WindowState(  755): WIN DEATH: Window{1f1812a6 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  755): Client connection lost with reason: 4
,W/PackageSettings(  755): Skipping PackageSetting{21bbf3ea com.example.hello/10278} due to missing metadata
,I/ActivityManager(  755):   Force finishing activity ActivityRecord{1fce3d2 u0 com.test.thalitest/.MainActivity t214}
,W/ActivityManager(  755): Spurious death for ProcessRecord{27b5a576 3281:com.test.thalitest/u0a270}, curProc for 3281: null
,I/ActivityManager(  755): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
,I/art     ( 1321): Explicit concurrent mark sweep GC freed 16134(877KB) AllocSpace objects, 2(32KB) LOS objects, 25% free, 19MB/25MB, paused 308us total 33.657ms
,I/art     ( 1600): Explicit concurrent mark sweep GC freed 12010(574KB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 22MB/30MB, paused 439us total 38.906ms
,I/art     ( 1241): Explicit concurrent mark sweep GC freed 3961(294KB) AllocSpace objects, 1(126KB) LOS objects, 38% free, 25MB/41MB, paused 4.011ms total 24.947ms
I/InputReader(  755): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 1569): Ignoring removeGeofence because network location is disabled.
I/Keyboard.Facilitator( 1078): resetDictionaries() : en_US
,I/Keyboard.Facilitator.DecoderInitializer( 1078): run()
,I/art     (  755): Explicit concurrent mark sweep GC freed 31039(1665KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 1.196ms total 70.448ms
,I/Decoder ( 1078): createOrResetDecoder
,D/VoicemailCleanupService( 2936): Cleaning up data for package: com.test.thalitest
,W/Launcher( 1241): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@3612d9b7 new=com.google.android.velvet.VelvetApplication@3612d9b7
I/UpdateIcingCorporaServi( 1321): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/Adreno-EGL(  949): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/OpenGLRenderer(  949): Initialized EGL, version 1.4
I/ActivityManager(  755): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3666 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,D/OpenGLRenderer(  949): Enabling debug mode 0
,I/ConfigService( 1569): onCreate
,D/BackupManagerService(  755): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  755): Receieved: android.intent.action.PACKAGE_REMOVED
,W/InputMethodManagerService(  755): Focus gain on non-focused client com.android.internal.view.IInputMethodClient$Stub$Proxy@25c8b836 (uid=10034 pid=949)
,D/TaskPersister(  755): removeObsoleteFile: deleting file=214_task.xml
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1078): run()
,I/UpdateIcingCorporaServi( 1321): UpdateCorporaTask done [took 109 ms] updated apps [took 109 ms] 
,W/ContextImpl( 3666): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
,D/PackageBroadcastService( 1600): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1600): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 1600): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1600): Module APK com.google.android.play.games already loaded
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1078): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1078): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1078): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1078): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1078): run() : Loading LM = history
,D/ChimeraCfgMgr( 1600): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1600): Module APK com.google.android.play.games already loaded
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1078): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1078): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1078): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1078): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1078): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1078): run()
I/StatsUtilsManager( 1078): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1078): shouldRecordStats() = Too Soon
,I/LocationSettingsChecker( 1600): Removing dialog suppression flag for package com.test.thalitest
,E/NetworkScheduler.SchedulerReceiver( 1569): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1569): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,W/InputMethodManagerService(  755): Got RemoteException sending setActive(false) notification to pid 3281 uid 10270
,I/Keyboard.Facilitator( 1078): onFinishInput()
,D/gH_CompatibleDatabase( 1600): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,D/gH_CompatibleDatabase( 1600): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1600): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1600): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/gH_CompatibleDatabase( 1600): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
,D/gH_CompatibleDatabase( 1600): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/gH_CompatibleDatabase( 1600): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,I/art     (  755): Explicit concurrent mark sweep GC freed 10145(497KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 1.974ms total 223.549ms
,D/gH_CompatibleDatabase( 1600): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
,D/gH_CompatibleDatabase( 1600): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 1600): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1600): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1600): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1600): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/ActivityManager(  755): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3701 uid=10039 gids={50039, 9997} abi=armeabi-v7a
,I/Launcher( 1241): Deferring update until onResume
,I/GMPM-SVC( 1600): App measurement is starting up, version: 8489
I/GMPM-SVC( 1600): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
W/BaseAppContext( 1600): Using Auth Proxy for data requests.
,W/ResourcesManager( 1241): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/BaseAppContext( 1600): Using Auth Proxy for data requests.
,W/ResourcesManager( 1241): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/AndroidRuntime( 3628): Shutting down VM
,I/Icing   ( 1600): doRemovePackageData com.test.thalitest
,I/Launcher( 1241): Deferring update until onResume
,I/ActivityManager(  755): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3726 uid=10007 gids={50007, 9997, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  755): Killing 2007:com.google.android.calendar/u0a31 (adj 15): empty #17
,W/libprocessgroup(  755): failed to open /acct/uid_10031/pid_2007/cgroup.procs: No such file or directory
,I/ActivityManager(  755): Killing 3073:com.google.android.gms:car/u0a8 (adj 15): empty #17
,W/libprocessgroup(  755): failed to open /acct/uid_10008/pid_3073/cgroup.procs: No such file or directory
,D/ExternalStorage( 3726): After updating volumes, found 1 active roots
,W/ResourcesManager( 3202): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 3202): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/Documents( 3701): Update found 7 roots in 336ms
,D/Documents( 3701): Update found 7 roots in 166ms

```
