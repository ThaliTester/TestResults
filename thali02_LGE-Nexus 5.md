#### Test 56151093f6e24ff_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
I/GAv4    ( 3173): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3173):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3173):   adb logcat -s GAv4
W/GAv4    ( 3173): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3173): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3173): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 3173): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
D/Finsky  ( 2651): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
W/ResourcesManager( 3173): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3173): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  734): Killing 2080:com.google.android.deskclock/u0a38 (adj 15): empty #17
V/JNIHelp ( 3173): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/libprocessgroup(  734): failed to open /acct/uid_10038/pid_2080/cgroup.procs: No such file or directory
W/System  ( 3173): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3173): Installed default security provider GmsCore_OpenSSL
V/GLSActivity( 1583): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 1639): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/Icing   ( 1639): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1639): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/Icing   ( 1639): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
I/ActivityManager(  734): Killing 2606:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
W/libprocessgroup(  734): failed to open /acct/uid_10069/pid_2606/cgroup.procs: No such file or directory
,D/AndroidRuntime( 3230): 
D/AndroidRuntime( 3230): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3230): CheckJNI is OFF
D/AndroidRuntime( 3230): Calling main entry com.android.commands.am.Am
I/ActivityManager(  734): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  734): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3251 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3230): Shutting down VM
V/ActivityManager(  734): Display changed displayId=0
I/WebViewFactory( 3251): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3251): Time to load native libraries: 1 ms (timestamps 1524-1525)
I/LibraryLoader( 3251): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3251): Binding Chromium to main looper Looper (main, tid 1) {3437e062}
I/LibraryLoader( 3251): Expected native library version number "",actual native library version number ""
I/chromium( 3251): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3251): Initializing chromium process, singleProcess=true
W/art     ( 3251): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3251): ApplicationContext is null in ApplicationStatus
,W/chromium( 3251): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3251): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3251): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3251): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  734): Message: 20
D/BluetoothManagerService(  734): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@124bdf84:true
,W/art     ( 3251): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3251): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3251): CordovaWebView is running on device made by: LGE
,W/art     ( 3251): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3251): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3251): Render dirty regions requested: true
,D/Atlas   ( 3251): Validating map...
,W/chromium( 3251): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3251): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3251): Enabling debug mode 0
,I/Keyboard.Facilitator( 1100): onFinishInput()
W/IInputConnectionWrapper( 3251): showStatusIcon on inactive InputConnection
,I/ActivityManager(  734): Displayed com.test.thalitest/.MainActivity: +416ms (total +55s813ms)
,W/BindingManager( 3251): Cannot call determinedVisibility() - never saw a connection for the pid: 3251
,D/CAR.SERVICE( 3046): mConnectedToCar = false, abort
,E/ActivityThread( 3046): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@1e4e723b that was originally bound here
E/ActivityThread( 3046): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@1e4e723b that was originally bound here
E/ActivityThread( 3046): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3046): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3046): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3046): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3046): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3046): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3046): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3046): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3046): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3046): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 3046): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 3046): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 3046): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 3046): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2731)
E/ActivityThread( 3046): 	at android.app.ActivityThread.access$1800(ActivityThread.java:144)
E/ActivityThread( 3046): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1361)
E/ActivityThread( 3046): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3046): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3046): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3046): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3046): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3046): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3046): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
,E/ActivityThread( 3046): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@2475bf22 that was originally bound here
E/ActivityThread( 3046): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@2475bf22 that was originally bound here
E/ActivityThread( 3046): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3046): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3046): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3046): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3046): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3046): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3046): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3046): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 3046): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 3046): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 3046): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 3046): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 3046): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2758)
E/ActivityThread( 3046): 	at android.app.ActivityThread.access$1900(ActivityThread.java:144)
E/ActivityThread( 3046): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
E/ActivityThread( 3046): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3046): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3046): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3046): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3046): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3046): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3046): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
,W/ActivityManager(  734): Unbind failed: could not find connection for android.os.BinderProxy@2ed0ed9
,D/JsMessageQueue( 3251): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3251): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257332480
D/JX-Cordova( 3251): jxcore cordova android initializing
,W/jxcore-log( 3251): Initializing JXcore engine
W/jxcore-log( 3251): JXcore engine is ready
,W/jxcore-log( 3251): Starting JXcore engine
,W/.test.thalitest( 3251): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[6411]" dev="sockfs" ino=6411 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3251): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
,W/.test.thalitest( 3251): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8550]" dev="sockfs" ino=8550 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3251): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[19642]" dev="sockfs" ino=19642 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3251): Platform android
W/jxcore-log( 3251): 
W/jxcore-log( 3251): Process ARCH arm
W/jxcore-log( 3251): 
,I/jxcore-log( 3251): JXcore Cordova bridge is ready!
I/jxcore-log( 3251): 
,W/jxcore-log( 3251): JXcore engine is started
I/chromium( 3251): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3251): Toggling radios to true
I/jxcore-log( 3251): 
,D/BluetoothAdapter( 3251): enable(): BT is already enabled..!
,D/WifiService(  734): New client listening to asynchronous messages
D/WifiService(  734): setWifiEnabled: true pid=3251, uid=10270
E/WifiService(  734): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3251): Radios toggled
I/jxcore-log( 3251): 
I/jxcore-log( 3251): My device name is: LGE-Nexus 5
I/jxcore-log( 3251): 
,I/wpa_supplicant(  981): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  734): WifiStateMachine: Leaving Connected state
,E/WifiConfigStore(  734): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
E/native  (  734): do suspend true
,D/CommandListener(  181): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1583): Read error: ssl=0x9ad05e00: I/O error during system call, Connection timed out
E/WifiConfigStore(  734): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  734): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  734): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,V/NativeCrypto( 1583): SSL shutdown failed: ssl=0x9ad05e00: I/O error during system call, Broken pipe
,E/WifiStateMachine(  734): Start Disconnecting Watchdog 1
,I/wpa_supplicant(  981): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/ConnectivityService(  734): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
E/native  (  734): do suspend true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): ValidatedState{ when=-1ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): DefaultState{ when=-1ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): Checking http://clients3.google.com/generate_204 on <unknown ssid>
,D/CommandListener(  181): Clearing all IP addresses on wlan0
,D/ConnectivityService(  734): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/Nat464Xlat(  734): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  734): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityManager.CallbackHandler(  898): CM callback handler got msg 524292
D/ConnectivityService(  734): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1639): CM callback handler got msg 524292
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  734): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): Disconnected - quitting
D/ConnectivityService(  734): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory( 1250): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WifiNetworkAgent(  734): NetworkAgent: NetworkAgent channel lost
,I/wpa_supplicant(  981): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant(  981): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant(  981): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant(  981): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  734): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  734): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  734): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiConfigStore(  734): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/CommandListener(  181): Setting iface cfg
E/WifiStateMachine(  734): Start Dhcp Watchdog 2
,E/native  (  734): do suspend false
,E/WifiStateMachine(  734): scanCount==0 - aborting
,I/dhcpcd  ( 3326): version 5.5.6 starting
E/dhcpcd  ( 3326): get_duid: Read-only file system
,I/dhcpcd  ( 3326): wlan0: rebinding lease of 192.168.1.114
,I/jxcore-log( 3251): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3251): 
,I/dhcpcd  ( 3326): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3326): wlan0: leased 192.168.1.114 for 86400 seconds
,W/NetworkUtils( 1389): OkHttp exception
,W/EventLoggerService( 1389): Unable to send logs Error code: 262146
,I/jxcore-log( 3251): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 3251): 
,E/native  (  734): do suspend true
,I/jxcore-log( 3251): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3251): 
,D/ConnectivityService(  734): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,E/WifiStateMachine(  734): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/ConnectivityService(  734): Adding iface wlan0 to network 101
,E/ConnectivityService(  734): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  734): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  734): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  734): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  734): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  734): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  734): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  734): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  734): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  734):    accepting network in place of null
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/CSLegacyTypeTracker(  734): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  734): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  734): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService(  734): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1639): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler(  898): CM callback handler got msg 524290
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 18 Jan 2016 13:53:26 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1453125206425], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1453125206412]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): Don't send network conditions - lacking user consent.
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): Validated
D/ConnectivityService(  734): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  734): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  734): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  734): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler(  898): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1639): CM callback handler got msg 524290
,D/ConnectivityService(  734): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/TelephonyNetworkFactory( 1250): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/jxcore-log( 3251): Test app app.js loaded
I/jxcore-log( 3251): 
,I/chromium( 3251): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/ConnectivityService(  734): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  734): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  734): MasterInitialState.processMessage what=3
,D/Tethering(  734): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2761): type=WIFI subType= reason=null isConnected=true
,E/GpsLocationProvider(  734): No APN found to select.
,V/MusicLeanback( 2761): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 2761): type=WIFI subType= reason=null isConnected=true
,E/GpsLocationProvider(  734): No APN found to select.
,D/Nat464Xlat(  734): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  734): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  898): CM callback handler got msg 524295
D/ConnectivityManager.CallbackHandler( 1639): CM callback handler got msg 524295
I/SystemUpdateService( 1639): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1639): onCreate
,D/SystemUpdateService( 1639): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1639): active receiver: enabled
I/SystemUpdateService( 1639): showing system update notification
,V/SystemUpdateService( 1639): retry (wakeup: false) in 3599986 ms
,I/ValidateNoPeople(  734): skipping global notification
,D/SystemUpdateService( 1639): onDestroy
,I/ActivityManager(  734): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3390 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GAv4    ( 3390): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3390):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3390):   adb logcat -s GAv4
,W/GAv4    ( 3390): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3390): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3390): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 3390): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3390): Time to load native libraries: 2 ms (timestamps 7834-7836)
I/LibraryLoader( 3390): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3390): Binding Chromium to main looper Looper (main, tid 1) {16976704}
,I/LibraryLoader( 3390): Expected native library version number "",actual native library version number ""
,I/chromium( 3390): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3390): Initializing chromium process, singleProcess=true
,W/art     ( 3390): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3390): ApplicationContext is null in ApplicationStatus
,W/chromium( 3390): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3390): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3390): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3390): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/AudioManagerAndroid( 3390): Requires BLUETOOTH permission
,I/NSApplication( 3390): Starting up...
,I/ActivityManager(  734): Killing 2547:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,D/ConnectivityService(  734): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,W/libprocessgroup(  734): failed to open /acct/uid_10045/pid_2547/cgroup.procs: No such file or directory
,V/MusicLeanback( 2761): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1639): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1639): onCreate
,D/SystemUpdateService( 1639): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1639): active receiver: enabled
,I/SystemUpdateService( 1639): showing system update notification
,I/ValidateNoPeople(  734): skipping global notification
,V/SystemUpdateService( 1639): retry (wakeup: false) in 3599975 ms
,D/SystemUpdateService( 1639): onDestroy
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 3251): BLE advertisement is supported
I/jxcore-log( 3251): 
,D/ConnectivityService(  734): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  734): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2761): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2761): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1639): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1639): onCreate
,D/SystemUpdateService( 1639): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1639): active receiver: enabled
,I/SystemUpdateService( 1639): showing system update notification
,E/GpsLocationProvider(  734): No APN found to select.
,I/ValidateNoPeople(  734): skipping global notification
,V/SystemUpdateService( 1639): retry (wakeup: false) in 3599978 ms
,D/SystemUpdateService( 1639): onDestroy
,D/Finsky  ( 2651): [255] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2651): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/art     (  734): Explicit concurrent mark sweep GC freed 47903(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 27MB/41MB, paused 1.131ms total 74.794ms
,V/GLSActivity( 1583): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1583): Vacuum at: now=1453125226669 tag=VacuumService
,I/PhenotypeConfigurator( 1583): Scheduling Phenotype for one-off execution 5667 seconds from now (1453125227049)
,D/GetConfigurationSnapshotOperation( 1583): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1583): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1583): Using platform SSLCertificateSocketFactory
,V/GLSActivity( 1583): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1583): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Keyboard.Facilitator.LanguageModelFlusher( 1100): run()
I/Keyboard.Facilitator( 1100): flushDynamicLanguageModels()
,I/ClearcutLoggerApiImpl( 1583): disconnect managed GoogleApiClient
,I/jxcore-log( 3251): TAP version 13
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): # setup
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): # multiplex can send data
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): # teardown
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): ok 1 String should be length:200
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): # setup
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): # basic
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): # teardown
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): ok 2 sane
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): # setup
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): # another
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): # teardown
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): ok 3 sane
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): # setup
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): # successfully create a new pkcs12 file and return hash value
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): # teardown
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): ok 4 should be equal
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): ok 5 null
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): ok 6 (unnamed assert)
I/jxcore-log( 3251): 
I/jxcore-log( 3251): ok 7 should be equal
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): ok 8 should not throw
I/jxcore-log( 3251): 
I/jxcore-log( 3251): # setup
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): # successfully read a previous pkcs12 file and return hash value
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): # teardown
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): ok 9 (unnamed assert)
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): ok 10 (unnamed assert)
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): ok 11 should not throw
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): ok 12 should be equal
I/jxcore-log( 3251): 
I/jxcore-log( 3251): ok 13 should be equal
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): # setup
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): # failed to extract public key because of corrupt pkcs12 file
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): # teardown
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): ok 14 should be equal
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): # setup
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): # failed to get mobile documents path
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): # teardown
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): ok 15 should be equal
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): # setup
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): # #init should register the peerAvailabilityChanged event
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): # teardown
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): ok 16 should be equal
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): ok 17 should be equal
I/jxcore-log( 3251): 
I/jxcore-log( 3251): ok 18 should be equal
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): # setup
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): # #init should register the networkChanged event
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): # teardown
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): ok 19 should be equal
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): # setup
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): # #startBroadcasting should throw on null device name
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): # teardown
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): ok 20 should throw
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): # setup
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): # #startBroadcasting should throw on empty string device name
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): # teardown
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): ok 21 should throw
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): # setup
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): # #startBroadcasting should throw on non-number port
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): # teardown
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): ok 22 should throw
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): # setup
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): # #startBroadcasting should throw on NaN port
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): # teardown
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): ok 23 should throw
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): # setup
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): # #startBroadcasting should throw on negative port
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): # teardown
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): ok 24 should throw
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): # setup
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): # #startBroadcasting should throw on too large port
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): # teardown
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): ok 25 should throw
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): # setup
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): # #startBroadcasting should call Mobile("StartBroadcasting") without an error
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): # teardown
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): ok 26 should be equal
I/jxcore-log( 3251): 
I/jxcore-log( 3251): ok 27 should be equal
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): ok 28 should be equal
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): # setup
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): # #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): # teardown
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): ok 29 should be equal
I/jxcore-log( 3251): 
I/jxcore-log( 3251): ok 30 should be equal
I/jxcore-log( 3251): 
I/jxcore-log( 3251): ok 31 should be equal
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): # setup
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): # #stopBroadcasting should call Mobile("StopBroadcasting") without an error
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): # teardown
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): ok 32 should be equal
I/jxcore-log( 3251): 
I/jxcore-log( 3251): ok 33 should be equal
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): # setup
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): # #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): # teardown
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): ok 34 should be equal
I/jxcore-log( 3251): 
I/jxcore-log( 3251): ok 35 should be equal
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): # setup
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): # #connect should call Mobile("Connect") with a port and without an error
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): # teardown
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): ok 36 should be equal
I/jxcore-log( 3251): 
I/jxcore-log( 3251): ok 37 should be equal
I/jxcore-log( 3251): 
I/jxcore-log( 3251): ok 38 should be equal
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): # setup
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): # #connect should call Mobile("Connect") and handle an error
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): # teardown
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): ok 39 should be equal
I/jxcore-log( 3251): 
I/jxcore-log( 3251): ok 40 should be equal
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): # setup
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): # should call Mobile("Disconnect") without an error
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): # teardown
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): ok 41 should be equal
I/jxcore-log( 3251): 
I/jxcore-log( 3251): ok 42 should be equal
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): # setup
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): # should call Mobile("Disconnect") and handle an error
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): # teardown
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): ok 43 should be equal
I/jxcore-log( 3251): 
I/jxcore-log( 3251): ok 44 should be equal
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): # setup
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): # ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): # teardown
I/jxcore-log( 3251): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): setDiscoveryMode: Mode set to BLE_AND_WIFI
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3251): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453125474554.3251
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3251): bind: Binding a new listener
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3251): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3251): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453125474554.3251","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3251): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3251): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3251): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3251): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3251): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3251): start: OK
I/io.jxcore.node.ConnectionHelper( 3251): start: Using peer discovery mode: BLE_AND_WIFI
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453125474554.3251
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3251): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3251): bind: Binding a new listener
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3251): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3251): createAdvertiseData: From: 1453125474554.3251 b6a44ad1-d319-4b3a-815d-8b805a47fb51 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3251): 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3251): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 52, -4, -17, 17, -82, 103]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3251): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3251): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453125474554.3251","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3251): start: {"pi":"34:FC:EF:11:AE:67","pn":"1453125474554.3251","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3251): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1453125474554.3251","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3251): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3251): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3251): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): setState: RUNNING_WIFI
,I/io.jxcore.node.ConnectionHelper( 3251): start: OK
,I/wpa_supplicant(  981): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3251): ok 45 Should be able to call startBroadcasting without error
I/jxcore-log( 3251): 
I/io.jxcore.node.ConnectionHelper( 3251): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3251): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3251): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3251): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3251): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3251): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3251): onServerStopped
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3251): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3251): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): stop: Stopping peer discovery...
,D/BluetoothLeScanner( 3251): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3251): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3251): stop: Stopping P2P device discovery...
,I/wpa_supplicant(  981): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3251): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): stopWifiPeerDiscovery: Stopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3251): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3251): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): setState: NOT_STARTED
,I/jxcore-log( 3251): ok 46 Should be able to call stopBroadcasting without error
I/jxcore-log( 3251): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): setDiscoveryMode: Mode set to BLE_AND_WIFI
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3251): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453125474620.3251
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3251): bind: Binding a new listener
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3251): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3251): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453125474620.3251","ra":"34:FC:EF:11:AE:67"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3251): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3251): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3251): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3251): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3251): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3251): start: OK
I/io.jxcore.node.ConnectionHelper( 3251): start: Using peer discovery mode: BLE_AND_WIFI
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453125474620.3251
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3251): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3251): bind: Binding a new listener
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3251): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3251): createAdvertiseData: From: 1453125474620.3251 b6a44ad1-d319-4b3a-815d-8b805a47fb51 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3251): 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3251): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 52, -4, -17, 17, -82, 103]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3251): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3251): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453125474620.3251","ra":"34:FC:EF:11:AE:67"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3251): start: {"pi":"34:FC:EF:11:AE:67","pn":"1453125474620.3251","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3251): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1453125474620.3251","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3251): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3251): start: Starting P2P device discovery...
,I/wpa_supplicant(  981): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): setState: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 3251): start: OK
I/jxcore-log( 3251): ok 47 Should be able to call startBroadcasting without error
I/jxcore-log( 3251): 
I/io.jxcore.node.ConnectionHelper( 3251): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3251): stop: Stopping Bluetooth...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3251): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3251): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3251): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3251): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3251): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): stop: Stopping peer discovery...
,D/BluetoothLeScanner( 3251): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3251): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3251): stop: Stopping P2P device discovery...
,I/wpa_supplicant(  981): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3251): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3251): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3251): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): setState: NOT_STARTED
,I/jxcore-log( 3251): ok 48 Should be able to call stopBroadcasting without error
I/jxcore-log( 3251): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): setDiscoveryMode: Mode set to BLE_AND_WIFI
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3251): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453125474653.3251
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3251): bind: Binding a new listener
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3251): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3251): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3251): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3251): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453125474653.3251","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3251): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3251): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3251): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3251): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3251): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3251): start: OK
I/io.jxcore.node.ConnectionHelper( 3251): start: Using peer discovery mode: BLE_AND_WIFI
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453125474653.3251
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3251): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3251): bind: Binding a new listener
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3251): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3251): createAdvertiseData: From: 1453125474653.3251 b6a44ad1-d319-4b3a-815d-8b805a47fb51 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3251): 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3251): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 52, -4, -17, 17, -82, 103]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3251): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3251): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453125474653.3251","ra":"34:FC:EF:11:AE:67"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3251): start: {"pi":"34:FC:EF:11:AE:67","pn":"1453125474653.3251","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3251): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1453125474653.3251","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3251): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3251): start: Starting P2P device discovery...
,I/wpa_supplicant(  981): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): setState: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 3251): start: OK
I/jxcore-log( 3251): ok 49 Should be able to call startBroadcasting without error
I/jxcore-log( 3251): 
I/io.jxcore.node.ConnectionHelper( 3251): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3251): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3251): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3251): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3251): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3251): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3251): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): stop: Stopping peer discovery...
,D/BluetoothLeScanner( 3251): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3251): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3251): stop: Stopping P2P device discovery...
,I/wpa_supplicant(  981): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3251): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3251): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3251): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): setState: NOT_STARTED
,I/jxcore-log( 3251): ok 50 Should be able to call stopBroadcasting without error
I/jxcore-log( 3251): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): setDiscoveryMode: Mode set to BLE_AND_WIFI
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3251): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453125474688.3251
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3251): bind: Binding a new listener
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3251): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3251): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453125474688.3251","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3251): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3251): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3251): startListeningForIncomingConnections: Starting...
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3251): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3251): onServerStopped
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3251): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3251): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3251): start: OK
I/io.jxcore.node.ConnectionHelper( 3251): start: Using peer discovery mode: BLE_AND_WIFI
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453125474688.3251
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3251): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3251): bind: Binding a new listener
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3251): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3251): createAdvertiseData: From: 1453125474688.3251 b6a44ad1-d319-4b3a-815d-8b805a47fb51 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3251): 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3251): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 52, -4, -17, 17, -82, 103]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3251): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3251): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453125474688.3251","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3251): start: {"pi":"34:FC:EF:11:AE:67","pn":"1453125474688.3251","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3251): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1453125474688.3251","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3251): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3251): start: Starting P2P device discovery...
,I/wpa_supplicant(  981): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): setState: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 3251): start: OK
I/jxcore-log( 3251): ok 51 Should be able to call startBroadcasting without error
I/jxcore-log( 3251): 
I/io.jxcore.node.ConnectionHelper( 3251): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3251): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3251): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3251): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3251): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3251): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3251): onServerStopped
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3251): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3251): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): stop: Stopping peer discovery...
,D/BluetoothLeScanner( 3251): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3251): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3251): stop: Stopping P2P device discovery...
,I/wpa_supplicant(  981): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3251): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3251): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3251): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): setState: NOT_STARTED
,I/jxcore-log( 3251): ok 52 Should be able to call stopBroadcasting without error
I/jxcore-log( 3251): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3251): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453125474728.3251
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3251): bind: Binding a new listener
D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3251): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3251): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453125474728.3251","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3251): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3251): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3251): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3251): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3251): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3251): start: OK
I/io.jxcore.node.ConnectionHelper( 3251): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453125474728.3251
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3251): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3251): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3251): Waiting for incoming connections...
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3251): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3251): createAdvertiseData: From: 1453125474728.3251 b6a44ad1-d319-4b3a-815d-8b805a47fb51 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3251): 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3251): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 52, -4, -17, 17, -82, 103]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3251): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3251): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453125474728.3251","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3251): start: {"pi":"34:FC:EF:11:AE:67","pn":"1453125474728.3251","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3251): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1453125474728.3251","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3251): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3251): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): setState: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 3251): start: OK
,I/wpa_supplicant(  981): p2p0: P2P: Reject scan trigger since one is already pending
,I/jxcore-log( 3251): ok 53 Should be able to call startBroadcasting without error
I/jxcore-log( 3251): 
I/io.jxcore.node.ConnectionHelper( 3251): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3251): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3251): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3251): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3251): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3251): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3251): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): stop: Stopping peer discovery...
D/BluetoothLeScanner( 3251): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3251): stop: Stopping services
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3251): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3251): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3251): stop: Stopping P2P device discovery...
,I/wpa_supplicant(  981): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3251): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): onIsWifiPeerDiscoveryStartedChanged: false
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3251): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3251): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): setState: NOT_STARTED
,I/jxcore-log( 3251): ok 54 Should be able to call stopBroadcasting without error
I/jxcore-log( 3251): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3251): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453125474757.3251
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3251): bind: Binding a new listener
D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3251): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3251): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453125474757.3251","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3251): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3251): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3251): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3251): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3251): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3251): start: OK
I/io.jxcore.node.ConnectionHelper( 3251): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453125474757.3251
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3251): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3251): bind: Binding a new listener
D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3251): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3251): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3251): createAdvertiseData: From: 1453125474757.3251 b6a44ad1-d319-4b3a-815d-8b805a47fb51 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3251): 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3251): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 52, -4, -17, 17, -82, 103]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3251): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3251): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453125474757.3251","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3251): start: {"pi":"34:FC:EF:11:AE:67","pn":"1453125474757.3251","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3251): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1453125474757.3251","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3251): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3251): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): onIsWifiPeerDiscoveryStartedChanged: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): start: OK
,I/wpa_supplicant(  981): p2p0: P2P: Reject scan trigger since one is already pending
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): setState: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 3251): start: OK
I/jxcore-log( 3251): ok 55 Should be able to call startBroadcasting without error
I/jxcore-log( 3251): 
I/io.jxcore.node.ConnectionHelper( 3251): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3251): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3251): Shutting down...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3251): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3251): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3251): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3251): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3251): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3251): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): stop: Stopping peer discovery...
,D/BluetoothLeScanner( 3251): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3251): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3251): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3251): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3251): release: No more listeners, de-initializing...
,I/wpa_supplicant(  981): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3251): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): setState: NOT_STARTED
I/jxcore-log( 3251): ok 56 Should be able to call stopBroadcasting without error
I/jxcore-log( 3251): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): setDiscoveryMode: Mode set to BLE_AND_WIFI
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3251): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453125474784.3251
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3251): bind: Binding a new listener
D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3251): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3251): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453125474784.3251","ra":"34:FC:EF:11:AE:67"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3251): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3251): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3251): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3251): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3251): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3251): start: OK
I/io.jxcore.node.ConnectionHelper( 3251): start: Using peer discovery mode: BLE_AND_WIFI
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453125474784.3251
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3251): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3251): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3251): Waiting for incoming connections...
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3251): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3251): createAdvertiseData: From: 1453125474784.3251 b6a44ad1-d319-4b3a-815d-8b805a47fb51 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3251): 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3251): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 52, -4, -17, 17, -82, 103]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3251): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3251): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453125474784.3251","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3251): start: {"pi":"34:FC:EF:11:AE:67","pn":"1453125474784.3251","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3251): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1453125474784.3251","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3251): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3251): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): onIsWifiPeerDiscoveryStartedChanged: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): start: OK
,I/wpa_supplicant(  981): p2p0: P2P: Reject scan trigger since one is already pending
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): setState: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 3251): start: OK
I/jxcore-log( 3251): ok 57 Should be able to call startBroadcasting without error
I/jxcore-log( 3251): 
I/io.jxcore.node.ConnectionHelper( 3251): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3251): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3251): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3251): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3251): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3251): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3251): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3251): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3251): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): stop: Stopping peer discovery...
,D/BluetoothLeScanner( 3251): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3251): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3251): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3251): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3251): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3251): release: No more listeners, de-initializing...
I/wpa_supplicant(  981): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): setState: NOT_STARTED
I/jxcore-log( 3251): ok 58 Should be able to call stopBroadcasting without error
I/jxcore-log( 3251): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): setDiscoveryMode: Mode set to BLE_AND_WIFI
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3251): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453125474807.3251
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3251): bind: Binding a new listener
D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3251): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3251): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453125474807.3251","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3251): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3251): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3251): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3251): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3251): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3251): start: OK
I/io.jxcore.node.ConnectionHelper( 3251): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3251): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453125474807.3251
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3251): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3251): bind: Binding a new listener
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3251): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3251): createAdvertiseData: From: 1453125474807.3251 b6a44ad1-d319-4b3a-815d-8b805a47fb51 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3251): 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3251): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 52, -4, -17, 17, -82, 103]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3251): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3251): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453125474807.3251","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3251): start: {"pi":"34:FC:EF:11:AE:67","pn":"1453125474807.3251","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3251): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1453125474807.3251","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3251): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3251): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): setState: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 3251): start: OK
I/wpa_supplicant(  981): p2p0: P2P: Reject scan trigger since one is already pending
I/jxcore-log( 3251): ok 59 Should be able to call startBroadcasting without error
I/jxcore-log( 3251): 
I/io.jxcore.node.ConnectionHelper( 3251): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3251): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3251): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3251): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3251): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3251): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3251): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3251): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3251): onServerStopped
,D/BluetoothLeScanner( 3251): could not find callback wrapper
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3251): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3251): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3251): setState: NOT_INITIALIZED
I/wpa_supplicant(  981): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3251): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3251): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): setState: NOT_STARTED
I/jxcore-log( 3251): ok 60 Should be able to call stopBroadcasting without error
I/jxcore-log( 3251): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3251): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453125474833.3251
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3251): bind: Binding a new listener
D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3251): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3251): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453125474833.3251","ra":"34:FC:EF:11:AE:67"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3251): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3251): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3251): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3251): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3251): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3251): start: OK
I/io.jxcore.node.ConnectionHelper( 3251): start: Using peer discovery mode: BLE_AND_WIFI
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3251): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453125474833.3251
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3251): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3251): bind: Binding a new listener
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3251): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3251): createAdvertiseData: From: 1453125474833.3251 b6a44ad1-d319-4b3a-815d-8b805a47fb51 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3251): 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3251): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 52, -4, -17, 17, -82, 103]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3251): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3251): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453125474833.3251","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3251): start: {"pi":"34:FC:EF:11:AE:67","pn":"1453125474833.3251","ra":"34:FC:EF:11:AE:67"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3251): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1453125474833.3251","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3251): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3251): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): setState: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 3251): start: OK
I/wpa_supplicant(  981): p2p0: P2P: Reject scan trigger since one is already pending
I/jxcore-log( 3251): ok 61 Should be able to call startBroadcasting without error
I/jxcore-log( 3251): 
,I/io.jxcore.node.ConnectionHelper( 3251): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3251): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3251): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3251): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3251): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3251): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3251): onServerStopped
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3251): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3251): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): stop: Stopping peer discovery...
,D/BluetoothLeScanner( 3251): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3251): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3251): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3251): setState: NOT_INITIALIZED
I/wpa_supplicant(  981): P2P-FIND-STOPPED 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3251): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3251): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): setState: NOT_STARTED
,I/jxcore-log( 3251): ok 62 Should be able to call stopBroadcasting without error
I/jxcore-log( 3251): 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3251): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453125474856.3251
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3251): bind: Binding a new listener
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3251): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3251): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453125474856.3251","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3251): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3251): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3251): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3251): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3251): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3251): start: OK
I/io.jxcore.node.ConnectionHelper( 3251): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3251): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453125474856.3251
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3251): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3251): bind: Binding a new listener
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3251): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3251): createAdvertiseData: From: 1453125474856.3251 b6a44ad1-d319-4b3a-815d-8b805a47fb51 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3251): 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3251): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 52, -4, -17, 17, -82, 103]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3251): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3251): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453125474856.3251","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3251): start: {"pi":"34:FC:EF:11:AE:67","pn":"1453125474856.3251","ra":"34:FC:EF:11:AE:67"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3251): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1453125474856.3251","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3251): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3251): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): startWifiPeerDiscovery: Wi-Fi Direct OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): start: OK
I/wpa_supplicant(  981): p2p0: P2P: Reject scan trigger since one is already pending
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): setState: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 3251): start: OK
I/jxcore-log( 3251): ok 63 Should be able to call startBroadcasting without error
I/jxcore-log( 3251): 
I/io.jxcore.node.ConnectionHelper( 3251): stop
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3251): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3251): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3251): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3251): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3251): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3251): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3251): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3251): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): stop: Stopping peer discovery...
D/BluetoothLeScanner( 3251): could not find callback wrapper
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3251): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3251): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3251): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3251): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3251): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): setState: NOT_STARTED
,I/wpa_supplicant(  981): P2P-FIND-STOPPED 
,I/jxcore-log( 3251): ok 64 Should be able to call stopBroadcasting without error
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): # setup
I/jxcore-log( 3251): 
,I/io.jxcore.node.ConnectionHelper( 3251): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3251): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3251): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3251): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 3251): onDiscoveryManagerStateChanged: RUNNING_WIFI
,I/io.jxcore.node.ConnectionHelper( 3251): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3251): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3251): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3251): Service requests cleared successfully
,I/io.jxcore.node.ConnectionHelper( 3251): onDiscoveryManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3251): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3251): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3251): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3251): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 3251): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 3251): onConnectionManagerStateChanged: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3251): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3251): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3251): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 3251): onDiscoveryManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3251): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3251): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3251): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3251): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 3251): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 3251): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3251): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3251): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3251): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 3251): onDiscoveryManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3251): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3251): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3251): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3251): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 3251): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 3251): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3251): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3251): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3251): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 3251): onDiscoveryManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3251): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 3251): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3251): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3251): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3251): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 3251): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3251): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3251): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3251): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 3251): onDiscoveryManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3251): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3251): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 3251): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3251): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2p,DeviceDiscoverer( 3251): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 3251): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3251): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3251): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3251): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 3251): onDiscoveryManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3251): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3251): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 3251): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3251): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3251): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 3251): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3251): Local services cleared successfully
I/io.jxcore.node.ConnectionHelper( 3251): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3251): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3251): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 3251): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3251): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 3251): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3251): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3251): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 3251): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3251): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3251): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3251): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 3251): onDiscoveryManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3251): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 3251): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3251): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3251): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3251): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 3251): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3251): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3251): P2P device discovery stopped successfully
I/io.jxcore.node.ConnectionHelper( 3251): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3251): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 3251): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3251): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 3251): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3251): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3251): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 3251): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3251): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3251): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3251): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3251): Service requests cleared successfully
,I/jxcore-log( 3251): # ThaliEmitter calls startBroadcasting twice with error,
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): # teardown
I/jxcore-log( 3251): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): setDiscoveryMode: Mode set to BLE_AND_WIFI
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3251): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453125477810.3251
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3251): bind: Binding a new listener
D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3251): initialize: My bluetooth address is 34:FC:EF:11:AE:67
D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3251): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453125477810.3251","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3251): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3251): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3251): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3251): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3251): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3251): start: OK
I/io.jxcore.node.ConnectionHelper( 3251): start: Using peer discovery mode: BLE_AND_WIFI
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453125477810.3251
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3251): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3251): bind: Binding a new listener
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3251): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3251): createAdvertiseData: From: 1453125477810.3251 b6a44ad1-d319-4b3a-815d-8b805a47fb51 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3251): 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3251): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 52, -4, -17, 17, -82, 103]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3251): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3251): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453125477810.3251","ra":"34:FC:EF:11:AE:67"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3251): start: {"pi":"34:FC:EF:11:AE:67","pn":"1453125477810.3251","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3251): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1453125477810.3251","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3251): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3251): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): setState: RUNNING_WIFI
,I/wpa_supplicant(  981): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/io.jxcore.node.ConnectionHelper( 3251): start: OK
,I/jxcore-log( 3251): ok 65 Should be able to call startBroadcasting without error
I/jxcore-log( 3251): 
I/jxcore-log( 3251): ok 66 Cannot call startBroadcasting twice
I/jxcore-log( 3251): 
I/io.jxcore.node.ConnectionHelper( 3251): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3251): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3251): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3251): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3251): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3251): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3251): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): stop: Stopping peer discovery...
,D/BluetoothLeScanner( 3251): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3251): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3251): stop: Stopping P2P device discovery...
,I/wpa_supplicant(  981): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3251): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3251): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3251): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): setState: NOT_STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3251): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3251): onServerStopped
,I/jxcore-log( 3251): ok 67 Should be able to call stopBroadcasting without error
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): # setup
I/jxcore-log( 3251): 
I/io.jxcore.node.ConnectionHelper( 3251): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3251): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3251): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3251): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 3251): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 3251): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3251): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3251): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3251): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 3251): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 3251): # ThaliEmitter throws on connection to bad peer
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): # teardown
I/jxcore-log( 3251): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): setDiscoveryMode: Mode set to BLE_AND_WIFI
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3251): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453125479783.3251
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3251): bind: Binding a new listener
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3251): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3251): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453125479783.3251","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3251): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3251): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3251): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3251): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3251): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3251): start: OK
I/io.jxcore.node.ConnectionHelper( 3251): start: Using peer discovery mode: BLE_AND_WIFI
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453125479783.3251
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3251): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3251): bind: Binding a new listener
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3251): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3251): createAdvertiseData: From: 1453125479783.3251 b6a44ad1-d319-4b3a-815d-8b805a47fb51 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3251): 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3251): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 52, -4, -17, 17, -82, 103]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3251): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3251): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453125479783.3251","ra":"34:FC:EF:11:AE:67"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3251): start: {"pi":"34:FC:EF:11:AE:67","pn":"1453125479783.3251","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3251): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1453125479783.3251","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3251): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3251): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): start: OK
,I/wpa_supplicant(  981): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): setState: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 3251): start: OK
,I/jxcore-log( 3251): ok 68 Should be able to call startBroadcasting without error
I/jxcore-log( 3251): 
I/io.jxcore.node.ConnectionHelper( 3251): connect: Trying to connect to peer with ID foobar
W/io.jxcore.node.ConnectionHelper( 3251): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
E/io.jxcore.node.ConnectionHelper( 3251): connect: Invalid Bluetooth address: foobar
I/jxcore-log( 3251): ok 69 Should not connect to a bad peer
I/jxcore-log( 3251): 
I/io.jxcore.node.ConnectionHelper( 3251): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3251): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3251): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3251): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3251): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3251): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3251): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): stop: Stopping peer discovery...
,D/BluetoothLeScanner( 3251): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3251): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3251): stop: Stopping P2P device discovery...
,I/wpa_supplicant(  981): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3251): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3251): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3251): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): setState: NOT_STARTED
I/jxcore-log( 3251): ok 70 Should be able to call stopBroadcasting without error
I/jxcore-log( 3251): 
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3251): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3251): onServerStopped
,I/jxcore-log( 3251): # setup
I/jxcore-log( 3251): 
I/io.jxcore.node.ConnectionHelper( 3251): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3251): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3251): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3251): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 3251): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 3251): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3251): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3251): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3251): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 3251): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 3251): # ThaliEmitter throws on disconnect to bad peer
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): # teardown
I/jxcore-log( 3251): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): setDiscoveryMode: Mode set to BLE_AND_WIFI
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3251): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453125481507.3251
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3251): bind: Binding a new listener
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3251): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3251): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453125481507.3251","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3251): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3251): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3251): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3251): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3251): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3251): start: OK
I/io.jxcore.node.ConnectionHelper( 3251): start: Using peer discovery mode: BLE_AND_WIFI
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453125481507.3251
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3251): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3251): bind: Binding a new listener
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3251): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3251): createAdvertiseData: From: 1453125481507.3251 b6a44ad1-d319-4b3a-815d-8b805a47fb51 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3251): 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3251): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 52, -4, -17, 17, -82, 103]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3251): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3251): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453125481507.3251","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3251): start: {"pi":"34:FC:EF:11:AE:67","pn":"1453125481507.3251","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3251): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1453125481507.3251","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3251): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3251): start: Starting P2P device discovery...
,I/wpa_supplicant(  981): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): setState: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 3251): start: OK
I/jxcore-log( 3251): ok 71 Should be able to call startBroadcasting without error
I/jxcore-log( 3251): 
D/io.jxcore.node.ConnectionHelper( 3251): disconnectOutgoingConnection: Trying to close connection to peer with ID foobar
E/io.jxcore.node.ConnectionHelper( 3251): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID foobar
D/io.jxcore.node.ConnectionHelper( 3251): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3251): disconnectOutgoingConnection: Failed to disconnect (peer ID: foobar), either no such connection or failed to close the connection
I/jxcore-log( 3251): ok 72 Disconnect should fail to a non-existant peer 
I/jxcore-log( 3251): 
I/io.jxcore.node.ConnectionHelper( 3251): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3251): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3251): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3251): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3251): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3251): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3251): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): stop: Stopping peer discovery...
,D/BluetoothLeScanner( 3251): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3251): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3251): stop: Stopping P2P device discovery...
,I/wpa_supplicant(  981): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3251): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3251): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3251): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3251): setState: NOT_STARTED
,I/jxcore-log( 3251): ok 73 Should be able to call stopBroadcasting without error
I/jxcore-log( 3251): 
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3251): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3251): onServerStopped
,I/jxcore-log( 3251): # setup
I/jxcore-log( 3251): 
I/io.jxcore.node.ConnectionHelper( 3251): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3251): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3251): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3251): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 3251): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 3251): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3251): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3251): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3251): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 3251): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 3251): # #startListeningForAdvertisements should emit wifiPeerAvailabilityChanged after test peer becomes available
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): # teardown
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): ok 74 should be equal
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): # setup
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): # #startUpdateAdvertisingAndListenForIncomingConnections should use different USN after every invocation
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): # teardown
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): ok 75 should not be equal
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): # setup
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): # verify that Thali-specific messages are filtered correctly
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): # teardown
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): ok 76 irrelevant messages should be ignored
I/jxcore-log( 3251): 
I/jxcore-log( 3251): ok 77 relevant messages should not be ignored
I/jxcore-log( 3251): 
I/jxcore-log( 3251): ok 78 messages from this device should be ignored
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): Tests Complete
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): Total: 0	Passed: 0	Failed: 0
I/jxcore-log( 3251): 
I/jxcore-log( 3251): Toggling radios to false
I/jxcore-log( 3251): 
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  734): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@3f81e066 mBinding = false
,D/BluetoothManagerService(  734): Message: 2
,D/BluetoothManagerService(  734): Sending off request.
,D/BluetoothAdapterState( 2103): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 2103): Setting state to 13
I/BluetoothAdapterState( 2103): Bluetooth adapter state changed: 12-> 13
,D/BluetoothAdapterProperties( 2103): onBluetoothDisable()
I/BluetoothAdapterState( 2103): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,D/BluetoothAdapterProperties( 2103): Scan Mode:20
,D/BluetoothAdapterState( 2103): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,V/BluetoothMapMasInstance( 2103): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 2103): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 2103): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
V/BluetoothMapMasInstance( 2103): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:489)
V/BluetoothMapMasInstance( 2103): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:399)
V/BluetoothMapMasInstance( 2103): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 2103): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 2103): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,E/BtOppRfcommListener( 2103): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,D/btif_config_util( 2103): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 2103): bta_dm_disable BTA_DISABLE_DELAY set to 100 ms
,W/bt-l2cap( 2103): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2103): L2CAP - PSM: 0x0017 not found for deregistration
,D/BluetoothManagerService(  734): Message: 60
D/BluetoothManagerService(  734): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
,D/BluetoothManagerService(  734): Bluetooth State Change Intent: 12 -> 13
,D/BluetoothMapService( 2103): onReceive
D/BluetoothMapService( 2103): STATE_TURNING_OFF
V/BluetoothMapService( 2103): Handler(): got msg=4
D/BluetoothMapService( 2103): MAP Service closeService in
D/BluetoothMapMasInstance( 2103): MAP Service shutdown
V/BluetoothMapService( 2103): MAP Service closeService out
,I/BtOppRfcommListener( 2103): stopping Accept Thread
I/BtOppRfcommListener( 2103): BluetoothSocket listen thread finished
,D/WifiService(  734): setWifiEnabled: false pid=3251, uid=10270
E/WifiService(  734): Invoking mWifiStateMachine.setWifiEnabled
,W/ContextImpl( 2714): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,E/WifiStateMachine(  734): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  734): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,I/jxcore-log( 3251): Radios toggled
I/jxcore-log( 3251): 
,I/jxcore-log( 3251): ****TEST TOOK:  ms ****
I/jxcore-log( 3251): 
I/jxcore-log( 3251): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3251): 
I/chromium( 3251): [INFO:CONSOLE(63)] "logCallback ------ Final results ---- ", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3251): [INFO:CONSOLE(63)] "logCallback Total: 0, Passed: 0, Failed: 0", source: file:///android_asset/www/js/thali_main.js (63)
E/native  (  734): do suspend true
D/DockEventReceiver( 2714): finishStartingService: stopping service
,D/CommandListener(  181): Clearing all IP addresses on wlan0
,D/AuthorizationBluetoothService( 1583): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/bt_userial( 2103): RX termination
,W/bt_userial( 2103): select_read return size <=0:-1, exiting userial_read_thread
D/bt_userial( 2103): Leaving userial_read_thread()
D/bt_userial( 2103): userial_close_reader Joined userial reader thread: 0
D/bt_hwcfg( 2103): hw_epilog_process
W/bt-btif ( 2103): ag scb idx 1 not allocated
E/bt-btif ( 2103): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 2103): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2103): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2103): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2103): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2103): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2103): L2CAP - PSM: 0x0017 not found for deregistration
I/bt_userial_vendor( 2103): device fd = 53 close
D/BluetoothPbap( 2714): Proxy object disconnected
,I/GKI_LINUX( 2103): gki_task task_id=0 [BTU] terminating
,I/GKI_LINUX( 2103): GKI_exit_task 0 done
I/GKI_LINUX( 2103): GKI_shutdown(): task [BTU] terminated
D/BluetoothAdapterState( 2103): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
I/jxcore-log( 3251): Toggling radios to false
I/jxcore-log( 3251): 
D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  734): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@3f81e066 mBinding = false
D/BluetoothManagerService(  734): Message: 2
D/BluetoothManagerService(  734): Sending off request.
D/PbapServerProfile( 2714): Bluetooth service disconnected
D/WifiService(  734): setWifiEnabled: false pid=3251, uid=10270
E/WifiService(  734): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3251): Radios toggled
I/jxcore-log( 3251): 
D/ConnectivityService(  734): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  734): NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,D/HeadsetService( 2103): Received stop request...Stopping profile...
,D/BluetoothAdapterService( 2103): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ff495f3
D/HeadsetStateMachine( 2103): Exit Disconnected: -1
,D/A2dpService( 2103): Received stop request...Stopping profile...
D/A2dpStateMachine( 2103): Exit Disconnected: -1
D/BluetoothAdapterService( 2103): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ff495f3
D/HidService( 2103): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2103): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ff495f3
D/BluetoothHeadset( 1250): Proxy object disconnected
E/WifiConfigStore(  734): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/BluetoothHeadset(  734): Proxy object disconnected
,D/BluetoothA2dp(  734): Proxy object disconnected
,D/BluetoothHeadset( 1210): Proxy object disconnected
D/BluetoothHeadset( 1210): Proxy object disconnected
D/BluetoothAdapterState( 2103): Stopping profile services that were post enabled
D/BluetoothAdapterState( 2103): CURRENT_STATE=PENDING, MESSAGE = USER_TURN_ON, isTurningOn=false, isTurningOff=true
I/BluetoothAdapterState( 2103): CURRENT_STATE=PENDING: Alreadying turning off bluetooth... Ignoring USER_TURN_OFF...
D/HealthService( 2103): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2103): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ff495f3
,E/WifiStateMachine(  734): scanCount==0 - aborting
,D/PanService( 2103): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2103): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ff495f3
,D/BtGatt.DebugUtils( 2103): handleDebugAction() action=null
D/BtGatt.GattService( 2103): Received stop request...Stopping profile...
D/BtGatt.GattService( 2103): stop()
D/BtGatt.AdvertiseManager( 2103): advertise clients cleared
D/BluetoothAdapterService( 2103): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ff495f3
D/HeadsetStateMachine( 2103): Unbinding service...
W/BluetoothHeadsetServiceJni( 2103): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 2103): Cleaning up Bluetooth Handsfree callback object
I/GKI_LINUX( 2103): gki_task task_id=2 [A2DP-MEDIA] terminating
,I/GKI_LINUX( 2103): GKI_exit_task 2 done
I/GKI_LINUX( 2103): GKI_shutdown(): task [A2DP-MEDIA] terminated
W/BluetoothHidServiceJni( 2103): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 2103): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 2103): Cleaning up Bluetooth GID callback object
,D/BluetoothMapService( 2103): Received stop request...Stopping profile...
D/BluetoothMapService( 2103): stop()
D/WifiScanningService(  734): SCAN_AVAILABLE : 1
,D/WifiScanningService(  734): StartedState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  734): DefaultState
D/WifiNetworkAgent(  734): NetworkAgent: NetworkAgent channel lost
D/RttService(  734): SCAN_AVAILABLE : 1
,E/native  (  734): do suspend true
D/RttService(  734): EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,D/BluetoothHeadset( 2714): Proxy object disconnected
D/HeadsetProfile( 2714): Bluetooth service disconnected
,D/BluetoothMapEmailAppObserver( 2103): deinitObservers()
D/BluetoothMapEmailAppObserver( 2103): removeReceiver()
,D/BluetoothAdapterService( 2103): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ff495f3
,W/BluetoothHealthServiceJni( 2103): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 2103): Cleaning up Bluetooth Health object
,W/BluetoothPanServiceJni( 2103): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 2103): Cleaning up Bluetooth PAN callback object
D/BluetoothA2dp( 2714): Proxy object disconnected
D/A2dpProfile( 2714): Bluetooth service disconnected
D/BluetoothInputDevice( 2714): Proxy object disconnected
D/HidProfile( 2714): Bluetooth service disconnected
D/BluetoothPan( 2714): BluetoothPAN Proxy object disconnected
D/PanProfile( 2714): Bluetooth service disconnected
,D/ConnectivityService(  734): notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,V/BluetoothMapService( 2103): Handler(): got msg=4
D/BluetoothMapService( 2103): MAP Service closeService in
V/BluetoothMapService( 2103): MAP Service closeService out
,D/BluetoothAdapterState( 2103): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/CommandListener(  181): Clearing all IP addresses on wlan0
D/BluetoothAdapterProperties( 2103): Setting state to 10
I/BluetoothAdapterState( 2103): Bluetooth adapter state changed: 13-> 10
D/BluetoothMapService( 2103): cleanup()
D/BluetoothMapService( 2103): MAP Service closeService in
V/BluetoothMapService( 2103): MAP Service closeService out
D/BluetoothManagerService(  734): Message: 60
D/BluetoothManagerService(  734): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService(  734): Broadcasting onBluetoothStateChange(false) to 11 receivers.
I/BluetoothAdapterState( 2103): Entering OffState
,D/BluetoothA2dp( 2714): onBluetoothStateChange: up=false
,D/Nat464Xlat(  734): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/CSLegacyTypeTracker(  734): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): Disconnected - quitting
,D/ConnectivityManager.CallbackHandler(  898): CM callback handler got msg 524292
,D/ConnectivityService(  734): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/BluetoothMap( 2714): onBluetoothStateChange: up=false
,D/ConnectivityService(  734): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  734): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  734): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/TelephonyNetworkFactory( 1250): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/BluetoothHeadset( 2714): onBluetoothStateChange: up=false
,D/ConnectivityManager.CallbackHandler( 1639): CM callback handler got msg 524292
,D/BluetoothHeadset( 1210): onBluetoothStateChange: up=false
,D/BluetoothInputDevice( 2714): onBluetoothStateChange: up=false
,D/BluetoothPbap( 2714): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1250): onBluetoothStateChange: up=false
,D/BluetoothA2dp(  734): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1210): onBluetoothStateChange: up=false
,D/BluetoothHeadset(  734): onBluetoothStateChange: up=false
D/BluetoothManagerService(  734): Calling onBluetoothServiceDown callbacks
,D/BluetoothManagerService(  734): Broadcasting onBluetoothServiceDown() to 9 receivers.
,D/BluetoothManagerService(  734): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@3f81e066 mBinding = false
,D/BluetoothManagerService(  734): Sending unbind request.
,I/ActivityManager(  734): Start proc com.google.android.keep for broadcast com.google.android.keep/.notification.AlertReceiver: pid=3622 uid=10071 gids={50071, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/wpa_supplicant(  981): p2p0: CTRL-EVENT-TERMINATING 
,D/BluetoothManagerService(  734): Bluetooth State Change Intent: 13 -> 10
,D/AndroidRuntime( 3610): 
D/AndroidRuntime( 3610): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/BluetoothAdapter(  898): 391267092: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter(  898): 391267092: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter(  898): 391267092: getState() :  mService = null. Returning STATE_OFF
,D/AndroidRuntime( 3610): CheckJNI is OFF
,D/BluetoothAdapter( 1583): 1049781526: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1583): 1049781526: getState() :  mService = null. Returning STATE_OFF
,I/wpa_supplicant(  981): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,I/GKI_LINUX( 2103): gki_task task_id=1 [BTIF] terminating
,I/GKI_LINUX( 2103): GKI_exit_task 1 done
I/GKI_LINUX( 2103): GKI_shutdown(): task [BTIF] terminated
I/BluetoothServiceJni( 2103): cleanupNative: return from cleanup
,I/art     ( 2103): System.exit called, status: 0
I/AndroidRuntime( 2103): VM exiting with result code 0, cleanup skipped.
,D/AndroidRuntime( 3610): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  734): Process com.android.bluetooth (pid 2103) has died
,I/ActivityManager(  734): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  734): Killing 3251:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
,W/PackageSettings(  734): Skipping PackageSetting{2fa9a8d6 com.example.hello/10278} due to missing metadata
,D/WifiService(  734): Client connection lost with reason: 4
,I/WindowState(  734): WIN DEATH: Window{15a831b4 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/Tethering(  734): InitialState.processMessage what=4
I/wpa_supplicant(  981): wlan0: CTRL-EVENT-TERMINATING 
,I/ActivityManager(  734):   Force finishing activity ActivityRecord{3c92d6c0 u0 com.test.thalitest/.MainActivity t216}
,W/ActivityManager(  734): Spurious death for ProcessRecord{38dfbf43 3251:com.test.thalitest/u0a270}, curProc for 3251: null
,D/Tethering(  734): sendTetherStateChangedBroadcast 0, 0, 0
,I/Adreno-EGL(  948): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
I/OpenGLRenderer(  948): Initialized EGL, version 1.4
,D/OpenGLRenderer(  948): Enabling debug mode 0
,W/Settings( 1948): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActivityManager(  734): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
,W/Settings( 1583): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/InputMethodManagerService(  734): Got RemoteException sending setActive(false) notification to pid 3251 uid 10270
,I/Keyboard.Facilitator( 1100): onFinishInput()
,I/art     ( 1277): Explicit concurrent mark sweep GC freed 3965(294KB) AllocSpace objects, 1(126KB) LOS objects, 38% free, 25MB/41MB, paused 466us total 18.584ms
I/Keyboard.Facilitator( 1100): resetDictionaries() : en_US
,W/GeofencerStateMachine( 1583): Ignoring removeGeofence because network location is disabled.
,I/Keyboard.Facilitator.DecoderInitializer( 1100): run()
,I/InputReader(  734): Reconfiguring input devices.  changes=0x00000010
,I/Decoder ( 1100): createOrResetDecoder
,I/art     ( 1389): Explicit concurrent mark sweep GC freed 1976(117KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 19MB/25MB, paused 336us total 50.645ms
,I/art     ( 1639): Explicit concurrent mark sweep GC freed 11874(567KB) AllocSpace objects, 1(16KB) LOS objects, 25% free, 22MB/30MB, paused 562us total 62.572ms
,I/art     (  734): Explicit concurrent mark sweep GC freed 42365(2MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 1.108ms total 79.978ms
I/art     (  734): WaitForGcToComplete blocked for 58.194ms for cause Explicit
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1100): run()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1100): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1100): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1100): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1100): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1100): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1100): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1100): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1100): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1100): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1100): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1100): run()
I/StatsUtilsManager( 1100): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1100): shouldRecordStats() = Too Soon
,W/IInputConnectionWrapper( 1277): showStatusIcon on inactive InputConnection
,I/Keyboard.Facilitator( 1100): onFinishInput()
,D/BackupManagerService(  734): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService(  734): Receieved: android.intent.action.PACKAGE_REMOVED
,I/art     (  734): Explicit concurrent mark sweep GC freed 4968(274KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 27MB/41MB, paused 961us total 91.516ms
,D/TaskPersister(  734): removeObsoleteFile: deleting file=216_task.xml
,W/ContextImpl( 2714): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,I/ActivityManager(  734): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=3697 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,D/DockEventReceiver( 2714): finishStartingService: stopping service
,D/AndroidRuntime( 3610): Shutting down VM
,I/ActivityManager(  734): Killing 2738:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/libprocessgroup(  734): failed to open /acct/uid_10003/pid_2738/cgroup.procs: No such file or directory
,I/Launcher( 1277): Deferring update until onResume
,W/ResourcesManager( 3697): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,W/ResourcesManager( 1277): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/AdapterServiceConfig( 3697): Adding HeadsetService
,D/AdapterServiceConfig( 3697): Adding A2dpService
D/AdapterServiceConfig( 3697): Adding HidService
D/AdapterServiceConfig( 3697): Adding HealthService
D/AdapterServiceConfig( 3697): Adding PanService
D/AdapterServiceConfig( 3697): Adding GattService
D/AdapterServiceConfig( 3697): Adding BluetoothMapService
,W/ResourcesManager( 1277): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/BluetoothAdapter( 2714): 958879860: getState() :  mService = null. Returning STATE_OFF
,I/ActivityManager(  734): Killing 2574:com.google.android.gm/u0a70 (adj 15): empty #17
,I/Launcher( 1277): Deferring update until onResume
,D/AuthorizationBluetoothService( 1583): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,W/libprocessgroup(  734): failed to open /acct/uid_10070/pid_2574/cgroup.procs: No such file or directory
,D/BluetoothAdapter( 2714): 958879860: getState() :  mService = null. Returning STATE_OFF
,D/VoicemailCleanupService( 1366): Cleaning up data for package: com.test.thalitest
,I/UpdateIcingCorporaServi( 1389): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,W/Launcher( 1277): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@2ff495f3 new=com.google.android.velvet.VelvetApplication@2ff495f3
,I/ActivityManager(  734): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3720 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/UpdateIcingCorporaServi( 1389): UpdateCorporaTask done [took 76 ms] updated apps [took 76 ms] 
,W/ContextImpl( 3720): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
,D/PackageBroadcastService( 1639): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1639): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 1639): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1639): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1639): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1639): Module APK com.google.android.play.games already loaded
,I/LocationSettingsChecker( 1639): Removing dialog suppression flag for package com.test.thalitest
,E/NetworkScheduler.SchedulerReceiver( 1583): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1583): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/ActivityManager(  734): Killing 2018:com.google.android.calendar/u0a31 (adj 15): empty #17
,D/gH_CompatibleDatabase( 1639): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,D/gH_CompatibleDatabase( 1639): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 1639): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1639): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,W/libprocessgroup(  734): failed to open /acct/uid_10031/pid_2018/cgroup.procs: No such file or directory
,D/gH_CompatibleDatabase( 1639): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1639): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1639): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/gH_CompatibleDatabase( 1639): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1639): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,W/BaseAppContext( 1639): Using Auth Proxy for data requests.
,D/gH_CompatibleDatabase( 1639): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,D/gH_CompatibleDatabase( 1639): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
,D/gH_CompatibleDatabase( 1639): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1639): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/ActivityManager(  734): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3753 uid=10039 gids={50039, 9997} abi=armeabi-v7a
,W/BaseAppContext( 1639): Using Auth Proxy for data requests.
I/GMPM-SVC( 1639): App measurement is starting up, version: 8489
I/GMPM-SVC( 1639): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,E/SQLiteDatabase( 1639): Failed to open database '/data/data/com.google.android.gms/databases/app_state.db'.
E/SQLiteDatabase( 1639): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1639): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1639): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1639): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1639): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1639): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1639): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1639): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1639): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1639): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1639): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/SQLiteDatabase( 1639): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 1639): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1639): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 1639): 	at com.google.android.gms.common.k.a.delete(SourceFile:272)
E/SQLiteDatabase( 1639): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:309)
E/SQLiteDatabase( 1639): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
E/SQLiteDatabase( 1639): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
E/SQLiteDatabase( 1639): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
E/SQLiteDatabase( 1639): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/SQLiteDatabase( 1639): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 1639): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 1639): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/SQLiteDatabase( 1639): 	at java.lang.Thread.run(Thread.java:818)
,E/ClearPendingStateOp( 1639): Runtime exception while performing operation
E/ClearPendingStateOp( 1639): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/ClearPendingStateOp( 1639): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/ClearPendingStateOp( 1639): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/ClearPendingStateOp( 1639): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/ClearPendingStateOp( 1639): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/ClearPendingStateOp( 1639): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/ClearPendingStateOp( 1639): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/ClearPendingStateOp( 1639): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/ClearPendingStateOp( 1639): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/ClearPendingStateOp( 1639): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/ClearPendingStateOp( 1639): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/ClearPendingStateOp( 1639): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/ClearPendingStateOp( 1639): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/ClearPendingStateOp( 1639): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/ClearPendingStateOp( 1639): 	at com.google.android.gms.common.k.a.delete(SourceFile:272)
E/ClearPendingStateOp( 1639): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:309)
E/ClearPendingStateOp( 1639): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
E/ClearPendingStateOp( 1639): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
E/ClearPendingStateOp( 1639): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
E/ClearPendingStateOp( 1639): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/ClearPendingStateOp( 1639): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearPendingStateOp( 1639): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearPendingStateOp( 1639): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/ClearPendingStateOp( 1639): 	at java.lang.Thread.run(Thread.java:818)
,F/ClearPendingStateOp( 1639): Killing (on development devices) due to RuntimeException
F/ClearPendingStateOp( 1639): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
F/ClearPendingStateOp( 1639): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
F/ClearPendingStateOp( 1639): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
F/ClearPendingStateOp( 1639): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
F/ClearPendingStateOp( 1639): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
F/ClearPendingStateOp( 1639): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
F/ClearPendingStateOp( 1639): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
F/ClearPendingStateOp( 1639): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
F/ClearPendingStateOp( 1639): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
F/ClearPendingStateOp( 1639): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
F/ClearPendingStateOp( 1639): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
F/ClearPendingStateOp( 1639): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
F/ClearPendingStateOp( 1639): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
F/ClearPendingStateOp( 1639): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
F/ClearPendingStateOp( 1639): 	at com.google.android.gms.common.k.a.delete(SourceFile:272)
F/ClearPendingStateOp( 1639): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:309)
F/ClearPendingStateOp( 1639): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
F/ClearPendingStateOp( 1639): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
F/ClearPendingStateOp( 1639): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
F/ClearPendingStateOp( 1639): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
F/ClearPendingStateOp( 1639): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
F/ClearPendingStateOp( 1639): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
F/ClearPendingStateOp( 1639): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
F/ClearPendingStateOp( 1639): 	at java.lang.Thread.run(Thread.java:818)
,I/Icing   ( 1639): doRemovePackageData com.test.thalitest
E/DropBoxManagerService(  734): Can't write: system_app_wtf
E/DropBoxManagerService(  734): java.io.FileNotFoundException: /data/system/dropbox/drop95.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  734): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  734): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  734): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  734): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  734): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  734): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12006)
E/DropBoxManagerService(  734): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  734): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  734): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  734): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  734): 	... 5 more
E/SQLiteLog( 1639): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,--------- beginning of crash
E/AndroidRuntime( 1639): FATAL EXCEPTION: IntentService[PeopleBackgroundTasks]
E/AndroidRuntime( 1639): Process: com.google.android.gms, PID: 1639
E/AndroidRuntime( 1639): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1639): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 1639): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AndroidRuntime( 1639): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 1639): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 1639): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AndroidRuntime( 1639): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/AndroidRuntime( 1639): 	at com.google.android.gms.people.c.e.a(SourceFile:110)
E/AndroidRuntime( 1639): 	at com.google.android.gms.people.sync.a.b.d(SourceFile:3165)
E/AndroidRuntime( 1639): 	at com.google.android.gms.people.service.bg.b.a(SourceFile:245)
E/AndroidRuntime( 1639): 	at com.google.android.gms.people.service.bg.PeopleBackgroundTasks.onHandleIntent(SourceFile:77)
E/AndroidRuntime( 1639): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 1639): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1639): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 1639): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteDatabase( 1639): Failed to open database '/data/data/com.google.android.gms/databases/google_app_measurement.db'.
E/SQLiteDatabase( 1639): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1639): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1639): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1639): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1639): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1639): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1639): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1639): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1639): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1639): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1639): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/SQLiteDatabase( 1639): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 1639): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1639): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 1639): 	at com.google.android.gms.measurement.internal.h.getWritableDatabase(SourceFile:2307)
E/SQLiteDatabase( 1639): 	at com.google.android.gms.measurement.internal.e.e(SourceFile:418)
E/SQLiteDatabase( 1639): 	at com.google.android.gms.measurement.internal.e.a(SourceFile:357)
E/SQLiteDatabase( 1639): 	at com.google.android.gms.measurement.internal.aq.s(SourceFile:1591)
E/SQLiteDatabase( 1639): 	at com.google.android.gms.measurement.internal.aq.p(SourceFile:1605)
E/SQLiteDatabase( 1639): 	at com.google.android.gms.measurement.internal.aq.c(SourceFile:306)
E/SQLiteDatabase( 1639): 	at com.google.android.gms.measurement.internal.ar.run(SourceFile:195)
E/SQLiteDatabase( 1639): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 1639): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 1639): 	at com.google.android.gms.measurement.internal.ap.run(SourceFile:294)
E/DropBoxManagerService(  734): Can't write: system_app_crash
E/DropBoxManagerService(  734): java.io.FileNotFoundException: /data/system/dropbox/drop96.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  734): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  734): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  734): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  734): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  734): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  734): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12006)
E/DropBoxManagerService(  734): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  734): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  734): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  734): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  734): 	... 5 more
,E/GMPM-SVC( 1639): Opening the database failed, dropping and recreating it
,I/Process ( 1639): Sending signal. PID: 1639 SIG: 9

```
