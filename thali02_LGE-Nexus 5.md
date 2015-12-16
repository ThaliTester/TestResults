#### Test 50650278b44f053_thali02_LGE-Nexus 5 Logs


```
--------- beginning of system
E/ActivityThread( 3042): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@3af6ee36 that was originally bound here
E/ActivityThread( 3042): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@3af6ee36 that was originally bound here
E/ActivityThread( 3042): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3042): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3042): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3042): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3042): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3042): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3042): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3042): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 3042): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 3042): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 3042): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 3042): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 3042): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2758)
E/ActivityThread( 3042): 	at android.app.ActivityThread.access$1900(ActivityThread.java:144)
E/ActivityThread( 3042): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
E/ActivityThread( 3042): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3042): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3042): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3042): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3042): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3042): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3042): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
W/ActivityManager(  734): Unbind failed: could not find connection for android.os.BinderProxy@10e0b2c7
--------- beginning of main
I/GAv4    ( 3162): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3162):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3162):   adb logcat -s GAv4
D/ChimeraCfgMgr( 1645): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1645): Module APK com.google.android.play.games already loaded
W/GAv4    ( 3162): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3162): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3162): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 3162): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
D/Finsky  ( 2662): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
W/ResourcesManager( 3162): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3162): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  734): Killing 2095:com.google.android.deskclock/u0a38 (adj 15): empty #17
V/JNIHelp ( 3162): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/libprocessgroup(  734): failed to open /acct/uid_10038/pid_2095/cgroup.procs: No such file or directory
W/System  ( 3162): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3162): Installed default security provider GmsCore_OpenSSL
V/GLSActivity( 1599): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 1645): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/Icing   ( 1645): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1645): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/Icing   ( 1645): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
,D/AndroidRuntime( 3217): 
D/AndroidRuntime( 3217): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3217): CheckJNI is OFF
D/AndroidRuntime( 3217): Calling main entry com.android.commands.am.Am
I/ActivityManager(  734): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  734): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3241 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3217): Shutting down VM
V/ActivityManager(  734): Display changed displayId=0
I/ActivityManager(  734): Killing 2632:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
W/libprocessgroup(  734): failed to open /acct/uid_10069/pid_2632/cgroup.procs: No such file or directory
I/WebViewFactory( 3241): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3241): Time to load native libraries: 1 ms (timestamps 887-888)
I/LibraryLoader( 3241): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3241): Binding Chromium to main looper Looper (main, tid 1) {1ebddb76}
I/LibraryLoader( 3241): Expected native library version number "",actual native library version number ""
I/chromium( 3241): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3241): Initializing chromium process, singleProcess=true
W/art     ( 3241): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3241): ApplicationContext is null in ApplicationStatus
W/chromium( 3241): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3241): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3241): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3241): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  734): Message: 20
D/BluetoothManagerService(  734): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2f510289:true
,W/art     ( 3241): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3241): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3241): CordovaWebView is running on device made by: LGE
,W/art     ( 3241): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3241): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3241): Render dirty regions requested: true
,D/Atlas   ( 3241): Validating map...
,W/chromium( 3241): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3241): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3241): Enabling debug mode 0
,W/IInputConnectionWrapper( 3241): showStatusIcon on inactive InputConnection
,I/ActivityManager(  734): Displayed com.test.thalitest/.MainActivity: +418ms (total +59s377ms)
,W/BindingManager( 3241): Cannot call determinedVisibility() - never saw a connection for the pid: 3241
,D/JsMessageQueue( 3241): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3241): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257332480
D/JX-Cordova( 3241): jxcore cordova android initializing
,W/jxcore-log( 3241): Initializing JXcore engine
,W/jxcore-log( 3241): JXcore engine is ready
W/jxcore-log( 3241): Starting JXcore engine
,W/.test.thalitest( 3241): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[7792]" dev="sockfs" ino=7792 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3241): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 3241): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6775]" dev="sockfs" ino=6775 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3241): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[20315]" dev="sockfs" ino=20315 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3241): Platform android
W/jxcore-log( 3241): 
W/jxcore-log( 3241): Process ARCH arm
W/jxcore-log( 3241): 
,I/jxcore-log( 3241): JXcore Cordova bridge is ready!
I/jxcore-log( 3241): 
,W/jxcore-log( 3241): JXcore engine is started
I/chromium( 3241): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3241): Toggling radios to true
I/jxcore-log( 3241): 
,D/BluetoothAdapter( 3241): enable(): BT is already enabled..!
,D/WifiService(  734): New client listening to asynchronous messages
,D/WifiService(  734): setWifiEnabled: true pid=3241, uid=10270
E/WifiService(  734): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3241): Radios toggled
I/jxcore-log( 3241): 
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 3241): Got Device Bluetooth address: 34:FC:EF:11:AE:67
I/jxcore-log( 3241): 
I/jxcore-log( 3241): Perf Test app loaded loaded
I/jxcore-log( 3241): 
,I/wpa_supplicant(  983): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  734): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  734): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
I/jxcore-log( 3241): check test folder
I/jxcore-log( 3241): 
E/native  (  734): do suspend true
I/jxcore-log( 3241): found test : ./testFindPeers.js
I/jxcore-log( 3241): 
,D/CommandListener(  181): Clearing all IP addresses on wlan0
,I/jxcore-log( 3241): found test : ./testSendData.js
I/jxcore-log( 3241): 
,V/NativeCrypto( 1599): Read error: ssl=0xaf32de00: I/O error during system call, Connection timed out
V/NativeCrypto( 1599): SSL shutdown failed: ssl=0xaf32de00: I/O error during system call, Broken pipe
,D/ConnectivityService(  734): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): ValidatedState{ when=-6ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): DefaultState{ when=-6ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): Forcing reevaluation
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
E/WifiConfigStore(  734): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  734): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  734): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,E/WifiStateMachine(  734): Start Disconnecting Watchdog 1
,I/wpa_supplicant(  983): wlan0: CTRL-EVENT-SCAN-STARTED 
E/native  (  734): do suspend true
,D/CommandListener(  181): Clearing all IP addresses on wlan0
,D/ConnectivityService(  734): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityManager.CallbackHandler(  886): CM callback handler got msg 524292
D/Nat464Xlat(  734): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  734): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,D/ConnectivityManager.CallbackHandler( 1645): CM callback handler got msg 524292
D/ConnectivityService(  734): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  734): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): Disconnected - quitting
,D/ConnectivityService(  734): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1275): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/chromium( 3241): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/WifiNetworkAgent(  734): NetworkAgent: NetworkAgent channel lost
,I/wpa_supplicant(  983): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant(  983): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant(  983): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant(  983): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  734): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  734): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  734): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  734): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  181): Setting iface cfg
,E/WifiStateMachine(  734): Start Dhcp Watchdog 2
,E/native  (  734): do suspend false
,E/WifiStateMachine(  734): scanCount==0 - aborting
,I/dhcpcd  ( 3362): version 5.5.6 starting
E/dhcpcd  ( 3362): get_duid: Read-only file system
,I/dhcpcd  ( 3362): wlan0: rebinding lease of 192.168.1.114
,I/dhcpcd  ( 3362): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3362): wlan0: leased 192.168.1.114 for 86400 seconds
,E/native  (  734): do suspend true
,D/ConnectivityService(  734): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  734): Adding iface wlan0 to network 101
,E/ConnectivityService(  734): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  734): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  734): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
E/WifiStateMachine(  734): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/ConnectivityService(  734): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/ConnectivityService(  734): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  734): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  734): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  734): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): DefaultState{ when=-2ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/ConnectivityService(  734): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  734):    accepting network in place of null
,D/CSLegacyTypeTracker(  734): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  734): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/ConnectivityService(  734): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  734): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  886): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1645): CM callback handler got msg 524290
,D/Nat464Xlat(  734): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  734): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  886): CM callback handler got msg 524295
D/ConnectivityManager.CallbackHandler( 1645): CM callback handler got msg 524295
,D/ConnectivityService(  734): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  734): MasterInitialState.processMessage what=3
,D/ConnectivityService(  734): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  734): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2775): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2775): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 2775): type=WIFI subType= reason=null isConnected=true
,E/GpsLocationProvider(  734): No APN found to select.
,E/GpsLocationProvider(  734): No APN found to select.
,I/SystemUpdateService( 1645): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1645): onCreate
,D/SystemUpdateService( 1645): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1645): active receiver: enabled
,I/SystemUpdateService( 1645): showing system update notification
,I/ValidateNoPeople(  734): skipping global notification
,V/SystemUpdateService( 1645): retry (wakeup: false) in 3599982 ms
,I/ActivityManager(  734): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3430 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/SystemUpdateService( 1645): onDestroy
,D/ConnectivityService(  734): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/GAv4    ( 3430): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3430):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3430):   adb logcat -s GAv4
,W/GAv4    ( 3430): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3430): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3430): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 3430): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3430): Time to load native libraries: 2 ms (timestamps 7904-7906)
,I/LibraryLoader( 3430): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3430): Binding Chromium to main looper Looper (main, tid 1) {26eef2f8}
,I/LibraryLoader( 3430): Expected native library version number "",actual native library version number ""
,I/chromium( 3430): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3430): Initializing chromium process, singleProcess=true
,W/art     ( 3430): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3430): ApplicationContext is null in ApplicationStatus
,W/chromium( 3430): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3430): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3430): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3430): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/AudioManagerAndroid( 3430): Requires BLUETOOTH permission
,I/NSApplication( 3430): Starting up...
,I/ActivityManager(  734): Killing 2578:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,W/libprocessgroup(  734): failed to open /acct/uid_10045/pid_2578/cgroup.procs: No such file or directory
,V/MusicLeanback( 2775): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1645): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1645): onCreate
,D/SystemUpdateService( 1645): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1645): active receiver: enabled
,I/SystemUpdateService( 1645): showing system update notification
,I/ValidateNoPeople(  734): skipping global notification
,V/SystemUpdateService( 1645): retry (wakeup: false) in 3599976 ms
,D/SystemUpdateService( 1645): onDestroy
,I/jxcore-log( 3241): BLE advertisement not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 3241): 
,D/ConnectivityService(  734): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  734): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2775): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2775): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1645): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1645): onCreate
,D/SystemUpdateService( 1645): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1645): active receiver: enabled
,I/SystemUpdateService( 1645): showing system update notification
,I/ValidateNoPeople(  734): skipping global notification
,E/GpsLocationProvider(  734): No APN found to select.
,V/SystemUpdateService( 1645): retry (wakeup: false) in 3599991 ms
,D/SystemUpdateService( 1645): onDestroy
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): EvaluatingState{ when=-1ms what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 16 Dec 2015 17:42:26 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450287746115], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450287746095]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): Don't send network conditions - lacking user consent.
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): Validated
,D/ConnectivityService(  734): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  734): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  734): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  734): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  886): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1645): CM callback handler got msg 524290
,D/ConnectivityService(  734): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/TelephonyNetworkFactory( 1275): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/Finsky  ( 2662): [255] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 2662): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/art     (  734): Explicit concurrent mark sweep GC freed 48111(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 27MB/41MB, paused 1.074ms total 70.328ms
,V/GLSActivity( 1599): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1599): Vacuum at: now=1450287758963 tag=VacuumService
,I/PhenotypeConfigurator( 1599): Scheduling Phenotype for one-off execution 3549 seconds from now (1450287759286)
,D/GetConfigurationSnapshotOperation( 1599): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1599): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1599): Using platform SSLCertificateSocketFactory
,V/GLSActivity( 1599): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1599): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ClearcutLoggerApiImpl( 1599): disconnect managed GoogleApiClient
,I/ActivityManager(  734): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=3601 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,I/GAv4    ( 3601): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3601):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3601):   adb logcat -s GAv4
,W/GAv4    ( 3601): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3601): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3601): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  734): Killing 2752:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/libprocessgroup(  734): failed to open /acct/uid_10003/pid_2752/cgroup.procs: No such file or directory
,I/jxcore-log( 3241): Connected to the server!
I/jxcore-log( 3241): 
,I/chromium( 3241): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3241): --- start :testFindPeers.js---
I/jxcore-log( 3241): 
,I/jxcore-log( 3241): testFindPeers created [object Object]
I/jxcore-log( 3241): 
I/jxcore-log( 3241): serverPort is 8876
I/jxcore-log( 3241): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): setDiscoveryMode: Mode set to WIFI
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3241): start: Peer ID: 34:FC:EF:11:AE:67, peer name: LGE-Nexus 5_PT9467
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3241): bind: Binding a new listener
D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3241): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3241): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT9467","ra":"34:FC:EF:11:AE:67"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3241): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3241): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3241): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3241): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3241): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3241): start: OK
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): start: Peer ID: 34:FC:EF:11:AE:67, peer name: LGE-Nexus 5_PT9467
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3241): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT9467","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3241): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT9467","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3241): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT9467","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3241): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onIsDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3241): start: OK
I/jxcore-log( 3241): StartBroadcasting started ok
I/jxcore-log( 3241): 
I/chromium( 3241): [INFO:CONSOLE(63)] "logCallback --- start :testFindPeers.js---", source: file:///android_asset/www/js/thali_main.js (63)
I/io.jxcore.node.ConnectionHelper( 3241): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3241): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3241): onDiscoveryManagerStateChanged: RUNNING
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3241): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service request added successfully
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): restart: Restarting...
,I/wpa_supplicant(  983): P2P-FIND-STOPPED 
,I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): Start timer timeout, starting now...
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  983): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: Note3-1 ea:50:8b:de:28:a3
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: Note3-1 ea:50:8b:de:28:a3
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/WifiP2pManager( 3241): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service request added successfully
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: Note3-1 ea:50:8b:de:28:a3
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service discovery started successfully
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  983): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: Note3-1 ea:50:8b:de:28:a3
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 4 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: Note3-1 ea:50:8b:de:28:a3
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT4268","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
I/io.jxcore.node.ConnectionHelper( 3241): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
D/io.jxcore.node.ConnectionHelper( 3241): notifyPeerAvailability: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268] is available
,I/jxcore-log( 3241): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:3C:51","peerName":"LGE-LG-H815_PT4268","peerAvailable":true}]
I/jxcore-log( 3241): 
I/jxcore-log( 3241): Found peer : F8:95:C7:87:3C:51, peerAvailable: true
I/jxcore-log( 3241): 
I/jxcore-log( 3241): weAreDoneNow
I/jxcore-log( 3241): 
,I/jxcore-log( 3241): done, now sending data to server
I/jxcore-log( 3241): 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: Note3-1 ea:50:8b:de:28:a3
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: Note3-1 ea:50:8b:de:28:a3
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): restart: Restarting...
,D/WifiP2pManager( 3241): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service request added successfully
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant(  983): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 6: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 8: Note3-1 ea:50:8b:de:28:a3
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 6: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 8: Note3-1 ea:50:8b:de:28:a3
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service discovery started successfully
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 9: Note3-1 ea:50:8b:de:28:a3
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): Got discovery timeout, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): restart: Restarting...
,I/wpa_supplicant(  983): P2P-FIND-STOPPED 
,I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): Start timer timeout, starting now...
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  983): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
,D/WifiP2pManager( 3241): Ignored { when=-6ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service request added successfully
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service discovery started successfully
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  983): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 3 device(s) discovered,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT8254","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onServiceDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Adding new peer: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254]
I/io.jxcore.node.ConnectionHelper( 3241): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
D/io.jxcore.node.ConnectionHelper( 3241): notifyPeerAvailability: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254] is available
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): restart: Restarting...
,D/WifiP2pManager( 3241): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service request added successfully
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254]
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service discovery started successfully
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT2838","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838]
I/io.jxcore.node.ConnectionHelper( 3241): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
D/io.jxcore.node.ConnectionHelper( 3241): notifyPeerAvailability: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838] is available
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): checkListForExpiredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268], add/update: false
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Removed [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
,I/io.jxcore.node.ConnectionHelper( 3241): onPeerLost: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
D/io.jxcore.node.ConnectionHelper( 3241): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268] removed
D/io.jxcore.node.ConnectionHelper( 3241): notifyPeerAvailability: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268] not available
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): restart: Restarting...
,I/wpa_supplicant(  983): P2P-FIND-STOPPED 
,I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): Start timer timeout, starting now...
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): restart: Restarting...
,D/WifiP2pManager( 3241): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service request added successfully
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service discovery started successfully
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT2451","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2451]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onServiceDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2451]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2451]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2451], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Adding new peer: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2451]
I/io.jxcore.node.ConnectionHelper( 3241): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2451], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 92:b6:86:43:73:1c
D/io.jxcore.node.ConnectionHelper( 3241): notifyPeerAvailability: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2451] is available
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): restart: Restarting...
,D/WifiP2pManager( 3241): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service request added successfully
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service discovery started successfully,
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): checkListForExpiredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838] expired
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): checkListForExpiredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Removed [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Removed [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254]
I/io.jxcore.node.ConnectionHelper( 3241): onPeerLost: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838]
D/io.jxcore.node.ConnectionHelper( 3241): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838] removed
D/io.jxcore.node.ConnectionHelper( 3241): notifyPeerAvailability: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838] not available
I/io.jxcore.node.ConnectionHelper( 3241): onPeerLost: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254]
D/io.jxcore.node.ConnectionHelper( 3241): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254] removed
,D/io.jxcore.node.ConnectionHelper( 3241): notifyPeerAvailability: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254] not available
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): restart: Restarting...
,I/wpa_supplicant(  983): P2P-FIND-STOPPED 
,I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): P2P device discovery started successfully
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  983): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2451], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2451]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 2 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2451], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2451]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
,D/WifiP2pManager( 3241): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service request added successfully
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  983): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2451], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2451]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2451], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2451]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: Android_608e 92:e7:c4:e6:4c:f8
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service discovery started successfully
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  983): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2451], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2451]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2451], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2451]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: Android_608e 92:e7:c4:e6:4c:f8
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT9108","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9108]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9108]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9108]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9108], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9108]
I/io.jxcore.node.ConnectionHelper( 3241): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9108], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
D/io.jxcore.node.ConnectionHelper( 3241): notifyPeerAvailability: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9108] is available
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT8771","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT8771]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8771]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8771]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8771], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT8771]
I/io.jxcore.node.ConnectionHelper( 3241): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8771], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
D/io.jxcore.node.ConnectionHelper( 3241): notifyPeerAvailability: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8771] is available
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT1538","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Resolved peer properties: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1538]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onServiceDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1538]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1538]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1538], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Adding new peer: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1538]
I/io.jxcore.node.ConnectionHelper( 3241): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1538], Bluetooth address: 90:E7:C4:F6:69:77, device name: Android_608e, device address: 92:e7:c4:e6:4c:f8
D/io.jxcore.node.ConnectionHelper( 3241): notifyPeerAvailability: Peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1538] is available
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9108], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9108]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1538], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1538]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2451], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2451]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8771], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8771]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT8254","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onServiceDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Adding new peer: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254]
,I/io.jxcore.node.ConnectionHelper( 3241): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
D/io.jxcore.node.ConnectionHelper( 3241): notifyPeerAvailability: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254] is available
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9108], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9108]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2451], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2451]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8771], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8771]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): restart: Restarting...
,D/WifiP2pManager( 3241): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service request added successfully
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service discovery started successfully
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  983): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9108], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9108]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2451], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2451]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2451], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2451]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Identity: "{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT9974","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Resolved peer properties: [44:80:EB:7B:5A:05 motorola-XT1072_PT9974]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onServiceDiscovered: [44:80:EB:7B:5A:05 motorola-XT1072_PT9974]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onPeerDiscovered: [44:80:EB:7B:5A:05 motorola-XT1072_PT9974]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 motorola-XT1072_PT9974], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Adding new peer: [44:80:EB:7B:5A:05 motorola-XT1072_PT9974]
I/io.jxcore.node.ConnectionHelper( 3241): onPeerDiscovered: [44:80:EB:7B:5A:05 motorola-XT1072_PT9974], Bluetooth address: 44:80:EB:7B:5A:05, device name: XT1072_23d5, device address: 44:80:eb:7b:5a:07
D/io.jxcore.node.ConnectionHelper( 3241): notifyPeerAvailability: Peer [44:80:EB:7B:5A:05 motorola-XT1072_PT9974] is available
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): restart: Restarting...
,I/wpa_supplicant(  983): P2P-FIND-STOPPED 
,I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): P2P device discovery started successfully
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): restart: Restarting...
,D/WifiP2pManager( 3241): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service request added successfully
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service discovery started successfully
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT9108","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9108]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9108]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9108]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9108], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9108]
I/io.jxcore.node.ConnectionHelper( 3241): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9108], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: , device address: ee:1f:72:63:11:86
W/io.jxcore.node.ConnectionHelper( 3241): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9108] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT9006","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9006]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9006]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9006]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9006], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9006]
I/io.jxcore.node.ConnectionHelper( 3241): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9006], Bluetooth address: 7C:F9:0E:51:18:22, device name: , device address: 7e:f9:0e:51:18:23
D/io.jxcore.node.ConnectionHelper( 3241): notifyPeerAvailability: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9006] is available
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT4249","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onServiceDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249]
I/io.jxcore.node.ConnectionHelper( 3241): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
D/io.jxcore.node.ConnectionHelper( 3241): notifyPeerAvailability: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249] is available
,I/ActivityManager(  734): Killing 2733:com.android.settings/1000 (adj 15): empty #17
,D/WifiService(  734): Client connection lost with reason: 4
,W/libprocessgroup(  734): failed to open /acct/uid_1000/pid_2733/cgroup.procs: No such file or directory
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT4268","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
I/io.jxcore.node.ConnectionHelper( 3241): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
D/io.jxcore.node.ConnectionHelper( 3241): notifyPeerAvailability: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268] is available
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT8854","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT8854]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT8854]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT8854]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT8854], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT8854]
,I/io.jxcore.node.ConnectionHelper( 3241): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT8854], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
D/io.jxcore.node.ConnectionHelper( 3241): notifyPeerAvailability: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT8854] is available
,D/WifiP2pManager( 3241): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service request added successfully
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  983): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 5 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT8854], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT8854]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9006], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9006]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT8854], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT8854]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service discovery started successfully
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT8854","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT8854]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT8854]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT8854]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT8854], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT8854]
I/io.jxcore.node.ConnectionHelper( 3241): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT8854], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper( 3241): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT8854] already in the list, will not add again
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): checkListForExpiredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254] expired
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): checkListForExpiredPeers: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2451] expired
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): checkListForExpiredPeers: Peer [44:80:EB:7B:5A:05 motorola-XT1072_PT9974] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Removed [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2451], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Removed [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2451]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 motorola-XT1072_PT9974], add/update: false
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Removed [44:80:EB:7B:5A:05 motorola-XT1072_PT9974]
I/io.jxcore.node.ConnectionHelper( 3241): onPeerLost: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254]
,D/io.jxcore.node.ConnectionHelper( 3241): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254] removed
D/io.jxcore.node.ConnectionHelper( 3241): notifyPeerAvailability: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254] not available
,I/io.jxcore.node.ConnectionHelper( 3241): onPeerLost: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2451]
,D/io.jxcore.node.ConnectionHelper( 3241): modifyListOfDiscoveredPeers: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2451] removed
D/io.jxcore.node.ConnectionHelper( 3241): notifyPeerAvailability: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2451] not available
,I/io.jxcore.node.ConnectionHelper( 3241): onPeerLost: [44:80:EB:7B:5A:05 motorola-XT1072_PT9974]
,D/io.jxcore.node.ConnectionHelper( 3241): modifyListOfDiscoveredPeers: Peer [44:80:EB:7B:5A:05 motorola-XT1072_PT9974] removed
D/io.jxcore.node.ConnectionHelper( 3241): notifyPeerAvailability: Peer [44:80:EB:7B:5A:05 motorola-XT1072_PT9974] not available
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): restart: Restarting...
,I/wpa_supplicant(  983): P2P-FIND-STOPPED 
,I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): P2P device discovery started successfully
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT8854], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT8854]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): restart: Restarting...
,D/WifiP2pManager( 3241): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service request added successfully
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT8854], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT8854]
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT2838","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838]
I/io.jxcore.node.ConnectionHelper( 3241): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
D/io.jxcore.node.ConnectionHelper( 3241): notifyPeerAvailability: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838] is available
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT8854], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT8854]
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT8854], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT8854]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): restart: Restarting...
,D/WifiP2pManager( 3241): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service discovery started successfully
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT8854], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT8854]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): restart: Restarting...
,D/WifiP2pManager( 3241): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service request added successfully
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT8854], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT8854]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service discovery started successfully
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT8854], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT8854]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT4268","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
I/io.jxcore.node.ConnectionHelper( 3241): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268], Bluetooth address: F8:95:C7:87:3C:51, device name: , device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3241): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT9006","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9006]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9006]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9006]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9006], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9006]
I/io.jxcore.node.ConnectionHelper( 3241): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9006], Bluetooth address: 7C:F9:0E:51:18:22, device name: , device address: 7e:f9:0e:51:18:23
W/io.jxcore.node.ConnectionHelper( 3241): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9006] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT8771","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT8771]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8771]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8771]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8771], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT8771]
,I/io.jxcore.node.ConnectionHelper( 3241): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8771], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 3241): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8771] already in the list, will not add again
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): checkListForExpiredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9108] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9108], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Removed [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9108]
I/io.jxcore.node.ConnectionHelper( 3241): onPeerLost: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9108]
D/io.jxcore.node.ConnectionHelper( 3241): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9108] removed
D/io.jxcore.node.ConnectionHelper( 3241): notifyPeerAvailability: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9108] not available
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT8854], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT8854]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9006], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9006]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8771], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8771]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): restart: Restarting...
,D/WifiP2pManager( 3241): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service request added successfully
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT8854], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT8854]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9006], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9006]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8771], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8771]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT4268","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
I/io.jxcore.node.ConnectionHelper( 3241): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3241): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT9006","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9006]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9006]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9006]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9006], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9006]
I/io.jxcore.node.ConnectionHelper( 3241): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9006], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
W/io.jxcore.node.ConnectionHelper( 3241): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9006] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT1538","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Resolved peer properties: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1538]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onServiceDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1538]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1538]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1538], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Adding new peer: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1538]
,I/io.jxcore.node.ConnectionHelper( 3241): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1538], Bluetooth address: 90:E7:C4:F6:69:77, device name: Android_608e, device address: 92:e7:c4:e6:4c:f8
W/io.jxcore.node.ConnectionHelper( 3241): modifyListOfDiscoveredPeers: Peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1538] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT8254","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onServiceDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Adding new peer: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254]
I/io.jxcore.node.ConnectionHelper( 3241): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
D/io.jxcore.node.ConnectionHelper( 3241): notifyPeerAvailability: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254] is available
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1538], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1538]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9006], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9006]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8771], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8771]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9006], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9006]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
,D/WifiP2pManager( 3241): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service discovery started successfully
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
,D/WifiP2pManager( 3241): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service discovery started successfully
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT2838","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838]
I/io.jxcore.node.ConnectionHelper( 3241): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 3241): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT2451","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2451]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onServiceDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2451]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2451]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2451], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Adding new peer: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2451]
I/io.jxcore.node.ConnectionHelper( 3241): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2451], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 92:b6:86:43:73:1c
D/io.jxcore.node.ConnectionHelper( 3241): notifyPeerAvailability: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2451] is available
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT4249","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onServiceDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249]
I/io.jxcore.node.ConnectionHelper( 3241): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249], Bluetooth address: 08:EC:A9:50:76:27, device name: , device address: 0a:ec:a9:50:76:28
W/io.jxcore.node.ConnectionHelper( 3241): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249] already in the list, will not add again
,I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838]
,D/WifiP2pManager( 3241): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service discovery started successfully
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: Note3-1 ea:50:8b:de:28:a3
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): checkListForExpiredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254] expired
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): checkListForExpiredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT8854] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Removed [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT8854], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Removed [58:3F:54:73:64:C0 LGE-LG-D855_PT8854]
I/io.jxcore.node.ConnectionHelper( 3241): onPeerLost: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254]
D/io.jxcore.node.ConnectionHelper( 3241): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254] removed
D/io.jxcore.node.ConnectionHelper( 3241): notifyPeerAvailability: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254] not available
,I/io.jxcore.node.ConnectionHelper( 3241): onPeerLost: [58:3F:54:73:64:C0 LGE-LG-D855_PT8854]
D/io.jxcore.node.ConnectionHelper( 3241): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT8854] removed
D/io.jxcore.node.ConnectionHelper( 3241): notifyPeerAvailability: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT8854] not available
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): restart: Restarting...
,I/wpa_supplicant(  983): P2P-FIND-STOPPED 
,I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): checkListForExpiredPeers: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2451] expired
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): checkListForExpiredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268] expired
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2451], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Removed [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2451]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Removed [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
I/io.jxcore.node.ConnectionHelper( 3241): onPeerLost: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2451]
,D/io.jxcore.node.ConnectionHelper( 3241): modifyListOfDiscoveredPeers: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2451] removed
D/io.jxcore.node.ConnectionHelper( 3241): notifyPeerAvailability: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2451] not available
I/io.jxcore.node.ConnectionHelper( 3241): onPeerLost: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
D/io.jxcore.node.ConnectionHelper( 3241): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268] removed
D/io.jxcore.node.ConnectionHelper( 3241): notifyPeerAvailability: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268] not available
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): Start timer timeout, starting now...
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): restart: Restarting...
,D/WifiP2pManager( 3241): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service request added successfully
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant(  983): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service discovery started successfully
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Identity: "{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT9974","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Resolved peer properties: [44:80:EB:7B:5A:05 motorola-XT1072_PT9974]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onServiceDiscovered: [44:80:EB:7B:5A:05 motorola-XT1072_PT9974]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onPeerDiscovered: [44:80:EB:7B:5A:05 motorola-XT1072_PT9974]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 motorola-XT1072_PT9974], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Adding new peer: [44:80:EB:7B:5A:05 motorola-XT1072_PT9974]
I/io.jxcore.node.ConnectionHelper( 3241): onPeerDiscovered: [44:80:EB:7B:5A:05 motorola-XT1072_PT9974], Bluetooth address: 44:80:EB:7B:5A:05, device name: XT1072_23d5, device address: 44:80:eb:7b:5a:07
D/io.jxcore.node.ConnectionHelper( 3241): notifyPeerAvailability: Peer [44:80:EB:7B:5A:05 motorola-XT1072_PT9974] is available
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): checkListForExpiredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Removed [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838]
I/io.jxcore.node.ConnectionHelper( 3241): onPeerLost: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838]
,D/io.jxcore.node.ConnectionHelper( 3241): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838] removed
D/io.jxcore.node.ConnectionHelper( 3241): notifyPeerAvailability: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838] not available
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): restart: Restarting...
,I/wpa_supplicant(  983): P2P-FIND-STOPPED 
,I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): P2P device discovery started successfully
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): restart: Restarting...
,D/WifiP2pManager( 3241): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service request added successfully
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  983): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service discovery started successfully
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  983): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT4249","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onServiceDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249]
I/io.jxcore.node.ConnectionHelper( 3241): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
W/io.jxcore.node.ConnectionHelper( 3241): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): Got discovery timeout, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): restart: Restarting...
,I/wpa_supplicant(  983): P2P-FIND-STOPPED 
,I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): Start timer timeout, starting now...
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  983): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3241): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service request added successfully
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service discovery started successfully
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  983): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  983): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT6856","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6856]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6856]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6856]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6856], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6856]
I/io.jxcore.node.ConnectionHelper( 3241): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6856], Bluetooth address: 08:EC:A9:50:75:41, device name: , device address: 0a:ec:a9:50:75:42
D/io.jxcore.node.ConnectionHelper( 3241): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6856] is available
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): checkListForExpiredPeers: Peer [44:80:EB:7B:5A:05 motorola-XT1072_PT9974] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 motorola-XT1072_PT9974], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Removed [44:80:EB:7B:5A:05 motorola-XT1072_PT9974]
I/io.jxcore.node.ConnectionHelper( 3241): onPeerLost: [44:80:EB:7B:5A:05 motorola-XT1072_PT9974]
D/io.jxcore.node.ConnectionHelper( 3241): modifyListOfDiscoveredPeers: Peer [44:80:EB:7B:5A:05 motorola-XT1072_PT9974] removed
D/io.jxcore.node.ConnectionHelper( 3241): notifyPeerAvailability: Peer [44:80:EB:7B:5A:05 motorola-XT1072_PT9974] not available
,W/bt-smp  ( 2125): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2125): Plain text(LSB ~ MSB) = ce 51 6e 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2125): Encrypted text(LSB ~ MSB) = 89 35 f5 d3 1a 8f 1d 7b a8 a4 c2 30 89 3e 7c 9a 
,W/bt-btm  ( 2125): Stopping oneshot timer
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): restart: Restarting...
,I/wpa_supplicant(  983): P2P-FIND-STOPPED 
,I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): Start timer timeout, starting now...
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): checkListForExpiredPeers: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Removed [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249]
I/io.jxcore.node.ConnectionHelper( 3241): onPeerLost: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249]
D/io.jxcore.node.ConnectionHelper( 3241): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249] removed
D/io.jxcore.node.ConnectionHelper( 3241): notifyPeerAvailability: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249] not available
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  983): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: Note3-1 ea:50:8b:de:28:a3
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: Android_50a5 fa:cf:c5:d9:e5:62
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: Note3-1 ea:50:8b:de:28:a3
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: Android_50a5 fa:cf:c5:d9:e5:62
,D/WifiP2pManager( 3241): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service request added successfully
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: Note3-1 ea:50:8b:de:28:a3
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: Android_50a5 fa:cf:c5:d9:e5:62
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: Note3-1 ea:50:8b:de:28:a3
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: Android_50a5 fa:cf:c5:d9:e5:62
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: Android_608e 92:e7:c4:e6:4c:f8
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  983): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: Note3-1 ea:50:8b:de:28:a3
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 5: Android_50a5 fa:cf:c5:d9:e5:62
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6856], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6856]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: Note3-1 ea:50:8b:de:28:a3
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 5: Android_50a5 fa:cf:c5:d9:e5:62
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6856], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6856]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service discovery started successfully
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): restart: Restarting...
,I/wpa_supplicant(  983): P2P-FIND-STOPPED 
,I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): P2P device discovery started successfully
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  983): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 3241): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service request added successfully
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  983): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  983): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: Android_50a5 fa:cf:c5:d9:e5:62
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: Android_50a5 fa:cf:c5:d9:e5:62
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: Android_50a5 fa:cf:c5:d9:e5:62
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service discovery started successfully
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  983): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: Android_50a5 fa:cf:c5:d9:e5:62
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: Android_50a5 fa:cf:c5:d9:e5:62
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT2838","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838]
,I/io.jxcore.node.ConnectionHelper( 3241): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
D/io.jxcore.node.ConnectionHelper( 3241): notifyPeerAvailability: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838] is available
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): restart: Restarting...
,I/wpa_supplicant(  983): P2P-FIND-STOPPED 
,I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): Start timer timeout, starting now...
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  983): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 3241): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service request added successfully
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service discovery started successfully
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT8771","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT8771]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8771]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8771]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8771], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT8771]
I/io.jxcore.node.ConnectionHelper( 3241): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8771], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 3241): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8771] already in the list, will not add again
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8771], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8771]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8771], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8771]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT2451","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2451]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onServiceDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2451]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2451]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2451], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Adding new peer: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2451]
,I/io.jxcore.node.ConnectionHelper( 3241): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2451], Bluetooth address: E0:DB:10:14:E2:C0, device name: Note4-1, device address: 92:b6:86:43:73:1c
D/io.jxcore.node.ConnectionHelper( 3241): notifyPeerAvailability: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2451] is available
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Identity: "{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT1675","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Resolved peer properties: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT1675]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onServiceDiscovered: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT1675]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onPeerDiscovered: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT1675]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT1675], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Adding new peer: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT1675]
I/io.jxcore.node.ConnectionHelper( 3241): onPeerDiscovered: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT1675], Bluetooth address: F8:CF:C5:D9:E5:61, device name: , device address: fa:cf:c5:d9:e5:62
D/io.jxcore.node.ConnectionHelper( 3241): notifyPeerAvailability: Peer [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT1675] is available
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2451], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2451]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8771], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8771]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT8854","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT8854]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT8854]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT8854]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT8854], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT8854]
,I/io.jxcore.node.ConnectionHelper( 3241): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT8854], Bluetooth address: 58:3F:54:73:64:C0, device name: , device address: 02:9a:02:7b:60:ac
,D/io.jxcore.node.ConnectionHelper( 3241): notifyPeerAvailability: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT8854] is available
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT1538","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Resolved peer properties: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1538]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onServiceDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1538]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1538]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1538], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Adding new peer: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1538]
I/io.jxcore.node.ConnectionHelper( 3241): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1538], Bluetooth address: 90:E7:C4:F6:69:77, device name: Android_608e, device address: 92:e7:c4:e6:4c:f8
W/io.jxcore.node.ConnectionHelper( 3241): modifyListOfDiscoveredPeers: Peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1538] already in the list, will not add again
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT8854], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT8854]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1538], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1538]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2451], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2451]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8771], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8771]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): checkListForExpiredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6856] expired
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6856], add/update: false
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Removed [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6856]
,I/io.jxcore.node.ConnectionHelper( 3241): onPeerLost: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6856]
D/io.jxcore.node.ConnectionHelper( 3241): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6856] removed
D/io.jxcore.node.ConnectionHelper( 3241): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6856] not available
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2451], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2451]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8771], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8771]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 5: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT8854], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT8854]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 6: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 7: Android_50a5 fa:cf:c5:d9:e5:62
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT1675], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT1675]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): restart: Restarting...
,D/WifiP2pManager( 3241): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service request added successfully
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT2838","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838]
I/io.jxcore.node.ConnectionHelper( 3241): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838], Bluetooth address: 7C:F9:0E:37:96:AB, device name: , device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 3241): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838] already in the list, will not add again
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT6856","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6856]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6856]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6856]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6856], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6856]
I/io.jxcore.node.ConnectionHelper( 3241): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6856], Bluetooth address: 08:EC:A9:50:75:41, device name: , device address: 0a:ec:a9:50:75:42
D/io.jxcore.node.ConnectionHelper( 3241): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6856] is available
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8771], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8771]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 6: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 8: Android_50a5 fa:cf:c5:d9:e5:62
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT1675], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT1675]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT4249","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onServiceDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249]
,I/io.jxcore.node.ConnectionHelper( 3241): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249], Bluetooth address: 08:EC:A9:50:76:27, device name: , device address: 0a:ec:a9:50:76:28
D/io.jxcore.node.ConnectionHelper( 3241): notifyPeerAvailability: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249] is available
D/WifiP2pManager( 3241): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service request added successfully
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  983): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6856], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6856]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 9: Android_50a5 fa:cf:c5:d9:e5:62
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT1675], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT1675]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 10 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6856], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6856]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 9: Android_50a5 fa:cf:c5:d9:e5:62
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT1675], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT1675]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 11 device(s) discovered
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6856], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6856]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 10: Android_50a5 fa:cf:c5:d9:e5:62
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT1675], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT1675]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service discovery started successfully
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  983): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 11 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6856], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6856]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 10: Android_50a5 fa:cf:c5:d9:e5:62
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT1675], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT1675]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 11 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6856], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6856]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 10: Android_50a5 fa:cf:c5:d9:e5:62
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT1675], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT1675]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT4249","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onServiceDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249]
I/io.jxcore.node.ConnectionHelper( 3241): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
W/io.jxcore.node.ConnectionHelper( 3241): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT6856","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6856]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6856]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6856]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6856], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6856]
,I/io.jxcore.node.ConnectionHelper( 3241): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6856], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper( 3241): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6856] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT2838","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838]
I/io.jxcore.node.ConnectionHelper( 3241): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 3241): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838] already in the list, will not add again
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 12 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 6: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6856], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6856]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 11: Android_50a5 fa:cf:c5:d9:e5:62
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT1675], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT1675]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 12: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): restart: Restarting...
,D/WifiP2pManager( 3241): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service request added successfully
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 12 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 6: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6856], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6856]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 11: Android_50a5 fa:cf:c5:d9:e5:62
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT1675], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT1675]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 12: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service discovery started successfully
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 13 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 6: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 8: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6856], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6856]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 11: Note3-1 ea:50:8b:de:28:a3
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 12: Android_50a5 fa:cf:c5:d9:e5:62
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT1675], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT1675]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 13: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT4997","ra":"E0:DB:10:1F:C9:5E"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4997]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onServiceDiscovered: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4997]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onPeerDiscovered: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4997]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4997], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Adding new peer: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4997]
I/io.jxcore.node.ConnectionHelper( 3241): onPeerDiscovered: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4997], Bluetooth address: E0:DB:10:1F:C9:5E, device name: Note3-1, device address: ea:50:8b:de:28:a3
D/io.jxcore.node.ConnectionHelper( 3241): notifyPeerAvailability: Peer [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4997] is available
,I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 11 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6856], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6856]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 10: Note3-1 ea:50:8b:de:28:a3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4997], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4997]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 11: Android_50a5 fa:cf:c5:d9:e5:62
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT1675], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT1675]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 11 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6856], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6856]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 10: Note3-1 ea:50:8b:de:28:a3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4997], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4997]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 11: Android_50a5 fa:cf:c5:d9:e5:62
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT1675], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT1675]
,D/WifiP2pManager( 3241): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service discovery started successfully
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: Note3-1 ea:50:8b:de:28:a3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4997], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4997]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: Note3-1 ea:50:8b:de:28:a3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4997], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4997]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: Note3-1 ea:50:8b:de:28:a3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4997], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4997]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: Note3-1 ea:50:8b:de:28:a3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4997], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4997]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
,I/wpa_supplicant(  983): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: Note3-1 ea:50:8b:de:28:a3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4997], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4997]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
,I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: Note3-1 ea:50:8b:de:28:a3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4997], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4997]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
D/WifiP2pManager( 3241): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service discovery started successfully
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  983): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: Android_50a5 fa:cf:c5:d9:e5:62
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT1675], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT1675]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 2 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: Android_50a5 fa:cf:c5:d9:e5:62
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT1675], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT1675]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: Android_50a5 fa:cf:c5:d9:e5:62
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT1675], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT1675]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): restart: Restarting...
,D/WifiP2pManager( 3241): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service request added successfully
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  983): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: Android_50a5 fa:cf:c5:d9:e5:62
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT1675], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT1675]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: Android_50a5 fa:cf:c5:d9:e5:62
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT1675], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT1675]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: Android_50a5 fa:cf:c5:d9:e5:62
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT1675], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT1675]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service discovery started successfully
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  983): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: Android_50a5 fa:cf:c5:d9:e5:62
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT1675], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT1675]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: Android_50a5 fa:cf:c5:d9:e5:62
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT1675], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT1675]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT2838","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838]
I/io.jxcore.node.ConnectionHelper( 3241): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838], Bluetooth address: 7C:F9:0E:37:96:AB, device name: , device address: 7e:f9:0e:37:96:ac
,W/io.jxcore.node.ConnectionHelper( 3241): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838] already in the list, will not add again
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): checkListForExpiredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6856] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6856], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Removed [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6856]
I/io.jxcore.node.ConnectionHelper( 3241): onPeerLost: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6856]
D/io.jxcore.node.ConnectionHelper( 3241): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6856] removed
D/io.jxcore.node.ConnectionHelper( 3241): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6856] not available
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): restart: Restarting...
,I/wpa_supplicant(  983): P2P-FIND-STOPPED 
,I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): Start timer timeout, starting now...
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): restart: Restarting...
,D/WifiP2pManager( 3241): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service request added successfully
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  983): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 3 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT9006","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9006]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9006]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9006]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9006], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9006]
I/io.jxcore.node.ConnectionHelper( 3241): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9006], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
,W/io.jxcore.node.ConnectionHelper( 3241): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9006] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT4268","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
,I/io.jxcore.node.ConnectionHelper( 3241): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
D/io.jxcore.node.ConnectionHelper( 3241): notifyPeerAvailability: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268] is available
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT8854","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT8854]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT8854]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT8854]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT8854], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT8854]
I/io.jxcore.node.ConnectionHelper( 3241): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT8854], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper( 3241): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT8854] already in the list, will not add again
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9006], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9006]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT8854], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT8854]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT8771","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT8771]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8771]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8771]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8771], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT8771]
I/io.jxcore.node.ConnectionHelper( 3241): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8771], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
,W/io.jxcore.node.ConnectionHelper( 3241): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8771] already in the list, will not add again
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): checkListForExpiredPeers: Peer [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4997] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4997], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Removed [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4997]
I/io.jxcore.node.ConnectionHelper( 3241): onPeerLost: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4997]
D/io.jxcore.node.ConnectionHelper( 3241): modifyListOfDiscoveredPeers: Peer [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4997] removed
D/io.jxcore.node.ConnectionHelper( 3241): notifyPeerAvailability: Peer [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4997] not available
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT6856","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6856]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6856]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6856]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6856], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6856]
I/io.jxcore.node.ConnectionHelper( 3241): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6856], Bluetooth address: 08:EC:A9:50:75:41, device name: , device address: 0a:ec:a9:50:75:42
D/io.jxcore.node.ConnectionHelper( 3241): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6856] is available
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT4249","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onServiceDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249]
I/io.jxcore.node.ConnectionHelper( 3241): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249], Bluetooth address: 08:EC:A9:50:76:27, device name: , device address: 0a:ec:a9:50:76:28
,W/io.jxcore.node.ConnectionHelper( 3241): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT2451","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2451]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onServiceDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2451]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2451]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2451], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Adding new peer: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2451]
,I/io.jxcore.node.ConnectionHelper( 3241): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2451], Bluetooth address: E0:DB:10:14:E2:C0, device name: , device address: 92:b6:86:43:73:1c
W/io.jxcore.node.ConnectionHelper( 3241): modifyListOfDiscoveredPeers: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2451] already in the list, will not add again
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  983): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT8854], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT8854]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8771], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8771],
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6856], add/update: true,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6856]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d,
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268],
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 6 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6856], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6856]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
,D/WifiP2pManager( 3241): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service request added successfully
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service discovery started successfully
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  983): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac,
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838],
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT2838","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838]
,I/io.jxcore.node.ConnectionHelper( 3241): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 3241): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT4249","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onServiceDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249]
I/io.jxcore.node.ConnectionHelper( 3241): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
W/io.jxcore.node.ConnectionHelper( 3241): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249] already in the list, will not add again
,I/UsageStatsService(  734): User[0] Flushing usage stats to disk
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): checkListForExpiredPeers: Peer [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT1675] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT1675], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Removed [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT1675]
I/io.jxcore.node.ConnectionHelper( 3241): onPeerLost: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT1675]
D/io.jxcore.node.ConnectionHelper( 3241): modifyListOfDiscoveredPeers: Peer [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT1675] removed
D/io.jxcore.node.ConnectionHelper( 3241): notifyPeerAvailability: Peer [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT1675] not available
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): restart: Restarting...
,I/wpa_supplicant(  983): P2P-FIND-STOPPED 
,I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): Start timer timeout, starting now...
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2451], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2451]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): restart: Restarting...
,D/WifiP2pManager( 3241): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service request added successfully
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2451], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2451]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT8254","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onServiceDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Adding new peer: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254]
I/io.jxcore.node.ConnectionHelper( 3241): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
D/io.jxcore.node.ConnectionHelper( 3241): notifyPeerAvailability: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254] is available
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2451], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2451]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): restart: Restarting...
,D/WifiP2pManager( 3241): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service request added successfully
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT2838","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838]
I/io.jxcore.node.ConnectionHelper( 3241): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 3241): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT8771","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT8771]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8771]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8771]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8771], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT8771]
I/io.jxcore.node.ConnectionHelper( 3241): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8771], Bluetooth address: F8:95:C7:87:85:54, device name: , device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 3241): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8771] already in the list, will not add again
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): checkListForExpiredPeers: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249] expired
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): checkListForExpiredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Removed [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Removed [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
I/io.jxcore.node.ConnectionHelper( 3241): onPeerLost: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249]
D/io.jxcore.node.ConnectionHelper( 3241): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249] removed
D/io.jxcore.node.ConnectionHelper( 3241): notifyPeerAvailability: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249] not available
I/io.jxcore.node.ConnectionHelper( 3241): onPeerLost: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
D/io.jxcore.node.ConnectionHelper( 3241): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268] removed
D/io.jxcore.node.ConnectionHelper( 3241): notifyPeerAvailability: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268] not available
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): restart: Restarting...
,I/wpa_supplicant(  983): P2P-FIND-STOPPED ,
,I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): Start timer timeout, starting now...
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  983): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
,D/WifiP2pManager( 3241): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service request added successfully
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service discovery started successfully
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): restart: Restarting...
,D/WifiP2pManager( 3241): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service request added successfully
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  983): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254]
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service discovery started successfully
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8771], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8771]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT8254","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onServiceDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254]
I/io.jxcore.node.ConnectionHelper( 3241): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
,W/io.jxcore.node.ConnectionHelper( 3241): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT2838","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838]
I/io.jxcore.node.ConnectionHelper( 3241): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 3241): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT8771","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT8771]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8771]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8771]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8771], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8771]
I/io.jxcore.node.ConnectionHelper( 3241): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8771], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 3241): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8771] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): restart: Restarting...
,I/wpa_supplicant(  983): P2P-FIND-STOPPED 
,I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): Start timer timeout, starting now...
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant(  983): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 3241): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service request added successfully
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  983): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service discovery started successfully
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  983): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): checkListForExpiredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8771] expired
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): checkListForExpiredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838] expired
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): checkListForExpiredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8771], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Removed [F8:95:C7:87:85:54 LGE-LG-D722_PT8771]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Removed [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Removed [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254]
,I/io.jxcore.node.ConnectionHelper( 3241): onPeerLost: [F8:95:C7:87:85:54 LGE-LG-D722_PT8771]
D/io.jxcore.node.ConnectionHelper( 3241): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8771] removed
,D/io.jxcore.node.ConnectionHelper( 3241): notifyPeerAvailability: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8771] not available
,I/io.jxcore.node.ConnectionHelper( 3241): onPeerLost: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838]
D/io.jxcore.node.ConnectionHelper( 3241): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838] removed
D/io.jxcore.node.ConnectionHelper( 3241): notifyPeerAvailability: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838] not available
I/io.jxcore.node.ConnectionHelper( 3241): onPeerLost: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254]
D/io.jxcore.node.ConnectionHelper( 3241): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254] removed
D/io.jxcore.node.ConnectionHelper( 3241): notifyPeerAvailability: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254] not available
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): restart: Restarting...
,I/wpa_supplicant(  983): P2P-FIND-STOPPED 
,I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): Start timer timeout, starting now...
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: Note3-1 ea:50:8b:de:28:a3
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): restart: Restarting...
,D/WifiP2pManager( 3241): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service request added successfully
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: Note3-1 ea:50:8b:de:28:a3
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service discovery started successfully
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: Note3-1 ea:50:8b:de:28:a3
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: S5-1 ee:1f:72:63:11:86
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT9108","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9108]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9108]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9108]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9108], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9108]
I/io.jxcore.node.ConnectionHelper( 3241): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9108], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
D/io.jxcore.node.ConnectionHelper( 3241): notifyPeerAvailability: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9108] is available
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT9006","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9006]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9006]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9006]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9006], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9006]
I/io.jxcore.node.ConnectionHelper( 3241): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9006], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
,W/io.jxcore.node.ConnectionHelper( 3241): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9006] already in the list, will not add again
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT8254","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onServiceDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Adding new peer: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254]
I/io.jxcore.node.ConnectionHelper( 3241): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254], Bluetooth address: B0:C5:59:3F:75:69, device name: , device address: ee:1f:72:18:8b:78
D/io.jxcore.node.ConnectionHelper( 3241): notifyPeerAvailability: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254] is available
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  983): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9108], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9108]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9006], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9006]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: Note3-1 ea:50:8b:de:28:a3
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9006], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9006]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: Note3-1 ea:50:8b:de:28:a3
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3241): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service request added successfully
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service discovery started successfully
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9006], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9006]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: Note3-1 ea:50:8b:de:28:a3
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT4268","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
I/io.jxcore.node.ConnectionHelper( 3241): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
D/io.jxcore.node.ConnectionHelper( 3241): notifyPeerAvailability: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268] is available
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9006], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9006]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: Note3-1 ea:50:8b:de:28:a3
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): restart: Restarting...
,D/WifiP2pManager( 3241): Ignored { when=-5ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service request added successfully
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 7 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 5: Note3-1 ea:50:8b:de:28:a3
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service discovery started successfully
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT1538","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Resolved peer properties: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1538]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onServiceDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1538]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1538]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1538], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Adding new peer: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1538]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1538], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1538]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 5: Note3-1 ea:50:8b:de:28:a3
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
I/io.jxcore.node.ConnectionHelper( 3241): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1538], Bluetooth address: 90:E7:C4:F6:69:77, device name: Android_608e, device address: 92:e7:c4:e6:4c:f8
W/io.jxcore.node.ConnectionHelper( 3241): modifyListOfDiscoveredPeers: Peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1538] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT4268","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
I/io.jxcore.node.ConnectionHelper( 3241): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3241): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268] already in the list, will not add again
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 6: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1538], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1538]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 7: Note3-1 ea:50:8b:de:28:a3
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254]
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 6: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 7: Note3-1 ea:50:8b:de:28:a3
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): restart: Restarting...
,D/WifiP2pManager( 3241): Ignored { when=-4ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service request added successfully
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 8: Note3-1 ea:50:8b:de:28:a3
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254]
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service discovery started successfully
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 8: Note3-1 ea:50:8b:de:28:a3
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): restart: Restarting...
,I/wpa_supplicant(  983): P2P-FIND-STOPPED 
,I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): Start timer timeout, starting now...
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): restart: Restarting...
,D/WifiP2pManager( 3241): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service request added successfully
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service discovery started successfully
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT8854","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT8854]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT8854]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT8854]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT8854], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT8854]
I/io.jxcore.node.ConnectionHelper( 3241): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT8854], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
,W/io.jxcore.node.ConnectionHelper( 3241): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT8854] already in the list, will not add again
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT8854], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT8854]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): restart: Restarting...
,D/WifiP2pManager( 3241): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service discovery started successfully
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT8854], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT8854]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): restart: Restarting...
,D/WifiP2pManager( 3241): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service discovery started successfully
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  983): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT8854], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT8854]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT8254]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT8854], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT8854]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): restart: Restarting...
,I/wpa_supplicant(  983): P2P-FIND-STOPPED 
,I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): Start timer timeout, starting now...
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  983): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  983): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT8854], add/update: true,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT8854]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
,D/WifiP2pManager( 3241): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service request added successfully
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 4 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service discovery started successfully
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 4 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT6856","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6856]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6856]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6856]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6856], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6856]
I/io.jxcore.node.ConnectionHelper( 3241): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6856], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper( 3241): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6856] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT4268","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
I/io.jxcore.node.ConnectionHelper( 3241): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3241): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT2838","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838]
I/io.jxcore.node.ConnectionHelper( 3241): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
D/io.jxcore.node.ConnectionHelper( 3241): notifyPeerAvailability: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838] is available
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT8854","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT8854]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT8854]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT8854]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT8854], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT8854]
,I/io.jxcore.node.ConnectionHelper( 3241): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT8854], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper( 3241): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT8854] already in the list, will not add again
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT8854], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT8854]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6856], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6856]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT1538","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Resolved peer properties: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1538]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onServiceDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1538]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1538]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1538], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Adding new peer: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1538]
I/io.jxcore.node.ConnectionHelper( 3241): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1538], Bluetooth address: 90:E7:C4:F6:69:77, device name: , device address: 92:e7:c4:e6:4c:f8
W/io.jxcore.node.ConnectionHelper( 3241): modifyListOfDiscoveredPeers: Peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1538] already in the list, will not add again
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6856], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6856]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: Note3-1 ea:50:8b:de:28:a3
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): restart: Restarting...
,D/WifiP2pManager( 3241): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service request added successfully
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service discovery started successfully
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: Note3-1 ea:50:8b:de:28:a3
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): restart: Restarting...
,I/wpa_supplicant(  983): P2P-FIND-STOPPED 
,I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
,I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): Start timer timeout, starting now...
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): restart: Restarting...
,D/WifiP2pManager( 3241): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service request added successfully
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service discovery started successfully
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838]
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT9108","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9108]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9108]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9108]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9108], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9108]
,I/io.jxcore.node.ConnectionHelper( 3241): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9108], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
W/io.jxcore.node.ConnectionHelper( 3241): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9108] already in the list, will not add again
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: Note3-1 ea:50:8b:de:28:a3
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9108], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9108]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: Note3-1 ea:50:8b:de:28:a3
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): checkListForExpiredPeers: Peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1538] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1538], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Removed [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1538]
I/io.jxcore.node.ConnectionHelper( 3241): onPeerLost: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1538]
D/io.jxcore.node.ConnectionHelper( 3241): modifyListOfDiscoveredPeers: Peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1538] removed
D/io.jxcore.node.ConnectionHelper( 3241): notifyPeerAvailability: Peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1538] not available
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): Got discovery timeout, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): restart: Restarting...
,I/wpa_supplicant(  983): P2P-FIND-STOPPED 
,I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): Start timer timeout, starting now...
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  983): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
,D/WifiP2pManager( 3241): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service request added successfully
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  983): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  983): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service discovery started successfully
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT9006","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9006]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9006]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9006]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9006], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9006]
I/io.jxcore.node.ConnectionHelper( 3241): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9006], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
W/io.jxcore.node.ConnectionHelper( 3241): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9006] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT8854","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT8854]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT8854]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT8854]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT8854], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT8854]
I/io.jxcore.node.ConnectionHelper( 3241): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT8854], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper( 3241): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT8854] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT2838","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838]
,I/io.jxcore.node.ConnectionHelper( 3241): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
,W/io.jxcore.node.ConnectionHelper( 3241): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838] already in the list, will not add again
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT8854], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT8854]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9006], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9006]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): restart: Restarting...
,D/WifiP2pManager( 3241): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service request added successfully
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9006], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT9006]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  983): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 5: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 6: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 7: Android_50a5 fa:cf:c5:d9:e5:62
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 5: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 6: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 7: Android_50a5 fa:cf:c5:d9:e5:62
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): checkListForExpiredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268] expired
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Removed [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
,I/io.jxcore.node.ConnectionHelper( 3241): onPeerLost: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
D/io.jxcore.node.ConnectionHelper( 3241): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268] removed
D/io.jxcore.node.ConnectionHelper( 3241): notifyPeerAvailability: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268] not available
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): restart: Restarting...
,I/wpa_supplicant(  983): P2P-FIND-STOPPED 
,I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): Start timer timeout, starting now...
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  983): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 3241): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service request added successfully
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service discovery started successfully
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  983): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  983): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT8771","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT8771]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8771]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8771]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8771], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT8771]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8771], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8771]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
I/io.jxcore.node.ConnectionHelper( 3241): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT8771], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
D/io.jxcore.node.ConnectionHelper( 3241): notifyPeerAvailability: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8771] is available
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8771], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8771]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8771], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8771]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT4249","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onServiceDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249]
I/io.jxcore.node.ConnectionHelper( 3241): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
,D/io.jxcore.node.ConnectionHelper( 3241): notifyPeerAvailability: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249] is available
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT8854","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT8854]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT8854]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT8854]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT8854], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT8854]
,I/io.jxcore.node.ConnectionHelper( 3241): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT8854], Bluetooth address: 58:3F:54:73:64:C0, device name: , device address: 02:9a:02:7b:60:ac
,W/io.jxcore.node.ConnectionHelper( 3241): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT8854] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT2838","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838]
I/io.jxcore.node.ConnectionHelper( 3241): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 3241): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838] already in the list, will not add again
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8771], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8771]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT4268","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
I/io.jxcore.node.ConnectionHelper( 3241): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
D/io.jxcore.node.ConnectionHelper( 3241): notifyPeerAvailability: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268] is available
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4249]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT8771], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT8771]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT1538","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Resolved peer properties: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1538]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onServiceDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1538]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1538]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1538], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Adding new peer: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1538]
I/io.jxcore.node.ConnectionHelper( 3241): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1538], Bluetooth address: 90:E7:C4:F6:69:77, device name: Android_608e, device address: 92:e7:c4:e6:4c:f8
D/io.jxcore.node.ConnectionHelper( 3241): notifyPeerAvailability: Peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1538] is available
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Identity: "{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT9974","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Resolved peer properties: [44:80:EB:7B:5A:05 motorola-XT1072_PT9974]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onServiceDiscovered: [44:80:EB:7B:5A:05 motorola-XT1072_PT9974]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onPeerDiscovered: [44:80:EB:7B:5A:05 motorola-XT1072_PT9974]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 motorola-XT1072_PT9974], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Adding new peer: [44:80:EB:7B:5A:05 motorola-XT1072_PT9974]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 motorola-XT1072_PT9974], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [44:80:EB:7B:5A:05 motorola-XT1072_PT9974]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1538], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1538]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT2838]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
I/io.jxcore.node.ConnectionHelper( 3241): onPeerDiscovered: [44:80:EB:7B:5A:05 motorola-XT1072_PT9974], Bluetooth address: 44:80:EB:7B:5A:05, device name: XT1072_23d5, device address: 44:80:eb:7b:5a:07
D/io.jxcore.node.ConnectionHelper( 3241): notifyPeerAvailability: Peer [44:80:EB:7B:5A:05 motorola-XT1072_PT9974] is available
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 motorola-XT1072_PT9974], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [44:80:EB:7B:5A:05 motorola-XT1072_PT9974]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT8854], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT8854]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1538], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1538],
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): restart: Restarting...
,D/WifiP2pManager( 3241): Ignored { when=-6ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service request added successfully
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service discovery started successfully
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT1538","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Resolved peer properties: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1538]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onServiceDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1538]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1538]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1538], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1538]
I/io.jxcore.node.ConnectionHelper( 3241): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1538], Bluetooth address: 90:E7:C4:F6:69:77, device name: Android_608e, device address: 92:e7:c4:e6:4c:f8
W/io.jxcore.node.ConnectionHelper( 3241): modifyListOfDiscoveredPeers: Peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1538] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT4268","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
I/io.jxcore.node.ConnectionHelper( 3241): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 3241): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268] already in the list, will not add again
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 motorola-XT1072_PT9974], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [44:80:EB:7B:5A:05 motorola-XT1072_PT9974]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT8854], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT8854]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1538], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1538]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT4997","ra":"E0:DB:10:1F:C9:5E"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4997]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onServiceDiscovered: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4997]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onPeerDiscovered: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4997]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4997], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Adding new peer: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4997]
,I/io.jxcore.node.ConnectionHelper( 3241): onPeerDiscovered: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4997], Bluetooth address: E0:DB:10:1F:C9:5E, device name: , device address: ea:50:8b:de:28:a3
D/io.jxcore.node.ConnectionHelper( 3241): notifyPeerAvailability: Peer [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4997] is available
,D/WifiP2pManager( 3241): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service request added successfully
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 motorola-XT1072_PT9974], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [44:80:EB:7B:5A:05 motorola-XT1072_PT9974]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1538], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1538]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 9: Note3-1 ea:50:8b:de:28:a3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4997], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4997]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service discovery started successfully
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): restart: Restarting...
,I/wpa_supplicant(  983): P2P-FIND-STOPPED 
,I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): Start timer timeout, starting now...
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): restart: Restarting...
,D/WifiP2pManager( 3241): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service request added successfully
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service discovery started successfully
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: Android_50a5 fa:cf:c5:d9:e5:62
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: G3-1 02:9a:02:7b:60:ac
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: Android_50a5 fa:cf:c5:d9:e5:62
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): restart: Restarting...
,D/WifiP2pManager( 3241): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service discovery started successfully
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT6856","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6856]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6856]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6856]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6856], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6856]
I/io.jxcore.node.ConnectionHelper( 3241): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6856], Bluetooth address: 08:EC:A9:50:75:41, device name: A3-1, device address: 0a:ec:a9:50:75:42
W/io.jxcore.node.ConnectionHelper( 3241): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6856] already in the list, will not add again
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): checkListForExpiredPeers: Peer [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4997] expired
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): checkListForExpiredPeers: Peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1538] expired
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): checkListForExpiredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268] expired
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): checkListForExpiredPeers: Peer [44:80:EB:7B:5A:05 motorola-XT1072_PT9974] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4997], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Removed [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4997]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1538], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Removed [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1538]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Removed [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 motorola-XT1072_PT9974], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Removed [44:80:EB:7B:5A:05 motorola-XT1072_PT9974]
I/io.jxcore.node.ConnectionHelper( 3241): onPeerLost: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4997]
D/io.jxcore.node.ConnectionHelper( 3241): modifyListOfDiscoveredPeers: Peer [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4997] removed
D/io.jxcore.node.ConnectionHelper( 3241): notifyPeerAvailability: Peer [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4997] not available
,I/io.jxcore.node.ConnectionHelper( 3241): onPeerLost: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1538]
D/io.jxcore.node.ConnectionHelper( 3241): modifyListOfDiscoveredPeers: Peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1538] removed
D/io.jxcore.node.ConnectionHelper( 3241): notifyPeerAvailability: Peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1538] not available
I/io.jxcore.node.ConnectionHelper( 3241): onPeerLost: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
D/io.jxcore.node.ConnectionHelper( 3241): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268] removed
D/io.jxcore.node.ConnectionHelper( 3241): notifyPeerAvailability: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268] not available
I/io.jxcore.node.ConnectionHelper( 3241): onPeerLost: [44:80:EB:7B:5A:05 motorola-XT1072_PT9974]
D/io.jxcore.node.ConnectionHelper( 3241): modifyListOfDiscoveredPeers: Peer [44:80:EB:7B:5A:05 motorola-XT1072_PT9974] removed
D/io.jxcore.node.ConnectionHelper( 3241): notifyPeerAvailability: Peer [44:80:EB:7B:5A:05 motorola-XT1072_PT9974] not available
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT1538","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Resolved peer properties: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1538]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onServiceDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1538]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1538]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1538], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Adding new peer: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1538]
,I/io.jxcore.node.ConnectionHelper( 3241): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1538], Bluetooth address: 90:E7:C4:F6:69:77, device name: , device address: 92:e7:c4:e6:4c:f8
D/io.jxcore.node.ConnectionHelper( 3241): notifyPeerAvailability: Peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1538] is available
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1,
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: Android_50a5 fa:cf:c5:d9:e5:62
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6856], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6856]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): restart: Restarting...
,D/WifiP2pManager( 3241): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service request added successfully
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 5: Android_50a5 fa:cf:c5:d9:e5:62
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6856], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6856]
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service discovery started successfully
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  983): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 9 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6856], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6856]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 8: Android_50a5 fa:cf:c5:d9:e5:62
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6856], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6856]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 8: Android_50a5 fa:cf:c5:d9:e5:62
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): restart: Restarting...
,I/wpa_supplicant(  983): P2P-FIND-STOPPED 
,I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
,I/ProcessStatsService(  734): Prepared write state in 41ms
,W/bt-smp  ( 2125): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2125): Plain text(LSB ~ MSB) = a7 b0 4f 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2125): Encrypted text(LSB ~ MSB) = d2 29 fc 01 e8 eb 0d 39 06 ad ac ff 3d 5e ca 03 
W/bt-btm  ( 2125): Stopping oneshot timer
,I/ProcessStatsService(  734): Pruning old procstats: /data/system/procstats/state-2015-12-16-04-00-51.bin
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  983): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 3241): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service request added successfully
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant(  983): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1538], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1538]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1538], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1538]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): restart: Restarting...
,I/wpa_supplicant(  983): P2P-FIND-STOPPED 
,I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant(  983): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): checkListForExpiredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6856] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6856], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Removed [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6856]
I/io.jxcore.node.ConnectionHelper( 3241): onPeerLost: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6856]
D/io.jxcore.node.ConnectionHelper( 3241): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6856] removed
D/io.jxcore.node.ConnectionHelper( 3241): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT6856] not available
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): P2P device discovery started successfully
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3241): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant(  983): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
,D/WifiP2pManager( 3241): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service request added successfully
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service discovery started successfully
,I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant(  983): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT4268","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onServiceDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
I/io.jxcore.node.ConnectionHelper( 3241): onPeerDiscovered: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
D/io.jxcore.node.ConnectionHelper( 3241): notifyPeerAvailability: Peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268] is available
,TIME-OUT KILL (timeout was 1800000ms),I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant(  983): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant(  983): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1538], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1538]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 6 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1538], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1538]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
D/WifiP2pManager( 3241): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service request added successfully
I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant(  983): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3241): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1538], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1538]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 3: Note3-1 ea:50:8b:de:28:a3
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3241): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT4268]
I/wpa_supplicant(  983): p2p0: CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant(  983): p2p0: P2P: Reject scan trigger since one is already pending
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3241): Service discovery started successfully
D/AndroidRuntime( 3686): 
D/AndroidRuntime( 3686): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3686): CheckJNI is OFF
D/AndroidRuntime( 3686): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  734): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  734): Killing 3241:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
I/WindowState(  734): WIN DEATH: Window{16722b3e u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  734): Client connection lost with reason: 4
W/PackageSettings(  734): Skipping PackageSetting{28309aaa com.example.hello/10278} due to missing metadata
I/ActivityManager(  734): Killing 3162:com.google.android.apps.docs/u0a40 (adj 13): empty for 1815s
I/ActivityManager(  734): Killing 3126:com.android.musicfx/u0a15 (adj 13): empty for 1816s
I/ActivityManager(  734): Killing 1492:com.google.android.partnersetup/u0a13 (adj 13): empty for 1816s
I/ActivityManager(  734): Killing 2836:com.android.providers.calendar/u0a2 (adj 13): empty for 1819s
I/ActivityManager(  734): Killing 3042:com.google.android.gms:car/u0a8 (adj 15): empty for 1819s
I/ActivityManager(  734): Killing 2019:com.google.android.calendar/u0a31 (adj 15): empty for 1849s
I/ActivityManager(  734): Killing 2596:com.google.android.gm/u0a70 (adj 15): empty for 1850s
I/ActivityManager(  734):   Force finishing activity ActivityRecord{170301ea u0 com.test.thalitest/.MainActivity t214}
W/ActivityManager(  734): Spurious death for ProcessRecord{a92cf8 3241:com.test.thalitest/u0a270}, curProc for 3241: null
W/libprocessgroup(  734): failed to open /acct/uid_10040/pid_3162/cgroup.procs: No such file or directory
W/libprocessgroup(  734): failed to open /acct/uid_10013/pid_1492/cgroup.procs: No such file or directory
W/libprocessgroup(  734): failed to open /acct/uid_10002/pid_2836/cgroup.procs: No such file or directory
W/libprocessgroup(  734): failed to open /acct/uid_10008/pid_3042/cgroup.procs: No such file or directory
W/libprocessgroup(  734): failed to open /acct/uid_10031/pid_2019/cgroup.procs: No such file or directory
W/libprocessgroup(  734): failed to open /acct/uid_10070/pid_2596/cgroup.procs: No such file or directory
W/libprocessgroup(  734): failed to open /acct/uid_10015/pid_3126/cgroup.procs: No such file or directory
I/Adreno-EGL(  944): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
I/OpenGLRenderer(  944): Initialized EGL, version 1.4
D/OpenGLRenderer(  944): Enabling debug mode 0
I/ActivityManager(  734): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
W/InputMethodManagerService(  734): Got RemoteException sending setActive(false) notification to pid 3241 uid 10270
I/Keyboard.Facilitator( 1093): onFinishInput()
I/art     ( 1413): Explicit concurrent mark sweep GC freed 11963(926KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 19MB/25MB, paused 710us total 39.013ms
I/art     ( 1296): Explicit concurrent mark sweep GC freed 3969(294KB) AllocSpace objects, 1(126KB) LOS objects, 38% free, 25MB/41MB, paused 695us total 16.944ms
I/art     ( 1645): Explicit concurrent mark sweep GC freed 11954(570KB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 22MB/30MB, paused 1.042ms total 57.506ms
I/Keyboard.Facilitator( 1093): resetDictionaries() : en_US
W/GeofencerStateMachine( 1599): Ignoring removeGeofence because network location is disabled.
I/Keyboard.Facilitator.DecoderInitializer( 1093): run()
I/Decoder ( 1093): createOrResetDecoder
I/InputReader(  734): Reconfiguring input devices.  changes=0x00000010
D/VoicemailCleanupService( 1388): Cleaning up data for package: com.test.thalitest
I/ActivityManager(  734): Start proc com.android.musicfx for broadcast com.android.musicfx/.Compatibility$Receiver: pid=3735 uid=10015 gids={50015, 9997, 3003, 3002} abi=armeabi-v7a
I/art     (  734): Explicit concurrent mark sweep GC freed 105242(4MB) AllocSpace objects, 11(249KB) LOS objects, 33% free, 28MB/43MB, paused 1.080ms total 82.804ms
I/art     (  734): WaitForGcToComplete blocked for 17.096ms for cause Explicit
I/Keyboard.Facilitator.MainLanguageModelLoader( 1093): run()
I/Keyboard.Facilitator.MainLanguageModelLoader( 1093): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1093): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1093): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1093): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1093): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1093): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1093): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1093): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1093): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1093): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1093): run()
I/StatsUtilsManager( 1093): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1093): shouldRecordStats() = Too Soon
W/Launcher( 1296): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@22f89577 new=com.google.android.velvet.VelvetApplication@22f89577
I/UpdateIcingCorporaServi( 1413): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
D/BackupManagerService(  734): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  734): Receieved: android.intent.action.PACKAGE_REMOVED
I/ActivityManager(  734): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3759 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
I/ActivityManager(  734): Killing 3019:com.android.defcontainer/u0a5 (adj 15): empty for 1814s
I/art     (  734): Explicit concurrent mark sweep GC freed 21633(1150KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 28MB/42MB, paused 1.446ms total 162.143ms
D/TaskPersister(  734): removeObsoleteFile: deleting file=214_task.xml
W/libprocessgroup(  734): failed to open /acct/uid_10005/pid_3019/cgroup.procs: No such file or directory
I/Launcher( 1296): Deferring update until onResume
W/ContextImpl( 3759): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
D/PackageBroadcastService( 1645): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1645): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1645): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1645): Module APK com.google.android.play.games already loaded
W/ResourcesManager( 1296): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/ChimeraCfgMgr( 1645): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1645): Module APK com.google.android.play.games already loaded
E/NetworkScheduler.SchedulerReceiver( 1599): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1599): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
W/ResourcesManager( 1296): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/Launcher( 1296): Deferring update until onResume
I/ActivityManager(  734): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=3783 uid=10040 gids={50040, 9997, 1028, 3003, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3686): Shutting down VM
I/LocationSettingsChecker( 1645): Removing dialog suppression flag for package com.test.thalitest
I/UpdateIcingCorporaServi( 1413): UpdateCorporaTask done [took 561 ms] updated apps [took 561 ms] 
D/gH_CompatibleDatabase( 1645): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1645): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1645): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1645): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 1645): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1645): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1645): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
I/GMPM-SVC( 1645): App measurement is starting up, version: 8489
I/GMPM-SVC( 1645): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
W/BaseAppContext( 1645): Using Auth Proxy for data requests.
D/gH_CompatibleDatabase( 1645): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1645): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
W/BaseAppContext( 1645): Using Auth Proxy for data requests.
D/gH_CompatibleDatabase( 1645): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1645): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1645): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1645): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/Icing   ( 1645): doRemovePackageData com.test.thalitest
I/GAv4    ( 3783): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3783):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3783):   adb logcat -s GAv4
W/GAv4    ( 3783): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3783): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 3783): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 3783): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 3783): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 3783): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteDatabase( 3783): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 3783): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3783): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3783): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 3783): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 3783): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3783): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3783): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3783): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 3783): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 3783): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 3783): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/SQLiteDatabase( 3783): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 3783): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 3783): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 3783): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 3783): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 3783): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 3783): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 3783): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 3783): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 3783): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 3783): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3783): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3783): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3783): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 3783): 	at gir$c.run(Unknown Source)
E/GAv4    ( 3783): Opening the database failed, dropping the table and recreating it
E/SharedPreferencesImpl( 3783): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteDatabase( 3783): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 3783): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3783): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3783): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 3783): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 3783): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3783): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3783): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3783): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 3783): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 3783): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 3783): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/SQLiteDatabase( 3783): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 3783): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 3783): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 3783): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 3783): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 3783): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 3783): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 3783): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 3783): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 3783): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 3783): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3783): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3783): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3783): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 3783): 	at gir$c.run(Unknown Source)
W/AnalyticsTrackerProxyImpl( 3783): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
E/GAv4    ( 3783): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/GAv4    ( 3783): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 3783): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 3783): Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 3783): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 3783): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteDatabase( 3783): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 3783): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3783): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3783): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 3783): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 3783): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3783): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3783): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3783): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 3783): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 3783): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 3783): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/SQLiteDatabase( 3783): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 3783): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 3783): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 3783): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 3783): 	at ael.a(PG:1521)
E/SQLiteDatabase( 3783): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 3783): 	at aen.run(PG:536)

```
