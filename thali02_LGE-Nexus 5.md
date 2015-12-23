#### Test 54312298af2c956_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
I/GAv4    ( 3138): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3138):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3138):   adb logcat -s GAv4
W/GAv4    ( 3138): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3138): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3138): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 3138): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
D/Finsky  ( 2649): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
W/ResourcesManager( 3138): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3138): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  758): Killing 2057:com.google.android.deskclock/u0a38 (adj 15): empty #17
V/JNIHelp ( 3138): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/AndroidRuntime( 3189): 
D/AndroidRuntime( 3189): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3189): CheckJNI is OFF
W/System  ( 3138): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3138): Installed default security provider GmsCore_OpenSSL
W/libprocessgroup(  758): failed to open /acct/uid_10038/pid_2057/cgroup.procs: No such file or directory
V/GLSActivity( 1664): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/AndroidRuntime( 3189): Calling main entry com.android.commands.am.Am
I/ActivityManager(  758): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  758): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3220 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3189): Shutting down VM
I/art     (  194): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 394us total 17.737ms
V/ActivityManager(  758): Display changed displayId=0
I/art     (  194): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 363us total 15.228ms
I/art     (  194): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 169us total 12.223ms
I/Icing   ( 1688): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/Icing   ( 1688): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1688): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/Icing   ( 1688): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
I/WebViewFactory( 3220): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3220): Time to load native libraries: 2 ms (timestamps 7086-7088)
I/LibraryLoader( 3220): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3220): Binding Chromium to main looper Looper (main, tid 1) {2e471a9a}
,I/LibraryLoader( 3220): Expected native library version number "",actual native library version number ""
I/chromium( 3220): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3220): Initializing chromium process, singleProcess=true
W/art     ( 3220): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3220): ApplicationContext is null in ApplicationStatus
W/chromium( 3220): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3220): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3220): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3220): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
D/BluetoothManagerService(  758): Message: 20
D/BluetoothManagerService(  758): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2ddc662a:true
W/art     ( 3220): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 3220): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 3220): CordovaWebView is running on device made by: LGE
W/art     ( 3220): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3220): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 3220): Render dirty regions requested: true
D/Atlas   ( 3220): Validating map...
W/chromium( 3220): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/OpenGLRenderer( 3220): Initialized EGL, version 1.4
D/OpenGLRenderer( 3220): Enabling debug mode 0
I/Keyboard.Facilitator( 1106): onFinishInput()
W/BindingManager( 3220): Cannot call determinedVisibility() - never saw a connection for the pid: 3220
W/IInputConnectionWrapper( 3220): showStatusIcon on inactive InputConnection
I/ActivityManager(  758): Displayed com.test.thalitest/.MainActivity: +503ms (total +54s637ms)
D/JsMessageQueue( 3220): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 3220): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257332480
D/JX-Cordova( 3220): jxcore cordova android initializing
I/ActivityManager(  758): Killing 2620:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
W/libprocessgroup(  758): failed to open /acct/uid_10069/pid_2620/cgroup.procs: No such file or directory
,W/jxcore-log( 3220): Initializing JXcore engine
W/jxcore-log( 3220): JXcore engine is ready
W/jxcore-log( 3220): Starting JXcore engine
,W/.test.thalitest( 3220): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[8404]" dev="sockfs" ino=8404 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/.test.thalitest( 3220): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 3220): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6555]" dev="sockfs" ino=6555 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3220): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[18362]" dev="sockfs" ino=18362 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3220): Platform android
W/jxcore-log( 3220): 
W/jxcore-log( 3220): Process ARCH arm
W/jxcore-log( 3220): 
,I/jxcore-log( 3220): JXcore Cordova bridge is ready!
I/jxcore-log( 3220): 
W/jxcore-log( 3220): JXcore engine is started
,I/Choreographer( 3220): Skipped 109 frames!  The application may be doing too much work on its main thread.
I/chromium( 3220): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/CAR.SERVICE( 3048): mConnectedToCar = false, abort
,E/ActivityThread( 3048): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@3e5ce113 that was originally bound here
E/ActivityThread( 3048): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@3e5ce113 that was originally bound here
E/ActivityThread( 3048): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3048): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3048): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3048): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3048): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3048): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3048): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3048): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3048): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3048): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 3048): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 3048): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 3048): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 3048): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2731)
E/ActivityThread( 3048): 	at android.app.ActivityThread.access$1800(ActivityThread.java:144)
E/ActivityThread( 3048): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1361)
E/ActivityThread( 3048): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3048): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3048): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3048): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3048): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3048): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3048): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
,E/ActivityThread( 3048): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@2d65f15a that was originally bound here
E/ActivityThread( 3048): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@2d65f15a that was originally bound here
E/ActivityThread( 3048): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3048): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3048): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3048): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3048): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3048): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3048): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3048): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 3048): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 3048): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 3048): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 3048): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 3048): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2758)
E/ActivityThread( 3048): 	at android.app.ActivityThread.access$1900(ActivityThread.java:144)
E/ActivityThread( 3048): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
E/ActivityThread( 3048): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3048): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3048): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3048): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3048): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3048): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3048): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
W/ActivityManager(  758): Unbind failed: could not find connection for android.os.BinderProxy@22974b94
,I/jxcore-log( 3220): Toggling radios to true
I/jxcore-log( 3220): 
,D/BluetoothAdapter( 3220): enable(): BT is already enabled..!
,D/WifiService(  758): New client listening to asynchronous messages
,D/WifiService(  758): setWifiEnabled: true pid=3220, uid=10270
E/WifiService(  758): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3220): Radios toggled
I/jxcore-log( 3220): 
,D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 3220): Got Device Bluetooth address: 34:FC:EF:11:AE:67
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): Perf Test app loaded loaded
I/jxcore-log( 3220): 
,I/wpa_supplicant( 1024): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  758): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  758): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/native  (  758): do suspend true
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1664): Read error: ssl=0xb3f2fe00: I/O error during system call, Connection timed out
I/jxcore-log( 3220): check test folder
I/jxcore-log( 3220): 
I/jxcore-log( 3220): found test : ./testFindPeers.js
I/jxcore-log( 3220): 
,V/NativeCrypto( 1664): SSL shutdown failed: ssl=0xb3f2fe00: I/O error during system call, Broken pipe
,D/ConnectivityService(  758): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): ValidatedState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): DefaultState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): Checking http://clients3.google.com/generate_204 on "NG7005g"
,E/WifiConfigStore(  758): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  758): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  758): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,I/jxcore-log( 3220): found test : ./testSendData.js
I/jxcore-log( 3220): 
,E/WifiStateMachine(  758): Start Disconnecting Watchdog 1
,I/wpa_supplicant( 1024): wlan0: CTRL-EVENT-SCAN-STARTED 
,E/native  (  758): do suspend true
,D/CommandListener(  179): Clearing all IP addresses on wlan0
D/ConnectivityService(  758): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler(  918): CM callback handler got msg 524292
D/Nat464Xlat(  758): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  758): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): Disconnected - quitting
,I/jxcore-log( 3220): found test : ./testSendData2.js
I/jxcore-log( 3220): 
,D/ConnectivityManager.CallbackHandler( 1688): CM callback handler got msg 524292
D/ConnectivityService(  758): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  758): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  758): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1273): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WifiNetworkAgent(  758): NetworkAgent: NetworkAgent channel lost
,I/chromium( 3220): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/ActivityManager(  758): Killing 2084:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,W/libprocessgroup(  758): failed to open /acct/uid_10045/pid_2084/cgroup.procs: No such file or directory
,V/GLSActivity( 1664): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1664): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/NetworkUtils( 1377): OkHttp exception
,W/EventLoggerService( 1377): Unable to send logs Error code: 262146
,W/ProcessCpuTracker(  758): Skipping unknown process pid 3308
W/ProcessCpuTracker(  758): Skipping unknown process pid 3309
W/ProcessCpuTracker(  758): Skipping unknown process pid 3318
W/ProcessCpuTracker(  758): Skipping unknown process pid 3319
W/ProcessCpuTracker(  758): Skipping unknown process pid 3322
,W/ProcessCpuTracker(  758): Skipping unknown process pid 3326
,I/wpa_supplicant( 1024): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant( 1024): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1024): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1024): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  758): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  758): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  758): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  758): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  179): Setting iface cfg
,E/WifiStateMachine(  758): Start Dhcp Watchdog 2
,E/native  (  758): do suspend false
,E/WifiStateMachine(  758): scanCount==0 - aborting
,I/dhcpcd  ( 3336): version 5.5.6 starting
,E/dhcpcd  ( 3336): get_duid: Read-only file system
,I/dhcpcd  ( 3336): wlan0: rebinding lease of 192.168.1.114
,I/dhcpcd  ( 3336): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3336): wlan0: leased 192.168.1.114 for 86400 seconds
,E/native  (  758): do suspend true
,E/WifiStateMachine(  758): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/ConnectivityService(  758): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  758): Adding iface wlan0 to network 101
,E/ConnectivityService(  758): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  758): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  758): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/ConnectivityService(  758): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  758): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  758): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  758): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  758): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/ConnectivityService(  758): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  758):    accepting network in place of null
,D/CSLegacyTypeTracker(  758): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  758): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  758): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  758): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler(  918): CM callback handler got msg 524290
D/ConnectivityService(  758): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityManager.CallbackHandler( 1688): CM callback handler got msg 524290
D/ConnectivityService(  758): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  758): MasterInitialState.processMessage what=3
,D/Tethering(  758): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2771): type=WIFI subType= reason=null isConnected=true
,E/GpsLocationProvider(  758): No APN found to select.
,I/NetworkMonitor( 2771): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2771): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,E/GpsLocationProvider(  758): No APN found to select.
,D/Nat464Xlat(  758): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  758): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler(  918): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 1688): CM callback handler got msg 524295
,I/SystemUpdateService( 1688): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1688): onCreate
,D/SystemUpdateService( 1688): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1688): active receiver: enabled
,I/SystemUpdateService( 1688): showing system update notification
,I/ValidateNoPeople(  758): skipping global notification
,V/SystemUpdateService( 1688): retry (wakeup: false) in 3599983 ms
,I/ActivityManager(  758): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3396 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/SystemUpdateService( 1688): onDestroy
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 23 Dec 2015 02:07:41 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450836461905], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450836461887]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): Validated
D/ConnectivityService(  758): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  758): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  758): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  758): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler(  918): CM callback handler got msg 524290
D/ConnectivityService(  758): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/TelephonyNetworkFactory( 1273): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1688): CM callback handler got msg 524290
,I/GAv4    ( 3396): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3396):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3396):   adb logcat -s GAv4
,W/GAv4    ( 3396): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3396): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3396): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 3396): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3396): Time to load native libraries: 2 ms (timestamps 3972-3974)
,I/LibraryLoader( 3396): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3396): Binding Chromium to main looper Looper (main, tid 1) {70c907c}
,I/LibraryLoader( 3396): Expected native library version number "",actual native library version number ""
,I/chromium( 3396): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3396): Initializing chromium process, singleProcess=true
,W/art     ( 3396): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3396): ApplicationContext is null in ApplicationStatus
,W/chromium( 3396): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3396): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3396): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3396): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/NSApplication( 3396): Starting up...
,I/ActivityManager(  758): Killing 2748:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/AudioManagerAndroid( 3396): Requires BLUETOOTH permission
,W/libprocessgroup(  758): failed to open /acct/uid_10003/pid_2748/cgroup.procs: No such file or directory
,V/MusicLeanback( 2771): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1688): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1688): onCreate
,D/SystemUpdateService( 1688): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1688): active receiver: enabled
,I/SystemUpdateService( 1688): showing system update notification
,I/ValidateNoPeople(  758): skipping global notification
,V/SystemUpdateService( 1688): retry (wakeup: false) in 3599970 ms
,D/SystemUpdateService( 1688): onDestroy
,D/ConnectivityService(  758): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): setDiscoveryMode: Mode set to WIFI
,I/jxcore-log( 3220): BLE supported!!
I/jxcore-log( 3220): 
,D/ConnectivityService(  758): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  758): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2771): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2771): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1688): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1688): onCreate
,D/SystemUpdateService( 1688): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1688): active receiver: enabled
,I/SystemUpdateService( 1688): showing system update notification
,I/ValidateNoPeople(  758): skipping global notification
,V/SystemUpdateService( 1688): retry (wakeup: false) in 3599987 ms
,I/art     (  758): Explicit concurrent mark sweep GC freed 46770(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 27MB/41MB, paused 888us total 64.100ms
,D/SystemUpdateService( 1688): onDestroy
,E/GpsLocationProvider(  758): No APN found to select.
,D/Finsky  ( 2649): [255] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2649): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/GLSActivity( 1664): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1664): Vacuum at: now=1450836482843 tag=VacuumService
,I/PhenotypeConfigurator( 1664): Scheduling Phenotype for one-off execution 2480 seconds from now (1450836483102)
,D/GetConfigurationSnapshotOperation( 1664): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1664): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1664): Using platform SSLCertificateSocketFactory
,V/GLSActivity( 1664): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1664): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Keyboard.Facilitator.LanguageModelFlusher( 1106): run()
I/Keyboard.Facilitator( 1106): flushDynamicLanguageModels()
,I/ClearcutLoggerApiImpl( 1664): disconnect managed GoogleApiClient
,D/HeadsetStateMachine( 2139): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 2139): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
D/HeadsetStateMachine( 2139): Disconnected process message: 11, size: 0
,I/jxcore-log( 3220): Connected to the server!
I/jxcore-log( 3220): 
,I/chromium( 3220): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3220): --- start :testFindPeers.js---
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): testFindPeers created [object Object]
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): serverPort is 8876
I/jxcore-log( 3220): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): setDiscoveryMode: Mode set to WIFI
,D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3220): start: Peer ID: 34:FC:EF:11:AE:67, peer name: LGE-Nexus 5_PT8145
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3220): bind: Binding a new listener
,D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3220): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3220): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT8145","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3220): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3220): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3220): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3220): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3220): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3220): start: OK
I/io.jxcore.node.ConnectionHelper( 3220): start: Using peer discovery mode: WIFI
,D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): start: Peer ID: 34:FC:EF:11:AE:67, peer name: LGE-Nexus 5_PT8145
,D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3220): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT8145","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3220): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3220): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT8145","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3220): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT8145","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3220): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3220): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3220): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3220): start: OK
I/jxcore-log( 3220): StartBroadcasting started ok
I/jxcore-log( 3220): 
I/chromium( 3220): [INFO:CONSOLE(63)] "logCallback --- start :testFindPeers.js---", source: file:///android_asset/www/js/thali_main.js (63)
,I/io.jxcore.node.ConnectionHelper( 3220): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3220): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3220): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3220): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3220): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3220): onDiscoveryManagerStateChanged: RUNNING
,I/wpa_supplicant( 1024): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1024): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1024): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1024): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3220): onP2pDeviceListChanged: 2 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3220): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/WifiP2pManager( 3220): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3220): Service request added successfully
,I/wpa_supplicant( 1024): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1024): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3220): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
,I/wpa_supplicant( 1024): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1024): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3220): Service discovery started successfully
,I/wpa_supplicant( 1024): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 1024): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3220): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3220): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3220): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT6430","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3220): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3220): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
I/io.jxcore.node.ConnectionHelper( 3220): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
D/io.jxcore.node.ConnectionHelper( 3220): notifyPeerAvailability: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430] is available
,I/jxcore-log( 3220): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:37:96:AB","peerName":"samsung-SM-A500FU_PT6430","peerAvailable":true}]
I/jxcore-log( 3220): 
I/jxcore-log( 3220): Found peer : 7C:F9:0E:37:96:AB, peerAvailable: true
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): weAreDoneNow
I/jxcore-log( 3220): 
I/jxcore-log( 3220): done, now sending data to server
I/jxcore-log( 3220): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3220): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3220): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3220): setState: RESTARTING
,I/wpa_supplicant( 1024): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1024): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant( 1024): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 1024): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
I/wpa_supplicant( 1024): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 1024): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3220): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3220): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3220): onP2pDeviceListChanged: 0 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3220): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3220): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3220): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3220): Start timer timeout, starting now...
,I/wpa_supplicant( 1024): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3220): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3220): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3220): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1024): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1024): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1024): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1024): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1024): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3220): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3220): restart: Restarting...
,D/WifiP2pManager( 3220): Ignored { when=-11ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3220): Service request added successfully
,I/wpa_supplicant( 1024): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1024): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1024): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3220): Service discovery started successfully
,I/wpa_supplicant( 1024): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3220): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3220): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT1715","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3220): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3220): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715]
I/io.jxcore.node.ConnectionHelper( 3220): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
D/io.jxcore.node.ConnectionHelper( 3220): notifyPeerAvailability: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715] is available
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3220): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT4270","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3220): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3220): onServiceDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270]
I/io.jxcore.node.ConnectionHelper( 3220): onPeerDiscovered: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270], Bluetooth address: 08:EC:A9:50:75:41, device name: , device address: 0a:ec:a9:50:75:42
D/io.jxcore.node.ConnectionHelper( 3220): notifyPeerAvailability: Peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270] is available
,I/wpa_supplicant( 1024): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1024): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1024): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1024): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3220): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3220): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3220): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3220): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3220): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3220): Service request added successfully
,I/wpa_supplicant( 1024): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1024): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3220): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT1715]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): modifyListOfDiscoveredPeers: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4270]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
,I/wpa_supplicant( 1024): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1024): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3220): Service discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): checkListForExpiredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430] expired
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): modifyListOfDiscoveredPeers: Removed [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
,I/io.jxcore.node.ConnectionHelper( 3220): onPeerLost: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
D/io.jxcore.node.ConnectionHelper( 3220): hasConnection: No connection with peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 3220): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430] removed
D/io.jxcore.node.ConnectionHelper( 3220): notifyPeerAvailability: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430] not available
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3220): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3220): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3220): setState: RESTARTING
,I/wpa_supplicant( 1024): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1024): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 1024): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 1024): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant( 1024): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 1024): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3220): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3220): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3220): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3220): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3220): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3220): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3220): Start timer timeout, starting now...
,I/wpa_supplicant( 1024): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3220): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3220): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3220): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1024): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3220): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3220): restart: Restarting...
,D/WifiP2pManager( 3220): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3220): Service request added successfully
,I/wpa_supplicant( 1024): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1024): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3220): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3220): Service discovery started successfully
,I/wpa_supplicant( 1024): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1024): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1024): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 1024): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3220): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT1694","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3220): onDnsSdServiceAvailable: Resolved peer properties: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1694]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3220): onServiceDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1694]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1694]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1694], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): modifyListOfDiscoveredPeers: Adding new peer: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1694]
I/io.jxcore.node.ConnectionHelper( 3220): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1694], Bluetooth address: 90:E7:C4:F6:69:77, device name: Android_608e, device address: 92:e7:c4:e6:4c:f8
D/io.jxcore.node.ConnectionHelper( 3220): notifyPeerAvailability: Peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1694] is available
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3220): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1694], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1694]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3220): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1694], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1694]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3220): onP2pDeviceListChanged: 5 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1694], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1694]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
,I/jxcore-log( 3220): teardown
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): testFindPeers stopped
I/jxcore-log( 3220): 
I/io.jxcore.node.ConnectionHelper( 3220): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3220): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3220): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3220): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3220): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3220): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3220): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3220): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3220): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3220): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3220): stop: Stopping P2P device discovery...
,I/wpa_supplicant( 1024): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1024): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
I/wpa_supplicant( 1024): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 1024): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 1024): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 1024): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3220): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3220): release: No more listeners, de-initializing...
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3220): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3220): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): setState: NOT_STARTED
,I/jxcore-log( 3220): StopBroadcasting went ok
I/jxcore-log( 3220): 
,I/chromium( 3220): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
I/io.jxcore.node.ConnectionHelper( 3220): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3220): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3220): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3220): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 3220): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 3220): --- start :testSendData.js---
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":14}bt-address length : 0
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): check server
I/jxcore-log( 3220): 
I/jxcore-log( 3220): serverPort is 57906
I/jxcore-log( 3220): 
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): setDiscoveryMode: Failed to set discovery mode to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): setDiscoveryMode: Mode set to WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): setDiscoveryMode: Mode set to WIFI
,D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3220): start: Peer ID: 34:FC:EF:11:AE:67, peer name: LGE-Nexus 5_PT8145
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3220): bind: Binding a new listener
,D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3220): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3220): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT8145","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3220): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3220): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3220): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3220): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3220): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3220): start: OK
I/io.jxcore.node.ConnectionHelper( 3220): start: Using peer discovery mode: WIFI
,D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): start: Peer ID: 34:FC:EF:11:AE:67, peer name: LGE-Nexus 5_PT8145
,D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3220): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT8145","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3220): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3220): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT8145","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3220): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT8145","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3220): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3220): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3220): start: OK
I/jxcore-log( 3220): StartBroadcasting started ok
I/jxcore-log( 3220): 
I/jxcore-log( 3220): null
I/jxcore-log( 3220): 
I/jxcore-log( 3220): 2015-12-23T02:15:56.946Z SendDataTCPServer.js: TCP/IP server is bound to port: 57906
I/jxcore-log( 3220): 
I/chromium( 3220): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
,I/wpa_supplicant( 1024): p2p0: CTRL-EVENT-SCAN-STARTED 
I/io.jxcore.node.ConnectionHelper( 3220): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3220): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3220): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3220): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3220): setState: RESTARTING
I/wpa_supplicant( 1024): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3220): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3220): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3220): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3220): onDiscoveryManagerStateChanged: RUNNING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3220): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3220): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3220): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3220): setState: RESTARTING
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3220): Waiting for incoming connections...
,I/wpa_supplicant( 1024): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3220): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,D/WifiP2pManager( 3220): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3220): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3220): Service discovery started successfully
,I/wpa_supplicant( 1024): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3220): Start timer timeout, starting now...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3220): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3220): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3220): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1024): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1024): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 1024): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3220): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3220): restart: Restarting...
,D/WifiP2pManager( 3220): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3220): Service request added successfully
,I/wpa_supplicant( 1024): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1024): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1024): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3220): Service discovery started successfully
,W/bt-btif ( 2139): info:x10
,D/        ( 2139): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2139): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 2139): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 1
E/bt-btif ( 2139): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2139): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2139): Entering PendingCommandState State
,W/BluetoothEventManager( 2728): CachedBluetoothDevice for device 7C:F9:0E:37:96:AB not found, calling readPairedDevices().
,E/BluetoothEventManager( 2728): Got bonding state changed for 7C:F9:0E:37:96:AB, but we have no record of that device.
,I/BluetoothBondStateMachine( 2139): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 0
,D/BluetoothAdapterProperties( 2139): Failed to remove device: 7C:F9:0E:37:96:AB
,I/BluetoothBondStateMachine( 2139): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 11 NewState: 10
,W/BluetoothEventManager( 2728): CachedBluetoothDevice for device 7C:F9:0E:37:96:AB not found, calling readPairedDevices().
,E/BluetoothEventManager( 2728): Got bonding state changed for 7C:F9:0E:37:96:AB, but we have no record of that device.
,W/bt-btif ( 2139): new conn_srvc id:26, app_id:255
W/bt-btif ( 2139): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2139): bta_dm_pm_ssr:2, lat:1200
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3220): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3220): Incoming connection initialized (thread ID: 300)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3220): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3220): Entering thread (ID: 300)
,I/BluetoothBondStateMachine( 2139): StableState(): Entering Off State
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3220): onBytesRead: Read 83 bytes successfully (thread ID: 300)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3220): Got valid identity from [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3220): onBytesWritten: 77 bytes successfully written (thread ID: 300)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3220): removeThreadFromList: Removing thread with ID 300
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3220): Handshake thread disposed (thread ID: 300)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3220): onIncomingConnectionConnected: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3220): onConnected: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
,I/io.jxcore.node.ConnectionHelper( 3220): onConnected: Incoming connection to peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
D/io.jxcore.node.ConnectionHelper( 3220): hasConnection: No connection with peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 3220): notifyPeerAvailability: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430] is available
,I/jxcore-log( 3220): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:37:96:AB","peerName":"samsung-SM-A500FU_PT6430","peerAvailable":true}]
I/jxcore-log( 3220): 
I/jxcore-log( 3220): Found peer : samsung-SM-A500FU_PT6430, Available: true
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): startWithNextDevice
I/jxcore-log( 3220): 
I/jxcore-log( 3220): device[1]: 7C:F9:0E:37:96:AB
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:18.403Z SendDataConnector.js: Start called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:18.403Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3220): 
I/jxcore-log( 3220): 2015-12-23T02:16:18.403Z SendDataConnector.js: do connect now
I/jxcore-log( 3220): 
,I/io.jxcore.node.ConnectionHelper( 3220): connect: Trying to connect to peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 3220): hasConnection: No connection with peer with ID 7C:F9:0E:37:96:AB
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3220): connect: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3220): connect: Trying to start connecting to A5-1 in address 7C:F9:0E:37:96:AB
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3220): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3220): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3220): onConnecting: A5-1 7C:F9:0E:37:96:AB
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3220): connect: Started connecting to A5-1 in address 7C:F9:0E:37:96:AB
I/io.jxcore.node.ConnectionHelper( 3220): connect: Connection process successfully started (peer ID: 7C:F9:0E:37:96:AB)
I/io.jxcore.node.ConnectionHelper( 3220): onConnected: Incoming socket thread, for peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430], created successfully
D/io.jxcore.node.ConnectionHelper( 3220): onConnected: The total number of connections is now 1
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3220): Exiting thread (ID: 300)
,D/io.jxcore.node.IncomingSocketThread( 3220): Entering thread (ID: 302)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3220): Trying to connect to peer with address 7C:F9:0E:37:96:AB (thread ID: 301)
W/BluetoothAdapter( 3220): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2139): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/jxcore-log( 3220): 2015-12-23T02:16:18.415Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3220): 
,I/io.jxcore.node.IncomingSocketThread( 3220): Local host address: localhost/127.0.0.1, port: 57906
,D/io.jxcore.node.IncomingSocketThread( 3220): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3220): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 3220): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3220): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3220): Exiting thread (ID: 302)
,D/io.jxcore.node.StreamCopyingThread( 3220): Entering thread (ID: 303, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 3220): Entering thread (ID: 304, name: Receiver)
,W/bt-sdp  ( 2139): process_service_search_attr_rsp
,W/bt-btif ( 2139): new conn_srvc id:26, app_id:1
W/bt-btif ( 2139): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2139): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2139): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3220): onSocketConnected: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3220): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 301)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3220): onBytesWritten: 77 bytes successfully written (thread ID: 305)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3220): Outgoing connection initialized (*handshake* thread ID: 305)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3220): Exiting thread (thread ID: 301)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3220): Entering thread (ID: 305)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3220): onBytesRead: Read 83 bytes successfully (thread ID: 305)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3220): Handshake succeeded with [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3220): onHandshakeSucceeded: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3220): onConnected: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
I/io.jxcore.node.ConnectionHelper( 3220): onConnected: Outgoing connection to peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430]
D/io.jxcore.node.ConnectionHelper( 3220): hasConnection: We have an incoming connection with peer with ID 7C:F9:0E:37:96:AB
W/io.jxcore.node.ConnectionHelper( 3220): onConnected: Already connected with peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430], continuing anyway...
W/io.jxcore.node.ConnectionHelper( 3220): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 3220): onConnected: Outgoing socket thread, for peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430], created successfully
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3220): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 3220): onConnected: The total number of connections is now 2
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3220): Exiting thread (ID: 305)
,D/io.jxcore.node.OutgoingSocketThread( 3220): Entering thread (ID: 306)
,D/io.jxcore.node.OutgoingSocketThread( 3220): Server socket local port: 48772
I/io.jxcore.node.OutgoingSocketThread( 3220): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3220): onListeningForIncomingConnections: Outgoing connection is using port 48772 (peer ID: 7C:F9:0E:37:96:AB)
I/jxcore-log( 3220): 2015-12-23T02:16:18.786Z SendDataConnector.js: CLIENT connected to 48772, error: null
I/jxcore-log( 3220): 
I/jxcore-log( 3220): 2015-12-23T02:16:18.787Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3220): 
,I/io.jxcore.node.OutgoingSocketThread( 3220): Incoming data from address: /127.0.0.1, port: 48772
D/io.jxcore.node.OutgoingSocketThread( 3220): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3220): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3220): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3220): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3220): Exiting thread (ID: 306)
,D/io.jxcore.node.StreamCopyingThread( 3220): Entering thread (ID: 308, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3220): Entering thread (ID: 307, name: Sender)
,I/jxcore-log( 3220): 2015-12-23T02:16:18.835Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:19.251Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:19.260Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:19.267Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:19.273Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:19.283Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:19.289Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3220): 
,D/        ( 2139): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23716
,I/jxcore-log( 3220): 2015-12-23T02:16:19.312Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:19.325Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:19.359Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:19.362Z SendDataTCPServer.js: TCP/IP server has received 45540 bytes of data
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:19.400Z SendDataTCPServer.js: TCP/IP server has received 47520 bytes of data
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:19.409Z SendDataTCPServer.js: TCP/IP server has received 49500 bytes of data
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:19.414Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 3220): 
,D/        ( 2139): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:13816
,I/jxcore-log( 3220): 2015-12-23T02:16:19.425Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:19.425Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:19.460Z SendDataTCPServer.js: TCP/IP server has received 63360 bytes of data
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:19.470Z SendDataTCPServer.js: TCP/IP server has received 65340 bytes of data
I/jxcore-log( 3220): 
,D/        ( 2139): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:5896
,I/jxcore-log( 3220): 2015-12-23T02:16:19.533Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:19.535Z SendDataTCPServer.js: TCP/IP server has received 77220 bytes of data
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:19.561Z SendDataTCPServer.js: TCP/IP server has received 79200 bytes of data
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:19.567Z SendDataTCPServer.js: TCP/IP server has received 81180 bytes of data
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:19.573Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:19.576Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:19.600Z SendDataTCPServer.js: TCP/IP server has received 89100 bytes of data
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:19.605Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:19.611Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:19.643Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:19.650Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:19.657Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:19.701Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3220): 
,W/bt-btif ( 2139): invalid rfc slot id: 5
,W/io.jxcore.node.StreamCopyingThread( 3220): Either failed to read from the output stream or write to the input stream (thread ID: 304, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 3220): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
,W/io.jxcore.node.ConnectionHelper( 3220): onDisconnected: Incoming connection, peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3220): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 302
D/io.jxcore.node.OutgoingSocketThread( 3220): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3220): doStop: Thread ID: 304
D/io.jxcore.node.OutgoingSocketThread( 3220): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3220): doStop: Thread ID: 303
D/io.jxcore.node.OutgoingSocketThread( 3220): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 3220): closeLocalSocketAndStreams: Closing the local input stream...
D/io.jxcore.node.OutgoingSocketThread( 3220): closeLocalSocketAndStreams: Closing the local output stream...
,W/io.jxcore.node.StreamCopyingThread( 3220): Either failed to read from the output stream or write to the input stream (thread ID: 303, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3220): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3220): onDisconnected: Incoming connection, peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 3220): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3220): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3220): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.StreamCopyingThread( 3220): Exiting thread (ID: 304, name: Receiver)
,D/io.jxcore.node.ConnectionHelper( 3220): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3220): Exiting thread (ID: 303, name: Sender)
,I/jxcore-log( 3220): 2015-12-23T02:16:19.741Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:19.750Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3220): 
I/jxcore-log( 3220): 2015-12-23T02:16:19.750Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3220): 
I/jxcore-log( 3220): oneRoundDownNow
I/jxcore-log( 3220): 
I/jxcore-log( 3220): 2015-12-23T02:16:19.753Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3220): 
I/jxcore-log( 3220): 2015-12-23T02:16:19.753Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3220): 
D/io.jxcore.node.ConnectionHelper( 3220): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:37:96:AB
I/io.jxcore.node.ConnectionHelper( 3220): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 7C:F9:0E:37:96:AB
I/io.jxcore.node.OutgoingSocketThread( 3220): close
D/io.jxcore.node.OutgoingSocketThread( 3220): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3220): doStop: Thread ID: 308
D/io.jxcore.node.OutgoingSocketThread( 3220): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3220): doStop: Thread ID: 307
D/io.jxcore.node.OutgoingSocketThread( 3220): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 3220): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3220): Either failed to read from the output stream or write to the input stream (thread ID: 307, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3220): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3220): onDisconnected: Outgoing connection, peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 3220): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 3220): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3220): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3220): Either failed to read from the output stream or write to the input stream (thread ID: 308, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.OutgoingSocketThread( 3220): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3220): onDisconnected: Outgoing connection, peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6430] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3220): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3220): disconnectOutgoingConnection: Successfully disconnected (peer ID: 7C:F9:0E:37:96:AB
,E/io.jxcore.node.ConnectionHelper( 3220): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:37:96:AB
,D/io.jxcore.node.ConnectionHelper( 3220): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3220): Exiting thread (ID: 307, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 3220): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 3220): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3220): Exiting thread (ID: 308, name: Receiver)
,I/jxcore-log( 3220): 2015-12-23T02:16:19.780Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): ---- round done--------
I/jxcore-log( 3220): 
I/jxcore-log( 3220): startWithNextDevice
I/jxcore-log( 3220): 
,W/bt-btif ( 2139): bta_jv_rfc_port_to_cb(port_handle:0xa):jv handle:0x0 not FOUND
,I/wpa_supplicant( 1024): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1024): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2139): info:x10
,D/        ( 2139): remote version info [90:e7:c4:f6:69:77]: 7, 1d, 7d3
E/BluetoothRemoteDevices( 2139): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 1024): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BluetoothBondStateMachine( 2139): bondStateChangeCallback: Status: 0 Address: 90:E7:C4:F6:69:77 newState: 1
E/bt-btif ( 2139): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2139): Bond State Change Intent:90:E7:C4:F6:69:77 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2139): Entering PendingCommandState State
,W/BluetoothEventManager( 2728): CachedBluetoothDevice for device 90:E7:C4:F6:69:77 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2728): Got bonding state changed for 90:E7:C4:F6:69:77, but we have no record of that device.
,I/BluetoothBondStateMachine( 2139): bondStateChangeCallback: Status: 0 Address: 90:E7:C4:F6:69:77 newState: 0
,D/BluetoothAdapterProperties( 2139): Failed to remove device: 90:E7:C4:F6:69:77
,I/BluetoothBondStateMachine( 2139): Bond State Change Intent:90:E7:C4:F6:69:77 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2139): StableState(): Entering Off State
,W/BluetoothEventManager( 2728): CachedBluetoothDevice for device 90:E7:C4:F6:69:77 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2728): Got bonding state changed for 90:E7:C4:F6:69:77, but we have no record of that device.
,I/wpa_supplicant( 1024): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2139): new conn_srvc id:26, app_id:255
W/bt-btif ( 2139): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2139): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3220): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3220): Incoming connection initialized (thread ID: 309)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3220): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3220): Entering thread (ID: 309)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3220): onBytesRead: Read 81 bytes successfully (thread ID: 309)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3220): Got valid identity from [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1694]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3220): onBytesWritten: 77 bytes successfully written (thread ID: 309)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3220): removeThreadFromList: Removing thread with ID 309
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3220): Handshake thread disposed (thread ID: 309)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3220): onIncomingConnectionConnected: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1694]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3220): Exiting thread (ID: 309)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3220): onConnected: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1694]
I/io.jxcore.node.ConnectionHelper( 3220): onConnected: Incoming connection to peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1694]
D/io.jxcore.node.ConnectionHelper( 3220): hasConnection: No connection with peer with ID 90:E7:C4:F6:69:77
W/io.jxcore.node.ConnectionHelper( 3220): modifyListOfDiscoveredPeers: Peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1694] already in the list, will not add again
I/io.jxcore.node.ConnectionHelper( 3220): onConnected: Incoming socket thread, for peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1694], created successfully
D/io.jxcore.node.ConnectionHelper( 3220): onConnected: The total number of connections is now 1
,D/io.jxcore.node.IncomingSocketThread( 3220): Entering thread (ID: 310)
,I/io.jxcore.node.IncomingSocketThread( 3220): Local host address: localhost/127.0.0.1, port: 57906
D/io.jxcore.node.IncomingSocketThread( 3220): Setting local streams and starting stream copying threads...
,I/jxcore-log( 3220): 2015-12-23T02:16:24.364Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3220): 
,I/io.jxcore.node.StreamCopyingThread( 3220): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3220): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3220): startStreamCopyingThreads: OK
,D/io.jxcore.node.IncomingSocketThread( 3220): Exiting thread (ID: 310)
,D/io.jxcore.node.StreamCopyingThread( 3220): Entering thread (ID: 312, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3220): Entering thread (ID: 311, name: Sender)
,I/wpa_supplicant( 1024): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1024): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3220): 2015-12-23T02:16:25.157Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:25.200Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:25.206Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:25.215Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:25.247Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:25.261Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3220): 
,I/wpa_supplicant( 1024): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3220): 2015-12-23T02:16:25.284Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:25.314Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:25.323Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:25.402Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:25.452Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:25.492Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:25.544Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:25.585Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:25.600Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:25.637Z SendDataTCPServer.js: TCP/IP server has received 37620 bytes of data
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:25.644Z SendDataTCPServer.js: TCP/IP server has received 39600 bytes of data
I/jxcore-log( 3220): 
,I/wpa_supplicant( 1024): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3220): 2015-12-23T02:16:25.695Z SendDataTCPServer.js: TCP/IP server has received 41580 bytes of data
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:25.707Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:25.742Z SendDataTCPServer.js: TCP/IP server has received 45540 bytes of data
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:25.796Z SendDataTCPServer.js: TCP/IP server has received 47520 bytes of data
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:25.803Z SendDataTCPServer.js: TCP/IP server has received 49500 bytes of data
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:25.809Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:25.890Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:25.922Z SendDataTCPServer.js: TCP/IP server has received 55440 bytes of data
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:25.938Z SendDataTCPServer.js: TCP/IP server has received 57420 bytes of data
I/jxcore-log( 3220): 
,I/wpa_supplicant( 1024): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3220): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3220): restart: Restarting...
,I/jxcore-log( 3220): 2015-12-23T02:16:25.974Z SendDataTCPServer.js: TCP/IP server has received 61380 bytes of data
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:25.978Z SendDataTCPServer.js: TCP/IP server has received 63360 bytes of data
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:26.009Z SendDataTCPServer.js: TCP/IP server has received 65340 bytes of data
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:26.015Z SendDataTCPServer.js: TCP/IP server has received 67320 bytes of data
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:26.021Z SendDataTCPServer.js: TCP/IP server has received 69300 bytes of data
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:26.096Z SendDataTCPServer.js: TCP/IP server has received 71280 bytes of data
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:26.101Z SendDataTCPServer.js: TCP/IP server has received 73260 bytes of data
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:26.140Z SendDataTCPServer.js: TCP/IP server has received 79200 bytes of data
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:26.150Z SendDataTCPServer.js: TCP/IP server has received 81180 bytes of data
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:26.183Z SendDataTCPServer.js: TCP/IP server has received 83160 bytes of data
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:26.220Z SendDataTCPServer.js: TCP/IP server has received 85140 bytes of data
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:26.237Z SendDataTCPServer.js: TCP/IP server has received 87120 bytes of data
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:26.283Z SendDataTCPServer.js: TCP/IP server has received 89100 bytes of data
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:26.293Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:26.303Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:26.326Z SendDataTCPServer.js: TCP/IP server has received 95040 bytes of data
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:26.404Z SendDataTCPServer.js: TCP/IP server has received 97020 bytes of data
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:26.414Z SendDataTCPServer.js: TCP/IP server has received 99000 bytes of data
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:26.440Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3220): 
,W/bt-btif ( 2139): invalid rfc slot id: 6
,W/io.jxcore.node.StreamCopyingThread( 3220): Either failed to read from the output stream or write to the input stream (thread ID: 312, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 3220): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3220): onDisconnected: Incoming connection, peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1694] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3220): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 310
,D/io.jxcore.node.IncomingSocketThread( 3220): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3220): doStop: Thread ID: 312
D/io.jxcore.node.IncomingSocketThread( 3220): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3220): doStop: Thread ID: 311
D/io.jxcore.node.IncomingSocketThread( 3220): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 3220): closeLocalSocketAndStreams: Closing the local input stream...
,W/bt-rfcomm( 2139): rfc_find_lcid_mcb LCID reused LCID:0x44 current:0x0
,W/bt-rfcomm( 2139): RFCOMM_DisconnectInd LCID:0x44
,W/io.jxcore.node.StreamCopyingThread( 3220): Either failed to read from the output stream or write to the input stream (thread ID: 311, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3220): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
,W/io.jxcore.node.ConnectionHelper( 3220): onDisconnected: Incoming connection, peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1694] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.IncomingSocketThread( 3220): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 3220): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3220): closeBluetoothSocketAndStreams
,D/io.jxcore.node.ConnectionHelper( 3220): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3220): Exiting thread (ID: 312, name: Receiver)
,D/io.jxcore.node.ConnectionHelper( 3220): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.StreamCopyingThread( 3220): Exiting thread (ID: 311, name: Sender)
,I/jxcore-log( 3220): 2015-12-23T02:16:26.565Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3220): 
,D/btif_config_util( 2139): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/WifiP2pManager( 3220): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3220): Service request added successfully
,I/wpa_supplicant( 1024): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1024): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3220): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,W/bt-btm  ( 2139): btm_acl_role_changed -> Issuing delayed HCI_Disconnect!!!
,E/bt-btm  ( 2139): tBTM_SEC_DEV:0xa3f50ebc rs_disc_pending=2
E/bt-btm  ( 2139): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 2139): bta_dm_check_av:0
,W/bt-btif ( 2139): btif_dm_cback : unhandled event (14)
,D/BluetoothMapService( 2139): onReceive
,D/BluetoothManagerService(  758): Message: 20
D/BluetoothManagerService(  758): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d3a4e02:true
,I/BTConnectionReceiver( 1377): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1377): Bluetooth Device Name: A5-1
,I/wpa_supplicant( 1024): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1024): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3220): Service discovery started successfully
,E/bt-btm  ( 2139): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2139): onReceive
,I/BTConnectionReceiver( 1377): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=90:E7:C4:F6:69:77, alias=null, name=HTC One M8s, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1377): Bluetooth Device Name: HTC One M8s
,W/bt-btif ( 2139): info:x10
,D/        ( 2139): remote version info [b0:c5:59:3f:75:69]: 7, f, 610c
E/BluetoothRemoteDevices( 2139): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 2139): bondStateChangeCallback: Status: 0 Address: B0:C5:59:3F:75:69 newState: 1
E/bt-btif ( 2139): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2139): Bond State Change Intent:B0:C5:59:3F:75:69 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2139): Entering PendingCommandState State
,W/BluetoothEventManager( 2728): CachedBluetoothDevice for device B0:C5:59:3F:75:69 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2728): Got bonding state changed for B0:C5:59:3F:75:69, but we have no record of that device.
,I/BluetoothBondStateMachine( 2139): bondStateChangeCallback: Status: 0 Address: B0:C5:59:3F:75:69 newState: 0
,D/BluetoothAdapterProperties( 2139): Failed to remove device: B0:C5:59:3F:75:69
,I/BluetoothBondStateMachine( 2139): Bond State Change Intent:B0:C5:59:3F:75:69 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2139): StableState(): Entering Off State
,W/BluetoothEventManager( 2728): CachedBluetoothDevice for device B0:C5:59:3F:75:69 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2728): Got bonding state changed for B0:C5:59:3F:75:69, but we have no record of that device.
,W/bt-btif ( 2139): new conn_srvc id:26, app_id:255
W/bt-btif ( 2139): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2139): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3220): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3220): Incoming connection initialized (thread ID: 313)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3220): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3220): Entering thread (ID: 313)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3220): onBytesRead: Read 82 bytes successfully (thread ID: 313)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3220): Got valid identity from [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3220): onBytesWritten: 77 bytes successfully written (thread ID: 313)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3220): removeThreadFromList: Removing thread with ID 313
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3220): Handshake thread disposed (thread ID: 313)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3220): onIncomingConnectionConnected: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3220): Exiting thread (ID: 313)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3220): onConnected: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
I/io.jxcore.node.ConnectionHelper( 3220): onConnected: Incoming connection to peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
D/io.jxcore.node.ConnectionHelper( 3220): hasConnection: No connection with peer with ID B0:C5:59:3F:75:69
,D/io.jxcore.node.ConnectionHelper( 3220): notifyPeerAvailability: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068] is available
I/jxcore-log( 3220): peerAvailabilityChanged [{"peerIdentifier":"B0:C5:59:3F:75:69","peerName":"samsung-SM-G900F_PT6068","peerAvailable":true}]
I/jxcore-log( 3220): 
I/jxcore-log( 3220): Found peer : samsung-SM-G900F_PT6068, Available: true
I/jxcore-log( 3220): 
I/jxcore-log( 3220): startWithNextDevice
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): device[2]: B0:C5:59:3F:75:69
I/jxcore-log( 3220): 
I/jxcore-log( 3220): 2015-12-23T02:16:31.568Z SendDataConnector.js: Start called with peer B0:C5:59:3F:75:69
I/jxcore-log( 3220): 
I/jxcore-log( 3220): 2015-12-23T02:16:31.568Z SendDataConnector.js: doConnect called with peer B0:C5:59:3F:75:69
I/jxcore-log( 3220): 
I/jxcore-log( 3220): 2015-12-23T02:16:31.568Z SendDataConnector.js: do connect now
I/jxcore-log( 3220): 
I/io.jxcore.node.ConnectionHelper( 3220): connect: Trying to connect to peer with ID B0:C5:59:3F:75:69
D/io.jxcore.node.ConnectionHelper( 3220): hasConnection: No connection with peer with ID B0:C5:59:3F:75:69
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3220): connect: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3220): connect: Trying to start connecting to Thali Test (Galaxy S5) in address B0:C5:59:3F:75:69
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3220): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3220): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3220): onConnecting: Thali Test (Galaxy S5) B0:C5:59:3F:75:69
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3220): connect: Started connecting to Thali Test (Galaxy S5) in address B0:C5:59:3F:75:69
I/io.jxcore.node.ConnectionHelper( 3220): connect: Connection process successfully started (peer ID: B0:C5:59:3F:75:69)
I/io.jxcore.node.ConnectionHelper( 3220): onConnected: Incoming socket thread, for peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], created successfully
D/io.jxcore.node.ConnectionHelper( 3220): onConnected: The total number of connections is now 1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3220): Trying to connect to peer with address B0:C5:59:3F:75:69 (thread ID: 314)
W/BluetoothAdapter( 3220): getBluetoothService() called with no BluetoothManagerCallback
,D/io.jxcore.node.IncomingSocketThread( 3220): Entering thread (ID: 315)
,D/BTIF_SOCK( 2139): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/jxcore-log( 3220): 2015-12-23T02:16:31.600Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3220): 
,I/io.jxcore.node.IncomingSocketThread( 3220): Local host address: localhost/127.0.0.1, port: 57906
,D/io.jxcore.node.IncomingSocketThread( 3220): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3220): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 3220): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.IncomingSocketThread( 3220): startStreamCopyingThreads: OK
,D/io.jxcore.node.IncomingSocketThread( 3220): Exiting thread (ID: 315)
,D/io.jxcore.node.StreamCopyingThread( 3220): Entering thread (ID: 316, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 3220): Entering thread (ID: 317, name: Receiver)
,W/bt-sdp  ( 2139): process_service_search_attr_rsp
,W/bt-btif ( 2139): new conn_srvc id:26, app_id:1
W/bt-btif ( 2139): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2139): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2139): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3220): onSocketConnected: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3220): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 314)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3220): onBytesWritten: 77 bytes successfully written (thread ID: 318)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3220): Outgoing connection initialized (*handshake* thread ID: 318)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3220): Exiting thread (thread ID: 314)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3220): Entering thread (ID: 318)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3220): onBytesRead: Read 82 bytes successfully (thread ID: 318)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3220): Handshake succeeded with [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3220): onHandshakeSucceeded: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 3220): Exiting thread (ID: 318)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3220): onConnected: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
,I/io.jxcore.node.ConnectionHelper( 3220): onConnected: Outgoing connection to peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068]
D/io.jxcore.node.ConnectionHelper( 3220): hasConnection: We have an incoming connection with peer with ID B0:C5:59:3F:75:69
W/io.jxcore.node.ConnectionHelper( 3220): onConnected: Already connected with peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], continuing anyway...
W/io.jxcore.node.ConnectionHelper( 3220): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 3220): onConnected: Outgoing socket thread, for peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068], created successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3220): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 3220): onConnected: The total number of connections is now 2
,D/io.jxcore.node.OutgoingSocketThread( 3220): Entering thread (ID: 319)
,D/io.jxcore.node.OutgoingSocketThread( 3220): Server socket local port: 52381
I/io.jxcore.node.OutgoingSocketThread( 3220): Now accepting connections...
,I/jxcore-log( 3220): 2015-12-23T02:16:32.489Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:32.501Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:32.527Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:32.552Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:32.591Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:32.625Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 3220): 
,I/io.jxcore.node.ConnectionHelper( 3220): onListeningForIncomingConnections: Outgoing connection is using port 52381 (peer ID: B0:C5:59:3F:75:69)
I/jxcore-log( 3220): 2015-12-23T02:16:32.651Z SendDataConnector.js: CLIENT connected to 52381, error: null
I/jxcore-log( 3220): 
I/jxcore-log( 3220): 2015-12-23T02:16:32.652Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3220): 
,I/io.jxcore.node.OutgoingSocketThread( 3220): Incoming data from address: /127.0.0.1, port: 52381
D/io.jxcore.node.OutgoingSocketThread( 3220): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3220): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3220): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3220): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3220): Exiting thread (ID: 319)
,I/jxcore-log( 3220): 2015-12-23T02:16:32.676Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3220): 
,D/io.jxcore.node.StreamCopyingThread( 3220): Entering thread (ID: 320, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 3220): Entering thread (ID: 321, name: Receiver)
,I/jxcore-log( 3220): 2015-12-23T02:16:33.110Z SendDataTCPServer.js: TCP/IP server has received 44648 bytes of data
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:33.169Z SendDataTCPServer.js: TCP/IP server has received 46628 bytes of data
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:33.290Z SendDataTCPServer.js: TCP/IP server has received 48608 bytes of data
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:33.370Z SendDataTCPServer.js: TCP/IP server has received 50588 bytes of data
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:33.434Z SendDataTCPServer.js: TCP/IP server has received 52568 bytes of data
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:33.695Z SendDataTCPServer.js: TCP/IP server has received 54548 bytes of data
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:33.702Z SendDataTCPServer.js: TCP/IP server has received 56528 bytes of data
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:33.710Z SendDataTCPServer.js: TCP/IP server has received 58508 bytes of data
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:33.783Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:34.047Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:34.522Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:34.893Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:35.168Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:35.354Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:35.387Z SendDataTCPServer.js: TCP/IP server has received 60488 bytes of data
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:35.417Z SendDataTCPServer.js: TCP/IP server has received 62468 bytes of data
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:35.451Z SendDataTCPServer.js: TCP/IP server has received 68408 bytes of data
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:35.472Z SendDataTCPServer.js: TCP/IP server has received 70388 bytes of data
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:35.502Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:35.513Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:35.561Z SendDataTCPServer.js: TCP/IP server has received 72368 bytes of data
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:35.591Z SendDataTCPServer.js: TCP/IP server has received 76328 bytes of data
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:35.622Z SendDataTCPServer.js: TCP/IP server has received 78308 bytes of data
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:35.633Z SendDataTCPServer.js: TCP/IP server has received 80288 bytes of data
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:35.644Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:35.645Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): oneRoundDownNow
I/jxcore-log( 3220): 
I/jxcore-log( 3220): 2015-12-23T02:16:35.653Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3220): 
I/jxcore-log( 3220): 2015-12-23T02:16:35.654Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3220): 
D/io.jxcore.node.ConnectionHelper( 3220): disconnectOutgoingConnection: Trying to close connection to peer with ID B0:C5:59:3F:75:69
I/io.jxcore.node.ConnectionHelper( 3220): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: B0:C5:59:3F:75:69
I/io.jxcore.node.OutgoingSocketThread( 3220): close
D/io.jxcore.node.OutgoingSocketThread( 3220): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3220): doStop: Thread ID: 321
D/io.jxcore.node.OutgoingSocketThread( 3220): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3220): doStop: Thread ID: 320
D/io.jxcore.node.OutgoingSocketThread( 3220): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 3220): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3220): Either failed to read from the output stream or write to the input stream (thread ID: 320, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3220): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3220): onDisconnected: Outgoing connection, peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 3220): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 3220): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3220): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3220): Either failed to read from the output stream or write to the input stream (thread ID: 321, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.OutgoingSocketThread( 3220): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3220): onDisconnected: Outgoing connection, peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3220): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3220): disconnectOutgoingConnection: Successfully disconnected (peer ID: B0:C5:59:3F:75:69
,E/io.jxcore.node.ConnectionHelper( 3220): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID B0:C5:59:3F:75:69
D/io.jxcore.node.ConnectionHelper( 3220): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,E/io.jxcore.node.ConnectionHelper( 3220): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID B0:C5:59:3F:75:69
D/io.jxcore.node.ConnectionHelper( 3220): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3220): Exiting thread (ID: 321, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 3220): Exiting thread (ID: 320, name: Sender)
,I/jxcore-log( 3220): 2015-12-23T02:16:35.697Z SendDataConnector.js: Mobile.Disconnect() callback with peer B0:C5:59:3F:75:69
I/jxcore-log( 3220): 
I/jxcore-log( 3220): ---- round done--------
I/jxcore-log( 3220): 
I/jxcore-log( 3220): startWithNextDevice
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:35.701Z SendDataTCPServer.js: TCP/IP server has received 82268 bytes of data
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:35.720Z SendDataTCPServer.js: TCP/IP server has received 84248 bytes of data
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:35.751Z SendDataTCPServer.js: TCP/IP server has received 86228 bytes of data
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:35.781Z SendDataTCPServer.js: TCP/IP server has received 88208 bytes of data
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:35.840Z SendDataTCPServer.js: TCP/IP server has received 90188 bytes of data
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:35.900Z SendDataTCPServer.js: TCP/IP server has received 92168 bytes of data
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:35.941Z SendDataTCPServer.js: TCP/IP server has received 94148 bytes of data
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:35.961Z SendDataTCPServer.js: TCP/IP server has received 96128 bytes of data
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:16:35.967Z SendDataTCPServer.js: TCP/IP server has received 98108 bytes of data
I/jxcore-log( 3220): 
,W/bt-btif ( 2139): bta_jv_rfc_port_to_cb(port_handle:0xd):jv handle:0x0 not FOUND
,I/jxcore-log( 3220): 2015-12-23T02:16:35.979Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3220): 
,W/bt-btif ( 2139): invalid rfc slot id: 8
,W/io.jxcore.node.StreamCopyingThread( 3220): Either failed to read from the output stream or write to the input stream (thread ID: 317, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.OutgoingSocketThread( 3220): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3220): onDisconnected: Incoming connection, peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3220): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 315
D/io.jxcore.node.OutgoingSocketThread( 3220): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3220): doStop: Thread ID: 317
D/io.jxcore.node.OutgoingSocketThread( 3220): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3220): doStop: Thread ID: 316
D/io.jxcore.node.OutgoingSocketThread( 3220): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 3220): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3220): Either failed to read from the output stream or write to the input stream (thread ID: 316, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3220): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3220): onDisconnected: Incoming connection, peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT6068] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.OutgoingSocketThread( 3220): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 3220): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3220): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3220): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3220): Exiting thread (ID: 317, name: Receiver)
,D/io.jxcore.node.ConnectionHelper( 3220): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 3220): Exiting thread (ID: 316, name: Sender)
,W/bt-rfcomm( 2139): rfc_find_lcid_mcb LCID reused LCID:0x46 current:0x0
W/bt-rfcomm( 2139): RFCOMM_DisconnectInd LCID:0x46
,I/jxcore-log( 3220): 2015-12-23T02:16:36.234Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3220): 
,D/btif_config_util( 2139): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2139): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2139): onReceive
,I/BTConnectionReceiver( 1377): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1377): Bluetooth Device Name: Thali Test (Galaxy S5)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3220): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3220): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3220): setState: RESTARTING
,I/wpa_supplicant( 1024): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1024): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 1024): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
I/wpa_supplicant( 1024): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3220): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3220): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3220): onP2pDeviceListChanged: 0 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3220): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3220): Start timer timeout, starting now...
,I/wpa_supplicant( 1024): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3220): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3220): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3220): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1024): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1024): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1024): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1024): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3220): onP2pDeviceListChanged: 1 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3220): restart: Restarting...
,D/WifiP2pManager( 3220): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3220): Service request added successfully
,I/wpa_supplicant( 1024): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1024): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1024): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1024): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3220): Service discovery started successfully
,I/jxcore-log( 3220): timeout now
I/jxcore-log( 3220): 
I/jxcore-log( 3220): weAreDoneNow, resultArray.length: 2
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): sendReportNow
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): done, now sending data to server
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:17:37.006Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3220): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3220): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3220): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3220): setState: RESTARTING
,I/wpa_supplicant( 1024): P2P-FIND-STOPPED 
I/wpa_supplicant( 1024): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3220): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3220): onP2pDeviceListChanged: 0 device(s) discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3220): Start timer timeout, starting now...
,I/wpa_supplicant( 1024): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3220): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3220): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3220): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1024): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1024): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3220): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3220): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3220): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/WifiP2pManager( 3220): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3220): Service request added successfully
,I/wpa_supplicant( 1024): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1024): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1024): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3220): Service discovery started successfully
,I/wpa_supplicant( 1024): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 1024): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 1024): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3220): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3220): onP2pDeviceListChanged: 2 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,I/jxcore-log( 3220): teardown
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): testSendData stopped
I/jxcore-log( 3220): 
I/io.jxcore.node.ConnectionHelper( 3220): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3220): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3220): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3220): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3220): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3220): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3220): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3220): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3220): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3220): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3220): stop: Stopping P2P device discovery...
,I/wpa_supplicant( 1024): P2P-FIND-STOPPED 
,I/wpa_supplicant( 1024): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant( 1024): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3220): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3220): release: No more listeners, de-initializing...
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3220): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3220): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3220): setState: NOT_STARTED
I/jxcore-log( 3220): StopBroadcasting went ok
I/jxcore-log( 3220): 
,I/jxcore-log( 3220): 2015-12-23T02:17:57.559Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
I/jxcore-log( 3220): 
I/chromium( 3220): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
,I/io.jxcore.node.ConnectionHelper( 3220): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3220): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3220): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3220): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 3220): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 3220): ****TEST TOOK:  ms ****
I/jxcore-log( 3220): 
I/jxcore-log( 3220): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3220): 
,D/AndroidRuntime( 3647): 
D/AndroidRuntime( 3647): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 3647): CheckJNI is OFF
,D/AndroidRuntime( 3647): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  758): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  758): Killing 3220:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
,I/WindowState(  758): WIN DEATH: Window{16f2adda u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  758): Client connection lost with reason: 4
,W/PackageSettings(  758): Skipping PackageSetting{a30af8e com.example.hello/10278} due to missing metadata
,I/ActivityManager(  758):   Force finishing activity ActivityRecord{24744607 u0 com.test.thalitest/.MainActivity t214}
,W/ActivityManager(  758): Spurious death for ProcessRecord{3d240313 3220:com.test.thalitest/u0a270}, curProc for 3220: null
,I/ActivityManager(  758): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
,I/art     ( 1343): Explicit concurrent mark sweep GC freed 3953(294KB) AllocSpace objects, 1(126KB) LOS objects, 38% free, 25MB/41MB, paused 562us total 19.349ms
,I/art     ( 1377): Explicit concurrent mark sweep GC freed 12660(526KB) AllocSpace objects, 3(48KB) LOS objects, 25% free, 18MB/25MB, paused 535us total 59.314ms
,W/GeofencerStateMachine( 1664): Ignoring removeGeofence because network location is disabled.
,I/Keyboard.Facilitator( 1106): resetDictionaries() : en_US
,I/Keyboard.Facilitator.DecoderInitializer( 1106): run()
,I/Decoder ( 1106): createOrResetDecoder
,I/InputReader(  758): Reconfiguring input devices.  changes=0x00000010
,I/art     ( 1688): Explicit concurrent mark sweep GC freed 7798(374KB) AllocSpace objects, 1(16KB) LOS objects, 25% free, 22MB/30MB, paused 1.012ms total 77.887ms
,I/LibraryLoader( 1517): Loading chrome directly from within /data/app/com.android.chrome-1/base.apk
I/art     (  758): Explicit concurrent mark sweep GC freed 34940(1818KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 1.080ms total 80.649ms
I/art     (  758): WaitForGcToComplete blocked for 36.846ms for cause Explicit
,D/VoicemailCleanupService( 1391): Cleaning up data for package: com.test.thalitest
,I/OpenGLRenderer(  940): Initialized EGL, version 1.4
D/OpenGLRenderer(  940): Enabling debug mode 0
,I/LibraryLoader( 1517): Time to load native libraries: 68 ms (timestamps 9978-46)
I/LibraryLoader( 1517): Expected native library version number "44.0.2403.133",actual native library version number "44.0.2403.133"
I/chromium( 1517): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
W/art     ( 1517): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 1517): Attempt to remove local handle scope entry from IRT, ignoring
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1106): run()
,I/UpdateIcingCorporaServi( 1377): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,W/Launcher( 1343): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@b7d6fcb new=com.google.android.velvet.VelvetApplication@b7d6fcb
,W/art     (  940): Attempt to remove local handle scope entry from IRT, ignoring
,I/ActivityManager(  758): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3693 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,D/BackupManagerService(  758): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService(  758): Receieved: android.intent.action.PACKAGE_REMOVED
,D/TaskPersister(  758): removeObsoleteFile: deleting file=214_task.xml
,W/InputMethodManagerService(  758): Got RemoteException sending setActive(false) notification to pid 3220 uid 10270
,I/Keyboard.Facilitator( 1106): onFinishInput()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1106): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1106): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1106): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1106): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1106): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1106): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1106): run() : Loading LM = user
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1106): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1106): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1106): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1106): run()
I/StatsUtilsManager( 1106): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1106): shouldRecordStats() = Too Soon
,W/ContextImpl( 3693): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
,D/PackageBroadcastService( 1688): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/ChimeraCfgMgr( 1688): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1688): Module APK com.google.android.play.games already loaded
,D/AccountUtils( 1688): Clearing selected account for com.test.thalitest
,I/Keyboard.Facilitator( 1106): onFinishInput()
,D/ChimeraCfgMgr( 1688): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1688): Module APK com.google.android.play.games already loaded
,E/NetworkScheduler.SchedulerReceiver( 1664): Invalid parameter app
,E/NetworkScheduler.SchedulerReceiver( 1664): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/UpdateIcingCorporaServi( 1377): UpdateCorporaTask done [took 155 ms] updated apps [took 155 ms] 
,I/ActivityManager(  758): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3727 uid=10039 gids={50039, 9997} abi=armeabi-v7a
,I/art     (  758): Explicit concurrent mark sweep GC freed 10827(534KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 1.423ms total 277.743ms
,I/LocationSettingsChecker( 1688): Removing dialog suppression flag for package com.test.thalitest
,I/Launcher( 1343): Deferring update until onResume
,W/ResourcesManager( 1343): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 1343): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/gH_CompatibleDatabase( 1688): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1688): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1688): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1688): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/gH_CompatibleDatabase( 1688): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1688): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1688): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,I/Launcher( 1343): Deferring update until onResume
,W/InputMethodManagerService(  758): Starting input on non-focused client com.android.internal.view.IInputMethodClient$Stub$Proxy@13aed159 (uid=10034 pid=940)
,D/gH_CompatibleDatabase( 1688): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1688): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 1688): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1688): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1688): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1688): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,W/BaseAppContext( 1688): Using Auth Proxy for data requests.
,W/BaseAppContext( 1688): Using Auth Proxy for data requests.
,I/GMPM-SVC( 1688): App measurement is starting up, version: 8489
I/GMPM-SVC( 1688): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,I/ActivityManager(  758): Killing 2582:com.google.android.gm/u0a70 (adj 15): empty #17
,D/AndroidRuntime( 3647): Shutting down VM
,W/InputMethodManagerService(  758): Starting input on non-focused client com.android.internal.view.IInputMethodClient$Stub$Proxy@13aed159 (uid=10034 pid=940)
,W/IInputConnectionWrapper(  940): showStatusIcon on inactive InputConnection
,W/libprocessgroup(  758): failed to open /acct/uid_10070/pid_2582/cgroup.procs: No such file or directory
,I/ActivityManager(  758): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3755 uid=10007 gids={50007, 9997, 1028, 1015, 1023} abi=armeabi-v7a
,I/Icing   ( 1688): doRemovePackageData com.test.thalitest
,I/ActivityManager(  758): Killing 1995:com.google.android.calendar/u0a31 (adj 15): empty #17
,W/libprocessgroup(  758): failed to open /acct/uid_10031/pid_1995/cgroup.procs: No such file or directory
,D/ExternalStorage( 3755): After updating volumes, found 1 active roots
,W/ResourcesManager( 3138): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3138): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/Documents( 3727): Update found 7 roots in 409ms
,D/Documents( 3727): Update found 7 roots in 189ms

```
