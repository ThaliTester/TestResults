#### Test 5615109319b4771_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
I/GAv4    ( 3164): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3164):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3164):   adb logcat -s GAv4
W/GAv4    ( 3164): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3164): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3164): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 3164): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
--------- beginning of system
W/ResourcesManager( 3164): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3164): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/CAR.SERVICE( 3048): mConnectedToCar = false, abort
E/ActivityThread( 3048): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@2a039fce that was originally bound here
E/ActivityThread( 3048): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@2a039fce that was originally bound here
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
E/ActivityThread( 3048): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@d354c01 that was originally bound here
E/ActivityThread( 3048): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@d354c01 that was originally bound here
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
W/ActivityManager(  738): Unbind failed: could not find connection for android.os.BinderProxy@18425dec
D/Finsky  ( 2650): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
V/JNIHelp ( 3164): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/ActivityManager(  738): Killing 2090:com.google.android.deskclock/u0a38 (adj 15): empty #17
W/System  ( 3164): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3164): Installed default security provider GmsCore_OpenSSL
W/libprocessgroup(  738): failed to open /acct/uid_10038/pid_2090/cgroup.procs: No such file or directory
V/GLSActivity( 1608): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 1634): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/Icing   ( 1634): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1634): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/Icing   ( 1634): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
I/ActivityManager(  738): Killing 2616:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
W/libprocessgroup(  738): failed to open /acct/uid_10069/pid_2616/cgroup.procs: No such file or directory
,D/AndroidRuntime( 3236): 
D/AndroidRuntime( 3236): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3236): CheckJNI is OFF
D/AndroidRuntime( 3236): Calling main entry com.android.commands.am.Am
I/ActivityManager(  738): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  738): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3257 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3236): Shutting down VM
V/ActivityManager(  738): Display changed displayId=0
I/WebViewFactory( 3257): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3257): Time to load native libraries: 2 ms (timestamps 9792-9794)
I/LibraryLoader( 3257): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3257): Binding Chromium to main looper Looper (main, tid 1) {2afef641}
I/LibraryLoader( 3257): Expected native library version number "",actual native library version number ""
I/chromium( 3257): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3257): Initializing chromium process, singleProcess=true
W/art     ( 3257): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3257): ApplicationContext is null in ApplicationStatus
W/chromium( 3257): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3257): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3257): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3257): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  738): Message: 20
D/BluetoothManagerService(  738): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@36bbf987:true
,W/art     ( 3257): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3257): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3257): CordovaWebView is running on device made by: LGE
,W/art     ( 3257): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3257): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3257): Render dirty regions requested: true
,D/Atlas   ( 3257): Validating map...
,W/chromium( 3257): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3257): Initialized EGL, version 1.4
D/OpenGLRenderer( 3257): Enabling debug mode 0
,I/Keyboard.Facilitator( 1103): onFinishInput()
,W/IInputConnectionWrapper( 3257): showStatusIcon on inactive InputConnection
,I/ActivityManager(  738): Displayed com.test.thalitest/.MainActivity: +449ms (total +58s863ms)
,W/BindingManager( 3257): Cannot call determinedVisibility() - never saw a connection for the pid: 3257
,D/JsMessageQueue( 3257): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3257): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257332480
D/JX-Cordova( 3257): jxcore cordova android initializing
,W/jxcore-log( 3257): Initializing JXcore engine
W/jxcore-log( 3257): JXcore engine is ready
,W/jxcore-log( 3257): Starting JXcore engine
,W/.test.thalitest( 3257): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[6372]" dev="sockfs" ino=6372 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3257): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 3257): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6481]" dev="sockfs" ino=6481 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3257): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[19709]" dev="sockfs" ino=19709 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3257): Platform android
W/jxcore-log( 3257): 
,W/jxcore-log( 3257): Process ARCH arm
W/jxcore-log( 3257): 
,I/jxcore-log( 3257): JXcore Cordova bridge is ready!
I/jxcore-log( 3257): 
W/jxcore-log( 3257): JXcore engine is started
,I/chromium( 3257): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/ActivityManager(  738): Killing 2562:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,I/jxcore-log( 3257): Toggling radios to true
I/jxcore-log( 3257): 
,D/BluetoothAdapter( 3257): enable(): BT is already enabled..!
,D/WifiService(  738): New client listening to asynchronous messages
,D/WifiService(  738): setWifiEnabled: true pid=3257, uid=10270
E/WifiService(  738): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3257): Radios toggled
I/jxcore-log( 3257): 
I/jxcore-log( 3257): My device name is: LGE-Nexus 5
I/jxcore-log( 3257): 
,I/wpa_supplicant(  991): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,E/WifiStateMachine(  738): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  738): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/native  (  738): do suspend true
,D/CommandListener(  181): Clearing all IP addresses on wlan0
,W/libprocessgroup(  738): failed to open /acct/uid_10045/pid_2562/cgroup.procs: No such file or directory
,V/NativeCrypto( 1608): Read error: ssl=0xafe85e00: I/O error during system call, Connection timed out
,D/ConnectivityService(  738): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  738): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,V/NativeCrypto( 1608): SSL shutdown failed: ssl=0xafe85e00: I/O error during system call, Broken pipe
,E/WifiConfigStore(  738): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiStateMachine(  738): Start Disconnecting Watchdog 1
,I/wpa_supplicant(  991): wlan0: CTRL-EVENT-SCAN-STARTED 
,E/native  (  738): do suspend true
,D/ConnectivityService(  738): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  738): ValidatedState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  738): DefaultState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  738): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  738): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  738): Checking http://clients3.google.com/generate_204 on <unknown ssid>
D/ConnectivityService(  738): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/Nat464Xlat(  738): requiresClat: netType=1, connected=false, hasIPv4Address=true
,D/CSLegacyTypeTracker(  738): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  738): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  738): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  738): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/CommandListener(  181): Clearing all IP addresses on wlan0
,D/ConnectivityManager.CallbackHandler(  900): CM callback handler got msg 524292
D/TelephonyNetworkFactory( 1289): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  738): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  738): EvaluatingState{ when=-8ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  738): DefaultState{ when=-8ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  738): Disconnected - quitting
D/ConnectivityManager.CallbackHandler( 1634): CM callback handler got msg 524292
,D/WifiNetworkAgent(  738): NetworkAgent: NetworkAgent channel lost
,I/wpa_supplicant(  991): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,I/wpa_supplicant(  991): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant(  991): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant(  991): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  738): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  738): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  738): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  738): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  181): Setting iface cfg
,E/WifiStateMachine(  738): Start Dhcp Watchdog 2
,E/native  (  738): do suspend false
,E/WifiStateMachine(  738): scanCount==0 - aborting
,I/dhcpcd  ( 3338): version 5.5.6 starting
,E/dhcpcd  ( 3338): get_duid: Read-only file system
,I/dhcpcd  ( 3338): wlan0: rebinding lease of 192.168.1.114
,I/jxcore-log( 3257): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3257): 
,I/jxcore-log( 3257): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 3257): 
,I/jxcore-log( 3257): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 3257): 
,I/jxcore-log( 3257): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 3257): 
,I/jxcore-log( 3257): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 3257): 
,I/jxcore-log( 3257): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 3257): 
,I/jxcore-log( 3257): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3257): 
,D/ConnectivityService(  738): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  738): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  738): MasterInitialState.processMessage what=3
,D/Tethering(  738): MasterInitialState.processMessage what=3
,I/dhcpcd  ( 3338): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,V/MusicLeanback( 2774): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/jxcore-log( 3257): Test app app.js loaded
I/jxcore-log( 3257): 
,I/SystemUpdateService( 1634): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,I/chromium( 3257): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/SystemUpdateService( 1634): onCreate
,D/SystemUpdateService( 1634): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/dhcpcd  ( 3338): wlan0: leased 192.168.1.114 for 86400 seconds
,I/SystemUpdateService( 1634): active receiver: enabled
,I/iu.Environment( 1634): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
I/iu.UploadsManager( 1634): num queued entries: 0
I/iu.UploadsManager( 1634): num updated entries: 0
,I/SystemUpdateService( 1634): showing system update notification
,I/iu.SyncManager( 1634): NEXT; no task
,I/Babel   ( 1941): connection state changed from CONNECTED to DISCONNECTED
I/ValidateNoPeople(  738): skipping global notification
,V/SystemUpdateService( 1634): retry (wakeup: false) in 3599980 ms
,I/ActivityManager(  738): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3362 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/GpsLocationProvider(  738): No APN found to select.
,D/SystemUpdateService( 1634): onDestroy
,E/GpsLocationProvider(  738): No APN found to select.
,E/native  (  738): do suspend true
,D/ConnectivityService(  738): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  738): Adding iface wlan0 to network 101
,E/WifiStateMachine(  738): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  738): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  738): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/ConnectivityService(  738): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  738): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  738): Setting Dns servers for network 101 to [/192.168.1.1]
,D/Nat464Xlat(  738): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  738): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  738): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  738): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  738):    accepting network in place of null
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  738): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  738): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  738): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  738): Checking http://clients3.google.com/generate_204 on "NG7005g"
,I/GAv4    ( 3362): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3362):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3362):   adb logcat -s GAv4
,D/CSLegacyTypeTracker(  738): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  738): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  738): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::5255:27ff:fef0:fd0b/64,192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  738): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler(  900): CM callback handler got msg 524290
D/ConnectivityManager.CallbackHandler( 1634): CM callback handler got msg 524290
,W/GAv4    ( 3362): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3362): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3362): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  738): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Sun, 17 Jan 2016 15:33:24 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1453044804368], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1453044804345]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  738): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  738): Validated
D/ConnectivityService(  738): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  738): rematching NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  738): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  738): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityManager.CallbackHandler(  900): CM callback handler got msg 524290
,D/ConnectivityService(  738): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1634): CM callback handler got msg 524290
D/TelephonyNetworkFactory( 1289): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/WebViewFactory( 3362): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3362): Time to load native libraries: 1 ms (timestamps 6116-6117)
,I/LibraryLoader( 3362): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3362): Binding Chromium to main looper Looper (main, tid 1) {30079b0b}
I/LibraryLoader( 3362): Expected native library version number "",actual native library version number ""
I/chromium( 3362): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3362): Initializing chromium process, singleProcess=true
,W/art     ( 3362): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3362): ApplicationContext is null in ApplicationStatus
,W/chromium( 3362): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3362): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 3362): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3362): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/AudioManagerAndroid( 3362): Requires BLUETOOTH permission
,I/NSApplication( 3362): Starting up...
,I/ActivityManager(  738): Killing 2750:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/libprocessgroup(  738): failed to open /acct/uid_10003/pid_2750/cgroup.procs: No such file or directory
,V/MusicLeanback( 2774): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1634): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1634): onCreate
,D/SystemUpdateService( 1634): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/iu.Environment( 1634): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/iu.UploadsManager( 1634): num queued entries: 0
,I/iu.UploadsManager( 1634): num updated entries: 0
I/iu.SyncManager( 1634): NEXT; no task
,I/SystemUpdateService( 1634): active receiver: enabled
,I/SystemUpdateService( 1634): showing system update notification
,I/ValidateNoPeople(  738): skipping global notification
,V/SystemUpdateService( 1634): retry (wakeup: false) in 3599980 ms
,D/SystemUpdateService( 1634): onDestroy
,I/Babel   ( 1941): connection state changed from DISCONNECTED to CONNECTED
,D/ConnectivityService(  738): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,D/ConnectivityService(  738): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  738): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2774): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2774): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1634): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1634): onCreate
,D/SystemUpdateService( 1634): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1634): active receiver: enabled
,I/SystemUpdateService( 1634): showing system update notification
,E/GpsLocationProvider(  738): No APN found to select.
,I/ValidateNoPeople(  738): skipping global notification
,V/SystemUpdateService( 1634): retry (wakeup: false) in 3599981 ms
,D/SystemUpdateService( 1634): onDestroy
,D/Finsky  ( 2650): [255] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2650): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/art     (  738): Explicit concurrent mark sweep GC freed 45123(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 27MB/41MB, paused 1.126ms total 103.848ms
,I/ActivityManager(  738): Start proc com.google.android.youtube for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator: pid=3518 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/GLSActivity( 1608): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 3518): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3518): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 3518): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 3518): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 3518): Installed default security provider GmsCore_OpenSSL
,I/dex2oat ( 3551): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads-2009103748.jar --oat-fd=24 --oat-location=/data/data/com.google.android.youtube/cache/ads-2009103748.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,E/YouTube MDX( 3518): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,I/dex2oat ( 3551): dex2oat took 35.513ms (threads: 4)
,W/InstanceID/Rpc( 3518): Found 10008
,I/ActivityManager(  738): Killing 2725:com.android.settings/1000 (adj 15): empty #17
,D/WifiService(  738): Client connection lost with reason: 4
,W/libprocessgroup(  738): failed to open /acct/uid_1000/pid_2725/cgroup.procs: No such file or directory
,I/VacuumService( 1608): Vacuum at: now=1453044822707 tag=VacuumService
,I/Keyboard.Facilitator.LanguageModelFlusher( 1103): run()
I/Keyboard.Facilitator( 1103): flushDynamicLanguageModels()
,I/ClearcutLoggerApiImpl( 1608): disconnect managed GoogleApiClient
,I/jxcore-log( 3257): --= Surplus to requirements =--
I/jxcore-log( 3257): 
I/jxcore-log( 3257): ****TEST TOOK:  ms ****
I/jxcore-log( 3257): 
I/jxcore-log( 3257): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3257): 
,D/AndroidRuntime( 3651): 
D/AndroidRuntime( 3651): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 3651): CheckJNI is OFF
,D/AndroidRuntime( 3651): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  738): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  738): Killing 3257:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
,I/WindowState(  738): WIN DEATH: Window{29b05277 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  738): Client connection lost with reason: 4
,W/PackageSettings(  738): Skipping PackageSetting{fccfec5 com.example.hello/10278} due to missing metadata
,I/ActivityManager(  738):   Force finishing activity ActivityRecord{30528b33 u0 com.test.thalitest/.MainActivity t216}
,W/ActivityManager(  738): Spurious death for ProcessRecord{1f0115d2 3257:com.test.thalitest/u0a270}, curProc for 3257: null
,I/ActivityManager(  738): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
,I/art     ( 1320): Explicit concurrent mark sweep GC freed 4006(296KB) AllocSpace objects, 1(126KB) LOS objects, 38% free, 25MB/41MB, paused 578us total 16.429ms
,I/Keyboard.Facilitator( 1103): resetDictionaries() : en_US
W/GeofencerStateMachine( 1608): Ignoring removeGeofence because network location is disabled.
I/InputReader(  738): Reconfiguring input devices.  changes=0x00000010
,I/Keyboard.Facilitator.DecoderInitializer( 1103): run()
D/VoicemailCleanupService( 1379): Cleaning up data for package: com.test.thalitest
,I/Adreno-EGL(  945): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
I/Decoder ( 1103): createOrResetDecoder
I/OpenGLRenderer(  945): Initialized EGL, version 1.4
,D/OpenGLRenderer(  945): Enabling debug mode 0
,I/art     (  738): Explicit concurrent mark sweep GC freed 18944(1145KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 2.119ms total 93.505ms
I/art     (  738): WaitForGcToComplete blocked for 47.548ms for cause Explicit
,I/art     ( 1634): Explicit concurrent mark sweep GC freed 10722(519KB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 22MB/30MB, paused 502us total 133.533ms
,I/art     ( 1391): Explicit concurrent mark sweep GC freed 15809(1095KB) AllocSpace objects, 1(39KB) LOS objects, 24% free, 18MB/25MB, paused 352us total 117.997ms
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1103): run()
,I/UpdateIcingCorporaServi( 1391): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1103): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1103): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1103): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1103): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1103): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1103): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1103): run() : Loading LM = user
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1103): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1103): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1103): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1103): run()
I/StatsUtilsManager( 1103): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1103): shouldRecordStats() = Too Soon
,W/Launcher( 1320): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@34dcd7e6 new=com.google.android.velvet.VelvetApplication@34dcd7e6
,I/ActivityManager(  738): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3694 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,D/BackupManagerService(  738): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  738): Receieved: android.intent.action.PACKAGE_REMOVED
,W/InputMethodManagerService(  738): Focus gain on non-focused client com.android.internal.view.IInputMethodClient$Stub$Proxy@3952da1d (uid=10034 pid=945)
,I/art     (  738): Explicit concurrent mark sweep GC freed 2718(133KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 27MB/41MB, paused 1.956ms total 121.453ms
,D/TaskPersister(  738): removeObsoleteFile: deleting file=216_task.xml
,W/InputMethodManagerService(  738): Got RemoteException sending setActive(false) notification to pid 3257 uid 10270
,I/Keyboard.Facilitator( 1103): onFinishInput()
,I/UpdateIcingCorporaServi( 1391): UpdateCorporaTask done [took 115 ms] updated apps [took 115 ms] 
,W/ContextImpl( 3694): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
,D/PackageBroadcastService( 1634): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1634): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 1634): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1634): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1634): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1634): Module APK com.google.android.play.games already loaded
,E/NetworkScheduler.SchedulerReceiver( 1608): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1608): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/LocationSettingsChecker( 1634): Removing dialog suppression flag for package com.test.thalitest
,I/ActivityManager(  738): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3723 uid=10039 gids={50039, 9997} abi=armeabi-v7a
,D/gH_CompatibleDatabase( 1634): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,D/gH_CompatibleDatabase( 1634): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 1634): 0 metrics were deleted when clearing package com.test.thalitest.
,D/gH_CompatibleDatabase( 1634): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/gH_CompatibleDatabase( 1634): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1634): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/gH_CompatibleDatabase( 1634): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/AndroidRuntime( 3651): Shutting down VM
,I/Launcher( 1320): Deferring update until onResume
,D/gH_CompatibleDatabase( 1634): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
,D/gH_CompatibleDatabase( 1634): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 1634): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1634): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1634): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
,D/gH_CompatibleDatabase( 1634): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,W/ResourcesManager( 1320): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/BaseAppContext( 1634): Using Auth Proxy for data requests.
,I/GMPM-SVC( 1634): App measurement is starting up, version: 8489
I/GMPM-SVC( 1634): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,W/BaseAppContext( 1634): Using Auth Proxy for data requests.
,W/ResourcesManager( 1320): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Launcher( 1320): Deferring update until onResume
,I/Icing   ( 1634): doRemovePackageData com.test.thalitest
,I/ActivityManager(  738): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3748 uid=10007 gids={50007, 9997, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  738): Killing 2586:com.google.android.gm/u0a70 (adj 15): empty #17
,W/libprocessgroup(  738): failed to open /acct/uid_10070/pid_2586/cgroup.procs: No such file or directory
,I/ActivityManager(  738): Killing 2022:com.google.android.calendar/u0a31 (adj 15): empty #17
,D/ExternalStorage( 3748): After updating volumes, found 1 active roots
,W/libprocessgroup(  738): failed to open /acct/uid_10031/pid_2022/cgroup.procs: No such file or directory
,W/ResourcesManager( 3164): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 3164): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/Documents( 3723): Update found 7 roots in 168ms
,D/Documents( 3723): Update found 7 roots in 119ms

```
