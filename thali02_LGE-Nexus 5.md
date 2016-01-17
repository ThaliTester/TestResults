#### Test 5615109389cecbd_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
I/GAv4    ( 3204): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3204):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3204):   adb logcat -s GAv4
W/GAv4    ( 3204): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3204): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3204): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 3204): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
E/SQLiteLog( 3204): (283) recovered 24 frames from WAL file /data/data/com.google.android.apps.docs/databases/DocList.db-wal
D/Finsky  ( 2632): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
W/ResourcesManager( 3204): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3204): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  762): Killing 2083:com.google.android.deskclock/u0a38 (adj 15): empty #17
V/JNIHelp ( 3204): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/libprocessgroup(  762): failed to open /acct/uid_10038/pid_2083/cgroup.procs: No such file or directory
W/System  ( 3204): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3204): Installed default security provider GmsCore_OpenSSL
V/GLSActivity( 1603): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/CAR.SERVICE( 3088): mConnectedToCar = false, abort
E/ActivityThread( 3088): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@3fbea9de that was originally bound here
E/ActivityThread( 3088): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@3fbea9de that was originally bound here
E/ActivityThread( 3088): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3088): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3088): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3088): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3088): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3088): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3088): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3088): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3088): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3088): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 3088): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 3088): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 3088): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 3088): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2731)
E/ActivityThread( 3088): 	at android.app.ActivityThread.access$1800(ActivityThread.java:144)
E/ActivityThread( 3088): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1361)
E/ActivityThread( 3088): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3088): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3088): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3088): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3088): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3088): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3088): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
E/ActivityThread( 3088): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@236fae51 that was originally bound here
E/ActivityThread( 3088): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@236fae51 that was originally bound here
E/ActivityThread( 3088): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3088): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3088): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3088): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3088): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3088): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3088): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3088): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 3088): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 3088): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 3088): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 3088): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 3088): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2758)
E/ActivityThread( 3088): 	at android.app.ActivityThread.access$1900(ActivityThread.java:144)
E/ActivityThread( 3088): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
E/ActivityThread( 3088): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3088): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3088): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3088): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3088): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3088): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3088): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
W/ActivityManager(  762): Unbind failed: could not find connection for android.os.BinderProxy@19ca16ba
I/Icing   ( 1637): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/Icing   ( 1637): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1637): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/Icing   ( 1637): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
I/ActivityManager(  762): Killing 2590:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
W/libprocessgroup(  762): failed to open /acct/uid_10069/pid_2590/cgroup.procs: No such file or directory
,D/AndroidRuntime( 3268): 
D/AndroidRuntime( 3268): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3268): CheckJNI is OFF
D/AndroidRuntime( 3268): Calling main entry com.android.commands.am.Am
I/ActivityManager(  762): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  762): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3289 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3268): Shutting down VM
V/ActivityManager(  762): Display changed displayId=0
I/WebViewFactory( 3289): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3289): Time to load native libraries: 1 ms (timestamps 1256-1257)
I/LibraryLoader( 3289): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3289): Binding Chromium to main looper Looper (main, tid 1) {16368891}
,I/LibraryLoader( 3289): Expected native library version number "",actual native library version number ""
I/chromium( 3289): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3289): Initializing chromium process, singleProcess=true
,W/art     ( 3289): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3289): ApplicationContext is null in ApplicationStatus
,W/chromium( 3289): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3289): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3289): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3289): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  762): Message: 20
D/BluetoothManagerService(  762): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f70223f:true
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
,W/IInputConnectionWrapper( 3289): showStatusIcon on inactive InputConnection
,I/ActivityManager(  762): Displayed com.test.thalitest/.MainActivity: +439ms (total +59s574ms)
,W/BindingManager( 3289): Cannot call determinedVisibility() - never saw a connection for the pid: 3289
,D/JsMessageQueue( 3289): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3289): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257343360
,D/JX-Cordova( 3289): jxcore cordova android initializing
,W/jxcore-log( 3289): Initializing JXcore engine
W/jxcore-log( 3289): JXcore engine is ready
,W/jxcore-log( 3289): Starting JXcore engine
,W/.test.thalitest( 3289): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[8399]" dev="sockfs" ino=8399 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3289): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 3289): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[9439]" dev="sockfs" ino=9439 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3289): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[19672]" dev="sockfs" ino=19672 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3289): Platform android
W/jxcore-log( 3289): 
W/jxcore-log( 3289): Process ARCH arm
W/jxcore-log( 3289): 
,I/jxcore-log( 3289): JXcore Cordova bridge is ready!
I/jxcore-log( 3289): 
,W/jxcore-log( 3289): JXcore engine is started
,I/Choreographer( 3289): Skipped 125 frames!  The application may be doing too much work on its main thread.
I/chromium( 3289): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3289): Toggling radios to true
I/jxcore-log( 3289): 
,D/BluetoothAdapter( 3289): enable(): BT is already enabled..!
,D/WifiService(  762): New client listening to asynchronous messages
,D/WifiService(  762): setWifiEnabled: true pid=3289, uid=10270
E/WifiService(  762): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3289): Radios toggled
I/jxcore-log( 3289): 
,I/jxcore-log( 3289): My device name is: LGE-Nexus 5
I/jxcore-log( 3289): 
,I/wpa_supplicant(  983): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  762): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  762): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/native  (  762): do suspend true
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1603): Read error: ssl=0xb3ef7e00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1603): SSL shutdown failed: ssl=0xb3ef7e00: I/O error during system call, Broken pipe
,D/ConnectivityService(  762): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): ValidatedState{ when=-1ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): DefaultState{ when=-1ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/ConnectivityService(  762): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,D/ConnectivityService(  762): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,E/WifiConfigStore(  762): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
E/WifiStateMachine(  762): Start Disconnecting Watchdog 1
E/native  (  762): do suspend true
I/wpa_supplicant(  983): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/CommandListener(  179): Clearing all IP addresses on wlan0
D/ConnectivityService(  762): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/Nat464Xlat(  762): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  762): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): Disconnected - quitting
D/ConnectivityService(  762): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler(  917): CM callback handler got msg 524292
,D/ConnectivityService(  762): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityManager.CallbackHandler( 1637): CM callback handler got msg 524292
,D/ConnectivityService(  762): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1304): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/ConnectivityService(  762): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,D/WifiNetworkAgent(  762): NetworkAgent: NetworkAgent channel lost
,I/wpa_supplicant(  983): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant(  983): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant(  983): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant(  983): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  762): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  762): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  762): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiConfigStore(  762): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  179): Setting iface cfg
E/WifiStateMachine(  762): Start Dhcp Watchdog 2
,E/native  (  762): do suspend false
,E/WifiStateMachine(  762): scanCount==0 - aborting
,I/dhcpcd  ( 3391): version 5.5.6 starting
,E/dhcpcd  ( 3391): get_duid: Read-only file system
,I/dhcpcd  ( 3391): wlan0: rebinding lease of 192.168.1.114
,I/dhcpcd  ( 3391): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3391): wlan0: leased 192.168.1.114 for 86400 seconds
,E/native  (  762): do suspend true
,D/ConnectivityService(  762): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService(  762): Adding iface wlan0 to network 101
,E/ConnectivityService(  762): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  762): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/ConnectivityService(  762): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  762): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  762): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  762): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  762): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  762): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/ConnectivityService(  762): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  762):    accepting network in place of null
,D/CSLegacyTypeTracker(  762): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  762): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  762): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  762): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  917): CM callback handler got msg 524290
D/ConnectivityManager.CallbackHandler( 1637): CM callback handler got msg 524290
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Sun, 17 Jan 2016 09:45:57 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1453023957312], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1453023957295]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  762): Validated
D/ConnectivityService(  762): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  762): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  762): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  762): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  762): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/TelephonyNetworkFactory( 1304): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler(  917): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1637): CM callback handler got msg 524290
,I/jxcore-log( 3289): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3289): 
,D/Nat464Xlat(  762): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  762): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler(  917): CM callback handler got msg 524295
D/ConnectivityManager.CallbackHandler( 1637): CM callback handler got msg 524295
,I/jxcore-log( 3289): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 3289): 
I/jxcore-log( 3289): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 3289): 
,I/jxcore-log( 3289): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 3289): 
,I/jxcore-log( 3289): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 3289): 
,I/jxcore-log( 3289): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 3289): 
,I/jxcore-log( 3289): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3289): 
,D/ConnectivityService(  762): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering(  762): MasterInitialState.processMessage what=3
D/ConnectivityService(  762): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  762): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2771): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2771): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 2771): type=WIFI subType= reason=null isConnected=true
,I/SystemUpdateService( 1637): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
D/SystemUpdateService( 1637): onCreate
D/SystemUpdateService( 1637): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/ActivityManager(  762): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3435 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SystemUpdateService( 1637): active receiver: enabled
,I/SystemUpdateService( 1637): showing system update notification
,E/GpsLocationProvider(  762): No APN found to select.
,E/GpsLocationProvider(  762): No APN found to select.
,I/ValidateNoPeople(  762): skipping global notification
,V/SystemUpdateService( 1637): retry (wakeup: false) in 3599955 ms
,D/SystemUpdateService( 1637): onDestroy
,I/GAv4    ( 3435): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3435):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3435):   adb logcat -s GAv4
,W/GAv4    ( 3435): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,D/ConnectivityService(  762): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,W/GAv4    ( 3435): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3435): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/jxcore-log( 3289): Test app app.js loaded
I/jxcore-log( 3289): 
,I/chromium( 3289): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/WebViewFactory( 3435): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3435): Time to load native libraries: 1 ms (timestamps 7546-7547)
,I/LibraryLoader( 3435): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3435): Binding Chromium to main looper Looper (main, tid 1) {3c7d80db}
,I/LibraryLoader( 3435): Expected native library version number "",actual native library version number ""
,I/chromium( 3435): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3435): Initializing chromium process, singleProcess=true
,W/art     ( 3435): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3435): ApplicationContext is null in ApplicationStatus
,W/chromium( 3435): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3435): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3435): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3435): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/AudioManagerAndroid( 3435): Requires BLUETOOTH permission
,I/NSApplication( 3435): Starting up...
,I/ActivityManager(  762): Killing 2542:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,W/libprocessgroup(  762): failed to open /acct/uid_10045/pid_2542/cgroup.procs: No such file or directory
,V/MusicLeanback( 2771): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1637): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1637): onCreate
,D/SystemUpdateService( 1637): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1637): active receiver: enabled
,I/SystemUpdateService( 1637): showing system update notification
,I/ValidateNoPeople(  762): skipping global notification
,V/SystemUpdateService( 1637): retry (wakeup: false) in 3599973 ms
,D/SystemUpdateService( 1637): onDestroy
,D/ConnectivityService(  762): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  762): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2771): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2771): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1637): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1637): onCreate
,D/SystemUpdateService( 1637): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1637): active receiver: enabled
,I/SystemUpdateService( 1637): showing system update notification
,E/GpsLocationProvider(  762): No APN found to select.
,I/ValidateNoPeople(  762): skipping global notification
,V/SystemUpdateService( 1637): retry (wakeup: false) in 3599985 ms
,D/SystemUpdateService( 1637): onDestroy
,D/Finsky  ( 2632): [255] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2632): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/art     (  762): Explicit concurrent mark sweep GC freed 48247(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 27MB/41MB, paused 818us total 71.029ms
,V/GLSActivity( 1603): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1603): Vacuum at: now=1453023975615 tag=VacuumService
,I/PhenotypeConfigurator( 1603): Scheduling Phenotype for one-off execution 4207 seconds from now (1453023976027)
,D/GetConfigurationSnapshotOperation( 1603): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1603): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1603): Using platform SSLCertificateSocketFactory
,V/GLSActivity( 1603): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1603): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ClearcutLoggerApiImpl( 1603): disconnect managed GoogleApiClient
,D/HeadsetStateMachine( 2107): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 2107): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
D/HeadsetStateMachine( 2107): Disconnected process message: 11, size: 0
,I/jxcore-log( 3289): --= Surplus to requirements =--
I/jxcore-log( 3289): 
I/jxcore-log( 3289): ****TEST TOOK:  ms ****
I/jxcore-log( 3289): 
I/jxcore-log( 3289): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3289): 
,D/AndroidRuntime( 3624): 
D/AndroidRuntime( 3624): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 3624): CheckJNI is OFF
,D/AndroidRuntime( 3624): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  762): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  762): Killing 3289:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
,I/WindowState(  762): WIN DEATH: Window{277c192f u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  762): Client connection lost with reason: 4
,W/PackageSettings(  762): Skipping PackageSetting{311a0c15 com.example.hello/10278} due to missing metadata
,I/ActivityManager(  762):   Force finishing activity ActivityRecord{1bd4896b u0 com.test.thalitest/.MainActivity t216}
,W/ActivityManager(  762): Spurious death for ProcessRecord{2c709e73 3289:com.test.thalitest/u0a270}, curProc for 3289: null
,I/ActivityManager(  762): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
,I/InputReader(  762): Reconfiguring input devices.  changes=0x00000010
,I/art     ( 1637): Explicit concurrent mark sweep GC freed 11791(563KB) AllocSpace objects, 1(16KB) LOS objects, 25% free, 22MB/30MB, paused 555us total 51.485ms
I/art     ( 1368): Explicit concurrent mark sweep GC freed 3845(287KB) AllocSpace objects, 1(126KB) LOS objects, 38% free, 25MB/41MB, paused 5.845ms total 22.554ms
I/Keyboard.Facilitator( 1097): resetDictionaries() : en_US
,I/Keyboard.Facilitator.DecoderInitializer( 1097): run()
,W/GeofencerStateMachine( 1603): Ignoring removeGeofence because network location is disabled.
,I/Decoder ( 1097): createOrResetDecoder
,I/art     (  762): Explicit concurrent mark sweep GC freed 20927(1224KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 1.614ms total 82.212ms
,I/Adreno-EGL(  939): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/OpenGLRenderer(  939): Initialized EGL, version 1.4
,D/VoicemailCleanupService( 1403): Cleaning up data for package: com.test.thalitest
,I/art     ( 1425): Explicit concurrent mark sweep GC freed 11714(908KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 19MB/25MB, paused 374us total 125.527ms
,D/OpenGLRenderer(  939): Enabling debug mode 0
,I/UpdateIcingCorporaServi( 1425): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,W/Launcher( 1368): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@3fa83f6 new=com.google.android.velvet.VelvetApplication@3fa83f6
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1097): run()
,W/InputMethodManagerService(  762): Got RemoteException sending setActive(false) notification to pid 3289 uid 10270
,I/Keyboard.Facilitator( 1097): onFinishInput()
,I/ActivityManager(  762): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3664 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,D/BackupManagerService(  762): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  762): Receieved: android.intent.action.PACKAGE_REMOVED
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1097): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1097): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1097): run() : Loading LM = contacts
,D/TaskPersister(  762): removeObsoleteFile: deleting file=216_task.xml
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1097): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1097): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1097): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1097): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1097): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1097): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1097): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1097): run()
I/StatsUtilsManager( 1097): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1097): shouldRecordStats() = Too Soon
,W/ContextImpl( 3664): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
,I/UpdateIcingCorporaServi( 1425): UpdateCorporaTask done [took 131 ms] updated apps [took 131 ms] 
,D/PackageBroadcastService( 1637): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1637): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1637): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1637): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1637): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1637): Module APK com.google.android.play.games already loaded
,I/LocationSettingsChecker( 1637): Removing dialog suppression flag for package com.test.thalitest
E/NetworkScheduler.SchedulerReceiver( 1603): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1603): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,W/ResourcesManager( 1368): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/art     (  762): Explicit concurrent mark sweep GC freed 6885(354KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 1.711ms total 156.463ms
,I/Launcher( 1368): Deferring update until onResume
,W/ResourcesManager( 1368): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Launcher( 1368): Deferring update until onResume
,D/gH_CompatibleDatabase( 1637): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1637): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1637): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1637): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/gH_CompatibleDatabase( 1637): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1637): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/gH_CompatibleDatabase( 1637): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/gH_CompatibleDatabase( 1637): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1637): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1637): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,D/gH_CompatibleDatabase( 1637): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1637): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1637): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/ActivityManager(  762): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3696 uid=10039 gids={50039, 9997} abi=armeabi-v7a
,W/BaseAppContext( 1637): Using Auth Proxy for data requests.
,I/GMPM-SVC( 1637): App measurement is starting up, version: 8489
I/GMPM-SVC( 1637): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,W/BaseAppContext( 1637): Using Auth Proxy for data requests.
I/ActivityManager(  762): Killing 2747:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,D/AndroidRuntime( 3624): Shutting down VM
,W/libprocessgroup(  762): failed to open /acct/uid_10003/pid_2747/cgroup.procs: No such file or directory
,I/Icing   ( 1637): doRemovePackageData com.test.thalitest
,I/ActivityManager(  762): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3721 uid=10007 gids={50007, 9997, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  762): Killing 2726:com.android.settings/1000 (adj 15): empty #17
,D/WifiService(  762): Client connection lost with reason: 4
,W/libprocessgroup(  762): failed to open /acct/uid_1000/pid_2726/cgroup.procs: No such file or directory
,I/ActivityManager(  762): Killing 2563:com.google.android.gm/u0a70 (adj 15): empty #17
,W/libprocessgroup(  762): failed to open /acct/uid_10070/pid_2563/cgroup.procs: No such file or directory
,D/ExternalStorage( 3721): After updating volumes, found 1 active roots
,W/ResourcesManager( 3204): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3204): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/Documents( 3696): Update found 7 roots in 302ms
,D/Documents( 3696): Update found 7 roots in 78ms

```
