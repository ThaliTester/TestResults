#### Test 549702617cfd775_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
D/Finsky  ( 2678): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
I/ActivityManager(  759): Killing 2498:com.google.android.youtube/u0a80 (adj 15): empty #17
W/ResourcesManager( 3172): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3172): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/libprocessgroup(  759): failed to open /acct/uid_10080/pid_2498/cgroup.procs: No such file or directory
V/JNIHelp ( 3172): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/System  ( 3172): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3172): Installed default security provider GmsCore_OpenSSL
V/GLSActivity( 1603): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 1639): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/Icing   ( 1639): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1639): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/Icing   ( 1639): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
D/CAR.SERVICE( 3046): mConnectedToCar = false, abort
E/ActivityThread( 3046): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@35a6d9a2 that was originally bound here
E/ActivityThread( 3046): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@35a6d9a2 that was originally bound here
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
E/ActivityThread( 3046): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@8092925 that was originally bound here
E/ActivityThread( 3046): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@8092925 that was originally bound here
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
W/ActivityManager(  759): Unbind failed: could not find connection for android.os.BinderProxy@132a3ec2
I/ActivityManager(  759): Killing 2103:com.google.android.deskclock/u0a38 (adj 15): empty #17
W/libprocessgroup(  759): failed to open /acct/uid_10038/pid_2103/cgroup.procs: No such file or directory
,D/AndroidRuntime( 3231): 
D/AndroidRuntime( 3231): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3231): CheckJNI is OFF
D/AndroidRuntime( 3231): Calling main entry com.android.commands.am.Am
I/ActivityManager(  759): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  759): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3252 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3231): Shutting down VM
I/art     (  194): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 391us total 18.663ms
I/art     (  194): Explicit concurrent mark sweep GC freed 8(256B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 362us total 16.951ms
V/ActivityManager(  759): Display changed displayId=0
I/art     (  194): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 163us total 12.869ms
I/WebViewFactory( 3252): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3252): Time to load native libraries: 2 ms (timestamps 8431-8433)
I/LibraryLoader( 3252): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3252): Binding Chromium to main looper Looper (main, tid 1) {1f830f65}
,I/LibraryLoader( 3252): Expected native library version number "",actual native library version number ""
I/chromium( 3252): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3252): Initializing chromium process, singleProcess=true
W/art     ( 3252): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3252): ApplicationContext is null in ApplicationStatus
,W/chromium( 3252): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3252): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3252): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3252): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  759): Message: 20
D/BluetoothManagerService(  759): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@14464127:true
,W/art     ( 3252): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3252): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3252): CordovaWebView is running on device made by: LGE
,W/art     ( 3252): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3252): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3252): Render dirty regions requested: true
,D/Atlas   ( 3252): Validating map...
,W/chromium( 3252): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3252): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3252): Enabling debug mode 0
,W/IInputConnectionWrapper( 3252): showStatusIcon on inactive InputConnection
,I/ActivityManager(  759): Displayed com.test.thalitest/.MainActivity: +453ms (total +56s612ms)
,W/BindingManager( 3252): Cannot call determinedVisibility() - never saw a connection for the pid: 3252
,D/JsMessageQueue( 3252): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3252): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257332480
,D/JX-Cordova( 3252): jxcore cordova android initializing
,W/jxcore-log( 3252): Initializing JXcore engine
W/jxcore-log( 3252): JXcore engine is ready
,W/jxcore-log( 3252): Starting JXcore engine
,W/.test.thalitest( 3252): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[8538]" dev="sockfs" ino=8538 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3252): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 3252): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[9609]" dev="sockfs" ino=9609 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3252): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[18709]" dev="sockfs" ino=18709 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3252): Platform android
W/jxcore-log( 3252): 
W/jxcore-log( 3252): Process ARCH arm
W/jxcore-log( 3252): 
,I/jxcore-log( 3252): JXcore Cordova bridge is ready!
I/jxcore-log( 3252): 
W/jxcore-log( 3252): JXcore engine is started
I/Choreographer( 3252): Skipped 112 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3252): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3252): Toggling radios to true
I/jxcore-log( 3252): 
,D/BluetoothAdapter( 3252): enable(): BT is already enabled..!
,D/WifiService(  759): New client listening to asynchronous messages
,D/WifiService(  759): setWifiEnabled: true pid=3252, uid=10270
,E/WifiService(  759): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3252): Radios toggled
I/jxcore-log( 3252): 
I/jxcore-log( 3252): My device name is: LGE-Nexus 5
I/jxcore-log( 3252): 
,I/wpa_supplicant(  984): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  759): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  759): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
E/native  (  759): do suspend true
,D/CommandListener(  178): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1603): Read error: ssl=0xb4130e00: I/O error during system call, Connection timed out
V/NativeCrypto( 1603): SSL shutdown failed: ssl=0xb4130e00: I/O error during system call, Broken pipe
D/ConnectivityService(  759): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): ValidatedState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): DefaultState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
E/WifiConfigStore(  759): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  759): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  759): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
E/WifiStateMachine(  759): Start Disconnecting Watchdog 1
I/wpa_supplicant(  984): wlan0: CTRL-EVENT-SCAN-STARTED 
E/native  (  759): do suspend true
,D/CommandListener(  178): Clearing all IP addresses on wlan0
,D/ConnectivityService(  759): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler(  897): CM callback handler got msg 524292
D/ConnectivityManager.CallbackHandler( 1639): CM callback handler got msg 524292
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Disconnected - quitting
,D/Nat464Xlat(  759): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  759): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  759): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  759): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  759): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory( 1255): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WifiNetworkAgent(  759): NetworkAgent: NetworkAgent channel lost
,I/wpa_supplicant(  984): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant(  984): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant(  984): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant(  984): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  759): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  759): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  759): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  759): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  178): Setting iface cfg
,E/WifiStateMachine(  759): Start Dhcp Watchdog 2
,E/native  (  759): do suspend false
,E/WifiStateMachine(  759): scanCount==0 - aborting
,I/dhcpcd  ( 3354): version 5.5.6 starting
E/dhcpcd  ( 3354): get_duid: Read-only file system
,I/dhcpcd  ( 3354): wlan0: rebinding lease of 192.168.1.114
,V/GLSActivity( 1603): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1603): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/NetworkUtils( 1395): OkHttp exception
W/EventLoggerService( 1395): Unable to send logs Error code: 262146
,I/dhcpcd  ( 3354): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3354): wlan0: leased 192.168.1.114 for 86400 seconds
,E/native  (  759): do suspend true
,D/ConnectivityService(  759): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  759): Adding iface wlan0 to network 101
,E/WifiStateMachine(  759): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  759): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  759): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  759): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  759): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  759): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  759): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  759): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  759): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/ConnectivityService(  759): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  759):    accepting network in place of null
,D/CSLegacyTypeTracker(  759): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  759): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  759): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService(  759): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  897): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1639): CM callback handler got msg 524290
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 11 Jan 2016 14:01:24 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452520884726], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452520884701]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Validated
,D/ConnectivityService(  759): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  759): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  759): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  759): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler(  897): CM callback handler got msg 524290
D/ConnectivityService(  759): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 1639): CM callback handler got msg 524290
D/TelephonyNetworkFactory( 1255): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/Nat464Xlat(  759): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  759): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  897): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 1639): CM callback handler got msg 524295
,D/ConnectivityService(  759): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  759): MasterInitialState.processMessage what=3
,D/ConnectivityService(  759): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  759): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2787): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2787): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 2787): type=WIFI subType= reason=null isConnected=true
,I/SystemUpdateService( 1639): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1639): onCreate
,D/SystemUpdateService( 1639): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1639): active receiver: enabled
,I/SystemUpdateService( 1639): showing system update notification
,I/ActivityManager(  759): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3417 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/GpsLocationProvider(  759): No APN found to select.
,I/ValidateNoPeople(  759): skipping global notification
,E/GpsLocationProvider(  759): No APN found to select.
,V/SystemUpdateService( 1639): retry (wakeup: false) in 3599909 ms
,D/SystemUpdateService( 1639): onDestroy
,I/GAv4    ( 3417): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3417):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3417):   adb logcat -s GAv4
,W/GAv4    ( 3417): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3417): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3417): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 3417): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3417): Time to load native libraries: 2 ms (timestamps 4516-4518)
,I/LibraryLoader( 3417): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3417): Binding Chromium to main looper Looper (main, tid 1) {1884028f}
,I/LibraryLoader( 3417): Expected native library version number "",actual native library version number ""
,I/chromium( 3417): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3417): Initializing chromium process, singleProcess=true
W/art     ( 3417): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3417): ApplicationContext is null in ApplicationStatus
,W/chromium( 3417): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3417): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3417): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3417): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/NSApplication( 3417): Starting up...
,W/AudioManagerAndroid( 3417): Requires BLUETOOTH permission
,D/ConnectivityService(  759): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/ActivityManager(  759): Killing 2605:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,W/libprocessgroup(  759): failed to open /acct/uid_10045/pid_2605/cgroup.procs: No such file or directory
,V/MusicLeanback( 2787): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1639): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1639): onCreate
,D/SystemUpdateService( 1639): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1639): active receiver: enabled
,I/SystemUpdateService( 1639): showing system update notification
,I/ValidateNoPeople(  759): skipping global notification
,V/SystemUpdateService( 1639): retry (wakeup: false) in 3599961 ms
,D/SystemUpdateService( 1639): onDestroy
,D/ConnectivityService(  759): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  759): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2787): type=WIFI subType= reason=null isConnected=true
V/MusicLeanback( 2787): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1639): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
D/SystemUpdateService( 1639): onCreate
D/SystemUpdateService( 1639): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,E/GpsLocationProvider(  759): No APN found to select.
,I/SystemUpdateService( 1639): active receiver: enabled
,I/SystemUpdateService( 1639): showing system update notification
,I/ValidateNoPeople(  759): skipping global notification
,V/SystemUpdateService( 1639): retry (wakeup: false) in 3599984 ms
,D/SystemUpdateService( 1639): onDestroy
,I/art     (  759): Explicit concurrent mark sweep GC freed 46085(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 27MB/41MB, paused 972us total 66.961ms
,I/jxcore-log( 3252): Test app app.js loaded
I/jxcore-log( 3252): 
,I/Choreographer( 3252): Skipped 393 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3252): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/Finsky  ( 2678): [255] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2678): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/GoogleURLConnFactory( 1603): Using platform SSLCertificateSocketFactory
,V/GLSActivity( 1603): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/PhenotypeConfigurator( 1603): Scheduling Phenotype every 14400 seconds, with flex of 1800 seconds
,W/PhenotypeConfigurator( 1603): Server returned 404
,I/VacuumService( 1603): Vacuum at: now=1452520904620 tag=VacuumService
,I/ClearcutLoggerApiImpl( 1603): disconnect managed GoogleApiClient
,I/PhenotypeConfigurator( 1603): Scheduling Phenotype for one-off execution 3544 seconds from now (1452520999517)
,D/GetConfigurationSnapshotOperation( 1603): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1603): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1603): Using platform SSLCertificateSocketFactory
,V/GLSActivity( 1603): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1603): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 3252): --= Surplus to requirements =--
I/jxcore-log( 3252): 
I/jxcore-log( 3252): ****TEST TOOK:  ms ****
I/jxcore-log( 3252): 
I/jxcore-log( 3252): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3252): 
,D/AndroidRuntime( 3598): 
D/AndroidRuntime( 3598): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 3598): CheckJNI is OFF
,D/AndroidRuntime( 3598): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  759): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  759): Killing 3252:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
,D/WifiService(  759): Client connection lost with reason: 4
,I/WindowState(  759): WIN DEATH: Window{36abc217 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/PackageSettings(  759): Skipping PackageSetting{3c0e4da9 com.example.hello/10278} due to missing metadata
,I/ActivityManager(  759):   Force finishing activity ActivityRecord{14b48810 u0 com.test.thalitest/.MainActivity t214}
,W/ActivityManager(  759): Spurious death for ProcessRecord{32d2519a 3252:com.test.thalitest/u0a270}, curProc for 3252: null
,I/ActivityManager(  759): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
,I/ActivityManager(  759):   Force finishing activity ActivityRecord{14b48810 u0 com.test.thalitest/.MainActivity t214 f}
W/ActivityManager(  759): Duplicate finish request for ActivityRecord{14b48810 u0 com.test.thalitest/.MainActivity t214 f}
,I/art     ( 1297): Explicit concurrent mark sweep GC freed 3957(294KB) AllocSpace objects, 1(126KB) LOS objects, 23% free, 25MB/33MB, paused 225us total 30.391ms
I/InputReader(  759): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 1603): Ignoring removeGeofence because network location is disabled.
I/Keyboard.Facilitator( 1107): resetDictionaries() : en_US
,I/Keyboard.Facilitator.DecoderInitializer( 1107): run()
,I/Decoder ( 1107): createOrResetDecoder
,I/Adreno-EGL(  942): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
I/OpenGLRenderer(  942): Initialized EGL, version 1.4
,D/OpenGLRenderer(  942): Enabling debug mode 0
,I/art     ( 1639): Explicit concurrent mark sweep GC freed 1888(75KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 22MB/29MB, paused 458us total 105.737ms
I/art     ( 1395): Explicit concurrent mark sweep GC freed 1940(125KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 19MB/25MB, paused 311us total 59.777ms
,D/VoicemailCleanupService( 1365): Cleaning up data for package: com.test.thalitest
,I/art     (  759): Explicit concurrent mark sweep GC freed 25046(1350KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 938us total 102.298ms
I/art     (  759): WaitForGcToComplete blocked for 15.423ms for cause Explicit
,I/UpdateIcingCorporaServi( 1395): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,W/Launcher( 1297): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@269c843a new=com.google.android.velvet.VelvetApplication@269c843a
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1107): run()
,I/ActivityManager(  759): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3637 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,D/BackupManagerService(  759): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  759): Receieved: android.intent.action.PACKAGE_REMOVED
,D/TaskPersister(  759): removeObsoleteFile: deleting file=214_task.xml
,W/InputMethodManagerService(  759): Focus gain on non-focused client com.android.internal.view.IInputMethodClient$Stub$Proxy@3e55054e (uid=10034 pid=942)
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1107): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1107): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1107): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1107): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1107): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1107): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1107): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1107): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1107): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1107): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1107): run()
I/StatsUtilsManager( 1107): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1107): shouldRecordStats() = Too Soon
,W/ContextImpl( 3637): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
,I/UpdateIcingCorporaServi( 1395): UpdateCorporaTask done [took 126 ms] updated apps [took 126 ms] 
,I/art     (  759): Explicit concurrent mark sweep GC freed 6785(358KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 1.351ms total 157.280ms
,D/PackageBroadcastService( 1639): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1639): Clearing selected account for com.test.thalitest
,I/ActivityManager(  759): Killing 2763:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,D/AndroidRuntime( 3598): Shutting down VM
,D/ChimeraCfgMgr( 1639): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1639): Module APK com.google.android.play.games already loaded
W/libprocessgroup(  759): failed to open /acct/uid_10003/pid_2763/cgroup.procs: No such file or directory
,I/LocationSettingsChecker( 1639): Removing dialog suppression flag for package com.test.thalitest
I/Launcher( 1297): Deferring update until onResume
,D/ChimeraCfgMgr( 1639): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1639): Module APK com.google.android.play.games already loaded
,E/NetworkScheduler.SchedulerReceiver( 1603): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1603): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,W/ResourcesManager( 1297): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/gH_CompatibleDatabase( 1639): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1639): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1639): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1639): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/gH_CompatibleDatabase( 1639): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1639): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1639): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/gH_CompatibleDatabase( 1639): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1639): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 1639): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,D/gH_CompatibleDatabase( 1639): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
,D/gH_CompatibleDatabase( 1639): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1639): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,W/ResourcesManager( 1297): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Launcher( 1297): Deferring update until onResume
,I/ActivityManager(  759): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3670 uid=10039 gids={50039, 9997} abi=armeabi-v7a
,I/GMPM-SVC( 1639): App measurement is starting up, version: 8489
,I/GMPM-SVC( 1639): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,W/BaseAppContext( 1639): Using Auth Proxy for data requests.
,W/BaseAppContext( 1639): Using Auth Proxy for data requests.
,I/Icing   ( 1639): doRemovePackageData com.test.thalitest
,I/ActivityManager(  759): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3694 uid=10007 gids={50007, 9997, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  759): Killing 2739:com.android.settings/1000 (adj 15): empty #17
,D/WifiService(  759): Client connection lost with reason: 4
,W/libprocessgroup(  759): failed to open /acct/uid_1000/pid_2739/cgroup.procs: No such file or directory
,I/ActivityManager(  759): Killing 2623:com.google.android.gm/u0a70 (adj 15): empty #17
,W/libprocessgroup(  759): failed to open /acct/uid_10070/pid_2623/cgroup.procs: No such file or directory
,D/ExternalStorage( 3694): After updating volumes, found 1 active roots
,W/ResourcesManager( 3172): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 3172): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.

```
