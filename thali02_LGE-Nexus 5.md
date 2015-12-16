#### Test 50650278e989a4f_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
I/GAv4    ( 3201): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3201):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3201):   adb logcat -s GAv4
W/GAv4    ( 3201): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3201): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3201): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 3201): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
,D/Finsky  ( 2674): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
I/ActivityManager(  759): Killing 2642:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
D/AndroidRuntime( 3245): 
D/AndroidRuntime( 3245): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3245): CheckJNI is OFF
W/ResourcesManager( 3201): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3201): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/libprocessgroup(  759): failed to open /acct/uid_10069/pid_2642/cgroup.procs: No such file or directory
V/JNIHelp ( 3201): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/AndroidRuntime( 3245): Calling main entry com.android.commands.am.Am
I/ActivityManager(  759): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
W/System  ( 3201): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3201): Installed default security provider GmsCore_OpenSSL
I/ActivityManager(  759): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3283 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3245): Shutting down VM
V/GLSActivity( 1595): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/ActivityManager(  759): Display changed displayId=0
I/Icing   ( 1637): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/WebViewFactory( 3283): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/Icing   ( 1637): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1637): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/LibraryLoader( 3283): Time to load native libraries: 1 ms (timestamps 7157-7158)
I/LibraryLoader( 3283): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3283): Binding Chromium to main looper Looper (main, tid 1) {2ea4d835}
I/LibraryLoader( 3283): Expected native library version number "",actual native library version number ""
I/chromium( 3283): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3283): Initializing chromium process, singleProcess=true
W/art     ( 3283): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3283): ApplicationContext is null in ApplicationStatus
,I/Icing   ( 1637): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
W/chromium( 3283): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3283): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3283): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3283): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
D/BluetoothManagerService(  759): Message: 20
D/BluetoothManagerService(  759): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2a6e2698:true
W/art     ( 3283): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 3283): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 3283): CordovaWebView is running on device made by: LGE
W/art     ( 3283): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3283): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 3283): Render dirty regions requested: true
D/Atlas   ( 3283): Validating map...
W/chromium( 3283): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/OpenGLRenderer( 3283): Initialized EGL, version 1.4
D/OpenGLRenderer( 3283): Enabling debug mode 0
I/Keyboard.Facilitator( 1075): onFinishInput()
W/BindingManager( 3283): Cannot call determinedVisibility() - never saw a connection for the pid: 3283
I/ActivityManager(  759): Displayed com.test.thalitest/.MainActivity: +437ms (total +55s255ms)
W/IInputConnectionWrapper( 3283): showStatusIcon on inactive InputConnection
D/JsMessageQueue( 3283): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 3283): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257343360
D/JX-Cordova( 3283): jxcore cordova android initializing
D/CAR.SERVICE( 3082): mConnectedToCar = false, abort
E/ActivityThread( 3082): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@3dde8832 that was originally bound here
E/ActivityThread( 3082): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@3dde8832 that was originally bound here
E/ActivityThread( 3082): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3082): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3082): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3082): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3082): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3082): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3082): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3082): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3082): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3082): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 3082): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 3082): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 3082): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 3082): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2731)
E/ActivityThread( 3082): 	at android.app.ActivityThread.access$1800(ActivityThread.java:144)
E/ActivityThread( 3082): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1361)
E/ActivityThread( 3082): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3082): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3082): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3082): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3082): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3082): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3082): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
E/ActivityThread( 3082): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@128841f5 that was originally bound here
E/ActivityThread( 3082): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@128841f5 that was originally bound here
E/ActivityThread( 3082): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3082): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3082): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3082): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3082): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3082): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3082): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3082): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 3082): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 3082): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 3082): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 3082): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 3082): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2758)
E/ActivityThread( 3082): 	at android.app.ActivityThread.access$1900(ActivityThread.java:144)
E/ActivityThread( 3082): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
E/ActivityThread( 3082): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3082): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3082): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3082): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3082): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3082): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3082): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
W/ActivityManager(  759): Unbind failed: could not find connection for android.os.BinderProxy@79f179d
I/ActivityManager(  759): Killing 2590:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
W/libprocessgroup(  759): failed to open /acct/uid_10045/pid_2590/cgroup.procs: No such file or directory
,W/jxcore-log( 3283): Initializing JXcore engine
W/jxcore-log( 3283): JXcore engine is ready
,W/jxcore-log( 3283): Starting JXcore engine
,W/.test.thalitest( 3283): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[6498]" dev="sockfs" ino=6498 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3283): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 3283): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8539]" dev="sockfs" ino=8539 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3283): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[19740]" dev="sockfs" ino=19740 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3283): Platform android
W/jxcore-log( 3283): 
W/jxcore-log( 3283): Process ARCH arm
W/jxcore-log( 3283): 
,I/jxcore-log( 3283): JXcore Cordova bridge is ready!
I/jxcore-log( 3283): 
W/jxcore-log( 3283): JXcore engine is started
I/Choreographer( 3283): Skipped 105 frames!  The application may be doing too much work on its main thread.
I/chromium( 3283): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3283): Toggling radios to true
I/jxcore-log( 3283): 
,D/BluetoothAdapter( 3283): enable(): BT is already enabled..!
,D/WifiService(  759): New client listening to asynchronous messages
,D/WifiService(  759): setWifiEnabled: true pid=3283, uid=10270
,E/WifiService(  759): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3283): Radios toggled
I/jxcore-log( 3283): 
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 3283): Got Device Bluetooth address: 34:FC:EF:11:AE:67
I/jxcore-log( 3283): 
,I/jxcore-log( 3283): Perf Test app loaded loaded
I/jxcore-log( 3283): 
,I/wpa_supplicant(  989): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,I/Choreographer( 3283): Skipped 57 frames!  The application may be doing too much work on its main thread.
I/jxcore-log( 3283): check test folder
I/jxcore-log( 3283): 
E/WifiStateMachine(  759): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  759): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
I/jxcore-log( 3283): found test : ./testFindPeers.js
I/jxcore-log( 3283): 
E/native  (  759): do suspend true
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,I/jxcore-log( 3283): found test : ./testSendData.js
I/jxcore-log( 3283): 
,V/NativeCrypto( 1595): Read error: ssl=0xb3c6ce00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1595): SSL shutdown failed: ssl=0xb3c6ce00: I/O error during system call, Broken pipe
,D/ConnectivityService(  759): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): ValidatedState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): DefaultState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Forcing reevaluation
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,E/WifiConfigStore(  759): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  759): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  759): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,E/WifiStateMachine(  759): Start Disconnecting Watchdog 1
,I/wpa_supplicant(  989): wlan0: CTRL-EVENT-SCAN-STARTED 
,E/native  (  759): do suspend true
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,D/ConnectivityService(  759): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityManager.CallbackHandler(  896): CM callback handler got msg 524292
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Disconnected - quitting
D/ConnectivityManager.CallbackHandler( 1637): CM callback handler got msg 524292
,D/Nat464Xlat(  759): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  759): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,D/ConnectivityService(  759): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  759): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  759): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1237): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WifiNetworkAgent(  759): NetworkAgent: NetworkAgent channel lost
,I/chromium( 3283): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/wpa_supplicant(  989): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant(  989): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant(  989): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant(  989): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  759): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  759): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  759): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  759): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  179): Setting iface cfg
,E/WifiStateMachine(  759): Start Dhcp Watchdog 2
,E/native  (  759): do suspend false
,E/WifiStateMachine(  759): scanCount==0 - aborting
,I/dhcpcd  ( 3372): version 5.5.6 starting
,E/dhcpcd  ( 3372): get_duid: Read-only file system
,I/dhcpcd  ( 3372): wlan0: rebinding lease of 192.168.1.114
,I/dhcpcd  ( 3372): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3372): wlan0: leased 192.168.1.114 for 86400 seconds
,V/GLSActivity( 1595): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1595): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/NetworkUtils( 1390): OkHttp exception
W/EventLoggerService( 1390): Unable to send logs Error code: 262146
,E/native  (  759): do suspend true
,D/ConnectivityService(  759): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  759): Adding iface wlan0 to network 101
E/WifiStateMachine(  759): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  759): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  759): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  759): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/ConnectivityService(  759): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  759): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  759): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  759): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  759): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  759): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  759):    accepting network in place of null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/CSLegacyTypeTracker(  759): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  759): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  759): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  759): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler(  896): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1637): CM callback handler got msg 524290
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 16 Dec 2015 02:30:28 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450233028822], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450233028803]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Validated
,D/ConnectivityService(  759): Validated NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  759): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  759): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  759): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler(  896): CM callback handler got msg 524290
,D/ConnectivityService(  759): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/TelephonyNetworkFactory( 1237): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 1637): CM callback handler got msg 524290
,D/Nat464Xlat(  759): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  759): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  896): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 1637): CM callback handler got msg 524295
,D/ConnectivityService(  759): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  759): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  759): MasterInitialState.processMessage what=3
,D/Tethering(  759): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2800): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 2800): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2800): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,E/GpsLocationProvider(  759): No APN found to select.
,E/GpsLocationProvider(  759): No APN found to select.
,I/SystemUpdateService( 1637): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1637): onCreate
,D/SystemUpdateService( 1637): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1637): active receiver: enabled
,I/SystemUpdateService( 1637): showing system update notification
,I/ActivityManager(  759): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3449 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ValidateNoPeople(  759): skipping global notification
,V/SystemUpdateService( 1637): retry (wakeup: false) in 3599948 ms
,D/SystemUpdateService( 1637): onDestroy
,I/GAv4    ( 3449): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3449):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3449):   adb logcat -s GAv4
,W/GAv4    ( 3449): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3449): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3449): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/ConnectivityService(  759): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/WebViewFactory( 3449): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3449): Time to load native libraries: 1 ms (timestamps 4050-4051)
I/LibraryLoader( 3449): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3449): Binding Chromium to main looper Looper (main, tid 1) {2f711adf}
,I/LibraryLoader( 3449): Expected native library version number "",actual native library version number ""
I/chromium( 3449): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3449): Initializing chromium process, singleProcess=true
,W/art     ( 3449): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3449): ApplicationContext is null in ApplicationStatus
,W/chromium( 3449): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3449): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3449): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3449): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/NSApplication( 3449): Starting up...
,I/ActivityManager(  759): Killing 2776:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/AudioManagerAndroid( 3449): Requires BLUETOOTH permission
,W/libprocessgroup(  759): failed to open /acct/uid_10003/pid_2776/cgroup.procs: No such file or directory
,V/MusicLeanback( 2800): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1637): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1637): onCreate
,D/SystemUpdateService( 1637): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1637): active receiver: enabled
,I/SystemUpdateService( 1637): showing system update notification
,I/ValidateNoPeople(  759): skipping global notification
,V/SystemUpdateService( 1637): retry (wakeup: false) in 3599985 ms
,D/SystemUpdateService( 1637): onDestroy
,I/jxcore-log( 3283): BLE advertisement not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 3283): 
,D/ConnectivityService(  759): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  759): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2800): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2800): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1637): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1637): onCreate
,D/SystemUpdateService( 1637): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,E/GpsLocationProvider(  759): No APN found to select.
,I/SystemUpdateService( 1637): active receiver: enabled
,I/SystemUpdateService( 1637): showing system update notification
,I/ValidateNoPeople(  759): skipping global notification
,V/SystemUpdateService( 1637): retry (wakeup: false) in 3599991 ms
,I/art     (  759): Explicit concurrent mark sweep GC freed 46178(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 27MB/41MB, paused 819us total 57.110ms
,D/SystemUpdateService( 1637): onDestroy
,D/Finsky  ( 2674): [255] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 2674): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/GLSActivity( 1595): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1595): Vacuum at: now=1450233048701 tag=VacuumService
,I/PhenotypeConfigurator( 1595): Scheduling Phenotype for one-off execution 1108 seconds from now (1450233048999)
,D/GetConfigurationSnapshotOperation( 1595): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1595): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1595): Using platform SSLCertificateSocketFactory
,V/GLSActivity( 1595): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1595): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Keyboard.Facilitator.LanguageModelFlusher( 1075): run()
I/Keyboard.Facilitator( 1075): flushDynamicLanguageModels()
,I/ClearcutLoggerApiImpl( 1595): disconnect managed GoogleApiClient
,I/jxcore-log( 3283): Connected to the server!
I/jxcore-log( 3283): 
,I/chromium( 3283): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,I/ActivityManager(  759): Killing 2758:com.android.settings/1000 (adj 15): empty #17
,D/WifiService(  759): Client connection lost with reason: 4
,W/libprocessgroup(  759): failed to open /acct/uid_1000/pid_2758/cgroup.procs: No such file or directory
,W/bt-smp  ( 2134): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2134): Plain text(LSB ~ MSB) = e4 d3 6a 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2134): Encrypted text(LSB ~ MSB) = 71 75 28 4f d4 d6 27 24 92 99 8a cd 01 13 a9 eb 
,W/bt-btm  ( 2134): Stopping oneshot timer
,I/ActivityManager(  759): Start proc com.google.android.youtube for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator: pid=3660 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 3660): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3660): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 3660): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 3660): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3660): Installed default security provider GmsCore_OpenSSL
,E/YouTube MDX( 3660): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,I/dex2oat ( 3702): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads-370217675.jar --oat-fd=25 --oat-location=/data/data/com.google.android.youtube/cache/ads-370217675.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 3702): dex2oat took 38.917ms (threads: 4)
,W/InstanceID/Rpc( 3660): Found 10008
,I/ActivityManager(  759): Killing 2610:com.google.android.gm/u0a70 (adj 15): empty #17
,W/libprocessgroup(  759): failed to open /acct/uid_10070/pid_2610/cgroup.procs: No such file or directory
,I/UsageStatsService(  759): User[0] Flushing usage stats to disk
,I/ProcessStatsService(  759): Prepared write state in 4ms
,I/ProcessStatsService(  759): Prepared write state in 3ms
,I/ProcessStatsService(  759): Prepared write state in 3ms
,W/bt-smp  ( 2134): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2134): Plain text(LSB ~ MSB) = 09 96 49 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2134): Encrypted text(LSB ~ MSB) = 53 1c e5 23 35 58 31 9c 9b 54 02 e9 a4 00 76 cf 
W/bt-btm  ( 2134): Stopping oneshot timer
,I/EventLogService( 1637): Aggregate from 1450232368530 (log), 1450232368530 (data)
,I/ProcessStatsService(  759): Pruning old procstats: /data/system/procstats/state-2015-12-15-16-15-01.bin
,I/ActivityManager(  759): Killing 2026:com.google.android.calendar/u0a31 (adj 15): empty for 1810s
,W/libprocessgroup(  759): failed to open /acct/uid_10031/pid_2026/cgroup.procs: No such file or directory
,V/GLSActivity( 1595): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1595): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,TIME-OUT KILL (timeout was 1800000ms),I/ActivityManager(  759): Killing 3201:com.google.android.apps.docs/u0a40 (adj 13): empty for 1813s
I/ActivityManager(  759): Killing 3082:com.google.android.gms:car/u0a8 (adj 13): empty for 1813s
I/ActivityManager(  759): Killing 3170:com.android.musicfx/u0a15 (adj 13): empty for 1813s
I/ActivityManager(  759): Killing 1459:com.google.android.partnersetup/u0a13 (adj 13): empty for 1814s
I/ActivityManager(  759): Killing 2870:com.android.providers.calendar/u0a2 (adj 15): empty for 1816s
W/libprocessgroup(  759): failed to open /acct/uid_10040/pid_3201/cgroup.procs: No such file or directory
W/libprocessgroup(  759): failed to open /acct/uid_10008/pid_3082/cgroup.procs: No such file or directory
W/libprocessgroup(  759): failed to open /acct/uid_10015/pid_3170/cgroup.procs: No such file or directory
W/libprocessgroup(  759): failed to open /acct/uid_10013/pid_1459/cgroup.procs: No such file or directory
W/libprocessgroup(  759): failed to open /acct/uid_10002/pid_2870/cgroup.procs: No such file or directory
I/ActivityManager(  759): Killing 3060:com.android.defcontainer/u0a5 (adj 15): empty for 1811s
W/libprocessgroup(  759): failed to open /acct/uid_10005/pid_3060/cgroup.procs: No such file or directory
D/AndroidRuntime( 3821): 
D/AndroidRuntime( 3821): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3821): CheckJNI is OFF
D/AndroidRuntime( 3821): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  759): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  759): Killing 3283:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
I/WindowState(  759): WIN DEATH: Window{3f8465c8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/PackageSettings(  759): Skipping PackageSetting{6df2979 com.example.hello/10278} due to missing metadata
D/WifiService(  759): Client connection lost with reason: 4
I/ActivityManager(  759):   Force finishing activity ActivityRecord{b612381 u0 com.test.thalitest/.MainActivity t214}
W/ActivityManager(  759): Spurious death for ProcessRecord{2aa695bc 3283:com.test.thalitest/u0a270}, curProc for 3283: null
I/ActivityManager(  759): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
I/ActivityManager(  759):   Force finishing activity ActivityRecord{b612381 u0 com.test.thalitest/.MainActivity t214 f}
W/ActivityManager(  759): Duplicate finish request for ActivityRecord{b612381 u0 com.test.thalitest/.MainActivity t214 f}
I/InputReader(  759): Reconfiguring input devices.  changes=0x00000010
I/Keyboard.Facilitator( 1075): resetDictionaries() : en_US
I/art     ( 1262): Explicit concurrent mark sweep GC freed 3988(295KB) AllocSpace objects, 1(126KB) LOS objects, 38% free, 25MB/41MB, paused 482us total 35.221ms
W/GeofencerStateMachine( 1595): Ignoring removeGeofence because network location is disabled.
D/VoicemailCleanupService( 1351): Cleaning up data for package: com.test.thalitest
I/Keyboard.Facilitator.DecoderInitializer( 1075): run()
I/ActivityManager(  759): Start proc com.android.musicfx for broadcast com.android.musicfx/.Compatibility$Receiver: pid=3851 uid=10015 gids={50015, 9997, 3003, 3002} abi=armeabi-v7a
I/art     ( 1390): Explicit concurrent mark sweep GC freed 2539(176KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 18MB/25MB, paused 19.798ms total 89.946ms
I/art     (  759): Explicit concurrent mark sweep GC freed 36590(2031KB) AllocSpace objects, 11(249KB) LOS objects, 33% free, 27MB/41MB, paused 2.235ms total 91.451ms
I/art     (  759): WaitForGcToComplete blocked for 90.795ms for cause Explicit
I/Decoder ( 1075): createOrResetDecoder
I/art     ( 1637): Explicit concurrent mark sweep GC freed 14892(777KB) AllocSpace objects, 3(48KB) LOS objects, 25% free, 22MB/30MB, paused 527us total 119.413ms
I/Adreno-EGL(  938): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
I/OpenGLRenderer(  938): Initialized EGL, version 1.4
D/OpenGLRenderer(  938): Enabling debug mode 0
I/Keyboard.Facilitator.MainLanguageModelLoader( 1075): run()
I/UpdateIcingCorporaServi( 1390): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/Keyboard.Facilitator.MainLanguageModelLoader( 1075): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1075): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1075): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1075): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1075): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1075): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1075): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1075): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1075): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1075): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1075): run()
I/StatsUtilsManager( 1075): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1075): shouldRecordStats() = Too Soon
I/ActivityManager(  759): Killing 2800:com.google.android.music:main/u0a60 (adj 15): empty for 1805s
W/Launcher( 1262): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@40e64ca new=com.google.android.velvet.VelvetApplication@40e64ca
D/BackupManagerService(  759): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  759): Receieved: android.intent.action.PACKAGE_REMOVED
W/InputMethodManagerService(  759): Focus gain on non-focused client com.android.internal.view.IInputMethodClient$Stub$Proxy@184116e4 (uid=10034 pid=938)
W/InputMethodManagerService(  759): Got RemoteException sending setActive(false) notification to pid 3283 uid 10270
I/Keyboard.Facilitator( 1075): onFinishInput()
I/art     (  759): Explicit concurrent mark sweep GC freed 6406(355KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 27MB/41MB, paused 1.564ms total 153.482ms
W/libprocessgroup(  759): failed to open /acct/uid_10060/pid_2800/cgroup.procs: No such file or directory
I/ActivityManager(  759): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3885 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
D/TaskPersister(  759): removeObsoleteFile: deleting file=214_task.xml
D/AndroidRuntime( 3821): Shutting down VM
I/Launcher( 1262): Deferring update until onResume
I/UpdateIcingCorporaServi( 1390): UpdateCorporaTask done [took 170 ms] updated apps [took 170 ms] 
W/ResourcesManager( 1262): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ContextImpl( 3885): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
D/PackageBroadcastService( 1637): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1637): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1637): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1637): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 1637): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1637): Module APK com.google.android.play.games already loaded
W/ResourcesManager( 1262): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/LocationSettingsChecker( 1637): Removing dialog suppression flag for package com.test.thalitest
E/NetworkScheduler.SchedulerReceiver( 1595): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1595): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
I/Launcher( 1262): Deferring update until onResume
D/gH_CompatibleDatabase( 1637): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1637): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1637): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1637): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 1637): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1637): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1637): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 1637): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1637): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1637): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1637): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1637): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1637): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/ActivityManager(  759): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=3910 uid=10040 gids={50040, 9997, 1028, 3003, 1015} abi=armeabi-v7a
I/GMPM-SVC( 1637): App measurement is starting up, version: 8489
I/GMPM-SVC( 1637): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
W/BaseAppContext( 1637): Using Auth Proxy for data requests.
W/BaseAppContext( 1637): Using Auth Proxy for data requests.
I/Icing   ( 1637): doRemovePackageData com.test.thalitest

```
