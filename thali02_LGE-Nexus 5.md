#### Test 5667282762e056f_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
D/ChimeraCfgMgr( 1675): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1675): Module APK com.google.android.play.games already loaded
D/CAR.SERVICE( 3111): mConnectedToCar = false, abort
--------- beginning of system
E/ActivityThread( 3111): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@172d5245 that was originally bound here
E/ActivityThread( 3111): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@172d5245 that was originally bound here
E/ActivityThread( 3111): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3111): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3111): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3111): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3111): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3111): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3111): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3111): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3111): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3111): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 3111): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 3111): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 3111): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 3111): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2731)
E/ActivityThread( 3111): 	at android.app.ActivityThread.access$1800(ActivityThread.java:144)
E/ActivityThread( 3111): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1361)
E/ActivityThread( 3111): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3111): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3111): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3111): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3111): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3111): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3111): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
E/ActivityThread( 3111): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@33855d54 that was originally bound here
E/ActivityThread( 3111): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@33855d54 that was originally bound here
E/ActivityThread( 3111): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 3111): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 3111): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 3111): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 3111): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3111): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 3111): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 3111): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 3111): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 3111): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 3111): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 3111): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 3111): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2758)
E/ActivityThread( 3111): 	at android.app.ActivityThread.access$1900(ActivityThread.java:144)
E/ActivityThread( 3111): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
E/ActivityThread( 3111): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3111): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3111): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/ActivityThread( 3111): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3111): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3111): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/ActivityThread( 3111): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
W/ActivityManager(  761): Unbind failed: could not find connection for android.os.BinderProxy@22e1ed0d
I/GAv4    ( 3231): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3231):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3231):   adb logcat -s GAv4
W/GAv4    ( 3231): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3231): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3231): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 3231): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
W/ResourcesManager( 3231): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3231): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/Finsky  ( 2643): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
I/ActivityManager(  761): Killing 2709:com.android.settings/1000 (adj 15): empty #17
V/JNIHelp ( 3231): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/WifiService(  761): Client connection lost with reason: 4
W/System  ( 3231): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3231): Installed default security provider GmsCore_OpenSSL
W/libprocessgroup(  761): failed to open /acct/uid_1000/pid_2709/cgroup.procs: No such file or directory
V/GLSActivity( 1610): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 1675): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/Icing   ( 1675): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1675): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/Icing   ( 1675): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
,I/ActivityManager(  761): Killing 2581:com.google.android.gm/u0a70 (adj 15): empty #17
D/AndroidRuntime( 3293): 
D/AndroidRuntime( 3293): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3293): CheckJNI is OFF
D/AndroidRuntime( 3293): Calling main entry com.android.commands.am.Am
W/libprocessgroup(  761): failed to open /acct/uid_10070/pid_2581/cgroup.procs: No such file or directory
I/ActivityManager(  761): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  761): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3331 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3293): Shutting down VM
V/ActivityManager(  761): Display changed displayId=0
I/WebViewFactory( 3331): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3331): Time to load native libraries: 2 ms (timestamps 4503-4505)
I/LibraryLoader( 3331): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3331): Binding Chromium to main looper Looper (main, tid 1) {14b6fc94}
I/LibraryLoader( 3331): Expected native library version number "",actual native library version number ""
I/chromium( 3331): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3331): Initializing chromium process, singleProcess=true
W/art     ( 3331): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3331): ApplicationContext is null in ApplicationStatus
W/chromium( 3331): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3331): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3331): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3331): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  761): Message: 20
D/BluetoothManagerService(  761): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c49ac1f:true
,W/art     ( 3331): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3331): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3331): CordovaWebView is running on device made by: LGE
,W/art     ( 3331): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3331): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3331): Render dirty regions requested: true
,D/Atlas   ( 3331): Validating map...
,W/chromium( 3331): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3331): Initialized EGL, version 1.4
D/OpenGLRenderer( 3331): Enabling debug mode 0
,I/ActivityManager(  761): Displayed com.test.thalitest/.MainActivity: +453ms (total +53s273ms)
,W/IInputConnectionWrapper( 3331): showStatusIcon on inactive InputConnection
,W/BindingManager( 3331): Cannot call determinedVisibility() - never saw a connection for the pid: 3331
,D/JsMessageQueue( 3331): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3331): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1405523712
,I/chromium( 3331): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 3331): Initializing JXcore engine
W/jxcore-log( 3331): JXcore engine is ready
,W/Thread-316( 3385): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[8170]" dev="sockfs" ino=8170 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-316( 3385): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-316( 3385): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[10317]" dev="sockfs" ino=10317 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-316( 3385): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[20681]" dev="sockfs" ino=20681 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3331): Starting JXcore engine
,W/jxcore-log( 3331): Platform android
W/jxcore-log( 3331): 
W/jxcore-log( 3331): Process ARCH arm
W/jxcore-log( 3331): 
,I/jxcore-log( 3331): JXcore Cordova bridge is ready!
I/jxcore-log( 3331): 
,W/jxcore-log( 3331): JXcore engine is started
,I/jxcore-log( 3331): Toggling radios to true
I/jxcore-log( 3331): 
,D/BluetoothAdapter( 3331): enable(): BT is already enabled..!
,D/WifiService(  761): New client listening to asynchronous messages
,D/WifiService(  761): setWifiEnabled: true pid=3331, uid=10270
E/WifiService(  761): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 3331): Radios toggled
I/jxcore-log( 3331): 
I/jxcore-log( 3331): My device name is: LGE-Nexus 5
I/jxcore-log( 3331): 
I/wpa_supplicant( 1031): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
E/WifiStateMachine(  761): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  761): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
E/native  (  761): do suspend true
D/CommandListener(  180): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1610): Read error: ssl=0xb3d3ae00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1610): SSL shutdown failed: ssl=0xb3d3ae00: I/O error during system call, Broken pipe
,D/ConnectivityService(  761): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): ValidatedState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): DefaultState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Checking http://clients3.google.com/generate_204 on "NG7005g"
,E/WifiConfigStore(  761): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  761): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  761): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,E/WifiStateMachine(  761): Start Disconnecting Watchdog 1
,E/native  (  761): do suspend true
,I/wpa_supplicant( 1031): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/CommandListener(  180): Clearing all IP addresses on wlan0
,D/ConnectivityService(  761): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler(  898): CM callback handler got msg 524292
D/Nat464Xlat(  761): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/CSLegacyTypeTracker(  761): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Disconnected - quitting
,D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityManager.CallbackHandler( 1675): CM callback handler got msg 524292
D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  761): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory( 1206): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WifiNetworkAgent(  761): NetworkAgent: NetworkAgent channel lost
,I/wpa_supplicant( 1031): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant( 1031): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1031): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1031): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  761): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  761): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  761): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  761): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  180): Setting iface cfg
E/WifiStateMachine(  761): Start Dhcp Watchdog 2
,E/native  (  761): do suspend false
,E/WifiStateMachine(  761): scanCount==0 - aborting
,I/dhcpcd  ( 3419): version 5.5.6 starting
E/dhcpcd  ( 3419): get_duid: Read-only file system
,I/dhcpcd  ( 3419): wlan0: rebinding lease of 192.168.1.114
,I/dhcpcd  ( 3419): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3419): wlan0: leased 192.168.1.114 for 86400 seconds
,E/native  (  761): do suspend true
,D/ConnectivityService(  761): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService(  761): Adding iface wlan0 to network 101
E/WifiStateMachine(  761): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  761): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  761): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  761): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  761): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  761): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  761): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  761): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  761): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): DefaultState{ when=-5ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Checking http://clients3.google.com/generate_204 on "NG7005g"
D/ConnectivityService(  761): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  761):    accepting network in place of null
D/CSLegacyTypeTracker(  761): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  761): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  761): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  898): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1675): CM callback handler got msg 524290
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 26 Jan 2016 17:55:56 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1453830956091], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1453830956072]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Validated
,D/ConnectivityService(  761): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  761): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  761): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  761): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  898): CM callback handler got msg 524290
D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1675): CM callback handler got msg 524290
,D/TelephonyNetworkFactory( 1206): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/Nat464Xlat(  761): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  761): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1675): CM callback handler got msg 524295
D/ConnectivityManager.CallbackHandler(  898): CM callback handler got msg 524295
,D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  761): MasterInitialState.processMessage what=3
,D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  761): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2747): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2747): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 2747): type=WIFI subType= reason=null isConnected=true
,I/SystemUpdateService( 1675): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1675): onCreate
,D/SystemUpdateService( 1675): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1675): active receiver: enabled
,I/SystemUpdateService( 1675): showing system update notification
,I/ActivityManager(  761): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3474 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ConnectivityService(  761): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,E/GpsLocationProvider(  761): No APN found to select.
,I/ValidateNoPeople(  761): skipping global notification
,E/GpsLocationProvider(  761): No APN found to select.
,V/SystemUpdateService( 1675): retry (wakeup: false) in 3599614 ms
,D/SystemUpdateService( 1675): onDestroy
,I/jxcore-log( 3331): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3331): 
,I/GAv4    ( 3474): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3474):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3474):   adb logcat -s GAv4
,W/GAv4    ( 3474): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3474): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3474): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 3474): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3474): Time to load native libraries: 1 ms (timestamps 996-997)
,I/LibraryLoader( 3474): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3474): Binding Chromium to main looper Looper (main, tid 1) {26ff9966}
,I/LibraryLoader( 3474): Expected native library version number "",actual native library version number ""
,I/chromium( 3474): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3474): Initializing chromium process, singleProcess=true
,W/art     ( 3474): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3474): ApplicationContext is null in ApplicationStatus
,W/chromium( 3474): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3474): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3474): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3474): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/AudioManagerAndroid( 3474): Requires BLUETOOTH permission
,I/NSApplication( 3474): Starting up...
,I/ActivityManager(  761): Killing 2956:com.google.android.keep/u0a71 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10071/pid_2956/cgroup.procs: No such file or directory
,V/MusicLeanback( 2747): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1675): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1675): onCreate
D/SystemUpdateService( 1675): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1675): active receiver: enabled
,I/SystemUpdateService( 1675): showing system update notification
,I/ValidateNoPeople(  761): skipping global notification
,V/SystemUpdateService( 1675): retry (wakeup: false) in 3599973 ms
,D/SystemUpdateService( 1675): onDestroy
,I/jxcore-log( 3331): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 3331): 
I/jxcore-log( 3331): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3331): 
,V/GLSActivity( 1610): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1610): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 3331): Test app app.js loaded
I/jxcore-log( 3331): 
,I/chromium( 3331): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 3331): BLE advertisement is supported
I/jxcore-log( 3331): 
,D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  761): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2747): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2747): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1675): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1675): onCreate
,D/SystemUpdateService( 1675): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1675): active receiver: enabled
,I/SystemUpdateService( 1675): showing system update notification
,I/ValidateNoPeople(  761): skipping global notification
,V/SystemUpdateService( 1675): retry (wakeup: false) in 3599922 ms
,I/art     (  761): Explicit concurrent mark sweep GC freed 46565(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 27MB/41MB, paused 1.173ms total 100.133ms
,D/SystemUpdateService( 1675): onDestroy
,E/GpsLocationProvider(  761): No APN found to select.
,D/Finsky  ( 2643): [255] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2643): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/GLSActivity( 1610): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1610): Vacuum at: now=1453830974546 tag=VacuumService
,I/PhenotypeConfigurator( 1610): Scheduling Phenotype for one-off execution 731 seconds from now (1453830974975)
,D/GetConfigurationSnapshotOperation( 1610): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1610): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1610): Using platform SSLCertificateSocketFactory
,I/ClearcutLoggerApiImpl( 1610): disconnect managed GoogleApiClient
,I/jxcore-log( 3331): TAP version 13
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): # setup
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): # multiplex can send data
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): # teardown
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): ok 1 String should be length:200
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): # setup
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): # enqueue and run in order
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): # teardown
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): ok 2 firstPromise setTimeout
I/jxcore-log( 3331): 
I/jxcore-log( 3331): ok 3 firstPromise result
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): ok 4 firstPromise testValue
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): ok 5 secondPromise setTimeout
I/jxcore-log( 3331): 
I/jxcore-log( 3331): ok 6 secondPromise result
I/jxcore-log( 3331): 
I/jxcore-log( 3331): ok 7 secondPromise testValue
I/jxcore-log( 3331): 
I/jxcore-log( 3331): ok 8 thirdPromise in promise
I/jxcore-log( 3331): 
I/jxcore-log( 3331): ok 9 thirdPromise result
I/jxcore-log( 3331): 
I/jxcore-log( 3331): ok 10 thirdPromise testValue
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): # setup
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): # basic
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): # teardown
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): ok 11 sane
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): # setup
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): # another
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): # teardown
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): ok 12 sane
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): # setup
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): # successfully create a new pkcs12 file and return hash value
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): # teardown
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): ok 13 should be equal
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): ok 14 null
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): ok 15 (unnamed assert)
I/jxcore-log( 3331): 
I/jxcore-log( 3331): ok 16 should be equal
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): ok 17 should not throw
I/jxcore-log( 3331): 
I/jxcore-log( 3331): # setup
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): # successfully read a previous pkcs12 file and return hash value
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): # teardown
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): ok 18 (unnamed assert)
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): ok 19 (unnamed assert)
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): ok 20 should not throw
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): ok 21 should be equal
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): ok 22 should be equal
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): # setup
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): # failed to extract public key because of corrupt pkcs12 file
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): # teardown
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): ok 23 should be equal
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): # setup
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): # failed to get mobile documents path
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): # teardown
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): ok 24 should be equal
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): # setup
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): # #init should register the peerAvailabilityChanged event
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): # teardown
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): ok 25 should be equal
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): ok 26 should be equal
I/jxcore-log( 3331): 
I/jxcore-log( 3331): ok 27 should be equal
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): # setup
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): # #init should register the networkChanged event
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): # teardown
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): ok 28 should be equal
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): # setup
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): # #startBroadcasting should throw on null device name
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): # teardown
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): ok 29 should throw
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): # setup
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): # #startBroadcasting should throw on empty string device name
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): # teardown
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): ok 30 should throw
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): # setup
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): # #startBroadcasting should throw on non-number port
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): # teardown
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): ok 31 should throw
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): # setup
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): # #startBroadcasting should throw on NaN port
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): # teardown
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): ok 32 should throw
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): # setup
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): # #startBroadcasting should throw on negative port
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): # teardown
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): ok 33 should throw
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): # setup
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): # #startBroadcasting should throw on too large port
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): # teardown
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): ok 34 should throw
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): # setup
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): # #startBroadcasting should call Mobile("StartBroadcasting") without an error
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): # teardown
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): ok 35 should be equal
I/jxcore-log( 3331): 
I/jxcore-log( 3331): ok 36 should be equal
I/jxcore-log( 3331): 
I/jxcore-log( 3331): ok 37 should be equal
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): # setup
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): # #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): # teardown
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): ok 38 should be equal
I/jxcore-log( 3331): 
I/jxcore-log( 3331): ok 39 should be equal
I/jxcore-log( 3331): 
I/jxcore-log( 3331): ok 40 should be equal
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): # setup
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): # #stopBroadcasting should call Mobile("StopBroadcasting") without an error
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): # teardown
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): ok 41 should be equal
I/jxcore-log( 3331): 
I/jxcore-log( 3331): ok 42 should be equal
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): # setup
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): # #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): # teardown
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): ok 43 should be equal
I/jxcore-log( 3331): 
I/jxcore-log( 3331): ok 44 should be equal
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): # setup
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): # #connect should call Mobile("Connect") with a port and without an error
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): # teardown
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): ok 45 should be equal
I/jxcore-log( 3331): 
I/jxcore-log( 3331): ok 46 should be equal
I/jxcore-log( 3331): 
I/jxcore-log( 3331): ok 47 should be equal
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): # setup
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): # #connect should call Mobile("Connect") and handle an error
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): # teardown
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): ok 48 should be equal
I/jxcore-log( 3331): 
I/jxcore-log( 3331): ok 49 should be equal
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): # setup
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): # should call Mobile("Disconnect") without an error
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): # teardown
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): ok 50 should be equal
I/jxcore-log( 3331): 
I/jxcore-log( 3331): ok 51 should be equal
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): # setup
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): # should call Mobile("Disconnect") and handle an error
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): # teardown
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): ok 52 should be equal
I/jxcore-log( 3331): 
I/jxcore-log( 3331): ok 53 should be equal
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): # setup
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): # ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): # teardown
I/jxcore-log( 3331): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): setDiscoveryMode: Mode set to BLE_AND_WIFI
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3331): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453831184354.3331
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3331): bind: Binding a new listener
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3331): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3331): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453831184354.3331","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3331): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3331): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3331): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3331): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3331): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 3331): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3331): start: OK
I/io.jxcore.node.ConnectionHelper( 3331): start: Using peer discovery mode: BLE_AND_WIFI
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453831184354.3331
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3331): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3331): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3331): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3331): createAdvertiseData: From: 1453831184354.3331 b6a44ad1-d319-4b3a-815d-8b805a47fb51 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3331): 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3331): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 52, -4, -17, 17, -82, 103]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3331): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3331): Waiting for incoming connections...
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3331): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453831184354.3331","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3331): start: {"pi":"34:FC:EF:11:AE:67","pn":"1453831184354.3331","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3331): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1453831184354.3331","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): setState: RUNNING_WIFI
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453831184354.3331
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): startBlePeerDiscovery: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3331): Local service added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3331): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 3331): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
,I/io.jxcore.node.ConnectionHelper( 3331): start: OK
,I/jxcore-log( 3331): ok 54 Should be able to call startBroadcasting without error
I/jxcore-log( 3331): 
I/io.jxcore.node.ConnectionHelper( 3331): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3331): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3331): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3331): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3331): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3331): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3331): onServerStopped
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3331): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3331): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 3331): onConnectionManagerStateChanged: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): stop: Stopping peer discovery...
,D/BluetoothLeScanner( 3331): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3331): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3331): Local services cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): stop: Stopping P2P device discovery...
,I/wpa_supplicant( 1031): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): P2P device discovery stopped successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): setState: NOT_INITIALIZED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3331): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3331): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3331): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 3331): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 3331): ok 55 Should be able to call stopBroadcasting without error
I/jxcore-log( 3331): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): setDiscoveryMode: Mode set to BLE_AND_WIFI
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3331): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453831184431.3331
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3331): bind: Binding a new listener
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3331): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3331): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453831184431.3331","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3331): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3331): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3331): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3331): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3331): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 3331): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3331): start: OK
I/io.jxcore.node.ConnectionHelper( 3331): start: Using peer discovery mode: BLE_AND_WIFI
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453831184431.3331
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3331): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3331): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3331): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3331): createAdvertiseData: From: 1453831184431.3331 b6a44ad1-d319-4b3a-815d-8b805a47fb51 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3331): 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3331): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 52, -4, -17, 17, -82, 103]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3331): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3331): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453831184431.3331","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3331): start: {"pi":"34:FC:EF:11:AE:67","pn":"1453831184431.3331","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3331): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1453831184431.3331","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): start: Starting P2P device discovery...
,I/wpa_supplicant( 1031): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): setState: RUNNING_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453831184431.3331
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): startBlePeerDiscovery: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): startWifiPeerDiscovery: Wi-Fi Direct OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3331): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): setState: RESTARTING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/io.jxcore.node.ConnectionHelper( 3331): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 3331): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
,I/wpa_supplicant( 1031): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): P2P device discovery stopped successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): setState: RESTARTING
,I/io.jxcore.node.ConnectionHelper( 3331): start: OK
I/jxcore-log( 3331): ok 56 Should be able to call startBroadcasting without error
I/jxcore-log( 3331): 
I/io.jxcore.node.ConnectionHelper( 3331): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3331): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3331): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3331): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3331): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3331): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3331): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 3331): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): stop: Stopping peer discovery...
,D/BluetoothLeScanner( 3331): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3331): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3331): Local services cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): setState: NOT_INITIALIZED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3331): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3331): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3331): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3331): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 3331): ok 57 Should be able to call stopBroadcasting without error
I/jxcore-log( 3331): 
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3331): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3331): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3331): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453831184475.3331
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3331): bind: Binding a new listener
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3331): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3331): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453831184475.3331","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3331): setConnectionTimeout: 15000
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3331): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3331): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3331): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3331): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 3331): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3331): start: OK
I/io.jxcore.node.ConnectionHelper( 3331): start: Using peer discovery mode: BLE_AND_WIFI
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453831184475.3331
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3331): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3331): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3331): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3331): createAdvertiseData: From: 1453831184475.3331 b6a44ad1-d319-4b3a-815d-8b805a47fb51 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3331): 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3331): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 52, -4, -17, 17, -82, 103]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3331): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3331): Waiting for incoming connections...
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3331): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453831184475.3331","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3331): start: {"pi":"34:FC:EF:11:AE:67","pn":"1453831184475.3331","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3331): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1453831184475.3331","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): setState: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 3331): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453831184475.3331
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): setState: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3331): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 3331): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 3331): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/wpa_supplicant( 1031): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): setState: STARTED
I/jxcore-log( 3331): ok 58 Should be able to call startBroadcasting without error
I/jxcore-log( 3331): 
I/io.jxcore.node.ConnectionHelper( 3331): stop
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3331): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3331): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3331): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3331): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3331): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3331): onServerStopped
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3331): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3331): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): stop: Stopping peer discovery...
I/io.jxcore.node.ConnectionHelper( 3331): onConnectionManagerStateChanged: NOT_STARTED
D/BluetoothLeScanner( 3331): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3331): stop: Stopping services
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/wpa_supplicant( 1031): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): P2P device discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3331): Local services cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3331): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): P2P device discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3331): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3331): Service requests cleared successfully
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 3331): onDiscoveryManagerStateChanged: NOT_STARTED
,I/jxcore-log( 3331): ok 59 Should be able to call stopBroadcasting without error
I/jxcore-log( 3331): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3331): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453831184527.3331
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3331): bind: Binding a new listener
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3331): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3331): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453831184527.3331","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3331): setConnectionTimeout: 15000
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3331): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3331): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3331): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3331): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3331): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3331): start: OK
I/io.jxcore.node.ConnectionHelper( 3331): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453831184527.3331
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3331): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3331): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3331): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3331): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3331): createAdvertiseData: From: 1453831184527.3331 b6a44ad1-d319-4b3a-815d-8b805a47fb51 34:FC:EF:11:AE:67
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3331): 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3331): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 52, -4, -17, 17, -82, 103]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3331): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3331): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453831184527.3331","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3331): start: {"pi":"34:FC:EF:11:AE:67","pn":"1453831184527.3331","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3331): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1453831184527.3331","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): startWifiPeerDiscovery: Wi-Fi Direct OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): setState: RUNNING_WIFI
I/wpa_supplicant( 1031): p2p0: P2P: Reject scan trigger since one is already pending
I/io.jxcore.node.ConnectionHelper( 3331): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453831184527.3331
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): setState: RUNNING_BLE_AND_WIFI
I/jxcore-log( 3331): ok 60 Should be able to call startBroadcasting without error
I/jxcore-log( 3331): 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3331): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 3331): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 3331): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3331): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3331): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3331): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3331): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3331): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3331): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3331): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1031): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3331): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3331): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): stop: Stopping peer discovery...
I/io.jxcore.node.ConnectionHelper( 3331): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): P2P device discovery stopped successfully
D/BluetoothLeScanner( 3331): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3331): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3331): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3331): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3331): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3331): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3331): Service requests cleared successfully
I/jxcore-log( 3331): ok 61 Should be able to call stopBroadcasting without error
I/jxcore-log( 3331): 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3331): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453831184558.3331
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3331): bind: Binding a new listener
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3331): initialize: My bluetooth address is 34:FC:EF:11:AE:67
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3331): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453831184558.3331","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3331): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3331): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3331): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 3331): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3331): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3331): start: OK
I/io.jxcore.node.ConnectionHelper( 3331): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3331): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453831184558.3331
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3331): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3331): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3331): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3331): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3331): createAdvertiseData: From: 1453831184558.3331 b6a44ad1-d319-4b3a-815d-8b805a47fb51 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3331): 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3331): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 52, -4, -17, 17, -82, 103]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3331): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3331): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453831184558.3331","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3331): start: {"pi":"34:FC:EF:11:AE:67","pn":"1453831184558.3331","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3331): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1453831184558.3331","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453831184558.3331
I/wpa_supplicant( 1031): p2p0: P2P: Reject scan trigger since one is already pending
I/io.jxcore.node.ConnectionHelper( 3331): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3331): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 3331): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 3331): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/jxcore-log( 3331): ok 62 Should be able to call startBroadcasting without error
I/jxcore-log( 3331): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/wpa_supplicant( 1031): P2P-FIND-STOPPED 
I/io.jxcore.node.ConnectionHelper( 3331): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3331): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3331): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3331): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3331): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3331): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3331): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3331): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3331): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3331): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): setState: RESTARTING
D/BluetoothLeScanner( 3331): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3331): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3331): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3331): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3331): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3331): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3331): Service requests cleared successfully
I/jxcore-log( 3331): ok 63 Should be able to call stopBroadcasting without error
I/jxcore-log( 3331): 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3331): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453831184586.3331
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3331): bind: Binding a new listener
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3331): initialize: My bluetooth address is 34:FC:EF:11:AE:67
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3331): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453831184586.3331","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3331): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3331): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3331): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 3331): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3331): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3331): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3331): start: OK
I/io.jxcore.node.ConnectionHelper( 3331): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453831184586.3331
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3331): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3331): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3331): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3331): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3331): createAdvertiseData: From: 1453831184586.3331 b6a44ad1-d319-4b3a-815d-8b805a47fb51 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3331): 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3331): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 52, -4, -17, 17, -82, 103]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3331): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3331): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453831184586.3331","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3331): start: {"pi":"34:FC:EF:11:AE:67","pn":"1453831184586.3331","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3331): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1453831184586.3331","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453831184586.3331
I/io.jxcore.node.ConnectionHelper( 3331): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): startBlePeerDiscovery: OK
I/jxcore-log( 3331): ok 64 Should be able to call startBroadcasting without error
I/jxcore-log( 3331): 
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): setState: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 3331): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3331): stop: Stopping Bluetooth...
I/io.jxcore.node.ConnectionHelper( 3331): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3331): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3331): stopListeningForIncomingConnections: Stopping...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3331): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3331): shutdown
I/io.jxcore.node.ConnectionHelper( 3331): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3331): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3331): setState: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3331): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3331): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): stop: Stopping peer discovery...
I/io.jxcore.node.ConnectionHelper( 3331): onConnectionManagerStateChanged: NOT_STARTED
D/BluetoothLeScanner( 3331): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3331): stop: Stopping services
I/wpa_supplicant( 1031): p2p0: P2P: Reject scan trigger since one is already pending
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3331): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3331): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3331): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): setState: STARTED
I/wpa_supplicant( 1031): P2P-FIND-STOPPED 
I/jxcore-log( 3331): ok 65 Should be able to call stopBroadcasting without error
I/jxcore-log( 3331): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3331): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453831184613.3331
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3331): bind: Binding a new listener
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3331): initialize: My bluetooth address is 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3331): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3331): Service requests cleared successfully
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3331): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453831184613.3331","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3331): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3331): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3331): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 3331): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3331): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3331): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3331): start: OK
I/io.jxcore.node.ConnectionHelper( 3331): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3331): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453831184613.3331
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3331): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3331): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3331): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3331): createAdvertiseData: From: 1453831184613.3331 b6a44ad1-d319-4b3a-815d-8b805a47fb51 34:FC:EF:11:AE:67
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3331): 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3331): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 52, -4, -17, 17, -82, 103]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3331): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3331): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453831184613.3331","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3331): start: {"pi":"34:FC:EF:11:AE:67","pn":"1453831184613.3331","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3331): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1453831184613.3331","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): setState: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 3331): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453831184613.3331
I/wpa_supplicant( 1031): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): startBlePeerDiscovery: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): setState: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 3331): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3331): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 3331): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/wpa_supplicant( 1031): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): P2P device discovery stopped successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): setState: RESTARTING
,I/jxcore-log( 3331): ok 66 Should be able to call startBroadcasting without error
I/jxcore-log( 3331): 
I/io.jxcore.node.ConnectionHelper( 3331): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3331): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3331): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3331): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3331): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3331): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3331): setState: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3331): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3331): onServerStopped
I/io.jxcore.node.ConnectionHelper( 3331): onConnectionManagerStateChanged: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): stop: Stopping peer discovery...
,D/BluetoothLeScanner( 3331): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3331): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3331): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3331): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3331): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3331): onDiscoveryManagerStateChanged: NOT_STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): P2P device discovery stopped successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3331): Service requests cleared successfully
I/jxcore-log( 3331): ok 67 Should be able to call stopBroadcasting without error
I/jxcore-log( 3331): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): setDiscoveryMode: Mode set to BLE_AND_WIFI
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3331): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453831184647.3331
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3331): bind: Binding a new listener
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3331): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3331): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453831184647.3331","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3331): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3331): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3331): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3331): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3331): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3331): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3331): start: OK
I/io.jxcore.node.ConnectionHelper( 3331): start: Using peer discovery mode: BLE_AND_WIFI
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453831184647.3331
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3331): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3331): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3331): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3331): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3331): createAdvertiseData: From: 1453831184647.3331 b6a44ad1-d319-4b3a-815d-8b805a47fb51 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3331): 34:FC:EF:11:AE:67
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3331): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 52, -4, -17, 17, -82, 103]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3331): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3331): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453831184647.3331","ra":"34:FC:EF:11:AE:67"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3331): start: {"pi":"34:FC:EF:11:AE:67","pn":"1453831184647.3331","ra":"34:FC:EF:11:AE:67"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3331): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1453831184647.3331","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): setState: RUNNING_WIFI
I/wpa_supplicant( 1031): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453831184647.3331
,I/io.jxcore.node.ConnectionHelper( 3331): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): setState: RUNNING_BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3331): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 3331): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/jxcore-log( 3331): ok 68 Should be able to call startBroadcasting without error
I/jxcore-log( 3331): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3331): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3331): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3331): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3331): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3331): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3331): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3331): release: 1 listener(s) left
I/wpa_supplicant( 1031): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3331): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): stop: Stopping peer discovery...
I/io.jxcore.node.ConnectionHelper( 3331): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3331): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3331): onServerStopped
D/BluetoothLeScanner( 3331): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): stopBlePeerDiscovery: Stopped
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3331): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3331): Local services cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3331): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3331): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3331): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3331): Service requests cleared successfully
,I/jxcore-log( 3331): ok 69 Should be able to call stopBroadcasting without error
I/jxcore-log( 3331): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): setDiscoveryMode: Mode set to BLE_AND_WIFI
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3331): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453831184678.3331
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3331): bind: Binding a new listener
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3331): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3331): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453831184678.3331","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3331): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3331): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3331): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3331): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3331): setState: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3331): start: OK
I/io.jxcore.node.ConnectionHelper( 3331): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 3331): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453831184678.3331
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3331): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3331): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3331): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3331): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3331): createAdvertiseData: From: 1453831184678.3331 b6a44ad1-d319-4b3a-815d-8b805a47fb51 34:FC:EF:11:AE:67
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3331): 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3331): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 52, -4, -17, 17, -82, 103]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3331): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3331): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453831184678.3331","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3331): start: {"pi":"34:FC:EF:11:AE:67","pn":"1453831184678.3331","ra":"34:FC:EF:11:AE:67"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3331): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1453831184678.3331","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): start: Starting P2P device discovery...
,I/wpa_supplicant( 1031): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): start: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453831184678.3331
I/io.jxcore.node.ConnectionHelper( 3331): start: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): startBlePeerDiscovery: Already running
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): startBlePeerDiscovery: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): setState: RUNNING_BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3331): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): restart: Restarting...
I/jxcore-log( 3331): ok 70 Should be able to call startBroadcasting without error
I/jxcore-log( 3331): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 3331): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3331): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3331): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3331): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3331): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3331): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3331): shutdown
I/wpa_supplicant( 1031): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3331): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3331): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): stop: Stopping peer discovery...
I/io.jxcore.node.ConnectionHelper( 3331): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3331): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3331): onServerStopped
D/BluetoothLeScanner( 3331): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3331): stop: Stopping services
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3331): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3331): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3331): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3331): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): P2P device discovery stopped successfully
I/jxcore-log( 3331): ok 71 Should be able to call stopBroadcasting without error
I/jxcore-log( 3331): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3331): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3331): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453831184707.3331
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3331): bind: Binding a new listener
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3331): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3331): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453831184707.3331","ra":"34:FC:EF:11:AE:67"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3331): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3331): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3331): startListeningForIncomingConnections: Starting...
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3331): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3331): setState: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3331): start: OK
I/io.jxcore.node.ConnectionHelper( 3331): start: Using peer discovery mode: BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3331): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3331): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453831184707.3331
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3331): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3331): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3331): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3331): createAdvertiseData: From: 1453831184707.3331 b6a44ad1-d319-4b3a-815d-8b805a47fb51 34:FC:EF:11:AE:67
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3331): 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3331): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 52, -4, -17, 17, -82, 103]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3331): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3331): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453831184707.3331","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3331): start: {"pi":"34:FC:EF:11:AE:67","pn":"1453831184707.3331","ra":"34:FC:EF:11:AE:67"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3331): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1453831184707.3331","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453831184707.3331
,I/io.jxcore.node.ConnectionHelper( 3331): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): startBlePeerDiscovery: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): setState: RUNNING_BLE_AND_WIFI
I/jxcore-log( 3331): ok 72 Should be able to call startBroadcasting without error
I/jxcore-log( 3331): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 3331): onDiscoveryManagerStateChanged: RUNNING_WIFI
,I/io.jxcore.node.ConnectionHelper( 3331): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 3331): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3331): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3331): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3331): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3331): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3331): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3331): setState: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3331): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3331): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): stop: Stopping peer discovery...
I/io.jxcore.node.ConnectionHelper( 3331): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3331): Local service added successfully
I/wpa_supplicant( 1031): p2p0: P2P: Reject scan trigger since one is already pending
D/BluetoothLeScanner( 3331): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3331): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): onIsWifiPeerDiscoveryStartedChanged: false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): P2P device discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): stopWifiPeerDiscovery: Stopped
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): setState: STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3331): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3331): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): setState: NOT_STARTED,
I/wpa_supplicant( 1031): P2P-FIND-STOPPED 
I/io.jxcore.node.ConnectionHelper( 3331): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 3331): ok 73 Should be able to call stopBroadcasting without error
I/jxcore-log( 3331): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3331): Local services cleared successfully,
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): P2P device discovery stopped successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3331): Service requests cleared successfully
,I/jxcore-log( 3331): # setup
,I/jxcore-log( 3331): 
,I/jxcore-log( 3331): # ThaliEmitter calls startBroadcasting twice with error
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): # teardown
I/jxcore-log( 3331): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): setDiscoveryMode: Mode set to BLE_AND_WIFI
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3331): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453831187743.3331
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3331): bind: Binding a new listener
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3331): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3331): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453831187743.3331","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3331): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3331): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3331): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3331): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3331): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 3331): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3331): start: OK
I/io.jxcore.node.ConnectionHelper( 3331): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453831187743.3331
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3331): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3331): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3331): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3331): createAdvertiseData: From: 1453831187743.3331 b6a44ad1-d319-4b3a-815d-8b805a47fb51 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3331): 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3331): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 52, -4, -17, 17, -82, 103]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3331): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3331): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453831187743.3331","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3331): start: {"pi":"34:FC:EF:11:AE:67","pn":"1453831187743.3331","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3331): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1453831187743.3331","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): start: OK
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): setState: RUNNING_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453831187743.3331
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): startBlePeerDiscovery: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3331): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): setState: RESTARTING
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3331): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 3331): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
,I/wpa_supplicant( 1031): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): setState: RESTARTING
,I/io.jxcore.node.ConnectionHelper( 3331): start: OK
I/jxcore-log( 3331): ok 74 Should be able to call startBroadcasting without error
I/jxcore-log( 3331): 
I/jxcore-log( 3331): ok 75 Cannot call startBroadcasting twice
I/jxcore-log( 3331): 
I/io.jxcore.node.ConnectionHelper( 3331): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3331): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3331): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3331): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3331): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3331): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3331): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3331): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): stop: Stopping peer discovery...
D/BluetoothLeScanner( 3331): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3331): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3331): Local services cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): setState: NOT_INITIALIZED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3331): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3331): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3331): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 3331): onDiscoveryManagerStateChanged: NOT_STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3331): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3331): onServerStopped
,I/jxcore-log( 3331): ok 76 Should be able to call stopBroadcasting without error
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): # setup
I/jxcore-log( 3331): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): Start timer timeout, starting now...
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): start: Cannot start, because not initialized
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): Start timer timeout, starting now...
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): start: Cannot start, because not initialized
,I/jxcore-log( 3331): # ThaliEmitter throws on connection to bad peer
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): # teardown
I/jxcore-log( 3331): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): setDiscoveryMode: Mode set to BLE_AND_WIFI
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3331): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453831190497.3331
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3331): bind: Binding a new listener
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3331): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3331): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453831190497.3331","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3331): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3331): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3331): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3331): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3331): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 3331): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3331): start: OK
I/io.jxcore.node.ConnectionHelper( 3331): start: Using peer discovery mode: BLE_AND_WIFI
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453831190497.3331
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3331): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3331): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3331): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3331): createAdvertiseData: From: 1453831190497.3331 b6a44ad1-d319-4b3a-815d-8b805a47fb51 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3331): 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3331): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 52, -4, -17, 17, -82, 103]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3331): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3331): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453831190497.3331","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3331): start: {"pi":"34:FC:EF:11:AE:67","pn":"1453831190497.3331","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3331): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1453831190497.3331","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): start: OK
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453831190497.3331
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): startBlePeerDiscovery: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3331): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): setState: RESTARTING
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3331): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 3331): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
,I/wpa_supplicant( 1031): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): setState: RESTARTING
,I/io.jxcore.node.ConnectionHelper( 3331): start: OK
I/jxcore-log( 3331): ok 77 Should be able to call startBroadcasting without error
I/jxcore-log( 3331): 
I/io.jxcore.node.ConnectionHelper( 3331): connect: Trying to connect to peer with ID foobar
W/io.jxcore.node.ConnectionHelper( 3331): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
E/io.jxcore.node.ConnectionHelper( 3331): connect: Invalid Bluetooth address: foobar
I/jxcore-log( 3331): ok 78 Should not connect to a bad peer
I/jxcore-log( 3331): 
I/io.jxcore.node.ConnectionHelper( 3331): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3331): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3331): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3331): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3331): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3331): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3331): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 3331): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): stop: Stopping peer discovery...
,D/BluetoothLeScanner( 3331): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3331): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3331): Local services cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): setState: NOT_INITIALIZED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3331): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3331): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3331): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): setState: NOT_STARTED
,I/io.jxcore.node.ConnectionHelper( 3331): onDiscoveryManagerStateChanged: NOT_STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3331): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3331): onServerStopped
,I/jxcore-log( 3331): ok 79 Should be able to call stopBroadcasting without error
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): # setup
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): # ThaliEmitter throws on disconnect to bad peer
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): # teardown
I/jxcore-log( 3331): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): setDiscoveryMode: Mode set to BLE_AND_WIFI
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3331): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453831190872.3331
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3331): bind: Binding a new listener
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3331): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3331): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453831190872.3331","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3331): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3331): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3331): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3331): getBluetoothService() called with no BluetoothManagerCallback
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3331): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 3331): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3331): start: OK
I/io.jxcore.node.ConnectionHelper( 3331): start: Using peer discovery mode: BLE_AND_WIFI
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453831190872.3331
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3331): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3331): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3331): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3331): createAdvertiseData: From: 1453831190872.3331 b6a44ad1-d319-4b3a-815d-8b805a47fb51 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 3331): 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 3331): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, 52, -4, -17, 17, -82, 103]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 3331): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 3331): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"1453831190872.3331","ra":"34:FC:EF:11:AE:67"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3331): start: {"pi":"34:FC:EF:11:AE:67","pn":"1453831190872.3331","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3331): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"1453831190872.3331","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): start: Starting P2P device discovery...
,I/wpa_supplicant( 1031): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): setState: RUNNING_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): start: Peer ID: 34:FC:EF:11:AE:67, peer name: 1453831190872.3331
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): startBlePeerDiscovery: Already running
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): startBlePeerDiscovery: OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): setState: RUNNING_BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3331): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): setState: RESTARTING
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 3331): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 3331): onDiscoveryManagerStateChanged: RUNNING_BLE_AND_WIFI
,I/wpa_supplicant( 1031): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): P2P device discovery stopped successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): setState: RESTARTING
,I/io.jxcore.node.ConnectionHelper( 3331): start: OK
I/jxcore-log( 3331): ok 80 Should be able to call startBroadcasting without error
I/jxcore-log( 3331): 
D/io.jxcore.node.ConnectionHelper( 3331): disconnectOutgoingConnection: Trying to close connection to peer with ID foobar
E/io.jxcore.node.ConnectionHelper( 3331): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID foobar
D/io.jxcore.node.ConnectionHelper( 3331): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3331): disconnectOutgoingConnection: Failed to disconnect (peer ID: foobar), either no such connection or failed to close the connection
I/jxcore-log( 3331): ok 81 Disconnect should fail to a non-existant peer 
I/jxcore-log( 3331): 
I/io.jxcore.node.ConnectionHelper( 3331): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3331): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3331): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3331): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3331): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3331): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3331): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3331): onConnectionManagerStateChanged: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): stop: Stopping peer discovery...
,D/BluetoothLeScanner( 3331): could not find callback wrapper
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): stopBlePeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3331): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3331): Local services cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): setState: NOT_INITIALIZED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3331): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 3331): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3331): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3331): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 3331): onDiscoveryManagerStateChanged: NOT_STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3331): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3331): onServerStopped
,I/jxcore-log( 3331): ok 82 Should be able to call stopBroadcasting without error
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): # setup
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): # #startListeningForAdvertisements should emit wifiPeerAvailabilityChanged after test peer becomes available
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): # teardown
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): ok 83 should be equal
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): # setup
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): # #startUpdateAdvertisingAndListenForIncomingConnections should use different USN after every invocation
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): # teardown
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): ok 84 should not be equal
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): # setup
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): # verify that Thali-specific messages are filtered correctly
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): # teardown
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): ok 85 irrelevant messages should be ignored
I/jxcore-log( 3331): 
I/jxcore-log( 3331): ok 86 relevant messages should not be ignored
I/jxcore-log( 3331): 
I/jxcore-log( 3331): ok 87 messages from this device should be ignored
I/jxcore-log( 3331): 
,I/jxcore-log( 3331): Tests Complete
I/jxcore-log( 3331): 
,I/chromium( 3331): [INFO:CONSOLE(63)] "logCallback ------ Final results ---- ", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3331): Total: 0	Passed: 0	Failed: 0
I/jxcore-log( 3331): 
I/jxcore-log( 3331): Toggling radios to false
I/jxcore-log( 3331): 
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  761): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@2db0de3c mBinding = false
,I/chromium( 3331): [INFO:CONSOLE(63)] "logCallback Total: 0, Passed: 0, Failed: 0", source: file:///android_asset/www/js/thali_main.js (63)
,D/BluetoothManagerService(  761): Message: 2
,D/BluetoothManagerService(  761): Sending off request.
,D/BluetoothAdapterState( 2048): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
,D/BluetoothAdapterProperties( 2048): Setting state to 13
I/BluetoothAdapterState( 2048): Bluetooth adapter state changed: 12-> 13
,D/BluetoothAdapterProperties( 2048): onBluetoothDisable()
I/BluetoothAdapterState( 2048): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,D/BluetoothAdapterProperties( 2048): Scan Mode:20
,D/BluetoothAdapterState( 2048): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,V/BluetoothMapMasInstance( 2048): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 2048): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 2048): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
V/BluetoothMapMasInstance( 2048): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:489)
V/BluetoothMapMasInstance( 2048): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:399)
V/BluetoothMapMasInstance( 2048): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 2048): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 2048): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,E/BtOppRfcommListener( 2048): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,D/btif_config_util( 2048): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 2048): bta_dm_disable BTA_DISABLE_DELAY set to 100 ms
,W/bt-l2cap( 2048): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2048): L2CAP - PSM: 0x0017 not found for deregistration
,D/BluetoothManagerService(  761): Message: 60
D/BluetoothManagerService(  761): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService(  761): Bluetooth State Change Intent: 12 -> 13
,D/BluetoothMapService( 2048): onReceive
D/BluetoothMapService( 2048): STATE_TURNING_OFF
V/BluetoothMapService( 2048): Handler(): got msg=4
D/BluetoothMapService( 2048): MAP Service closeService in
D/BluetoothMapMasInstance( 2048): MAP Service shutdown
V/BluetoothMapService( 2048): MAP Service closeService out
,I/BtOppRfcommListener( 2048): stopping Accept Thread
,I/BtOppRfcommListener( 2048): BluetoothSocket listen thread finished
,D/WifiService(  761): setWifiEnabled: false pid=3331, uid=10270
E/WifiService(  761): Invoking mWifiStateMachine.setWifiEnabled
,I/ActivityManager(  761): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=3748 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/jxcore-log( 3331): Radios toggled
I/jxcore-log( 3331): 
I/jxcore-log( 3331): ****TEST TOOK:  ms ****
I/jxcore-log( 3331): 
I/jxcore-log( 3331): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3331): 
,E/WifiStateMachine(  761): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  761): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
E/native  (  761): do suspend true
,D/CommandListener(  180): Clearing all IP addresses on wlan0
,W/ContextImpl( 3748): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,V/NativeCrypto( 1610): Read error: ssl=0xb3d3ae00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1610): SSL shutdown failed: ssl=0xb3d3ae00: I/O error during system call, Broken pipe
,D/bt_userial( 2048): RX termination
W/bt_userial( 2048): select_read return size <=0:-1, exiting userial_read_thread
D/bt_userial( 2048): Leaving userial_read_thread()
W/bt-btif ( 2048): ag scb idx 1 not allocated
E/bt-btif ( 2048): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 2048): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2048): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2048): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2048): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2048): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2048): L2CAP - PSM: 0x0017 not found for deregistration
D/bt_userial( 2048): userial_close_reader Joined userial reader thread: 0
D/bt_hwcfg( 2048): hw_epilog_process
,I/bt_userial_vendor( 2048): device fd = 53 close
,D/ConnectivityService(  761): reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10008
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): ValidatedState{ when=-1ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): DefaultState{ when=-1ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Checking http://clients3.google.com/generate_204 on "NG7005g"
,I/GKI_LINUX( 2048): gki_task task_id=0 [BTU] terminating
I/GKI_LINUX( 2048): GKI_exit_task 0 done
I/GKI_LINUX( 2048): GKI_shutdown(): task [BTU] terminated
D/BluetoothAdapterState( 2048): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,D/BluetoothAdapterState( 2048): Stopping profile services that were post enabled
,D/HeadsetService( 2048): Received stop request...Stopping profile...
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/BluetoothAdapterService( 2048): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@156d33d
,D/HeadsetStateMachine( 2048): Exit Disconnected: -1
D/ConnectivityService(  761): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  761): NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
I/jxcore-log( 3331): Toggling radios to false
I/jxcore-log( 3331): 
D/BluetoothHeadset( 1170): Proxy object disconnected
,E/WifiConfigStore(  761): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/BluetoothHeadset( 1170): Proxy object disconnected
D/BluetoothHeadset( 1206): Proxy object disconnected
D/A2dpService( 2048): Received stop request...Stopping profile...
D/A2dpStateMachine( 2048): Exit Disconnected: -1
,D/BluetoothAdapterService( 2048): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@156d33d
,E/WifiStateMachine(  761): scanCount==0 - aborting
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  761): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@2db0de3c mBinding = false
D/BluetoothManagerService(  761): Message: 2
D/BluetoothManagerService(  761): Sending off request.
D/BluetoothAdapterState( 2048): CURRENT_STATE=PENDING, MESSAGE = USER_TURN_ON, isTurningOn=false, isTurningOff=true
I/BluetoothAdapterState( 2048): CURRENT_STATE=PENDING: Alreadying turning off bluetooth... Ignoring USER_TURN_OFF...
D/HidService( 2048): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2048): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@156d33d
D/HealthService( 2048): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2048): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@156d33d
D/PanService( 2048): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2048): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@156d33d
D/BtGatt.DebugUtils( 2048): handleDebugAction() action=null
D/BtGatt.GattService( 2048): Received stop request...Stopping profile...
D/BtGatt.GattService( 2048): stop()
D/BtGatt.AdvertiseManager( 2048): advertise clients cleared
D/BluetoothAdapterService( 2048): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@156d33d
D/BluetoothMapService( 2048): Received stop request...Stopping profile...
D/BluetoothMapService( 2048): stop()
D/BluetoothMapEmailAppObserver( 2048): deinitObservers()
D/BluetoothMapEmailAppObserver( 2048): removeReceiver()
D/BluetoothAdapterService( 2048): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@156d33d
D/HeadsetStateMachine( 2048): Unbinding service...
W/BluetoothHeadsetServiceJni( 2048): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 2048): Cleaning up Bluetooth Handsfree callback object
I/GKI_LINUX( 2048): gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 2048): GKI_exit_task 2 done
I/GKI_LINUX( 2048): GKI_shutdown(): task [A2DP-MEDIA] terminated
W/BluetoothHidServiceJni( 2048): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 2048): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 2048): Cleaning up Bluetooth GID callback object
W/BluetoothHealthServiceJni( 2048): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 2048): Cleaning up Bluetooth Health object
W/BluetoothPanServiceJni( 2048): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 2048): Cleaning up Bluetooth PAN callback object
V/BluetoothMapService( 2048): Handler(): got msg=4
D/BluetoothMapService( 2048): MAP Service closeService in
V/BluetoothMapService( 2048): MAP Service closeService out
D/BluetoothAdapterState( 2048): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 2048): Setting state to 10
I/BluetoothAdapterState( 2048): Bluetooth adapter state changed: 13-> 10
D/BluetoothMapService( 2048): cleanup()
D/BluetoothMapService( 2048): MAP Service closeService in
V/BluetoothMapService( 2048): MAP Service closeService out
D/BluetoothManagerService(  761): Message: 60
D/BluetoothManagerService(  761): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService(  761): Broadcasting onBluetoothStateChange(false) to 5 receivers.
I/BluetoothAdapterState( 2048): Entering OffState
D/BluetoothHeadset( 1170): onBluetoothStateChange: up=false
D/BluetoothHeadset(  761): onBluetoothStateChange: up=false
D/BluetoothA2dp(  761): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1206): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1170): onBluetoothStateChange: up=false
,D/BluetoothManagerService(  761): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService(  761): Broadcasting onBluetoothServiceDown() to 8 receivers.
D/BluetoothManagerService(  761): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@2db0de3c mBinding = false
D/WifiNetworkAgent(  761): NetworkAgent: NetworkAgent channel lost
D/BluetoothManagerService(  761): Sending unbind request.
,D/WifiScanningService(  761): SCAN_AVAILABLE : 1
D/RttService(  761): SCAN_AVAILABLE : 1
D/RttService(  761): EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiScanningService(  761): StartedState got{ when=-5ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  761): DefaultState
,D/WifiService(  761): setWifiEnabled: false pid=3331, uid=10270
E/WifiService(  761): Invoking mWifiStateMachine.setWifiEnabled
D/ConnectivityService(  761): notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  898): CM callback handler got msg 524292
D/Nat464Xlat(  761): requiresClat: netType=1, connected=false, hasIPv4Address=true
,D/CSLegacyTypeTracker(  761): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1675): CM callback handler got msg 524292
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Disconnected - quitting
,I/jxcore-log( 3331): Radios toggled
I/jxcore-log( 3331): 
E/native  (  761): do suspend true
,D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/BluetoothManagerService(  761): Bluetooth State Change Intent: 13 -> 10
,D/ConnectivityService(  761): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/ConnectivityService(  761): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,D/BluetoothManagerService(  761): Message: 20
D/BluetoothManagerService(  761): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1acba228:true
,D/TelephonyNetworkFactory( 1206): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/CommandListener(  180): Clearing all IP addresses on wlan0
,D/BluetoothAdapter(  898): 411782902: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter(  898): 411782902: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter(  898): 411782902: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 3748): 347536532: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothManagerService(  761): Message: 30
,D/BluetoothAdapter( 1610): 280290243: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1610): 280290243: getState() :  mService = null. Returning STATE_OFF
,I/GKI_LINUX( 2048): gki_task task_id=1 [BTIF] terminating
,I/GKI_LINUX( 2048): GKI_exit_task 1 done
I/GKI_LINUX( 2048): GKI_shutdown(): task [BTIF] terminated
,I/BluetoothServiceJni( 2048): cleanupNative: return from cleanup
,I/art     ( 2048): System.exit called, status: 0
I/AndroidRuntime( 2048): VM exiting with result code 0, cleanup skipped.
,D/BluetoothManagerService(  761): Message: 30
,D/LocalBluetoothProfileManager( 3748): Adding local MAP profile
,D/BluetoothMap( 3748): Create BluetoothMap proxy object
,D/BluetoothManagerService(  761): Message: 30
D/BluetoothManagerService(  761): Message: 30
,I/ActivityManager(  761): Process com.android.bluetooth (pid 2048) has died
,D/LocalBluetoothProfileManager( 3748): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 3748): finishStartingService: stopping service
,D/WifiService(  761): New client listening to asynchronous messages
,D/AndroidRuntime( 3783): 
D/AndroidRuntime( 3783): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 3783): CheckJNI is OFF
,I/wpa_supplicant( 1031): p2p0: CTRL-EVENT-TERMINATING 
,I/ActivityManager(  761): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=3795 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,I/wpa_supplicant( 1031): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,I/ActivityManager(  761): Killing 2982:com.qualcomm.timeservice/u0a76 (adj 15): empty #17
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): Start timer timeout, starting now...
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 3331): start: Cannot start, because not initialized
,D/AndroidRuntime( 3783): Calling main entry com.android.commands.pm.Pm
,W/PackageSettings(  761): Skipping PackageSetting{3289a5e8 com.example.hello/10278} due to missing metadata
,I/ActivityManager(  761): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  761): Killing 3331:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
,I/WindowState(  761): WIN DEATH: Window{ed5079c u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  761): Client connection lost with reason: 4
,D/Tethering(  761): InitialState.processMessage what=4
I/wpa_supplicant( 1031): wlan0: CTRL-EVENT-TERMINATING 
,E/libprocessgroup(  761): failed to kill 1 processes for processgroup 3331
I/ActivityManager(  761):   Force finishing activity ActivityRecord{1606cf28 u0 com.test.thalitest/.MainActivity t216}
,W/libprocessgroup(  761): failed to open /acct/uid_10076/pid_2982/cgroup.procs: No such file or directory
,W/ActivityManager(  761): Spurious death for ProcessRecord{3625a6b1 3331:com.test.thalitest/u0a270}, curProc for 3331: null
,D/Tethering(  761): sendTetherStateChangedBroadcast 0, 0, 0
,I/OpenGLRenderer(  946): Initialized EGL, version 1.4
,D/OpenGLRenderer(  946): Enabling debug mode 0
,I/LibraryLoader( 1509): Loading chrome directly from within /data/app/com.android.chrome-1/base.apk
,W/Settings( 1941): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActivityManager(  761): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
,W/Settings( 1610): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/art     (  946): Attempt to remove local handle scope entry from IRT, ignoring
,W/ResourcesManager( 3795): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,W/InputMethodManagerService(  761): Got RemoteException sending setActive(false) notification to pid 3331 uid 10270
,I/Keyboard.Facilitator( 1071): onFinishInput()
,D/AdapterServiceConfig( 3795): Adding HeadsetService
D/AdapterServiceConfig( 3795): Adding A2dpService
D/AdapterServiceConfig( 3795): Adding HidService
D/AdapterServiceConfig( 3795): Adding HealthService
D/AdapterServiceConfig( 3795): Adding PanService
D/AdapterServiceConfig( 3795): Adding GattService
D/AdapterServiceConfig( 3795): Adding BluetoothMapService
,I/art     ( 1252): Explicit concurrent mark sweep GC freed 3923(292KB) AllocSpace objects, 1(126KB) LOS objects, 38% free, 25MB/41MB, paused 6.803ms total 29.955ms
,I/InputReader(  761): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 1610): Ignoring removeGeofence because network location is disabled.
I/Keyboard.Facilitator( 1071): resetDictionaries() : en_US
I/ActivityManager(  761): Killing 2559:com.google.android.deskclock/u0a38 (adj 15): empty #17
,I/LibraryLoader( 1509): Time to load native libraries: 129 ms (timestamps 6894-7023)
I/art     ( 1372): Explicit concurrent mark sweep GC freed 13365(945KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 19MB/25MB, paused 376us total 62.995ms
I/LibraryLoader( 1509): Expected native library version number "44.0.2403.133",actual native library version number "44.0.2403.133"
I/chromium( 1509): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,W/art     ( 1509): Attempt to remove local handle scope entry from IRT, ignoring
I/art     ( 1675): Explicit concurrent mark sweep GC freed 11763(563KB) AllocSpace objects, 1(16KB) LOS objects, 25% free, 22MB/30MB, paused 675us total 92.995ms
W/art     ( 1509): Attempt to remove local handle scope entry from IRT, ignoring
,I/Keyboard.Facilitator.DecoderInitializer( 1071): run()
,I/art     (  761): Explicit concurrent mark sweep GC freed 45376(2MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 1.062ms total 77.474ms
,I/Decoder ( 1071): createOrResetDecoder
,D/AuthorizationBluetoothService( 1610): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,W/libprocessgroup(  761): failed to open /acct/uid_10038/pid_2559/cgroup.procs: No such file or directory
I/ConfigService( 1610): onCreate
,W/ContextImpl( 3748): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/DockEventReceiver( 3748): finishStartingService: stopping service
,D/BackupManagerService(  761): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  761): Receieved: android.intent.action.PACKAGE_REMOVED
I/Keyboard.Facilitator.MainLanguageModelLoader( 1071): run()
,D/BluetoothAdapter( 3748): 347536532: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 3748): 347536532: getState() :  mService = null. Returning STATE_OFF
,D/AuthorizationBluetoothService( 1610): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothAdapter( 3748): 347536532: getState() :  mService = null. Returning STATE_OFF
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1071): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1071): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1071): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1071): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1071): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1071): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1071): run() : Loading LM = user
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1071): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1071): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1071): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1071): run()
I/StatsUtilsManager( 1071): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1071): shouldRecordStats() = Too Soon
I/ActivityManager(  761): Start proc com.google.android.keep for broadcast com.google.android.keep/.notification.AlertReceiver: pid=3869 uid=10071 gids={50071, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/TaskPersister(  761): removeObsoleteFile: deleting file=216_task.xml
,I/Launcher( 1252): Deferring update until onResume
,W/ResourcesManager( 1252): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/art     (  761): Explicit concurrent mark sweep GC freed 9432(497KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 1.202ms total 156.459ms
,W/ResourcesManager( 1252): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Launcher( 1252): Deferring update until onResume
,D/AndroidRuntime( 3783): Shutting down VM
,I/ActivityManager(  761): Killing 2271:com.google.android.calendar/u0a31 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10031/pid_2271/cgroup.procs: No such file or directory
,D/BluetoothAdapter( 3748): 347536532: getState() :  mService = null. Returning STATE_OFF
,D/VoicemailCleanupService( 2866): Cleaning up data for package: com.test.thalitest
,I/UpdateIcingCorporaServi( 1372): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,W/Launcher( 1252): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@156d33d new=com.google.android.velvet.VelvetApplication@156d33d
,I/ActivityManager(  761): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3898 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/UpdateIcingCorporaServi( 1372): UpdateCorporaTask done [took 138 ms] updated apps [took 138 ms] 
,W/ContextImpl( 3898): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
,D/PackageBroadcastService( 1675): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/AccountUtils( 1675): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 1675): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1675): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1675): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1675): Module APK com.google.android.play.games already loaded
,E/NetworkScheduler.SchedulerReceiver( 1610): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1610): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/LocationSettingsChecker( 1675): Removing dialog suppression flag for package com.test.thalitest
,E/SQLiteDatabase( 1675): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 1675): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1675): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1675): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1675): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1675): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1675): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1675): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1675): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1675): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1675): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1675): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/SQLiteDatabase( 1675): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 1675): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 1675): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1675): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 1675): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 1675): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1675): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1675): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 1675): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/PhenotypeInitializer( 1675): Could not unregister android package com.test.thalitest
E/PhenotypeInitializer( 1675): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/PhenotypeInitializer( 1675): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/PhenotypeInitializer( 1675): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/PhenotypeInitializer( 1675): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/PhenotypeInitializer( 1675): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/PhenotypeInitializer( 1675): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/PhenotypeInitializer( 1675): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/PhenotypeInitializer( 1675): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/PhenotypeInitializer( 1675): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/PhenotypeInitializer( 1675): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/PhenotypeInitializer( 1675): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/PhenotypeInitializer( 1675): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/PhenotypeInitializer( 1675): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/PhenotypeInitializer( 1675): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/PhenotypeInitializer( 1675): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/PhenotypeInitializer( 1675): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/PhenotypeInitializer( 1675): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/PhenotypeInitializer( 1675): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/PhenotypeInitializer( 1675): 	at android.os.Looper.loop(Looper.java:135)
E/PhenotypeInitializer( 1675): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteLog( 1675): (3850) statement aborts at 151: [DELETE FROM FileContent163 WHERE hash IN WipeoutFileContentHashView AND hash NOT IN ()] disk I/O error
,E/DocListDatabase( 1675): Failed to delete from FileContent163 table
E/DocListDatabase( 1675): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DocListDatabase( 1675): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/DocListDatabase( 1675): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/DocListDatabase( 1675): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/DocListDatabase( 1675): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/DocListDatabase( 1675): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/DocListDatabase( 1675): 	at com.google.android.gms.drive.database.k.a(SourceFile:330)
E/DocListDatabase( 1675): 	at com.google.android.gms.drive.database.f.a(SourceFile:987)
E/DocListDatabase( 1675): 	at com.google.android.gms.drive.b.e.run(SourceFile:74)
E/DocListDatabase( 1675): 	at com.google.android.gms.drive.j.ah.run(SourceFile:51)
E/DocListDatabase( 1675): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DocListDatabase( 1675): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DocListDatabase( 1675): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteDatabase( 1675): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 1675): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1675): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1675): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1675): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1675): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1675): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1675): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1675): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1675): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1675): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1675): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/SQLiteDatabase( 1675): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 1675): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1675): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 1675): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 1675): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 1675): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 1675): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 1675): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1675): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1675): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 1675): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteOpenHelper( 1675): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 1675): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1675): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1675): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1675): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1675): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1675): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1675): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1675): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 1675): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 1675): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1675): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/SQLiteOpenHelper( 1675): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 1675): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 1675): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 1675): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 1675): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteOpenHelper( 1675): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 1675): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 1675): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 1675): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 1675): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteOpenHelper( 1675): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,--------- beginning of crash
E/AndroidRuntime( 1675): FATAL EXCEPTION: pool-7-thread-1
E/AndroidRuntime( 1675): Process: com.google.android.gms, PID: 1675
E/AndroidRuntime( 1675): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1675): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1675): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 1675): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1675): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1675): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 1675): 	at com.google.android.gms.drive.database.k.a(SourceFile:330)
E/AndroidRuntime( 1675): 	at com.google.android.gms.drive.database.f.a(SourceFile:987)
E/AndroidRuntime( 1675): 	at com.google.android.gms.drive.b.e.run(SourceFile:74)
E/AndroidRuntime( 1675): 	at com.google.android.gms.drive.j.ah.run(SourceFile:51)
E/AndroidRuntime( 1675): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 1675): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 1675): 	at java.lang.Thread.run(Thread.java:818)
,W/SQLiteOpenHelper( 1675): Opened metrics.db in read-only mode
D/gH_CompatibleDatabase( 1675): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1675): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,E/SQLiteLog( 1675): (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
,D/gH_CompatibleDatabase( 1675): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,I/Process ( 1675): Sending signal. PID: 1675 SIG: 9
,I/ActivityManager(  761): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3930 uid=10039 gids={50039, 9997} abi=armeabi-v7a
,E/DropBoxManagerService(  761): Can't write: system_app_crash
E/DropBoxManagerService(  761): java.io.FileNotFoundException: /data/system/dropbox/drop96.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  761): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  761): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  761): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  761): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  761): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  761): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12006)
E/DropBoxManagerService(  761): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  761): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  761): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  761): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  761): 	... 5 more
,D/ConnectivityService(  761): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@342269bb)
D/ConnectivityService(  761): releasing NetworkRequest NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  761): RemoteException caught trying to send a callback msg for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/ActivityManager(  761): Process com.google.android.gms (pid 1675) has died
,W/ActivityManager(  761): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 1000ms
,W/ActivityManager(  761): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
W/ActivityManager(  761): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 1000ms
W/ActivityManager(  761): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 10999ms
W/ActivityManager(  761): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 10999ms
W/ActivityManager(  761): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 10999ms
W/ActivityManager(  761): Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 20999ms
W/ActivityManager(  761): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 30999ms
,I/ActivityManager(  761): Killing 3111:com.google.android.gms:car/u0a8 (adj 15): empty #17

```
